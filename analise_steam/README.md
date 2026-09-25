# Ciência de Dados e Jogos Digitais: Explorando o Steam Games Dataset

**Análise Exploratória de Dados (EDA)** do conjunto de jogos da Steam, com foco em compreender os dados antes da etapa de Machine Learning.

## Objetivos

Investigar:

- quantidade e estrutura dos jogos;
- preços e comercialização;
- estimativa de proprietários e alcance;
- Peak CCU;
- avaliações de jogadores;
- idiomas e áudio completo;
- sistemas operacionais;
- tempo de jogo e atividade recente;
- desenvolvedores e publishers;
- gêneros, categorias e tags;
- relações entre variáveis numéricas.

Arquivo: `steam_games_eda.ipynb`

**Machine Learning:**

1. **Regressão:** prever o preço de um jogo;
2. **Classificação:** classificar o alcance estimado em faixas.

Arquivo: `ml_prever_preco_alcance.ipynb`

## Origem dos dados

Os dados originais são do **Steam Games Dataset**, de **FronkonGames**, disponibilizado no Hugging Face:

`https://huggingface.co/datasets/FronkonGames/steam-games-dataset`

O dataset original informa que os dados foram obtidos a partir da API da Steam e do Steam Spy.

## Unidade de análise

Cada linha representa um **jogo**, e não um usuário, uma venda ou uma sessão de jogo.

## Fluxo

**Dados → compreensão → preparação → EDA → feature engineering → insights → Machine Learning**
