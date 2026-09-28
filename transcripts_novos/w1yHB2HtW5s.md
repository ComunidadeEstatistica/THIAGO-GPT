# Aula 02 – Trabalhando com as ações do IBOV através da BatchGetSymbols - Trading com Dados

- **URL:** https://www.youtube.com/watch?v=w1yHB2HtW5s
- **ID:** w1yHB2HtW5s

## Transcrição

bom então né Então vou mostrar para
vocês como que a gente pode trabalhar
com dados de várias ações de uma vez e o
que que é mais recomendado para nós para
quem tá começando bem Tem vários
indicadores índice aí de mercado
financeiro ao redor do mundo aumenta
esse vídeo esses Eles procuram de alguma
forma consolidar né através de uma
ponderação percentual por exemplo Eles
procuram consolidar o comportamento de
um mercado no Brasil a gente tem o
índice Bovespa que faz mais ou menos
isso com as nossas ações Então esse
Bovespa ele é composto pelas ações de
maior liquidez do Brasil na ele muda
periodicamente e pra gente trabalhar com
várias ações de uma vez eu acho a melhor
opção a gente começar trabalhando com a
composição do índice Bovespa Porque como
ela já contém as ações
as mais famosas mais negociadas do
Brasil facilita nossa vida também porque
a gente não vai ter que trabalhar com
ações que são poucos negociadas hoje
atualmente ações que não tem dado sabe
quem dados faltantes porque
eventualmente o por alguma razão não
teve ação não foi negociado no pregão as
ações que estão no Ibó elas não vão não
vão ter esse problema são justamente as
ações mais negociadas a biblioteca
aberta e símbolos ela tem uma função bem
bacana pessoal que ela traz a composição
mais atualizada do Ibovespa que a função
que eu vou mostrar para vocês aqui agora
é a função get e Body talks se executar
essa função aqui vamos tomar esse de
bofe mesmo executar vocês vão ver que
ela vai me trazer a composição mais
atualizada de boa então vamos aprender
bom então PC é bom que ela tá me
trazendo os stickers tá trazendo na
descrição que aquela empresa o tipo da
ação né seu urinária preferencial sair o
único quantidade de ações a porcentagem
né então no Ibope Qual que é a
participação percentual de cada um
desses papéis tá e a data de referência
daquela última composição devolve E aí
eu sugiro que a gente conversa
trabalhando na verdade com esse deitar
frame aqui já que o que a gente precisa
não já que tem a composição de boa
provavelmente vocês devem ter notado né
como eu falei antes que pra gente
importar os dados de ações com essa
biblioteca a gente precisa colocar um
s.a. aqui no código delas não dá pra
gente simplesmente trabalhar dessa forma
Então qual que é a minha sugestão a
gente vai ter que criar uma outra coluna
que Adicione um ponto s.a. aqueles secas
como que a gente pode fazer isso vem não
é a gente tem uma função bastante
conhecida que a Xuxa
o que ela permite juntar trem juntar
pedaços de texto Então o que é que eu
vou fazer aqui eu vou pegar essa coluna
como referência então a coluna pictures
Então vamos fazer embora ticket
e eu vou dizer para ele que eu quero
adicionar um ponto s.a. e eu quero
também que a separação dessas Strings
seja vazia não tem nada Ou seja aquele
junte o nome da ação com.sa e eu vou
chamar isso aqui pede uma nova coluna me
chamar de Bohr me Shaker s.a. por
exemplo Nossa vai se tornar uma nova
coluna com o nome da ação e um ponto
s.a. que a gente executar isso aqui
voltar a Playboy observa em que ele fez
isso que a gente precisava então vocês
têm aqui
e os nomes das ações com um ponto s.a.
no final Beleza então a gente já tem
aqui na já temos uma coluna já temos uma
descrição das ações que a gente quer
trazer e qual é a diferença aqui pessoal
é porque antes a gente pegou uma ação
específica e colocou dentro da Beth Beth
símbolos agora vocês vão notar que ao
invés de pegar uma ação específica eu
vou pegar um vetor contendo várias ações
ou aqui no nosso caso uma coluna contém
várias ações então ele vai te pegar esse
objeto a criação eu vou pegar esse
objeto aqui que a própria coluna que tem
várias ações nela eu vou substituir aqui
e aqui nesse caso não é dado de uma ação
né que é dados e Borges vamos chamar
assim de boa vi mesmo intervalo de datas
então todo jeito que a gente precisa
vamos executar isso aqui
se observa em que ele vai fazer o
download exatamente de todas as ações
que compõem o ibov Então até se vocês
têm curiosidade observem ali embaixo ele
tá baixando ação por ação né são 77
papéis ele tá baixando um por um tão
pouco em alguns conhecidos né cog na
Cosan
a CVC Cyrela enquanto ele baixa todos os
papéis
e vamos esperar um pouquinho
e vocês vão ver que a forma como ele vai
trazer esses dados vai ser novamente no
formato de lista da mesma forma que ele
trouxe aqui obviamente trabalhar com
lista não é tão
é intuitivo assim então o que é que eu
vou fazer eu já vou substituir isso
daqui aqui embaixo porque eu sei que ele
vai me trazer um formato de leite então
já vou deixar esse código pronto aqui
pra facilitar minha filha então como eu
falei tem uma lista aqui
e eu vou tirar uma pena de que eu
preciso que é o segundo elemento da
lista não é isso aqui debaixo o kicker
Eu e meu dado cyborg agora tem 82 mil
linhas então uma coisa interessante
observa em que Ele trouxe todos esses
dados não deita Femme só né pode não ser
muito prática trabalhar com isso porque
normalmente eu vou querer esse dados
separados certo não vou querer um deita
frame contendo todos os dados de todas
as ações né como é que a gente consegue
então manipular essa tabela de tal forma
que ela separe os dados oração para
começar agora para você a gente pode
usar função
o verde plena era do JK Power
nós vamos pegar aqui esse daí tá firme
que a gente tava usando da hora de boa
vem e aí eu vou falar para ele que eu
quero que ele se separe e se deitar
frame em vários outros deitar frame de
acordo com a coluna querer
Oi e aí eu vou criar uma função aqui
rápida
e onde nessa função
e ele vai separar as minhas de acordo
com o ativo de referência vocês vão ver
que o resultado que vai dar mãe
e já antecipo para vocês que isso daqui
vai dar uma lista de deitar frame uma
pessoa então vamos executar isso aqui
não vou chamar se quiser alguma coisa
você vai receber lagos de imóvel 2
é um ver estrutura observa em que
é uma coisa interessante tá pessoal a
vejam que eram 77 ações do Bob que ele
trouxe mais aqui na nossa lista Ele
trouxe 69 então a tendência isso ele não
trouxe tudo tá obviamente pode ter
alguma razão a eu acredito
particularmente aqui isso acontece
porque nem todas as ações estavam sendo
negociadas no período que a gente já
terminou como data de início então ele
tenta fazer ali a o encaixe para trazer
nem ações que de fato tiveram dados né
Tem dados naquele período inteiro que a
gente determinou então percebam que ele
trouxe uma lista com vários deita frame
ainda não está no formato que eu queria
porque também não é muito intuitivo a
gente ter uma lista gigantesca com
várias situações não é muito prático a
gente trabalhar com uma lista gigantesca
não é uma lista que contém aí 69 deitar
frente como vocês
e eu particularmente eu gosto de formato
bem específico eu gosto de um formato
onde eu tenho um dele tá frame cada
coluna representa o preço ajustado de
uma ação específica e cada linha
representa um pregão específico
representa um dia de negociação esse
particulamente ao é o estilo que eu
gosto de deitar frame de mercado
financeiro para trabalhar e aí eu vou
mostrar para você como a gente vai
chegar lá o que que interessante a gente
observar não é estrutura dessa lista
aqui que a gente obteve se eu quiser
a uma ação específica não sei se eu
ponho que vocês queiram talvez
a transações não se por aqui Ambev abev3
que é o primeiro lugar ou não vamos
supor b3sa três ações da B3 com que a
gente pode extrair e se deitar frame a
gente precisa usar o nosso indexador
delícia indexador é só essa chave sair
uma dentro da outra vou colocar por
exemplo 2 eu chamar isso aqui de B3
vamos b3sa
i3s 33 vulcanic b3sa 3
o que a gente vai ou você
e observe então eu obtive o deita frame
com os dados da B3 Então dessa forma
poderia replicar isso E aí eu ia
conseguir os dados de todos letra
Friends obviamente não vou fazer isso
para cada um jeito assim cada um dos
dentes da frente já tem formas mais
fáceis a gente fazer isso se eu quisesse
um elemento específico aqui dentro
Suponho que eu quisesse por alguma razão
Se eu quisesse colunas específicas eu
quisesse colunas e já colou na sede né
eu tinha falado para vocês que o formato
de deitar as pernas que eu gosto de
trabalhar eu formato de cada coluna é
uma ação né cada linha é um pregão
específico se eu quiser montar um deita
firme desse contendo esses dados para
cada uma dessas ações então pensem
comigo eu vou ter que trazer as colunas
6
Oi e a coluna 7 de cada um desses daí
pra frente se eu quisesse trazer apenas
da coluna
e as colunas tem e a coluna 7 O que é
que eu teria que ele B3 eu tenho
exatamente só duas colunas com as
informações que eu preciso eu preciso
apenas do preço ajustado e o dia que eu
vou ter que fazer isso para cada uma das
ações Então vamos lá como eu vou fazer
isso pessoal eu vou criar aqui um loop
tá E nesse loop eu vou esperar eu vou
fazer isso para cada uma dessas ações e
no fim a gente vai obter um deitar frame
só um jeito as terminou onde se deitar
firme resultante vai ter cada coluna vai
ser os dados de cada ação antes de fazer
isso eu só queria mostrar para vocês
algo que a gente precisa se dá conta que
é o nome aqui dessas colunas eu não
quero trabalhar com esses nomes né não
quero trabalhar em inglês Então como que
eu posso fazer eu vou
quer dizer que qual nem bb3sa três é o
que a primeira coluna posso chamar de Ti
e eu vou simplesmente chamar
e aqui no caso seria preço ajustado né
então se eu quisesse colocar o preço
ajustado e aqui no final quisesse
colocar data né pra gente usar se isso
dessa forma tem né os nomes que a gente
quer mas aí eu vou fazer algo
ligeiramente diferente com vocês vão
pensar que é um pouco e se ao invés de
ter a data aqui como a segunda coluna
colocar essa data com a primeira coluna
isso ajudaria né porque depois quando eu
for cruzar os dados de todas as ações
que a data vem a esquerda para facilitar
minha vida porque a coluna da data vai
ficar sempre à esquerda você a primeira
coluna e todas as colunas que vieram
depois vão ser as colunas dos preços das
ações e esse formato que eu quero toca
como fazer aqui com vocês eu vou mudar
um pouco eu vou mudar a ordem então
quero primeira coluna certo depois a
coluna sei executando esse daqui não
bom então esse formato onde primeiro
venha dó e depois vem o preto e aí eu
quero fazer algo ligeiramente diferente
também acompanha meu raciocínio ao invés
de dar o nome de genérico aqui de preço
por exemplo o que é que a gente vai
fazer eu vou criar uma coluna em que o
nome dessa coluna vai receber também o
nome da ação Então o que a gente pode
fazer eu vou usar a função peixe como
seja viram ela concatena textos né com
café nesse treino vou colocar preços
primeiro lugar no meu estilingue depois
o que é que eu vou fazer pessoal eu vou
pegar esse elemento aqui
O que é o deitar frame de B3 dentro da
lista vou trazer isso aqui para dentro
do meu Face ou seja né na prática o que
eu estou fazendo eu estou vindo aqui
dentro de se deitar Femme aqui de B3
abrindo ele
e como é que seria o equivalente a
e vamos Deixa eu tirar esse aqui bem
rápido para mostrar para vocês seria o
equivalente a isso daqui o que que a
gente vai fazer agora eu vou pegar essa
primeira linha da coluna 7 então PSP
serão aqui a primeira coluna da coluna 7
link da coluna 79 a coluna 8 o que é que
a coluna 8 tem a coluna 8 tem o próprio
título então eu vou pegar isso daqui vou
pegar esse elemento e eu vou colocar
dentro
eu vou voltar aqui você é feito eu vou
colocar aqui dentro para compor o nome
da coluna então aqui o que é que vai ser
vai ser a primeira Aline da coluna 8
Isso aqui vai estar dentro do meu peixe
vamos tempo tá isso aqui de novo para B3
se eu executar dentro daqui para mandar
o nome das colunas sobre servem o que eu
fiz agora a coluna com o preço ajustado
de B3 tem o nome dela e isso é muito
útil para gente e aí pessoal basicamente
o que queria fazer agora simples a gente
vai tentar replicar esse raciocínio aqui
para todas as ações que estão dentro
dessa lista vamos fazer isso é muito
rápido eu vou copiar isso aqui tá vou
criar o meu for
Oi e aí vou fazer uma coisa a bem
diferente Bem diferente não um pouco
diferente a verdade não é tão diferente
assim eu vou começar a partir do item
dois eu vou até o item 69 porque eu tô
indo até o 69 trouxer vem aqui que a
minha lista dá uma doce Bob ela pegou
até pegou 69 ações e Bob tem 77 não sei
porque ela pegou 69 Então a gente vai
até 69 aqui tá pessoal o que é que eu
vou fazer aqui em cima vou modificar
ligeiramente eu vou chamar isso aqui de
ação para ficar mais genérico ação vai
se chamar isso daqui
e eu vou começar com a ação um né mas é
porque eu dei para vocês eu comecei com
uma dois é que eu vou começar com um no
caso Ambev para ficar mais genérico aqui
eu estaria se referindo
e ao item 1 da lista então é uma aqui
também e isso daqui tudo eu vou passar
para dentro do meu
se for Tap só
eu estou
Oi comadre isso daqui beleza colocando
dentro que a gente precisa saber bem
ação já está definido aqui fora então
não posso usar o mesmo não é que eu vou
fazer que eu vou chamar de Nova ação que
é um outro elemento esse nova ação ele
vai estar sendo iterado então aqui é um
não é mais um um as colunas 76
permanecem sendo assim mesmo sem já
continua usando as mesmas
e ao invés de mudar o nome de ação eu
vou mudar o nome de Nova ação porque
Instagram dentro do meu foto data
permanece mesmo preço permanece o mesmo
só que aqui ao invés de pegar o primeiro
elemento da lista vou pegar o um
elemento da lista porque eu vou esperar
dentro do forno E para completar o nosso
forno a gente precisa fazer o quê que eu
preciso adicionar tudo isso ao que já
existiu tiver acidente é ação um então
percebeu que eu começo com ação um aqui
fora entra no meu fora a partir da ação
de número dois e aí eu vou adicionando
as ações que eu for manipulando a esse
elemento então eu vou dizer que ação não
é nada mais é do que um verde né tô
fazendo um joinha eu tô juntando esses
dentes da frente é um morde de ação com
nova ação
e e eu estou usando Justamente a data eu
tinha falado para você como a minha
coluna chave para fazer esses jovens
para fazer essa união entre essas bases
que a gente rodar esse daqui vocês vão
ver que relaxante rápido
se faltou alguma coisa aqui pessoal
então vamos ver o que ficou faltando né
obviamente faltou definir data Não
executei este daqui então o deita Femme
data Na verdade nem existia então agora
sim executando a gente vai conseguir
executar o nosso for então percebo que
temos aqui ação ou 909 observações de 70
colunas e aí vocês tem o formato que a
gente queria que era justamente isso
temos a coluna de data descrevendo todos
os pregões observem que a gente vai
conseguir começar a parte de 24 de
Fevereiro 2017 apesar da gente ter
selecionado a partir de 2016 mas nem
todas as ações têm dados em 2016 e temos
todas as ações aí com o nome delas
certinho e isso Vai facilitar muito a
nossa vida tava só
e na próxima etapa eu vou mostrar para
vocês como que a gente consegue fazer
gráficos fazer flocos com várias dessas
ações ao mesmo tempo e eventualmente a
gente vai montar a nossa carteira e
comparar a nossa carteira com emoji e