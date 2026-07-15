# 🌍 World Energy Consumption — Análise Exploratória de Dados

Projeto final da disciplina de Análise Exploratória de Dados (AED) — UNIFEI.

## 📖 Sobre o projeto

Análise exploratória completa sobre o dataset **World Energy Consumption**, da Our World in Data, investigando como o poder econômico dos países (PIB per capita) se relaciona com a adoção de energias renováveis ao redor do mundo.

## 🎯 Objetivo

Entender, através de análise univariada, bivariada e multivariada, se países mais ricos avançam mais rápido na transição energética — e como esse padrão varia entre continentes.

## 🗂️ Dataset

- **Fonte:** [Our World in Data](https://ourworldindata.org/) — World Energy Consumption
- **Escopo:** indicadores de consumo de energia e PIB per capita por país/continente

## 🔍 Metodologia

- Análise univariada (distribuições, tendências centrais)
- Análise bivariada (PIB per capita × adoção de renováveis)
- Análise multivariada, com segmentação por continente
- Enriquecimento dos dados com `pycountry_convert` (mapeamento país → continente)
- Refinamento visual dos gráficos com `adjustText` para evitar sobreposição de rótulos

## 🛠️ Ferramentas

`Python` · `Google Colab` · `pandas` · `matplotlib` / `seaborn` · `pycountry_convert` · `adjustText`

## 📊 Entregáveis

- Notebook completo de EDA (Google Colab)
- Documento técnico de verificação
- Relatório executivo de duas páginas, em português, voltado a público não técnico

## 🚀 Como executar

1. Abra o notebook `.ipynb` no Google Colab ou Jupyter
2. Instale as dependências:
   ```bash
   pip install pandas matplotlib seaborn pycountry_convert adjustText
   ```
3. Execute as células em ordem — a primeira seção carrega e trata o dataset

## 📌 Principais achados

> Preencha aqui com a conclusão central do seu relatório executivo (ex: relação entre PIB per capita e adoção de renováveis por continente).

---

Projeto acadêmico desenvolvido para a disciplina de AED — UNIFEI.
