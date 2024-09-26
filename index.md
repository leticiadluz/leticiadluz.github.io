# Portfólio

## Sobre mim
Atualmente, estou em formação em Ciência de Dados pela Data Science Academy e recentemente concluí o Bootcamp de Data Science do programa Santander Coders, uma parceria entre a Ada Tech e a Santander Open Academy.   
Sou farmacêutica graduada pela Universidade Federal do Paraná e atuei em diversos setores da área da saúde. Meu interesse por dados surgiu durante minha experiência na área de epidemiologia, onde percebi o impacto significativo da análise de dados para a melhoria de processos.  
Meu objetivo é ajudar as empresas a superar desafios na tomada de decisões, fornecendo soluções baseadas em dados e transformando informações em ideias que impulsionem o crescimento e a inovação.

**Habilidades Técnicas:**  
- Linguagens de Programação: R, Python
- Análise de Dados: Excel, SQL

---

## Projetos de Machine Learning <a name="projetos-ml"></a>

### Previsão de Câncer de Pulmão com R e Deploy na AWS ECS
![image](https://github.com/user-attachments/assets/3c43007e-7d45-4ef2-8101-15508083c055)

**Contexto:** Este projeto visa prever o risco de câncer de pulmão utilizando machine learning com Tidymodels em R. O modelo ajuda a compreender o risco de desenvolver câncer de pulmão baseado em diversos fatores, auxiliando na tomada de decisões na área da saúde. 

**Objetivos:**
- Criar um modelo preditivo com Tidymodels para prever o risco de câncer de pulmão.  
- Utilizar a interface do Tidymodels para todas as etapas do processo de modelagem, desde a preparação dos dados até a validação do modelo e a geração de previsões.  
- Realizar o deploy do modelo na nuvem utilizando AWS, Vetiver e Plumber para tornar o modelo acessível pela internet.  

**Resultados:**
- Foram desenvolvidos cinco modelos de machine learning para a previsão de câncer de pulmão, com o modelo KNN alcançando um recall de 0.90 nos testes, usando ADASYN para balanceamento de classes. Apesar de espaço para melhorias, o modelo já consegue identificar casos de alto risco, aumentando as chances de tratamento eficaz.
- O modelo foi disponibilizado via API em R, usando Plumber e Vetiver, e hospedado na AWS através do Elastic Container Service (ECS), garantindo acesso online.
- A imagem Docker foi hospedada no Elastic Container Service (ECS) da AWS. Isso garantiu que o modelo fosse acessível pela internet.
- Este projeto mostrou o potencial dos modelos de machine learning em prever câncer de pulmão e a viabilidade de seu deploy em ambientes de produção utilizando a AWS. 

**Ferramentas e Cloud Utilizadas :**
- Jupyter Notebook
- Docker
- R
- AWS

#### Para acessar o projeto basta clicar em:     [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/ml_lung_cancer_deploy)
---
### Previsão de Cancelamento de Serviço de Internet e Segmentação de Clientes
![image](https://github.com/user-attachments/assets/45f7431d-0632-4d6f-bdce-934a1206e80a)

**Contexto:** Com a crescente competição entre os provedores de internet, manter os clientes existentes tornou-se uma prioridade para aumentar a receita. Diante desse cenário, entender o fenômeno do churn é crucial. Identificar os clientes com maior probabilidade de cancelar os serviços permite a implementação de estratégias eficazes de retenção.

**Objetivos:** 
- O primeiro objetivo é criar um modelo capaz de prever quando um cliente está prestes a cancelar seu serviço de internet.
- O segundo objetivo é agrupar os clientes que cancelaram o serviço de internet usando técnicas de clusterização. Ao identificar grupos de clientes com características e comportamentos semelhantes, conseguimos desenvolver estratégias de marketing específicas para reter esses clientes.

**Resultados:**
- Construímos seis modelos de Machine Learning utilizando três estimadores. Realizamos pré-processamento das variáveis e otimização de hiperparâmetros. A métrica escolhida foi o recall. O modelo final, utilizando o estimador XGBoost, alcançou um recall de 0.94 nos dados de teste, indicando sua eficácia em identificar casos de churn. 
- Realizamos também uma análise de clusterização com os clientes que cancelaram o serviço, usando os algoritmos K-Means e DBSCAN. Optamos pelo K-Means devido à sua eficiência computacional e capacidade de identificar uma segmentação mais detalhada dos dados, otimizando a diferenciação entre perfis de clientes.
  
**Ferramentas Utilizadas:**
  - Google Colab
  - Python

#### Para acessar o projeto basta clicar em:  [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/ml_internet_provider_churn)

---
### Ciência de Dados em Recursos Humanos
![image](https://github.com/user-attachments/assets/5ce61a51-3138-42ee-8286-54ae6136d5a1)

**Contexto:** Este projeto é dedicado à análise e compreensão das altas taxas de rotatividade de funcionários enfrentadas por uma empresa de tecnologia. Ele faz parte do desafio da Data Viking, onde foram disponibilizados dados reais de uma software house para os participantes interessados. A empresa tem experimentado uma rotatividade significativa de funcionários, chegando a 30% em alguns semestres. Essa alta taxa de rotatividade tem custos substanciais e impactos no negócio. 

**Objetivos:** 
- Utilizar técnicas de análise exploratória, modelos preditivos e clusterização para desenvolver estratégias mais eficazes de retenção e identificar fatores críticos que contribuem para o turnover.

**Resultados:**
- Análise exploratória mostrou que funcionários com altas pontuações de desempenho e mais horas extras têm maior probabilidade de se desligarem da empresa.  
- Construímos modelos de Machine Learning, com o recall como métrica de otimização.  
- Utilizamos uma abordagem de ensemble com VotingClassifier, obtendo um recall de 0.62 nos dados de teste, indicando bom desempenho na identificação de funcionários propensos a sair.  
- Realizamos clusterização com K-Means, revelando que o Cluster 1 é composto por funcionários sêniores que fazem mais horas extras e recebem salários mais altos.  
- Os padrões identificados podem ajudar a empresa a desenvolver estratégias específicas para reduzir o turnover.  
- O projeto garantiu o 1º lugar entre mais de 500 inscritos no desafio.  
  
**Ferramentas Utilizadas:**
  - Google Colab
  - Python
    
#### Para acessar o projeto basta clicar em:  [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/HR_datascience_insights)

---
## Projetos de Análise de Dados <a name="projetos-analise"></a>
- [Análise Exploratória de Dados Literários com SQL e PostgreSQL](https://github.com/leticiadluz/projetos_ADA/blob/main/banco_dados/Projeto_banco_dados.ipynb)

---

## Estatística Aplicada à Análise de Dados: Conceitos e Implementações em R e Python <a name="projetos-estatistica"></a>
O objetivo deste tópico é proporcionar uma visão abrangente dos principais conceitos estatísticos aplicados à análise de dados, com ênfase em suas implementações práticas nas linguagens R e Python.  

- [Estatística Descritiva para Variáveis Qualitativas em Python](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/1_estatistica_descritiva_qualitativas__python.ipynb)
- [Estatística Descritiva para Variáveis Quantitativas em R](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/2_estatistica_descritiva_quantitativas_R.ipynb)
- [Análise Bidimensional em R](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/3_analise_bidimensional_R.ipynb)
- [Análise combinatória e Probabilidades em Python](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/4_analise_combinatoria_probabilidade_python.ipynb)
- [Variáveis aleatórias discretas e suas distribuições em R](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/5_variaveis_aleatorias_discretas_distribuicoes_R.ipynb)

---
## Processamento de Dados em Machine Learning: Técnicas e Melhores Práticas  <a name="ml-processamento"></a>

Neste projeto, busquei abordar uma das dúvidas mais comuns no estudo de Machine Learning: o processamento de dados. Meu objetivo foi identificar e aplicar as melhores práticas, evitando armadilhas comuns e tornando o código mais reutilizável. Para isso, elaborei um resumo abrangente que explora os seguintes tópicos essenciais:
- Técnicas para evitar vazamento de dados.
- Tratamento de Valores Ausentes e Outliers.
- Técnicas de Encoding: Comparação entre One-Hot, Target e CatBoost Encoder, explicando a premissa por trás de cada um deles.
- Análise das características de diferentes técnicas scaling.
- Estratégias para otimizar os parâmetros dos modelos para melhorar o desempenho.
- Técnicas como holdout e validação cruzada para avaliar a performance do modelo de forma robusta.
- Utilização de métodos wrapper, incorporados e de filtro para identificar as features mais relevantes.
- Abordagens para lidar com datasets desbalanceados e a nova funcionalidade do scikit-learn 1.5 (TunedThresholdClassifierCV), que ajuda a ajustar os limiares de decisão de forma mais adequada.
- Exemplos completos de pipelines para automatizar o processo de pré-processamento e modelagem, tornando o código mais reutilizável e organizado.
- Também explorei a decomposição de viés e variância tanto para regressão quanto para classificação, aprofundando-me além da simples premissa de underfitting, overfitting e complexidade de modelos, proporcionando uma compreensão mais sólida sobre esses conceitos.

#### Para acessar o projeto basta clicar em:  [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://leticiadluz.github.io/ml_introduction/resumo_ml.pdf)

---
## Estimadores e métricas de avaliação em Machine Learning <a name="projetos-estimadores"></a>
Aqui você encontra resumos que detalham o funcionamento dos estimadores em Machine Learning e as métricas de avaliação para classificação e regressão:  


- [Métricas de Avaliação para Classificação](https://github.com/leticiadluz/resumo_estimadores/blob/main/classificacao_metricas.ipynb)
- [Árvores de Decisão](https://github.com/leticiadluz/estimadores/blob/main/decision_tree.ipynb)

---
## Certificados
Para acessar os certificados, basta clicar [aqui](https://github.com/leticiadluz/Certificados/tree/main)

---

Entre em contato comigo por meio de:  

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/leticiadluz/) 
[<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">](mailto:leticiadluz@gmail.com) 


© 2024 Leticia da Luz. 

