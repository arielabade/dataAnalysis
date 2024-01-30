# Guerra da Ucrânia: Estatísticas de Perdas do Exército Russo

## Introdução/Justificativa

Atualmente, a guerra entre Ucrânia e Rússia é o principal conflito mundial ativo, iniciada pela Rússia em 24 de fevereiro de 2022. A Ucrânia busca independência da Rússia desde 1991, mas conflitos persistem, agravados pela anexação da Crimeia e a política agressiva russa.

## Objetivo

Este relatório visa avaliar, de forma gráfica, os esforços da Rússia para anexar partes do território ucraniano. Utilizamos um dataset de perdas do exército russo, incluindo óbitos, prisioneiros, aviões, helicópteros, tanques e outros dados do Ministério de Defesa da Ucrânia.

## Materiais e Metodologia

- **Fonte de Dados:** Kaggle.
- **Ferramentas:** Google Collaboratory, Python (NumPy, Pandas, Matplotlib, Seaborn, Statsmodels).
- **Formato de Dados:** CSV.
- **Limpeza e Processamento:** Remoção de colunas irrelevantes, substituição de valores nulos por 0.
- **Análise Exploratória:** Identificação de padrões e anomalias.

## Análise Exploratória

- **Dados Gerais:**
  - Colunas: 21
  - Linhas: 675

- **Limpeza de Dados:**
  - Remoção de colunas desnecessárias.
  - Substituição de NaN por 0 em colunas específicas.

## Análise Tabular

- **Métricas Descritivas:**
  - Média, Desvio Padrão, Quartis.

- **Artilharia por Categoria:**
  - Terrestre, Naval, Aeronáutica.

## Análise Gráfica

- **Matriz de Correlação:**
  - Relações entre variáveis ao longo do tempo.

- **Principais Resultados:**
  - Maior foco em artilharia terrestre.
  - Uso significativo de drones.
  - Aumento nas defesas antiaéreas.

## Conclusões

- Rússia prioriza artilharia terrestre.
- Número alto de drones indica apoio em solo.
- Estabilização no uso de aeronaves.
- Mais de 350.000 soldados russos mortos (02/2022 - 12/2023).

## Apêndice

**Acrônimos:**
- POW: Prisioneiro de Guerra.
- MRL: Lançador Múltiplo de Foguetes.
- APC: Veículo Blindado de Transporte de Pessoal.
- SRBM: Míssil Balístico de Curto Alcance.
- UAV: Veículo Aéreo Não Tripulado.
- RPA: Veículo Pilotado Remotamente.

**Histórico do Conjunto de Dados:** Criado em 02/03/2022.

## Referências

1. Petro Ivaniuk. (2022). "2022 Ukraine Russia War" [Kaggle Dataset](https://doi.org/10.34740/KAGGLE/DS/1967621).
2. [Google Sheets](https://docs.google.com/spreadsheets/u/0/?tgif=d).
3. Ariel Bandeira. (2024). [Guerra da Ucrânia: Estatísticas de Perdas do Exército Russo](https://colab.research.google.com/drive/1yoDXCwB_MfsYc0icgN8xcEDaGA9ho1bz?usp=sharing).
