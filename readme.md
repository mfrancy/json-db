# Student ID – Student Data

Repositório utilizado como uma base de dados simples em JSON para o projeto **Student ID – Carteirinha Digital do Aluno**.

Este repositório armazena as informações básicas dos estudantes utilizadas pela aplicação, como nome e foto.

## Objetivo

O objetivo deste repositório é fornecer uma fonte de dados simples para a aplicação Student ID durante os estudos de desenvolvimento front-end.

A estrutura permite simular o consumo de uma API ou banco de dados, utilizando arquivos JSON como fonte de informações.


## Estrutura dos dados

Cada estudante é identificado pelo seu **RA (Registro Acadêmico)**, que funciona como a chave principal do objeto.

Exemplo:

```json
{
  "824214769": {
    "senha": "100602",
    "nome": "Mariana Lopes Francisco",
    "curso": "Análise e Desenvolvimento de Sistemas",
    "status": "ativo",
    "matricula": "07/2025",
    "foto": "https://mfrancy.github.io/json-db/assets/824214769.jpg"
  }
}