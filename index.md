# Portfólio

---
## Sobre mim
  Me chamo Letícia da Luz. Atualmente, estou em formação em Ciência de Dados pela Data Science Academy e recentemente concluí o Bootcamp de Data Science do programa Santander Coders, uma parceria entre a Ada Tech e a Santander Open Academy.   
  Sou farmacêutica graduada pela Universidade Federal do Paraná e atuei em diversos setores da área da saúde. Meu interesse por dados surgiu durante minha experiência na área de epidemiologia, onde percebi o impacto significativo da análise de dados na tomada de decisões e na melhoria de processos.  
  Meu objetivo é ajudar as empresas a superar desafios na tomada de decisões estratégicas, fornecendo soluções baseadas em dados e transformando informações em ideias que impulsionem o crescimento e a inovação.

Linguagens de Programação:
- R: readr, dplyr, caret, randomforest, ggplot2, xgboost e catboost.
- Python: pandas, scikit-learn, matplotlib e seaborn.
- SQL

Ferramentas:
- Microsoft Azure Machine Learning
- Power BI
- Excel
---

[Projetos Machine Learning](#projetosml)    
[Projetos SQL](#projetos)  
[Projetos Power BI](#projetos)  
[Projetos Excel](#projetos)  

## Projetos em Machine Learning <a name="projetosml"></a>

### Processamento de Dados em Machine Learning: Técnicas e Melhores Práticas
![image](https://github.com/leticiadluz/leticiadluz.github.io/assets/138510840/d9be65b3-1de2-4763-8def-d55f63766ab5)

**Objetivos:** Neste projeto, busquei abordar uma das dúvidas mais comuns no estudo de Machine Learning: o processamento de dados. Meu objetivo foi identificar e aplicar as melhores práticas, evitando armadilhas comuns e tornando o código mais reutilizável. Para isso, elaborei um resumo abrangente que explora os seguintes tópicos essenciais:
- Ordem de Pré-Processamento: Técnicas para evitar vazamento de dados, garantindo a integridade do modelo.
- Tratamento de Valores Ausentes e Outliers: Métodos eficazes para lidar com dados faltantes e valores discrepantes.
- Técnicas de Encoding: Comparação entre One-Hot, Target e CatBoost Encoder, explicando a premissa por trás de cada um e o motivo pelo qual devemos evitar One-Hot Encoding em árvores de decisão.
- Métodos de Scaling: Análise das características de diferentes técnicas scaling.
- Tunagem de Hiperparâmetros: Estratégias para otimizar os parâmetros dos modelos para melhorar o desempenho.
- Métodos de Validação: Técnicas como holdout e validação cruzada para avaliar a performance do modelo de forma robusta.
- Seleção de Variáveis: Utilização de métodos wrapper, incorporados e de filtro para identificar as features mais relevantes.
- Dados Desbalanceados: Abordagens para lidar com datasets desbalanceados como o ajuste estratégico dos pesos de classe e a nova funcionalidade do scikit-learn 1.5 (TunedThresholdClassifierCV), que ajuda a ajustar os limiares de decisão de forma mais adequada.
- Pipelines: Exemplos completos de pipelines para automatizar o processo de pré-processamento e modelagem, tornando o código mais reutilizável e organizado.
- Também explorei a decomposição de viés e variância tanto para regressão quanto para classificação, aprofundando-me além da simples premissa de underfitting, overfitting e complexidade de modelos, proporcionando uma compreensão mais sólida sobre esses conceitos.

**Ferramentas Utilizadas:**
  - Python
  - Jupyter Notebook
    
Para acessar o projeto basta clicar [aqui](https://leticiadluz.github.io/ml_introduction/resumo_ml.pdf).


### Previsão de Cancelamento de Serviço de Internet e Segmentação de Clientes

![image](https://github.com/leticiadluz/leticiadluz.github.io/assets/138510840/5a3b7280-76f7-4f5b-a5fa-ab2607be7bc3)


**Contexto:** Com a crescente competição entre os provedores de internet, manter os clientes existentes tornou-se uma prioridade vital para aumentar a receita. Diante desse cenário, entender o fenômeno do churn, ou seja, a taxa de cancelamento de serviços, é crucial. Os provedores buscam identificar quais clientes apresentam maior probabilidade de cancelar seus serviços, pois isso lhes permite antecipar tais movimentos e implementar estratégias eficazes de retenção.

**Objetivos:** 
- O primeiro objetivo é criar um modelo capaz de prever quando um cliente está prestes a cancelar seu serviço de internet.
- O segundo objetivo é agrupar os clientes que cancelaram o serviço de internet usando técnicas de clusterização. Ao identificar grupos de clientes com características e comportamentos semelhantes, conseguimos desenvolver estratégias de marketing específicas para reter esses clientes.

**Resultados:**
- Construímos seis modelos de Machine Learning utilizando três estimadores: KNN, SVC e XGBoost. Realizamos pré-processamento das variáveis e otimização de hiperparâmetros. A métrica escolhida foi o recall, visando minimizar falsos negativos e identificar o maior número de clientes em risco de churn. O modelo final, utilizando o estimador XGBoost, alcançou um recall de 0.94 nos dados de teste, indicando sua eficácia em identificar casos de churn. 
- Realizamos também uma análise de clusterização com os clientes que cancelaram o serviço, usando os algoritmos K-Means e DBSCAN. Embora ambos tenham produzido scores semelhantes, optamos pelo K-Means devido à sua eficiência computacional e capacidade de identificar uma segmentação mais detalhada dos dados, otimizando a diferenciação entre perfis de clientes.
  
**Ferramentas Utilizadas:**
  - Google Colab
  - Python  
Para acessar o projeto basta clicar em:  [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/ml_internet_provider_churn)

---
### Ciência de Dados em Recursos Humanos
![image](https://github.com/leticiadluz/leticiadluz.github.io/assets/138510840/d87a167e-8d6a-4699-9704-a364500a87be)

**Contexto:** Este projeto é dedicado à análise e compreensão das altas taxas de rotatividade de funcionários enfrentadas por uma empresa de tecnologia. Ele faz parte do desafio da Data Viking, onde foram disponibilizados dados reais de uma software house para os participantes interessados. A empresa tem experimentado uma rotatividade significativa de funcionários, chegando a 30% em alguns semestres. Essa alta taxa de rotatividade tem custos substanciais e impactos no negócio. 

**Objetivos:** 
- Utilizar técnicas de análise exploratória, modelos preditivos e clusterização para desenvolver estratégias mais eficazes de retenção e identificar fatores críticos que contribuem para o turnover.

**Resultados:**
- Na Análise Exploratória dos Dados, identificamos que as variáveis 'Pontuação de Desempenho' e 'Horas Extras' mostram uma relação significativa com a taxa de desligamento. Funcionários com pontuações de desempenho mais altas e aqueles que realizam mais horas extras têm uma maior probabilidade de se desligarem da empresa.
- Construímos modelos de Machine Learning, a métrica escolhida para otimização foi o recall. Ao final, utilizamos uma abordagem de ensemble que combina as forças de dois algoritmos de ML para melhorar o desempenho da classificação através de um VotingClassifier. O resultado final foi um recall de 0.62 nos dados de teste, indicando um desempenho razoável na identificação de funcionários propensos a sair.
- Realizamos uma análise de clusterização dos funcionários desligados utilizando o algoritmo K-Means, a análise de clusterização dos funcionários desligados revelou que o Cluster 1 é composto por funcionários de nível sênior que fazem mais horas extras e recebem um salário maior. Os padrões encontrados neste projeto podem ajudar a empresa a desenvolver estratégias específicas para diminuir o turnover.
- Este projeto me rendeu o 1º lugar entre mais de 500 inscritos no desafio.
  
**Ferramentas Utilizadas:**
  - Google Colab
  - Python  
Para acessar o projeto basta clicar em:  [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/HR_datascience_insights)

---

## Mini projetos

- [Mini projeto 1 - Análise combinatória e Probabilidades em Python](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/analise_combinatoria_probabilidade_python.ipynb)
- [Mini projeto 2 - Variáveis discretas e suas distribuições em R](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/variaveis_aleatorias_discretas_distribuicoes_R.ipynb)
- [Mini projeto 3 - Variáveis contínuas e suas distribuições em R]()
- [Mini projeto 4 - Estatística Descritiva em R](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/estatistica_descritiva_R.ipynb)
- [Mini projeto 5 - Testes Paramétricos em R]()
- [Mini projeto 6 - Testes Não Paramétricas em R]()
- [Mini projeto 7 - Teste de Qui-quadrado em R](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/teste_qui_quadrado_R.ipynb)
- [Mini projeto 8 - Análise Exploratória de Dados utilizando SQL e Python](https://github.com/leticiadluz/projetos_ADA/blob/main/banco_dados/Projeto_banco_dados.ipynb)
- [Mini projeto 9 - Construção de um algoritmo baseado em k-NN em Python](https://github.com/leticiadluz/projetos_ADA/blob/main/logica_programacao_II/KNN_projeto_carteira_investimentos.ipynb)


---
## Certificados
Para acessar os certificados, basta clicar [aqui](https://github.com/leticiadluz/Certificados/tree/main)

---

Entre em contato comigo por meio de:  

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/leticiadluz/) 
[<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">](mailto:leticiadluz@gmail.com) 


© 2024 Leticia da Luz. 

