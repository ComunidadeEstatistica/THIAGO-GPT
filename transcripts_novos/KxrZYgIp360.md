# Aula 7 - Criando e Manipulando Listas - Curso de R para Finanças Quantitativas

- **URL:** https://www.youtube.com/watch?v=KxrZYgIp360
- **ID:** KxrZYgIp360

## Transcrição

[Música]
fala pessoal sejam bem vindos aqui há
laudos pouco e marketing
meu nome é leandro guerra e hoje nós já
entramos na aula sete do nosso curso de
r para finanças quantitativas
se você está aqui pela primeira vez só
lembrando que o meu site é o altis pouco
marcante pontocom lá no menu você
encontra a área do curso dr
onde você vai poder fazer o download de
todo o material que disponibiliza
gratuitamente com os arquivos da aula
também a apostila que eu comentei no
primeiro vídeo e no assunto de hoje nós
teremos a criação e manipulação de
listas o que é a diferença da lista para
um vetor né que nós vimos logo na
primeira aula ou por exemplo da frame
que a gente viu na aula 4
a grande e significativa diferença é que
a lista tenha vantagem de receber
diferentes estruturas de dados dentro
dos seus elementos
o leandro não entende do que você está
falando lembra que quando a gente criar
um vetor o vetor ele tinha que ser o
inteiro numérico ou ele tinha que ser ou
inteiro feito por texto por caracteres
ea mesma coisa acontece com as colunas
de som da frente eu até posso ter um
data frame com colunas de valores do
tipo de valores diferentes porém na
mesma coluna não posso te tipo número é
ou um texto diferentemente da lista onde
a gente tem essa característica então
com que a gente cria uma lista então
vamos dar um nome que a lista vai
receber lembrando que é que sempre só o
nome da variável pode ser o que o que
você quiser
a função daí a função list quando eu
abri os parentes e começou a colocar o
que tem dentro lá da lista então vamos
inventar alguma coisa que vamos chamar
uma lista onde vou ter um primeiro
componente chamado ativo tá onde esse
ativo
eu vou colocar aqui o nome de euro o sd
do padrão dólar fazendo uma alusão ao
forex porque é o meu segundo componente
da lista vai ser por exemplo a semana
que eu estou fazendo as análises vamos
porque é a semana é número quatro de do
ano então coloco aqui por exemplo a
quarta semana de janeiro a questão
informações com a quaisquer está pessoal
só para vocês nem diferença
o número de entregas que nós tivemos até
essa semana vamos deixar aqui
padronizado e deixar tudo um minúsculo
ok que vão ser por exemplo quatro e os
preços que nós tivemos até então
então a gente vai movimentar r 1.75 1.76
e 1.73 olha que legal o pessoal aqui a
lista eu estou recebendo quatro campos
diferentes quatro elementos diferentes
onde dois deles são estreantes
um deles é um valor numérico e um outro
é um vetor de valores numéricos essa é a
grande capacidade
aí você vai ver que eventualmente eu
posso fazer essa atribuição aqui não
dentro da lista você tem que colocar
sempre com valor de igual ao invés desse
sinal do menor e do hífen por quê porque
senão além da lista ele vai te criar
componentes 11 uma outra variável para
cada um desses componentes então essa é
uma dúvida que eu recebi por e mail
o dentro sempre que você fizer a
atribuição da variável é o sinal do
menor e o hífen juntos ou pode ser o
igual mas obrigatoriamente quando você
está fazendo a atribuição seja na
criação de de uma lista o eleitor alguma
coisa você sempre tem que colocar igual
quando executo ele vem aqui no
envasamento tenha lista de quatro
elementos quando clica aqui para
expandir tenho então ativo semana pregão
preços todos com é características
diferentes
para visualizar elas ensinam
invariavelmente eu coloco aqui você vê
que tem uma estrutura um pouco diferente
daquilo que a gente
visto anteriormente então como que a
gente acessa os dados dentro da lista
bem não diferente daquilo que a gente
viu tanta frame eu quero acessar o
primeiro elemento da minha lista coloca
o nome dela
coloco entre colchetes um e aí ele vai
me dar o que ele vai me dar o primeiro
componente que é o ativo em o euro o
dólar mas repara que ele o valor desse
elemento lista um aqui é tudo isso aqui
não é apenas euro dólar euro ou sd que a
gente tem aqui como eu faço para acessar
esse cara aqui dentro apenas eu posso
fazer de duas formas não posso fazer
listas duplo colchetes 1
e aí eu vou trazer apenas o euro o dólar
porque porque se daqui é um operador
onde você acessa dentro da lista aquele
componente ativo para aí sim você
acessar o euro o dólar aqui embaixo
então quando eu coloco o colchetes duplo
eu já saltou direto aqui uma outra coisa
que eu posso fazer é como a gente fazia
nos data frames fazer lista
o operador aqui do dólar aí no caso r
estúdio já sugere qual que é o
componente da lista que você pode
selecionar então se dizer aqui ativo e
aí sim eu tenho aquele mesmo resultado
eo sd então é esses dois modos aqui de
adu acessar os elementos dentro da
listas são equivalentes e aí
naturalmente se você pega uma parte da
lista que é por exemplo preços
então vou acessar a lista preços eu
tenho ali aqueles três elementos dentro
disso eu posso aplicar funções que a
gente já viu como a média tão lista
preços e aí ela vai minar a média dos
preços qualquer uma das outras operações
que a gente fez você pode fazer é
manipulando e acessando essa estrutura
dentro da lista esses componentes aqui
são muito semelhantes à quando você
trabalha com da tra fêmeas e pra gente
fechar uma outra e última forma lembra
dos preços como eu vou acessar se eu
fizer esse cara aqui
preços é o meu com o meu componente
número 4 então ele vai me dá aquela
lista
se eu quiser acessar som dos elementos e
adiciona ou colchetes outro colchetes
aqui fora e por exemplo um o que eu
estou fazendo aqui eu tô acessando o
quarto elemento da lista entrando
exatamente dentro daquele vetor que foi
criado aqui e pegando no segundo gol
cheias que está aqui do lado de fora o
primeiro componente beleza pessoal
parece um pouco complicado mas não e é
importante vocês entenderem acessar essa
estrutura aqui ao invés um dos nomes
porque quando a gente vai fazendo
interações ou os loops você deixar esses
postos livres para que eles assumam o
valor de variáveis vai ser muito
importante quando a gente vai fazendo o
desenvolvimento dos modelos beleza
pessoal
lembre-se qualquer dúvida sugestão
comentário deixa aqui em baixo ou me
mandou um e mail se você não está
inscrito no canal faz fica aqui o
convite para se inscrever
compartilhe com seus amigos um grande
abraço e até o próximo vídeo tchau tchau
[Música]