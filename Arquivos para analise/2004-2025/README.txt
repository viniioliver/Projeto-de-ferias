# 🌦️ Análise Climática do Estado do Rio de Janeiro (2020–2025)

Este projeto tem como objetivo analisar dados climáticos históricos (temperatura e precipitação) do estado do Rio de Janeiro entre os anos de 2020 e 2025, com foco na identificação de **eventos extremos**, como:

- Ondas de calor  
- Ondas de frio  
- Quantidade de chuvas (precipitação acumulada e eventos intensos)

## 📚 Fonte dos Dados

Os dados utilizados foram obtidos por meio do **Banco de Dados Meteorológicos para Ensino e Pesquisa (BDMEP)** do INMET, abrangendo diversas estações meteorológicas em todo o estado do Rio de Janeiro.

## ⚙️ Ferramentas Utilizadas

- Python
  - Pandas
  - Matplotlib
  - Seaborn
  - NumPy
- Power BI (para relatório final)
- VS Code / Jupyter Notebook

## 📌 Etapas do Projeto

1. **Importação dos Dados**  
   Leitura de arquivos CSV com dados diários de temperatura máxima, mínima e precipitação.

2. **Tratamento de Dados**
   - Conversão e padronização de datas
   - Identificação e tratamento de valores nulos
   - Filtragem por estações do estado do RJ

3. **Análise Estatística**
   - Cálculo de medidas descritivas: média, mediana, Q1, Q2, Q3
   - Identificação de outliers por estação e por ano
   - Comparações entre municípios e regiões

4. **Visualização**
   - Boxplots para comportamento anual da temperatura
   - Gráficos de linha com tendências de variação
   - Mapa geográfico no Power BI com distribuição de estações meteorológicas e eventos extremos

5. **Detecção de Eventos Extremos**
   - **Ondas de calor:** dias com temperaturas máximas superiores ao terceiro quartil
   - **Ondas de frio:** dias com temperaturas mínimas inferiores ao primeiro quartil
   - **Chuvas intensas:** precipitação acima de valores típicos para o período

6. **Relatório Final no Power BI**
   - Dashboard com insights visuais sobre comportamento climático, tendências e alertas de extremos

## 💡 Dificuldades Encontradas

- Integração de dados de diferentes estações com formatos variados
- Volume elevado de registros exigindo otimização de performance
- Definição de limiares estatísticos adaptáveis por estação para eventos extremos
- Limpeza de dados meteorológicos com falhas pontuais nos sensores

## 🤖 Apoio do ChatGPT

Durante o desenvolvimento do projeto, foi utilizado o **ChatGPT (OpenAI)** como ferramenta de apoio técnico para:

- Escrita e depuração de códigos Python para análise e visualização
- Criação de gráficos adequados com Matplotlib e Seaborn
- Interpretação estatística dos dados
- Sugestões na estruturação do notebook e organização do projeto
- Geração deste `README.md` e do `requisitos.txt` com base nos pacotes utilizados

## 👨‍💻 Autor

- **Vinicius Oliveira**  
  Projeto realizado como parte da jornada prática em análise de dados, com foco em climatologia, eventos extremos e visualização aplicada.
