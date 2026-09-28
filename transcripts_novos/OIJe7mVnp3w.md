# Aula 6 - A função tapply   Curso de R para Finanças Quantitativas

- **URL:** https://www.youtube.com/watch?v=OIJe7mVnp3w
- **ID:** OIJe7mVnp3w

## Transcrição

[Música]
fala pessoal sejam muito bem vindos aqui
aos poucos e marketing
meu nome é leandro guerra hoje é
quinta-feira é dia do curso de r para
finanças quantitativas
entre no site www.aocp.com.br para
finanças quantitativas e aqui você vai
ter acesso a todo o material que
disponibilizou gratuitamente no site e
particularmente na aula de hoje eu vou
me aprofundar um pouco mais no material
de apoio de introdução ao r que você
pode baixar aqui precisamente na página
16 porque vou falar pra vocês de um
assunto muito bacana aqui na aula 6 que
é a função tempo online
uma das coisas que eu mais gosto no r
é a flexibilidade que você tem a
velocidade de aplicar funções há certas
base de dados principalmente quando
trabalhamos com os data frames que a
gente viu na nossa aula 4
hoje eu trago os exemplos que está além
do material de apoio então nós temos um
vetor com o nome do estado da austrália
é um vetor chamado state como que a
gente vai pra que vai servir essa função
tem apply primeiro o que nós vamos fazer
é criar um outro vetor de apoio que é um
transformar esse vetor de caracteres com
9 no acima dos estados em fatores
então a gente viu na nossa aula cinco
que você pode usar a função é factor ou
também somente factor como você está
vendo na aula de hoje então eu criei
esse vetor como state efe
e ele vai me dar um fator com oito
níveis primeiro ponto puxa leandro um
vetor state tinha 30 elementos e agora
tá saindo um detetor de fatores com oito
níveis tem alguma coisa errada não você
simplesmente fez a conversão para a
fator
e aí você pode conferir o r pra você
aqui não vai ter que repetir falar com
você tem 30 mil
é diferente você não tem 30 níveis você
tem 30 elementos mas eles são oito
distintos então quando você usa a função
level e coloca o nome do seu elemento
que é um fator
ele te traz aqui os oitos estados
diferentes dentre aquelas 30 repetições
porquê porque aqui a gente vai fazer uma
outra estrutura de dados um protetor com
a arrendar de cada as entradas para cada
estado imagina que seja um número muito
grande
está também com 30 elementos
e aí onde que vai entrar e por quê que
você vai utilizar uma função como a
função como a função te apply imagina
que você queira calcular a média dessa
renda para cada um dos estados que não
vai pegar a calculadora nem sair
calculando a mão certo então como que
você associa a renda por estado para
calcular a média é para isso que serve a
função tem a placa comum criar aqui um
outro vetor já é chamado de inca um
baque e abreviado média está em mim sabe
onde eu chamo essa função te apply e o
que ela vai receber como argumento
ela vai trazer como primeiro elemento
aquilo que eu quero calcular que vão ser
o que eu vou usar para calcular melhor
dizendo que são a cinco anos
baseado em quê eu quero calcular em cada
um dos meus estados transformados em
fatores talvez um outro uso para você
pegar um fator porque na verdade não era
média patinho eu quero a média para 8
porque eu tenho oito estados
oito níveis diferentes eo terceiro e
último argumento da função é o que você
quer fazer
bem eu quero calcula a média então a
gente coloque a função média feito
quando você aplica o tempo lá e aí você
dá uma olhada no que você tem dentro ali
do
que é o vetor que a gente criou de saque
para cada um dos estados
automaticamente o cálculo da média
pessoal isso aqui é muito muito útil
quando a gente tiver calculando as
variáveis dos modelos porque imagina
você vai calcular desvio-padrão a
calcular a média dos últimos fechamentos
calcular a média das aberturas você
tenha uma base de dados de cinco dez
anos de graça no time foi de 1 minuto
você vai ter 200 300 e 500 mil linhas
até a praia vai ser fundamental pra você
fazer isso porque por que eu não posso e
não preciso na função tem apply utilizar
só a função pré-definida eu também que
no caso aqui é a função da média
eu posso criar uma função minha que eu
vou chamar aquele uma função customizada
então como eu mesmo em cadeia aqui um
exemplo e também tem lá no material um
criar a função nossa do estado daniela
inglês
como que eu queria uma função r eu vou
atribuir ela alguma coisa também é certa
aqui no caso eu tô atribuindo a estrada
de terra e aí eu vou ter uma função
function que é o modo genérico ou
introduzir alguma coisa que é x 1 x aqui
vai ser no futuro qualquer coisa e o que
eu vou fazer com essa coisa x que eu vou
receber é a raiz quadrada da aliança
desses elementos de x dividido pelo
cumprimento de x o perdão estava
invertido aqui certo
criei aqui eu tenho você vê que muda
quem não vai à mente ao invés de valores
eu tenho functions agora tem uma função
que vai receber x que chama estado de
guerra e agora vamos criar o nosso
diretor da do cinco anos com o sr
vamos chamar aqui em que sr como a gente
fez lt apply da variável em camps para
state efe
a nossa função customizada sp dr
olha que maravilha
quando você gira aqui o nosso retornou
para cada um dos dois estados
beleza pessoal vocês perceberam eu subir
aqui o nível de complexidade de um modo
muito simples você nem percebeu você
hoje já aprendeu aplicar uma função que
vai percorrer todo um conjunto de dados
dos vetores ou data prémios para
calcular uma coisa específica que você
quis e te ensinei a cocal criar já a sua
primeira função no r
um grande abraço qualquer dúvida deixe
um comentário ou me mande um e mail se
inscreva no canal se você ainda não está
escrito aquele curtir no vídeo e até o
próximo ao shopping
[Música]