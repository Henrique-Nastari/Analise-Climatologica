# Análise Climatológica Comparativa: Macau e Mossoró (RN)

Este projeto realiza uma análise climatológica descritiva e comparativa dos dados históricos das estações meteorológicas de Macau e Mossoró, duas importantes cidades do estado do Rio Grande do Norte, Brasil. A análise foi desenvolvida como parte da disciplina de Meteorologia Aplicada (TAD0044).

## 🎯 Objetivo

O objetivo principal deste trabalho é analisar e comparar as normais climatológicas de precipitação, temperatura e umidade relativa para as cidades de Macau e Mossoró, a fim de:

1.  Identificar os padrões sazonais (períodos chuvosos/secos e quentes/frios).
2.  Compreender a relação entre as principais variáveis meteorológicas.
3.  Avaliar a aptidão climática de cada município para a produção de culturas agrícolas específicas: **mamão, acerola e melancia**.

## 📊 Dataset

O conjunto de dados utilizado consiste em uma série histórica de 30 anos (360 meses), abrangendo as seguintes variáveis para cada estação:

-   **Prec:** Precipitação pluviométrica média mensal (mm)
-   **temp:** Temperatura média mensal (°C)
-   **UR:** Umidade Relativa do ar média mensal (%)
-   **Rad:** Radiação solar média mensal

O arquivo original, `BD_Macau_e_Mossor.csv`, foi processado e limpo para a análise.

## 🛠️ Ferramentas Utilizadas

-   **Linguagem:** Python
-   **Bibliotecas Principais:**
    -   **Pandas:** Para manipulação e análise dos dados.
    -   **Matplotlib:** Para a criação das visualizações gráficas (gráficos de barras e combinados).
    -   **Numpy:** Para operações numéricas.

## 📈 Análises Realizadas

O notebook Jupyter (`analise_climatologica.ipynb`) segue uma estrutura lógica, dividida nos seguintes passos:

1.  **Carregamento e Limpeza:** Leitura do arquivo `.csv`, tratamento dos cabeçalhos e conversão dos tipos de dados.
2.  **Preparação dos Dados:** Separação do dataset principal em dois DataFrames distintos, um para Macau e outro para Mossoró.
3.  **Análise de Precipitação:** Criação de gráficos de barras para visualizar e comparar a precipitação média mensal, identificando os meses mais chuvosos e secos.
4.  **Análise de Temperatura:** Geração de gráficos de barras para comparar a temperatura média mensal e determinar os meses mais quentes e frios.
5.  **Análise de Correlação (Umidade vs. Precipitação):** Criação de gráficos combinados (barras e linhas) para analisar visualmente a relação entre a umidade relativa e os períodos de chuva.
6.  **Análise de Aptidão Agrícola:** Comparação dos dados climatológicos anuais de cada cidade com as condições ideais para o cultivo de mamão, acerola e melancia, resultando em uma recomendação fundamentada.

## 💡 Principais Conclusões

-   **Padrão de Chuvas:** Ambas as cidades apresentam um regime de chuvas bem definido, com uma estação chuvosa concentrada no primeiro semestre (pico em **Abril**) e um período seco no segundo semestre.
-   **Padrão de Temperatura:** O clima é quente e estável ao longo do ano, com temperaturas ligeiramente mais amenas nos meses de **Junho e Julho**.
-   **Aptidão para Culturas:**
    -   **Melancia:** Ambas as cidades são **altamente aptas**, com temperatura e precipitação dentro da faixa ideal.
    -   **Mamão e Acerola:** Embora a temperatura seja ideal, a precipitação anual é **insuficiente**, tornando a **irrigação suplementar um fator crítico** para a produção em ambos os locais.

## Como Executar

1.  Clone este repositório.
2.  Certifique-se de ter Python e as bibliotecas listadas instaladas.
3.  Abra e execute o notebook `analise_climatologica.ipynb` em um ambiente como Jupyter Lab ou VS Code.
