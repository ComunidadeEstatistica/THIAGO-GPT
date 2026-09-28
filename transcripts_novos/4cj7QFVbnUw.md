# 7º Meet Up Data Science 2020 - Ciênica de dados e Estatística em Python -  Diogo Picco(Inferir e BB)

- **URL:** https://www.youtube.com/watch?v=4cj7QFVbnUw
- **ID:** 4cj7QFVbnUw

## Transcrição

tá trabalhando na Brasil prev como
cientista de dados Senior lá tô
assumindo a gestão aqui de de Analytics
do Banco do Brasil e então eu tô em
processo de mudança peguei deng tá uma
beleza tá uma confusão e eu tô
terminando o doutorado eu qualifico
agora semana até o final do mês eu tô
qualificando a Minha tese Então assim tá
uma correria eh ela me propôs fazer uma
palestra sobre Python eh eu não sei se
vocês sabem estatístico em geral quem
não é da área de computação a gente
gosta muito mais do r mas eu beixo
bastante bem no no no no Python também e
eu falei com ela mas como é que eu vou
fazer uma palestra sobre Python eh então
o que que eu pensei vamos aplicar um
caso de uso um uso de Eh vamos pegar um
exemplo como é que eu usaria isso como é
que eu fazia um modelo disso lendo um
pouco sobre o ccro eu vi que vocês têm a
parte digital da carteira digital né
Carteira do motorista digital vocês tê
algumas documentações digitalizadas
então vocês têm reconhecimentos de
imagem F Ah isso é um tema legal a gente
pode utilizar um algoritmo simples um
algoritmo Inicial que KNN né que é um
algoritmo bastante simples e bastante
falado que é muito utilizado para
reconhecimento de imagem e classificação
de objetos eu falei ah vou pegar um
estudo de caso sobre isso e vamos
inventar Ah eu peguei base de dados
estatística qu não pega base de dados a
gente começa a viajar né eu já trabalho
bom contar Uma Breve História Sobre a
minha
formação ela já contou né eu comecei na
ence eh por motivos de de de trabalho
para chegar na ence que é no centro do
Rio e chegar na uer era mais rápido eu
chegar na uerg aí no final do sexto
período eu troquei pela uerg me formei
pela uerg mas antes de ser estatística
eu fiz biomedicina tá gente então assim
eu sou biomédico também então eu gosto
muito de trazer exemplos na área médica
Isso aqui vai ser um exemplo basicamente
na área médica vocês vão ver esse
pizinha aqui vão entender um pouco
porque que eu uso exemplos dessa área
médica ou da área de de saúde em geral
biológica que seja eh pela minha
primeira formação aí eu passei no
concurso Brasil vim para trabalhar como
estatístico aqui desde 2011
ah depois fiz o mestrado na na UnB em
estatística não tem doutorado na NB
estatística então tive que procurar um
doutorado em outra área trabalhando em
banco né não não me surgiu muita outra
oportunidade se não fosse um dout
economia oual eu tava trabalhando e eu
tô
Minha tese
agora agora no final do ano Minha tese é
voltada pra previdência né E como se
fosse um robô advisor pra previdência
como faria isso né
como como
melhor entregar
retorno de
aposentadoria para um
cliente para uma pessoa
como administrar melhor a minha bastante
dão ouvindo me falem tá tudo bem tá me
ouvindo bom eh Essa é a minha formação
eh eu sou coordenador do curso de de
pós-graduação de estatística da UDF eh
sou professor da do IESB de Inteligência
Artificial e de tecnologia disruptiva
ã dei aula também no Rio de Janeiro
bastante tempo tava dando aula na UnB
agora como complemento na minha do meu
doutorado né Eh ten a empresa de
consultoria que é que inferir
estatístico a gente também tem
treinamento e tudo mais a gente tem
treinamentos online hoje em dia tá tendo
treinamento
[Música]
online Diogo desculpa te interromper mas
o teu áudio tá falhando um bocadinho viu
em
Bras né
ag agora que a minha
salin é da
empresa pode ser só me dar um Talvez
caia que vou ter que trocar a rede aqui
estão me
ouvindo f
tá bem falhado o teu áudio viu Diogo
seu microfone tá desligado
Diogo como é que eu faço para
sair estão me ouvindo Tá melhorando
melhor agora agora tá melhor Ah então
Ótimo vou compartilhar aqui a tela de
novo
eu vou passar esse notebook para vocês
bom tá me ouvindo agora tá melhor agora
tá joia Ah então Ótimo então não precisa
sair bom eh eu vou apresentar para vocês
uma aplicação do algoritmo KNN Tá feito
em Python utilizando learning então a
principal biblioteca Python para análise
de dados para manipulação de dados é o
pandas o pandas o nump e o pit learning
são as três bibliotecas que a gente mais
usa o pandas a gente usa muito ele para
manipular base de dados quando a gente
vai manipular base de dados pequena se
tiver um Big Data o panda já não
consegue trabalhar com o panda você tem
que partir pro Spark quando você por
exemplo se eu tô falando em trabalhar no
as você vai trabalhar em uma em Big Data
efetivamente Big Data né porque tem
gente que fala que ah tem 2 milhões de
linas isso não é Big Data e como o
Thiago apresentou na apresentação
anterior o volume de dados para ser
considerado até muito maior do que 3 4
milhões de linhas por exemplo e é um
volume constante cada segundo você tem
novas informações então Eh trabalhando
em Big Data o pandas não seri um dos
melhores bibliotecas ou ferramentas
dentro do Python para você manipular a
base de dados e sim o
Spark teria que usar o pandas o Spark
para manipular a base de dados e não
mais o pandas como aqui é um exemplo eh
para vocês entenderem como é que a gente
pode usar ciência de dados uma aplicação
estatística para construção de um modelo
e eu tô usando o pandas então
inicialmente aqui no código e eu tô
importando a biblioteca pandas é o nome
da biblioteca então importa pandas éd e
tô dando um apelido para essa biblioteca
chamando de pd tá objeto clássico do
pandas é o Data Frame assim como no R tá
um objeto clássico no R é um dataframe
que é uma base de dados compostos por
linhas e colunas similar a uma planilha
Excel tá gente nós podemos carregar
diversos tipos de arquivos tabul com
pandas E para isso a gente faz uso de
métodos iniciados por read basta u ar o
método usado read underline alguma coisa
a gente consegue ler alguns ah algumas
bases no no panda se você tem o read
underline csv como é que eu tô usando
aqui ó pdre underline csv eu t falando o
seguinte olha Leia esse arquivo csv qual
arquivo pinguim pcsv ele tá indexado
pela coluna zero ou seja e no pandas eh
no pandas no Python começa pelo zero não
começa pelo um como no R né Então a
primeira coluna é o zero no Python ou a
primeira linha é o zero no no R já
começa com a primeira linha sendo um
aqui a gente tem que dizer que o indexo
de coluna é zero ou seja começa na
primeira coluna tem indexador e tô
guardando a variável DF por exemplo
tenho vários métodos no pandas com read
underline não tenho só csv eu tenho read
underline xlsx tenho read underline SAS
tem read Under Line n outras extensões
tá gente são várias extensões que a
gente tem como o objeto ou o método read
dentro do pandas então tô utilizando
pandas só para ler a biblioteca que eu
chamei de
pcsv beleza Isso aqui é uma aplicação eu
sei que no início parece um pouquinho
chato que eu vou trazendo um código mas
é só para vocês entenderem um pouquinho
como é que a gente faz uma leitura de
uma base de dados bom existem inúmeros
parâmetros que a gente precisa
configurar na hora que a gente tá lendo
essa base de dados por exemplo o CP O
separador Opa Deixa eu voltar para cá o
separador
eh O separador
indica ou indicado no arquivo do CS CV
normalmente criado em Excel em português
é o ponto e vírgula Ou seja que eu
separa uma coluna da outra quando quando
eu Gero um csv do Excel que é em
português é o ponto e vírgula mas
mundialmente O separador quando eu gera
um csv que não seja um Excel em
português é somente vírgula então posso
dizer aqui olha o que que separa uma
coluna da outra se o meu ponto csv é
americano ou é europeu qualquer outro
país sem ser em português por incrível
que pareça eu não preciso dizer que O
separador é vírgula porque ele ele adota
isso como padrão é um default do Rich
csv O separador ser uma vírgula mas se
você tiver trabalhando com csv criado em
Excel em português você tem que botar
aqui vírgula CP igual abre aspas ponto e
vírgula você tem que dizer que o
separador desse csv que você gerou em
português né Ele é um ponto e vírgula e
não uma vírgula tá decimal decimal é uma
coisa muito importante tá aqui na hora
que a gente for ler o decimal em
português ele deve utilizar vírgula eh
quer dizer o decimal da gente é a
vírgula
eh 1000 é 1.00 vírgul 00 é o separador
de decimal o decimal em americano é o
ponto então é uma coisa que é bem
diferente que a gente tem que se atentar
a isso e normalmente algumas bibliotecas
que a gente vai utilizar elas são
Americanas ou São escritas em inglês na
verdade eles adota um padrão único Então
se atente ao decimal o reader funciona
igualzinho como se fosse o o Heat o head
na na no no R ele vai te trazer as
primeiras colunas As cinco primeiras
colunas do seu Data Frame eu tô usando
aqui ó eu li esse Data Frame guardei
nesse objeto DF e vou começar a
trabalhar ele quem é esse meu Data Frame
Eu trouxe um objeto read df. read ou
seja traga as cinco primeiras linhas
para mim vamos ver que informações eu
tenho nesse meu Data Frame tá legal
nesse meu Data Frame eu tenho a espécie
do pinguim eu tenho a ilha que ele vem
eu tenho o que a gente chama de P length
ou seja o comprimento do bico eu ten que
a gente chama de build Death Ou seja
a a espessura pod pode ser ou ou quão
profundo é né Qual a altura desse bico
do pinguim eu tenho flicker e o flipper
Len o comprimento da da das AAS eu tenho
a base eu tenho a massa dele o peso dele
e tenho o sexo do pinguim então nessa
base de D da gente a gente tem a espécie
tem de que Ilha Ele foi pego ou
capturado eh ou medido no caso né eu
tenho o comprimento do seu bico eu tenho
a o comprimento do bico eu tenho a
espessura não é o tamanho eh
profundidade do bico digamos assim eu
tenho o comprimento da das asas eu tenho
a massa do pinguim e eu tenho o sexo
dele então tem todas essas informações
na nossa base de dados agora o que que a
gente faz quando a gente tem uma base de
dados para analisar em ciência de dados
gente sempre sempre que a gente vi uma
base de dados a gente procura fazer uma
análise descritiva da base de dados vê
quantos valores missem eu tenho se eu
tenho algum Aler Quais são as as
espécies que eu encontro na minha base
de dados quais são os tipos de ilhas que
eu encontro Qual o tamanho da minha base
de dados tudo isso eu tenho que fazer
inicialmente antes fazer qualquer coisa
qualquer modelo outra coisa se eu
quisesse ver os últimos cinco elementos
da minha base de dados DF eu usava a
função Tail tá PR cliquei aqui tem que
rodar então Tail ele me traz os últimos
cinco elementos da minha base de dados o
o He me traz os cinco primeiros tá então
fazer um count fiz um count Zinho aqui
nessa base de dados e vi lá ó da espécie
eu tô contando a espécie a vari ch
espécie Se eu quisesse contar Island
podia vaiar df. Island PV counts ele vai
contar quantas Ilhas tem separadamente
aqui eu só quero contar as espécies Olha
eu tenho três espécies a função a a
espécie é del eu tenho 146 observações
a espécie gento eu ten 119 observações a
espécie Shin Strap eu tenho 68
observações e eu tenho aqui uma
descrição da minha variável é uma
variável inteira é um contador da da da
variável espécie que é uma variável
caracter então tô contando então eu
contei Quantas espécies eu tenho cada um
deles e eu posso fazer isso para cada
uma das variáveis então é interessante
para cada uma delas eu vou mandar contar
eu conto Que tipo de variável eu posso
contar isso é uma outra coisa que a
gente tem que analisar adianta contar
uma variável contínua imagine assim aqui
eu tô vendo o comprimento do do do bico
que tá em milímetro
beleza e só tem uma casa decimal 37.8
Então pode ter até uma repetição mas
imagina que eu tenho mais de 50 casas
decimais aqui se você mandar contar ou
seja ele vai ter que procurar uma outra
informação 37.8 345 6 78 que é similar
na sua base de dados se base D pode ser
1 milhão de linhas então assim se você
tem uma variável contínua você não conta
ela só conta variáveis categóricas ou
discretas limitadas por exemplo eu tenho
uma variável lá 1 3 4 5 que é o número
de de pinguins observados naquela Ilha
eu consigo contar porque você é limitado
de um a c agora uma variável contínua Ou
seja que ela é infinita o comprimento
dela é infinito o que que são as
variáveis contínuas volume peso tempo
São variáveis contínuas essas variáveis
você não faz um processo de Contagem e
sim você faz um um processo de
mensuração de medida uma coisa é um
processo de Contagem e outra coisa é o
processo de medida são medidas são
coisas completamente diferente então
aqui eu vou fazer quando eu quero fazer
um velho count eu vou contar quem
espécies Ilhas e sexo as outras
variáveis eu tô vendo que são todas
numéricas e dificilmente devem ter
repetições então não faa uma contagem
que que eu consigo fazer com variáveis
numéricas contínuas uma média uma
variância um desvio padrão o coeficiente
de correlação a gente pode fazer um eh
um coeficiente de dispersão que no caso
seria o div padrão né ou a a própria
variancia e etc você tem medidas de
dispersão ou medidas de tendência
Central para você calcular em cada uma
das suas variáveis
contínuas nas variáveis categóricas ou
Eh Ou discretas finitas você pode fazer
um processo de Contagem aqui eu escolhi
uma das variáveis para vocês verem como
é que que a gente faz uma contagem aqui
é só para você caracterizar sua base de
dados tá eu botei a foto aqui do ping
vocês entenderem que que seria o
comprimento que seria o o o o DIP e aqui
são as espécies de pinguin você olhando
assim gente de longe imagina um processo
Você tá no CPO você faz foto para para
identificar se o cara imagina o seguinte
tá tá num processo jurídico
eh baseado numa imagem e eles querem
comparar com a imagem tirada na carteira
de motorista eles quer saber se aquela
foto que tá num processo de um
assassinato de alguém é similar a foto
que tá n no banco de dados da serp Então
tem que fazer um depara para saber se
aquela pessoa é ela mesma eh é difícil
você comparar isso então a mesma coisa
aqui o quero saber o seguinte esse
pinguim eu vou tirar fotos de vários
pinguins com aquelas fotos qual pinguim
deve ser ou seja um processo de
identificação de imagem vocês vão
entender que toda esse é o nosso grande
problema agora o processo de
identificação de imagem a gente vai usar
um algoritmo bem simples vocês vão ver
no final Mas antes a gente tá estudando
a nossa base eu tenho que compreender o
que que eu tenho aqui primeiro bom
e nota que a primeira coluna sem título
foi criada como uma sequência direta ó
primeira coluna aqui sem título foi
criada como uma sequência direta
ah essa coluna é conhecida como índice
dos dados e pode ser acessada através do
DF index ou seja eu tenho um índice de
cada dado ou seja a linha zero é uma
pessoa nesse caso aqui é um é um pinguim
específico a linha um a linha 1 2 3 cada
uma das Linhas é um pinguim
específico tá e eu posso acessar cada um
deles na forma que eu quiser usando
simplesmente esse código DF index e eu
posso Opa ficar rodando todo l isso aqui
aí posso dentro de. index eu posso botar
a coluna que eu quiser pegar que eu
quiser identificar Imagine se eu tivesse
um Missing velho aqui ou o como O Thiago
falou na aula na na apresentação dele
anterior um outlier eu digitei errado 35
9.05 por exemplo o cara tem 355 MM 159
MM dentro dos pinguins Que você estão
fazendo aqui é absurdamente diferente
dos demais seria um outl provavelmente
foi gerada por um erro de digitação ou
um ou um erro de mensuração da máquina
que que acontece tá
bom Eh vamos entender um pouquinho que
seriam as variáveis no sentido
estatístico Já comecei a falar para
vocês eu tenho dois tipos de variáveis
no sentido estatístico as variáveis do
tipos quantitativas e do tipos
qualitativas as variáveis do tipo
quantitativa elas podem ser discretas ou
contínuas discretas são são são geradas
através de processo de contagens número
de filhos um filho dois filhos três
filhos se conta um processo de Contagem
ela pode ser finita ou não tá esse
processo de Contagem pode ser infinito
variáveis contínuas ela é gerada através
de um processo de medição Você mede o
comprimento das coisas você mede o
volume Você mede o peso Você mede o
tempo então Eh podem assumir qualquer
valor no intervalo numérico entre faixas
né e é infinito cada uma das faixas eh
São resultados de medidas exemplo altura
do indivíduo velocidade de um veículo
saldo de um cliente
idade a idade a gente
discretização contínua Que beleza sempre
esqueço FIC aper nesse troço aqui a
idade é uma variável contínua variáveis
qualitativas elas podem ser do tipo
nominais ou ordinais do tipo nominal há
uma ordenação entre as categorias eh não
há na verdade não há ordenação entre as
categorias exemplo sexo gênero cor dos
olhos não tem ordem já as variáveis
ordinais Você tem uma ordenação entre as
qualidades por exemplo numa corrida de
de de automóveis quem chega em primeiro
segundo terceiro e quarto tem uma
ordenação por chegar
nível de escolaridade nível superior
nível médio isso tudo tem um tem uma uma
ordenação nível de renda tem uma
ordenação faixa de idade você tem uma
ordem então assim as variáveis
qualitativas ela tem dois tipos os
nominais onde você não tem nenhum
critério de ordenação Ou seja você tem
menos informação depois você tem um
nível ordinal que você tem um pouquinho
mais de informação Você tem o critério
de ordem depois você vai pro critério
discreta que você tem mais informação
ainda e por fim o tipo contínua e teria
mais um tipo que seria o tipo razão que
te dá mais informação ainda possível
dentro as vari Dent tipos de variáveis
estatísticas aqui eu só trouxe quatro
tipos quia mais um bom eh as variáveis a
gente pode fazer um resumo dela porque
imagina a gente tá numa base de dados
com 3 4 milhões de pessoas no Brasil não
sei quantas pessoas TM carteira de
motorista mas supondo que nós somos nós
somos 210 milhões de habitantes Digamos
que tenha pessoas e carteira de
motorista em torno de 70 80 milhões de
de de de pessoas que tenham carteira de
motorista você não vai mensurar a idade
das pessoas que bateram no último
semestre por exemplo imagina que você tá
no Detran simplesmente olhando uma base
dados todas as pessoas porque podem ter
mais de 3 milhões de pessoas que bateram
você não valear um a um você então vai
ter que criar formas de analisar isso
aqui Isso aí que entra a estatística
descritiva são as variáveis de resumo eu
posso contar o número de acidente eu
posso fazer a média entre os acidentes
eu posso fazer uma taxa de de de
acidentes fatais então vocês vai entrar
a ideia de resumo de uma variável é como
que a gente vai analisar ela quantidade
de elementos em uma amostra existem 168
pinguins machos e 165 pinguins fêmeas
isso é um resumo de uma variável é um
processo de Contagem simplesmente conter
o número de machos e o número de
fêmeas e como é que eu faço isso Def
entre colchete sex porque se você olhar
sua variável Aqui tá escrito
sex ou teria outra forma teria como é
que eu fiz aqui
ó eu não fiz ó df. espécies poderia
falar df.
P vue counts outra forma de fazer é você
simplesmente fazer DF entes abre aspas
sexv counts ele vai contar também a
mesma coisa só que eu não vou contar
variáveis do tipo contínuo do tipo
contínuo a gente vai começar a fazer
achar o máximo achar a média achar o
mínimo seriam variáveis que a gente vai
ser um processo a gente vai calcular
estatísticas tá é o que a gente chama de
estatística então para achar o máximo de
uma variável se eu quero saber o máximo
do Body mass seria o peso dos Pinguins
eu botava lá minha base de dados DF
entre colchete De novo abre aspas b m
que é o nome da variável ponto max el
vai trazer um peso máximo observado dos
Pinguins 6 kg 6,300 pesadinho esse
pinguin he se eu quiser saber a média do
Peso dos Pinguins a média o que que é é
a soma de todos os pesos dividido pela
quantidade de pinguins Isso aqui é uma
média não ponada na verdade ela tá dando
pesos iguais para cada um dos pesos
observados
tá média por exemplo mi ou x Barra na
estatística tem muita diferença quando
eu falo uma letra grega e uma letra
Romana e não sei se é grega ou Romana
agora verdade mi é grego o x Barra é não
sei se é Latina não sei exatamente qual
é não é Romana é uma letra índica não
sei exatamente como é que é só sei que a
letra grega elas representam população
Ou seja quando eu falo mi eu tô falando
uma média da população que que é uma
média populacional é um número que não
vai mudar nós estamos aqui 250 alunos na
sala se calcular média média de idade de
vocês vai ser x se eu pegar de novo os
mesmos 250 nesse exato momento 5 minutos
depois se ninguém fez aniversário em 5
minutos que acho que não faz Ou a gente
calcula aniversário no dia a média
continua sendo a mesma x Barra
representa a média
amostral Então sempre que você vê x bar
S2 S são termos que remetem a amostra
Quando você vê mi Sigma Sigma quadr são
termos que remetem a população e qual a
diferença
amostra é uma variável aleatória ou seja
se eu pegar uma amostra eu vou calcular
a média e pegar uma amostra de novo você
não vai conseguir pegar a mesmo sof são
aleatórios você vai ter outra média
então x Barra ele é variável mi ele é
fixo tudo bem assim é uma separação
entre estatística e termos
populacionais bom se eu quiser calcular
o mínimo eu posso fazer um print de
geral aqui ó print Def o mínimo Def min
e Def Max el fal prou ó o mínimo
2,700g a média
4,27 e o máximo
6,300 beleza essa aqui seria a média dos
Meus pesos se eu quiser calcular um
ponto mediano é só você usar a função
médian mas a mediana Ele simplesmente
pega um ponto que separa sua
distribuição de pontos entre 50% para
baixo daquele valor e 50% para cima
daquele valor ou seja se eu eu tenho
três números ordenados 1 2 e 3 a minha
mente mediana vai ser dois por quê deixa
o um para baixo deixa o três para cima
agora se eu tenho quatro pontos 1 2 3 e
4 a minha mediana vai ser a média dos
pontos centrais ou seja do ponto 2is e
do ponto TR vai ser o 2,5 você não tá
observando o 2,5 mas o 2,5 separa um e o
dois para baixo com a mesma distância e
o três e o quatro para cima com a mesma
distância entre os pontos centrais Tudo
bem então sua mediana se for o número
ímpar ela simplesmente é o Ponto Central
no exemplo 1 3 5 7 9 vai ser o c se for
uma ição par sua mediana você vai juntar
os dois termos centrais e dividir por
dois fazer a média dos termos centrais
seria o quro que você não observa ou
seja sua mediana pode ser observada ou
não observada na sua amostra nesse caso
foi
4,50 div padrão e variancia divir padrão
e variancia te D uma ideia de dispersão
tá imagina o seguinte eu quero saber o
grau de homogeneidade de um grupo ou ou
ou perfil de dispersão de um grupo eu
vou calcular primeiro uma variancia que
vai ser um termo quadrado por isso que
depois a gente tira de Gir padrão porque
imagina se eu tô trabalhando aqui com
minha variável X é uma é altura das
pessoas Todo mundo vai ter 1,80 1,70
1,50 m vai tá entre 1 m 40 até 2,10 m
por exemplo só que você eleva o termo ao
quadrado esse número vai ser metros
quadrados ou seja tô pegando uma reta e
transformando numa área então eu não
consigo comparar metos quadr
se forma volta a tá em metros tem outra
forma sem ser elevado ao quadrado tem se
eu botar o módulo de x menos a sua média
eu tenho uma coisa chamada desvio médio
que ele é em módulo em vez de variância
Então você tem a variância e o desvio
médio que serve mesma ideia de de de
dispersão tá bom gente eu não vou entrar
muito no detalhe aqui senão a gente não
vai ter muito tempo Acho que eu já tô
falando muita coisa nem cheguei no
modelo
KNN bom aqui a gente calcularia a varian
simplesmente você pode
botar STD que é o desvi padrão Ou então
var eh DF pon aqui você botaria ponto
STD quec desvi padrão então ponto var C
A variância se eu quiser calcular a
medida descritiva de toda a base de
dados df. Scribe ele fez a descritiva ou
seja ele conta faz a média faz o padrão
faz o mínimo primeiro quartil mediano ou
segundo quartil terceiro quartil e o
ponto máximo de todas as variáveis
numéricas repara Eu não disse para ele
quais variáveis ele ia fazer mas Ele
identificou Quais são as variáveis
numéricas e fez isso para mim sejam elas
discretas ou contínuas tá Ah ele pode
incluir todas inclui All se eu quiser
botar Olha bota toda minha base tá você
não não não identifica para mim mas olha
o que que ele traz aqui para você ó
espécie e Ilha ele não vai te trazer
média de espécie Ilha porque são
variáveis nominais né então ele vai
ficar aqui com
n e assim no sexo também nas demais ele
vai calcular você quiser incluir todas
você vai botar include ou sen não você
vai só botar no
scrip se a gente quiser selecionar um
subconjunto de dados só quero pegar na
minha base só a espécie e a massa
corpórea eu S botaria esse aqui dois
colchetes selecionei as variáveis que eu
queria e posso guardar o d aqui no a a
igual a isso então guardei uma nova base
de dados selecionei só que eu queria
selecionar
Ahã se eu quiser pegar só uma coluna só
mesma coisa só fazer isso aqui ah só
quero criar Então pega somente Quem é
maior que 200 ou que seja quem tem um
comprimento de asas maior que 200 mm
então vai lá d a variável que eu quero
maior igual a 200 você vai tá guardando
esse M que 200 aí conta quantos pinguins
T MX maior que 200
Olha eu tenho 185 menores ou seja false
e 148 true Ou seja eu tenho 148 pinguins
que tem maiores que 200 o seu
comprimento de de Asa e eu posso só
pegar toda a base de dados com aqueles
que TM maior que 200 Porque eu guardei
ela aqui né Aí eu trago a base de dados
aqui que eu
quis a gente pode combinar operadores
lógicos e o e que operador Lógico é o
seu e Comercial o ou é essa barra
vertical e o not ou seja não incluído só
só botar um tio então se eu quiser pegar
Olha é pinguins do sexo masculino que
tem um comprimento de ASO maior que 200
e que tem um comprimento
e de bico né menor que 42 então traga
tudo isso aqui para mim ele trouxe então
combinei ó igual igual a isso e e eu
combinei eu poderia pegar um ou se eu
quisesse e mudar Aí eu posso fazer um
histograma também disso aqui e você vai
usar o mar plot Lead para fazer um
histograma então pego a fazer histograma
de quê de variáveis contínuas só faço o
histograma de variáveis contínuas
variáveis numéricas qu a variável
categórica a gente vai fazer outra coisa
eu posso também combinar variáveis
categóricas quero pegar sexo dos
Pinguins e eu quero saber a dispersão
deles eu vou fazer um box plot
comparativo aqui eu quero fazer um
histograma por exemplo da da massa
corpórea do pinguim aí observa Olha que
tem poucos pinguins com peso muito alto
a maioria tá por em torno de 3.000 a
4000 eh milig
né Se quiser fazer um box plot o usando
eu tô usando o Mat plot Lib tá É só usar
lá eu quero fazer um box plot de quem do
comprimento do bico e do comprimento do
e da espessura do bico aí tô botando
todos os pinguins aqui se eu quiser
pegar contar fazer um gráfico de
espécies eu posso fazer um sun count
plot ele vai contar e vai fazer um
gráfico para mim comparativo de espécies
se eu quiser fazer agora e a
distribuição
[Música]
eh deu uma travada
mestre teu áudio tá travado seu
comprimento do bico a outra vai ser e
outro batei em vermelho pul pulou um
pouquinho ali que teu trado pulou um
pouquinho é paraou onde aí aonde você
quando você tava saindo desse e indo pro
pra pro 26 isso isso isso tá eu já
deixei rodado tá gente para adiantar que
se fosse rodar tudo agora que não ia dar
tempo já tô extrapolando o horário já
quase bom aqui se eu quiser pegar a
distribuição da do comprimento do bico
de de cada um do dos dos Pinguins e do
da espessura dos bicos eu vou usar de
novo S tô usando SM de splot eu tô
plotando aqui a distribuição dos
comprimentos de cada um dos bicos aí eu
consigo ter uma nossa S esse aqui são
mais concentrados esse aqui é um
pouquinho mais disperso eu consigo ter
uma noção de cada uma das variáveis Por
quê Qual é a minha intenção eu quero ver
quais são as variáveis que eu consiga
classificar melhor cada espécie AB
baseada numa foto então se eu pegar o
comprimento de bico a gente sabe na
Biologia que cada um do tipo ou espécie
de pinguim o comprimento de bico difere
os seus pinguins como a gente sabe que o
ser humano a idade a distância entre
cada um dos olhos a distância da orelha
Até a ponta do nariz evolui com a idade
então assim quanto mais maior a
distância maior a idade do indivíduo se
você comparar ele com ele tirando fotos
dele ao longo da vida você consegue
estimar mais ou menos a idade de um
indivíduo pegando algumas estatísticas
de foto ou seja de comprimentos Então o
que a gente vai fazer para classificar
fotos é isso a gente também pode pegar
tonalidade de cor por exemplo a foto se
você conseguir entender aí a foto vai
sair o mega pixis lá para você você
consegue então expandir ou comprimir pro
tamanho que você quer você consegue
saber a cor da pele do indivíduo e
começar a classificar esses indivíduos
Baseado Em algumas fotos então tem
várias características aqui o nosso
interesse é qual é a espécie de pinguim
baseado nessas variáveis que eu tenho eu
eu tô usando só comprimento de bico mas
eu po ter comprimento da asa eu tenho
peso também tem sexo tem outras
características e aqui eu tô combinando
e uma outra coisa interessante a gente
vai fazer um scatter plot aqui primeiro
só do comprimento do bico e do da
espessura do bico do pinguim por espécie
Olha só que coisa legal se eu pegar só o
comprimento do bico e e a espessura do
bico eu consigo já discriminar a espécie
ó a Adele ela fica mais ou menos aqui tá
tudo em azul a gento ela tá toda aqui em
verde e a Shin Strap ela tá em laranja
repara que tem já uma divisão tem uma
uma zona confusa aqui eu tenho algumas
espécies que se confundem mas eu consigo
ir na maioria dos casos separar as
espécies só pelo comprimento do bico e
pela espessura do B como que eu sei isso
a gente pode descobrir dados mas em
geral gente eu não posso sair mexendo em
dados sem saber
daar um pouquinho antes como é que eu
separ como é que eu identifico as
pessoas como é que eu classifico espécie
E por incrível que pareça uma das
classificações de espécie em pinguins
com leão muito semelhante é comprimento
de bico então já sabendo disso já era
esperado que o comprimento de bicos
diferentes eu posso diferenciar
espécies é mais ou menos isso então
gente a ciência de dados ela serve para
fazer análise expor
tá me
ouvindo sim sim é que tá aqui ninguém
consegue ouvir
apresentação não não tá Ah tá é que
normal é Ah então tá
eh então não a gente não sai da análise
de dados sem conhecer o objeto de estudo
eu aqui peguei um objeto que eu já
conhecia eh alguma característica e e é
uma exemplo de aula um exemplo de
aplicação que eu fiz no webinário Então
já conhecia um pouco desses dados Ah
aqui eu posso fazer só para para fazer
um processo de Contagem posso de novo
pegar os cinco primeiros Agora eu quero
fazer o seguinte eu quero fazer um Per
plot por espécies aí eu vou fazer lá
olha eu vou ver a massa corpórea eu vou
ver o comprimento de asa eu vou ver
espessura de bico e eu vou ver o
comprimento de do bico você percebe que
todas essas variáveis olha só que o a
comprimento da asa ela aqui ela se
confunde quando você cruza o comprimento
da asa com com a massa corpórea eu não
consigo separar muitas espécies azul e
laranja nesse nessa combinação de
variáveis e não consigo também na no
comprimento de bico com a massa corpórea
Ou seja a massa corpórea Eu só consigo
separar ou visualmente separar né que
visualmente que a gente tá vendo quando
eu pego o comprimento do bico junto com
a massa corpórea eu tenho uma separação
mais visível eu consigo separar esses
elementos que é o nosso objeto eu eu
quero classificar esses pinguins em
relação a suas espécies então a gente tá
fazendo toda uma análise descritiva
antes de entrar pro
modelo eh e eu S cruzar outras duas
variáveis você você consegue ver você
consegue separar a a a comprimento de
bico aqui
com a espessura dele é que melhor
segrega eu consigo se separação mais
clara repara que eu tenho poucas
misturas aqui eu já tenho misturas
maiores entre verde e azul e laranja do
que eu tenho aqui eu preciso ter duas
variáveis só eu posso ter três posso ter
quatro Você pode ter um monte de
variáveis só que você vai entrar no
grande eh grande problema que é que é o
problema de dimensionalidade que eu vou
começar a citar aqui agora para vocês
bom no pacote sakit learning a gente tem
já implementado o KNN que é o k nearest
neighborhood ou seja um número de
elementos vizinhos por que isso isso é
um classificador muito simples tá eu Ken
o mais simples classificador muitas das
vezes gente os nossos problemas não
precisam ter um modelo absurd aburdo às
vezes os modelos mais simples são os
melhores se a gente sempre tem que
ponderar custo benefício eu posso
demorar 50 meses para fazer um modelo
excepcional que tem um acerto de 93% ou
eu posso demorar 5 dias e faço um modelo
que tem 90% de acerto gente ganhar 3% e
demorar 50 meses a mais na velocidade
que tem hoje o o que o mundo é compensa
não sei se compensa a gente tem que
sempre ponderar custo do benefício em
modelagem tá bom então k o KNN ou k
nearest neighborhood e ele é um
algoritmo que pega os k vizinhos mais
próximos e ele pode ser utilizado tanto
pra classificação quanto para C vizinho
mais próximos né Isso é bem complicado
imagina o seguinte que você tem seu
scatter plot aqui de cima que você tem o
comprimento do bico E você tem e a
espessura do bico e comprimento do bico
você tem essa isso aqui é sua base Aí
entrou um novo indivíduo marcar um
xizinho aqui xizinho aqui em cima ele tá
aqui digamos que ele tá aqui eu consigo
escrever aqui onde que tem alguma
ferramenta de escrita aqui não tem
né Acho que não não tem é que no no Zoom
tem imagina que eu tenho um xininho Eu
tenho um shinz inho aqui onde eu t
circundando com o meu mouse não sei se
vocês estão conseguindo visualizar eu
digo para vocês o seguinte eu vou
observar os seis os sete vizinhos mais
próximos desse ponto para definir se ele
é azul ou laranja Aí Se Eu Olhar faço um
círculo em volta você vai ver que a
maioria são laranjas então o que que
você conclui no no KNN se eu vou olhar
sete Vizinhos se eu tenho cinco laranjas
e dois azuis esse novo indivíduo que
entrou nesse ponto que a distância
euclidiana desse indivíduo novo para
cada um dos indivíduos baseado na no seu
comprimento de bico e na sua espessura
de bico Eu tenho dois azuis e cinco
laranjas você vai dizer que esse novo
indivíduo é o quê você não sabe a cor
dele você precisa classificar a espécie
dele você vai dizer que ele é laranja
porque tem a maioria em volta dele é
laranja e aí entrou um outro problema né
quantos vizinhos eu olho você pode fazer
isso paraa classificação imaginamos eu
tô classificando agora entre laranja e
azul disse que é laranja ou eu posso
fazer por exemplo calcular o salário
dele aí eu tenho a variável aqui
comprimento do bico digamos queou o peso
dele por exemplo eu tenho comprimento do
bico dele aqui a espessura do bico e o
comprimento do bico ele cai no mesmo
local eu quero saber qual deve ser o
peso desse pinguim baseado nesses dois
aqui aqui eu pego os sete vizinhos aqui
eu tô pegando as cores né porque eu tô
vendo
espécie o peso desse vizinho o peso
desse vizinho peso de cada um dos setes
como é que eu diria que esse novo
indivíduo que tá aqui no centro Qual o
peso dele eu faria a média então um KNN
pode ser utilizado tento sempre pra
classificação ou para modelo de
regressão que te dá uma média e um
algoritmo simples ele vai calcular a
média entre os sete indivíduos e vai
dizer olha provavelmente esse indivíduo
pesa em torno de 300 e pouco e 3 kg 200
por exemplo se eu tivesse naquele meio
ou ele deve ser laranja se você quiser
classificar a cor dele então o Cain pode
ser utilizado para variáveis numéricas
que o qu dizer numérica contínua né que
é peso eh poderia ser salário de alguém
masos que sejao problema ou paraa
classificação são pros dois métodos a
gente pode utilizar então recordando a
definição de variáveis que vimos podemos
a grosso modo entender variáveis como
quantitativas ou qualitativas e o KNN
serve para as duas eu posso fazer
modelos de classificação que seriam para
variáveis qualitativas eu posso fazer um
KNN para modelos de tipo de regressão
que são para variáveis quantitativas
então o mesmo algoritmo serve pros dois
casos
usualmente Esse é o mais usual nós
referimos a resposta usando kain quando
a resposta
qualitativa e problemas quantitativos a
gente usa regressão normalmente mas a
gente pode usar o KNN também tá ele pode
ser utilizado pros dois
modos agora aí tem o acerto e erro vamos
uma aplicação aqui bobinha Olha eu tenho
esses três novos elementos que estão
guardadinhos aqui ó esse elemento aqui
obviamente eu vou classificar ele como
Azul tudo que eu olho volta dele ele é
azul esse elemento aqui tudo que eu vou
olhar em volta dele a maioria vai ser
laranja Então vou classificar como
laranja e esse elemento aqui agora gente
aqui do meio ele vai ser classificado
como o qu olha como é que a gente faz
Olha eu vou aumentar esse espaçozinho e
esse esse cater plot que eu fiz aqui eu
adicionei esse xinho nesses pontos tá
vendo eu botei os pontos que eu queria e
botei o ponto x ponto Y que eu queria
dele só para marcar um xinho para vocês
verem aí agora eu vou fazer um zoom
nesse x aqui eu vou fazer um zoom para
ele tá Fiz um zoom dele tá vendo a
maioria tá laranja volta só um verdinho
aqui como que eu vou classificar aqui eu
peguei um outro xizinho fazendo zoom
Olha se eu olhar só um vizinho mais
próximo eu vou dizer que ele é verde Se
eu olhar Dois Vizinhos Eu vou ficar em
dúvida ele é verde ou ele é azul porque
eu tenho ah pego mais próximo então
classificaria como Verde mas assim os
dois mais próximos Eu tenho um de cada
cor não consigo classificar se eu pegar
os três mais próximos eu vou ter um
verde um azul e um laranja não consigo
classificar se pegar o quatro mais
próximo Você aumentar esse R você vai
ver Olha tem o próximo é laranja então
então teria dois laranjas um verde e um
azul pelo critério de classificação
classificaria ele como laranja e como é
que eu falo que é distância porque o
ponto ele tá aqui eu calculo a distância
euclidiana dele pro Verde quem a
distância euclidiana X1 - o x observado
elevado ao quadrado mais y1 - Y elevado
quadado isso aqui a gente aprendeu no
segundo grau gente ou seja esse método
de cálculo de distância vai calcular a
distância daqui para cá vai dar um
número distância daqui para cá um
vetorzinho a gente pode ver at em física
vai dar um outro número daqui para cá
outro número daqui para cá outro número
então são distâncias tem só distância
euclidiana que existe não existem
milhões de distâncias então de acordo
com o método de distância que você tá
utilizando Pode ser que sua
classificação mude tá aqui eu tô usando
o exemplo mais clássico que é dist eana
e aqui você classificaria tá vendo tô
fazendo un circulozinho para você
entender à medida que eu vou aumentando
os vizinhos eu vou aumentando esse
círculo Ou seja eu posso mudar a minha
classificação à medida que aumenta o
número de
vizinhos onde que eu paro nisso Diogo
como é que eu defino o número de
vizinhos aí a gente tem um gráfico de
elbow Ou aquele gráfico de cotovelo que
define a medida que aumenta o número de
vizinhos onde eu tevo parar que não
tenha mudança de classificação eu não
trouxe aqui o método de elbo Mas é para
vocês entenderem é o método que eu uso
para definir o número de k vizinhos
quantos vizinhos eu vou olhar
Ah aqui eu só fiz um gráfico para vocês
entenderem blá blá blá fiz o head aqui
eu dropei algumas espécies e fiz algumas
classificações
agora o grande problema nesse algoritmo
de cainn é da dimensionalidade que que é
isso basicamente quanto maior o número
de dimensões que que eu falo dimensões
variáveis explicativas eu peguei lá
espessura do do bico e comprimento do
bico Ah só tem essas Du que vai
adicionar mais posso adicionar
comprimento da asa vou adicionando um
monte de variáveis ou seja
dimensionalidade aumentando
dimensões então com quanto maior o
número de dimensões em um data 7 mais
irrelevante as distância entre os pontos
se
torna Então a gente tem que ter
parcimônia na hora que a gente for usar
o número de variáveis você podia falar
assim ah para que que eu usei duas podia
usar 200.000 aí vai entrar um problema
as distâncias se tornam irrelevantes
você você não consegue
classificar Então aí tem a maldição da
dimensionalidade isso é um grande
problema no KNN também bom se aí ali eu
tava fazendo aquele Exemplo né se
considerarmos um Círculo Verde só teria
um vizinho se considerarmos três
vizinhos o círculo azul eu classificaria
de outra forma se eu tivesse sete
vizinhos que é outro ciclo paraa
classificação gente a gente sempre
considera o número ímpar de vizinhos por
quê Porque eu tenho desempate
automaticamente você considera o número
par eu corro o risco de empatar na
classificação Aí ferrou se eu tiver Um
empate aí o algoritmo Vai falar Vou
classificar como quê não vai classificar
como nada ele não vai saber porque o
número de de a classificação que ele te
traz como resposta é de acordo com o
número de que tá dando se der empate ele
vai botar lá para você não não sei se de
tem dois amarelos dois azuis como é que
eu quer que que eu diga aqu ele é azul
ou amarelo eu não sei te dizer você me
disse que eu vou classificar ele pela
maioria pela presença da maioria porque
essa é a definição do knm Ah então vou
trazer cinco porque Obrigatoriamente se
eu tiver dois grupos um vai ter três
outro vai ter dois no máximo Então vou
classificar pelo máximo observado bom ah
agora a gente pode entender a base do
algoritmo depois que a gente entendeu a
ideia todinha do algoritmo como é que a
gente faz ele a gente pode trazer ele
pelo S kit learn a gente importa o s kit
learn Navy base gusan trazendo um p e eu
tô usando a função ó k neighborhood catf
usando um vizinho só aí eu pego uma base
de treinamento de x e de Y ou seja eu
separo as minhas variáveis de entradas
que são meu x ou seja Quais são as
variáveis que eu vou usar para
classificar e meu Y são as
classificações Ou seja a espécie aqui
são as espécies e aqui são as variáveis
que vão ajudar a classificar a espécie
então separo né então meu KNN com um
vizinho só separando e trago aqui faço a
previsão olha ele fez a previsão para
mim olha esse primeiro indivíduo é Adel
o segundo é Adel o terceiro é Adel ele
já tá classificando para mim como é que
ele classificou Diogo eu disse só um
vizinho então aquele cara o vizinho mais
próximo dele é a del então ele vai
classificar com a del e assim
vai agora vamos checar algumas métricas
do modelo como é que eu sei se modelo tá
adequado e se não tá adequado a gente
tem uma que a gente chama de Matriz de
confusão ou ou um um report da Matriz de
confusão o que que seria a matriz de
confusão seria quantos eu disse que é da
espécie a e efetivamente é da espécie a
quantos que dis que é da spsa mas ela é
da B Ou seja eu tenho como checar o que
é certo e o que é errado e eu tenho uma
coisa que eu chamo de acura score ou
seja com modelo simples já achei uma
curaça de 85% na classificação entre os
pinguins baseado somente no comprimento
da
da do bico e da espessura do bico aqui
eu posso printar eu tenho uma noção a
precisão do AD 84 do chip 75 ou seja tem
a precisão de cada um deles tá diferente
eu tenho a curaça do modelo como todo e
assim eu tenho as classificações ó o que
que é relevante que que é mais aí outra
coisa que eu tenho que checar também no
modelo de classificação que que é mais
relevante o falso positivo ou falso
negativo que que entende isso aqui hoje
que a gente tá falando muito no mundo
que vai trabalhar muito com falso
positivo e falso negativo a vacina pro
covid que que a vacina covid faz ela
cria eles estão criando vários métodos
de Vacina se ele através de método
genético ou vírus atenuado ou ulação do
vírus e por parte do DNA do vírus na
para que suas células produzam
anticorpos você tem vários métodos para
você gerar vacina só que acontece cada
um reage de forma diferente e você vai
testar a reação dele pessoa tá doente ou
não tá doença ou seja o falso negativo é
pior do que o falso positivo ou não
imagine o seguinte eu tô criando a
vacina que se eu não te curar eu te mato
olha que absurdo né mas imagina que seja
assim e eu ten um falso
negativo é bom ou é ruim que seria o
falso negativo é imagina que é que você
tem um um um uma doença que que seja o s
covid não o dois né e o m que ele mata a
pessoa rapidamente ou então um ebola da
vida eu testo você imagina que o ebola e
é o ebola é altamente Contagioso eu vou
testar você você vai entrar no país eu
digo não testei você e disse você não
tem a Bola E Se isso for um falso
negativo ou seja eu diz que você não tem
mas na verdade você tem você vai
transmitir a bola pro Brasil inteiro em
questão de dias
então falso negativo nesse caso é
complicadíssimo é melhor eu ter o qu um
falso negativo ou um falso positivo
nesse caso um falso positivo então
identificar que não somente a curá é
importante mas saber no que eu tô
errando eu tô errando mais para falso
negativo ou para falso positivo o que
que causa o meu erro porque você sempre
vai ter erro tá então os estudos do
falso negativo falo falso positivo são
extremamente importantes ainda mais na
área de saúde
ah aí eu posso fazer um treinamento eu
tô fazendo alguns treinamentos aqui
calculando a a para deixar mais claro
esses resultados nó vamos verificar a
fronteira de decisão do KNN eh em caso
de duas variáveis no caso assim a
fronteira que decide esse valor aqui de
distância se eu tiver uma distância
menor eu classifico de um jeito maior
classifico de outro então tô só
identificando Qual é a minha Fronteira
de decisão
Ah aqui eu tô entrando com os vetores
aqui eu não vou entrar no passo a passo
de cada uma das programações eu vou
deixar isso aqui para vocês tá gente
Caso vocês queiram ver Eu também Criei
um outro esse aqui é o que eu já deixei
pronto para dar aula e eu tenho outro
com tudo isso aqui em branco para que
vocês possam fazer é tipo Professor eu
faço isso não deixo em branco Olha meus
alunos façam isso eu trago um pronto
para dar aula aí depois eu quero que
vocês usem um em branco para fazer a
ideia é mais ou menos essa e como é uma
ideia de classificação eh no final eu
rodei aquele KN neighborhoods aqui eu só
tô testando como aqui eu tô fazendo um
gráfico para dechar mais bonitinho e que
isso aqui seriam as fronteiras de
classificação Observe nessas fronteiras
Eu tenho um cara outro que eu
classifiquei errado não tá no verde Ele
é vermelho estaria classificando no
verde e assim vai então tô criando Na
verdade tô criando Essas funções aqui o
KL tá criando essas duas essas digamos
três funções vai mas na verdade são duas
essa função aqui e essa função aqui essa
função que faz isso e essa função que
faz isso aqui para separar baseado em
quem na sua amostra peguei uma
amostrinha como o Thiago disse
selecionei uma amostra criei essas
fronteiras e tô aplicando no todo para
classificar todo mundo
essa a ideia do akn e aqui eu tô
classificando espécies eu poderia
classificar pessoas é ela mesmo ou não é
ela mesmo então tem várias formas de
classificar e vocês usam muito isso com
foto bom essa era a ideia que eu trouxe
para vocês o código é muito grande eu já
passei muito do meu tempo por isso eu
avancei um pouco e não entrei no detalhe
de cada um dos códigos Aqui tá o kainen
neighborhood classifi vai classificar eu
classifiquei baseado só em um vizinho eu
poderia aqui botar sete aí aí o KNN
predict ele vai trazer suas previsões do
seu Y vai baseado no que você trouxe
como classificador aqui qu você criou o
seu modelo quem seriam as suas previsões
no teste ou seja não é na minha base que
eu treinei é na minha base de teste a
depois eu faço o seguinte eu
classifiquei meu teste com essas eu
comparo com que efetivamente eu tenho
porque eu minha base de teste eu
classifiquei ela mas eu tenho valor real
observado aí vou fazer um depara é o que
a gente chama de acuracidade que seria
acuracidade eu bot o y de teste o y
predito quanto do teste eu acertei na
previsão
gente era isso que eu tinha trazer para
vocês aqui posso fazer a matriz de
confusão para saber qu que eu tô errando
acertando baseado nas espécies vou
deixar o código disponível para todo
mundo é uma aula
curta na verdade fazer diferente de uma
apresentação que seria uma sequência de
apresentações não sei se seria legal
espero que vocês tenham gostado era isso
que eu tinha muito Masso cara parabéns
legal demais
vem bem bacana mesm era bem aquela essa
pegada que a gente tava imaginando né
primeiro a gente entrava com uma uma
parte mais explanatória para chamar o
pessoal para para esse universo e depois
eh aplicar isso na na vida real né para
ver como é que essas coisas de fato
funcionam então foi foi muito bacana a
gente recebeu aqui umas perguntas aí
depois vocês vão me passar essas
apresentações tem muita gente pedindo as
apresentações muita gente elogiando
então aí depois a gente vai fazer essa
organização aqui para passar tá E aí eu
recebi algumas perguntas aqui eu não vou
não dá para fazer todas eh eu vou passar
depois pro e-mail de vocês pra gente
também não se alongar demais aqui mas eu
vou eu vou fazer algumas perguntas eh
paraa gente ter esse esse final de
bate-papo aqui aí Thiago Eu queria
começar contigo
eh o nosso colega Denis mandou uma
pergunta que é o
seguinte existe de existe no mercado
programas de alfabetização de dados né o
data litery que objetivam capacitar as
pessoas na organização no entendimento
análise e comunicação dos dados com base
em métodos e
ferramentas na sua opinião qual a
importância de um programa desse tipo no
cérebro você tem alguma dica para dar
pra gente nesse
sentido eu eu eu acho fundamental né
porque para você você trabalhar com com
dados tomar melhores decisões né você
fica ficar nesse negócio de achismo na
nas empresas a aquele aquela tradição de
a pessoa mais bem paga né o o ripo né
High opinion Person não tem isso né a
gente tem que pegar os dados analisar
todas as nossas decisões têm que ser
orientadas a dados né data driven né
então Eh eu acredito que a gente tem que
ter uma uma revolução nesse sentido né
hoje a gente tá imerso em dados né como
eu eu falei né né pô 80% dos dados são
não estruturados então não só os dados
que a gente tem de tabelas eh tabulares
enfim a gente tem que também ter saber
trabalhar com textos imagem fazer
análise de sentimento saber o que que as
pessoas estão pensando em relação a
determinado assunto a sua empresa por
exemplo né O que que seus clientes estão
pensando de você né são tanto os que já
tão clientes como os que já vão vão vão
vir a ser clientes Enfim fazer análise
de chne né quer ver a retenção dos
clientes eh pegar toda essa essa ideia
de dados e trazer de Fato né nesse data
liter né que é a alfabetização dos dados
né aprender a a analisar os dados o que
que as variáveis estão te dizendo como é
que elas se comportam em relação a à
presença de outros e achar associações
ou até mesmo eh e aí tem que tomar um
determinado cuidado de associação e
causalidade né não são a mesma coisa
E e esse tipo de coisa né então eh eu
acho que as pessoas têm que investir
bastante os empresários as empresas tem
que investir bastante em treinamento
nessas áreas né Tá aí o Diogão aí com a
com a inferi né eu tenho aluns
treinamentos também estatística então F
né e eu acho que as empresas T tem a
ganhar muito com isso né porque
investimento que traz um retorno absurdo
né Eh você implantar um um to to uma
cadeia uma governança de dados né
aprender a a colocar porque por exemplo
a lgpd tá por aí né e isso vai ser muito
sério né a forma de que a gente vai
lidar com dados pessoais né as
consultorias e tudoo isso tudo vai ter
que ser adequado né Porque quanto mais
informação mais a gente consegue eh eh
tomar melhores decisões conseguir
otimizar as coisas mas também a gente
precisa ter um lado de de ver eh como é
que esses dados vão vão vão vão ser
utilizados né até a própria se discute
muito hoje a ética né nos modelos de
Martin learning né
Eh por exemplo no tem teve um caso no
nos Estados Unidos né em que o o modelo
ele utilizado lá para para para dar a
penalização das penas né dos presos E aí
eh um um um um preso que ele era negro e
não Reincidente tava sendo mais pen
do que um branco Reincidente então entra
to uma questão de ética né O que que
Como Treinar algoritmos né para serem os
menos possíveis esse tipo de
coisa então tem que ter toda uma cultura
data driven por trás aí eu acredito que
seja nessa linha queria ouvir a opinião
do Diogo a
também eu não lembro da pergunta de
verdade gente
asse a
perun de refrescar aí o pessoal tava
querendo saber sobre o alfabetização de
dados né como é que se isso é importante
na na numa empresa como por exemplo e
qualquer outro né como é que a gente
pode basicamente hoje o mundo gente o
mundo hoje eu eu vim agora de São Paulo
eu tava tava trabalhando no mercado a
Brasil prévio uma empresa privada né
Tudo bem que é do Banco do Brasil mas
ela contrata no mercado então é privada
eh e eu fui em várias várias
concorrentes fui no mercado de São Paulo
é bem grande eh
não existe hoje no mercado no mundo acho
que nenhum no governo então é muito mais
fácil a gente a gente direcionar tudo
para dados é mais fácil ter o controle
né é mais fácil a gente ter a observação
é mais fácil questionar então assim
alfabetização de dados é é para ser dade
agora acho PR criança 5 anos 2 anos de
idade é important saber mexer em dados
manipular dados saber interpretar dados
saber como usar os dados e saber que
tudo que a gente observa todas as
informações que são passadas pra gente
as pessoas manipulam dados tá Gente
manipulam o que a gente interpreta o que
a gente gosta de ouvir então muitas das
notícias que são vinculadas seja ela a b
c o d elas também são frutos de
observações
então nós temos que entender que nós
usamos os dados para que a gente
interprete as informações mas a gente
também é influenciado por eles tudo que
vem até a gente também nos influencia tá
como O Tiago acabou de dar um exemplo
nos Estados Unidos sobre as
penas Como como o algoritmo pode
influenciar isso o Google faz isso gente
a gente tá no Google meeting por exemplo
o Google vocês sees pararem eles
conhecem muito bem a gente porque nós o
ser humano aí tem nas ciências humanas n
ciênci biológic na biomedicina nós somos
repetitivos tá nós repetimos nossos
comportamentos o tempo todo e se a gente
repetir nosso comportamento no Google
seja para pesquisa de qualquer coisa eu
vou entender quem é você e eu entendendo
quem é entendendo você eu te sei o que
que o produto eu posso te oferecer eu
sei que você não quer saber eu sei
quando te abordar eu sei de que forma te
abordar não sei como falar com você ou
seja Resumindo você fica na mão dos
dados é basicamente isso então feração
de dados hoje é eu diria que é assim
como psicologia tá gente que a
psicologia ajudar muito a entender eh
porque a estatística tenta interpretar a
partir do dado tá a psicologia vai me me
ajudar a interpretar o ser humano a
partir da informação que eu te passei de
dados então Eh e tem já uma área muito
grande na na na na na Dad voltando pra
parte psicológica de de interpretar o
ser humano e e e e suas relações baseada
em dados É bem interessante acho que não
tem outra volta é um caminho sem volta
tá com certeza né análise de redes por
exemplo né análise de redes sociais por
meio de grafos né teoria dos grafos hoje
tá fundamental é muito massa muito legal
vê quem é o cara que tá articulando na
rede quem quem é o cérebro quem é todo
mundo reproduz quem tá pensando hoje nós
somos assim tá então gente eh não não
tem jeito é da minha visão no meu ponto
de vista ainda mais agora senda gestor
de analíticas né do do próprio banco eh
e aí O lgpd o que ele falou é
importantíssimo lgpd que veio veio
porque ainda vai valorizar mais ainda o
estatístico porque antes que que eles
estavam fazendo Ah eu tenho acesso a
tudo qu é dados então eu jogo todo mundo
aqui dentro uma serero tudo qu é dado
vai me dar uma resposta não não me
interessa o que a causa o efeito
casualidade que nem o Thiago tava
falando não me interessa então ser agora
não eu não vou ter acesso a tudo qu é
dado eu vou ter que pedir ao cliente
para saber se eu posso ter ou não ter
acesso a isso e ou seja vai ter que ser
muito mais elaborada vai ter que
conhecer muito mais a teoria de clientes
a teoria financeira a teoria psicológica
teoria de relação n teorias eu vou ter
que conhecer para conseguir fazer
modelos ou usar dados mais apropriados
principalmente com lgpd assim espera-se
né não sei como é que vai ser no Brasil
Às vezes a gente imagina uma coisa né
mas a lgpd entrou agora tem um mês eu
acho não tem muito tempo mas é isso que
eu entendo de de dados Então vamos lá
deixa eu eu recebi assim muitas
perguntas eh até tanto no e-mail como
aqui no no chat o pessoal acho que a
gente atinge o nosso objetivo eu tô
muito feliz porque bastante gente se
empolgou muito com o assunto estatística
E aí as pessoas estão fazendo de formas
variadas mas no fundo no fundo querendo
saber a mesma coisa como é que a gente
faz para aprender esse negócio por onde
que a gente começa quem não tá quem não
é formado em matemática consegue encarar
um um mestrado como é que é isso aí eu
queria ouvir dos dois assim né porque
vocês dois têm T lá de experiência e
formação nisso aí alguém começa a atirar
para qualquer canto não dá certo a
maioria de nós tem alguma formação numa
ou na na administração ou na Ciência da
Computação Tod muitos de nós
desenvolvedores então com muita parte
técnica bastante avançada mas matemática
e estatística não é o a os a formação
principal da maioria da da Galera que tá
aqui então tá todo mundo assim muito por
onde que eu vou eu vou para um uma
trilha básica eu vou para uma formação
acadêmica de fato o que que eu faço aí
eu queria que vocês dois dessem a
opinião de vocês aqui aí as outras
perguntas a gente vai compilar e mandar
por e-mail só pra gente terminar esse
nosso bate-papo aqui fica à vontade aí
Diogão pode
eu tá então assim eh como é que eu acho
que todo mundo pode aprender estat
crística tá gente se se até eu aprendi
acho que todo mundo pode aprender e e
quanto mais a gente vai estudando eu tô
falando por mim tava comentando com o
Thiago um pouco mais cedo Quanto mais eu
estudo mais eu vez que eu sem memos é
impressionante isso quanto mais
aprofundando você vai estudando e eu
tava comentando isso agora no no banco
que eu tô terminando meu doutorado a
pessoa Ah mas já é doutor falei gente
doutor sabe o a pulga da pulga que tá no
cavalo não sabe nada é tão específico
que não serve no final para quase nada
então
assim todos podem aprender todos agora
tem que tirar essa barreira que vem da
construção da gente eu não sei quanta
vocês mas eu estudei no rio eu sou
carioca como teag tem alguns problemas
de construção na nossa na nossa no nosso
nível médio na nossa formação que a
cultura que as pessoas não gostam muito
de matemática não pode ter isso Gente
vocês não existe isso vocês precis se
dedicar com esse matemática tem vários
canais no YouTube te ensinando
matemática básica é uma coisa que eu
vejo muas gente pessoas quer fazer Ah eu
quero saber fazer logo modelo mas não
sabe o básico da Matemática às vezes é é
o que a gente chama de semianalfabeto
nesse caso o cara vai fazer vai queimar
a casa que nem thago apresentou lá você
pode fazer isso porque a gente tá num
processo acelerado né que a gente quer
saber logo no final a gente pode começar
a final mas depois vai voltando para
entender o que você tá fazendo que aí te
forma um profissional melhor te D mais e
mais suporte para para suas decisões e
te dar mais clareza n n suas decisões
então assim o que que você faz para você
aprender eu hoje o que que eu faria tem
muita plataforma aberta tem aulas no
YouTube excelentes tem o canal do
próprio professor Thiago aqui tem muitos
outros canais que a gente pode aprender
gratuitamente pelo menos o básico a
gente vai começar a ganhar esse
conhecimento e e outra coisa gente
também tem canal né eu a Não tenho assim
eu gravo algumas coisas e boto lá eu não
tenho não tenho esse canal ainda não
também tenho o canal lá da inferi né a
gente tem o canal da inferir estatística
mas eu não o Thiago tem uma ele ele
trabalha isso todos os dias né eu vou lá
gravo um vídeo eu vou lá gravo outro
vídeo dou algumas dicas vocês podem me
acompanhar no canal ten mas eu tenho
menos vídeos que que que o Thiago Eu tô
tentando fazer isso mas o meu tempo tá
completamente escasso gente eu não tenho
tempo para respirar então não consigo
ter essa velocidade inclusive tá devendo
uma palestra lá também na na eu
sei não tá com tempo nem para ficar
doente direito né então é verdade É
verdade quant tempo ficar doente mas
assim na minha opinião gente todos pod
procurem hoje hoje falando agora em 2020
e essas aulas em canais abertos tem tem
muito Professor bom de matemática até
básica que é bem legal depois que vocês
tiverem com isso ao mesmo acho que você
pode fazer concomitantemente tá vai
aprendendo técnicas vai porque a gente é
muito acelerado né Tá todo mundo
cobrando a gente o mundo hoje é agitação
Dan nada então não dá para falar vai
aprender devagar isso depois não vai ser
assim ele não vai conseguir então pode
fazer concomitantemente
mas nunca fica satisfeito porque saiu ah
já fiz o modelo já sei aplicar esse
modelo não cada problema tem uma
ferramenta específica nem tudo você vai
usar
Marreta Tá bom então assim na minha
opinião todos podem aprender todos todos
se eu aprendi gente qualquer um pode de
verdade eu não só E é só dedicação o que
vai fazer você ser melhor profissional
aprender estatística matemática é o
quanto você se dedica e não precisa
matemática você você precisa necessitar
as necessidad do humano faz a gente
aprender tudo vocês não tem noção da
nossa capacidade todos são depende do
quanto necessário é pra gente S
sensacional eh eh reitero aí né Tem
muita coisa boa né mas também é toma um
pouco de de cuidado né com algum alguns
materiais porque assim eu como o falou
né você tem que eh eh valorizar mais os
fundamentos né porque a tecnologia R
Python né a mã Júlia Isso muda né
efêmero né a comunidade evolui né então
Eh você tem que tendo tendo os
fundamentos os fundamentos eles perduram
ao longo do tempo né já as ferramentas
elas elas vão vão vão mudar né então Eh
investe na base né tem muitos cursos né
como eu falei né tem o Curse Ero EDX tem
de Harvard de e né hoje você pode
estudar com os melhores professores do
mundo né então a internet ela te te
proporciona isso né e foca sempre nos
fundamentos e e procura algo que você
goste né Por exemplo você gosta de
esporte vai fazer uma análise em esporte
você gosta de Finanças vai fazer finança
então isso vai te trazer uma uma
satisfação maior em encontrar resultados
que vão fazer sentido para você né então
isso te ajuda a entender melhor né E não
só isso como a gente viu aqui a
demonstração aqui brilhante aqui do
professor Diogo né Ele trouxe uma
apresentação prática né e associando e
nunca deixando de lado a a teoria né
então Eh é misturar a teoria e a prática
é fundamental né Sempre quando você
aprender a teoria né aprendeu lá
estatística descritiva vai lá e faz na
prática num software no R no Python na
Júlia Enfim no software que você quiser
pode ser até Point clique né mas tenta
tangibilizar né a gente tem a gente não
é bom com com abstrato né números assim
soltos né agora quando a gente faz um
gráfico faz uma um diagram coloca umas
coisas que façam sentido né a gente
começa a associar melhor né a gente
aprende por repetição e Associação n não
tem jeito então quanto mais você
conseguir eh fazer essas associações né
e repetir esse conteúdo isso vai
entrando e e compartilha esse
conhecimento né porque quando você
Compartilha você enxerga de uma forma
diferente você vai tentando elencar eh
de forma lógica os conteúdos e e isso
vai te trazendo uma uma maior vivência
no tempo isso vai entrando mais na sua
cabeça né e compartilhar conhecimento é
base né porque você vai dormir e e já
esqueceu grande parte do que você
aprendeu no dia né então você tem que
compartilhar esse conhecimento para isso
se perdurar né virar uma boa de Neve e
surgirem ideias Geniais aí né Então faz
um blog faz canal no YouTube divulga né
então isso é muito importante tá eh eh a
a o efeito comunidade muito pirem né
então Eh por conta disso que eu tento
trazer na comunidade estatística essa
ideia de comunidade né então todo mundo
se ajuda eu cobro bastante da galera
para se ajudar né e não só tem não é um
eu falo que não é o curso n é uma
comunidade né então todo mundo lá se
ajuda né a gente tem de diversos níveis
né Tem gerentes de Analytics a a pessoas
que tão entrando na área estudantes né
enfim então Eh essa esse efeito
comunidade eu espero que vocês façam aí
o github de vocês compartilh os projetos
hoje em dia currículo tem Tem cada vez
mais perdido o seu valor né hoje em dia
os profissionais vão direto no Linkedin
né eu mando diversas vagas de
recrutadores me procuram para mandar
vagas né em em Analytics né a gente tem
algumas eh que até vão direto na gente
né E já mandam pra gente lá a gente
divulga pros alunos divulga nas redes né
então cara o Linkedin hoje em dia é uma
fonte de Triagem de currículo às vezes
até com inteligência artificial Eles já
fazem essa triagem sem precisar de uma
pessoa para para para selecionar né
então Eh o Linkedin se inscrevam no
Linkedin né também é é uma coisa muito
boa e façam seus portfólios faz um blog
bota lá os projetos que você desenvolveu
a criatividade Eu acho que isso vai
trazer eh um um potencial Grande para
para você receber inputs diferenciados
né pessoas vão te ajudar e você vai
evoluindo vai ajudar outras pessoas
também então eu acho que esse ciclo ele
é muito válido e e e é o que fica tá
então basicamente é É isso
aí gente muito muito muito obrigada
mesmo pela pela pelo tempo de vocês
Tiago Diogo muito muito obrigado mesmo a
gente acho que a gente plantou a
sementinha da estatística aí eu acho que
a gente pelo tanto de de e-mails que eu
tô recebendo aqui com com parabenizando
e pedindo material e e fazendo perguntas
Ach no WhatsApp lá você pega lá depois
pode encaminhar para todo mundo eu
mandei dois materiais eu mandei um que
tá escrito full que é esse completo que
vocês viram aí que eu já tá que eu já tá
rodado e tem outro lá branco ou seja pra
pessoa treinar eu fiz isso é mania minha
de fazer dois Mater é o mesmo material
tá um em branco pra pessoa ficar
treinando e outro eu já deixo pronto
para ter a aula fica mais fácil eu isso
eu sei eu sei eu já já já já tive essa
experiência é bom demais é é bom demais
então gente de novo agradeço se a gente
teve público bem bacana a gente achou
que ia ter um problema aqui com a
ferramenta porque a gente tá com alguns
problemas no no meeting e a gente achou
que ia ter uma limitação de pessoas
dentro da sala mas a gente conseguiu o
recurso ainda tá funcionando e a gente
ficou com uma média de 260 participantes
durante a apresentação toda então a
gente teve um público bem bacana aqui a
gente já tá mais de 2 horas Ainda temos
mais de 200 pessoas Então assim o
assunto é legal vocês dois são demais
então só agradecimento mesmo muito
obrigada Com certeza a gente vai ter
outras outras oportunidades aí discutir
de novo e trazer outras visões desses
assuntos para PR comunidade seana show
de bola muito obrigado pelo
conv
Valeu adorei junto a depois temar go Lar
sua com tô devendo mesmo vou te
perturbar hein vou mandar mensagem
lá show muito muito obrigado mesmo pelo
convite adorei participar e precisando
aí novamente é uma nova uma nova
palestra que vocês queiram a gente faz
de novo eu faço esses webinários
frequentemente aí eu monto outro exemplo
precisando estamos aí muito obrigado
gente Bom dia valeu