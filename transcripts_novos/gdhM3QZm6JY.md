# Aula 09 - Stacking classificação - Prof. Flávio Clésio

- **URL:** https://www.youtube.com/watch?v=gdhM3QZm6JY
- **ID:** gdhM3QZm6JY

## Transcrição

o estágio dados tudo bem que é o Flávio
Clésio Então a gente vai dar
continuidade aqui o nosso Nossa lista
aqui de Mach Lane a o r dentro do olhar
nos olhos Ah mas não sente mais nada
queria pedir para quem não é assinante
do canal se inscreva aqui no canal do
estatidados tem uma fonte controle de
qualidade desde estatística avançada
ciência de dados visualização e tudo
mais tudo de graça para vocês e também a
outra informação que ele passar para
vocês aqui todos esses Córregos estão no
repositório do mitt Ramos chamado
estatidados traço h2oh tá se você é
usuário do kit só fazer o o clone do
repositório funcionar a usuários Unity
só clicar nesse botão verde com o
download e escolher essa opção aqui
download Zip e todos os códigos todo o
código fonte aqui de todas as aulas a
vão estar disponíveis aqui pra vocês tá
bom hoje a gente vai para nossa para o
nosso papinha aqui hoje sobre destaques
em Tá bom então deixa eu abrir aqui o
nosso rstudio então A ideia é hoje é
falar um
é sobre a implementação dessa
os dois pertencem para o dentro do h2oe
fazer algumas permutações Então vem aqui
em documentos etirama está te dados só
orsitec sem bow eu vou Hobby para o
problema de classificação pode colocar
para cima a então tudo que a gente
primeiramente Então vou todo toda aquela
parte de boilerplate Cold naquele código
que não é relacionado com a nossa aula
de hoje aqui eu vou rodar eles todos de
uma vez para quem quiser ver um detalhe
em relação as fissuras em relação
conjunto de dados propriamente dito eu
recomendo Vocês vão na segunda aula da
parte de download e tudo mais que lá tem
todas as informações das duas bases de
dados tá certo ah então eu vou fazer a
carga aqui do h2oh da biblioteca a nossa
nossa vou travar o sítio nome daqui em
42 e vou conectar no nosso cluster do
h2oh também tava descartando o nosso
costura aqui o posto tá em pé dois
segundos
e os 12 cores a gente vai estar aqui
também trabalhando aqui com 20 gigas de
memória tá e dessa parte para baixo aqui
então vou fazer a carga do nosso Dona
sou do nosso da base nossa base de dados
né que tá no ambiente Rubi na descida
fullHD quad-core a ponte S ver aqui
então eu vou a gente vai transformar ele
no Nogueira Freire não h2oh frente chama
na Ponto Rex tá que vai ser um objeto
h2oh E lembrando que todos os objetos
toda a dos olhos eles a é possível rodar
funções nativas do próprio R sobre esses
conjuntos de dados nesse h2oh firme
corrente eu dou aqui o Summer tá a Então
a gente vai fazer só algumas
transformações aqui de algumas variáveis
a categóricos vou colocar as todas as
como Factor então o rodão são ele
novamente só para verificar se a todos
variáveis estão com os tipos corretos
casamento o educação por aí vai Tap
é a minha variável dependem Opa antes de
mais nada que eu vou usar o Sprint frame
tá aqui essa função que vai dividir o
nosso conjunto de de dados em uma base
de treino e teste tá nesse caso vai ser
noventa porcento para a parte de
treinamento e 10 por cento para parte
teste e a base nossa base de treino vai
tá no primeiro fugir na nossa voz de
teste vai tá no segundo fold a nossa
variável dependente vai ser a parava de
forma que indica se o cliente pagou ou
não empréstimo do nosso banco lehman
Brothers EA de novo para quem quiser
saber um pouquinho mais a base de dados
é só ir no segundo no segundo vídeo
sobre de logo está que o ponto do vídeo
não é fazer nenhum tipo de Fit with the
new e nem um tipo de análise
exploratória de dados é mais para dar
uma olhada no está aqui no centro tá
então primeira coisa que a gente vai
fazer agora é
e a gente vai estabelecer o número de
foguetes para o nosso cross-validation
de 10 tá isso aqui é muito interessante
isso aqui é muito interessante muito
importante vocês levar em consideração
por quê Porque o steffensen boldo h2oh é
por de fogo todos todos os os algoritmos
estiverem dentro do stacking eles tem
que necessariamente usarem
cross-validation tá porque esses Fundos
do Cross validation é que vai ser aqui
que vão ser usados para parte do meta
treinamento tá E esse aqui a nossa
função do então a gente pode treinar os
nossos modelos basiquinha Morro da agora
eu vou dar só uma 30 segundos ali de uma
parte teórica tá então que são os stakes
Saímos da zona né a bastante conceito de
100 donar é a gente trabalha com vários
modelos base né então vamos ter inúmeros
modelos nosso caso aqui inúmeros modelos
de classificação entre modelo um modelo
2 modelo 3 modelo 4 tá no nosso caso
vamos usar cinco modelos
e no qual cada um desses modelos vão ser
treinados de forma Independente com o
mesmo conjunto de dados e cada um com as
suas especificidades de cada os valores
como a gente vai dar uma olhada mais o
frente e esse essa primeira parte aqui
desse a desses modelos nós chamamos de
base laners né que são os os modelos
básicos gente vai usar para para fazer o
primeiro estágio da da parte do
treinamento e na segunda parte aqui é o
que é interessante é que a gente depois
que a gente faz a a previsão a petição
com o primeiro modelo a gente pega as
expedições que foram feitas e nós nós
geramos por exemplo se fosse uma espécie
de um público e Tiramos uma nova coluna
e e assim por a por baixo do capô nós
concatenarmos essa coluna com o conjunto
de dados que a gente tá treinando então
qualquer ideia aqui é a gente pegar as
variáveis que a que nós temos o nosso
modelo tá aqui nesse caso aqui vão estar
representados a como m né que vai ser o
um conjunto de Treinamento
e a gente pena esses modelos e para cada
um desses modelos ou tipo desses modelos
não ter uma vai ter a coluna que vai ser
a nossa repetição e essa coluna A gente
vai agregar no nosso conjunto de
Treinamento porque a porque essas
colunas vão ajudar a nossa a senha
Grosso módulo vão ajudar no nosso o
nosso segundo classificador que vão tá
aqui nesse século leva o modo a ter mais
ou menos um alguns valores e porventura
possam seus valores de pressão aqueles
modelos né E aí essa parte dos sendo é
que nós chamamos aqui pode se for uma
uma variável por exemplo de continuar né
a essa parte desse tema pode servir a
quem te chama de Abreu in Black vão ser
tiradas as medidas das flexões por mesmo
contra o mesmo registro usando o sal
tipo de todos os modelos a esse foi
modelo de classificação Pode ser aí
usado por exemplo estratégias como Vult
tá a E aí nesse segundo neste segundo
neve aqui nós
um conjunto de Treinamento quanto ao
discutir esses modelos através do
treinamento desse segundo do desse
segundo nível aqui de modelos nós temos
a pretensão final a aqui nesse gráfico a
gente tem deixou só maximizar aqui um
pouco a tela então aqui a gente tem uma
representação nas no carro a gente teria
nosso o conjunto original de dados no
primeiro nível teremos os modelos aqui
que vão de do modelo 12 até o modelo M
aqui nós agregamos no conjunto de
Treinamento as predições dos modelos
imediatamente anteriores tá no segundo
nível de modelos nós treinávamos alguns
modelos utilizando não somente o x né
que é o nosso conjunto de dados mas
também as medições são feitas e no final
gente tem a nossa a nossa repetição aqui
tá Isso é ficar mais claro agora no
código Deixa eu voltar aqui no estúdio e
o que a gente vai fazer agora vamos
treinar Qual que você nossa estratégia
de Treinamento por esse stecken a sendo
aqui nós vamos usar
em alguns modelos de Gamas assim Vanilla
né o alguns modelos mais simples é como
beijo landers e a gente vai ao longo na
segunda na segunda o segundo nível e a
gente vai treinar com modelos a modelos
um pouquinho mais complexo Então nesse
caso aqui encheu usar uma o primeiro
modelo a gente vai terminar com uma
Hunger Force tá que vai estar aqui com
50 árvores com step House com a
Ben 10 A 10 stackhouse nem que seja a
vai demorar se tiver menos se tiver mais
de dez rounds que não tenha nenhum tipo
de evolução mais top metro aqui nesse
caso aqui ó se o algoritmo vai lá e vai
parar certo e de novo sente quiser
acompanhar o treinamento que a gente
pode fazer aí no flor tá e onde que vai
estar o flor local host 2.543 21 se
estiverem na máquina local de vocês
vocês tiverem conter vai ser o endereço
do cluster tá primeira coisa poster
estados Costa operacional e tiver aqui
nos Jobs e o nosso Job aqui de reforços
já está rodando aqui comente pode
acompanhar que você clicar aqui em cima
ele já está em Progresso aqui de 87 por
188 e já tá quase terminando tá fazendo
os Scorpions
E aí daqui a pouco ele vai girar o
resultado para gente aqui já acabou eu
volto aqui para mim a para ideia aqui
para estúdio a ideia agora não vai ser
muito acompanhar pelo flor a quem quiser
saber o que é o flow acompanha os outros
alguns nos recomendo que vão nos vídeos
específicos de cada uma das técnicas que
lá tem todas as inscrições a dos
algoritmos para permitir e do flor
também e no qual vocês podem a realizar
a visualização de dados nessa parte do
front-end tá é o nosso. Agora a gente
vai lá somente do está cancerous
e o segundo o modelo básico é o segundo
beijo beijo Model eu vou trazer também
uma uma uma Hunger Force tá e uma coisa
uma característica importante vocês é
levar em consideração é que além dos dos
envolvidos não é do Cross validation uma
das coisas vocês tem que colocar para
todos os algoritmos de treinamento é
esse keep Cross validation portions
porque esse é só essa variável vai ser
esse esse atributo vai ser o atributo
que vai determinar se os furos do pros
Vale deixam que estado que estão sendo
usados para a parte de validação entrada
modelo vão ser usados para a fase
imediatamente posterior no caso sem
tiver os homens pertencem aos tá então
isso aqui é bastante importante modelo
base segundo treinado eu vou terminar um
outro modelinho aqui usando Deep Lane tá
a sua mente com duas camadas escondidas
tá então nosso modelo aqui é um fique
forno Então vai ser todos os neurônios a
conectados m
o neurônios posteriores aqui como eu
estou usando. 1. 1 tanto no L um ponto
nele 2 ele tá dando aqui no mailasqui
net tá e o mesmo com o mesmo atributo de
que próximo ali deixam perdition's perdi
que os que vai ajudar a gente a levar as
predições dos fontes do próximo edition
para as fases e medicamente e
posteriores quando tiver fazendo o
Stephanie sendo os tá então está aqui 98
por cento de acabou de terminar então e
agora o próximo modelo base bom CBC modo
eu vou usar aqui uma implementação do
Edson aguardente Booster tá bem Vanilla
mesmo bem simples tá com 50 árvores a
nível de profundidade nem tão não muito
profundo né de três de três livros de
profundidade a com no mínimo 5 a
registros no fold a nos nossos folha né
e com ler aqui de 0.2 tá lembrando de
novo que pros Vale deixe o prefixo para
o dia que você igual cru
e o número de fogos que vai ser o número
de fontes aqui a gente declarou
anteriormente que vai ser 10 tá e até
mesmo por questões de consistência no
momento em que tive usando a dentro do a
implementação do está crescendo aos do
h2oh é importante que o mesmo número de
genes ou seja mantido para todos os bens
na Benz módulos a porque senão vai dar
vai dar problema vai vai quebrar a
implementação porque ele vai tentar ou
Achar algo ele vai fazer a petição de
algum food aqui não tem correspondente
Então seja imagina que vocês usam vocês
usem 10 Fundos e na para treino mas as
tomadas os algoritmos base e posteriores
não tá usando cinco Então vai ter algum
algum algum tipo de problema e ao
contrário também é verdadeiro então Se
tiverem a - foad do que os outros
modelos base é a não o treinamento não é
possível usando-se técnicas erros e
último modelo que eu vou usar aqui ao
segundo modelo de e construindo a gente
Boost só a única diferença com
e a um pouquinho menor tá com a com dois
níveis de profundidade um pouco maior
aqui a então e de novo para quem quiser
saber mais sobre tanto a questão da
dentro do se enquanto Rondon Four Seven
comente Vocês vão no like no vídeo daqui
da lista a sobre esses algoritmos
específicos um qual eu falo
especificamente sobre a esses essas
implementações propriamente ditas Tá
então vamos esperar aqui e se a gente
for no flor novamente a gente vai
conseguir ver os nossos jogos rodando
então a que Dom já terminou antes de
você Seja você já trouxe então
praticamente todos os nossos modelos de
gestão foram treinados em por cento e
agora que começa a nossa a nossa
brincadeira aqui tá então é o conceito
do Blaze moda né então sente voltar
e a aqui que eu não sou para o nosso o
nosso diagrama a essa esse primeiro
nível desses modelos já estão treinando
já que são esses modelos imediatamente
anteriores aqui que nós chamamos de bens
imóvel tá que são esse esse quem te
chama tá aqui como é level então que a
gente vai fazer a gente vai criar uma
lista para cada um desses modelos base
que nós temos aqui tá tanto o modelo de
Rutherford quando o modelo de thunder
Force 2 os dois modelos disso existe um
gradient boosting e o modelo de depilar
então se eu colocar um samurai por
exemplo e colocar o nosso modelo de
diploma ele vai trazer todas as
informações a dos modelos o modelo de
Victoria que a gente acabou de treinar a
mesma coisa por exemplo se a gente
utilizar o os ama e sobre o The handle
for está a Então a gente vai criar uma
lista com esses modelos básicos tá e a
gente vai colocar vai chamar o nome
dessa lista de bens e módulos por causa
aqui no meio e modos E aí que entra a a
não esqueca dissemble do h2oh deixa eu
colocar o ponto de interrogação aqui só
para gente ver a documentação dentro do
Real perdi o próprio a do próprio
estúdio então aqui ele tem implementação
do as aqueles em bow aquelas e chama
aqui de super ler e aqui tem todas as as
características dessa dessa
implementação tá a tanto o as variáveis
as variáveis Independentes conta parava
independente responder parado aqui o
conjunto de Treinamento vai ser esse
nosso lehman Brothers trem que a gente
já definiu anteriormente e o beijo e
modos vai ser lista de modelos Nos quais
a gente já treinou os nossos bens
Imóveis estão que está dentro desse
dessa variável chamado beijo modos
também a
e deixa eu ver se tem algumas algumas
algumas funções aqui a gente pode usar
em relação ao metal Warner né ah o que a
gente pode usar o h2óó por telefone usa
ele usa sempre alimentação aqui que
chama de alto né que ele identifica Qual
o melhor algoritmo que vai se adaptar
com conjunto de Treinamento dados os
posts que vem a dos bens landers e ele
vai fazer atribuição o nosso caso não
quero colocar alto aqui eu quero
escolher ele como meta ler né nosso
metalom aí vai ser esse esse céu e se o
algoritmo gente vai fazer a pressão
final que vai levar em consideração ao
resultado os outros treinamentos eu
quero usar que o é costume gradient
boosting ou no meu metaller a se tem
algum ver se tem alguma opção bacana vou
só travar que o sítio como 42
é só para a gente para garantir que o
mesmo resultado que eu tenho aqui vocês
vão ter na máquina de vocês só vou
explorar essas opções aqui e vou rodar o
nosso está crescendo que vai chamar o
número modelo comecei no coloquei para
rodar já tá rodando aqui vamos ver que
não Jobs admin jogos vocês tem algum
diabo mudando de posição escrow
o que já terminou de fazer o treinamento
e agora da mesma forma que fez os nos
algoritmos anteriores A gente vai usar a
classe H 2 o ponto performance tá que a
gente vai passar dois a duas variáveis a
variáveis em bom né No No caso que vai
ser o nosso modelo e Oliveira que vai
ser nossa base de teste a gente vai usar
aqui só pra frente conveniência o ideal
que usam a basicamente roudaut tá e
colocar os resultados dentro desse perto
né Desse dessa a variável chamada
performance e aqui a gente vai usar
algumas funções zinhos do próprio do
próprio R para armazenar esses modelos
pra gente ter uma ideia melhor é de do
que que é cada uma dessas petições tão
que a gente vai fazer aqui
e a gente vai usar o nosso o nosso
modelo naquele está chamando aqui de mm
o nosso me odeio aqui vai ser nossa
própria base de teste e a gente vai
colocar essa função não adianta declaro
aqui em cima que vai chamar o nosso h2oh
pontual cê né que é Aranda de Corvo ela
dentro desse gateaux então o seu esse
acontece camaradas que ele já criou
Nossa função e eu vou chamar só esse
s.a. pai do r no qual os aos meios e
modos para gerar o AOC individualizado
para cada um dos bens landers tá então
tá gerando aqui ou os planos você tá
gerado aqui para gente então tenho todas
essas usar vocês para cada um dos bens
landers Então os dois primeiros
resultados aqui são os algoritmos
renoforce e segundo aqui nosso algoritmo
de depilar e esses dois últimos são os
nossos algoritmos de a espingarda e se
vo se a então se eu pegar os o Max aqui
ou caneta vez do Nordeste ao CT
e se esse no caso vai ser o nosso último
modelo do ET galinha te buscar e a gente
pode pegar ele pela perform a rodando h
u c perform.exe eu vou dar esse esses
dois por isso aqui ele vai trazer o
melhor modelo base
e vai ser 0.77 e modelos sendo Vai dar
vai tá zero 76 tá aqui a gente tá
fazendo só para fins de demonstração
ideal que seria que tivesse uma
normalização das features a Muito
provavelmente esse modelinho aqui do
nosso o nosso modelo de depilar tá Opa o
nosso modelo de depilar né o beijo mão
dele tá trazendo a performance muito
muito muito muito para baixo né tá
praticamente adoro aqui a mais afim de
demonstração aqui de como que é a
implementação dos técnicos em mudou
h2ovos a essa que a ideia é isso aí
quiser salvar essa esse modelo para a
produção né para ser realizar esse
modelo o que a gente vai fazer só girar
o nosso caminho tá nesse caso aqui eu
vou chamar esse acta como o caminho que
eu tô aqui usando na minha máquina tá
deixa eu abrir o faz aqui no próprio
estúdio Vocês estão vendo aqui só tem
dois skates e eu posso chamar os seis
módulos
é aquele vai ser o método que vai salvar
esses objetos ano diz que então vou
chamar o mesmo dele sem o meu caminho né
que nesse caso tá como esse aqui latam e
eu vou colocar a força como truque
aparece caso houver algum outro modelo
ele vai lá e vai subir escrever então eu
vou desse camarada aqui ele já aparece o
modelinho aqui já se realizavam
E se eu quiser visualizar o caminho
desse modelo com o nome dele vai estar
todo o caminho do modelo aqui junto com
o nome do objeto se eu quiser fazer um
teste desse modelo né para ver se ele tá
se ele tá rodando mesmo né A única coisa
que eu preciso fazer só pegar o caminho
dele e chamar esse esse método Model e
carregar nesse nesse objeto que eu chamo
de
a saída de moda então se eu vou dar o
sorry nesse save Model ele vai trazer
para mim aqui as informações do modelo
né Então nesse caso aqui tá dando um
modelo está crescendo já tá dando aqui
do modelo e já tá dando todas as
métricas aqui de de avaliação do modelo
né Então tá dando aqui zero85 aqui de ar
você realmente muito na parte de
Treinamento não de teste tá de variação
desculpa a E se a gente quiser fazer uma
predição com esse sempre modo o que a
gente vai fazer só usar o nosso h2oh
presentes no qual a gente vai passar o
serve de modo que o nosso modelo gente
acabou de carregar e a nossa base de
peste que é uma h2oh frame a que a gente
vai carregar dentro desse modo por
dentro dessa camada aqui
eu já rodei o meu modo a perder e se eu
quisesse ao resultado essas pressões eu
só vou dar esse print no modo perder que
Deus amei né ele já vai trazer aqui ele
vai trazer tanta Classe A que ele fez na
proibição quanto à parte de
probabilidade tá E lembrando de novo né
Só um só uma pequena dica para quem
tiver usando é probabilidades na parte
de de classificação do h2ooh Eu
recomendo fortemente vocês usem as
opções de calibração de cada um dos
classificadores a porque isso aumenta um
pouco mais a robustez em relação a como
a que as probabilidades são dispostas no
momento da apreensão na querida com
algum short rosa alguma coisa estica tá
se a gente quiser fazer a celebrização
no modelo para artefatos a tanto pojo
quanto Mojo na questão é que faz que
podem ser a embutidos em códigos a da
linguagem Scala e da linguagem Java o
que a gente precisa
Eu também te chamar essa esse esse
método download Mogi no corrente vai
ficar só um modelo que nesse caso é sem
mão e já passar o caminho a aqui nesse
caso aqui vai ser o mesmo caminho que a
gente salvou o modelo anteriormente fica
com amor tratar e ele e vai a gente vai
pedir para ele gerar o objeto já desse
desse modelo que vai ser esterilizado
então só rodar aqui ele já vai aparecer
mais dois objetos aqui que vai ser esse
está acontecendo naquele vai estar como
o zip e vai ter esse h-2 o-18 Model a
ponto já aqui então é a partir desse
momento por exemplo alguns cientistas de
dados uma pessoa que o analista de dados
a pessoa que tiver criança esse modelo
já consegue entregar esses dois aquivos
aqui para os desenvolvedores a tanto
Jeová contra escala e eles já conseguem
embutir esse código a introdução tá aí
se eu quiser fazer a importar esses
esses arquivos novamente dentro do ar e
nem posso só preciso
o caminho né nesse caso eu tô chamando
de Model nos forjar nos pés tá aqui vai
estar o meu ponto Zip nesse caso aqui
vai ser o seu arquivo o bojo e eu vou
usar essa essa função chamada importa
hoje eu não posso eu vou passar o
caminho e eu vou a pegar esse modelo ser
realizado e vou armazenar aqui no nosso
importa móvel se eu pudesse cara que ele
já fez em porta modo a Uma das uma
aquele vai dá erro aqui mas a
e isso é uma benção das coisas que
importante levar em consideração que
tanto os arquivos ser realizados quanto
o meu anjo Quanto podiam nesse caso como
a gente tá usando uma miríade de
diversos modelos parte desse o ideal
aqui no Stephanie sem bolso vocês foram
usadas tanto como mojo.com pojo o ideal
seria que vocês usassem sempre a mesma
família de modelos né então no caso usar
famílias de modelos na baseado em
árvores por exemplo todo mundo como
renoforce o a aguardente aguardente
Blues Machine + Random fortes mais
atenção garimpo single a fazer a
combinação ali dos modelos de glm por aí
vai tá para não ter nenhum tipo de
inconsistência a em relação à ao número
de coluna Azul a forma na qual o
Stephanie sambou está está colocado tá a
Então é isso E aí é isso aqui a gente
então aqui no final deixa só fazer um
o negão fazendo longe mais uma vez a
então a ideia pessoal é muito mais a
gente a gente fazer uma outro sobre o
status de Simone falou pouquinho a das
questões teóricas tá em relação à está
sendo ou não uma música função ideia
geral e essa é a forma que vocês podem
usar e diversos algoritmos a Existe
limite para está crescendo ou não que o
seu limite quanto mais variedade de
algoritmos melhor a porque ajuda ter um
resultado pouco mais robusto seja para
na parte de ao tilar se por exemplo né
Que Se tiverem a valores muito distintos
e Foge muito a médica e os
classificadores às vezes não não não
lidam muito bem a ter uma miríade de
classificadores diferentes a ser
interessante Não Existe limite de bens
módulos e não existe limite de Estágios
então a algumas arquiteturas podem ser
colocados por exemplo 10 modelos no Benz
módulos o segundo
a gente trata com 5 modelos o terceiro
nível com três modelos e no modelo final
metalier a gente usa somente uma
atividade Tibúrcio em CrossFire E por aí
vai tá bom pessoal então é isso é por
esse vídeo de hoje é queria pedir para
vocês sem vocês não são as tranças do
canal assim o Canal dos candidatos deixa
o joinha aqui no vídeo e até o próximo
vídeo tchau tchau