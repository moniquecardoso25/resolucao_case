# CPI Data API

## Objetivo
- Este projeto obtém os dados via API das Séries da Inflação dos EUA (CPI) através da BLS (Bureau of Labor Statistics) no site: https://www.bls.gov/.
- O case faz parte de um processo de seleção para uma vaga de estágio em ciência de dados. O objetivo é demonstrar habilidades com APIs e na manipulação e visualização de dados, utilizando Python e suas bibliotecas, assim como o FastAPI.

## Funcionalidades
- Extração de dados: via API;
- Carregamento de Dados: Os dados do CPI são carregados a partir de um arquivo CSV e armazenados num DataFrame Pandas;
- Variação Percentual: Cálculo da variação percentual dos índices ano a ano;
- Visualização de Dados: Geração de gráficos interativos utilizando as bibliotecas Plotly e Matplotlib;
- FastAPI: A aplicação FastAPI fornece um endpoint para acessar os dados carregados.


## Estrutura do Projeto
main.py: Contém a implementação da API FastAPI.
cpi_data.csv: Arquivo CSV com os dados do CPI utilizados.
requirements.txt: Lista de dependências do projeto.
