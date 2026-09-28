# Análise de dados no Python - Lendo arquivos Excel e Manipulação de dados.

- **URL:** https://www.youtube.com/watch?v=gwRUuOA81wo
- **ID:** gwRUuOA81wo

## Transcrição

Olá pessoal Voltei Tudo bom vamos dar
continuidade ao nosso bate-papo sobre
análise de dados com python pandas vamos
para a segunda parte da aula vou mostrar
alguns outros métodos bem bacanas e para
essa aula a gente vai trabalhar com o
arquivo em Excel na primeira parte da
aula trabalhamos com o arquivo csv se
você ainda não assistiu dá uma olhada lá
tá muito legal e vamos agora trabalhar
com o arquivo em
Excel primeiro passo é importar a
biblioteca pandas Então vamos dar o
nosso
Import pandas como
pd e Vamos carregar aqui o nosso
conjunto de dados que eu vou chamar d DF
e vai ser
pd pid vou dar um Tab ele vai mostrar
todas as opções disponíveis e o nosso
arquivo é um
Excel e ele se encontra dentro da minha
pasta dados
nome do arquivo é
planilha vendas p
xlsx carregamos o nosso arquivo vamos
visualizar as cinco primeiras linhas pon
R está aqui As cinco primeiras linhas do
nosso arquivo então o nosso Arquivo ele
tem cidade
ID ele tem a data da venda valor da
venda a loja id e a quantidade vendida
e o que que a gente vai fazer aqui vamos
visualizar o tipo de cada
coluna já vimos esse método na aula
passada então ele retorna aqui o tipo de
cada coluna cidade ID ele retornou como
float data ele já retornou como date
time vendas
float loja ID ele retornou como float
também e quantidade como
inteiro Então qual o primeiro método que
eu queria mostrar para vocês aqui a
gente vai transformar essa coluna loja
ID para texto string por quê Porque não
Iremos realizar cálculo com ela então a
gente não precisa dessa coluna como
número como float Então a primeira coisa
que eu queria mostrar a vocês é como
alterar o tipo de dado de uma coluna
Então a gente vai colocar aqui loja ID
como string como que a gente faz
DF a coluna que a gente quer alterar
loja id e ela vai receber
DF loja ID
Opa loja
ID pon S Type o que que eu tô querendo
dizer com isso eu quero que você pegue
loja ID como tipo e qual o tipo que a
gente quer alterar a gente quer colocar
em Object
se eu der um shift enter já alteramos o
tipo de dado da coluna loja ID Vamos
colocar um detal novamente só para ver
se ele realmente
alterou Pronto já está aqui ó loja ID já
retornou como Object podemos fazer a
mesma coisa para Cidade ID Que também
está como float tá Fica aí como
exercício alterar cidade ID para
string continuando Muita gente me
perguntou como adicionar uma nova coluna
ao nosso conjunto de dados é muito
simples tá pessoal o que a gente vai
fazer aqui é criar uma coluna de receita
por quê Porque em nosso conjunto de
dados temos venda e temos quantidade
Qual é falta colocar aqui a receita Qual
é a receita venda ve vezes quantidade a
gente vai multiplicar o valor da venda
pela quantidade vendida e vamos
descobrir a nossa receita Então vamos
adicionar essa nova coluna aqui como que
a gente faz DF o nome da nossa nova
coluna vai ser
receita e ela vai ser o quê Ela vai ser
DF
vendas multiplicado pela coluna
quantidade e como é que a gente faz isso
a gente dá ponto mu de multiplicação e a
gente quer multiplicar por abre
parênteses
DF
quantidade shift enter vou dar aqui
novamente o df. r pra gente visualizar
aqui tá aqui a nossa coluna receita
Quando a gente pega as cinco primeiras
linhas ele traz todo mundo com
quantidade um Então vamos colocar aqui
te para observar as últimas
linhas pronto podemos observar aqui ó
nas últimas linhas do nosso conjunto
temos aqui R
15,62 foram vendidas duas unidades r
31,24 3,41 x 7
93,87 Então tá aqui a nossa coluna de
receita simples muito fácil vamos
continuar eu queria mostrar agora para
vocês como tratar valores faltantes em
nosso conjunto de dados O que fazer
quando temos colunas com valores nulos E
como eu descubro quantos valores n nulos
eu tenho em meu conjunto de dados
simples a gente vai dar
df. isn que quer dizer é nulo e o que
que eu quero eu quero a soma de valores
nulos em meu conjunto Então vou dar um
ponto
s ele já retornou aqui pra gente ó então
nós temos dois valores nulos na coluna
cidade aid em Duas vendas realizadas não
foi registrado a cidade id e e quatro
valores nulos na coluna loja ID em
quatro vendas não foram registrados os
ids das respectivas lojas o que é que
isso me diz me diz que eu não poderei
dizer qual foi a loja onde essas vendas
foram realizadas e quais foram as
cidades nessas duas linhas onde nós
temos valores faltantes a gente pode
substituir esses valores caso a gente
tenha os valores corretos tá
como a gente não tem o que que eu vou
fazer eu vou apagar essas seis linhas do
meu conjunto de dados vou mostrar como
apagar caso você queira excluir essas
linhas do seu conjunto para continuar
suas análises muito simples também a
gente vai dar um
df.
dropna e eu vou passar um parâmetro aqui
que é o parâmetro
inl igual a true O que é que esse
parâmetro faz ele apaga o objeto em
memória por se eu não passo esse
parâmetro ao continuar as minhas
análises os valores faltantes vão
continuar aparecendo porque eu não
apaguei em memória eu apaguei apenas
nessa linha de código aqui então a gente
passa o parâmetro o parâmetro em Place
iG true para apagar em memória vou dar
um shift enter já apagamos novamente vou
copiar aqui esse código vou colar aqui
pra gente ver se realmente foram
excluídas as linhas e e tá aqui ó não
temos mais linhas com valores
nulos certo pessoal vamos continuar eu
queria mostrar agora para vocês
eh Como retornar à venda com valor o
valor máximo da venda o valor mínimo a
receita máxima aí e a mínima e é muito
simples também a gente vai dar apenas um
df.max ele já retorna pra gente aqui ó a
venda de maior receita foi uma venda da
loja
1037 e a receita foi
1913 10 itens vendidos tem como saber a
mínima tem
df.min ele retorna foi uma venda apenas
de um item vendido no valor de 3,34 Essa
foi a minha menor venda o menor valor
vendido
aqui continuando eu queria mostrar vocês
eu queria fazer uma análise pra gente
ver como estão as vendas de cada loja a
gente vai utilizar novamente o group buy
tá que a gente aprendeu aí na aula
passada e eu quero retornar aqui pra
gente a receita por loja ID quanto cada
loja vendeu Então como é que a gente faz
é o DF pon group
buy group buy e eu quero agrupar por eu
quero trazer loja
id e eu quero saber a receita por cada
loja
id e eu vou dar aqui uma soma porque eu
quero a soma de da
receita Pronto ele já trouxe aqui pra
gente ó eh a loja
1035
ela vendeu R
424 a loja 1036 vendeu
19.27 enquanto a loja 1037 vendeu 1
milhão não
12158
24 certo a loja 1035 acho que não anda
muito bem não né tá vendendo um
pouquinho continuando que eu queria
mostrar para vocês agora a gente vai
conhecer agora o método sort Vales o que
que esse método faz ele
ordena o nosso conjunto de dados e ele
ordena por uma determinada coluna coluna
essa que a gente escolhe Então vou
ordenar o meu conjunto de dados pela
coluna receita eu quero visualizar da
maior receita para menor como é que a
gente faz DF
pon
sort
Vales abro parêntese e eu vou passar
aqui um parâmetro chamado by que esse
parâmetro pede a coluna que a gente quer
ordenar e eu quero ordenar por receita
então eu coloco aqui
receita e eu vou colocar aqui outro
parâmetro que é o ascend que eu quero
que seja por ordem
eh decrescente então eu vou colocar aqui
a send igual a false senão ele ordenaria
por ordem crescente mas eu quero da
maior para menor e eu já vou colocar
aqui um ponto head pra gente visualizar
as colocar aqui as 10 primeiras
linhas então ele já já trouxe aqui pra
gente ó em ordem decrescente pela maior
receita que é a de 1913 e36 que é a
receita que a gente viu aqui ó quando a
gente deu um DF pon Max 1913 a maior
receita ela já vem aqui da loja 1037 E
se a gente olhar aqui as 10 maiores
vendas realmente foram da loja 1037 a
loja que tá aí campeã de
vendas certo pessoal simples vamos
continu
e Fernanda Digamos que eu finalizei
minhas análises e agora eu preciso gerar
uma nova planilha eu quero salvar essas
análises que eu que eu Constru aqui em
uma nova planilha como que a gente faz
simples a gente vai utilizar o método to
Excel Vou salvar em um novo Excel Como
que eu faço isso a gente vai dar aqui um
DF pon
to Excel dei um Tab aqui ó para mostrar
as opções disponíveis e tá aqui ó true
Excel a gente vai Abrir parênteses e o
que é que ele pede o nome da planilha
que a gente tá salvando Então vou
colocar aqui digamos
nova planilha
vendas pon
XLS x e eu vou passar aqui um parâmetro
chamado index
igual a f o que é que esse parâmetro faz
se a gente como eu já falei na aula
passada quando a gente carrega aqui no
Python ele traz o index aqui ó que eu
falei que o index em Python começa do
zer se a gente voltar aqui ó 0 1 2 3 4
esse é o nosso índex se eu deixo o índex
igual a true aqui esse index vai pra
nossa planilha em Excel quando a gente
salvar mas não quero levar esse index
para lá então eu coloquei index igual a
false vou dar aqui um shift enter Salvei
a minha planilha e onde que essa
planilha tá simples tá aqui
ó nova planilha vendas ela fica salva em
nosso diretório notebook se você voltar
lá na sua pastinha tá aqui ó nova
planilha vendas eu posso marcar ela
fazer download carregar em uma
ferramenta de visualização de dados Como
por exemplo o Power bi e continuar e
construir
visualizações é isso Pessoal espero que
vocês tenham gostado na próxima aula eu
volto para vocês pra gente conversar um
pouquinho sobre visualização de dados e
construir alguns gráficos com python
obrigada e até a próxima