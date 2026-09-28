# Aula 01 - h2o arquitetura casos uso - Prof. Flávio Clésio

- **URL:** https://www.youtube.com/watch?v=cMlZqpXskWA
- **ID:** cMlZqpXskWA

## Transcrição

o clube clésio que eu vou falar um
pouquinho hoje sobre mach lane no r
usando o h2o.ai a ideia aqui dessa série
é falar um pouquinho da arquitetura do
h2oh em conjunto com r alguns casos de
uso no qual gente pode usar essa
plataforma né objetivo aqui não é
trabalhar com a parte de modelagem e
nessa série não é a trabalhar com essa
parte de fitness genir não a trabalhar
com a parte de explicação de parâmetros
e modelos de mach lane mas sim
apresentar o rg junto com h2óó como
alternativa aí para para lhe dar a com
algumas limitações do r&amp;a ter aí de uma
forma para entregar aí modelos de mach
lane e o modelos estatísticos do
notebook ou da sua máquina direto para
para produção mas primeiro deixe-me
apresentar então meu nome é flávio
clésio
e eu trabalho como engenheiro de mach
lane aqui na alemanha e eu tenho
mestrado engenharia de produção e eu
escrevo algumas coisas sobre deita
science machine learning no meu site
flávio colares.com e eu venho dando
algumas palestras aí em alguns lugares
né no corsa esse a mente eu falo de mach
lane produção e de alguns casos de uso
também mas vamos falar um pouquinho
sobre o h2oh na então h2 é uma
plataforma open-source a que é
desenvolvida pela a empresa de do mesmo
nome h2o.ai que é que tem como
característica de trabalhar com tanta
últimos estatísticos ou a parte de
manipulação de dados a totalmente
compras também tem memória de forma
distribuída né então onde que alguns
algumas implementações como site por
exemplo que trabalham a majoritariamente
memória ou até mesmo no l também né que
bastante todos os algoritmos de mach
lane trabalha memória o hd isole
consegue trabalhar
é bem com essa com os dados em memória
né com processamento e memória mas
também fazendo a troca de com disco para
fazer esse gerenciamento né o que a
gente vai ver vai ver um pouco mais à
frente além do que o h2 ó e aí ele tem
aí o módulo de alto ml não automático
uma churn no qual pessoas que não tem um
conhece muito conhecimento de modelagem
estatística hoje mach lane conseguem é
passar os dados aí para o para esse
modelo e o modelo conseguem saber o
modelo consegue saber qual que é o
melhor conjunto de hiperparâmetros o
arquiteturas ou modelos que se adaptam
melhor aos dados e consigam ter o melhor
resultado seja a área abaixo da curva
seja a recall seja por cision a seja
acurácia e por aí vai
e ai e uma característica tão importante
do h2oh né que é o que eu acho que é uma
das coisas que faz o h2 obrigar é que a
parte de transpor modelos da parte de
experimentação para a produção é feito
de uma forma muito mais fácil quando a
ensinar os né que aplicação principal
seja pode ser uma vida sua bancária
comer se algum site de estágio de
empregos ou não importa o domínio mas
que essa plataforma seja escrita em java
escala né porque a contrário por exemplo
de modelos em pai tão ou até mesmo r o
aumento que a gente treina esses modelos
usando a plataforma h2oh alguns dos
modelos eles podem ser serializado na
então eles podem ser gerados um objeto
físico no disco a no qual esses objetos
podem ser usados é por essas plataformas
que possui essas linguagens né então
isso deixa a parte de integração de dos
o site mach lane muito mais fácil para
para para as aplicações então vamos
dizer que você a sua empresa ela precisa
colocar um sistema de score mas o beck
angeletti totalmente programado em java
por exemplo então sente-se de dados pode
vir com h2o.ai treinar o algum algoritmo
pode ser uma rondon force pode ser um
algoritmo de costume por exemplo a ser
realizar esse objeto esse objeto está
pronto aí como inscrito já vá a no qual
esse engenheiro de software que cuida
dessa a plataforma beck and só vai fazer
a integração dessa desse escrito dentro
da aplicação então isso vai deixar de
uma certa maneira é esse esse espaço
entre desenvolvimento aí mas thriller
barra deita saem para a produção ea de
uma forma muito mais fácil integração
muito mas muito mais é redonda para se
dizer muito mais tranquila
oi e aí né a gente tá falando um pouco
aí do pouco da dois almas url ele ele é
ele tem ele tem uma algumas
características né eu coloquei aqui
problema mas eu acho que seria mais
características dos quais é muitas
pessoas que não conhece a linguagem que
não conhece a história da linguagem de
programação acha que são problemas eu
coloquei problemas aqui mas sejam
características da linguagem né em que
hoje no mundo que a gente vive com o de
videira não é com alto volume de dados
isso está com essas características
acabam virando é problemas né welia a
principal característica do erre ser uma
linguagem de computação matemática
street né então ela não foi ela não a
linguagem não nasceu para ser uma
linguagem de uso geral como por exemplo
o pai então o gol a linguagem gol a
linguagem java a linguagem scala então é
a linguagem ela possui algumas
características alguns problemas que nos
dias de hoje sua como algumas limitações
para algum
em alguns filmes de uma se lona ou se
esse de dados por exemplo como lidar com
alto volume de dados dado que o ferry
ele trabalha maioritariamente com todos
os dados e memória então se você tem um
volume de dados que serve o a quantidade
disponível de dados você tem memória
você às vezes você não consegue
aplicação fica congelado ou às vezes que
você consegue processar esses dados fica
fica muito lento né outra outra coisa
também tem um problema conhecido não é
lhe é a parte de gerenciamento de
memória né no qual r ele não é tão bom
assim ah e demanda aí um conhecimento de
sistemas operacionais para lidar com
esse esse tipo de troca entre memória
disco né que grande parte dos cientistas
de dados até mesmo alguns redes de mach
lane não tem esses essas habilidades né
para fazer esse gerenciamento a e também
né eu acho que a grande a grande
a limitação do erre e também do python
né é que quando se tem aplicações
escritas e já vão ou até mesmo escala é
precisa se fazer uma engenharia muito
grande né construir um rapper que vai
chamar a linguagem a linguagem r vai
executar aquele aquela parte daquele
script e aí começa a se colocar a
diversas peças dentro do aplicação desde
um beck enche que deixa a parte de
engenharia muito ruim pelos integração e
deixa muito suscetível a erros ea
problemas né então essas são algumas
alguns dos problemas conhecidos no r
oi e aí fala um trazendo um pouco desses
programas do erre né e colocando é
trazer de perspectiva com a o h2 uai
como uma uma plataforma de computação né
mas nós dois olhos não somente é
trabalha como r como uma uma linguagem
que do qual pode-se dizer usa o h2oh
como plataformas pode ser usado por
exemplo outras linguagens como o python
como já os escala e o h2oh também tem
integrações com outras plataformas de
visualização de dados tá bloco como
tablô e o spotify também então é aqui a
gente tem o ciclo tanto da parte de
visualização de dados programação e
integração com a plataforma e a parte de
desenvolvimento a de modelos de mach
lane o deita size ou qualquer que seja
esses modelos né e além da parte de
integração de dados né que pode lidar
tanto com um banco de dados
o que é sql então pode se você pode
plugar o seu ch 2 ohms 1 sql server ou
no hdfs por exemplo se tiver usando o
cluster hadouken o condado sair nu na
própria óptimo próprio aí ws-3 né e aí
dentro dessa rede de computação do h2oh
é existe um mundo de possibilidades não
é nem desde a parte de de análise
exploratória de dados até a utilização
de modelos modelo supervisionados e não
supervisionados a parte de fit ingerir
então tudo isso que que faz parte do
trabalho aí de um cientista de dados ou
de um engenheiro de mach lane de fazer
essa modelagem né de acordo com o seu
domínio de dados toda a parte difícil
engeniro pode ser feita dentro a dessa
and de computação lugar dois ovos e o
mais interessante é que o h2oh também
através desses dessas
e a funcionalidade de exportação desses
artefatos você tem aí basicamente de um
de uma linha de comando duas linhas de
comando você deixa modelo de mach lane
tons a para serem servidos em outras
plataformas como a por exemplo se tiver
amanhã piauí oeste que a gente vai fazer
aqui no no final do nosso curso até
mesmo você tiver escorre usando a parte
história mow dentro do apache spark
então é a gente pode ver que o h2l faz
muito bem essa amarração entre linguagem
de programação visualização de dados
fonte de dados e até mesmo essa parte de
servir sinais de como colocar esses
esses modelos para serem servidos em
produção
a e agora a gente vai falar um pouquinho
sobre o h2 ó por baixo do capô né que é
basicamente que a gente vai falar um
pouquinho de como funciona de como é a
parte desses internos né de como que
funciona a esse mecanismo porque o h2l é
uma ferramenta poderosa né ah o h2 óleo
ele foi criado a a ideia dele foi ser
uma plataforma na qual ela consiga
trabalhar e com uma um nível de inter
operabilidade entre memória e disco de
uma maneira muito mais simples no qual é
no momento que não haja espaço em
memória o h2oh automaticamente faz uma
sincronização com o disco e aí faz
somente retorna somente a a parte dados
que é interessante em memória então em
vez de você ter uma parte do
ineficiência de ter que fazer um upload
upload de 5 gigas de memória a
é de um objeto por exemplo no qual você
vai usar somente 100 megas a desse
objeto no meio de uma computação da
parte de presente pode ser uma instrução
matemática pode ser feito engineer enfim
o h2 é só vai lidar com esse volume
mínimo de dados que precisa estar em
memória que precisa de velocidade para
processar e o restante desses dados vai
estar tudo para esse fim de escutar e o
agradeço ele tem um princípio né ele é
um princípio bem bem conhecido da
computação que ele trabalha com a de
forma de pôster na então ou seja existe
uma interligação de inúmeras máquinas e
cada uma dessas máquinas que vão estar
desligados vai ser o nome e aqui é a
gente pode quando a gente fala de câncer
e nós parece que é uma coisa que demanda
muita infraestrutura e números analista
de infraestrutura para montar algo mas a
quando a gente fala disso pode parecer
algo muito grande mas o h2oh uma das
características como a gente vai vir
aqui no
e a nossa nosso própria playlist aqui
ele lida muito bem com com dados na
própria máquina então se eu sou eu posso
fazer da minha máquina que eu tô usando
um um desktop aqui no esse desktop vai
ser o meu câncer por exemplo eu posso
fazer o treinamento esse coisinha assim
e aí o seu limite né se você tiver um
time de infraestrutura na sua empresa ou
na do seu na sua universidade consiga
interligar vários computadores né
instalar o agrosol agora já ele ele é
feito para isso você pode usar inúmeras
máquinas pode ser até máquinas que bom
estava linhas ali mas que vai ter um
pouco de memória um disco você consegue
criar um cluster né criam uma
interligação dessas máquinas e ela dois
ó ele vai fazer essa orquestração de
processamento e uso de memória de todas
essas máquinas ao mesmo tempo então é um
paradigma de computação extremamente
eficiente
e a e outro e algumas das
características nem tão mais e aí alguns
pode até não dar mais flávio a gente vai
ter que aprender uma linguagem de
programação para trabalhar com a dois ou
não quando há 2 horas há mais é do que
uma plataforma no qual ele só vai usar
ele vai ter um tempo prestador interno
que ele vai pegar o seu código mr vai
passar para para para para engenharia de
computação dele e ali que ele vai fazer
essa higiene vai fazer essa esse
gerenciamento desses objetos não tem
memória quanto dispo e aí depois vai
retornar esse é o resultado dessa
votação via uma uma chamada oeste então
o basicamente quando você tá programando
em r o dentro do h2ovos você tá usando
assim táxi r a linguagem r com tudo você
tava a parte de digamos assim de
carregar o piano na parte de
levantamento de peso vai dar toda com o
h2 só que a gente vai tá fazendo isso
então é é somente uma interface cliente
do desse clã ser do h 2 ohms
oi e aí como a gente vai ver um pouco no
um pouco mais à frente do diagrama né
esse gerenciamento de dados que é feito
do h2oh ele persiste todos os dados em
disco através de um mecanismo de
chave-valor então a imaginando que a
gente tem todos os nossos dados
particionadas não é dentro do disco cada
uma dessas partes vai ter uma chave e
esses dados voz burro que estão
precisando de cima seu valor e no
momento a gente precisa desse desse
dessa pequena parte de dados o h2oh ele
faz o gerenciamento ele chama essa chave
e aí por isso que o da visão consegue
ser tão eficiente nessa nessa nessa
computação e aí o volume de chaves que
vai estar em memória vai ser vai ser
gerenciado pelo próprio h2oe no momento
que a gente tem um enchimento desse hip
de memória digamos assim que é desse
desse volume de memória suficiente para
o h2 a fazer o processamento na hora que
ele sabe que ele veio aqui ele tá cheio
e fascina olha eu não
a vocês a mais que isso mas que se eu
vou causar lentidão eu vou jogar por
disco e dessa forma eu vou usar um pouco
mais de cpu mas eu vou garantir que essa
computação ela vai ela vai conseguir
rodar a grosso modo é isso que o jogador
vai fazendo e esse e essas minhas essas
chaves basicamente são ponteiros né no
qual o cluster dona dos olhos conseguem
mapear o dado em qualquer disco é não
importa o diz que ele precisa só do ip
da máquina aí de acordo com esse p da
máquina e a chave ele consegue acessar
esse valor então vamos dar uma olhada um
pouco mais é em algumas das vantagens da
dois ó então é isso tem um dente marcos
aquino na prova apresentação tem os
links né que vai tá disponível lá dois
olhos consegue ser até 100 vezes mais
veloz aí que o que a implementação do
pai do site flor ele tem escalabilidade
né não somente escalabilidade vertical a
e você pode assim que você coloca mais
recursos em uma só máquina é você
consegue ter um poder de computação
maior e o h2 valente dessa
escalabilidade vertical tem também a
escala habilidade horizontal então seja
se encontram mais máquinas forem a
colocar dentro do cluster aumento poder
computacional do h2oh também e olha dois
ó como a gente vai ver um pouco mais à
frente tem uma uma interface de
monitoramente lado flor na qual a gente
consegue ter o histórico de todos os as
tarefas que estão ser executada a gente
consegue monitorar todos os
processadores que estão trabalhando
dentro de um processo de consegue a
saber por exemplo a qual o volume
disponível a de recursos que o poster
tem por aí vai então é uma plataforma
que ela não somente ela vem para ajudar
os cientistas de dados na parte de a
o treino e manipulação de valsa o nome
de dados mas ele dá todo o controle
completo a desse gerenciamento de
recursos no qual é não somente os
entidades podem fazer escalar esse
costura escalar a própria computação mas
como pode monitorar também e se
porventura fazer alguns ajustes e ver se
algo precisa ser a melhorado não como
por exemplo de memória um um
pré-processamento para a redução do
tempo de processamento de processamento
via cpu para permite editar
bom então esse aqui é o desenho da
arquitetura né então como eu tinha
falado anteriormente então a linguagem
de programação aqui no nosso caso vai
ser o r é vai ser somente um
interpretador né vai ser somente uma uma
linguagem de comunicação e abaixo a
gente tem né ah o cluster não é do do
h2oe dentro do posto a gente tem alguns
algoritmos na que a gente fala alto
deixar o como é que são alguns já estão
a dentes aqui lamentação que só tão
prontos para usar só passar os dados e
usar como gere mg pm de pilar em aqueles
especiais por aí vai e também né como eu
já tinha falado anteriormente então
mandar o exame ele é um ele faz o
gerenciamento de dados via chave-valor
então a se você tiver um dado no cluster
uma outra máquina lá dois vale vai saber
que tem que pegar o dado daquela máquina
e trazer no momento do processamento por
exemplo e essa parte de que o h2ol pode
ser
e com plataformas a de computação né
como radup e o spike também né de
processamento de dados quanto também a
pode ser rodado dentro de uma de uma
máquina sozinha né que chama de stand
alone que a forma que a gente vai rodar
aqui nessa nossa alice tá imaginou se
você tiver a analista de infraestrutura
e pessoas que engelider infraestrutura
consiga te ajudar a colocar mais
máquinas nesse clã seria o alerta já é
muito fácil para fazer isso é o senhor
literalmente o seu limite aqui em
relação à escalabilidade é do poder
computacional que o que o sentido de
dados encher imaginarem podem ter para
para usar o processar o solo de dados
então de novo né então dando um passinho
atrás aqui que a gente tinha falado
então que a gente consegue ver um
diagrama né que o usuário do erre aqui
ele vai dar um comando então nesse caso
aqui é um esporte fácil e seria mais ou
menos como se fosse o nosso
o csv a do do pai do por exemplo ou isso
é se verdadeira te vão no corre vai ler
um csv aqui no nosso caso é um hdfs mas
pode se dentro do sistema de arquivos na
própria máquina e no momento que se faz
esse esse import faro digamos assim a
esses dados eles são eles são ingeridos
dentro desse cluster do h2oh e aí quando
eu falo câncer aqui de novo né pode ser
uma máquina estadual não pode ser várias
máquinas interligadas tá e esses dados
vão estar persistidos dentro desse desse
cluster e esse esse rolo esse esses
dados persistidos não é dentro do disco
eles não vão ser um csv ou não vão ser
um dado do hdff mas vai ser um a gente
vai chamar de h2oh frente então é um
tipo de objeto como se fosse um inteira
frame por exemplo do do pai então o
próprio madeira table do erre que é um
tipo específico
é desse jeito de formato de dados no
qual esse formato né esse esse frame ele
vai ter esse chá esse conjunto de chave
valor que vai estar distribuído é dentro
do disco da se formam numa máquina
standalone vários riscos se for cluster
no qual é esses dados nesses valores vão
tá unidos dessa chave e o esse
gerenciamento desses objetos de levar
para o rito de memória eu não vai ser
feito pela agindo o próprio h2omem
e olha aqui é só o último diagrama em
relação à a como que funciona a é como
que funciona o comando da então a gente
vai chegar lá faz um script numa da do
sol a gente manda para o agente dono r
né perdão esse script ele vai prolongar
dois olhos né então nesse caso quem está
chamando o algoritmo de glm e aí dentro
quando a gente passa esse comando por
esse h2o.ai glm que a gente chama esse
esse modelo ah o que acontece aqui a
dentro das interpretador de linguagem r
a gente manda esse comando via uma
requisição abrir uma ipiau head uma
requisição http que vai fazer uma
conexão via tcpip né uma conexão de rede
com cluster do h 2 o que vai receber
essa instrução e a esses points do do h
2 o mané desse desse clã se tornar de
nessa parte do do do coisa principal ele
vai
é isso não jovem então toda vez que a
gente manda o modelo a uma tarefa de
processamento de dados em chamando de
jovem a gente vai ver se mais para
frente no flow que vai ficar bem
exemplificado né então no momento que a
gente faz por exemplo atribui uma faz
uma tarefa difícil ingerir a gente tá
fazendo uma chamada uma chamada http viu
enfiar oeste que vai mandar para o clã
ter o crush vai transformar esse um job
a e aí na parte de computação desse
desse desse ao político na nosso caso
aqui hoje lm ele vai pegar vai fazer a
parte de split né de que a gente chama
de divisão forte e do johnny é como se
fosse uma espécie de natal reduz a esse
gerenciamento desses dados vai ser um
ser feito e esse chave valor e aí o esse
h2oh próximos aqui vai fazer toda a
parte pontuação e aqui vai ter esse essa
essa esse essa interoperabilidade entre
memória e disco e no momento que
organizou essa gente computação tem o
rei
e ele devolve de novo a do mesmo
processo né só para contrário a para o
interpretador é e aí a gente consegue
ver os resultados como a gente vai ver
nas próximas aulas um pouco mais
práticas
bom então é isso pessoal é por fim isso
a mais para para dar um gostinho aqui na
um pouco mais teórico de como funciona a
plataforma a pra gente entender que não
tem nenhuma mágica por trás disso e
esses são alguns alguns algumas
referências ano com esse material foi
feito esses lados vão estar disponíveis
na aqui na descrição do vídeo e agora
vamos pra parte prática valeu pessoal
até mais obrigado