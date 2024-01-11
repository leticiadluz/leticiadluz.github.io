# Portfólio

---

## Classificação

### Prevendo o Status de Extinção de Chamas de Combustível por Ondas Sonoras em R
<span style="font-size: 14px;"> Este projeto tem como objetivo principal criar um modelo de Machine Learning capaz de prever se uma chama será extinta ao empregar um sistema de extinção por ondas sonoras, com base em simulações computacionais. 

<span style="font-size: 14px;">Os incêndios, provenientes de diversas causas, são considerados desastres naturais, e a busca por abordagens mais ecológicas e inovadoras para seu controle tem sido uma prioridade. No âmbito dessa pesquisa, um sistema de extinção de incêndios baseado em ondas sonoras foi concebido e está passando por testes para avaliar sua eficácia no combate aos incêndios. 

<span style="font-size: 14px;">Assim, utilizando dados reais disponíveis publicamente iremos desenolver um modelo em Machine Learning, nosso objetivo é desenvolver um modelo de Machine Learning capaz de prever a eficácia de um sistema de extinção de incêndios por ondas sonoras. Para alcançar esse objetivo, utilizamos quatro algoritmos: **o GLM (General Linear Model), Naive Bayes, Random Forest e Árvores de Decisão C50, incluindo uma versão com função de custo**. Notavelmente, as Árvores de Decisão C50 se destacaram, apresentando um desempenho superior, com uma acurácia superior a 0.98. 

<span style="font-size: 14px;">O dataset original pode ser acessado clicando [aqui](https://www.muratkoklu.com/datasets/vtdhnd07.php) 

<span style="font-size: 14px;">[![View on GitHub](https://github.com/leticiadluz/mini_projetos_ML_R/blob/main/Prevendo_status_extincao_chamas_ondas_sonoras_ML.ipynb)

Para ilustrar a sensibilidade e especificidade do modelo, apresentamos abaixo a imagem da curva ROC.
<img src="fotos_modelos/curva_roc_modelo_extincao.jpg"/>


### Avaliação de Risco de Crédito em linguagem R
<span style="font-size: 14px;">Este projeto tem como objetivo desenvolver um modelo preditivo destinado a classificar o risco de concessão de crédito para os clientes de uma instituição bancária. O objetivo principal é aprimorar a tomada de decisões relacionadas à concessão de crédito por meio da implementação de um modelo que avalie de forma precisa e eficiente o risco associado a cada cliente. 

<span style="font-size: 14px;">O conjunto de dados 'German Credit Data' será usado para construir e treinar o modelo, neste experimento. Este dataset é baseado em dados reais gerados por um pesquisador da Universidade de Hamburgo, na Alemanha.  

<span style="font-size: 14px;">Para o treinamento do modelo, utilizamos três algoritmos: o **GLM (General Linear Model), Naive Bayes e Random Forest**. Previamente, empregamos técnicas de balanceamento de dados, como SMOTE e ROSE, com o intuito de aprimorar o desempenho do modelo diante de desequilíbrios na distribuição dos dados.  

<span style="font-size: 14px;">[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/mini_projetos_ML_R/blob/main/Classificacao_avaliacao_risco_credito_R.ipynb)

<span style="font-size: 14px;">O dataset original pode ser acessado clicando [aqui](https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data) 

<span style="font-size: 14px;">Imagem da curva ROC que ilustra o desempenho do modelo de classificação binária:
<img src="fotos_modelos/curva_roc.jpg"/>

---

## Regressão

### Prevendo o Consumo de Energia de Carros Elétricos em linguagem R

<span style="font-size: 14px;"> O projeto Prevendo o Consumo de Energia de Carros Elétricos tem como propósito desenvolver um modelo de Machine Learning capaz de prever o consumo de energia de carros elétricos. 

<span style="font-size: 14px;">Na construção do modelo, empregou-se a biblioteca **RandomForest** para avaliar a importância das variáveis. Ao final desse processo, optou-se pela utilização do **modelo de regressão** linear para a criação do modelo final. 

<span style="font-size: 14px;">Já a avaliação de desempenho do modelo de regressão inclui a análise de métricas fundamentais, como o **Erro Quadrático Médio (MSE)**, a **Raiz do Erro Quadrático Médio (RMSE)** e o **Coeficiente de Determinação (R²)**. Além disso, são realizadas verificações adicionais, como a avaliação da **homocedasticidade** para assegurar a constância da variância dos resíduos ao longo dos valores preditos, assim como a verificação da **normalidade** dos resíduos.

<span style="font-size: 14px;">[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/mini_projetos_ML_R/blob/main/Consumo_carros_eletricos_ML.ipynb)

<span style="font-size: 14px;">A base de dados  é composta por 53 carros elétricos e pode ser acessada clicando [aqui](https://data.mendeley.com/datasets/tb9yrptydn/2)

<span style="font-size: 14px;">Abaixo apresenta-se o Gráfico de Resíduos versus Valores Ajustados, auxiliando na verificação da suposição de homocedasticidade, juntamente com um histograma para avaliação da normalidade dos resíduos:
<img src="fotos_modelos/residuos.jpg"/>

---

## Mini projetos

- [Mini projeto 1 - Resumo Estatístico em R](https://github.com/leticiadluz/estatistica_com_R/blob/main/Resumo_Estatistica_R_Jupyter.ipynb)
- [Mini projeto 2 - Testes de Hipóteses em R](https://github.com/leticiadluz/estatistica_com_R/blob/main/Teste_Hipotese.ipynb)
- [Mini proejeto 3 - Análise de Variância (ANOVA) em R ](https://github.com/leticiadluz/estatistica_com_R/blob/main/Anova_R.ipynb)
- [Mini projeto 4 - AED em Dados Categóricos e Teste Qui-Quadrado em R](https://github.com/leticiadluz/AED_categoricos-qui_quadrado_R/blob/main/AED_Categoricos.ipynb)



---
© 2024 Leticia da Luz. Desenvolvido por Jekyll e the Minimal Theme.
