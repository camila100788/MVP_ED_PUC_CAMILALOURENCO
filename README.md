# MVP_ED_PUC_CAMILALOURENCO
Repositório do MVP de Engenharia de Dados PUC de Camila Lourenço

# Análise de Preços de Combustíveis - ANP 2025

## Visão Geral

Este trabalho tem como objetivo realizar uma análise preliminar de viabilidade para a abertura de um novo posto de gasolina. O foco principal está na rentabilidade do empreendimento, não abrangendo variáveis adicionais como aspectos criminológicos, carga tributária, custos de franquia ou cálculos de break-even usando dados abertos da ANP (Agência Nacional do Petróleo, Gás Natural e Biocombustíveis).  

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

•	Qual estado apresenta maior rentabilidade e qual bairro mais contribui para esse resultado?
•	Quais bandeiras de postos apresentam maior lucro total e margem média?
•	Quais produtos possuem maior margem de lucro em relação ao preço médio de revenda? 
•	Quais postos ou produtos tiveram os maiores aumentos percentuais de preços recentemente?
•	Quais produtos e postos apresentam margem negativa, indicando possíveis áreas de atenção?


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


