# Aula 2 - Machine learning - Introdução a Regressão Linear em Python

- **URL:** https://www.youtube.com/watch?v=H5Efih9wEfo
- **ID:** H5Efih9wEfo

## Transcrição

olá nessa aula
vamos aprender a aplicar de forma
prática o algoritmo the machine lane
regressão linear para s exemplo a gente
vai usar a regressão linear aplicado a
dados de mercado financeiro
o objetivo é criar um modelo que consiga
predizer o valor de fechamento de uma
ação
vamos treinar algoritmo e validar o
modelo então o pessoal o primeiro passo
é entender que os scripts aqui que a
gente vai utilizar essa alma são os
crimes que estão disponíveis no nosso
objetivo é só você clicar aqui e efetuar
o download
outra coisa é que os dados de preços né
no caso a gente vai usar dados de preço
das ações da preta da petrobras estão
também nunca te amo você consegue fazer
download dos dois dos dois arquivos ok
vamos em frente
as bibliotecas que a gente vai utilizar
são essas que já estão utilizando aqui
então são bibliotecas que a gente já
trabalhou por exemplo bandas netão
biblioteca a gente utilizou no curso né
a nós do texas novas aqui são saque
chillán e o próprio é o melhor técnico
utilizado para pilotar dados de mercado
de séries temporais financeiras
ok no mais a biblioteca martelotte livre
já é conhecida
ok e vamos em frente à biblioteca saque
thylane pessoal é a biblioteca que vamos
utilizar em todo o curso em escape to
the machine lane é uma biblioteca para
fazer é trabalhar com machine no pai do
rock
a biblioteca bem famosa seguindo o
primeiro passo é ler um arquivo de dados
né então aqui eu estou usando o panda
netão pb que é um apelido que eu dei
aqui pro meu pandas panda de um a um
eles né
eu criei vou usar a função wi fi csv e
vou passar aqui o arquivo csv contendo
os preços na ação da petrobras
ok executar
desculpa eu não executei aqui primeira
importação das bibliotecas executado
ontem por 12 mil lotéricas agora vou
executar agora o comando que é porque
não comprou meu eu sp de votar o quanto
valeu arquivo novamente prefeito já leu
o arquivo em disco e agora eu vou
transformar a meio a minha coluna de
leite para um tipo desde time porque
essa coluna de ti como eles arquivo pan
de dente com ela como coluna do tipo
stream ou converter esses valores e
agora a gente vai visualizar dentro do
prédio como coloquei a casa
os dados na variável deitar 7 usei aqui
o meu deitar 7 agora é um em bandas de
frevo mulher como a gente aprendeu na
aula de pano muito tranquilo então que o
pessoal usa um método hit para
visualizar a 5 cinco primeiras linhas o
meu data 7 então que eu tenho aqui nem
eu tenho data 7 de preços é que contém a
data néon 11 do quadro 2017
o valor de abertura da ação 1497 o valor
máximo da ação no dia 14 99
o valor mínimo da ação no dia 14 55 e o
valor de fechamento da ação 14.568 né e
o valor de volume
o volume negociado na ação no dia que
fez e falou que o ok então eu tenho isso
no período de 2010 até 2007 ou seja tem
sete anos de preços das ações da
petrobras diários
ok então que eu tenho dados 11 de 14 10
do 47 do 46 e sim por diante o que a
gente vê os os valores aqui vou usar a
função tenho que vai pegar os últimos
valores é do dj set
vamos executar aquilo que a gente
consegue ver que o oito de 12 mil idéias
né 4 do mundo de 2010 então seja de 2010
até 2007 o valor do preço que o valor do
prefeitura nessa data 8 de um 2010 0 37
16 37 39 e assim por diante o ok então a
gente tem uns dados no espelho
mais à frente a gente vai pilotar esses
dados a gente vai visualizar de forma
gráfica como é que estão a distribuição
desses dados
e esse período temporal de preços não é
perfeito vamos lá
outra coisa que vou fazer pessoal é que
há uma coluna chamada variation que nada
mais é que a variação entre o preço de
abertura eo preço de fechamento o que
seria essa variação a diferença seria a
diferença do preço de abertura - o preço
de fechamento eu tenho avaliação do dia
então seja se a ação abriu há um ballo
por exemplo 16 50 e fechou a 1660 ela
teve uma variação de zero ponto 10 de 10
centavos ok então muito simples é essa
coluna que eu vou criar muito tranquilo
então essa coluna recebe beta 7
variation que a coluna que eu vou criar
agora é se é deitar 7.1 close ou seja
com lobos a minha coluna minha variável
de fechamento de preço de fechamento
foto sam deita 7 opinião seja pega o
preço de fechamento - o preço de
abertura de todas as linhas
quem executar eu tenho valor de
variation agora vou dar vou usar o
método rio novamente a gente visualizar
os dados pronto aqui eu tenho variação
de menos ponto zero ponto 29 na no dia
11 de 14 uma variação de zero ponto 0 40
ponto 09 10 09 - 0.48 e assim por diante
para todas as linhas dominantes set eu
tenho avaliação da do fechamento
- a abertura do dia o rock isso é
interessante pra gente visualizar é o
percentual de alteração do dia tá é
quando a gente fala assim a ação e vão à
valorização de de 1% e 2%
a gente pode fazer esse cálculo através
dessa coluna de variação ok tranquilo
outra coisa que eu vou utilizar agora a
gente vai começar a partir de
visualização dos dados antes de entrar
no algoritmo de marchi lana de entrada
regressão linear
eu acho interessante a gente visualizar
os dados né a gente tá fazendo ciência
dos dados então importa
muita gente visualiza esses dados ao
longo do tempo então aqui pessoal eu vou
pilotar o valor dos preços no período
analisado no período de 2010 a 2017
para isso vou utilizar pai pilote que a
biblioteca para aprontar dados temporais
financeiros porque eu falei em cima é
essa biblioteca é que a gente importou
lote ponto gráfico beleza
vamos fazer a execução então como é que
essa biblioteca funciona
eu passei aqui o que é uma variável
chamado x 1 paranavaí y essa variável x
1 recebe o conteúdo direita 7 ponto de
ti ou seja a coluna de data ea variável
e y un seria meu eixo 1 x 68 y recebe o
valor de fechamento todos os valores que
eu chamei essa função go pontos cap que
passa o valor de x um valor de y ou seja
quer pilotar uma dispersão desses dados
ao longo do tempo e define que o que o
minhas configurações de layout vão
seguir algumas configurações simples por
exemplo faixa de valores aqui data vai
ser 11 2010 até hoje o quadro de 2007 ou
seja no eixo x vou ter meus preços é e
no eixo itron eu vou ter o valor
desculpa no meio e chukchis eu tenho
datas a essa faixa que de 1 10 11 que
2010 até 11 do quarto e 2017 eo eixo y e
tem um valor das ações o preço de
fechamento neste período
ok em seguida eu chamei coloquei isso
tudo bem objeto mato fique que recebem
um gol ponto figura que o método de
figura
passei para ele os dados que definir
aqui no layout com definir aqui ok
confrontar a gente ver como é que fica
esse gráfico veja que interessante
pessoal e ligará ele pilotou pra mim
aqui os dados temporais é tão no eixo x
eu tenho que os meus dados de data em
2011 2012 2013 até 2017 eo eixo y é o
valor de fechamento
então perceba que esta biblioteca a
biblioteca interativa de forma que a
gente consegue passar o mouse aqui ó
sobre sobre as linhas sobre a linha no
tempo a gente consegue ver o valor de
fechamento então o que é possível
perceber que em 2010 a janeiro de 2010 a
ação valia 36 por 36 de ver claramente
que essa ação vem caindo ao longo dos
anos né
ao longo dos tempos e valem cada vez
menos até chegar aqui num valor menor
que ela já que ela é o valor dela menor
foi 4.20 alguma coisa né
e hoje é hoje não né no período março de
2017 ela para ela estava nesse valor de
1494
então essa é a nossa nosso de 77 nossos
dados de preços que a gente tem que vai
que vão ser os dados que a gente vai
usar para treinar nossa regressão linear
ok dados de 2000 e 2010 até 2017
vamos em frente não é só a primeira
visualização dos preços ao longo dos
anos o que agora vamos em aprender a
própria os kindles que seria os 500 e os
kindles seriam os gráficos informar de
barras né então quando a gente está
trabalhando com dados financeiros é de
ações a gente utiliza quem dos xix né
que são os gráficos informado de velas
né
onde a gente tem um eixo 11 e superior e
um eixo inferior que tem um corpo dessa
dela então quando a gente provou
fotografa vocês vão ver como como é
simples
essa representação por que então o que
pra não ter que alterar meu dj set e
definir outra vai arrumar deitar 72 que
recebem 17 pontos
ou seja quer as sete primeiras linhas
apenas para facilitar e passei para a
função go ponto que investiga essa
função o gol é a minha biblioteca potter
e nem que eu mostrei anteriormente eo
meio e ela contém um método chamado quem
deus chip que é um método que vai
procurar os kindles pra mim né
os gráficos de vela oq esse método quem
não recebe um valor x nec é o valor o
valor de x vai ser assim a data né
vai ser um período de tempo e vou passar
o valor de abertura open recebe a deitar
7.1 pe
ray recebe 17 pontos hi low e clubes e
assim por diante então eu passei o valor
de abertura máxima mínima e fechamento
do dia
ok pra dentro do meu da minha e do
método google.com investique seguida eu
coloquei isso tudo em data perfeita
por fim eu pilotei data né definir um
nome de arquivo que caso queira fazer
download com executar que ele girou pra
mim olha que interessante
agora tenho gráficos do tipo quem do
stick os gráficos do tipo que a gente
chique são gráficos do tipo vela pessoal
onde esse corpo superior que são as
vênus
essas linhas que são os eixos onde tem o
valor máximo 15 16 o valor
o valor de abertura um valor que a ação
fechou o valor máximo o valor mínimo da
ação
ok então os gráficos de quem não são
utilizados no mercado para avaliação de
de preços né
a estratégia de análise técnica e assim
por diante
então com essa biblioteca é bem
interessante a gente consegue pilotar os
kindles né
assim como os analistas de mercado
financeiro conseguem visualizar os dados
de preço né e trabalhar com isso a gente
também consegue pilotar da mesma forma
que então que a ação abril caso 61
fechou quatro pontos e tenta ao máximo
de papo 14.191 a mínima de 14 pontos fez
o que bem tranquila é esse são que nos
desse dos sete últimos dias né
sete últimos dias dando os preços da
soja
agora eu vou pilotar para ficar
a gente tem outra visualização os
câmbios os últimos seis meses
ok quem nada mais é que a mesma mesmo
código a diferença aqui é que eu passo
que eu peguei 180 das 180 preços é ou
seja nos últimos 180 preços do meio
dados do meu do meu direita freitas 7
coloquei tudo aqui dentro de 272
executar o mesmo código anterior
diferença só a quantidade de dados
vamos ver olha que interessam
agora eu consertei quase aquela
representação né
ao longo dos anos e agora ao longo de
seis meses mas são kindles tics plotados
durante seis meses
então a gente vê que essa biblioteca é
bem interessante né interativo a gente
consegue visualizar isso aqui
essa biblioteca importa é interessante
caso a gente queira salvar esse gráfico
online e assim por diante se você se
interessar mais por essa biblioteca
basta pesquisar e abril a biblioteca
própria
ok mercado financeiro essa biblioteca é
bem interessante eu consigo definir uma
faixa que menor na qual quer analisar é
dar um zoom aqui num determinado período
ok aqui eu tenho as informações de
período de dez dias informações de preso
outro recurso muito interessante é a
gente plantar a variação dos preços
nesse período então é eu posso pilotar
aqui é minha coluna variation aquela
coluna que eu criei anteriormente que
tem a variação do preço de abertura e
fechamento né pra gente ver a variação a
gente entender como é que se dá à
distribuidora que a nossa ação
ela vem só caindo né no período de 2010
a 2017 se a gente olhar a gente viu com
gráfico acima a gente percebeu que essa
ação vem caindo ao longo dos anos é que
é simples de entender diz porém nesses
sete anos essa ação teve 11 teve uma
variação muito alta então foi
simplesmente só caiu os né
ela só subiu ela teve um período de
queda e e subidas né
de forma que que tem oscilação muito
grande nos preços nesse período
então que vou pilotar o gráfico de
variação ea gente vai entender
veja o pessoal que no período de 2010 a
2017 a gente teve uma oscilação de na
pesca da ação né não os preços né
ok então que eu pilotei no eixo x a
coluna data e deixo isso a coluna
variation netão olha só a variação foi
muito alta em ação
eu bem aleatórios preços aqui ok
tranquilo
outro recurso é agente pilotar com
relação de fitness ea classe qual seria
a classe a classe é nosso preço de
fechamento e as features talvez seria
mas nossos pés de abertura o preço de
mim o preço de máximo
o objetivo aqui o objetivo aqui é tentar
identificar se há uma correlação entre o
preço de abertura e o preço de
fechamento ou se há alguma relação entre
o preço da máxima eo prêmio fechamento e
assim por diante
ok então vamos botar esses gráficos aqui
para entender isso melhor do que eu fiz
aqui foi definir os variados chamou uma
variável chamado trem que nada mais é
que a cópia do meu jeito a 7 com todos
os dados porque eu fiz isso porque mais
à frente eu quero dividir os dados de
treino e os dados de teste então já
define sua tarefa treino que para ficar
mais simples
ok agora eu vou pilotar foi executado
aqui né meu gráficos essa variável
vou pilotar agora a dispersão entre o
preço de abertura open quem o fechamento
nos últimos 100 dias porque a gente pro
tal valor todo né os dados inteiro a
gente vai ver que não é possível ter
essa visualização gráfico vai
redirecionar na nossa tela aqui e vou
executar nada mais é que estou usando a
biblioteca martelotte livre é bem
simples e um gráfico do tipo de
expressão então passa é que o eixo x
seria usado na abertura o eixo y da de
fechamento é nos últimos 100 dias chamei
o meu método escape x e y define uma
curva que coloquei o valor de bebê então
e chukchis label recebe vai receber
esses têm que prestar abertura e eixo y
lei vai receber o preço de fechamento o
que é bem tranqüilo e vou e por fim o
próprio ponto show essas configurações
aqui são para definir os eixos valores
máximos e mínimos e o alto esquerdo a
falso executar
vejo que eu tenho um gráfico bem simples
mas já me mostra uma coisa interessante
né
nos últimos 100 dias eu posso perceber
que o preço de abertura à medida que
aumentava a simples leitura e tinha que
ele tende a aumentar
o fechamento pode ser bem simples
representação que pode ser que nos
últimos 100 dias a ação só subiu né
o teve uma subida um período de subida
ok mas a gente poderia é interessante
esse gráfico de inspeção para entender
se há uma correlação inversa entre estas
duas variáveis
vamos executar esse mesmo código para as
outras variáveis né do nosso 17 para
entender se a van com relação à ue por
hora vou interromper esse vídeo aqui
para não ficar tão grande a nossa aula
vamos continuar na próxima aula
ok um grande abraço