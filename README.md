# Modelo_Previsao_Transacoes


<p align="center">
  <img src = './img01.png' width = '50%'>
</p>

## Descrição do Projeto

No Santander, nossa missão é ajudar as pessoas e os negócios a prosperar. Estamos sempre procurando maneiras de ajudar nossos clientes a entender sua saúde financeira e identificar quais produtos e serviços podem ajudá-los a atingir suas metas financeiras.

Nossa equipe de ciência de dados está continuamente desafiando nossos algoritmos de aprendizado de máquina, trabalhando com a comunidade global de ciência de dados para garantir que possamos identificar com mais precisão novas maneiras de resolver nosso desafio mais comum, problemas de classificação binária, como: um cliente está satisfeito? Um cliente comprará este produto? Um cliente pode pagar este empréstimo?

Neste desafio, convidamos os Kagglers a nos ajudar a identificar quais clientes farão uma transação específica no futuro, independentemente do valor em dinheiro transacionado. Os dados fornecidos para esta competição têm a mesma estrutura dos dados reais que temos disponíveis para resolver este problema.

Este projeto tem o intuito de ser um Modelo de Machine Learning para prever a insatisfação dos Clientes. A coluna ‘TARGET’ é a variável resposta. Ela é igual a 1 para clientes insatisfeitos e igual a 0 para clientes satisfeitos. Duas bases são dadas, uma para treino e uma para avaliação. Três são as tarefas a serem realizadas.

a) Um falso positivo ocorre quando classificamos um cliente como insatisfeito, mas ela não se comporta como tal. Neste caso, o custo de preparar e executar uma ação de retenção é um valor fixo de R$ 10 por cliente. Nada é ganho pois a ação de retenção não é capaz de mudar o comportamento do cliente. Um falso negativo ocorre quando um cliente é previsto como satisfeito, mas na verdade ele estava insatisfeito. Neste caso, nenhum dinheiro foi gasto e nada foi ganho. Um verdadeiro positivo é um cliente que estava insatisfeito e foi alvo de uma ação de retenção. O benefício neste caso é o lucro da ação (R$ 100) menos os custos relacionados à ação de retenção (R$ 10). Por fim, um verdadeiro negativo é um cliente insatisfeito e que não é alvo de nenhuma ação. O benefício neste caso é zero, isto é, nenhum custo, mas nenhum lucro. A primeira tarefa deste case é maximizar o lucro esperado por cliente considerando o contexto descrito no parágrafo acima.

b) A segunda tarefa consiste em dar uma nota de 1 a 5 para cada cliente da base teste, respeitando a variável ‘TARGET’, isto é, o seu nível de satisfação, sendo 1 o mais insatisfeito e 5 o mais satisfeito. Ao dar essa nota deve-se ter em mente que somente os clientes com nota 1 serão alvos de uma ação de retenção e que o objetivo dessa ação é maximizar o lucro esperado por cliente (usando os mesmos valores da primeira questão).

c) Todo conjunto de dados é passível de ser dividido em grupos coesos, conhecidos como agrupamentos naturais. A terceira tarefa é encontrar os três grupos naturais que possuem os maiores lucros esperados por cliente (usando os mesmos valores da
primeira questão).

## Fundamentação Teórica

- [x] Fundamentos de GIT
- [x] SQL
- [x] Python
- [x] Análise de Dados 
- [x] Técnicas de Machine Learning
- [x] Modelagem Matemática e Estatística

## Status do Projeto

<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

## Referências

[KAGGLE](https://www.kaggle.com/competitions/santander-customer-transaction-prediction)
