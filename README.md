# Análise Estatística - Preços de Imóveis na Califórnia

## Descrição do Projeto

Este repositório contém a análise estatística desenvolvida para a disciplina **TAD0022 - Estatística Aplicada**, do curso de Análise e Desenvolvimento de Sistemas da Escola Agrícola de Jundiaí (UFRN).

[cite_start]O projeto consiste na análise de uma base de dados sobre os preços de imóveis na Califórnia[cite: 4], com o objetivo de explorar os dados, identificar os fatores que influenciam o valor mediano dos imóveis e desenvolver um modelo preditivo. [cite_start]A análise segue um roteiro estruturado que inclui a verificação e tratamento dos dados [cite: 19, 21][cite_start], análise de distribuições [cite: 23][cite_start], avaliação de correlação [cite: 25][cite_start], elaboração de testes de hipóteses [cite: 27][cite_start], comparação de médias com ANOVA [cite: 29] [cite_start]e o desenvolvimento de um modelo de regressão[cite: 30].

## Estrutura do Repositório

O projeto está organizado da seguinte forma:
```
├── Analise_Estatistica_Imoveis.ipynb
├── relatorio/
│   └── Relatorio_Final.pdf
└── README.md
```
* **`Analise_Estatistica_Imoveis.ipynb`**: Notebook Jupyter contendo todo o código Python, as análises, os testes estatísticos e a geração dos gráficos.
* [cite_start]**`relatorio/`**: Pasta que contém o relatório final do projeto em formato PDF, redigido segundo as normas da ABNT[cite: 8].
* **`README.md`**: Este arquivo, com a descrição e instruções para o projeto.

## Como Executar o Projeto

Para replicar a análise, é necessário ter o **Anaconda** ou o **Miniconda** instalado no seu sistema.

### 1. Preparação do Ambiente

Abra o **Anaconda Prompt** e execute os seguintes comandos para criar um ambiente virtual limpo e instalar todas as dependências necessárias.

**a. Crie o ambiente (chamado "estatistica"):**
```bash
conda create --name estatistica python=3.9
b. Ative o novo ambiente:
```
Bash

conda activate estatistica
c. Instale todas as bibliotecas de uma vez:

Bash
```
conda install notebook pandas matplotlib seaborn scikit-learn scipy

```
2. Execução do Notebook
Com o ambiente estatistica ainda ativo no seu terminal:

a. Navegue até a pasta raiz deste projeto:

Bash
```
cd caminho/para/a/pasta/do/projeto
```
b. Inicie o Jupyter Notebook:

Bash
```
jupyter notebook
```
Isso abrirá uma aba no seu navegador. Basta clicar no arquivo Analise_Estatistica_Imoveis.ipynb para abri-lo e executar as células.

Autor
Alfredo Henrique Silveira Bezerra dos Santos

## Apresentação em Vídeo
Uma apresentação em vídeo completa, guiando por toda a análise e resultados do projeto, está disponível no YouTube.

[Clique aqui para assistir à apresentação no YouTube](https://www.youtube.com/watch?v=VnC0YGGu2O0)

Autores



---
