# 🦠 Análise de Casos de COVID-19 no Brasil – 2025 - Atualizado até 18/04/2025

Este projeto tem como objetivo analisar os dados de COVID-19 no Brasil, com foco nos **novos casos** e **óbitos** por **região geográfica**, utilizando visualizações interativas para facilitar a interpretação dos dados.

## 📊 Dados utilizados

Os dados foram extraídos de fontes oficiais e correspondem à **semana epidemiológica de 2025**, contendo:

- População por região
- Casos novos e acumulados
- Óbitos novos e acumulados
- Incidência e taxa de mortalidade por 100 mil habitantes

## 🌍 Visualização

Foi criado um **mapa interativo** das regiões do Brasil com destaque para os óbitos novos na semana:

➡️ [Clique aqui para ver o mapa interativo](outputs/mapa_obitos_covid_2025.html)

## 🧪 Tecnologias utilizadas

- Python 3.10+
- Pandas
- Folium
- GeoJSON
- Jupyter Notebook

## 📁 Estrutura

- `data/`: contém os dados utilizados
- `notebooks/`: notebooks de análise e geração de visualizações
- `outputs/`: resultados prontos para visualização
- `requirements.txt`: dependências do projeto

## 🚀 Como executar

```bash
git clone https://github.com/marceloBilbyIA/covid19BR2025.git
cd covid19BR2025
pip install -r requirements.txt
jupyter notebook
