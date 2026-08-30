# 🚗 Análise do Mercado Automotivo Brasileiro

Análise exploratória do mercado brasileiro de automóveis entre **julho de 2025 e junho de 2026**, com foco na evolução dos emplacamentos, desempenho de marcas e modelos e crescimento dos veículos eletrificados.

## 🎯 Objetivo

O objetivo deste projeto é analisar o comportamento do mercado automotivo brasileiro e responder perguntas como:

- Quais marcas e modelos tiveram maior presença entre os veículos mais emplacados?
- Como os emplacamentos evoluíram ao longo dos 12 meses?
- Quais modelos ganharam ou perderam força?
- Como evoluiu a participação dos veículos eletrificados?
- O crescimento foi maior entre veículos híbridos ou 100% elétricos?

## 📊 Dados

Os dados utilizados foram obtidos a partir dos informativos mensais de emplacamentos da **FENABRAVE**.

Período analisado:

**Julho/2025 a Junho/2026**

O projeto utiliza duas bases:

- `automoveis_fenabrave_jul2025_jun2026.csv`
- `eletrificados_fenabrave_jul2025_jun2026.csv`

A primeira contém os **50 modelos de automóveis mais emplacados em cada mês**.

A segunda contém informações mensais sobre o mercado de veículos **híbridos e 100% elétricos**.

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- Git/GitHub

## 🔎 Etapas da análise

O projeto foi desenvolvido seguindo as seguintes etapas:

1. Importação e exploração dos dados
2. Verificação da qualidade da base
3. Tratamento e padronização
4. Análise da evolução mensal dos emplacamentos
5. Ranking das principais marcas
6. Análise dos modelos mais emplacados
7. Análise de crescimento e queda dos modelos
8. Evolução dos veículos híbridos e elétricos
9. Análise da participação dos eletrificados no mercado
10. Identificação dos principais insights

## ⚡ Principais resultados

Entre julho de 2025 e junho de 2026:

- Os veículos eletrificados cresceram aproximadamente **114,60%**
- Os híbridos cresceram **80,75%**
- Os veículos 100% elétricos cresceram **202,29%**
- A participação dos eletrificados passou de **13,73% para 25,17%**
- Isso representa um ganho de **11,44 pontos percentuais**

O maior avanço mensal da participação dos eletrificados ocorreu em **dezembro de 2025**, com aumento de **4,46 pontos percentuais**.

Os resultados mostram que os eletrificados não cresceram apenas em volume: também aumentaram sua participação no mercado de automóveis durante o período analisado.

## 📈 Análises realizadas

O notebook apresenta visualizações e análises de:

- evolução mensal dos emplacamentos;
- ranking de marcas;
- participação das marcas dentro do Top 50;
- ranking de modelos;
- posição média dos modelos;
- presença no Top 5 e Top 10;
- modelos que ganharam e perderam posições;
- evolução de híbridos e elétricos;
- participação dos eletrificados;
- comparação entre crescimento do mercado e dos eletrificados.

## ⚠️ Limitações

A análise de marcas e modelos utiliza os **50 automóveis mais emplacados de cada mês**.

Por isso, as participações calculadas a partir dessa base representam a participação dentro da amostra Top 50 e **não devem ser interpretadas como market share oficial das fabricantes**.

A análise de eletrificação utiliza dados agregados e, portanto, não identifica quais modelos ou fabricantes eletrificados foram responsáveis pelo crescimento observado.

## 📁 Estrutura do projeto

```text
analisar-mercado-automotivo/
│
├── README.md
├── AnaliseMercadoAutomotivo.ipynb
│
└── dados/
    ├── automoveis_fenabrave_jul2025_jun2026.csv
    └── eletrificados_fenabrave_jul2025_jun2026.csv
