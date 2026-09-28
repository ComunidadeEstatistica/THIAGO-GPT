# Parte 1 - Aula prática 06 - Gráficos Estatísticos - Variáveis Qualitativas Nominais - R

- **URL:** https://www.youtube.com/watch?v=soCHMSsHm-8
- **ID:** soCHMSsHm-8

## Transcrição

Bom vamos lá então galera essa aqui é a
nossa hora de gráfico né a gente viu já
na teoria os tipos de gráficos
Associados a cada tipo de variável né E
a gente vai estar agora fazendo aqui na
prática não é Tá
ensinando como é que a gente faz esses
gráficos né para cada tipo de variável a
gente vai estar aí na sequência beleza e
a gente vai aprender aqui no r a
biblioteca chamada GG port dois tá então
é uma das bibliotecas mais utilizadas do
Erre tá para você poder customizar os
seus gráficos tá de uma forma mais
profissional Beleza então primeiramente
aquilo que a gente tem que fazer eu
tenho que instalar os pacotes não se
você ainda não instalou aqui ó está o
ponto PEC você vem aqui um vetorzinho
com o nome dos pacotes que é Os queijos
e o pai de husky é o tarde você é um
conjunto de pacote com as funções mais
utilizadas do erro tá é você vê aí Gegê
plot2d pai do um saco de manipulação de
data também tenho úbere de leite né
então tem vários pacotes aí que a gente
vai abordar um longo do curso tá e você
pode instalar ele de forma direta né
então você está lá no tarde você vai
estar lá tudo isso aqui né aí depois é
só dar um rico ai tá nesse limite pacote
que a gente vai precisar tá é o José
Parte 2 o de pra gente não deve precisar
no sala Mas é bom tá instalado já tá
aí você carregar também o isqueiro uso
próprio e o verde aqui ser beleza legal
então vamos criar o nosso banco de dados
né Para a gente conseguir
fazer aqui os nossos gráficos tá a gente
vai começar aqui com as qualitativas
nominais primeiro né exemplos de
qualitativas nominais como a gente viu
na aula teórica é o sexo cor dos olhos
fumantes e não-fumantes doente e sadio é
casado ou solteiro né variáveis
dicotômicas pode ser 01 também né então
a gente vê aqui que representa um
qualidades que não podem ser ordenadas
de uma ordem pista beleza legal então
aqui ó a gente tem um vetorzinho com a
variável sexo tem aqui ó masculino
feminino tá
aqui embaixo a gente tem né Preto
castanho azul verde fumante ou não
fumante doente ou sadio solteiro ou
casado então
selecione a Quina e aí você dá o Darlan
ou você aperta contra o gente tá
Oi
e aí a gente rodou tá se a gente chama
aqui por exemplo sexo mas tá aqui ó
masculino feminino beleza legal
E aí aqui ó
e a gente quê que faz os tempo né o
sempre faz uma amostra aleatória simples
o que que é isso eu vou pegar uma mostra
de acordo com a minha variável com o
indicar aqui para ele não vou falar o
sexo eu quero a variável sexo que tem
masculino feminino Tá eu vou querer uma
amostra de tamanho sem e esse replay
esse aqui ele quer dizer que corre
posição ou sem reposição que que é isso
com reposição é assim você como você
tivesse sorteando né as pessoas dentro
de um saco né você coloca o nome de todo
mundo lá dentro e aí você tira o nome de
uma pessoa por exemplo na pra sortear a
segunda você coloca o nome da pessoa de
volta no saco para sortear o segundo tá
isso é com reposição ou seja se não
altera o teu espaço amostral né vai ter
sempre o mesmo número de pessoas dentro
do saco tá E se eu quiser o replay igual
a falso né que é sem a posição que que
eu vou fazer eu vou tirar a primeira
pessoa e não vou recolocar quando eu
tirar segunda tá então tirei a segunda
sem recolocar a primeira que eu já tirei
Beleza então a gente vai estar o tempo
no espaço amostral e a probabilidade de
seleção também vai mudar Beleza então
quê que eu quero aqui eu quero aqui
criar uma amostra de tamanho e sem tá
com reposição de
variáveis que tem só esse botãozinho
masculino e feminino né então só para a
gente entender que o que que ele vai
geral
o pênis heróis gerou um vetor com 100
posições né onde tem falso feminino e
masculino beleza e aí eu faço a mesma
coisa para a cor dos olhos para fumante
doente está decidiu e tarde tá
Oi beleza
o então gerente diretores né todos de
tamanhos em E aí eu vou eu quero colocar
esse um Data Frame né Para a gente
conseguir trabalhar com ele tá E aí eu
chamei esse data frango de variáveis
categóricas nominais tá aqui
e o nosso dataframe vai ter o que o sexo
cor dos olhos fumantes doentes a dia
está civil e a nossa Dame de estado
civil tá vai ser no caso se for solteiro
vai ser um E se for casado vai ser
beleza legal então vamos lá ó
eu gerei aqui no Data Frame se a gente
quiser ver o Data Frame agora é só puxar
né
E se a gente quiser vir de uma forma
mais destacada né abrindo outra janela a
gente dá um rio né E aí ele aparece aqui
ó primeira coluna que é o sexo cor dos
olhos fumantes beleza legal
bom então a gente já tem aqui o nosso tá
tá frio para poder trabalhar né E aí eu
queria dar um geralzão aqui do Rio de
porte como é que ele funciona né no caso
a biblioteca que a gente tá usando em
dia parte 2 mas o nome das funções que a
gente vai usar a gente pode tá a gente
vai chamar para fazer os gráficos e aí
qual ou Quais são as os elementos que
dividem nessa função como é que eu
consigo repartir essa função de forma
que eu entendo construir 15 a construir
o gráfico todo né então a gente tem
primeiro a gente vai fornecer a base de
dados que a gente vai utilizar tá
segunda a gente vai fornecer a geometria
Ou seja é o tipo de gráfico não é
gráfico de barra histograma gráfico de
pizza então é o tipo de gráfico que a
gente vai estar utilizando beleza e o
terceiro é o a parte estética do gráfico
né O aztec mapping que a parte mais
estética do gráfico que tem a gente vai
dar os eixos as cores está e não os
textos tá então vai depender da
geometria que a gente tiver utilizando
tá
a quarta coisa a escala né se a gente
quer manter o formato da unidade de
medida né outro a gente quer logaritmo
né quer fazer transformação nos dados né
Então essa quarta ele aumenta e o quinto
são os rótulos os títulos e as legendas
né porque todo o gráfico tem laço o
título sua legenda né seus votos para
que são no caso os legumes né das
variáveis tá legal
então construir aqui um gráfico de
colunas né Barras verticais tá e como é
que a gente faz eu vou chamar gráfico de
gráfico coluna geral Esse vai ser o nome
do meu gráfico lá eu vou armazenar nesse
objeto aqui que vai ser um gráfico tá GG
port beleza e aí a gente chama a função
Geisa pote tá quê que eu vou dar de
entrada qual a primeira coisa aqui só
lembrar aqui ó primeira coisa base de
dados né quem é a base da diz que a
gente criou variáveis categóricas
nominais tá segundo passo da geometria
né então a geometria no caso aqui ainda
ainda tem a parte da estética né acho
que a estética do do gráfico aqui vai
ser o que eu só tenho o eixo né Eu só tô
trabalhando com eixo então aqui vai ser
a cor dos olhos tá a gente quer fazer um
gráfico da cor dos olhos tá E aqui
na geometria a gente faz fazer um
gráfico de baixo né a gente vai usar
position igualdade para ele fazer em
coluna está se fosse Oi gente vai ver
que tem como fazer empilhado também e dá
para inverter esse gráfico tá na
sequência a gente vai ver o fio Ele tá
dizendo o que eu vou preencher essas
barras com vermelho tá eu quero da cor
vermelha Tá eu vou ter o título do
gráfico tá digitar então a gente chama o
título número de alunos por conta dos
olhos Ou seja eu quero ver a quantidade
de alunos que têm determinado a cor dos
olhos tá aí você vai ser o nosso gráfico
e aqui vai ser o x Lab para dizer o
eixo X né quem é o eixo X é a cor dos
olhos né que eu quero cor dos olhos
nesse x NY a minha frequência você já
quantidade de alguns né então o y abre
vai me dar a frequência simples que a
quantidade de alunos Beleza e como é que
a gente faz a gente seleciona aqui roda
né ou a gente clica aqui do lado
o que já roda que ele vai rodar tudo e
aí a gente percebe que não foi gerado em
um gráfico né porque porque a gente
armazenou no gráfico colunas geral tá é
um objeto aqui do nosso gráfico tá
inclusive se a gente chamar que
parece é
o gráfico coluna geral olha o que ele
trazer um objeto já já pote tá é objeto
de gráfico tá e como é que agente faz
para aparecer ele a gente selecionava do
explica a gente abre um pouquinho janela
aqui né é o gráfico aparecer e da
Controlar enterrou vai lá no ar né
Beleza apareceu o gráfico aqui né
aqui que a gente percebe que não xixi só
a cor dos olhos né que a gente viu a
frequência simples aqui no eixo Y Na
quantidade de alunos por cor dos olhos
tem o que esse gráfico está
representando né e a gente vê que a
quantidade de azul castanho Preto verde
né mas a gente vê que não é interativo
né Por exemplo castanho aqui ó não fica
muito claro Qual é esse valor aqui que a
gente pode fazer para melhorar esse né
existe uma biblioteca não é chamada Play
tá ele deixa de gráficos bem interativos
é muito interessante está cê pode fazer
filtro visual mesmo no gráfico né O que
que a gente faz para gerar a gente pega
o objeto que a gente tirou do jeito é
próprio do Gegê pote tá E aí você faz
veja é play-doh objetos que você criou
tá então rodando aqui
e agora você percebe que ao passar o
mouse nas Barras ele aparece aqui ó
quantidade de olho azul fervente
quantidade de Castanha foi 23 olho preto
23 e verde 34 tá legal E se eu quiser
fazer se eu quiser ver só o castanho
comunicação no castanho ele já ele já
seleciona para você tá isso por exemplo
se fosse masculino e feminino aqui você
colocaria você apertando no masculino
ele já abriria só o masculino tá então
você consegue fazer vários filtros aqui
cê consegue também fazia aqui ó uso é
e no gráfico ó pode clicar numa parte
específica do gráfico tá beleza
a distancia do Espírito já volto beleza
legal e aqui se você quiser salvar o
gráfico também
vem aqui em salvar download corte
s.png né aí você clica está um pouquinho
ele já vai pedir para salvar o local né
aí você bota o local que você quer aí
dela salvar que ele vai salvar lá
naquele local beleza legal
bom então vamos continuar aqui a gente
viu o gráfico de colunas né o Barras
verticais tá
isso com números absolutos aqui na
frequência absoluta simples isso a gente
quiser por exemplo Antes aqui de fazer
porcentagem a gente vai separar eles por
sexo né Por exemplo gráfico de colunas
ou Barras verticais
os siks como é que a gente vai fazer
isso uma forma prática de fazer isso é o
seguinte