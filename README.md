# Desafio Modelagem & Análise 📊



## Índice

**[1. Respostas do Desafio de Modelagem & Análises ](#heading--1)**
* [1.1. Resposta do Primeiro Desafio](#heading--1-1)

* [1.2. Resposta e Considerações do Segundo ](#heading--1-2)

**[2. Referências Bibliográficas](#heading--2)**
 
1.1  Como comparar municípios? (descritiva)
 
Imagine que um gestor público entra hoje no Farol e quer ter a possibilidade de comparar seu município com outros municípios de seu interesse. (a) Como você selecionaria municípios para comparação? Descreva quais características você selecionaria para definir municípios semelhantes. (b) Descreva 2 (duas) análises ou visualizações que você montaria para comparar a situação entre esses municípios.


* Responda esta pergunta de forma descritiva em seu README.

a) Como você selecionaria municípios para comparação? Descreva quais características você selecionaria para definir municípios semelhantes.
 
 
Para o gestor público comparar o seu município a outros , é necessário compreender qual o seu interesse, se ele quer comparar com uma cidade similar a dele ou com outra que não é. Assim sendo, caso for similar selecionaria municípios que apresentam características demográficas e socioeconômicas parecidas.
 
As características que selecionaria para definir municípios semelhantes seriam densidade demográfica, índice de desenvolvimento humano municipal (IDHM), cidades que aderiram ou não ao Lockdown, migração sazonal de pessoas, capacidade hospitalar e infraestrutura que permita contato exógeno(portos e aeroportos).
 
A variável de densidade demográfica possui enorme relevância, tendo em vista que  podem ser cidades pequenas, médias ou grandes, podendo ser mais ou menos povoada.
 
Uma variável essencial é verificar se apresentam IDHM similar, uma vez que as características sócio-econômicas serão parecidas entre eles.
 
Embora, este índice inclua a parte econômica e portanto a capacidade hospitalar de cada município podem ser similares. Contudo, ainda assim, é importante verificar se apresentam a mesma, visto que é uma análise que abarca variáveis hospitalares.
 
Outra variável importante seria se apresentam migração sazonal de pessoas semelhantes, visto que se forem diferentes a demanda de um hospital será maior, uma vez que a probabilidade de ter maior números de casos de COVID é alta.
 
Além disso, verificar  a presença de municípios com aeroportos e/ou portos, uma vez que o contato exógeno pode alterar o número de casos de COVID.
 
Ademais, é interessante verificar se essas cidades aderiram ou não ao lockdown, pois caso uma aderiu e a outra não, poderiam apresentar características distintas.
 
 
Caso não seja similar é possível efetuar a tentativa de padronização das variáveis citadas acima de forma que se torne mais fidedigno a comparação, podendo analisar com uma melhor acurácia.
 
b) Descreva 2 (duas) análises ou visualizações que você montaria para comparar a situação entre esses municípios.


Duas análises ou visualizações que montaria para comparar a situação entre esses municípios seria um gráfico que ilustra as mortes confirmadas por COVID no ano de 2020.
 
Dessa forma, ao visualizar este delta de mortalidade comparando com municípios similares, se o nível de mortalidade está parecido podemos hipotetizar que as medidas sócio-políticas foram seguidas de forma semelhante, se houver diferenças podemos conjecturar que as políticas e medidas foram feitas de forma desigual 
 
Outra análise que faria seria: uma análise de números de casos de COVID acumulados entre esses municípios pois, poderia verificar a aceleração da contaminação da doença em cada município. Assim, pode-se hipotetizar qual munícipio está seguindo as políticas e medidas de segurança. 
 
Além disso, poderia ser realizada uma análise entre esses dois gráficos e verificar se, embora, um município apresente mais casos de COVID e no entanto tem menor número de mortes, pode-se especular que a  capacidade hospitalar e a qualidade de saúde é melhor no município em questão


1.2. Como você montaria um dashboard para a gestão municipal? (Jupyter notebook)
Um(a) gestor(a) público(a) conta com você para construir um dashboard de monitoramento que mostre a situação de seu município. Quais informações devem ser acompanhadas, e como você as apresentaria? Elabore um conjunto análises e visualizações com as principais informações para esse(a) gestor(a) de 1 (um) município a sua escolha, utilizando os dados do FarolCovid e Saúde em Ordem (ambos em nossa ferramenta ou use nossa API se preferir).


* Implemente este desafio num Jupyter notebook em seu repositório privado.

*  Seu notebook deve conter no máximo 5 visualizações.

*  Todos os gráficos devem conter legenda e título. Junto a ele deve conter uma breve explicação da análise apresentada em Markdown.


* Requisítos

Instalar Bibliotecas
 
pip install plotly
 
pip install cufflinks


*  Visualização do Modelo de Dashboard criado no Power BI


Resolvi comparar os gráficos que fiz no Jupyter Notebook com os que criei na ferramenta do Power BI coloco como adicional
 
 
![dashb](https://user-images.githubusercontent.com/61422039/91675692-9e3e2400-eb13-11ea-8361-8ba7a392981c.png)
 
 
 
 
2. Referências Bibliográficas


https://farolcovid.coronacidades.org/


https://covid.saude.gov.br/ - planilha de dados eu tirei do arquivo disponibilizado


https://plotly.com/


