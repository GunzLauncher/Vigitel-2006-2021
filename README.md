# Vigitel-2006-2021

Impact analysis of anti-smoking public policies in Brazil, using the time series from the Epidemiological Analysis and Surveillance of Non-communicable Diseases (VIGITEL)

# Step 1: dados_Vigitel_2006-2021.rmd

Data base preparation:

The csv files from the 16 years that make up the analysis were obtained from the website https://svs.aids.gov.br/download/Vigitel/

They were stacked into a single dataframe, and only the columns of initial interest were selected.

# Step 2: Limpeza_dados_Interesse

Data cleaning and treatment:

The necessary transformations were performed on the independent variables of the database for later use in the econometric model.

# Step 3: LSDV_Vigitel_Tabagismo.rmd

The treated database is submitted to the LSDV model, a statistical technique used to control for unobserved heterogeneity among units, estimating specific fixed effects for each of them.

# PT - BR

# Vigitel-2006-2021

Análise de impacto das políticas públicas antitabagistas no Brasil, utilizando a série temporal da Análise Epidemiológica e Vigilância de Doenças Não Transmissíveis (VIGITEL)

# Passo 1: dados_Vigitel_2006-2021.rmd

Preparação da base de dados:

 Os arquivos csv dos 16 anos que compõem a análise foram obtidos no site https://svs.aids.gov.br/download/Vigitel/

 Foram empilhados num único dataframe e apenas as colunas inicialmente de interesse foram selecionadas.

 # Passo 2: Limpeza_dados_Interesse

 Limpeza e tratamento dos dados:

 Foi realizada as transformações necessárias nas variáveis independentes da base da dados para posterior utilização no modelo econométrico,

 # Passo 3: LSDV_Vigitel_Tabagismo.rmd

 A base de dados tratada é submetida ao modelo LSDV, técnica estatística utilizada para controlar a heterogeneidade não observada entre as unidades, estimando efeitos fixos específicos para cada uma delas.
