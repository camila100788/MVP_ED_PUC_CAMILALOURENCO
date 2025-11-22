# MVP_ED_PUC_CAMILALOURENCO
Repositório do MVP de Engenharia de Dados PUC de Camila Lourenço

# Análise de Preços de Combustíveis - ANP 2025

## Visão Geral

Este projeto realiza uma análise de preços e rentabilidade de combustíveis usando dados abertos da ANP (Agência Nacional do Petróleo, Gás Natural e Biocombustíveis).  

O pipeline inclui:

- Download automático do arquivo ZIP da ANP
- Extração e leitura do CSV
- Normalização de colunas e tratamento de dados
- Conversão de valores monetários
- Criação de DataFrames Spark e tabelas dimensionais (Tempo, Produto, Posto)
- Criação da tabela fato de preços
- Consultas para análise de rentabilidade e margem
- Visualização com matplotlib e seaborn

O código foi desenvolvido e testado no Databricks Free Edition.

---

## Principais análises

1. Postos mais rentáveis
2. Estados e bairros mais lucrativos
3. Lucro por bandeira
4. Produtos com melhor margem
5. Produtos/Postos com margem negativa
6. Produtos com aumento de preço recente

---

## Estrutura do Código

- `analise_anp.py` — Script principal com todo o ETL e análises
- Bibliotecas utilizadas:
  - Pandas: manipulação inicial do CSV
  - PySpark: criação de dimensões e fato
  - Matplotlib e Seaborn: visualização

---

## Como Rodar

### Pré-requisitos

- Python 3.8+ (ou ambiente Databricks)
- Java 8+ (necessário para PySpark)
- Dependências Python:


