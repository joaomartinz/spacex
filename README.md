# 🚀 Applied Data Science Capstone - Previsão de Pouso do Falcon 9

Projeto final do **IBM Data Science Professional Certificate** (Coursera), no qual assumo o papel de cientista de dados trabalhando para uma startup que deseja competir com a SpaceX em licitações de lançamentos de foguetes.

## 📋 Sobre o Projeto

A SpaceX anuncia lançamentos do foguete Falcon 9 a um custo de **62 milhões de dólares**, enquanto outros fornecedores cobram a partir de **165 milhões de dólares**. Essa economia se deve, em grande parte, à capacidade da SpaceX de reaproveitar o primeiro estágio do foguete.

O objetivo deste projeto é **prever se o primeiro estágio do Falcon 9 pousará com sucesso**, permitindo estimar com mais precisão o custo de um lançamento — informação valiosa para empresas concorrentes em processos de licitação.

## 🎯 Perguntas de Negócio

- Quais variáveis (massa da carga útil, local de lançamento, número de voos, órbita) afetam o sucesso do pouso do primeiro estágio?
- É possível prever a probabilidade de reaproveitamento do primeiro estágio com base em dados históricos?

## 🛠️ Tecnologias e Ferramentas

- **Python** (Pandas, NumPy)
- **SQL** (consultas exploratórias)
- **BeautifulSoup** (web scraping)
- **Requests** (consumo de API REST)
- **Matplotlib / Seaborn** (visualização de dados)
- **Folium** (visualização geográfica interativa)
- **Plotly Dash** (dashboard interativo)
- **Scikit-learn** (modelos de Machine Learning)
- **Jupyter Notebook**

## 🔍 Metodologia

1. **Coleta de Dados**
   - Requisições à API pública da SpaceX
   - Web scraping de dados complementares (Wikipedia)

2. **Data Wrangling**
   - Tratamento de valores ausentes
   - Padronização e transformação de variáveis categóricas

3. **Análise Exploratória (EDA)**
   - Consultas SQL para extrair insights
   - Visualizações com Matplotlib/Seaborn

4. **Visualização Geográfica**
   - Mapas interativos com Folium mostrando locais de lançamento e proximidade com infraestrutura

5. **Dashboard Interativo**
   - Construído com Plotly Dash para exploração dinâmica dos dados

6. **Modelagem Preditiva**
   - Divisão dos dados em treino/teste
   - Ajuste de hiperparâmetros para:
     - Regressão Logística
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - Árvore de Decisão
   - Comparação de acurácia entre os modelos

7. **Relatório Final**
   - Conclusões de negócio e recomendações estratégicas de licitação

Este projeto foi desenvolvido para fins educacionais como parte do **IBM Data Science Professional Certificate** na Coursera.

**João Vitor Martins**

[LinkedIn](https://www.linkedin.com/in/jo%C3%A3o-vitor-martinz/)
