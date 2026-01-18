#  Perguntas de Negócio e 🛒 Market Basket Analysis (MBA) 

## 📌 Visão Geral do Projeto

Este projeto tem como objetivo aplicar **Market Basket Analysis (MBA)** utilizando o algoritmo **Apriori** em Python, com base em dados reais de compras de um supermercado americano. Além da análise de associação entre produtos, o projeto também responde **perguntas de negócio estratégicas**, focadas em entender o comportamento do consumidor e identificar **produtos, departamentos e corredores mais populares**.

Embora parte das análises não esteja diretamente ligada ao Market Basket Analysis, elas complementam o estudo ao fornecer **insights exploratórios essenciais** para decisões de negócio.

---

## 🎯 Objetivos

* Identificar **padrões de compra** e produtos frequentemente adquiridos juntos
* Gerar **regras de associação** utilizando o algoritmo Apriori
* Calcular métricas como **support**, **confidence** e **lift**
* Analisar a popularidade de **produtos**, **departamentos** e **corredores**
* Responder perguntas de negócio relevantes para o varejo

---

## 🧠 Perguntas de Negócio Respondidas

O projeto inclui a resposta para perguntas como:

* Quais são os produtos mais vendidos?
* Quais departamentos possuem maior volume de pedidos?
* Quais corredores são mais populares?
* Quais produtos têm maior taxa de recompra?
* Quais departamentos concentram mais produtos frequentemente recomprados?

Essas análises ajudam a entender o comportamento do cliente, mesmo fora do escopo direto do MBA.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib / Seaborn**
* **Jupyter Notebook**

---

## 📊 Market Basket Analysis

A análise de Market Basket foi realizada utilizando o **algoritmo Apriori**, com os seguintes passos:

1. Preparação dos dados para aplicação do algoritmo
2. Devido ao tamanho do dataset foi utilizado apenas uma amostra de produtos
3. Extração de regras de associaçã
4. Visualização do support, confidence e lift

Exemplo de insight obtido:

> Clientes que compram *Produto A* têm alta probabilidade de comprar *Produto B* na mesma compra.

---

## 🚀 Resultados e Insights

* Identificação de **combinações frequentes de produtos**
* Insights úteis para **cross-sell** e **promoções conjuntas**
* Melhor entendimento da estrutura de vendas por departamento e corredor
* Base analítica sólida para decisões estratégicas no varejo
