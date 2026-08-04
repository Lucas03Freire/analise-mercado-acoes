## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte da minha formação em Análise de Dados na EBAC (Escola Britânica de Artes Criativas e Tecnologia), com o objetivo de aplicar conceitos de Análise Exploratória de Dados (EDA) utilizando Google Sheets. A partir de uma base de dados contendo operações de compra e venda de ações, desenvolvi análises estatísticas, tabelas dinâmicas, visualizações gráficas e uma classificação automática do perfil dos investidores utilizando funções do Google Sheets.

O foco do projeto foi transformar dados brutos em informações relevantes, simulando uma análise inicial que poderia apoiar a tomada de decisão em um ambiente financeiro.

## 🎯 Objetivos
- Organizar uma base de dados de operações do mercado de ações.
- Aplicar técnicas de estatística descritiva.
- Criar análises utilizando tabelas dinâmicas.
- Desenvolver visualizações para facilitar a interpretação dos dados.
- Utilizar funções do Google Sheets para automatizar análises.
- Classificar clientes conforme seu perfil de negociação.

## 📁 Base de Dados

A base utilizada neste projeto contém informações de operações de compra e venda de ações realizadas por clientes fictícios, incluindo:

- Código do cliente
- Nome
- E-mail
- Tipo de operação
- Ticker
- Valor da operação
- Data
  
## 🛠 Ferramentas e Técnicas Aplicadas

- **Google Sheets**

- **Estatística Descritiva**
  - Soma
  - Média
  - Máximo
  - Mínimo
  - Contagem

- **Funções do Google Sheets**
  - COUNTIF
  - SUMIF
  - AVERAGEIF
  - IFS

- **Tabelas Dinâmicas**
  - Resumo de dados por cliente e ticker.

- **Visualização de Dados**
  - Gráficos de linhas e barras horizontais.

## 📂 Estrutura do Projeto
Organizei o repositório da seguinte forma:

- **dados/**
  - `operacoes_mercado_acoes.csv` — Base de dados utilizada nas análises.

- **planilha/**
  - `Analise_Mercado_Acoes.xlsx` — Planilha contendo todas as análises, fórmulas, tabelas dinâmicas e gráficos.

- **imagens/**
  - `01_estatistica.png`
  - `02_tendencia_temporal.png`
  - `03_compra_venda_acao.png`
  - `04_cliente_compra_venda.png`
  - `05_perfil_cliente.png`

- **README.md**
  - Documentação do projeto.
  
## 📊 Etapas da Análise
### 1. Base de Dados
#### Base de dados contendo o histórico de operações de compra e venda realizadas pelos clientes.

Informações disponíveis:
- Código do cliente
- Nome
- E-mail
- Operação (Compra ou Venda)
- Ticker
- Valor da operação
- Data da operação
  
### 2. Estatística Descritiva
#### Resumo estatístico contendo:

- Quantidade de operações
- Soma dos valores das operações
- Média dos valores
- Maior operação
- Menor operação

Além disso, realizei uma contagem das operações por ticker.

### 3. Tendência Temporal
#### Análise da quantidade de operações realizadas ao longo do tempo, permitindo visualizar períodos de maior movimentação.

Recursos utilizados:
- Tabela dinâmica
- Gráfico de linhas

### 4. Compra e Venda por Ticker
#### Identificação dos 10 tickers com maior volume financeiro movimentado.

Recursos utilizados:
- Tabela dinâmica
- Soma dos valores negociados
- Gráfico de barras horizontais

### 5. Clientes com Maior Volume Financeiro
#### Identificação dos 10 clientes com maior volume financeiro movimentado, considerando o total negociado em operações de compra e venda.

Recursos utilizados:
- Tabela dinâmica
- Soma dos valores das operações
- Gráfico de barras horizontais

### 6. Perfil do Cliente
#### Desenvolvi uma análise interativa que permite selecionar um cliente por meio de uma lista suspensa, atualizando automaticamente os indicadores e a classificação do perfil do investidor. A classificação foi realizada utilizando a função IFS, de acordo com a quantidade de operações realizadas.

Automaticamente são exibidos:
- Total de operações
- Volume financeiro movimentado
- Valor médio das operações
- Perfil do investidor

## 📸 Visualização de Dados
O projeto contém capturas de tela das principais análises realizadas:

- Estatística Descritiva
- Tendência Temporal
- Compra e Venda por Ticker
- Clientes por Volume Financeiro
- Perfil do Cliente

## 💡 Competências Desenvolvidas
Este projeto permitiu desenvolver competências em:

- Organização e estruturação de bases de dados.
- Estatística descritiva.
- Construção de tabelas dinâmicas.
- Criação de visualizações para apoiar a interpretação dos dados.
- Documentação de projetos para portfólio.
- Boas práticas de organização e apresentação de análises.

## ✔️ Conclusão da Análise

O desenvolvimento deste projeto me permitiu aplicar, na prática, conceitos fundamentais de Análise Exploratória de Dados (EDA) utilizando o Google Sheets. A partir de uma base de operações do mercado de ações, organizei os dados, gerei estatísticas descritivas, construí tabelas dinâmicas e desenvolvi visualizações que facilitaram a interpretação das informações.

Além da análise dos dados, utilizei funções nativas do Google Sheets para automatizar cálculos e classificar o perfil dos clientes, demonstrando como recursos do Google Sheets podem ser aplicados na construção de análises organizadas, consistentes e de fácil interpretação.

Este trabalho representa o primeiro projeto do meu portfólio em Análise de Dados e marca o início da aplicação prática dos conhecimentos adquiridos durante minha formação. Ele estabelece uma base sólida para o desenvolvimento de projetos futuros utilizando SQL, Python e Power BI, permitindo ampliar a complexidade das análises e explorar novas ferramentas e tecnologias.
