<p align="center">
  <img src=".github/banner.svg" alt="Desafio QuarentenaDados" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="Scikit-Learn" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
  <a href="https://colab.research.google.com/github/charles-gabriel-cc/Desafio-QuarentenaDados/blob/master/DesafioFinal_QuarentenaDados.ipynb"><img src="https://img.shields.io/badge/Abrir%20no-Google%20Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white" alt="Open in Colab" /></a>
</p>

## Sobre o Projeto

Solução desenvolvida para o desafio final da **#QuarentenaDados**, utilizando uma amostra dos **Microdados do ENEM 2018** para prever a nota de **Linguagens, Códigos e suas Tecnologias (`NU_NOTA_LC`)** a partir das demais notas da prova.

## Etapas da Análise

1. **Carregamento e exploração:** leitura dos datasets de treino e teste (`CN`, `CH`, `MT`, `REDACAO` → `LC`).
2. **Análise de correlação:** visualização da relação entre as áreas de conhecimento via *heatmap* (`seaborn` / `matplotlib`).
3. **Modelagem e otimização:** pipeline de pré-processamento + **`RandomForestRegressor`** ajustado com **`GridSearchCV`**.
4. **Avaliação:** comparação entre valores reais e previstos no conjunto de teste usando **Erro Quadrático Médio (MSE)**.

## Como Executar

Clique no botão **Abrir no Google Colab** no topo deste README ou rode localmente:

```bash
git clone https://github.com/charles-gabriel-cc/Desafio-QuarentenaDados.git
cd Desafio-QuarentenaDados
jupyter notebook DesafioFinal_QuarentenaDados.ipynb
```
