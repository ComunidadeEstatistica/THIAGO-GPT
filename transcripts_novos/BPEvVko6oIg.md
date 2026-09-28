# Ponto de corte em tarefas de classificação: uma escolha inteligente - Prof. Felipe Polo - Parte 1

- **URL:** https://www.youtube.com/watch?v=BPEvVko6oIg
- **ID:** BPEvVko6oIg

## Transcrição

e fala pessoal todo mundo com vocês aqui
quem fala é felipe eu gostaria de trazer
um compra do super legal para vocês hoje
mas primeiro eu gostaria de agradecer ao
thiago novamente por ter me convidado
para gravar um vídeo canal dele é sempre
um prazer estar aqui com vocês e no
vídeo de hoje a gente vai abordar um
tema que assim eu considero um super a
importante que é como a gente vai
decidir qual vai ser o ponto de corte do
nosso classificado do nosso
classificador binário você está em
classificador e a gente tem duas partes
possíveis 01 a gente quer fazer a
classificação mas nosso nosso modelo
marcação logística por exemplo uma rede
neural lá vai retirar uma probabilidade
um score mas e aí qual que vai ser o
ponto ponto de corte para vim te dizer
que daqui para cima vai ser a gente vai
classificar como um e daqui para baixo a
gente vai classificar com 10 né que
existem existem algumas maneiras de se
fazer essa
e aqui a gente vai abordar uma uma
maneira que é utilizando a terceira
decisão a teoria da decisão a uma área
dentro da estatística que nos ajuda a
tomar melhores decisões se a gente
conhece a gente tem informação a
respeito das distribuições de
probabilidade que regem nossos os nossos
regem os fenômenos que a gente tem
engraçados tá essa é uma abordagem que
se você abrir um livro de estatística um
livro de aziz um livro de mach lane um
pouco mais avançado você vai encontrar
lá no entanto eu vejo que cursos online
por exemplo é muito difícil de achar
alguma coisa assim que seja mais
acessível então por isso que eu trouxe
para vocês a bordar tá tenho geralmente
que a gente faz quando a gente tem uma
coisa que eu dormi nada a gente o gente
avalia as curvas de precisão e de recall
aqui eu tô sumindo que você já
o que é uma curva de precisão de recall
vou mostrar para vocês logo menos mas eu
também vou colocar alguns links nesse
vídeo vocês vão ver aí para baixo e aí
vocês vão poder dar uma lida se vocês
ainda não sabe o que que é que são a
essas métricas de precisava de recall
você poder ligar para essas métricas é e
decidir qual que é o melhor ponto de
corte da dessas metas uma outra
alternativa seria por exemplo seu olhar
curva a curva roc e aí decidir qual que
é o como que você escolheria esse ponto
de corte tá aqui eu não vou abordar
essas duas maneiras eu vou até mostrar a
curva de precisão de recall mas eu vou
mostrar uma maneira aqui eu acho que é
mais inteligente da gente fazer a
escolha do ponto de corte então vamos lá
esse notebook eu vou disponibilizar para
vocês tá vai tá aí no link do vídeo aí
embaixo no
e aí na descrição aqui tá meu nome né
meu site então aqui tá tudo nos contatos
qualquer feedback a respeito desse nesse
vídeo ou qualquer coisa vocês podem
entrar em contato comigo eu tô super
acessível tá então vamos começar então
aqui a gente começa abrindo nossos
pacotes né de pacotes mais comuns né
sete lane mascote líder um pai o panda
que a gente vai utilizar todos eles e
aqui eu coloquei uma parte line que a
gente vai seguir isso aqui nesse nesse
vídeo tá como a gente vai a esse treinar
o modelo de mochila em dados reais isso
aqui na a única maneira de fazer mas a
maneira que a gente vai seguir aqui é o
primeiro passo é seria a gente limpar os
dados e tirar variáveis dando você levar
as binárias a partir das variáveis
qualitativas você tem uma variável que
ela qualitativa não vai haver categórico
ó
e aí eu teria que primeiro transformar
ela em variáveis binárias aqui tá
explicando certinho como tá fazendo aqui
no como não foco do vídeo eu só vou
passar rapidamente e depois a gente
somente ter que entender aqui que cada
variável tá querendo dizer nosso dos
milagres antes dividia a parte dos dados
para treino parte para teste antes dele
ficaria como que é a nossa área de
interesse y está distribuída no conjunto
de treino das viradas variável x quais
são qualitativas quais são quantitativas
como que suas variáveis estão
distribuídas as faria nas causas
análises mais descritivas primeiro né tá
precisando box-plot sou scatterplots aí
vai de vocês
e aqui um pouco super importante a gente
vai ter uma parte em validação sempre
que a gente faz quem está treinando
nosso modelo mas a gente tem
hiperparâmetros envolvidos seja na parte
de regularização ou seja na parte de
escolha do ponto de corte por exemplo
que o ponto de corte no fundo ele é um
hiperparâmetro não é algo que ele não é
utilizado quando você tem nosso modelo
sempre utilizar usando o conjunto de
validação do que a gente vai fazer
dividir o conjunto de treino é parte
para validação tá e aí a gente vai
treinar no nessa parte quente realmente
destino por treino vai validar nas
contas de validação vai utilizar o zíper
parâmetros ali e depois vai retreinar o
modelo no conjunto de treino inteiro e
vai fazer o teste no final mas o teste
lembra que você vai usar ele depois que
tiver tudo pronto mandei o terminado a
última costume de fazer a utilizar a
base de teste tá
ah tá bom em relação à o pênalti
primeiro tem que a gente vai normalizar
padronizar serve criar um modelo e
depois vai avaliar tá você que vocês vão
poder ler com mais calma depois eu vou
disponibilizar tá
e aqui acho que nem é o foco né dessa
aula então vamos lá e se eu tiver
trabalhar com exemplo que ele é uma base
do sus do espírito santo e nessa base a
gente tem o cada linha dessa dessa base
de dados é um paciente que agendou uma
consulta e aí a gente quer ver quais em
quais agendamentos a gente conseguia
prever que a pessoa vai faltar tudo bem
então nessa loja a gente tem diversas
características a gente tem lidero
paciente tem um gênero paciente quando
ele marcou a consulta quanto de quando
de fato é a consulta e dois consegue ver
quantos dias antes ele marcou a gente
consegue saber que vizinhança que é esse
postinho de saúde que marcou a consulta
é se ele recebe bolsa família se ele tem
problemas de saúde se ele receber um sms
avisando que ter consulta e tá lembrar
ele na intestino tem várias variáveis
aqui tá e a nossa
o risco nosso y amarelo binária e é um
caso ele não compareceu a consulta que é
0 caso ele compareceu tá então é um caso
lhe falte que é o nosso interesse é para
dizer quem vai faltar e 0 caso ele não
falte tá aqui eu vou fazer uma aqui eu
conectei no meu google drive né que é
que eu tô no collab e eu já abri a base
de dados da tim mas eu vou
disponibilizar tudo para vocês depois
depois você dá uma olhada com mais calma
que eu só para dar uma visualizada
usados aqui eu tô arrumando algumas
variáveis vocês podem lá depois acho que
não foco aqui eu tô fazendo umas
análises descritivas ou tirando alguns
sites vocês vão poder passar com mais
calma depois um para onde interessa a
gente tá que a partir daqui então aqui
já vocês conseguem ver que eu criei
matrizes x e matriz y que a minha matriz
x a matriz e features
a y a matriz de rock tablet quer criar
um modelo que vai prever os votos dados
aos filhos
e aqui a gente faz a divisão é de parte
para treino parte proteste tá
ó e aqui a gente vai a gente de vídeo ou
conjunto de treino em treino dois que a
gente vai usar para na parte de
validação e a base de variação que a
única fazer testar nossos a gente vai
utilizar e preparando tá então no fundo
na parte a utilização de parâmetros que
a parte validação a gente só vai usar
essas bases aqui é fiz treino dois
edição fernando 2x val e com val e
depois que a gente utilizou se
preparando que no caso o nosso ao ponto
de corte a gente vai fazer treinar
modelo final no treino e depois aplicar
um teste tá
é a que a gente fez uma avaliação dos
dados tão antigo assim normalizadora
clímax hábito depois eu acho bom você
dar uma olhada no site planck que se
quer se quer dizer mas algo tranquilo e
aí bom a tia já tô indo tô treinando o
meu modelo de regressão logística
consegue ver aqui no naquela base do
x-treme 2 edição treino dois e tô
fazendo a validação para escolher qual
que seria o ponto de corte ideal pra
gente contou aqui essa curva aqui ó
curva de precisão e recall e no eixo nos
sushis a gente tem o ponto de corte tá
então foi testando vários pontos de
corte para cada um desses pontos de
corte ele retornou precisão e o recall
tá então nesse caso o nosso em que tipo
dizer que como a gente quer prever quem
são as pessoas que estão faltando que
têm mais risco de faltar o recall é para
gente ler mais
é porque tipo você está tem um me coloco
quer dizer que ele está realmente
descobrindo quem são essas pessoas
apesar da de que a precisão disso talvez
não seja muito alto mas a gente sabe que
o recall nosso caso é mais importante aí
tem que poderia olhar aqui os pontos de
corte ver as combinações possíveis de
recalque precisão e escolher não algo
que faz sentido pra gente o problema que
apesar da gente saber que o recall ele é
mais importante a gente a gente não sabe
exatamente o com mais importante ele é e
como se eu falasse assim aí é duas vezes
mais importante que a precisão mas o que
isso quer dizer na prática como a gente
levar essa informação é no momento de
decisão como a gente escolheria um ponto
de corte sabendo disso é um pouco
difícil de saber né então isso que a
gente vai ver mais à frente então aqui
tem fim das combinações aqui a gente
escolheu escolher alguma
e é c1 c2 c3 para cada uma das
combinações eu tirei que as metas
principais do usando o pacote do saco de
ler
oi e aí tá pra esse vídeo não ficar
muito longo eu vou começar a falar a
teoria da decisão no próximo vídeo tá
aqui eu só estou usando para ganhar o
modelo do final né dá para depois
escolher um ponto de corte e aí é
oi e aí no próximo vídeo a gente vai
falar de teoria da decisão de facto e
como a gente vai escolher esse ponto de
corte de uma maneira mais inteligente
beleza então até o próximo vídeo