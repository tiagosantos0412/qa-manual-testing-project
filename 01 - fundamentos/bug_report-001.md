# 🐞 Bug Report

## BUG-001 - Sistema permite preço negativo

Descrição:
O sistema permite cadastrar produtos com valor negativo, o que viola a regra de negócio.
evidência disponível em /evidencias

Passos para reproduzir:

1. Acessar tela de cadastro de produto
2. Inserir valor -100 no campo preço
3. Clicar em salvar

Resultado esperado:
Sistema deve impedir cadastro e exibir mensagem de erro

Resultado obtido:
Produto cadastrado com valor negativo

Severidade: Alta
Prioridade: Alta
Status: Aberto
