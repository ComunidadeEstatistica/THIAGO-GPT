# Ponto de corte em tarefas de classificação: uma escolha inteligente - Prof. Felipe Polo - Parte 2

- **URL:** https://www.youtube.com/watch?v=HD1vgCfCMsM
- **ID:** HD1vgCfCMsM

## Transcrição

e fala pessoal agora a gente vai voltar
com o nosso sem mas agora a gente vai
usar a teoria do decisão para ajudar a
gente escolher o ponto de corte mais
inteligente tá do que simplesmente fica
olhando para uma para escolha de
precisão de recall ou para uma curva
rosa tá então basicamente que que a
teoria da decisão ela como a funciona de
fa aquele decisão ela assume que a gente
tem três coisas principais a gente tem é
um certeza a respeito do que vá câncer
ou se a gente tem probabilidade ar-ar a
gente tem é uma função de perda ou seja
a gente dependendo da decisão que a
gente tomar por exemplo dependendo do
ponto de corte que a gente escolher a
gente vai estar um correr alguma perda
tá interno correndo algum custo e
terceiro a gente tem é possíveis
decisões a ser feitas pois têm essas
três coisas tá tô
e a probabilidade geralmente é ligada
para ela dada pela pela circunstância tá
em segundo lugar a função de perdas vai
depender de você ou seja o que que é
pior para você né tem um falso-positivo
ou falso-negativo e como e como que você
vai quantificar isso então isso depende
da sua subjetividade ou descer lá da
subjetividade da sua empresa na próxima
e que é pior em terceiro os passos de
escolhas ou seja o cônsul quais são os
possíveis valores de ponto de corte que
eu vou poder escolher isso também é dado
pela situação tá então vamos lá no fundo
aqui a gente vai trabalhar muito com
aquela ideia de matriz de confusão que
você não está confortável com essa ideia
de matriz de confusão eu sugiro que você
leia artigos a respeito depois volte
para assistir o vídeo tá bom então vamos
lá a tia eu coloquei uma matriz
é aquilo tem vários textos né tem várias
coisas que vocês vão poder ler com mais
calma depois mas antes chocolate e vai
partir direto para as matrizes que algo
mais direto tá então aqui tem matriz de
confusão é aqui na nas linhas a gente
tem o que o nosso modelo vai prever ou
seja nosso modelo ele pode prever que
elas fizeram o classe 1 para indivíduos
certo e tem a realidade de fato que que
é 0 que quer um tudo bem
ó e aqui a gente tem as possíveis
combinações então aqui na diagonal
principal agente se ele é de fato é zero
e eu previ que era zero eu acertei se de
fato ele é um e eu previ que era um eu
acertei também se ele é zero e eu previ
que era um a gente tem um falso positivo
e se ele é um imprevisto e 0 a gente tem
falso negativo tudo bem e aqui no nosso
caso do nosso exemplo dos das consultas
médicas a classe um é a pessoa faltar
então é aqui o nosso falso negativo
seria a pessoa faltar eu dizer que ela
não faltou tudo bem e aqui seria a
pessoa não faltar e eu dizer que ela vai
faltar tudo bem então aqui vai ser
importante muito importante a gente
entender isso aqui né porque aonde que a
gente tá comentando erros
o hospital não vai ser tão interessante
aqui para gente porque a gente tá
acertando eu te falo tá e fica essa
matriz de confusão nesse caso aqui tá
dando ela tá dando probabilidade na
minha população dependendo do ponto de
cortes e qual que é a probabilidade de
um indivíduo caiaque aleatoriamente qual
que é a probabilidade de um indivíduo
caiaque exatamente eu aqui ó aqui tá
então essa somas de probabilidades elas
têm que ser um tudo bem porque são
quatro opções e o indivíduo tem que cair
em alguma delas com certa probabilidade
e isso vai depender do meu ponto de
cortes e certo que se o meu ponto de
corte se for muito baixo eu vou prever
que mais pessoas vão ser aquela 51 então
eu queria mais pessoas concentradas
nessa linha ti e menos essa daqui mas se
o ponto de corte foi muito alto seja
otária valorizando mais a precisão é
queria pessoas mais concentradas nessa
linha aqui e poucas aqui tá em todos os
valores de pele
o ponto de corte tudo bem que é isso que
eu tô falando aqui né tem que ser um
para qualquer ponto de corte em cris r1
tá tô aqui ele está definido é aquelas
três coisas que foi probabilidade função
de perda e possível em decisões aqui
estavam de probabilidade tá então aqui
só vocês problema probabilidade de cair
em cada um desses quadradinho um
e aqui já nessa outra uma crise de
confusão eu tô definindo quais somam-se
as perdas certo então se eu tenho um
indivíduo que ele é zero e eu prevejo
que ele é zero eu cometo eu perco l1 se
eu falo sim o indivíduo ele é um de
presente que ele é zero eu comer eu
perco l2 cometa um erro que comete é
perder ele duas unidades celular de
unidades militares pode ser por exemplo
se ele é zero eu prefiro que ele é um eu
perco ele 3 ele é um e o primeiro que
ele é um eu perco ele quatro tá então é
razoável a gente dizer que que vai ter
uma função chamar a função de perda
esperada que ela vai ser as perdas
condenadas pelas probabilidades tá então
a perda l1 vez a probabilidade de perda
perda a perder e dois meses há por trás
do terça-feira etc e por aí vai certo e
essa função é de perdi estrada ela
depende do meu ponto de corte tudo bem
razoável
o modo que a outra coisa que a gente vai
assumir aqui l1 e ele quatro é zero
porque são situações que eu estou
acertando então se vida é zero açúcar e
zero eu tô acertando eu não perco nada
sem vida é quatro ele é um e eu falo que
ele é um eu acerto e eu não tô perdendo
nada então eu vou falar com essas perdas
nesse caso esse caso o hélio e papo é
zero então me a função de perda esperada
no fundo seria ap-202 mais t303 também e
dependendo do ponto de cortes e isso
aqui é uma essa função de perda esperada
uma coisa que eu não consigo avaliar
porque isso aqui na minha população
certa vou ter uma mostra então o que que
vou ter que fazer a este massa essa essa
função tá eu no fundo o que eu vou fazer
eu vou pegar minha base no processo de
validação eu vou assumir várias valores
para ser e aí eu vou cá
a função para vários valores de c e vou
ver qual que é o valor de ser que
minimiza a minha perda esperada tudo bem
então beleza então agora a gente vai
para um exemplo mais concreto no nosso
exemplo que o exemplo das consultas
médicas um supor que a gente tem dois
casos né de que a gente pega um para um
caso que a gente tem pó positivos e um
caso que a gente tem falso negativo uns
o pouco caso que a gente tem falso
negativo a gente tem um curso de 30
reais
é porque falso positivo no nosso caso
quando a gente fala que a pessoa vai
faltar e ela não fala é estão curso de
enterrar os porque o subo que eu falo
aquela foto mas ela não falta e por isso
eu tenho que se ela for de fato eu vou
ter uma complicação dos horários ali eu
vou ter que ajeitar ela em algum outro
horário e aí eu vou ter um uma bagunça
na minha agenda então vou ter um curso
curso de 30reais tá e vamos um pouquinho
para cada caso de falso-negativo botar
um curso de 75 anos porque porque um
falso negativo no nosso caso seria a
gente falar que a pessoa ela vai e ela
não vai ou seja o médico vai ficar
aprontando lá vai ficar plantado ali no
chão sem atender ninguém tenho mais seu
curso de uma consulta que não custam um
pouco mais alto do que eu bagunçar minha
agenda tá então tem esses dois cursos
que vão ser l2 no caso 65 e vai ser l3
no caso dos 30 reais o
e aí
bom então no fundo a gente vai escolher
o ponto de corte que vai minimizar essa
perda esperada então a gente vai lá
vamos usar resolver esse problema eu vou
treinar o número de regressão logística
usando aquela aquelas bases de validação
x treino dois estão querendo dois e já
prevendo as probabilidades para o x val
aqui eu vou definir um intervalo de
pontos de corte que vai dizer a um de
acontecer em números entre 0 e 1 vou
descer minhas perdas l1 l2 no fundo que
eu tô rodando é um look nessa possíveis
pontos de corte tô fazendo a obtém
naquela matriz de confusão e tô
calculando a minha função é perda
esperada estimando ela né como é a base
de dados e aqui vocês conseguem ver que
interessante que a gente consegue ver
claramente que existe um ponto de corte
vai minimizar essa função e perda
esperada
ah tá e aqui os valores eles estão em
unidades monetárias ou seja se por
exemplo eu escolhesse um ponto de corte
meio que é um ponto forte é mais ou
menos natural quando a gente trabalha
com uma chinela me a perda esperada
seria de 21 reais e 50 centavos tá isso
porque o meu modelo é também aí ele
nunca consegue prever exatamente quem
vai quem não vai no entanto os seus
corações a o ponto de corte que há mais
ou menos 03 aqui que é o ponto de corte
mais inteligente possível
e o meu curso ele cai em torno os três
ais tá por pessoa em média
e isso é uma economia de 14 por cento
que algo super significativo quando você
fala de um sistema de saúde de uma
cidade ou de um estado porque se eu
gasto milhões 1 milhões você economizar
14 por cento em média a cada consulta
agendada isso no final do ano vai vai
gerar uma economia absurda tá isso eu
poderia pensar no contexto de uma
empresa também tá estou fazendo essa
escolha de corte no ponto de corte de
uma maneira mais inteligente definir uma
função perda usando teoria da decisão
vai fazer com que a gente realmente
saiba ou o réu é feito no nosso da nossa
escolher tá então aqui a gente consegue
fazer umas coisas super muito mais
inteligente a gente consegue ver quanto
que a gente tá economizando de unidades
monetárias e as eu acho que é um negócio
super interessante né e aqui eu tô só
buscando qual seria o ponto de corte
ideal que seria 03 de fato né
ó e aqui no fim eu só tô treinando na
base de trem no total e fazendo a
previsão e vendo as métricas na base
teste mas o que é mais importante que
vocês entenderam essa ideia o com isso
pode o quanto que isso pode impactar no
trabalho de vocês tá era isso por hoje
assim eu fico super aberta a receber
sugestões feedback tirar dúvidas de
vocês entre em contato comigo qualquer
coisa tá um grande abraço e espero ver
vocês em breve 1