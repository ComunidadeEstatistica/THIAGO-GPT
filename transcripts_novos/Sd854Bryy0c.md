# Aula 04 -  H2o Data load regressão - Prof. Flávio Clésio

- **URL:** https://www.youtube.com/watch?v=Sd854Bryy0c
- **ID:** Sd854Bryy0c

## Transcrição

oi tudo bem aqui é o flávio clésio de
novo e a gente vai falar um pouquinho
mais sobre mach lane na linguagem r
dentro jogadores ó a ideia aqui hoje
nesse vídeo falar um pouquinho sobre a
carga de dados para os modelos de
regressão antes de mais nada queria
pedir para vocês se vocês não são
inscritos no canal se inscreva no canal
sempre tem conteúdo de altíssima
qualidade estatística avançada
estatística básica matemática
visualização de dados ciência de dados
mach lane tudo da melhor qualidade
totalmente feito atualmente em português
altamente inclusive tá certo
e outra coisa é todos os códigos dessa
playlist estão disponíveis aqui no git
hub do estatidados aqui na minha na
minha conta então sal vocês acessarem
aqui a url que é usuário do kit rubi só
fazer o forte continuo os códigos da
maneira que você tá querendo continuar
ou se você somente quer fazer o download
dos dados só clicar que incluem download
a escolher a opção download zip bora lá
para o estúdio tô aqui na estúdio já fiz
o download do depositório vou abrir aqui
na minha pasta estatidados essa aí cê 02
download 02.02 deram londres guache
primeira coisa que a gente vai fazer a
gente vai a fazer a carta da nossa da
nossa biblioteca do h2oh é que a gente
colocou aqui e vai colocar nossa semente
no do homem cá para 42 por quê porque os
mesmos resultados que eu tiver aqui na
minha máquina você
e aí na máquina de vocês isso é
extremamente importante para a parte de
experimentação para fazer com que o
algoritmo a obtém os mesmos resultados
sempre acerta na questão de
reprodutibilidade então a gente vai aqui
inicializar o nosso cluster do h2ovos
então a gente vai subir aqui no nosso
local rosto na porta 5 4 3 2 1 a nesse
ele traz aqui que é o número de
processadores ah eu vou escolher menos
um que é para usar todos os
processadores disponíveis no meu caso
aqui eu tenho 12 processadores ou vocês
podem ver então eu vou usar a todos eles
se eu quiser os a seis só escolher a
opção seis aqui por exemplo fazer eu vou
usar todos estão disponíveis ela e
volume máximo de memória eu vou usar 20
gigas na minha máquina eu tenho 20 gb de
memórias aqui 32 gigas de memória
desculpa e aqui é só uma das principais
diferenças do h2ocl em relação r puro
porque aqui você consegue flexibilizar o
volume de dados nos quais a você
o mar então em vez de trabalhar com a
máquina totalmente a quem te chama da
gíria em são paulo em gargalhada né
totalmente acusa trabalho para fazer e
funcionando lento às vezes nem
funcionando aqui tem como a gente
controlar tanto processamento quanto
memória a primeira coisa que a gente vai
fazer aqui a gente já pegar essa base de
dados aqui chamada a dados residenciais
na residential building inteira certo
aqui são aí antes de mais nada a gente
vai conferir um flor né então local host
5 4 5 4 3 2 1 só para ver se o flor está
funcionando funcionando então significa
que o nosso clã se ele está operacional
a gente clicar aqui na sua opção a de
mim e clicar aqui com as três passos a
gente pode ver que o nosso clã que ele
está totalmente operacional como estou
numa versão standalone do h2oh ele vai
aparecer somente um endereço de ip aqui
do meu local rosto e a porta 54321 se eu
tivesse três quatro 1060 máquinas essas
máquinas estar
e a aparecendo aqui também em relação ao
cluster a voltando na parte do código no
então tem essa base aqui station
building the lancet que é uma base deixa
eu coloquei no dessa página seguinte
verb que é um csv no qual eu tenho
algumas variáveis para uma financeiras a
que eu tento predizer por exemplo o
valor de uma casa por assim dizer uma
base muito antiga é que tem que a
principal característica dessa dessa
base de dados aqui até é somente uma
alta dimensionalidade não é um mal do
volume de de colunas por assim dizer mas
eu vou dar uma olhada nessa dessa base
aqui a dentro do rack vai ficar um pouco
mais interessante então eu pego é sua rl
coloco nesse objeto aqui chamado
resident evil oral chama o objeto
spotify e e como a gente se a gente
quiser de novo né voltando aí para duas
linhas atrás se eu quiser ver o que o
método faz só colocar um ponto
olá pessoal antes dele como eu coloquei
aqui nesse caso eu quero ver o spotify
ele vai trazer a documentação aqui ao
então esse importa o pai ele vai receber
alguns parâmetros para importar arquivos
dentro do pôster nesse caso aqui perto
que é o caminho eu vou porque eu vou
passar vou passar o rl eu já mostrei
para vocês e o frango vai ser o ponto
rex e aqui uma coisa que é interessante
é o seguinte no momento que a gente faz
é que estão se spotify o que a gente tá
fazendo a gente tá passando esses dados
por nosso coisa do h2ovos o que
significa que se eu tiver várias
máquinas esses dados vão estar a vou
estar apaixonados dentro de números
máquinas é quem determina esse aonde que
cada lado vai ficar é a própria higiene
de computação h2o.ai nesse caso é cada
cada tipo de dado na casa da pedaço de
data ele vai ter o endereço de ip a
chave e o valor no qual representa no
meu caso aqui como eu tô numa rodando há
dois anos tendo da loja então o clã
o mapa dos dados vão estar aqui e como a
gente pode conferir isso a gente pode
vir aqui por exemplo no flor deixa
fechar isso flor de novo local host
54322 ponto 5 4 3 2 1 eu vou clicar aqui
é de mim e e lembrando da primeira aula
que a gente falou em relação à parte de
arquitetura do h2oh nesse caso aqui toda
vez que a gente manda um comando do enem
para engenharia de computação do h2oh
ele trata ele trata essa esse comando
como um job então nesse caso aqui o
jovem que eu subi foi esse residencial
rex aqui essa aqui é o tempo começou o
tempo que terminou né só para dar um
timestamp e o status dona aqui se eu
quiser ver as informações dessa base de
dados e o clica em cima aqui do meu
jovem cesta básica tivesse sendo
carregado ainda ele ataque como lembrem
time há um tempo então falta cinco
minutos dois minutos minutos por aí vai
e se a gente quiser olhar aqui dentro do
flor
a própria interface gráfica as
características a dessa base nada só a
gente vir aqui nessa opção at once
clicar envio e aqui a gente tem 372 há
registros 232 registros 109 colunas e o
tamanho dele aqui que é uma base
pequenininha 412 acabares e aí a gente
tem o summer aqui não sumarização por
cada uma das colunas na então a gente
tem a starkey erétil ano que começou
então o primeiro ano começou foi 1972 a
o ano máximo foi 1988 com a média eo
desvio-padrão a aqui o trimestre no qual
aquele aquele móvel começou a ser feito
a o ano o ano que o que a obra foi
concluída e o corte o que que ela foi
concluída e algumas outras variáveis
aqui como por exemplo algumas
informações a physical fascination é que
pode ser
e a ligadas por exemplo a parte de
construção da casa em sua importa muito
para gente é nesse caso de novo foco
aqui não vai ser na parte de análise
exploratória fit ingerirem moda
interpretation nem nada nosso foco
tivesse rh2 o e modelos para a produção
então esse lado está em um pouco disso a
gente não vai fazer um tipo difícil
engenil mas é legal só para gente fazer
um exercício de abstração para saber o
que o que cada campo significa nesse
caso aqui a gente tem variáveis física
alfinetes na que pode ser por exemplo a
custo de mão de obra custou a presença
do terreno o custo do metro quadrado
construído o curso do projeto por aí vai
né então a gente tem oito variáveis
financeiras diferentes e a a gente tem
algumas outras variáveis aqui que a
gente chama de econômica index né que
pode ser indicadores econômicos que
podem ser por exemplo ao ipca ou uma
taxa selic uma taxa de crédito
interbancário
a dejà just a xyz que aqui nesse caso
nós teremos a cê me engano 19 variáveis
econômicas e para cada uma dessas
variáveis econômicas não vai estar no v1
v2 v3 v4 a gente vai ter um leg que o
leg nada mais é que a ação é absagen
dessa métrica em relação àquele valor
então seja leve um vai ser a aquela
métrica do dia anterior o leve dois vai
ser dois dias para trás o mais de três
vai ser três dias para trás e assim
sucessivamente então aqui gente tem esse
leve um que vai dar variavam até 8 se a
gente quiser ver mais coluna só vim aqui
nesse next chore code ou próximos vinte
colunas a e aqui a gente vai ter por
exemplo leg-12 então dois dias para trás
a variável uma variável dois três e
assim sucessivamente a gente pode ver
essas informações também dentro do h2oh
antes disso a gente vai comente vai
e como a regressão a gente vai converter
essas duas variáveis a dependentes que é
o ao tive um ao tive dois para numérico
ou executar aqui e a gente pode rodar o
samba ali né que é uma função nativa do
era em cima desses objetos tu h2óó que
vai trazer para gente todas as variáveis
é sumarizadas aqui então desde os
primeiros indicadores financeiros como
enchimento colocado aqui na physical
fascination até passando por a pelos
leads né leg um dois três quatro até o
leg até o leg nesse caso dessa base aqui
oleg 5 6 5 dias para trás ou pode ser
cinco meses para trás para a gente
importa a com as nossas variáveis
independentes v1 e v2 aqui tá no qual
gente tem um valor mínimo valor máximo e
assim sucessivamente a gente vai treinar
agora o modelinho aqui
é a que a gente vai usar o modelo bem
simples de regressão o nosso caso nesse
caso aqui chip não vai terminar modelo a
gente só vai fazer o split da base tá a
ideia aqui é o seguinte essa que vai ser
a parte de download e dele split que a
gente vai usar para todos os problemas
de regressão todos os algoritmos de
regressão que a gente foi tratar aqui no
curso tá porque a porque com uma base de
dados fixa a gente consegue ter uma
ideia mais ou menos de como os
algoritmos funcionam e importância das
variáveis de acordo com cada o cada
algoritmo e ao longo do curso e a gente
vai ver onda playlist aqui e falei que
parte do código ele é bem ele ele é bem
repetitivo né então a gente vai abstrair
essa parte novamente a gente não vai
fazer nada difícil jennewein nada de
exploratório de análises o nosso
objetivo aqui vai ser explorar os
algoritmos do h2oh com r e gerar esses
modelos para a produção então nesse caso
aqui eu vou chamar o sprint frame que a
nossa
é nossa função nosso método que vai
dividir os dados qual que vai ser a base
de dados esse presidente o rex tá o a
proporção que nem aqui vai estar
representado que por esse por esse
argumento eixos aqui vai ser 90 né então
esse 90 parte de treinamento 10% a parte
de teste e os ide odômetro que a gente
vai rodar aqui vai ser o 42 que é o mês
que a gente distanciou anteriormente que
se necessite quente vou usar para todos
experimente para ter a mesma
reprodutibilidade ou seja o resultado
que eu tiver vocês vão ter também não
importa a máquina que vocês estão
mudando poder computacional a memória ou
até mesmo a rede que vocês tiverem
usando o caso você estiver usando o
dentro de um cluster erro do split aqui
o primeiro objeto do split a vai ser a
parte de treinamento então se mudar se
eles deixam building trem aqui ele vai
trazer 336 registros com c
oi e a minha parte do teste que ela
parte do forro de dois do objeto do
split vou desse cara aqui e se eu for
chegar o meu residential building pouco
teste eu tenho 36 a linhas com 109
colunas a minha variável dependente
nesse quis aqui vai ser sempre esse
áudio viu um e as variáveis
independentes vai ser o que a gente
colocar aqui todos todo esse código vai
estar dentro de cada a script para os
modelos de regressão que vai ter as
variáveis tantos variáveis físicas e os
índices econômicos e se for e voltados
dentro desse objeto do do x a ser tipo o
dá o nosso x aqui a gente vai conseguir
ver as nossas 103 variáveis que nós
vamos usar para os nossos modelos de
regressão então é isso pessoal essa
nossa parte de card dados então a partir
desse momento a gente não vai comentar
nada sobre a carga de dados a análise
exploratória de dados
o juninho nem nada a gente vai
concentrar especialmente na parte dos
algoritmos com r usando h2oh para
modelos introdução tá certo então espero
vocês no próximo vídeo valeu muito
obrigado desse joelho no vídeo se
inscreve no canal e até o próximo vídeo