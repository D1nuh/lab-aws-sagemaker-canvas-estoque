# Previsão de estoque com SageMaker Canvas

Olá pessoal, me chamo Luiz Hilario e esse é meu modelo de ML via AWS, o desafio foi proposto pela DIO uma plataforma bem completa para desenvolvimento de habilidades em TI, o Bootcamp do desafio se chama ```ML para iniciantes com a AWS```, propôs desafios interresante, confira esse comigo.

## Base de dados

A base de dados foi criada por mim mesmo, é uma base de dados bem grande por ter registrada cada compra de produtos, também uma base de dados fictícia em CSV usada para fins de analise e estudos, aqui esta os dados principais dela.

|Id do produto|Nome do Produto|Categoria|Preço Atual|Vendas diárias|Vendas mensais|Vendas Anuais|
|-------|-------|--------|--------|--------|-------|-------|
|1|Smartphone |Eletrônicos|R$ 1499.00|10|50|200|
|2|Laptop Gamer|Eletrônicos|R$ 2699.00|8|30|90|
|3|Tênis Esportivo|Moda|R$ 299.00|500|600|1200|
|4|Câmera Fotografia|Fotografia|R$ 1199.00|10|80|200|
|5|Panela Elétrica|Cozinha|R$ 99.00|120|600|1000|


## Objetivos principais
• Coleta de insights dos sobre as vendas

• Previsões e aprimoramento de preço dos produtos 

• Melhora na indentificação de agentes que influenciam as vendas

• indentificar futuros crescimentos ou quedas nas demandas dos produtos

## Tecnologias usadas
• AWS (Amazon Web Services) - Software de aplicação.

• Arquivo CSV (Comma-separated values) - Formato do banco de dados.

• ChatGpt - Assistência no banco de dados

## Metricas do modelo
Obtive os seguintes resultados nas metricas de desempenho do modelo:

Avg.wQL - 0.668

RMSE - 6.553

MASE - 0.345

WAPE - 0.782

MASE - 0.147

## Observações e Resultados

Ao finalizar o processo de treinamento do sistema de ML analisei os seguintes Insight:

• Ao observar a taxa em porcentagem de crescimento, os medidores de P10, P50 e P90 estavam paralelos, o que ja esperava, pois, não teve taxa de variação de médias de vendas.

• Outro insight valioso foi a taxa de prejuízo anual que considerando os Feriodos do ano no Brasil (11 a 13 dias), indicou um prejuízo de: 

• P10(Minimo) R$ 2.309.472,00

• P50(média) R$ 2.510.254.00

• P90(Maximo)R$ 2.729.176,00

Preço obrido ao analisar o preço que iria ser obtido ao desconsidera os feriados com o cenário que se considera.

## Feedback

O modelo de ML da AWS É um mecanismo muito prático e muito moderno para análise e desenvolvimento de insights para empresas, é um modelo no-code te espero trabalhar mais no futuro, pois, pessoalmente, eu domino mais da área de Front-End e API e essa ferramenta é essencial para melhoras as minhas análises de dados

```Luiz Hilario - Licença MIT```



