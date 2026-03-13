<!-- Capa animada superior -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=2F2F2F&height=120&section=header" alt="Capa animada superior" width="1000" />
</p> 



# 🚢 Projeto Titanic - Previsão de Sobrevivência com Machine Learning

Neste projeto foi desenvolvido um modelo de Machine Learning para prever a sobrevivência de passageiros no desastre do Titanic.

O desafio consiste em analisar características dos passageiros como classe social, idade, sexo e estrutura familiar para identificar padrões que influenciaram a sobrevivência.

O projeto segue o fluxo completo de um projeto de Data Science, incluindo tratamento de dados, análise exploratória, engenharia de variáveis, treinamento de modelo preditivo e avaliação de desempenho.

<br>

**Objetivos do Projeto.**

- Explorar e compreender o dataset do Titanic;
- Realizar tratamento e limpeza dos dados;
- Criar novas variáveis relevantes para o modelo;
- Realizar análise exploratória dos dados (EDA);
- Treinar um modelo de classificação;
- Avaliar o desempenho do modelo;
- Gerar previsões para novos passageiros;
- Identificar fatores que influenciaram a sobrevivência.

<br>

**O que foi realizado.**

- Importação e exploração inicial do dataset;
- Tratamento de valores ausentes;
- Remoção de variáveis irrelevantes;
- Conversão de variáveis categóricas em numéricas;
- Aplicação de One-Hot Encoding;
- Criação de novas variáveis:
  - FamilySize
  - IsAlone
- Análise exploratória com gráficos e correlação;
- Separação dos dados em treino e teste;
- Treinamento de modelo de Machine Learning;
- Avaliação utilizando métricas de classificação;
- Geração de previsões para o dataset de teste.

<br>

**Modelo Aplicado.**

- **Regressão Logística**

A Regressão Logística é um modelo amplamente utilizado em problemas de classificação binária, sendo ideal para prever eventos com dois resultados possíveis, como sobrevivência ou não sobrevivência.

Além disso, o modelo permite interpretar o impacto de cada variável na probabilidade do evento ocorrer.

<br>

**Avaliação do Modelo.**

O desempenho do modelo foi avaliado utilizando:

- Accuracy
- Matriz de Confusão
- Classification Report
- Precision
- Recall
- F1-Score

O modelo alcançou aproximadamente:

79.89% de acurácia

Isso significa que o modelo conseguiu prever corretamente cerca de 8 em cada 10 passageiros.

<br>

**Principais Fatores que Influenciam a Sobrevivência.**

A análise do modelo identificou alguns fatores importantes:

- Sexo do passageiro;
- Classe do passageiro (Pclass);
- Idade;
- Tarifa paga (Fare);
- Tamanho da família (FamilySize).

Essas variáveis tiveram influência significativa na probabilidade de sobrevivência.

<br>

**Insights Encontrados.**

- Mulheres apresentaram maior taxa de sobrevivência;
- Passageiros da 1ª classe tiveram maiores chances de sobreviver;
- Crianças tiveram prioridade durante o resgate;
- Passageiros viajando sozinhos tiveram menor probabilidade de sobrevivência;
- Passageiros que pagaram tarifas mais altas tiveram maiores chances de sobreviver.

Esses padrões refletem fatores sociais e estruturais presentes no contexto do desastre.

<br>

**Tecnologias Utilizadas.**

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

<br>

**Estrutura do Repositório.**

📦 Titanic-Survival-Prediction

- 📓 titanic_machine_learning.ipynb  
- 📄 README.md  
- 📄 submission.csv  

<br>

**Acesso ao Projeto**

- 📓 Notebook: https://github.com/LarisSanto/Titanic_previs-o.git
- 📎 Google Colab: https://colab.research.google.com/drive/1VcwpurftFNH9a6g-cj9ik-61Flu66G8n?usp=sharing

<br>


## 👩🏽 Sobre Mim

Sou Larissa dos Santos Silva, estudante da Universidade Anhembi Morumbi e do Programa ONE (Oracle + Alura).  

Aqui compartilho os principais projetos que desenvolvi durante minha formação na área de Dados.

Este projeto faz parte do meu processo de aprendizado e desenvolvimento em Data Science e Machine Learning.

Estou sempre aberta a sugestões, feedbacks e troca de conhecimentos!

<br>

### 📫 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil%20Profissional-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/seu-perfil)

www.linkedin.com/in/laris-santos

https://unique-onion-409.notion.site/Ol-meu-nome-Larissa-dos-Santos-1ffae8705fee800499d2fd44643ebcf5?source=copy_link

✉️ larissa.santos.silva9902@gmail.com


---

<p align="center">Feito com 🖤 por Larissa dos Santos Silva</p>

<!-- Capa animada inferior -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=2F2F2F&height=120&section=footer" alt="Capa animada inferior" width="1000" />
</p>
