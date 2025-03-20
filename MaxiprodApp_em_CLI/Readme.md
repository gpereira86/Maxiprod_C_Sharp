# Controle de Gastos Residenciais

## Descrição

Este sistema permite o cadastro de pessoas e transações financeiras, com o objetivo de controlar despesas e receitas de cada pessoa cadastrada. O sistema fornece funcionalidades para consultar o total de despesas, receitas e saldo de cada pessoa, além de exibir transações e possibilitar a exclusão de registros.

## Funcionalidades

1. **Cadastro de Pessoas**: Permite o cadastro de uma nova pessoa, informando nome e idade.
2. **Cadastro de Transações**: Cadastra transações financeiras associadas a uma pessoa, podendo ser despesas ou receitas.
3. **Consulta de Totais**: Exibe o total de receitas, despesas e saldo por pessoa, além de um total geral.
4. **Consulta de Pessoas e suas Transações**: Exibe as transações financeiras de cada pessoa cadastrada.
5. **Listagem de Pessoas**: Exibe a lista de todas as pessoas cadastradas no sistema.
6. **Exclusão de Pessoa**: Permite excluir uma pessoa do sistema e todas as suas transações associadas.

## Tecnologias Utilizadas

- C#
- .NET Framework

## Como Rodar o Projeto

1. Clone este repositório para o seu computador.
2. Abra o projeto no Visual Studio ou outro IDE compatível com C#.
3. Compile e execute o programa.

## Instruções de Uso

1. **Cadastro de Pessoas**:
   - Escolha a opção `1` para cadastrar uma nova pessoa.
   - Informe o nome e a idade da pessoa. A idade deve ser um número inteiro válido.

2. **Cadastro de Transações**:
   - Escolha a opção `2` para cadastrar uma transação.
   - Escolha o ID da pessoa associada à transação.
   - Informe o tipo da transação (`despesa` ou `receita`).
   - Forneça a descrição e o valor da transação.

3. **Consultar Totais**:
   - Escolha a opção `3` para visualizar o total de receitas, despesas e saldo de cada pessoa, além do total geral.

4. **Consultar Pessoas e suas Transações**:
   - Escolha a opção `4` para listar todas as transações de cada pessoa cadastrada.

5. **Listar Pessoas**:
   - Escolha a opção `5` para visualizar a lista de pessoas cadastradas no sistema.

6. **Excluir Pessoa**:
   - Escolha a opção `6` para excluir uma pessoa e suas transações associadas.

7. **Sair**:
   - Escolha a opção `7` para encerrar o programa.

## Exemplo de Uso

Ao iniciar o sistema, você verá um menu de opções. O programa continuará executando até que você escolha a opção `7` para sair.

Exemplo de interação:

```shell
Controle de Gastos Residenciais

1. Cadastro de Pessoas
2. Cadastro de Transações
3.Consultar Totais
4.Consultar Pessoas e suas Transações
5.Pessoas Cadastradas
6.Excluir Pessoa
7.Sair 

Escolha uma opção: 1
 
Cadastro de Pessoa
Nome: Glauco
Idade: 28

>>> Pessoa cadastrada com sucesso! <<<
Pressione qualquer tecla para voltar.

```

### Enjoy!