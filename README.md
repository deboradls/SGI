# 💰 Sistema de Gerenciamento de Investimentos 📈
Este projeto foi desenvolvido como parte da disciplina **Laboratório de Programação**, ministrada pelo professor **Luiz Fernando**, no curso de **Ciência da Computação**.

## 📑 Sumário
- [💰 Sistema de Gerenciamento de Investimentos 📈](#-sistema-de-gerenciamento-de-investimentos-)
  - [📑 Sumário](#-sumário)
  - [📝 Descrição](#-descrição)
  - [⚙️ Funcionalidades](#️-funcionalidades)
  - [📁 Estrutura do Projeto](#-estrutura-do-projeto)
  - [🛠️ Como Compilar](#️-como-compilar)
  - [🚀 Como Executar](#-como-executar)
  - [📚 Dependências](#-dependências)
  - [👩🏻‍💻 Créditos](#-créditos)

## 📝 Descrição
O Sistema de Gerenciamento de Investimentos permite ao usuário gerenciar informações financeiras relacionadas a diferentes tipos de investimentos. O sistema é capaz de calcular impostos com base no tempo de aplicação, calcular valores brutos e líquidos com base em juros compostos e organizar os investimentos por tipo e data de aplicação.

## ⚙️ Funcionalidades
- **Cálculo de Impostos**: Baseado no tempo de aplicação.
- **Cálculo de Juros Compostos**: Atualiza o valor bruto do investimento.
- **Gerenciamento de Investimentos**: Inserir, editar e deletar investimentos.
- **Organização por Tipo e Data**: Agrupamento de investimentos por tipo e ordenação por data de aplicação.
- **Visualização de Totais**: Exibição de valor bruto e valor líquido total dos investimentos.

## 📁 Estrutura do Projeto
O projeto é dividido nos seguintes arquivos:
- **calculo_investimento.h/c**: Contém as funções responsáveis pelo cálculo de juros e impostos.
- **gerenciamento_investimento.h/c**: Contém as funções para manipulação de dados dos investimentos, além de funções utilitárias para conversão e ordenação.
- **main.c**: Arquivo principal que interage com o usuário, permitindo o cadastro e gerenciamento dos investimentos.
- **Makefile**: Facilita a compilação do projeto.

## 🛠️ Como Compilar
Para compilar o projeto, use um compilador C como o `gcc`. Siga os seguintes passos:

```bash
gcc -g main.c calculo_investimento.c gerenciamento_investimento.c -o investimento
```
ou
```bash
make
```
Os comandos acima irão gerar o executável investimento.

## 🚀 Como Executar
Após a compilação, execute o programa com o comando:
```bash
./investimento
```

## 📚 Dependências
- stdio.h
- stdlib.h
- string.h
- time.h
- math.h
  
## 👩🏻‍💻 Créditos
Este projeto foi desenvolvido por Débora Lima no decorrer do semestre 2024.1.
