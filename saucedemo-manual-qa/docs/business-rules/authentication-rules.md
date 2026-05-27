# Regras de Negócio — Autenticação

## Objetivo

Garantir que apenas usuários válidos e autenticados consigam acessar a plataforma SauceDemo.

---

# Escopo

Este documento descreve as regras de negócio relacionadas ao fluxo de autenticação da aplicação.

Módulo:
- Login
- Validação de credenciais
- Segurança básica da autenticação

---

# Regras de Negócio

## RN-001 — Login válido

O sistema deve permitir acesso apenas a usuários autenticados com credenciais válidas.

---

## RN-002 — Bloqueio de login inválido

O sistema deve impedir o acesso quando username ou password forem inválidos.

---

## RN-003 — Campos obrigatórios

Os campos username e password são obrigatórios para autenticação.

---

## RN-004 — Redirecionamento pós-login

Após login bem-sucedido, o usuário deve ser redirecionado para a página de produtos.

---

## RN-005 — Mensagem de erro

O sistema deve exibir mensagem de erro clara em caso de falha na autenticação.

---

## RN-025 — Máscara da senha

O campo password deve mascarar os caracteres digitados.

### Observação
RN-025 adicionada posteriormente após revisão de segurança da autenticação.

---

# Riscos Identificados

- Usuário acessar sistema sem autenticação
- Exposição da senha em texto puro
- Falha de validação de campos obrigatórios
- Mensagens de erro inconsistentes
- Redirecionamento incorreto após login

---

# Critérios de Qualidade

- Segurança da autenticação
- Clareza das mensagens de erro
- Validação obrigatória de campos
- Navegação correta do fluxo de login

---

# Versionamento

| Versão | Data | Descrição |
|---|---|---|
| 1.0 | 21/05/2026 | Criação inicial das regras de autenticação |
| 1.1 | 21/05/2026 | Inclusão da RN-025 referente à máscara de senha |