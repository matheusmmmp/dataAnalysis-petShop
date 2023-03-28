<h1 align="center">
   📊 <a href="#"> Análise de Dados de PetShop através do Power BI </a>
</h1>

<h3 align="center">
  Desenvolvimento e Visualização de uma Dashboard de uma PetShop através do Power BI
</h3>

<h4 align="center"> 
	 Status: Concluído🚀
</h4>
 
<p align="center">
 <a href="#sobre-o-projeto">Sobre</a> •
 <a href="#estrutura-dos-dados">Dados</a> •
 <a href="#conclusão">Conclusão</a> •
 <a href="#tecnologias">Tecnologias</a> • 
 <a href="#licença">Licença</a>
</p>


## ✎Sobre o projeto

Este projeto é uma forma de praticar meus conhecimentos em ciência de dados, principalmente com parte de **Business Intelligence no Power BI**. Ele nos orienta em um fluxo de trabalho para resolver um problema em um cenário de uma empresa de petshop, onde através dos dados fornecidos pelo suposto cliente, será necessário sanar algumas dores requisitadas pelo mesmo, tais como:
  - **Faturamento**: Entender o Faturamento total e também mensal do estabelecimento;
  - **Filtro**: Visualizar os dados e filtra-los através das marcas de produtos;
  - **Visualização**: Permitir visualizar quais produtos estão presentes em estoque e até mesmo visualizar o faturamento através de cada produto ou de todos.
  - **Distribuição de Dados**: Permitir identificar o interesse de determinado gênero para um produto.
  - **Análise de Tendência**: Através dos dados, permitir uma estratégia para gerir uma nova filial.  

O principal objetivo deste projeto é servir como um guia de fluxo de trabalho passo a passo, permitindo que eu mesmo revise este caderno e sirva de estudo para casos futuros.

Este dashboard foi desenvolvido dentro do ambiente Power BI.

---

## ⚙Estrutura dos Dados
Os dados foram adquiridos através de 3 métodos diferentes. Os dados referentes aos processos de vendas em período anual estão dispostos em 3 documentos de extensão .xlsx. Para dados referentes a clientes, foram extraídos de um documento de extensão .txt e por fim, os dados referentes aos produtos foram adquiridos através de uma tabela online presente no seguinte link: [Tabela Produtos](https://docs.google.com/spreadsheets/d/e/2PACX-1vSi6zD0nOJDf4YVOBQVXuSpAwihl4i5H4vrv7PjM3y0l0M-oHOaWYRrVXrZ1o3TOUFNnzo3sSi9b0Pu/pubhtml) 

```
DataSets

  -Clientes/
    -ID Consumidor
    -Genero
    -Estado Civil
    -Bairro
    -Pets
    
  -Produtos/
    -ID Produto
    -Marca
    -Nome Produto
    -Url Img
    -Valor
    -Categoria
    
  -Vendas/
    -vendas_2018/
      -Transacao      	
      -ID Consumidor
      -ID Produto
      -Quantidade
      -Data de compra
      -Valor
    -vendas_2019/
      -Transacao
      -ID Consumidor
      -...
    -vendas_2020/
      -Transacao
      -ID Consumidor
      -...
      

```


---

## 🔬Conclusão

Através das estruturas de dados propostos, foi possível atender a todas as expectativas do exercício e assim gerar um Dashboard que permite visualizar e gerar um storytelling do comércio em questão.
O Dashboard pode ser acessado através desse link:  [Alura Petshop](https://app.powerbi.com/view?r=eyJrIjoiNzJkZGYwMDAtZWFiZi00OTcxLTg0ZWMtNDAxODcyOTcwMzE3IiwidCI6ImQwOTEwZmZkLThhMzctNGJkYi1iYTY1LTdkMmQwZWI1N2RlOSIsImMiOjR9)

E o projeto pode ser visualizado tanto em Desktop quanto em dispositivos móveis:
<h1 align="center">
  <img alt="Imagem Demonstrativa 1" title="#Img1" src="https://user-images.githubusercontent.com/33897566/228261270-aa052c98-04dc-42d7-ad09-4015a71124d3.PNG" style="width: 800px;" />
  <img alt="Imagem Demonstrativa 2" title="#Img2" src="https://user-images.githubusercontent.com/33897566/228261321-37d2a287-b544-4da2-aedd-c29308d02519.PNG" style="width: 380px;" />
</h1>

---

## 🛠Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

-   [Power BI](https://powerbi.microsoft.com/pt-br/)

---

## 📝Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Matheus Pereira 👋🏽 [Entre em contato!](www.linkedin.com/in/matheus-de-medeiros-pereira-52b245140)
