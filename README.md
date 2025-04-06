# Análise de Dados de Varejo

## Acesso ao dados

Este é um projeto de análise dados de uma organização do setor varejista e o texto a seguir explica com mais detalhes a seu respeito.

Os dados utilizados podem ser obtidos em: https://www.kaggle.com/datasets/mmohaiminulislam/ecommerce-data-analysis/data

## Introdução

O setor de varejo é preponderante na geração de riqueza em todo mundo, além de desempenhar funções essenciais que incluem a distribuição de bens aos consumidores e a geração de empregos. Um exemplo bastante representativo desta importância é o Walmart, maior organização varejista do mundo, que emprega mais de dois milhões de pessoas, está presente em 20 países e sua receita, apenas no terceiro trimestre de 2024, foi de, aproximadamente, 170 bilhões de dólares.

Uma corporação com estes números, sem dúvida, depende de uma extensa e complexa rede de conexões e infraestrutura, e gera, com suas atividades diárias, uma consistente e variada gama de informações. Por esse motivo, em um mundo no qual as estratégias dependem diretamente da análise de dados, um negócio de tamanha proporção e relevância, sem dúvida, não pode ser diferente.

Definir com quais fornecedores trabalhar, onde será a nova loja da rede e como será a próxima campanha de marketing, por exemplo, são decisões comuns a serem tomadas no cotidiano do setor varejista. Para apoiar o processo decisório e sanar eventuais questões, é preciso definir quais recortes e combinações fazer, considerando a totalidade de dados coletados no decorrer do tempo.


## Objetivo 

O propósito deste projeto, além de sua função didática como ferramenta de aprendizado em análise de dados, foi explorar, por meio de algumas perguntas objetivas, alguns aspectos de uma empresa do setor varejista localizada em Bangladesh, a fim de obter alguns insights. Para este fim, foram mescladas seis tabelas com informações sobre clientes, lojas, transações bancárias, data e hora da compra, preços e produtos. Estes dados foram obtidos no repositório Kaggle e são fictícios.

## Solução

A partir da utilização do Jupyter Lab, empregando linguagem Python e comandos SQL, com o pacote SQLite3, o projeto foi desenvolvido em duas etapas: a de ETL (Extract, Transform, Load) e o EDA (Exploratory Data Analysis). 
No decorrer da fase de ETL foram carregados os arquivos .csv, salvando-os em dataframes Pandas e realizando as alterações necessárias. Neste momento, foi observado o formato dos dados, alterando-os quando preciso e incluída uma nova coluna, com dados de população, na tabela de localização das lojas. Em seguida, foi feita a conversão para tabelas do Database SQL. 
Em um segundo momento, já na fase de EDA, para melhor definir as análises e guiar a exploração dos dados, foram elaboradas 12 perguntas objetivas, apresentadas no corpo da análise e respondidas logo abaixo. Alguns recursos diagnósticos a serem destacados foram a aplicação da correlação de Pearson com gráfico de dispersão e linha de tendência, análise de série temporal e gráfico de Pareto. 

## Conclusões

Após concluir a análise da dados, as principais conclusões obtidas foram:

1.Os produtos a partir dos quais a organização mais fatura, não tem seu fornecimento centralizado em poucos fornecedores, o que traz maior segurança quanto ao abastecimento e faturamento;

2.Quando analisados, em conjunto, o faturamento por cidade, o faturamento percapita por cidade e o número de lojas, entende-se que é preciso averiguar com maior cuidado as razões que colocam Dhaka e Chittagong como os locais que mais faturam, mais tem lojas e que possuem os menores faturamentos percapita, dado que isso indica um potencial subexplorado do mercado destas cidades;

3.Houve, principalmente no mês de janeiro dos anos de 2014 e 2021, quedas excepcionais no faturamento e estes são citados como pontos de alerta, cujas motivações, para tanto, devem ser analisadas e internalizadas, a partir de medidas de prevenção e mitigação de riscos;

4.Dentre os destaques de faturamento, pode-se mencionar a cidade de Dhaka, como o local em que as lojas mais faturaram, os produtos Redbull, K Cups Daily Chef e K Cups Original Donut como os top 3 em faturamento, Bangladesh e Índia como os países que exportam os produtos de maior faturamento e o fornecedor DENIMACH LTD como o que mais forneceu produtos de maior faturamento.




