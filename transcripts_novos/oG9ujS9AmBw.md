# Aula 11 - Automl Classificação - Prof. Flávio Clésio

- **URL:** https://www.youtube.com/watch?v=oG9ujS9AmBw
- **ID:** oG9ujS9AmBw

## Transcrição

o destaque dado tudo bem aqui é o Flávio
de novo então a gente vai dar
continuidade que não as a lista de Mach
Lane no próprio h2ovos a e hoje a gente
vai falar um tema polêmico né que vai
ser o tema do auto ml Ah mas eu tinha
mais nada queria pedir para vocês vocês
não são as plantas do canal se inscreva
no canal de 7 dados Tá bastante conteúdo
de qualidade desde aí de estatística
avançada visualização de dados parte
piso inteligência por aí vai então muito
bacana muito conteúdo de qualidade a e
também a outra informação que a passar
para vocês é que a todas as todos os
códigos dessa série de vídeos aqui no
slides por aí vai estão dentro do
repositório estatidados no kit Rubi
então a gente hub.com tá é só entrar lá
e pesquisar estatidados traço h2omem e e
todos os pode vão estar disponíveis
então a para quem é usuário do
interruptor dá um clone do repositório
ou dá um forte né só a e é isso é bem
bem
e vocês não são usuários para quem não é
usuário né do do kit Rubi só clicar
nesse botãozinho Verde aqui cone or
download e clica nessa opção aqui
download Zip quem vai a fazendo download
não somente dessa dessa implementação
que a gente vai falar aqui hoje mas
também de todos o código e de todas as
aulas também tá bom então a gente vai
para o tema polêmico hoje a chamado alto
ml de colocar primeiro não aqui a Então
na verdade só para explicar um pouco
mais né eu vou explicar só mais alto
nível do que é o alto ml depois a gente
a parte de implementação que eu a ideia
Nossa aqui do da nossa lista é mais
partir para a parte prática tá mais alta
ml ele vem aí para para preencher uma
lacuna digamos assim na parte
metodológica na forma na qual a gente a
gente faz as estratégias de Treinamento
tá então você no passado nessa a gente
pega aí quando começou esse os grandes
avanços aí na parte de Mach Lane né a
gente pega 2013/2014
Essa é a parte de Treinamento não eram
era uma parte muito empírica era muito
do conhecimento de domínio e da forma
com na qual alguns parâmetros de alguns
modelos eles religião religião ou
convergiam a durante um treinamento de
acordo com a sua Distribuição e por aí
vai mas é uma coisa que remite um pouco
mais a alquimia no que a ciência
propriamente dita né e o h2zone veio é o
na verdade volta ml desculpa ele vem
muito mais é para simplificar essa parte
de Treinamento no qual é pessoas que não
são especialistas em Mach Lane elas
consigam a pensa assim a partir do
princípio que os fios os dados vão estar
pré-processados jogar esses dados dentro
de um conjunto de algoritmos acidente de
conjunto de estratégias de convergências
desse desse desses algoritmos a pra
conseguir o melhor resultado dentro de
centenas de milhares de
a cair vídeo possibilidade nova
probabilidade as possibilidades a de
parâmetros as famílias de modelos que ou
de combinações de famílias de modelos e
parâmetros aqui o alto ml pode gerar
também tá certo a para quem quiser saber
mais essa aqui é a documentação do Alto
da implementação do alto ml do próprio
h2ovos e eu escrevi um artigo ou esses
dias sobre aspectos práticos teóricos
algumas vantagens e limitações do
próprio alto ml e para quem quiser saber
mais sobre alta ml aqui é uma eu coloco
da perspectiva três perspectivas né a
qual que é a graça do alto ml que que
ele ajuda o que que ele é de Fato né E
aí eu falo aqui da Perspectiva da parte
de a de parametrização de modelos partes
de metalom enedim meta aprendizado e
também da parte de a busca de
arquiteturas de redes neurais daqui
chama de neuroarchitecture sorte a todos
eles estão nessa
e aqui todas as referências de materiais
também então para quem quiser ter um
pouco mais de curiosidade nos aspectos a
teórico nem um pouco e também práticos
não é do alto ml todos estão nesse posto
aqui que eu coloquei no próprio Beira
hacker Tá bom mas a gente não vai falar
do aspecto teórico a partir para a
implementação do alto ml dentro do
próprio h2oh usando é certo então bora
porque estúdio então eu vou entrar aqui
na pastinha do estatidados é seis e a
lição aqui no meio dessa alta ml eu vou
abrir a parte de classificação também
como a gente fiquei nos últimos vídeos
anteriores lá então essa parte de carga
de dados e conexão dentro do poster é eu
vou dar esse todo esse bloco de código
de uma vez só porque toda a parte de a
de carga de dados Fitness gênero e de
exploração a dos dados foi feito nas
aulas anteriores então aqui hoje eu vou
só a fazer vou passar para frente essa
e essa parte até para que a gente possa
explorar tem um pouco mais de tempo para
explorar e explorar o próprio alto ml
Vou colocar aqui a nossa mente a a
panela de fogo então vou rodar toda a
parte de carne de dados ele vai conectar
no cluster do h2oh
e a vai gerar aqui o ponto Rex e eu vou
colocar aqui dentro queixam para deixa
eu pegar aqui o lehman Brothers outro
resto Então se rodar um samurai meu
ponto Rex aqui vai retornar para mim
todos os variados tá eu quero passar
como categóricos aqui não somente essa
variável de fogo né que vai ser a
variável a aqui de pagamento ou não mas
eu quero colocar também como categórica
essas variáveis essa variável education
essa variável mert também tá que é
relativas lá a grau de escolaridade e
esse a pessoa está casada não tô deixou
só substituir aqui tô passando as fato
para que é uma função Nativa do próprio
R que o h2oh frame ele ele também
consegue entender isso você não sabe o
que que é o h2off ainda recomendo
fortemente Vocês vão na segunda a
primeira aula que eu falo sobre a
arquitetura h2oe o princípio por trás a
dessa implementação então eu já fiz
um pouco aqui se eu vou dar uma segunda
olhada nos dados só para ter certeza
então aqui de volta como 01 tá e aqui a
partir do queixo emerge as variáveis já
estão a já é convertidas aqui para
Factor também o outro sobre aqui embaixo
e eu vou usar o nosso Sprint frame tá
noventa porcento a parte de Treinamento
10% a parte teste no qual a a nossa
parte de Treinamento vai estar no fundo
número um e o nosso a nossa parte teste
vai tá no fundo número 2 do nosso objeto
split que nós já acabamos de atribuir
aqui anteriormente Tom vou fazer só esse
split normalmente até os já tenho tanta
plástica na mente teste se eu quiser
conferir Summer alemã bordas name of
Brothers full track e bairro daqui
Matriz todas as informações da base de
dados aqui de foi por várias
as estatísticas descritivas na como
mínimo máximo mediana e por aí vai a a
variável dependente que a gente vai
escolher vai ser essa de fornece o
cliente entrou na situação de calote ou
não eu vou tirar que a Barão de gênero
dá para a gente ir nesse caso aqui
importa e eu vou colocar as variáveis
Independentes aqui que são todas as
outras variáveis que a gente tem na
nossa base do nosso lehman brothers aqui
certo e agora a gente vai passar por
nosso a alto ml propriamente dito tá
então a gente primeira coisa então
primeiro para gente conseguir trabalhar
com o alto ml a gente tem que chamar o
esse esse método da Luisa. Alto ml ele
já faz a a parte da atribuição do
treinamento do nosso modelo no qual a
gente vai passar né o x vai ser a nossa
as nossas variáveis a independência o y
vai ser a nossa variável dependente o
treme-treme vai ser a nossa base de
treinamento que a gente acabou de fazer
a a divisão em cima usando o nosso o
nosso espírito frame 1
um frame quem está usando aqui a gente
vai usar base de teste aqui só para para
fins para fins de conveniência mas a
gente poderia usar que apresenta uma
base roudaut né uma base totalmente fora
do conjunto de Treinamento desde que
essa base ela ela não seja né uma uma
base a não pode ser um dele até e dou
não pode são csv tem que ser ela tem que
ser convertida por para o h2oh frame
senão não funciona tá E aqui para baixo
a gente tem algumas informações já do
nosso próprio Premiere Então a primeira
coisa que a gente pode colocar aqui é o
número de modelo mapa de modelos o
número máximo de modelos que a gente
pode treinar nesse caso que eu vou
colocar aqui o alto ml Gere para mim 25
modelos diferentes Tá certo
o número de fogo eu vou colocar como
cinco aqui mas essa gente quiser usar a
parte de cross validation do próprio
alto miado alto ml para fazer essa parte
da avaliação do modelo durante o
treinamento é só a gente colocar o
número de fontes aqui colocar de forma
explícita nesse caso tô usando cinco
Fontes só do do prazo e deixa mais aqui
fica a critério de que no qual vocês que
os Aqui também tá a shopmetric tá
comente havia alguns vídeos anteriores
né Essa aqui é a vai ser a métrica aqui
vai ser usada como critério de parada tá
mas alguns Alguns algoritmos né algumas
implementações a de Mach Lane elas elas
usam a e aqui no propagado idosos usam a
função de pena né nesse caso aqui no no
h2oh em cima de logo nós que é um número
que indica a por exemplo qual que foi a
perda em relação àquela aquela interação
do treinamento né a isso é bastante
comum mais comum
I had to learn aqui que envolvem uma
função de pergunte aí utiliza a isso uma
uma frequência maior mais a
implementação h2oh ao invés da gente
usar uma função de perda a gente pode
usar por exemplo uma métrica de
avaliação de modelo para fazer as vezes
da função de perda então ao invés de ser
uma uma função de vai ter um número a e
para gente na grande maioria das vezes
não são grandes tinta a gente pode usar
por exemplo uma métrica nesse caso que
eu vou usar só a área abaixo da curva né
o Aos aos e mais se fosse um problema de
regressão por exemplo poderia usar o RMS
Eu poderia usar o ms e eu poderia usar o
RMS l e também para problemas de
regressão e nos foram assim
classificação poderia usar por exemplo a
poderia usar rir se poderia usar o
próprio ao cê tá ou eu poderia deixar o
alto né no caso e aí o de acordo com a
o jogador Zoe dias a terminar para mim
qual que seria a metre a melhor métrica
para fazer essa essa minimização tá
então a gente tem que eu vou colocar
aqui né vai ser o nome desse desse desse
projeto do alto ml que eu vou o nome
dele que eu vou que a gente vai
conseguir nem ficar lá no próprio fogo
que a gente vai ver posteriormente tá é
costume de alguns né que é a lista de
algoritmos que a gente vai conseguir que
a gente vai excluir tá aí como os dados
não estão normalizadas aqui eu decidi a
retirar essa guri que me depilando aqui
mas se eu quisesse por exemplo tirar o
algoritmo de gbm e eu só colocar, a
grossos aqui colocar gbm E aí a todos os
modelos da família toda a família de
modelos do Gradiente book Machine a vão
ficar fora do conjunto de treinamento e
uma coisa interessante aqui pessoal aqui
no alto ml ele não vai fazer somente é o
treino a com uma
o último ela de forma específica mas ele
vai estourar também é o poder dos
técnicos em bolsa então ele vai ele ele
não vai somente a gerar um modelo de de
renda forte por exemplo mas às vezes ele
pode virar um inspection bom com três
modelos dois modelos de gradient
boosting a com o modelo de higiene por
exemplo uma outra combinação está
crescendo ou que vai ter como base ler
por exemplo cinco modelos Direction
Garden tribos em e o modelo de 5 nível 1
g BM também tá então o propagador os
olhos da isso pra gente tá então vou ler
por considerar o gbm também eu tirar só
de plano A métrica e esse é um monte de
informação do aqui do da sedimentação do
alto ml esses York métrica que é a a
métrica que a gente vai usar para fazer
o ranking de cada um dos modelos Porque
no final a gente vai nesse caso aqui a
gente vai treinar no máximo 20
é só que para a gente fazer um aqui qual
o modelo que vai ser o melhor a gente
tem que terminar o critério para isso e
nesse no nosso caso aqui é a a nossa
métrica do AOC aqui tá certo que a gente
vai estabelecendo em cima como sua
primeira língua de verbosidade né então
vou colocar que todos os fornos sejam
apareceram aqui no console até pra gente
conseguir ver a como que está sendo
feita com urgência do palco ml E se a
gente quiser ver todas as informações a
todos os atributos desse método aqui só
de colocar o sinal de. De interrogação
h2oh a ponto alto ml a gente roda esse
camarada aqui e a todas as informações
vão estar aqui dentro do próprio rapper
a do próprio rstudio toque e a gente
pode ver que tem várias outras a a
vários outros atributos por exemplo esse
ali boyfriend Little Wood Frame
não tem como um h2oh frame por exemplo
que poderia ser uma base de uma base de
rodat que a gente estabeleceria Quais
quais são os melhores modelos não pela
base de teste não pela base de
treinamento mas sim por base totalmente
isolada do conjunto de Treinamento E aí
sim se o modelo tiver a uma boa
performance usando essa essa base a aqui
tá nesse Líder Warframe aqui a o modelo
vai ficar ranqueado a uma posição maior
também a pra modelos de classificação né
que a gente tem uma outra variável
naquele chama aqui de Belas classes
Então imagina que a gente está
trabalhando com alguns modelos por
exemplo de fraude né ah que é 99,999%
das transações não são fraude e apenas
uma fração dessas transações são fraudes
então tem uns balança mente dados o h2oh
ele internamente consegue fazer esse
balanceamento a gente colocar sua
balança e classes come true
em algumas outras informações que é o
Max wines at Nec é o número máximo de
segundos no qual o alto ml pode fazer o
treinamento então aí Aqui tem uma uma
dica mas vocês foram trabalhar com alta
ml o que que eu gosto de fazer muito
mais não usar o número de modelos a mas
sim usar um período de tempo a Parque
outro ml Gere inúmeros modelos né então
a E aí nos casos de uso do alto ML né
que estão mais descritos no artigo que o
que eu mostrei pra vocês que vão tá aqui
na descrição do vídeo ah o ideal do alto
ml usar ele para geração de bens Lines
lá então a gente vai gerar um modelo
inicial no qual a gente vai conseguir
interagir no qual a gente deixa eu a
máquina treinando sozinha a bem que
vazio listas de Treinamento que próprio
h2oleo alto ml implementa E aí sei lá a
gente coloca um período de tempo para
acertar esse algoritmo por exemplo de 24
horas então eu te deixa a máquina
criando um
E durante 24 horas E aí na de acordo com
as estratégias de convergência Qual
lista aí com e com adaptabilidade dos
dados dentro do modelo a parte depois
dessas 24 horas aí vai ter alguns
modelos lá que a gente pode usar esses
modelos com um ponto de partida para uma
otimização E aí se entrariam uma um ser
humano ali que vai entender Qual foi a
estratégia de convergência que foi usada
para gerar Aquele modelo e isso é fácil
porque o alto ml já só treinar modelos e
só dá e só gera as implementações de
algoritmos que já estão dentro dele
então não tem nenhuma surpresa esse algo
totalmente Black Box na disse algo Black
Box a e ainda assim a gente consegue
dentro do espelho de tempo explorar
possibilidades que se a gente fosse
fazer manualmente demandaria muito
alquimia e a gente não poder chegar no
resultado a tão satisfatório então aqui
a gente tem uma abordagem que a gente
estabelece um período de tempo no qual a
gente vai fazer processamentos de
e usando alto ml geração de modelos
dentro do espelho de tempo a que a gente
tá vendo aqui e aqui são as outras Stop
metros né então é como falei pra vocês a
gente pode usar esse aí s r s r s l e
por aí vai AOC a Mente Consciente também
e a o erro médio por classe tá aqui
número de stockhausen também a discutir
alguns nessa Então a gente está
excluindo os algoritmos The Deep Lane e
é isso que a gente vai usar aqui eu vou
querer os checkpoints Então vamos
colocar o alto ml aqui para ele começar
a morrer Os dados aqui então eu vou
rodar esse camarada aqui ó chegou a cair
para vocês a e agora o pano foi definido
isso deixei Virada do conjunto de
treinamento de novo
Oi tá fazendo toda parte treinamento de
teste agora eu vou usar o meu alto ml
tampa Y venceu y e o x minúsculo o
variável errada não tem como realizar o
conjunto de Treinamento agora eu começou
para valer a gente vai no show aquele já
tá dando ordem para gente aqui que está
habilitado A próxima Deixa então
e a já está sendo usado a próxima deixa
para fazer a validação interna de cada
um dos modelos então a gente vem aqui no
flor qualquer endereço do flor na
máquina de vocês se você estiver usando
você da Oni local Rosso 2 pontos 5 4 3 2
1 e vai e apareceu aqui no flores clica
aqui no admin protestados no nosso
poster tá totalmente operacional aqui e
se a gente quiser ver os jovens gente
clica aqui nos jogos e ligar pra tá
aparecendo cada um dos modelos que o
alto ml já tá botando para morrer aqui
então ele tá aqui o nosso estatidados
alta ml e aqui a gente tem um primeiro
modelo né nesse caso aqui o nosso outro
lugar dentro e buscar o primeiro modelo
e tá gerando toda a a brincadeira aqui
pra gente e está girando todos os
pontinhos aqui que tá sendo a todas as
árvores né que tão sendo que estão sendo
usados partitura em não me interessa
agora o treinamento de um modelo
específico eu quero ver o que o alto ml
tá fazendo aqui então vou clicar nesse
estatidados alto ml que foi
o que a gente estabeleci lá no próprio
r-studio tão pequeno esse cara aqui e
ele tá dando aqui o meu time de zero de
um minuto e 17 segundos e o tempo aqui
restante né do treinamento né do alto ml
tá dando aqui cinco minutos está
aumentando o pagode tá diminuindo tá
aumentando Tá variando mas a quem já
consegue ver volução dele tá em 24 a por
cento aqui devolução está gerando os
modelos se aplicar que Ele ouviu ele já
mostra que os modelos que ele já
conseguiu gerar Então já gerou um cara
que o gradiente Boost Machine já gerou
um antes do lugar dentro boosting e
girou um distribuidor Reforce que já
gerou um segundo a esse lado e bolsa e
assim sucessivamente Então se isso a
gente quiser ver a esses modelos né É
todas as informações estão aqui nesse
que a gente aqui de ser líder bordo né
que são o quadro um quadro Líder aqui
que vai tá todos os os modelos estão
sendo treinados
quem quiser havia evolução desses
treinamentos né a dos elementos modelo
somente clicar aqui nesse monitor Live e
ele já vai aparecer todos os modelos que
já foram criados aqui para a gente aqui
já inclusive todos eles ordenados pelo
próprio alce no qual o melhor modelo
está ranqueado em primeiro então aqui a
gente já tem o nosso modelo campeão aqui
a no começo que o nosso Gradiente Dulce
Machine sente quiser saber os parâmetros
que esse modelo foi utilizado Easy só
clicar em cima do modelo ele já traz
todas as informações aqui em modo para
Mirins Então fala Olha só o gbm2 alta ml
eu tenho cinco fontes de cross
validation as variáveis ignorados foram
aí de aí gênero tenho 36 árvores a 7
graus de profundidade na minha árvore e
aqui o meu sidman dormem com a minha
Distribuição e as informações aqui de
central rebate a cola Super radical
hoje a gente consegue ter também as
métricas modelo então aqui na parte
treinamento ele teve 82. 54 por cento e
na parte de validação de teve 77, 35
também a então EA isso a gente consegue
ver a de maneira interativa aqui no
próprio flor dá certo galera então ele
tá morrendo aqui para gente Está no
próprio Liverpool de 46 por cento a por
enquanto o nosso gradient boosting The
Machine 2 ele tá sendo nosso campeão a
gente quiser por exemplo explorar alguns
outros modelos Até agora ele não gerou
nenhum A i-tec ensemble tá mais
ligeiramente gera que os agentes quiser
entrar nesse no quinto lugar aqui do
Excel internet e Lucy aqui a gente pode
ver todas as informações more para
Mirins 5 fold Cross validation a 31
árvores e número de profundi a
profundidade das águas dos cinco níveis
e isso a gente quiser vir aqui o logo
loss a
Oi tá aqui no lá descendente ainda
talvez precise a gente mais House sair
de de tolerância do stop mestre tá para
evoluir mas ah tá OK Até então a gente
tá vendo só para fins educacionais aí
que a gente também tem uns lotes tanto
para a parte de Treinamento quanto a
parte de validação a mais suave se eu
tiver e aqui também tem o plot da parte
de decroly deixam também então as
informações que já haviam anteriormente
nos outros algoritmos do flor como
importância das variáveis a matriz de
confusão tanto para a parte de
Treinamento válida sangue para os olhos
deixan e a tabela dele se por aí vai
então isso a gente tem não somente para
o alto ml mas a gente tem isso por ter
fou de todos os algoritmos quem estiver
usando dentro da implemento que o alto
ml for gerar para a gente tá certo ah tá
fazendo aqui Já gerou 16 modelos então e
aqui pessoal é a ideia é muito simples é
assim o som sentido de dados né então ao
invés de 80
Olá a todas as famílias de modelos
tentar manualmente e fazer um por um
para cada um dos parâmetros vou usar um
grito sorte infinito dentro de uma
família de algoritmos específica a gente
pode só usar o alto ml deixa ele lá
molhando a carne lá durante durante que
24 Horas 5:00 10 horas e por aí vai a e
o alto ml já deixa o modelo base lá e
ali que a gente pode a tentar bater esse
modelo com algumas outras implementações
também tá certo então aqui tá em 63 por
cento tá demorando um pouquinho porque
eu coloquei a muitos modelos está
demorando de convergente tá com muito é
construindo a gente busca que apesar de
ser um modelo rápido mas a gente tá com
o grau de profundidade em
suficientemente razoável para esse
conjunto de dados que a gente tem
o que mais precisa falar para vocês que
a Então já falei e aí aqui já volto e
sua Opa a gente tem um novo modelo aqui
então nosso gbm um aquele já caiu para
terceiro lugar esse G BM Grid. Um aqui o
nosso número um vamos ver o que que ele
tá trazendo aqui para gente manda para
mim ir no meio de fortes ocupando 30
árvores com um nível de profundidade
nova Então seja tá deixando o alto ml a
ele ele está identificando que essa
família de algoritmos do A gradient
boosting Machine
A tá trazendo melhor convergência então
ele aqui já tá trazendo Ele é aquele
diminui uma árvore aquelas alta e pronto
a senhora tem que ter uma atendente uma
árvore se não me engano é o número de
árvores só que invés de número da
profundidade de árvores e de sete agora
ele tá com 19 e aí o que torna a nossa a
nossa árvore um pouco mais específica
também né então isso naturalmente vai
subir a a nossa a nossa performance
dentro do nosso do nosso algoritmo na
Vamos ver quanto tempo falta que eu
finalmente terminou aqui Demorou 6
minutos e 59 segundos eu tive que
enrolar vocês por quase sete minutos e
durante esse tempo aqui o gradiente o
desculpa o alto ml gerou
a todos esses esses algoritmos aqui e um
meu telefone que eu esqueci de falar que
aqui eu trabalho na minha máquina a de
forma Estendeu longe né mas imagino que
a gente estaria estivesse no prosternar
distribuído no qual o time de
infraestrutura e na empresa que você
trabalha organização que vocês trabalham
a conseguiu colocar um cluster é uma
máquina que vai ser um aquilo que vai
ser o o digamos assim Onde fica o alto
ml vai ao também era um disco colocar
dois ovos não tá instalado e dentro
disso né ah não somente os meus
experimentos de alta ml pode ficar aqui
mas os outros experimentos de outros
cientistas de dados também então eu
tenho modelos dentro do meu treinamento
do meu alto ml Então esse aí vai ter o
meu somente um a minha chave aqui né do
do meu tratamento alto ml a poderia por
exemplo céu assim 10 a321neo número de
sentido de dados fazendo o mesmo
treinamento de alta ml com todos os
todos os líder
o que a já definidos na então a gente já
tem um ranking dos melhores modelos aqui
já viram os saques em gol no apagar das
luzes aqui então vê se está acontecendo
aqui com a força do melhor modelo modo
para Mirins então olho uso quantos meses
Modas aqueles um dois três quatro cinco
25 modelos que eles usam aqui cão bens
Model há cinco anos foram de metallers
então ele deixou aqui o modelo muito
muito muito muito mais complexo no
corrente teve um alceno treinamento que
de noventa porcento ano a parte de
validação mesma coisa 77 e na parte de
no Cross validation ele teve 17878 por
cento também tá a então basicamente é
isso e todos os poros também né de
importância das variáveis também
eu vou está toda dentro aqui do nosso do
nosso próprio a flor ao que a gente pode
ver aqui até mesmo pela parte do Logo
logo aqui né ah ele tá numa descendente
ainda né Então teve nenhum Spike que
indicasse digamos assim que a que que a
parte do do treinamento
e começou a ter um overfeat de fato
então gente poderia explorar esse aqui
um pouco um pouco mais daí explorar um
pouco mais esse treinamento a e voltando
de novo aqui para o nosso a estudante já
viu bastante o frame né então vocês
quiser ver o próprio laender Birds a
Bordo A dentro do próprio alto ml então
lençol chamar o modelo alto ml@pegar o
atributo uma Líder por colocar nessa
variável LB e fazer o print dela
trazendo o ranking
o jado dos melhores modelos aqui que ele
vai trazer para nós os nossos técnicos
em bow de todos os modelos do alto ML né
dos outros os outros 25 modelos que
foram utilizados então aqui a gente vai
pegar o líder por exemplo né então a
ml@livre vai pegar somente o modelo
top-down melhor e da mesma forma que a
gente uso fez com os outros modelos né
se a gente quiser fazer as previsões
usando esse modelo que foi gerado pelo
alto ml o que a gente precisa fazer
somente pegar alta ml@líder e passar ele
como objetivo e como New deira a gente
passar a nossa base de teste aqui também
para nossa função aqui do produto e
armazenar as pressões dentro aqui do
prédio Então são variados E se eu quiser
ver por exemplo para o que ele retorna
aqui
e vai tá todas as fricções quem já fez
aqui para todos os nossos registros tá
então vai estar a apreensão tá então 01
aqui então não deixou no Le fou a caso
de calote caso de não calote e as
probabilidades também a para cada uma
das classes Lembrando que toda vez vocês
foram trabalhar com a probabilidade sem
classificação ideal que vocês usem a
própria calibração a pra fazer isso ou a
gasóleo tem ele tem bibliotecas a dentro
de todas as limitações de classificação
ele já implementa a parte de ir passar
um frame de calibração também para ter
resultados um pouco mais robustos tá aí
aqui a gente consegue também usando
usando o nosso método do olhos e a
utilizando o nosso o nosso o nosso Líder
módulo né digamos assim
hoje a gente consegue checar o nosso o
nosso sol ser tanto na parte de
Treinamento pelo menos o valor que a
gente teve lá nosso flor né do de 90,6
por cento quanto o nosso a nossa área
abaixo da curva a da nossa base de
validação que nos fazem que a nossa base
de teste só porque eu vi esse de 77,8
mil e três por cento mas suave com que a
gente consegue Salvar esse modelo que
ele gerou no alto ML né como a gente
consegue pegar esse modelo Líder aqui e
salvar ele o que a gente precisa fazer
eu vou só criar um caminho né do meu
diretório então onde que eu vou salvar
esse modelo deixou até Abrir normalmente
aqui o meu em forma se vê aqui não faz é
dentro da minha pasta aqui está te dados
Essa é esse alto ml tem esses dois
escrito está todo de regressão como de
classificação o caminho que eu vou
passar um
Essa é a continuação de todos os
diretórios raízes aqui
é a do meu e do meu projeto que vai para
dentro eu trabalhava chamado arquivar
terra né que vai ser o caminho da minha
variar a tivesse só o caminho que eu vou
só esses modelos e eu uso o método
chamado seja imóvel no qual eu vou
passar tanto o modelo a líder né como um
objeto que eu vou salvar o caminho e o
force que ela se ele tiver alguma outro
modelo já salvo ele vai sobre a escrever
esse modelo talvez devo desse camarada
aqui e ele já aparece dentro aqui do meu
inverno do meu a h2oh
e vai aparecer o modelo que a gente
acabou de treinar aqui no caso aqui o
melhor modelo né que é o stephanes é bom
tá se a gente quiser fazer a carga desse
modelo novamente a única coisa que a
gente precisa fazer é só pegar esse
caminho para onde que esse modelo Tá
salvo e chamar o nosso método load Model
a no qual gente vai salvar esse modelo
dentro desse ser esse horário é chamado
sejas moda
bom E como que eu faço para saber se
esse modelo ele é um modelo ser
realizado Não Posso rodar o Summer
o que a função Nativa do próprio R em
cima desse modo ele vai trazer aqui para
gente a todas as informações do modelo
então o pão deixa boca para cima eu falo
assim Olha isso aqui não está crescendo
e esse é o nome do modelo e sol sendo
modelo não tem prometido em relação do
treinamento aqui tá falando aqui ó a
relatório dos dados de Treinamento Esse
é o aqui a matriz de confusão e algumas
outras métricas como o FMI sphor
apreciam e cole por aí vai a isso a
gente quiser fazer salvar né ah não
salvar Desculpa se ele quiser fazer
petição em relação a esse modelo que a
gente acabou de ser realizar a gente só
usar o nosso o nosso método preditivo já
haviam anteriormente não pode deixar
passar o nosso cervere moda atual modelo
que a gente acabou de carregar e a nossa
base de teste apenas por conveniência
vou gerar Pioneiro frame só para gente
porque a gente conseguiu visualizar aqui
de uma maneira a tabular e eu vou
colocar dentro desse modo por dentro
e esse camarada aqui ele vai gerar esse
modo eu prender aqui na minha meu bobão
Vargas É só ficar nessa nessa nessa
tabelinha aqui em cima ele já vai
aparecer todas as pressões para a gente
então aparecer quem não entrei em
situação de pagode que entrou em
situação de plástico e também as
probabilidades se a gente quiser também
usar as probabilidades e não o valor a
01 a hipertensão a gente quiser Salvar
esse modelo esse melhor modelo que o até
medir ou a gente vai usar o mesmo mesmo
princípio do Vai Girar os objetos tanto
mojo.com bojo né porque esses a modelo
sejam a sejam utilizados aí em em
plataformas que tem código tanto escala
quanto a já tão no qual Vou passar o meu
modelo é o líder eu vou gerar o caminho
né que vai ser o caminho
é esse n anteriormente e ele vai gerar o
ponto já há como o tio vamos ver se ele
vai vir aqui para gente
a preguiça vai ser um problema
eu e ele acabou de gerar para gente
esses dois objetos Ok ser realizados
então aqui a gente já tá pronto trapa
pegar esses esses esses modelos passar
para os ossos pelos desenvolvedores aí
já vi escala e esses modelos não tá
pronto sair para ser embutidos dentro de
plataformas né E aí pode ser tanto de
uma plataforma política pode ser a
dentro de apis tá aí então eu tive o
pessoal alta ele era nada de não é
nenhum Bicho de Sete Cabeças era muito
simples Eu recomendo fortemente que
vocês Leiam esse artigo que eu escrevi
não não deita hackers e ele tá bem
completo que ele dá tantas explicações
em termos teóricos e algumas limitações
como em relação a exploração do espaço
de busca e por aí vai tudo bem Então é
isso A então gostaria de pedir para
vocês mais uma vez você não vocês não
são inscritos se vocês vão ser inscrito
no canal se inscreva no canal tá a e
deixa o joinha no vídeo tá muito
importante para aumentar o alcance desse
material para
ah ah ah dentro do algoritmo YouTube Tá
certo então esse pessoal Muito obrigado
e até mais