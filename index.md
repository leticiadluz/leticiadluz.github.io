# Portfólio <a name="inicio"></a>

## Sobre mim 
Profissional com experiência em análise de dados e habilidades em desenvolvimento de modelos preditivos, estatística, versionamento de código e dashboards para visualização de dados e tomada de decisão.  

Minha experiência em análise de dados na Saúde Pública durante a graduação, deu origem à minha trajetória na área. Durante esse período, percebi como a análise de dados pode impactar significativamente a melhoria de processos e potencializar a geração de resultados positivos.     

Atualmente, estou cursando a formação Cientista de Dados pela Data Science Academy e concluí a formação em Data Science do programa Santander Coders, uma parceria entre a Ada Tech e a Santander Open Academy.    

Meu objetivo é apoiar empresas na tomada de decisões estratégicas, oferecendo soluções baseadas em dados para impulsionar o crescimento e a inovação.    

**Habilidades Técnicas:**    
- Linguagens: R, Python e SQL  
- Ferramentas: Docker, Excel, Git e Power BI. 

---
## Projetos de Análise de Dados <a name="projetos-analise"></a>

### Pipeline de Dados: ETL com Airflow, Python e Visualizações no Power BI
![image](https://github.com/user-attachments/assets/d4845070-9a1c-4774-b08a-b0e9c41f5cc7)

**Contexto:** Este projeto teve como foco a construção de um pipeline de dados para análise de vendas de uma loja online fictícia, utilizando a FakeStoreAPI. Ele abrangeu todas as etapas de um processo ETL (Extração, Transformação e Carregamento), além do desenvolvimento de dashboards no Power BI para visualização dos dados.

**Objetivos:**
- Implementar um pipeline ETL utilizando Python em conjunto com Docker, Airflow e PostgreSQL, demonstrando a integração dessas ferramentas.
- Extrair e transformar dados da FakeStoreAPI, organizando informações sobre produtos, carrinhos e usuários para análises detalhadas.
- Realizar análises descritivas e diagnósticas para identificar padrões de vendas e comportamento do consumidor.
- Disponibilizar os dados transformados em um formato acessível para visualização analítica no Power BI.

**Resultados:**
- As análises revelaram que as categorias "men's clothing" e "electronics" lideram em volume de vendas. Recomenda-se investir em campanhas de marketing direcionadas a essas categorias, além de criar combos promocionais que combinem produtos mais vendidos com itens de menor desempenho, promovendo a diversificação e contribuindo para o aumento do ticket médio.
- A análise revelou uma relação positiva entre as avaliações e o volume de vendas, indicando que produtos bem avaliados têm maior impacto nas vendas. Implementar um sistema automatizado que incentive os clientes a deixarem feedbacks pode resultar em um aumento do volume de vendas.
- Alguns produtos receberam avaliações baixas, destacando a importância de uma análise detalhada para identificar os motivos dessas classificações. Essa abordagem permite implementar melhorias nos produtos, prevenindo impactos negativos na reputação da marca e fortalecendo a confiança dos clientes, além de impulsionar as vendas.

**Ferramentas e linguagens utilizadas:**
- Airflow
- Docker
- Git
- PostgreSQL
- Power BI
- Python
- SQL
- Visual Studio Code
  
#### Para acessar o projeto basta clicar em:      [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/pipeline_analise_etl)
---

### Análise RFV e Clusterização
![image](https://github.com/user-attachments/assets/845adaec-d8d5-4746-9f2c-fa1320fd0f86)


**Contexto:** Este projeto focou na segmentação de clientes de uma loja online por meio de análise RFV e clusterização, identificando padrões de comportamento de compra e desenvolvendo estratégias personalizadas para marketing e retenção.

**Objetivos:**
- Implementar a metodologia CRISP-DM para orientar todas as etapas do projeto, desde o entendimento do negócio até a avaliação dos resultados.
- Realizar uma análise RFV para segmentar os clientes em diferentes categorias com base em seu histórico de compras.
- Aplicar o algoritmo KMeans para identificar grupos distintos de clientes e otimizar a segmentação.
- Responder a cinco perguntas estratégicas para otimizar vendas e gestão de inventário.

**Resultados:**
- A análise RFM permitiu classificar os clientes em dez categorias, oferecendo uma visão clara dos grupos com maior valor e dos clientes em risco de churn.
- A clusterização com KMeans identificou quatro clusters principais, revelando padrões de compra significativos.
- Respondemos a cinco perguntas estratégicas de negócios, fornecendo informações detalhadas sobre os produtos mais vendidos, padrões sazonais, picos de vendas, clientes de maior valor e oportunidades para otimização do inventário.
- Foram feitas recomendações estratégicas para otimizar o inventário, personalizar campanhas de marketing e melhorar a retenção de clientes, baseadas nos padrões de compra identificados.

**Ferramentas e linguagens utilizadas:**
- Git
- MySQL
- Python
- SQL
- Visual Studio Code
  
#### Para acessar o projeto basta clicar em:      [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/analise_rfv)
---

## Projetos de Machine Learning <a name="projetos-ml"></a>

### Previsão de Câncer de Pulmão com R e Deploy na AWS ECS
![image](https://github.com/user-attachments/assets/3bcebe28-5773-430d-bea1-bf1bfeb0a3f3)


**Contexto:** Este projeto visa prever o risco de câncer de pulmão utilizando machine learning com Tidymodels em R. O modelo ajuda a compreender o risco de desenvolver câncer de pulmão baseado em diversos fatores, auxiliando na tomada de decisões na área da saúde. 

**Objetivos:**
- Criar um modelo preditivo com Tidymodels para prever o risco de câncer de pulmão.  
- Utilizar a interface do Tidymodels para todas as etapas do processo de modelagem, desde a preparação dos dados até a validação do modelo e a geração de previsões.  
- Realizar o deploy do modelo na nuvem utilizando AWS, Vetiver e Plumber para tornar o modelo acessível pela internet.  

**Resultados:**
- Cinco modelos de machine learning foram desenvolvidos para prever câncer de pulmão, com o KNN alcançando um recall de 0.90 nos testes, usando ADASYN para balanceamento, identificando casos de alto risco e aumentando as chances de tratamento eficaz
- O modelo foi disponibilizado via API em R, usando Plumber e Vetiver, e hospedado na AWS através do Elastic Container Service (ECS), garantindo acesso online.
- A imagem Docker foi hospedada no Elastic Container Service (ECS) da AWS. Isso garantiu que o modelo fosse acessível pela internet.
- Este projeto mostrou o potencial dos modelos de machine learning em prever câncer de pulmão e a viabilidade de seu deploy em ambientes de produção utilizando a AWS. 

**Ferramentas, linguagens e Cloud utilizadas:**
- AWS
- Docker
- Jupyter Notebook
- R

#### Para acessar o projeto basta clicar em:     [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/ml_lung_cancer_deploy)
---
### Previsão de Cancelamento de Serviço de Internet e Segmentação de Clientes
![image](https://github.com/user-attachments/assets/b14165eb-3322-4a70-baae-166fe57e3df3)


**Contexto:** A competição entre provedores de internet torna a retenção de clientes essencial. Compreender o churn é crucial para identificar clientes propensos ao cancelamento e aplicar estratégias eficazes de retenção.

**Objetivos:** 
- Criar um modelo capaz de prever quando um cliente está prestes a cancelar seu serviço de internet.
- Agrupar clientes que cancelaram o serviço de internet usando clusterização para identificar perfis semelhantes e desenvolver estratégias de marketing específicas para retenção.

**Resultados:**
- Construímos seis modelos de Machine Learning com três estimadores, realizando pré-processamento e otimização de hiperparâmetros. O modelo final, usando XGBoost, alcançou um recall de 0.94 nos testes, mostrando eficácia na identificação de churn.
- Realizamos uma análise de clusterização com clientes que cancelaram o serviço, usando K-Means e DBSCAN, optando pelo K-Means por sua eficiência e capacidade de segmentar detalhadamente os perfis de clientes.
  
**Ferramentas e linguagens utilizadas:**
  - Google Colab
  - Python

#### Para acessar o projeto basta clicar em:  [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/ml_internet_provider_churn)

---
### Ciência de Dados em Recursos Humanos
![image](https://github.com/user-attachments/assets/278c990c-d2d3-4f7f-83e8-a690660dcb00)

**Contexto:** Este projeto visa analisar as altas taxas de rotatividade de funcionários em uma empresa de tecnologia. Ele faz parte do desafio da Data Viking, onde foram disponibilizados dados reais de uma software house para os participantes interessados. A empresa enfrenta rotatividade significativa, chegando a 30% em alguns semestres, gerando custos substanciais e impactos no negócio.

**Objetivos:** 
- Utilizar técnicas de análise exploratória, modelos preditivos e clusterização para desenvolver estratégias mais eficazes de retenção e identificar fatores críticos que contribuem para o turnover.

**Resultados:**
- Análise exploratória mostrou que funcionários com altas pontuações de desempenho e mais horas extras têm maior probabilidade de se desligarem da empresa.  
- Construímos modelos de Machine Learning, com o recall como métrica de otimização.  
- Utilizamos uma abordagem de ensemble com VotingClassifier, obtendo um recall de 0.62 nos dados de teste, indicando bom desempenho na identificação de funcionários propensos a sair.  
- Realizamos clusterização com K-Means, revelando que o Cluster 1 é composto por funcionários sêniores que fazem mais horas extras e recebem salários mais altos.  
- Os padrões identificados podem ajudar a empresa a desenvolver estratégias específicas para reduzir o turnover.  
- Meu projeto conquistou o 1º lugar entre mais de 500 participantes inscritos no desafio.  
  
**Ferramentas e linguagens utilizadas:**
  - Google Colab
  - Python
    
#### Para acessar o projeto basta clicar em:  [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/leticiadluz/HR_datascience_insights)

---

## Estatística Aplicada à Análise de Dados <a name="projetos-estatistica"></a>
Meu objetivo neste tópico foi proporcionar uma visão abrangente dos principais conceitos estatísticos aplicados à análise de dados, com ênfase em suas implementações práticas nas linguagens R e Python.  

- [Estatística Descritiva para Variáveis Qualitativas em Python](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/1_estatistica_descritiva_qualitativas__python.ipynb)
- [Estatística Descritiva para Variáveis Quantitativas em R](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/2_estatistica_descritiva_quantitativas_R.ipynb)
- [Análise Bidimensional em R](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/3_analise_bidimensional_R.ipynb)
- [Análise combinatória e Probabilidades em Python](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/4_analise_combinatoria_probabilidade_python.ipynb)
- [Variáveis aleatórias discretas e suas distribuições em R](https://github.com/leticiadluz/estatistica_com_r_py/blob/main/5_variaveis_aleatorias_discretas_distribuicoes_R.ipynb)

---
## Fundamentos de Engenharia de Dados <a name="fundamentos-ed"></a> 
Nste tópico, explorei os fundamentos essenciais do ciclo de vida dos dados em uma solução de Engenharia de Dados, abrangendo desde a origem até o preparo final para análise.

- [ETL e ELT](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/1_extracao_dados_etl_elt.pdf)
- [Armazenamento e Modelagem em Data Warehouse](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/2_data_warehouse_modelagem%20.pdf)
- [Data Lake, Data Lakehouse, Delta Lake e Arquitetura Medalhão](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/3_datalake_lakehouse_deltalake.pdf)
- [Conteúdo Extra: Design e Normalização de Banco de Dados SQL e Banco de Dados NoSQL](https://github.com/leticiadluz/fundamentos_eng_dados/blob/main/extra_bancodedados_sql_nosql.pdf)

---
## Guia Prático de Machine Learning <a name="guia-prático"></a> 
### Processamento de Dados em Machine Learning 

Neste projeto, abordei uma das principais dúvidas em Machine Learning: o processamento de dados. Meu objetivo foi aplicar boas práticas, evitando erros comuns e promovendo a reutilização de código. O trabalho incluiu:

- Técnicas para evitar vazamento de dados.
- Tratamento de Valores Ausentes e Outliers.
- Comparação entre One-Hot, Target e CatBoost Encoder.
- Análise das características de diferentes técnicas scaling.
- Métodos para ajustar parâmetros e melhorar desempenho.
- Uso de holdout e validação cruzada para avaliar modelos.
- Seleção de features: métodos de filtro, wrapper e embedded.
- Estratégias para balanceamento e uso do novo TunedThresholdClassifierCV para ajustar limiares de decisão.  
- Exemplos completos de pipelines para automatizar o processo de pré-processamento e modelagem.
- Decomposição de viés e variância para regressão e classificação.

#### Para acessar o projeto basta clicar em:  [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://leticiadluz.github.io/ml_introduction/resumo_ml.pdf)

----
### Estimadores e métricas de avaliação em Machine Learning
Aqui, você encontra os resumos que preparei, detalhando o funcionamento dos estimadores em Machine Learning e as métricas de avaliação para classificação e regressão:  


- [Métricas de Avaliação para Classificação](https://github.com/leticiadluz/resumo_estimadores/blob/main/classificacao_metricas.ipynb)
- [Regressão Linear](https://github.com/leticiadluz/resumo_estimadores/blob/main/regressao_linear.ipynb)
- [Árvores de Decisão](https://github.com/leticiadluz/estimadores/blob/main/decision_tree.ipynb)

---
## Certificados
Para acessar os certificados, basta clicar [aqui](https://github.com/leticiadluz/Certificados/tree/main)

---

Entre em contato comigo por meio de:  

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">](https://www.linkedin.com/in/leticiadluz/) 
[<img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">](mailto:leticiadluz@gmail.com) 


© 2024 Leticia da Luz. 

