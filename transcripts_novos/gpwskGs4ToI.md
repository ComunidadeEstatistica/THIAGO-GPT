# Live with Tiago Dantas - Head of Blu - Increasing the predictive power of time series

- **URL:** https://www.youtube.com/watch?v=gpwskGs4ToI
- **ID:** gpwskGs4ToI

## Transcrição

e esse negócio de pandemias ficar em
casa e eu tô com filho pequenininho aí
significa que eu tô com tempo
razoavelmente limitado né em muitas
vezes eu me programo para fazer uma
coisa eu tenho que dar errado e mudar a
ideia que eu conseguisse ter feito uma
apresentação um pouquinho melhor essa e
que essas slides não tivesse em inglês
mas enviou acabou que eu aproveitei
muita coisa que eu já tinha para dar
tempo de colocar aqui só para dar um
contexto tiago me chama para fazer essa
participar das suas aulas dele já tem
tempo e eu mas é desde que se
desenvolveu a gente pote fainé é desde o
tiago dragão me chama aí e eu cara deixe
eu não gosto de falar tô enrolado é
verdade é verdade e aí fim boa boa
em algumas pessoas que estão aí dentro
da sua live talvez me deixa mentir assim
mais momento diz ele trabalhando junto e
aí agradeço a primeiro dragão aí por ter
me chamado e não ter ficado chateado
comigo por ter levado quase dois anos
que eu consegui nada que é isso aquilo
eu chamo aí pessoal ver quando que cara
que todo mundo é bem vindo entendeu todo
mundo que eu que que tem aqui uma
vontade de compartilhar conhecimento né
que eu sei que você é um cara que disse
mina bastante conhecimento já
desenvolveu o pacote a contribuiu muito
para a comunidade né então a ideia aqui
é assim né compartilhar com a comunidade
conhecimentos que talvez na nossa língua
sejam um pouco privados né de você achar
e tal pouco mais difícil né então acho
que e a gente é muito bom né e
tecnologia o que é parece um paradoxo né
a gente é muito bom mas não dissemina
conhecimento então acho
e mais se a gente fizer isso acho que
vai ser melhor aí para o nosso país com
certeza bacana então vamos lá sem os
slides estão em inglês mas altamente
chega que eu falar em português né a
gente vai vai vai vai tocando assim eu
não sei como é que vocês costumam fazer
essas enfim que a gente deixa pergunta
ficava vocês querem interromper se você
que você ia cid vocês sejam deve fazer
como vocês vão ganhar cara assim tanto
faz se faz para mim você controla o
tempo aí essa beleza de boa de boa né
é tão eu deixei aqui alguns contatos
vocês quiserem enfim entrar em contato
comigo de alguma forma são os principais
é para quem não me conhece não sou
thiago se doutorado em engenharia
industrial com foco em previsão de
séries temporais assistindo por técnicas
de machim burn fiz mestrado em
engenharia elétrica é o foco também de
previsão de séries temporais na época
previsão de séries de evento basicamente
para que ela este turbilhão de energia
eólica e o graduada em estatística da
oficial está na em si e mestrado
doutorado na puc puc rio então hoje eu
tô como chefe da área de ser de dados da
blue e ele passará trabalhei como
trabalhando ibge
a pesquisa desenvolvimento e isso
bastante consultoria em tanto empresa
privada quando pública é basicamente em
técnicas de machine learning séries
temporais modelagem estatística
econometria do relacionado basicamente a
previsão tá e aí alguns de vocês acho
que eu conheço enviou de alguma
interação ceição do cliente ou de alguma
interação da gente trabalhando junto a
tendo aula você lá do bar também deve
tente do bairro bom tem que alguns fatos
curiosos né o dragão me chamou aqui para
ver falar dessa spotify a princípio eu
falei passou tanto tempo que eu passei a
não não dá mais manutenção né responde
fight spotify como um pacote em r para
conectar com dados do spotify e fazer
análise de dados praticamente com as
informações estão dentro do spotify
o pacote aí hoje em dia de novo não dou
mais manutenção que bastante trabalhoso
é mas quem quiser usar é possível tá só
uma dúvida galera só tá vazando muito
porque eu tenho parar com uma mulher
também tá fazendo uma uma uma call na de
boa chegar muito ruim me fala que eu amo
desligar o peço a unidade lugar aonde eu
vou tá tranquilo e eu também criei são
os criadores desse método é chamado bug
de crescer e fies que é o que a gente
vai falar meio que hoje ele é produto de
uma tese de doutorado eu fiquei
encantada pelo serrano seguindo olhar um
coautor desse desse desse método mas
vamos vamos falar sobre isso tá hoje
então iniciando eu não sei se está
absolutamente claro para todo mundo o
que que é uma série temporal né então eu
tentei ser
o médico possível mas cês vão ver que a
cor lá vai começar a acelerar um
pouquinho mais rápido porque não dá
tempo tá então pra começo de conversa
uma série temporal nada mais é do que
uma sequência é de dados né ordenados ao
longo do tempo e isso você pode
considerar uma observação não é uma
realização de uma série temporal não
seja uma série temporal como uma
realização de um processo estocástico tá
tão exemplo pensa na taxa de desemprego
nos estados unidos na botei eu botei
exemplo porque gente como a gente tá
vivendo essa crise né nesse momento é
uma pergunta que você faz é beleza eu
tenho a evolução da taxa de desemprego
ao longo do tempo tá e a pergunta que se
faz é cara qual vai ser a taxa de
desemprego para esse ano dado que a
gente
o ambiente de crise e onde existe muito
certeza muito grande né sobre o futuro
tá é
é só o minutos
g1
e aí
o perdão galera eu queria botar o pé eu
só não tava entrando aqui não sabe mais
nada isso é bom então a pergunta que se
faz é claro que que vai acontecer no
futuro dado essa cacetada de informação
que eu tenho né você em tudo que
observei né então quando eu tô falando
de previsão de séries temporais em geral
o que eu quero é encontrar algum tipo de
modelo algoritmo que vá prever o que vai
acontecer dali para frente né baseado em
informações que eu tenho até esse
momento né e aí para fazer esse trabalho
eu tenho uma série de métodos método
jogo métodos métodos barra modelo está
tão dos mais conhecidos ahriman
amortecimento diferencial redes neurais
de flor neila enfim é
em the bling ring é uma a um tipo de
rede neural também né mas a verdade é
que ele tem uma série de métodos para
fazer esse trabalho é o quão bom ou não
vai eu vou fazer esse trabalho vai
depender muito do método que eu tô
usando da forma como fazer o problema
das escolhas que eu faço tá ele a minha
capacidade de entender o fenômeno de
existir sinal dentro do seu número que
consiga conversar com os dados o futuro
tá bom
bom então é
a forma dúvida porque tem uma uma tela
aqui que tá aparecendo no meu cabelo tá
aparecendo essa tela para vocês ou tipo
vocês estão se enxergando ou não só tá
gente só tá aparecendo para mim parece
mas só com emocional você tinha lá para
cima tá bom beleza
bom então é eu vou focar quem um método
específico tá talvez seja o método um
dos mais utilizados que o método de
amortecimento exponencial tá e talvez
seja um dos mais populares dos mais
flexíveis tá é a ideia desse método é
basicamente dá mais fez o para as
observações mais recentes tá então
coisas que aconteceram no passado
próximo tem mais peso do que há coisas
que aconteceram no passado distante tá e
à medida que eu vou evoluindo no tempo
os as observações vão ficando antigas e
os pesos vão decaindo de forma
exponencial sim forma bem resumida e
isso é o que é o é essa aqui é a
característica principal desses desses
métodos dessa classe de amortecimento
diferencial tá imagina imagina
e eu tenho por exemplo dessa série aqui
que é uma série de em si é um índice né
de vendas a crédito tá é para ela está
evoluindo aqui e aí suponha que eu tenha
dado sorte 2002 a 2018 dezembro de 2018
e quisesse prevê o ano de 2019 que que
eu faria né
e é bom eu poderia aplicar o método de
amortecimento diferencial vai fazer essa
essa previsão tá então em azul eu tenho
o meta é a minha previsão e em vermelho
eu tenho os valores reais que depois ter
que o fenômeno aconteceu observei e
conseguia comprar tá tão idealmente eu
quero estar perto meus meus o que eu
prever né eu gostaria que tivesse perto
dos valores reais né hoje não gostaria
de errar muito tá e aí dentro dessa
classe de modelos de amortecimento
diferencial eu tenho vários ele tem uma
taxonomia na verdade que esse modelo
está aí quando eu falo e modelos eu tô
me referindo a modelos mesmo no e não
ameto tá porque existe um nível de tocar
tocar este cidade aí dentro da forma
como eu vou abordar tava lá
adicionalmente a gente enxergue
enxergava os modelos de amortecimento
exponencial muito como método porque eu
não consegui incluir meio que aline
a ele a glória de fórmula é espírita e
aí o existe um autor ao hobby rhaylan
que chega aí dá uma nova roupagem para
esses métodos ao enquadrar esse esses
métodos sobre um aspecto de transferir
tu não mas sombrio um arcabouço de
modelos de espaço de estado está e
quando ele faz isso ele passa a
incorporar efeito genro e aí quando ele
passa encontrar em frente genro ele
consegue calcular melhor intervalos de
confiança é porque porque ele passa
saber a variabilidade né desse lado de
alguma forma tá é basicamente uma
previsão utilizando quando eu tô falando
e tse são esses modelos né de
amortecimento diferencial com essa
configuração aqui tá artenise
multiplicativo erros multiplicativos
também é bom se eu tivesse evoluindo
para hoje né para o
oi para o dia de hoje como que seria
minha previsão seja se eu chegasse por
último dado observado e olhasse que que
vai acontecer com as vendas a crédito
daí para frente como que eu poderia
fazer uma previsão é da mesma forma seus
a si mesmo modelo agora eu tenho novo
dado e foi repara que a informação a
última informação mostra que criou as
vendas a crédito reduziram de um nível
absurdo né é um efeito muito da crise
você tivesse fazer uma previsão essa
quem azul seria minha previsão pro
futuro tá os próximos anos tá é a óbvio
que a medida que a gente vai recebendo
novos informações a gente vai
atualizando as previsões tá mas hoje com
os dados que eu tenho essa seria a minha
previsão futura ser bem negativa né
e aí
oi e aí beleza isso são os netos já
acontecimentos diferencial vocês podem
me parando e filho me disse montando
dúvida tá porque agora eu vou começar a
andar no ponto que eu quero chegar né
outra esses métodos eles funcionam tá é
o esmalte amortecimento exponencial tem
histórico de mais de 50 anos de
previsões com sucesso e ajudando a
indústria e academia em vários cenários
tá mas mais recentemente é e aí em 2009
posteriormente 2016 alguns autores
começaram olhar para esses métodos e
pensa a cara com o que eu posso melhorar
ainda mais este método dos que já são
bons mas ele está com a forma tão meio
que datados né e aí basicamente aquele
passaram a fazer foi utilizar algumas
técnicas que já era o meio que conhecida
sou do campo da estatística
e eu no campo da ciência da computação
tá então ir na interseção entre esses
dois entre entre esses dois carros tá é
então tanto bergman e e os seus foram
autores contra a clara cordeiro eles
passarão a olhar aparecimento de
amortecimento diferencial e tentaram
melhorar aí com mais sucesso e segundo
autor alberto tá que eles passarão a
fazer a usar uma técnica que se chama
bag naquela basicamente agregação de
envia goodstrap e aí eu vou explicar um
pouquinho mais à frente tá é o método
que foi o busto foi até o método foi
proposto pelo leo brainly 96 e é de
passaram a condenar isso o método de
amortecimento diferencial que esses que
eu acabei de falar para você está isso
na tentativa de obter melhores previsões
seja errar menos sobre o que vai
acontecer no futuro tá
oi e aí a ideia que eles falam é
basicamente usar bootstrap para gerar um
conjunto de previsões para o futuro e
esse conjunto de previsões você dessa
forma agregar em uma única previsão né
porque no fim das contas o que se você
perguntar cara qual que vai ser a taxa
de desemprego amanhã não quero não quero
que você me diga é eu não quero
responder para você a taxa de desemprego
vai ser cinco seis sete 12 três não
quero que você eu quero te responder que
a taxa de desemprego é celular nós por
cento sei lá tá então por isso a única
resposta né mas que a meio que a
combinação entre várias previsões e aí
combinação para quem aí já teve alguma
experiência com que a água seja já devem
ter visto que quase toda a solução do
que algo envolve algum tipo de
condenação tá aí
o ponto aqui é vai ser meio que explicar
para vocês por quê que isso funciona tá
o quê que é bom combinar tá e aí
especificamente em séries temporais sabe
que o o motivo é o mesmo tá é e aí vocês
enfim eu espero quando a gente chegar no
final aqui vocês entendam que muito
provavelmente se você gerar em um único
método esse um olho que o método não vai
ser tão bom como uma combinação de
métodos uma combinação de previsões tá
fechadão semi você tá olhando os
comentários aí eu não abri ela se tornar
pois é não a parte que mandou assim
precisa reprojetar a quantidade de área
de ordem de serviço para o próximo mês
qual o método posso usar
e aí então não acreditar em geral né é é
e você pode usar vários métodos né mas a
forma é isso barba o com bom vai ser vai
depender da qualidade do teu dado com
aderentes ao teu dado ao tipo de modelo
que você tá usando o horizonte que você
quer prever e eu tenho certeza que você
que você tá né nesse momento o nível de
certeza tá gigante e prova a gente está
a tua vai atuar em um estado é diferente
do que a gente vinha atuando na área as
provas estão a gente já está atuando no
estado de diferente é porque a gente
tava do então se você usar o único
modelo para isso o que não leva em
consideração essas coisas que não seja
rápido o suficiente para se adaptar às
mudanças significa que você
provavelmente vai persistirem erros ao
longo do tempo né vai carregar esses
erros e
ah tá então é isso isso depende muito né
e varia de acordo com o teu problema né
beleza beleza vai preparando aí tiago à
medida que você acha que vale para eu
parar efeito que eu não tô vendo as
perguntas tá tranquilo tá chegando é bom
que que é esse método que o bergman
criou em dois lá em 2016 vai ser vou
passar para mim buscar o que que ele faz
a primeira coisa que ele faz com ele
olha para uma série é cara eu entendo
que tem um efeito de variância né de
variabilidade que acontece aqui e ele é
um pode ser um pouco danoso para isso
técnicas que eu vou aplicar e em seguida
tá que várias técnicas exigem certa
forma é que tem uma série de
pressupostos heterocedasticidade ao que
em geral você quer controlar o evitar e
aí
uma das coisas que e ele inicia a
fazenda fazendo meio que uma
transformação que a gente chama de box
box box box é uma é um tipo de
transformar uma família na verdade o
transformações que tem por objetivo meio
que um dos principais objetivos a
estabilizar bahia você tá de farra a
primeira coisa que ele faz é aplicar
essa transformação no que sobra nessa
transformação sério você já nessa série
um pouco mais comportada ele faz é
aplicar um negócio que se chama de
composição externa essa decomposição
stellia olhar para série temporal e de
compôr ela em basicamente em componentes
que a gente chama de não observar está
não é o efeito sazonal o efeito de
tendência e o efeito que a gente chama
de vermelha é basicamente e sobra entre
o componente sazonal e componente de
tendência tá por quê que eu quero fazer
isso porque eu enxergo que existe sinal
de
e do componente sazonal e sinal dentro
do componente de tendência o problema é
que se eu consigo me isolar esses
efeitos problema não final a vantagem é
que se eu consigo isolar esses efeitos o
que sobra na teoria seria boa parte
ruído tá é o que a gente tá chamando de
uma emenda tá é o seu consigo me isolar
o ruído eu consigo depois aplicado
escreve porque
é que nesse pedaço onde só existe ruído
o efeito de temporal entre essas
observações ele passa a não existir tão
fortemente da ele é mitigado eu abaixo
do sinal eu já está aí nessa de
composição espere ainda tem uma vantagem
ela manda composição aditiva então posso
tomar esses componentes eu somar esses
componentes no final componente tiro o
que passar original tá então fica tô
querendo dizer com isso é isso aqui ó
imagina que eu tenho essa série tá esse
aqui só meus dados e essa série de
crédito e aí eu decomponho ela os em
componentes são observados então
concorrentes nacional e se a quinta
série o componente de estacionalidade
dela ao longo do tempo é esse aqui bem
comportado tá então são os seus
realidade é que ele fez que se repete
dentro de um período específico de tempo
nós dentro do mesmo prêmio de tempo e
esse aqui é o componente de tendência
oi e aí o que sobra que não é efeito
sazonal e enfeites tendência é esse cara
aqui que eu tô chamando de mim ainda tá
é o problema se a gente aplicar um teste
de autocorrelação ao o mesmo olhar para
fake' fake' em cima do vermelho desejo
vocês veriam que esse essa técnica aí na
verdade nenhuma técnica é perfeita tá
então ainda pode sobrar alto correlação
serial entre esses entre os dados que
estão aqui dentro por isso eu não posso
aplicar é o método de bootstrap aqui
diretamente tá e o que que é um método
de método tipo de só que eu pegar
observações aqui dentro e real mostrar
tá e selecionar aleatoriamente com
reposição de forma reconstruir essa
série com valores trocados em posições
diferentes tá o bruno eu não tô aqui a
partir dessa decomposição modelo
consegue lidar bem com dados não
estacionários e
e isso é uma boa pergunta de
decomposição cara não sei se eu entendi
completamente a pergunta você quer
reformular ele a partir dessa
decomposição modelo consegue lidar bem
com dados e quais com séries não
estacionárias não sei cara depende né
assim é depende você pode você pode eu
entendi tá falando que você tá falando
né que você gostaria de fazer nesse caso
é por exemplo retirar o efeito da
tendência né então você alisou o efeito
da tendência você como é que eu tô
tratando de uma decomposição aditiva eu
diminuo esse efeito do meu dado original
não teria mais tendência o gado na
teoria numa forçação de barra talvez
tivesse estacionar alisado talvez não
sei vai depender muito do teu dado mais
uma pode ser uma saída assim vocês vão
ver que eu não vou ter nenhuma
se você me perguntar exata tá ir assim
se alguém tiver alguma resposta exata
pelo seu nome é observado cara de confie
assim uma certeza muito grande acho tem
que tentar né testar entender as
limitações você tá trabalhando não tá
posso poderia assim serve para atestar a
voltando assunto né o que ele faz depois
é usar bootstrap em cima do remember
porque o que ele quer gerar novas
versões do vermelho ler a medida que ele
gera novas versões a sua emenda ele pode
depois somar com as com as concorrentes
que ele já tinha estimado e ele tem
novas versões da mesma série é o que eu
tô querendo dizer com isso ele pega esse
remender aqui esse pedaço e faz isso
aqui ó imagina que isso aqui isso aqui a
série tá e ela tá ordenada né então
primeira observação 2ª 3ª 4ª e até a
vigésima como eu falei que dá pode
existir um efeito de autocorrelação
é o que eu faço é não aplicar bootstrap
direto nesses dados mas separar essa
série em blocos tá em blocos de mesmo
tamanho de forma que o preserve
autocorrelação dentro dos blocos e jerry
atualidade entre os blocos tá na prática
o que eu tô fazendo aqui ó tem esse
bloco esse outro bloco esse outro bloco
em bloco e depois eu dou uma testada
aqui né você pegasse degres esse várias
partes a distribuição na onde cada
quartil você você considera ali uma que
não vai ter esse problema de alta
correlação serial né mas quando eu faço
isso dentro do bloco eu preservo né a
autocorrelação que ainda possa existir
agora entre os blocos eu posso mexer
eles né melhor legal aí você seleciona
aleatoriamente entre esses blocos né e
na prática faz 2 apresenta os
selecionáveis bota x 1
o logotipo novo centro bloco aqui esse
outro bloco aqui mesa tô selecionando
aleatóriamente beleza acabei de
reconstruir uma série de ir vender deixa
eu ver com isso dessa série de vermelha
eu posso tomar com aquela aquele
componente sazonal mas o concorrente de
tendência eu tenho uma nova versão
daquela séria tá massa eu realmente está
na prática que eu tenho essa série aqui
eu posso gerar várias outras versões
dessa série aqui tá aí por que que faz
sentido isso faz sentido que ele abra lá
no início da
e dessa apresentação falei que uma uma
série temporal seja essa aqui nada mais
é do que uma única realização de um
processo estocástico tá aqui do lado
processos estocásticos sendo gerado
várias outras realizações de seus
processos locais da eu gerei de forma
artificial tá então agora eu passo até
várias séries tá você passa a ter várias
séries ao invés de aplicar o método de
amortecimento exponencial ou na verdade
qualquer método que eu quisesse tá é
nessa série eu passo aplicar em ele
séries aqui em bcl se eu tivesse aí
sérios que hoje ele vive algum short
cara vou aplicar em tem esse método isso
aí dessa série que eu apliquei sem dessa
história eu posso até sempre horizonte
ao invés de uma única previsão tá e
quando eu passo você sem previsões eu
posso agregar essas previsões de alguma
forma aí vai depender do dente como eu
queira né é o berg na e vai
e ele aliás cara da da universidade de
monash na austrália tá lá também é onde
essa de cima do apartamento onde tá o
robin hammond é o pacote podcast era
durante muitos anos foi editor-chefe do
international journal for casting que é
o principal jornal de previsão de séries
temporais causaram departamento de
esportes aqui é o método deles deles né
na verdade ou um dos coautores do berg
manuel robinho já jantou de um monte de
coisa tá e aí a previsão no final das
contas é eu aplicar o método de
amortecimento exponencial em cada uma
dessas séries e deixar o método
selecionar o melhor é perdão e deixar
esse deixar o próprio algoritmo meio
selecionar o melhor método de
amortecimento especial para cada uma
dessas séries que eu escolhi então isso
certa forma perm
a variabilidade até de parâmetros estão
de dentro exposição de grafite gasparini
e a previsão final na verdade obtenho
com fazendo a média a mediana hoje a
média aparada operou tran
bom então no fim das contas isso que eu
estou gerando tomar olhar
o pão segundo dia de ao meio copo de
água
o opa um problema só me ouvindo direito
a piorou um pouquinho só fala alguma
fala alguma coisa e aí tá aí é
e a lu está me ouvindo direito fala de
novo eu tô vendo sim tá beleza deixa eu
só não tá bom é um copo d'água aqui eu
eu falo a gente muito e aí um beijo
nossa nos traga aqui no coração segundo
aí galera tranquilo e
e aí
e é normal né com o nome da música aula
presencial e nesse fica gesticulando
muito na online você não precisa se
mexer tanto na tela até porque dispersa
né atenção não é no presencial é muito
interessante que você já se cuida né
então ele homem já deu aula e presenciar
o
é bastante né
e aí
olá pessoal pessoal que tá fazendo
algumas perguntas eu tô eu tô salvando
aqui ó tem da lívia tendo periquito lá
no youtube e tem da luciane tá a gente
faz aqui no final
e se der tempo a gente vai a gente vai
fazendo tá a
e fala galera é selecione sim sim tá
ótimo eu derrubei um copo d'água em cima
do meu no meu computador acho que ele
não morreu é a nossa primeira vez que eu
faço isso tudo bem desastrada então
imagina que você tem a série e é você já
gerou na nesse caso aqui ele seja link
autores falam até de 99 versões né então
chegamos em séries eles geram ou seja
sair eles não mais 99 versões na minha
matéria eles aplicam métodos de
amortecimento exponencial aí geram novas
observações novas previsões tá que é
esse esse carinha aqui tá vendo então
tem várias prisões e o final é uma
agregação de certa forma usando alguma
medida de resumo nesse caso aqui eles
usam a mediana tá muito legal esse cara
é exato aí você passa a ter passar e ter
uma única série e passa a ter várias
séries né
e é para quem já está um pouquinho não é
parecido com o sistema de próximo
validez né é perto ali vários parte da
dívida em várias partes nem vai testando
cada um no final faz uma agregação ali
né que vai te dizer aquele é que tá bom
não né é mais ou menos né fazer uma
comparação aí é a ideia de desistir mas
o jeito que é feito é parecido assim é a
idade selecionar a partir essa é a ideia
na verdade o racional ele aparecido tá é
tipo cara só tem uma série hoje só tem
um conjunto cidade como é que eu vou
validar com outro de fugir da são não
tenho né é como é que eu posso inflar
esse treco de uma maneira artificial mas
talvez ainda faça sentido lá e essa aqui
é uma forma beleza então esse esse
método aqui é chamado de greg
o bld nem sei na verdade o nome que é
que tá aqui porque a gente pega blw bebê
ponto 10 porque eu tô usando o bergue né
eu tô fazendo uma transformação box-cox
eu tô eu tô fazendo uma bootstrap via
moving blocks muito perto queres ser
essa forma de fazer botticelli e eu tô
aplicando até se tá eu falei para ela
que saiu 2016 e cara gerou muito
escurinho na época porque eu estou
ajudando a comunidade científica porque
principal motivo foi que eles aplicaram
em um conjunto chamado m3 e é uma
competição de previsão que aliás nesse
momento acontecendo a m5 é eles
mostraram que esse método deles ganhava
de todos que estavam na m3 tá é e aí já
era bastante bastante guri tá é a
oi e aí só que o problema é quando eles
aplicaram isso ele não nos dela trabalho
de ver isso na vida real né no aplicar
isso não é meio que na vida real porque
ela não conjunto agir de precisão e aí
tem esse paper aí quem quiser dar uma
lida que a gente eu fiz lá em conjunto
com fernando com o hugo é basicamente
aplique esse modelo e aplica bug no fim
das contas é para prever a demanda por
transporte aéreo tá aí também rápido mas
é saber o que vai acontecer o que que
vai ser a demanda de transporte aéreo
tem uma série de implicações práticas
para indústria tá e aí você você previa
mal significa aqui você não vai
conseguir alocar direito circulações
você não vai conseguir ingerir de
direito receita autogerenciamento
receita você vai cair em casa jogar boot
ele tem uma série de impactos tá eles
têm regulações pesadas do pneu
dependendo do país então qualquer é um
o que seja melhor ela é a bem viva
dentro desse dentro desse calcutá é eu
que a gente fez foi basicamente usar
esse método para tentar prever melhor e
fazer geração fazer previsões mais
precisas dentro desse contexto dentro e
para essa indústria tá então a gente fez
foi pegar a dados de 14 países séries
mensais e fazer uma previsão para um ano
à frente eu sei o que que vai acordado
eu tenho dados 2007/2014 mensal sobre
demanda de passageiros né seja o blocks
pelo menos demanda né que é o total de
passageiros que tá voando que que vai
ser o daqui para frente né o quê que vai
ser dito de janeiro 2014 a dezembro 2014
né então é
e as séries eram tão diversas quanto
essas são system presents a
estacionalidade alguns casos ela é mais
ou menos caótica em determinado caso tem
tendência outras não tem tendência é
para ele vai tá aí em vermelho são as
nossas previsões em preto foi o que
aconteceu ficou bem próximo né e aí a
gente não parou essa esse método com o
outros métodos tradicionais de previsão
a ima ets o benchmark mais mais fogo
está em análise é engessado estão
ficando essa tabela acho que não vale eu
passar casa caso mas e sim é para
conclusão tá conclusão que a gente
chegou foi que basicamente usar bag você
seja fazer essa gregação essa combinação
é e geral reduzir o erro e aí o erro que
a gente tava falando é esse esse aqui
que é o meio chamou parecido com o mar
o carro é percentual mas isso aqui tem
uma correção que corrigir várias
inconsistências do mata é basicamente
usar bag fazer combinação gerava erros
em média vinte por cento menores tá ou
seja cara 20 porções menores
significativo tá é e aí se eu fosse caso
a caso e fosse olhando né e se acaso
tipo o cara se eu for aplicar o
holt-winters é um amortecimento
diferencial com velho e o sem bag tô
falando uma redução ainda 33% tá dia é
bem significativo nacionalidades também
né é encorpado essas habilidades
perfeita assim eu não quis gastar o
tempo de explicação sobre esses métodos
dia amortecimento especial porque como
foco é melhorar previsões eu tô
entendendo que ele até fazer um outro
papo depois eu explicando os métodos de
fato de você não você não me manda a
gente forte não
e o leão pode amor é esse só de
curiosidade e cs map com qual a
diferença dele para o mato que você
falando mas em que sentido assim é o
mapa e na verdade quando eu tô falando
de ele é o leão eu percentual mas os
valores estão muito pequeno esse treco
história e faz várias a gente faz várias
ele tem uma série de problemas tá é
conceitualmente ele tem vários problemas
assim na prática na prática galera pode
usar o mapa e sem muitos problemas mas
quase totalidade pequenininhos eu tô
falando muito de ganhar na vírgula né e
aí bem aqui nesse caso nem ela vírgula
eu tô falando quando a gente ganhou nem
arando a vírgula mas é dentro da
academia se tem uma percepção e mar
comprovação teórica de que o marco tem
um monte de erro enfeite monte
e aí vai se machucar ele vem para
corrigir a medida em que tem outras
medidas sem base a gente tem vários
corrigir em vários outros programas
porque também tem outros problemas tá
bom então então é isso cara a gente foi
a gente viu aí que deve em geral a
previsão de muito mais precisas do que
as versão ou seja aplicar bag dentro de
uma técnica significava gerar erros
menores tá é e aí o ponto faz é tá bom
você me disse que gera erro menor a
pergunta que eu e fica aí a porque né o
que que fazer isso aí e se você
e esse bacalhau todo aí você fez por quê
que isso gera dado é o que que gera
previsão melhor né e o problema é que
esse paper do do bergman no e do raiva
não explicava muito eles prestavam e
usavam berg e berg e na teoria não é uma
técnica de não é uma técnica de séries
temporais é uma técnica bem conhecida em
macho igor né e aí só que não tava muito
caro porque que você não estraga
funcionava né como eu era estudante de
doutorado é na época né o meu papel era
entender nessa depois que funcionava sem
entende a fundo o problema é
oi e aí até que a lógica de flores
princípios né que você vai entendendo
cada passo do problema para você
entender onde que dá para melhorar a
gente faz sentido né é
o que você entende por que que eu tava
com acontecendo você consegue talvez
propor soluções aí foi o ponto de tentar
entender por que que esse método
funcionava explicação é muito na teoria
muito simples tá ele está falando de
erro quadrático médio de previsão e aí
eu vou usar essa medida muito mais fácil
de mostrar o meu ponto né para falar o
meu ponto é o erro quadrático médio
previsão é a cara quanto que eu tô
errando sobre algo que eu previa algo
que de fato aconteceu tá é basicamente
isso tá deixa eu ver que esse esse erro
quadrático médio de previsão ele pode
ser meio que decomposto em três parcelas
tá uma parcela que é de variância que é
inerente do dado depende do modelo você
não tem que fazer
ah tá tem uma parcela de viés tá que aí
sim depende do seu modelo do teu
algoritmo que você tá usando e eles
estão fiéis ao quadrado em uma parcela
de variância tá que depende também do
teu modelo então essas duas parcelas
estão vendo a mãozinha quando eu tô
passando tá então essas duas parcelas
elas são controláveis de certa forma
essa aqui não é um cara essa aqui não é
não tem nada que eu posso fazer então
tem que atuar
e nessas duas então para errar e para
reduzir o meu erro de previsão porque eu
tenho que fazer ou reduzir fiéis ou
reduzir criança é basicamente isso então
qualquer momento o que é é na verdade é
por isso que não quer agora as
combinações fazem sentido tá porque é
porque no fim das fontes as combinações
ela é o avançar um pouquinho vocês vão
ver tá mas as combinações elas atuam em
algum aspecto dessa passagem dela por
isso que nenhuma solução dentro do carro
é ainda mais no volume que você tem de
missões onde há de fato a solução é a
enfim o resultado o método vencedor é
feito ele em geral é na vírgula né essas
coisas fazem muito sentido porque
qualquer ponto percentual que você ganha
só tá no que a você tá vendo uma
competição numa indústria de milhão de
milhão de trilhão ele fica muito
dinheiro né
e vale a pena então o que acontece
beleza só que ela decomposição do erro
quadrático médio de previsão agora
lembra que eu tô fazendo eu tô agregando
uma série de previsões né no fim das
contas eu tomei que fazendo uma média né
das dessas previsões que eu direi certo
vocês conseguem entender isso seja em
várias profissões e no final eu agreguei
tudo bem que como uma média então na
verdade a minha previsão é esse carinha
aqui né que nada mais é do que é a média
tão só uma de cada uma das previsões
dividido pelo número de previsões tá bem
é o número de amostras do scrap que ele
direita beleza e aí cara o que que eu
tenho que fazer agora eu tenho que olhar
para o viés e tem que olhar para a
variância não de som de de né que a
série única mas do conjunto né é olhar
para o conjunto então o seu olho para o
viés nada mais o viés do conjunto nada
mais é do que a soma de vieses de cá
e dessas previsões que ele que eu tô
gerando é dividido pelo número de
previsões então assim se vieres é
razoavelmente constante o que vai
acontecer que essas novas amostras o
sepe elas não vão fazer nada elas vão
manter o viés paradinho tá ah joão vão
aumentar o viés nem vou reduzir porque
se o viés há mais ou menos parecia que
em cada uma dessas as previsões que eu
fiz tão bom se fosse aquela uma
constante vai receber vezes a constante
/ bené a verdade própria constante tá
então a gente tem uma versões multitrack
aí é ele tem um com amostras
razoavelmente não via sagres o conjunto
ele era um exato também tá bom beleza
isso é muito bom tá já para começo de
conversa porque para quem já estudou uma
senhor não sabe que existe um trade-off
entre viagens e variância à medida que
você vai aumentando viés seja dos vales
e vice-versa tá é difícil você é meio
que ter as duas coisas difícil senão
impossível muitas vezes tá então cara só
de manter constante algo positivo aí
agora eu tenho a segunda parte cara se
você comprou aquela variância na verdade
que que ela é ela basicamente ela é uma
soma de variâncias individuais né / b ao
quadrado né pelo número de um machado
quadrados mas uma soma de covariância
está significa o seguinte que se essas
amostras elas são é independente nessas
regiões são independentes eu consigo
reduzir aquele treco a variância para
avaliar as variâncias e dividuais
dividido pelo total né por isso que têm
todos os pra tirar ocorrendo as criadas
da dele não da autocorrelação mais tá
correlação entre essas essas previsões
né e é
a beleza só que repara e para o método
que o raio mãe br quiser eu não tem nada
que eles fizeram ali trata da
covariância né para o fim das contas
como eles estão agregando um monte de
série o que estão fazendo no fim das
contas é reduzir variância por quê
porque ele está gerando bené velho
variáveis então tá usando aliança de
certa forma tá então só lembrando ele
reduz variantes se mantém isso aqui
constante só que ele não controla o que
acontece com o erro eu reduz o por isso
que ele reduz o erro então reduza essa
parcela mantém essa constante essa aqui
eu não tenho que fazer então esse essa o
final desse desse desse equação aqui que
é o erro ele vai reduzir essa parcela
ontem as outras funções essa aqui vai
reduzir e é por isso que bebe em
funciona tá é só que aí tem um problema
né
e quem disse repara que contra o
gerenciar as amostras essas amostras eu
gerei usando o sysprep então essas
amostras elas não são não com
relacionadas na verdade a correlação até
bem alta tá então essa essa parcela aqui
ela existe tá esse ela existe tem eu
tenho espaço para endereçar ela e
reduzir ainda mais a criança vai ser um
ganho expressivo cara não
necessariamente a pode ser um ganho é
possível reduzir covariância aqui já
tinha reduzido balança é essas variantes
aqui essa parcela gente reduzidos eu
reduzo essa que deixou valiosas a
variância total ela vai ser reduzida tá
e aí o os produtos lado do meu doutorado
foi basicamente pensar no método de
reduzir esse treco aqui tá e aí como que
a gente faz isso o método que a gente a
gente tem o nome de bag de conhecer ets
daí a ideia é basicamente a tua
é nesse pedaço tá o que tava faltando tá
isso gerou um paper lá na internet no
jornal for casting quem tiver aí na não
é à toa que estou usando meu nome é
porque eu tô tentando te explicar essa
história aqui e aí quem quiser enfim
quiser me pede aí o pede para o tal que
o que eu passo o paper também vocês
quiserem ler antes sempre foi achar
interessante porque não tem jeito você
faz paper para você e mais duas pessoas
leem né muitas vezes com você o reinaldo
falou para mim que eu eu mando fiquei só
é bom e aí como é que a gente dividiu e
cimento a primeira coisa foi entender o
que que funcionava no método do dr maria
a gente entendeu que essa geração de
amostras bootstrap para gente cara isso
tava perfeito tava ótimo bem feito
funcionando agora o processo
procedimento de gerar previsão de
agregar as séries para
o som tava bom né para mim não fala bom
era algo a gente poderia melhor melhorar
tá então vou passar rapidinho daqui a
grande diferença agora andar de geração
em séries eu passo a gerar um número
maior de séries e aí eu vou eu explico
depois o porteiro princípio geral new
séries hd sem tá beleza o curso é porque
porque eu quero ter meio que graus de
liberdade aí para poder selecionar
séries e sejam menos correlacionados né
entre elas é só jogar esse macacão
deixando
bom então os gatos eles diferem na forma
como eles temos seja com esse conjunto
de previsões é constituído tá é enquanto
método lado dos outros autores
consideravam todas as versões do chefe
na hora de agregar a gente vai na
verdade a considerar um grupo um pouco
menos que o relacionado entre si tá
justamente mitigar esse efeito a
covariância a pode ser algo sei lá
negativamente correlacionado cara não
porque porque se você fizer isso você
começa a afetar aquela parcela de
viagens né e aí tava forma você vai vai
reduzir variância ela vai aumentar viés
então é isso aí é um é uma dança sem o
jogo você tem que fazer é
e então como foi a nossa ideia para
gerar um conjunto menos foi relacionado
thiagão se eu tiver aí do rápido e você
quiser me parar esse a pergunta ela me
falou tá tranquilo pessoal então dá um
ok
eu só queria acompanha aqui ó ó eu aqui
oi daniel daniel não conta né beleza uma
ligue não podem disponibilizar o slide
no final e aí vai disponibilizar depois
beleza posso problema é é bom então para
criar um livro tá falando aqui que
podemos seguir ele bola é tão para criar
um conjunto - correlacionado a ideia é
que a gente ter casos tanto várias
coisas em nada funcionava direito eu tô
só uma solução analítica e meu nível de
matemática era era muito baixo eu acho
para para sair com solução analítica
funcionário funcionasse no tempo ter eu
tinha não sei nem se existir ali a prova
esses dias mas assim é eu não tinha
tanta eu achava que dava para sair de
outra forma tá e aí fica aí até porque
fica aí para quem quiser
o site uma solução analítica para isso
cara eu eu boto fé e e pode ser com
autor de vocês aí vocês quiser é
basicamente a ideia que a gente fez foi
cara quê que acontece como é que custa
response o não né coxa idealmente quando
eu tô construindo um coxa o que que eu
quero eu quero que as observações que
estejam dentro de um coxa sejam muito
parecidas né agora uma observação que tá
no cluster eu quero que seja parecida
com uma observação que esteja em outro
costa não eu quero que as observações
que estejam com esses seres diferentes
sejam o mais diferente possível né o
sejam costa na teoria ele deveria
separar muito bem de outro coxa né ou
seja a observação estão ali dentro no
meu caso falando sério tem coragem então
as séries temporais que estivessem
dentro de um cluster elas deveriam ser o
mais diferente possível das séries
temporais que
o outro costa beleza então no momento
que eu gero mil cores mil séries e
posteriores as séries é a ideia é na
teoria muito simples agora falando não é
óbvio que eu morra quebrei muita carne
da estratificação cara perfeito então
não é porque eu trabalhava de
estratificação me ajudou muito essa
noção de estratificação ok é isso né
você vai fazer e aí na verdade foram
muitas conversas até com meus amigos
almoço deles lá de vegeta é cara quando
você tá falando você tá pensando no
costa aqui é coisas parecidas sejam ali
dentro coisas é diferente estejam mais
distante possível então se você pôsteres
aquelas 1000 séries amiga essa na cara
isso eu era assim realizar essas
utilizar essas mil e selecionar sem é
pela
é indicada costa e talvez um conjunto um
pouco menos parecido entre ser talvez eu
reduza é a correlação né e covariância é
aí cara a ideia foi essa basicamente foi
essa aí cara isso gerou uma série de
direto né você fazer isso é isso gera
uma série de desdobramentos né então
tipo a ideia como a ideia do coisa é
maximizar a similaridade do grupo e nem
mesmo minimizar qualidade entre os
grupos o seguinte resposta exata e aí a
minha expectativa você selecionar sempre
diferente eu ia ter um conjunto em
setembro um pouco menos correlacionado e
se ele fosse um pouco menos
correlacionar as as previsões também
seria um pouco menos ou relacionadas lá
e aí quando eu agregasse no final das
contas eu reduziria aquela parcela de
covariância que existia lá dentro
daquela criança que eu mostrei pra vocês
não faz todo sentido é hoje faz nela
em uma época foram algumas noites aí de
bateção de cabeça errando né aí a ideia
era como operacionalizar isso porque o
método computacionalmente intensivos né
porque esse cara pensa que só ia gerar
uma série aí agora eu tô te falando que
na verdade não vai tirar uma série
também não só vai tirar previsão para
uma série você vai gerar 1000 série vai
gerar previsões para 1000 séries depois
você vai fazer uma coisa que eles ação
em cima de 1000 séries depois mais
difícil né uma pergunta que uma pergunta
responder a quantos feliz você vai vai
fazer né que é uma pergunta de
aprendizado não supervisionado né que o
cara eu quero fazer isso de forma
sistemática não quero na mão no olho
selecionando número de coisa né conferir
e mais eu poderia gerar a morte séries
muito esdrúxulas malucas eu não gostaria
que isso acontecesse porque impactar o
meu o meu viés não fez a pergunta que eu
tava em mente aqui quase
o que usou para clusterizar acho que não
vai precisar ele já a cristalização ela
acontece é uma coisa realização de
séries temporais é nesse caso eu usei a
distância euclidiana tá e aí não é uma
uma noção para passar com eu meio que
bota uma série guardar outro e vou
comparando ouça ponto tá cada sério
beleza existem formas de você com
esterilizar usando metadados dessas
séries tem o raimundinho trabalho
importantes sobre isso mas enfim não não
cabe aqui acho que dentro dessa essa
formas na verdade é até uma boa ideia tá
como forma de melhoria que provérbio de
coxa e testa é constituída usando esses
metadados mas não usamos é então cara a
forma de evitar acessar desejos foi cara
nunca usar o caminho já vou usar tipo
carne androides né porque porque aí
e aí deixa trabalhar com a média né dos
centróides vou trabalhar com a mediana
do centróide então porque aí eu evito um
pouco essas coisas aí por isso esse
algoritmo pan e por que ele também era
muito rápido não é para processar tá é e
aí a segunda pergunta era o número de
coxas cara você pode fazer várias formas
seja na mão seja fazendo validação
cruzada é o seja e usando o método aí
nesse caso dos mestres da silhueta ele
tinha uma heurística no fim das contas
selecionar que não fez uma pergunta que
interessante problema na transformação
dos seus algum tipo de normalização
e a transformação dos dados ela seguiu a
mesma lógica do lado do do br mas o
rayman né ela começa lá no início com a
transformação box-cox tudo começa com a
transformação box cox e tudo termina com
a inversa da transformação box-cox né
que você faz tempo depois você se
transforma beleza
a intenção não sei se eu respondi aí é
bom e aí usei o cimento da silhueta né
no final que eu passava isso aqui era o
berg de ld mbb até ser o método que a
gente tava olhando ao invés de eu ter um
tipo de série né eu tenho vários tipos
de sério onde aqui onde cada cor faz
parte de um coxa é o mesmo tá aí mais
colorido então cada série em cada cor é
um crush então vou selecionar dentro de
cada um desses custos aí a única
pergunta que fica beleza mas quanto que
eu seleciono em cada cluster é porque eu
tenho série e já tem um número diferente
de cada coisa era ia chega uma tô bem e
quando ele foi fez a a falo sobre a
fisiologia com amostragem estratificada
né seleciona cara cara não tem uma forma
você pode pensar né que você quiser mas
proporcional ao tamanho
e me parece razoável tá aí foi que eu
quero que eu fiz né é só que quais
proporcionais ao tamanho né porque bom
ficou que eu tenho um pôster com 20
séries eu tenho que selecionar duas
séries mas quase duas ali de leandro eu
vou selecionar aleatóriamente ali dentro
aí não o que a gente fez foi fazer uma
etapa de validação daquelas exale dentro
também então na verdade a selecionarem
as duas melhores dali de dentro tá
o ok isso de novo para evitar também
aquela parcela de viagem porque ela
parcela de viagens ou menos assim e aí
no final das contas eu ficaria ao invés
de mim eu ficaria com 100 e agregaria
sair sem séries beleza então o a minha
previsão seria um treco meio que aceita
vendo cores diferentes vem de conhecer
os diferentes e aí é esse isso aí é o
esse método chamado deve-se conhecer lts
eu vou mostrar aqui rapidamente onde que
a gente aplicou e por que tu vai se isso
funciona não funciona em onde que é eu
vi essa funciona e onde que a gente
aplicou está a primeira coisa foi
aplicar onde os autores anteriores
aplicaram então no caso foi m3ta é
e nem me três vamos lá
o olaf tá acabando m3 essa abordagem
nossa ela gerou resultados melhores do
que tudo está então assim é inclusive do
qual a gente tava querendo bater tá dava
resultado os melhores tá que era esse
berg de pele de mbps o nosso abordagem
obter resultados melhores e foi melhor
resultado de sempre triste isso para dar
dos mensagens quando a gente está
falando de dados trimestrais a gente
começou a perder e aí tem um motivo
muito caro porque tem menos dados tá é
quando você passa a falar de dados
semestrais a gente tá falando menos da
diz o esse método ele é mais conselho
diferença posso falar isso mas ele é
mais computacionalmente intensivos do
que o que o outro né ele fazer mais
coisa então tem mais locais onde falta
de dados é mais crítica né me dados a
nós também a gente perdeu mas diga-se de
passagem tiberghien já não fazer
e também não bebe e também não perdeu o
e quando a gente passou a falar de dados
trimestrais e dados anuais tá outra com
outro dado que a gente comprou foi nessa
competição que foi nessas iff 2016 a
competição achei que rolou e a nossa
abordagem para dados artificiais lá já
competição também foi melhor do que a
gente todos ficavam lá e aí tem um ponto
interessante que tinha lá um ensemble de
lsb msn é um tipo de arquitetura de flor
né é de redes recorrente já é e a gente
bateu né bateu com folga essa essa gente
tá é para dar dos reais a gente perdeu
tá que era mais adaptativa e foi pior
agora considerando tudo a gente perdeu
uma perdeu por pouco tá aparecer
conjunto de ali é cm tá e até se e aí
tem uns interessante porque o autor de
ser
e esse método aqui foi um cara que na
época trabalhava na microsoft e depois
foi para o uber esse mesmo cara foi o
cara que ganhou am4 depois tá esse mês
momento tá e aí é o que eu vou mostrar
ele quatro ele teve um grande
diferencial porque antes eu tava falando
de celular 20 poucas séries né no sif já
nem lembro se a gente pouco 40 em poucas
séries ele am3003 séries que você tinha
que prender nem me quatro a gente tem um
desafio porque eram 100.000 séries com
frequências muito variadas tá e aí cara
prever para sem o sérgio condado inter
intencional então não tem que ser isso
não computacionalmente intensivas foi um
desafio significa que ele teve que subir
crush tem na w a s d fazer um monte de
coisa eu tive que paralisar o código e
fazer um monte de coisa para comer dar
esse dinheiro para dar tempo de chegar
no final da
e a submissão né é a gente fez o
resultado cara não foi tão ruim ele
ficou bateu todos os feitos marcos
existiam bateu sócio aqui que que
existia então você tem lá orquestra ó é
bater o banco que que tava lá dentro
participando então elas fargo participou
se você pegar um beijo ficou tão mal
assim comparado com os resultados
vencedores tá e aí o interessante aqui
no brasil teve o cursor louzada lá da
usp é participou e foi bem ficou ficou
bem colocação boa vou usar o chute é eu
tava no sinapina que ele fez aquele
aquela previsão lá para a copa do mundo
né ela lembra da palestra delia se você
não acredita em está isso eu acredito no
povo né que serve o povo do fantástico
naquela época que tá acertando e o povo
é a voz de deus vai botar o povo lá do
fantástico
é muito bom a população eu era uma
e eu lembro de decidir aí a cara assim
eu acho interessante era o seguinte é a
senhora uma competição de a gente tinha
gente da indústria e gente da academia
então você olhar e tem óculos pô harvard
tem um monte de lugar é puxado e você
participava da seguinte forma você
submete os resultados e você não tinha
uma líder board do tipo do que algo que
você vai acompanhando vai meio que o ver
titã da leader board né então não
acontece isso eu subi netinho e depois e
esperar e aí um evento que acontecer
hoje todo mundo ia nos estados unidos
então foi lá no da casa tava também lá
na universidade de colorado em boda e aí
todo mundo foi e aí eles apresentaram
resultado na hora na frente eu tava com
caça né porque por no meu celular não
queria pegar o resultado ridículo né e
eu respondi foi bom você mandou o
currículo para ele
e dentro do esperado não conseguiu carta
melhor resultado ficar fui aí para mim
foi excelente e ideal para entender o
que que o que que deu certo e que não
deu certo para mim foi encontrado
importante na verdade é o nos principais
pontos né tanto faz doutorado é entender
tem que dar certo que que não dá certo
porque da serra por que que não dá certo
né isso assim a metodologia ela
funcionou e graças a deus eu não passei
vergonha na frente do primeiro dos
resíduos depois de gente boa da
indústria e depois a gente volta
academia né então assim só para
finalizar cara o que a gente viu
conhecimento do foi que basicamente a
gente sabe eu não mostrei aqui cara tem
bem mais extenso mas enfim várias
simulações a gente mostra que esse
método de fato
o brasileiro em pensei se não conseguir
ver consegue reduzir a parcela de culpa
aliança o número de coisa ele tem um
papel muito fundamental na forma como se
como método vaga não e aí esse é um dos
motivos na verdade do método da gente
ter ficado nessa posição e a gente não
conseguiu fazer validação cruzada né
utilizar um monte de coisa a gente só
fez para entregar os resultados
empíricos mostraram láctea e essa método
bastante possível de gerar pelo menos
isso em média na rede gera resultados
melhores do que as combinações e o berg
existe para série séries temporários
hoje então esse é o estado-da-arte berg
e abastecimento referencial ou menos até
onde eu sei é e aí é um ponto é usado
funciona e ele funciona dentes sônica
dados mensais né começa você tem mais
dado né mas a lógica de combinação ela
continua valendo tá é a gente ia agente
k
há várias possibilidades daí pra frente
primeiro a gente pensa que a gente a
grupo essas séries meio que na média na
mediana ou seja quando faz isso a gente
dá o mesmo peso para todo mundo quando o
cara mesmo que poderia dar peso
diferente que o gerará resultados
melhores ou piores e aí tem forma justa
fazer isso a gente já pensou agora desde
o outro ingrediente bush para fazer
exatamente as etapa final é de flor
exatamente fazer essa etapa final e nem
tem forma de você combinar uma abordagem
estilo de vida na cidade resultado
principal foi foi uma abordagem híbrida
tá e aí de volta direto de decomposição
que não é sério que vocês poderão
encantar e principal pão eu acho que
negativo desse método é que na verdade
era um método computacionalmente muito
intensivo né quando ele gente ficar
longe dos seus ar ele é para ir ao invés
de usar duas o outro tipo de método tá é
o nome do pai
e ai george girl forma das séries
temporais lembrava console com foi
bastante eu eu gastei eu gastei uma vela
pesada aí de pesquisa do fernanda é a
pra poder rodar não estou feliz da vida
essa é mais caro acho que foi foi bem
relevante esse trabalho ele assim dentro
da academia e dentro dos principais
revisores atendeu no fim das contas
caras está no ambiente cutiano né de
previsão de séries temporais algumas
pessoas relevantes atuam né que é
basicamente essa comunidade do df na
internação de on forest edwards dessa
galera da austrália tem uma galera na
inglaterra como é que todo mundo se
conhece então quando esse feito ele foi
para submissão a bastante claro até
pelas dúvidas quem eram os revisores que
estavam revisão quero que a gente já fiz
com graça de fazer as vezes de perguntas
e tal quando pega foi aprovado cara as
pessoas estavam anos parabéns
o numerador é uma coisa bacana ela vai
fazer o responder delas que ia acontecer
esse ano no meio do ano em julho e vai
ficar por conta do corinthians eu
cancelar eu tava acontecendo que vem o
internet exposição forcast vai ser a puc
esse ano é ano que vem agora no caso né
e isso é o principal item de previsão
então se você entende que a samara que
você quer dar assistência está chegando
para onde o raio plantar olha a chance
dele cara tiago iso que perguntar coisas
você tá em contato então essas não
conhecia o cara que desenvolveu a parte
the deep lane de previsão de séries
temporais dos 76 e ao gerente de da
grécia sem conhecer afirma conversar de
tomar cerveja é esse cara verde uma
dessa ele veio para o brasil chama ele
pena porque ele do palestra assim é um
ambiente legal e indústria e academia
um e-mail quando está dar esse método
que eu falei ele tá disponível no detran
pe eu tinha prometido fazer um pacote lá
nunca fiz então na verdade ele tá com
uma função lá dentro quem quiser usar e
talvez até me ajudar aí para eu tô um
pouco preguiçoso de mexer nessas coisas
e e adulta e me funciona perigoso abrir
colocar trabalho a bolsa que você usa as
funções que eles querem você é chato
ficar dando manutenção no clã ficar
subindo por não grite ramo é muito mais
fácil de você dar continuidade na minha
opinião não sei essa planta um negócio
né the global e tal o pessoal vai usar
globalmente o código então né e que
talvez nem tanto é mais tem outras aí
também né mas fazer o quê exato concordo
caro plataforma de colaboração e a gente
o pior que se vocês não usam seus
deveriam usar é então meu ponto ela se
vocês quiserem dar uma olhada o código
talaria completamente aberto melhorar a
perguntar preferência a contribuir acho
que vale tá tem uma pessoa mexendo essa
foto parece que foi sensacional tem mais
realmente pouco mais de 70 pessoas aqui
assistindo o negócio foi doendo nem
pegar a pessoa que está pedindo desculpa
é o davi que eu acho que tá na cola na
financeira nessa live ele é aluno do
ferro do cirino e a gente foi adianta
ele na no mestrado é legal ele tá
olhando para histórico também então
assim pessoas que tiverem interesse
nisso conversa em vez em quando havia de
preferência não tem que fazer mas se ele
quiser também fazer uma que com a gente
fica à vontade de ir tranquilo deixa eu
te falar um negócio uma doença existe a
soma soma então eu vou ter aqui
questions mas na verdade agora é mais
que um ask me anything tá bom então
qualquer coisa desde é da escola até
esse modelo eu posso responder essa
potência de dados enfim já tem uma
história as realmente referir muita
coisa bati minha cabeça já é bastante
acho que tá aberto aí para vocês fazer
um esperando vocês quiserem mas
e deixa eu acho que é só de curiosidade
mesmo né de existe modelos irá atrás tem
coragem existe e o principal é
desenvolvedor é o ramon ele resolveu uma
série uma série de coisas em eu chamo de
raiara que eu tá em sines e ele tem uma
série de porque esse é um problema que
na verdade qual que é o problema do da
hierarquia né é como que se reconstrói a
medida que você faz você pode fazer o
top-down bottom-up né agora o problema é
já conciliar né você faz a previsão aqui
casaco aqui em cima e aí é um problema
matematicamente complexo tá é ele
resolver os problemas na verdade tem
alguns alunos resolvendo isso e sem
existe existe pacote no erp para fazer
esse é o melhor professor luiz paulo
sérgio inclui
o próximo aí 21 horas ele vai fazer uma
live aí de data vir junto com o rafael
também é o último próxima do lado da
serra hoje vai fazer aqui com a gente
autole do do do análise de dados né
manual de análise idade vai ser essa bem
legal também se quiser assistir para
convidado também né fica à vontade na
cana deixa eu te falar eu gostei sexo
perguntas durante a live que a gente não
respondeu a lívia ela mesmo deixa eu ver
aqui ela perguntou na hora que você tava
falando bag ela perguntou tio aqui
a autocorrelação entre os blocos é que
seria artificial gerada pelo bootstrap
certo para o drag a autocorrelação entre
os blocos na verdade dentro do bloco
existe autocorrelação entre os blocos eu
mitiguei né porque seu são entendo que
existe uma eu já está componente de
tendência e componente de sazonalidade o
que sobra é meio que ruído então se
existir ainda outro correlação eu na
teoria como faço blocos de mesmo tamanho
assalto com relação a ela vai existir
dentro do bloco mas entre o bloco ela na
teoria é desprezível mas sem marca aí né
é definição do tamanho do bloco em geral
e tem formas para fazer isso no nosso
caso a gente botou motor meio que o
dobro da frequência tá então candidados
duas netas das mensagens em 20 blocos
também 24 ma
eu tinha muito mais tentativa e erro do
que do que uma ciência tão racional é
cara se eu colocar mais do que um dado
eu consigo capturar até a sazonalidade
talvez ainda tenha ficado ali tá vou
pegar a sério racional olha exatamente
outra pergunta que era eu costumo ter
dificuldade foi 27 por exemplo modelar
uma taxa de inadimplência com variáveis
macroeconômicas quando surge uma crise
política ou então previsão de demanda
quando surgiu uma pandemia uma fazer
para tratar esses eventos e uma
modelagem de podcast foi essa pergunta
que ela fez a pergunta é difícil né que
tá todo mundo se fazendo cara todos os
modelos funcionavam até antes da crise
né porque porque a beleza eu eu sei
lidar com uma crise de 2008 eu não sei
ligar lidar com uma crise onde teve um
economia desligou ana é praticamente
então o que o ponto aqui é caras
idealmente deve
o luiz que se adaptassem rápido a
mudança tá então toda classe de modelos
onde você consegue tratar rápido a
mudança e tem parâmetros certa forma
variante no tempo seria um modelo que de
ver melhor tô na minha cabeça tá bebê
melhor nesse momento tá então esse é o
primeiro ponto segundo é para você vai
ter que conviver com o erro tá eu erro
vai ser maior e não tem jeito de ser o
ponto é para quê que você quer essa
previsão né que dependendo do que você
quer fazer uma previsão não é o melhor
não é melhor casa né uma previsão de
séries temporais a vez melhor caso é
meio que gerar cenários onde eu tô
expostos foram disposto tá você vai
depender muito muito do teu problema e
como eu falei dados de séries temporais
em geral a gente olha para o passado
para previsão futuro né
olá tudo negócio ali que você me
precedente o que que eu passado que eu
consigo eu consigo olhar né é difícil é
não eu não tenho uma resposta para isso
não que o que está muito na minha cabeça
que em fim de discutir o leque
claramente a gente tá tatu a paz atuar
em um regime diferente tá e aí modelos
que trabalham com mudanças de regime de
certa forma deveriam é também acomodar
melhor essas coisas tá máscara previsão
serão ver um fraco difícil esse acho que
todo mundo está você vem falar que sabe
o que que vai acontecer nada com três
meses caramba só tá mentindo cara não
tem como saber se ninguém sabe a
extensão do estrago né
oi e aí o periquito maligno também tinha
uma pergunta aqui sempre é necessário
transformar uma série temporal e uma
série estacionar para obter melhores
resultados depende depende depende do
método que você tá trabalhando preservar
uma tem pressuposto de estacionariedade
meio por isso é precisa fazer em vários
outros métodos dos existe esse
pressuposto a e aí como está falando de
econometria também e aí se você não tem
estacionalidade muitas coisas não várias
passa puxar coisas lá de cointegração
que você tá falando sério múltiplas e
isso vai ao muito tá variado tem modelo
que você sabe é que se você estacionar
alisar uma sério enfim para
transformando uma série que toda vez que
se transforma você perde a forma alguma
coisa né perde informação então é
ensinar a escolha aí de vai ganhar eu
de um lado e perder em outro lado você
tem que avaliar o que que que compensa
mais para você a luciene ela tinha
falado que queria ouvir novamente a
última frase na seleção que não aumenta
viés e não lembro agora exatamente
também como é que é ela ela qual que é a
frase é passou muito passou muito tempo
luciane você lembra alguma coisa é a
seleção de séries dentro de cada cluster
de forma que não aumente o viés
ah tá que é o seguinte é seu gerasse uma
é realmente tu não entendeu o que eu
falei ontem uma área do que eu tô
passando super rápido né mas fica
acontece essa previsão ela lembra que eu
falei que eu quero selecionar caras meio
que diferente vai para gerar um enfermo
seja um conjunto um pouco menos
relacionar eu levo o seu começa a
selecionar caras muito diferente não é à
toa que eles estão diferentes né muitas
vezes ele tá diferente porque é uma
série que tá meio que mal feita né então
tem uma coisa esquisita e ela vai gerar
uma previsão meio esquisita também não
se ele gera uma previsão de quesitos que
acaba acontecendo é que eu vou errar né
previsão mais eu tô errando eu tô tendo
correndo no programa de viés aí tá e eu
quero evitar que isso aconteça para
evitar que isso aconteça eu meio que faz
uma validação cruzada ali dentro do
dentro dos coster está aí foi isso que
eu passei rápido como que eu faço uma
validação cruzada
e para um pedaço dos dados tá então para
o temporalmente um pedaço dos dados
então o que que tu falou não tô querendo
te conhecer então só tô querendo te
dizer ela janeiro dia de janeiro de2005
em dados de janeiro 2.002 a a janeiro de
perdão a dezembro de 2019 eu separei
especialmente entre dezembro de entre
janeiro 2019 e pedaço de janeiro 2019
dezembro de 2019 como meio que um
conjunto de validação treinaria de
janeiro de2012 2002 a dezembro de 2018 e
faria previsão para esse período de
validação que eu conheço esse ia gerar
uma enfim várias métricas de ali dentro
e o seleção e aí eu conseguiria meio que
ordenais séries que estão gerando melhor
tá ali dentro dessa validação e aí
quando eu tenho que selecionar você
selecionar uns poucos fazem duas realiza
selecionaria
e aí de menores eu tenho um impacto
titãs o viés tá eu tenho curso de fazer
isso porque como eu tô gerando série de
menor erro dessa forma que nessas séries
são meio parecidas né é isso assim
também aí eu tenho um pouquinho de
covariância mas é o que eu falei uma
dança né ao menos um pouquinho de um
lado eles um pouquinho do o altair
perguntou que você recomenda o
referência além do for casting
princípios em partes
o cara tem uma área de séries temporais
ter mais literatura extensa e depende
muito do que você quer tá é ir minha
experiência com séries temporais aqui
dependendo do livro que você lê eu acho
que a galera de sete temporais e
econometria e me desculpe aí se tiver
alguém lendo eu acho que as pessoas
complicam lotação para ou para parecer
inteligente ou para o para o para sei lá
por quê porque motivo para ser o mais
preciso possível mas fica muito difícil
de ler depois né e aí dependendo do
livro que você pegue pode ser que
anotação seja enjoado perde um tempo
muito mais tentando entender anotação e
ainda aparece aquelas letras horrorosas
e tal mas são necessárias muitas vezes
você entender é daqui ativamente no
método né então outras referências que
eu acho melhor ficar assim vamos lá é
tu tem cara de tem livros têm livres que
são enfim se você está em certa pressa
tem que já ter passado algum momento da
em português tem aquele do morettin mas
eu não acho não acho aquele livro que
você deveria começar por ele tá aqui
para mim o livro de consulta tá depois
você olha escrever eu acho que ele e ele
vai no nível que você precisa de uma
explicação de alguém ali para ela mas
para mim tá foi assim aí pode ser que eu
sou meio burro também mas a galera é
talvez tenha a mesma idade que eu acho
que o livro do renilton tá ensino
zaneles ele é meio que uma referência
quase todo mundo ler esse livro é
bom então tem uma retinho e tem esse
tendo remilton é aí começa a entrar nos
temas muito específicos né então tem tem
um autor lá em professor da universidade
de cambridge e é o
o rapaz esqueci o nome do cara é que
basicamente ele tem uma visão
frequentista do modelo de espaço de
estado está então com essa visão
frequentes do espaço de estados ele te
ajuda a entender um monte de coisa né
mas é um livro aí também é difícil de
entender para entender a lógica porque
no fim das contas espaço de estados é
uma lógica quase speziano né das coisas
tem livre domingão né daí nem me criar
modas uma coisa assim também é uma
referência em previsão de séries
temporais de 13 anos tá e aí altair acho
que você tá na se for mesmo alto aí que
eu tô pensando que nós rj diferença o
igual um eles ele tem um material muito
bom disso né é só se tem vários já cara
eu acho que o ufpb que foi isso que ele
falou ele tem uma grande cima vantagem
que é primeiro ano foi feito pelo
rhaylan e o raiz marea
a previsão de séries temporais segundo
ele vai numa linguagem muito simples de
entendimento e com código em baixo tá
com código em r embaixo a cara para mim
eu não sei como é que funciona para as
pessoas não foi a melhor forma de
aprender algo é a programar esse treco
que eu tenho que entender a fundo o que
tá acontecendo e aí o esse livro aí ele
tem porque se que estou zen crafts algo
sinta que esse livro do rayman para mim
é o que eu sempre recomendo que ele é
bem bem didático tá beleza vamos fazer
uma pergunta então aqui me fora aqui
você acha que esse conhecimento
aprofundado é necessário para era de
dessa estatística mais trivial é mas tu
viu a resolve a maioria dos problemas
o que você acha que conhecimento
aprofundado é necessário para área de ds
o estatística a mais trivial resolve a
maioria dos problemas ele tá perguntando
se precisa ter horário essa pergunta é
acho que tá perguntando se precisa ter
doutorado minha resposta para você eu
vou te dar o porquê que eu fiz doutorado
e depois vou te dar uma resposta como
chefe da área de sentido de malha de ser
de dados e precisamos não precisa e o
que que minhas impressões na doutora a
primeira coisa eu fiz doutorado porque
eu tava começando a achar que eu tava
emburrecendo tá é quando eu tava ao
longo do tempo assim achar que eu estou
chegando em casa jogando videogame
fazendo coisa hoje do tipo eu achava que
tava com muito tempo então ele vai ter
um doutorado que achava que eu tava com
stephanie a chave tava esquecendo as
coisas mesmo amarela seus filhos eu
esqueci dinheiro nos fez tá aí foi por
isso que eu entrei no doutorado eu acho
que é né
o horário é como aí falando como gestor
eu digo que não não não acho que é
necessário dependendo da onde você é vai
trabalhar tá e aí a minha lógica é não
sei se você em janeiro um livro do peter
tia o que é vamos ver o último ano se tu
tem um caseiro leio né mas é uma lógica
é que a maior geração de valor acontece
quando não existe nada e você faz alguma
coisa e essa muita essa alguma coisa
quando ele está falando em face de dados
muitas vezes é quase que política tá
esse a nada eu fiz um modelo de
regressão linear e já está quase dois tá
eu fiz um algo relacionado a negócio e
que te deu uma informação relevante cara
de jardim valor para caramba tá então eu
acho que ele que não é necessário fazer
doutorado para estar nessa área eu acho
que é preciso que
a lição das coisas tá pelo menos é do
por que que você tá fazendo eu acho que
alto é meu ou seja machine learning
automático não resolve o problema do dia
a dia tá de dado se trabalho evoluir e
melhorar talvez vai passar resolver tá
mas eu acho que a vida ela é bem
diferente do que os problemas do que
água tá e aí muitas vezes saber um pouco
mais aprofundado ajuda mas não acho que
é fundamental então respondendo não acho
que você precisa de doutorado para tá na
área tá então cara ah desculpa aí o que
que tu cobra para minha impressão de
doutorado que eu falei que ia responder
para mim foi ele diferença é difícil
porque ela ia trabalhose então significa
14 anos de muita madrugada aí
e é mas eu tive muita ajuda do de onde
eu tava né porque eu tava no ibge meu
chefe era eu acho que eu tava
dentro de uma área que era uma área de
pesquisa então eu conseguia fazer muita
coisa né então assim a galera meus
amigos do ibgm e ajudaram muito tá para
fazer isso eu não tinha filho na época
então também me ajudou muito nem a minha
mulher me ajudou muito tipo me ajudar
mesmo assim de debate que eu precisava
então assim é bom tomar rede de apoio tá
para fazer e eu e mais assim no fim do
gelo de muita sorte dentro do outro lado
primeiro porque boa parte do doutorado a
escolha um orientador que muda seja
parceiro te ajude isso eu tive enfim
desde antes de entrar no doutorado tá é
a
oi e aí tela estão as limitações macho
cobre porque senão você termina de 4
horas e serão chega no final tá é e eu
dei muita sorte da pesquisa que eu
comecei a fazer ter ter acontecido no
ambiente onde cara o cara que mandou um
presente e o paper dele só foi ficar
pronto no meio de dois anos depois eu já
tava trabalhando e eu errei muito pouco
o sorte tá em muito pouco por sorte
muitas vezes as pessoas doutorado
esbarro em caminho sem saída e eu não
esbarrei quase nenhum caminho sem sair
então as coisas foram andando de forma
muito muito suave tá mas é trabalhoso
trabalhoso e não não é um passeio do
parto da se vai você vai sofrer vai se
vai se questionaram o efeito a síndrome
do impostor ela existe muito dando
doutorado que você sempre acha as
pessoas 300 milhões de vezes melhores
que você é
é mas deus horário um caminho
persistência de ser o final dos pessoas
mas a minha aqui traga um caminho de
persistência e saber fazer as escolhas
né mas corretas né e eu estou me ajuda a
bastante depois é a nossa vida né é meio
escolher no início fazer as perguntas
que eu deveria tá fazendo né pelo menos
o ponto de vista técnico tá tudo bom
aliviar concordou aqui com você na
concordo plenamente com você fez
frequentemente pessoas buscando
alternativas das de automático lane e
sabemos que modelar vai muito além disso
tem até um meme né que eu fiz uma vez tá
garota garotinha assim né aí atrás no
fundo tá a casa pegando fogo né eu botei
a você você quer aprender estatística
você quer saber modelagem sem saber
estatística você vai colocar fogo na
casa que nem garantia 1
o trem tem muito tem que saber né tratar
os dados e cara eu já eu eu fiz bastante
e bastante consultoria na vida né eu já
vi cada coisa que é nem fez eles
ficariam meio partes ficaram preocupadas
ou raridades e tem gente que vende só
ficamos sabendo mínimo né então é bom
ficar ligado assim é bom ficar ligado
show de bola quer tá um pouco queria te
agradecer mais uma vez foi foi
sensacional lembrei aí de conceitos de
séries temporais depois utilização até
de amostragem lembrei aqui bacana foi
foi muito legal né e acho que o pessoal
curtir demais a gente tá com pergunta
até ano que vem né eu deixei lá na
descrição do vai ficar fazer a pode
fazer a cara eu tenho tá disponível
porque fazer pergunta que depois eu
respondo
o braço perguntar agora porque o
ah vixe mas não vi aqui eu não sei e aí
eu tirei a noite para responder isso
desde queira e nalva falou assim ao se
comparar duas ou iniciantes temporais de
de parâmetros diferentes haveria alguma
normalização e considerada a mais
adequada pela para interpretação dos
resultados ou você recomendo nesse caso
o box duas séries temporais de
parâmetros o que que você quer dizer
como a série um parâmetro de uma série
temporal superior para entender né
e eu acho que ele tá falando
comparadores tipo aí mas tem alguma
coisa nesse sentido colocar a culpa é
isso tá comparação entre modelos é
benéfica no sentido de no final de
agrupamento está se poderia fazer e aí
usar um crescimento exponencial de turvo
em o reta parte do teto e depois
combinar tudo no final poderia tá ela
tem nenhum programa e fazer isso na
verdade é tá bom vocês põe o teu
resultado a valores mais diferentes tá e
era um ponto de pode ser explorado sim
e agora tem que lembrar de combinar o
daniel ele perguntou na definição do
número de creches de seu método qual é o
último validade do número de classes é
uma questão de idade de processar ou de
previsão o número de câncer eu acho que
é de tudo né se você fizer com mais
flash não sei que não é uma dificuldade
for necessário que você já calculou as
distâncias calcular as distâncias que
ela quer o complicado depois aplicar o
método não é tão intenso eu acho ódio
que você tiver um método que de
clusterização que use modelo por trás aí
você vai ter mais demais mas dor de
cabeça é qual que foi por você pergunta
te falar deixa eu falar uma conta nessa
brincadeira quanto mais ou menos você
gastou lá na amazon com costura cara
vamos lá vamos lá eu eu fiz isso não
período no p
eu não sabia nem a primeira coisa eu nem
sabia subir uma essa dois tá na época
hoje acho que o que eu sei não sei não
não sou engenheiro de idade mas eu sei
alguma coisa tá então começa a daí tá
então eu não vou te dizer da forma que
eu que eu deveria eu acho que durante a
competição aí eu gastei aí um mas do
resto tá não é o que na muito muito mas
mas eu fui para mim não queria gastar
com meu bolsa isso aí então eu usei na
época o fernando ele tinha uma esfera de
pesquisa a gente usou é alvo de pesquisa
porque era para pesquisa de fato de água
da puc porque é uma outra possibilidade
é usar os pôsteres da puc mas como o
carão como o fernando está de falar que
era um péssimo aluno da puc não gostava
de papo que tem que ficar fazendo e
perdendo tempo lado e lembrando que o
boneco que eu já trabalhava da
a fazer a consultoria então eu tenho que
era militar que você se eu pudesse
acessar de qualquer lugar uma máquina
potente aí a w é servir basta na verdade
eu usei a ws eu usei a nuvem do google
né gcp é que basicamente e mais
basicamente que usava cara era servidor
lindo tá então usava servidores lilo
mais potente e mais potente significava
com mais núcleos tá porque porque como
eu tinha paralisado partes do código
significava que eu distribuir os
cálculos né então quando eu mandava por
11 coisa por um ficam service o celular
com 16 coxas 13264 coisas significava
que ele fazia outra coisa do tipo 1 64
ovos do tempo né porque basicamente o
paralisei o código tá para a gente sair
vamos falar sobre vamos ser sincero bem
que eu também fica no final é pedaços
ficar bem
o código também aparelho dizer que dá
para aparelho usar rápido deixando o
código rodando com o tempo que eu tinha
um
e o renato nery fala thiago vocês
utilizam alguma técnica específica para
computar intervalo de confiança dessa
projeção ou é razoável usar com antes
específicos da distribuição de previsões
finais ficar ótica razoável usar com
antes mas como eu acabo enfim deixando a
sério muito próximas eles muito próximas
do valor original ou do valor que quer
dizer se conheceu ele é muito estreito
tá mas o que você pode poderia fazer
lembra que eu tô usando modelos então e
não tô usando métodos para predizer eu
tô usando modelos e não usando métodos
significa que eu tenho dirigir arroz
dentro deste modelo está poderia certa
forma combinar estas medidas dia coisa
que eu não fiz tá poderia olhar
pontualmente né mas poderia pensar como
distribuição olhar constante dele assim
mas a previsão é efetivamente a forma
que eu fiz ela ficaríamos com as
buscariam muito perto o valor original
tá então
e ela avaliar o quão com vale do seria
se esse negócio especificamente no lugar
e desconhecer ets mas você poderia fazer
uma modificação para acomodar isso de
uma forma um pouco melhor e preservar de
certa forma o todo ferramental teórico
que o fps que aquela guarda a gente
passa de estado de trás tá o meu número
é esse não era meu objetivo é verdade
era o meu objetivo mas não deu tempo tá
beleza eu tô aqui
se você fazer doutorado e trabalhava
funtime
em janeiro sim mas de novo eu tenho tem
pontos a se considerar tá é o primeiro
ponto é cara eu não sei nem um tempo nem
o horário nem um horário tá nem morar eu
tava tipo foram por 14 ano e hoje eu não
tinha nem um horário só que quando eu
sair eu tinha um horário aí com os
amigos fui fazer as coisas mas mas eu
não tivesse tá eu não tinha nenhum
horário e obá gastar o basicamente com
doutorado e madrugada é um pedaço da
madrugada muitas vezes é consultoria as
muitas vezes não tomava um tempo aí não
sei se a anna anna o daniel então aí mas
deixam mentir que muitas vezes era de
madrugada que a gente fazer umas coisas
eu tirei algumas madrugadas dentro da
mais e aí agora até ela é mas o café à
base de café cerveja algumas vezes pizza
e aí o daniel está sendo eu fiz e mais
um ponto que eu gosto de que eu quero
deixar claro é eu tinha uma rede de
suporte que me ajudava bastante tá então
enfim desde os meus amigos e chefes no
trabalho a dentro de casa e agora eu
tenho um filho eu vejo com difícil é uma
vez que você tem filho né você tem que
ir na coisa muda bastante de figura é
mas foi uma base muito red bull cara se
respondendo nos red bull eu devolvi uma
gastrite aí mas para sim eu botei um
lema lá porque eu vi uma vez não sei se
foi o quê
o skrillex sei lá se foi algum algum
provavelmente não sei se saulo catharino
da tá aí mas ele sabe quem ela é um cara
que fala é a sleep when i'm dead esse
tipo nesse não sei porque eu eu eu botei
isso entendeu então eu não acho que a
mente não dormir então em vários e
vários e vários e vários vídeos meus dos
meus amigos não sacaneia deu dormindo
tipo na mesa dentro da pizzaria eu
dormindo com a cabeça na assim todo
mundo comeu dormindo com a cabeça no a
mesa eu dormindo em pé em festa eu
dormir em qualquer lugar para mim era
preciso dormir entendeu
é porque tava sempre cansado e vai
sempre cansado sempre sempre devendo
alguma coisa para alguém tá também você
falei muito ficava administrando
incêndios beleza obrigado mais uma vez
né e aí a gente agora vai dar um tempo
na uns cinco minutinhos aí que eu o
perfume não fazer e o rafael da não
tiver vai entrar aí obrigado demais cara
muito legal né depois que vai
disponibilizar né o slide para mandar
para mim posso mandar para cima da mesa
aí quem quiser depois só entre em
contato comigo próprio antena bem
acessível lá no linkedin né é amanda lá
que eu respondo beleza beleza então quem
ficou com alguma dúvida e só procurar
ele lá no linkedin né e brigado pela
ajuda igual se quiser assistir aí ficava
super convidado bem legal beleza galera
e o rafael dal monte
o show de bola galera obrigado aí para
vocês terem participado obrigado pela
presença acho que tem uma esposa muito
mais gente do que eu imaginava que
entrar mas vários é é amigo é tudo nessa
vida né é é a mais adiciona o tiago lá
na linkedin tá lá descrição dele lá no
youtube né tem que a gente vai lá no
youtube só pegar descrição lá do vídeo
adicionar ele lá no linkedin beleza
galera obrigado obrigado de novo por ter
me convidado aí desculpa por ter
demorado tanto para fazer o show de bola
e se quiser voltar também para falar um
pouco mais de séries temporais aí a
gente marca com certeza que me chamou já
falei que eu quero falar sobre assuntos
finalizadores né então deixava para
finalizar eu gostei do da gente podia
fazer uma live aí deixa o saldo ainda tá
aí eu podia fazer uma live de dar
o funk olha aí ó que legal pode você
pode pegar aquela aquela aquela
biblioteca que se faz é como é que fala
conexão com googletrans né aí pegar as
funkeiras né maneiro aí assuntos membros
menos técnicos nas mais divertidas ou
técnicos mais mais divertidos que pesado
gostaria obrigado galera valeu boa noite
aí valeu
e valeu cara
e aí
bom então te dá um intervalo aqui
pessoal daqui a pouco a gente volta tá
uns 5 minutinhos a gente está de volta
aí tiago a gente continuar nessa mesma
nesse mesmo mim que eu uso de doido
e a gente continuar nesse mesmo link que
eu muda para outro smiley mesmo like ah
tá ah tá