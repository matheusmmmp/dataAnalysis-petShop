<h1 align="center">
   📱 <a href="#"> Estudo de Modelos de Classificação de um DataSet de Telecomunicações </a>
</h1>

<h3 align="center">
   Modelagem de dados em um cenário de uma empresa de Telecomunicações utilizando três tipos de modelo: o KNN, o Bernoulli Naive Bayes, as Árvores de decisão
</h3>

<h4 align="center"> 
	 Status: Concluído🚀
</h4>
 
<p align="center">
 <a href="#sobre-o-projeto">Sobre</a> •
 <a href="#funcionalidades">Funcionalidades</a> •
 <a href="#conclusão">Conclusão</a> •
 <a href="#tecnologias">Tecnologias</a> • 
 <a href="#licença">Licença</a>
</p>


## ✎Sobre o projeto

Este notebook é uma forma de praticar meus conhecimentos em ciência de dados, principalmente com a **biblioteca de Machine Learning do SKLearn**. Ele nos orienta em um fluxo de trabalho para resolver um problema em um cenário de uma empresa de telecomunicações, onde atraves de algoritmos de classificação, sera possivel comparar e medir quais modelos serao mais uteis para o problema proposto.

As informações que serão adquiridas através da analise dos dados são:
  - **Faturamento**: Entender o Faturamento total e também mensal do estabelecimento;
  - **Filtro**: Visualizar os dados e filtra-los através das marcas de produtos;
  - **Visualização**: Permitir visualizar quais produtos estão presentes em estoque e até mesmo visualizar o faturamento através de cada produto ou de todos.
  - **Distribuição de Dados**: Permitir identificar o interesse de determinado gênero para um produto.
  - **Análise de Tendência**: Através dos dados, permitir uma estratégia para gerir uma nova filial.  

O principal objetivo deste notebook é servir como um guia de fluxo de trabalho passo a passo, permitindo que eu mesmo revise este caderno e sirva de estudo para casos futuros.

Este dashboard foi desenvolvido dentro do ambiente Power BI.

---

## ⚙Funcionalidades

- [x]  Pré-Processamento;
- [x]  Modelo K-nearest neighbors (KNN);
- [x]  Modelo Bernoulli Naive Bayes;
- [x]  Modelo de Arvore de Decisão;
- [x]  Validação dos modelos;

---

## 🔬Conclusão

Dentre os modelos estudados, vale evidenciar que todos se destacaram em métrica em particular. Dentre os destaques estão:

  - **Precisão**: O melhor modelo para precisão foi a árvore de decisão com 79,73%;
  - **Acurácia**: O melhor modelo para acurácia foi o KNN com 81,48%;
  - **Recall**: O melhor modelo para Recall foi o Bernoulli com 84,24%;
  
 Devido a natureza do problema proposto, a melhor métrica para classificação dos clientes é a **precisão**. Pois permite medir quantos valores positivos foram previstos de forma correta com um todo no nosso modelo, sem ser penalizado pela classificaçãos de valores negativos; Então o modelo escolhido para o problema será a  **Árvore de decisão**.

---

## 🛠Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

-   [Python](https://www.python.org/)
-   [SKLearn](https://scikit-learn.org/stable/user_guide.html)
-   [Seaborn](https://seaborn.pydata.org)
-   [KNN](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
-   [BernoulliNB](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.BernoulliNB.html)
-   [DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)

---

## 📝Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Matheus Pereira 👋🏽 [Entre em contato!](www.linkedin.com/in/matheus-de-medeiros-pereira-52b245140)
