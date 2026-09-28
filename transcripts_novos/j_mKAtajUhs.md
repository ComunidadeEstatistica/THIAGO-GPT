# Análise de Sentimento Twitter - Candidatos a Presidência - Parte 2

- **URL:** https://www.youtube.com/watch?v=j_mKAtajUhs
- **ID:** j_mKAtajUhs

## Transcrição

ea segunda nos na a polaridade ou
sentimento de cada um dos tweets ser
positivo neutro ou negativo
após isso vamos criar um mandato à
frente contando o texto do tweet
a emoção que melhor classificou acredito
it ea qualidade que melhor pois ficou
aflito int e se houver ameaça vamos
classificá los como essa podemos votar
então um gráfico para ver a nossa
polaridade vamos fazer um estourando nas
polar inácia obtidas para substituir
utilizando o pacote totti chile
temos então 1.298 twitts negativos 288
neutros e 7825 twitts positivos
vamos então ver as emoções relacionadas
às tuítes sendo que aquelas que não
identificar estarão com n ha
vamos criar então gráfico de pizza
utilizando g cot
só desejamos a parte que foi reconhecida
toda essa área cinza é contido dna e
vemos aqui que a maioria dos tweets
classificados têm uma emoção de raiva e
alguns de medo alguns de alegria
tristeza e bem pouco de surpresa são as
classificações aqui obtidas
vamos então utilizar a biblioteca
adversa para fazer um grupo bae das
polaridades e agrupá las em três linhas
né positiva negativa e neutra
vamos então em cima do resultado remover
stop works
isto é aquelas palavras do português que
não tem muito sentido né
executámos esta parte
podemos ver quais são agora quais são
essas palavras que não nos interessa
temos aqui uma relação de 200 e poucas
palavras
vamos removê las dos nossos tweets
ok como todo o teste online
vamos fazer então a criação um corpos
com o nosso texto em cima dele e vamos
criar a nossa matriz e termos do
documento
vamos colocar então o nome dos termos de
acordo com as polaridades
classificando-as positivo negativo e
neutro
feito isso podemos que a nossa o
workabout com as palavras que mais
aparecem são mencionados nos twitters e
sendo que essas palavras como foram
classificadas se o perdesse um ato eles
positivos atos negativos
o ato its neutros
executando do pacote wormbald temos aqui
então nosso orgulho cloud com essas
palavras em vermelho alaranjado são as
atitudes classificados como neutras
assim verde dos twitts negativos e as
azuis dos tweets positivos
ok foi esse o nosso trabalho utilizando
o pacote recentemente
vamos para o pacote lexicon pt ele tem 2
data 7
vamos carregar los vamos novembro então
há dois na frente que vamos utilizar
temos aqui o complexo com um versão 3.0
vamos na str paralelas variáveis
temos hotel classificado inclusive
emoticons e tem o tipo né
a qualidade e se foi feita manualmente
ou automaticamente vamos ver aqui a
nossas tabelas de freqüência temos
adjetivos emoticon os hashtags verbos
verbos aditivados maps adverbiais nevos
com proposições e verbos não por
posicionar mais nossas popularidades
temos menos um para negativo 14.000 0
para neutros e um para positivos temos
aqui 28 mil palavras que foram
classificados automaticamente enquanto
que 4163 palavras foram classificadas
manualmente por nenhum extras
então este é o dicionário oferecido pelo
o pelé zico vamos utilizá-lo batendo com
as palavras que nós temos no nosso
twitter
primeiro de tudo utilizando nossa nota
frame de tweets
vamos contar diversas criar uma coluna à
índia do tweet como a linha de cada
tweet
temos 9411
para o final
temos aqui então esta coluna com um
tweet
haidê criado rock agora desmembrar cada
tweet
em uma palavra então se o tweed tem dez
palavras vamos criar dez linhas
referentes a crédito int ok aqui 237 mil
linhas né criadas 107 mil palavras
vamos listar aqui as 20 primeiras só
problemas aqui temos diferentes um
assunto e só e aqui as palavras
compostas nesse tweet
ok vamos fazer agora um estudo de
correlação de palavras
vamos tentar identificar palavras
correlacionados de dois em dois né
usando para mais essa função para
correlação vamos agrupar desde que essas
ligações têm mais do que 20 meses né e
criar então nossa variável que tem
correlação temos aqui então um exemplo
das correlações por exemplo ofertar
governança ofertar secretários e assim
por diante
tem uma correlação de algumas outras
palavras aqui que tem algumas
correlações com os seus coeficientes
vamos filtrar apenas aqueles que tenham
correlação um coeficiente maior do que
pontos 50 e jogar um gráfico do
geografia essas correlações do twitter
criamos aqui então várias palavras né
que aparecem combinados nos tweets
então estamos procurando alguma teoria
de conspiração podemos utilizar essa
ferramenta
aqui por exemplo deve ser um assunto
muito recorrente e aqui também temos
outros
assunto recorrente nos tweets
temos algumas palavras que aparecem
juntas como ficha limpa
os nomes dos candidatos e outros termos
como federal estadual deputado estão
relacionadas às eleições
ok