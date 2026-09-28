# Aula 07 - Random Classificação - Prof. Flávio Clésio

- **URL:** https://www.youtube.com/watch?v=0oia19nuUWs
- **ID:** 0oia19nuUWs

## Transcrição

o ponto partidários tudo bem que é o
Flávio atrás de novo e a gente vai dar
continuidade à nossa série do h2ovos e
agora a gente vai falar um pouquinho
sobre a distributor dobrou força ou
florestas aleatórias distribuídas tá
nesse vídeo A dentro do Erre usando o
h2oh mas antes de mais nada eu queria
convidar vocês se vocês não são
inscritos no canal se inscreva no canal
a tem bastante conteúdo interessante
desde a parte de visualização de dados e
estatística avançada mochila licença de
dados Então se inscreva aqui no canal e
deixa o joinha aí no vídeo tá deixa o
like no vídeo que é muito importante
para a gente ir para o canal também para
aumentar aí a amplitude desse jeito de
não a divulgação a a difusão desse vídeo
aí é através da daqui do algoritmo do
YouTube Tá bom então primeira coisa a
gente vai fazer para quem está começando
agora essa aula aqui todos os códigos
estão nessa presente aula aqui é todos
os códigos estão aqui dentro de si
se alguém tiver me chamado estatidados
traço h2oh acessível para qualquer
pessoa se você é usuário do kit Rubi só
dar o clone do repositório se você não é
um usuário do que te ame que é somente
fazer o download dos códigos só entrar
aqui na URL clicar nesse botãozinho
Verde aqui no Clone Hero download e
clica na opção aqui download Zip que
todos os códigos a não só desse dessa
aula de hoje mas de todos de todas as
idades de toda a série é bom Está dentro
está dentro desse arquivo use tá tão
entre o abrir aqui o meu rstudio
É sobre o nosso é estúdio vou em vou
entrar aqui no projeto tão deixou fechar
aqui essa última janela vem aqui eu fiz
o download documentos Ramos estatidados
ver aqui src
e depois vai sair seu entra aqui em
Rondon Force agora a gente vai fazer um
problema de a classificação também tem
tanto o a o h2oh duplo em relação à
parte regressão e classificação mas aqui
o humor a classificação só por
conveniência mas os dois códigos estão
funcionais só entrar lá e a fazer o
download fazer os seus experimentos a
certo então primeira coisa que a gente
vai fazer aqui a gente vai fazer carga
do pacote do h2oh h2oh a instalar ele se
ele não tiver ou fazer sua mente o load
nele e a gente vai travar o nosso sítio
andrônico para 42 tá para que os
experimentos reprodutíveis então mesmo
resultado que eu tiver aqui na minha
casa no meu computador na minha máquina
vocês vão ter o mesmo resultado na
máquina de vocês também a Então a gente
vai fazer a inicialização do nosso
poster do H 2 ohms então eu já chamar
aqui o ponto rinite a ponta Henrique a
gente vai passar o nosso
a porta 5 4 3 2 1 número de todos os
processadores usando 20 GB de memória e
dentro do meu clã chamado estatidados
contra já rodei aqui o meu limite já tem
todas as informações aqui do meu
consertar então ele não inicializou
plantar só conectou Então esse aqui é o
o time do meu kloster a memória
disponível e os cortes que vão ser
utilizados aqui então se eu quiser fazer
um teste por exemplo se o se o meu
cluster extrativo vem aqui no flor por
exemplo tá então vem aqui meu almoço dia
de Itaqui local onde: porta 5 4 3 2 1 e
como eu tô estendo Alone já apareceu
aqui o flor para gente aqui tá bom ah
então vamos voltar para o h2oe aqui
vamos voltar aqui pro H2 ó vou tá aqui
para o nosso estúdio e que a gente vai
fazer a gente vai fazer a carga do nosso
da nossa base de dados essa base de
dados aqui é de um toque prova no
chamado alemã Brothers né que é uma base
de empréstimos digamos assim que vai
prever se o uso
a estação de calote ou não que vai estar
nessa variável de chamado de Fogo A
então só vou colocar essa URL aqui
dentro só variável e a primeira coisa
que a gente vai fazer vai chamar aqui o
importa o pai ou e vai passar o nosso
caminho da nossa URL e vai e o destino é
sofrer desse cara que a gente chama como
lembrou dois. Rex que vai ser a nossa
base de dados no formato no formato do H
2 o frame a que a gente vai usar daqui
em diante para fazer a parte do
treinamento mas suave pode usar de la
table pode usar um csv não toda a parte
de treinamento dos objetivos do ali ó
ele lida somente com dados como com a
com dados aqui são objetos voadores
Warframe por quê Porque a toda a parte
de treinamento e a parte de
gerenciamento de objeto de memória ele é
feito de forma distribuído pelo h2oh ele
é feito isso é feito usando esse
formato. Reto está para mais detalhes em
relação a essa parte do que eu tô
falando que ponto Rex cluster nós e tudo
mais
Eu sugiro que vocês vão primeiro no
primeiro vídeo lá sobre arquitetura da
h2oh ao como que ele funciona é como que
ele funciona por baixo do capô tá a
ideia do vídeo aqui vai ser muito mais
fazer um outro em relação a esse
algoritmo de Handel forças aqui tá Então
como já fez o nosso o nosso longe do
nosso o nosso dados do ponto reto então
se eu pegar aqui para vou dar um sobre é
uma função Nativa do próprio Hermes cima
do meu frango h2ox ele já vai trazer
aqui algumas estatísticas descritivas
então é trazer aqui o agir ao limite vai
trazer aqui o limite mínimo a mediana
média de um máximo vai trazer algumas
variáveis aqui canto agora se pra gente
como sexo e do kit mete aí de novo
pessoal até por questões de de ética em
relação à parte de imaginar no Netflix
inteligentes não usem variáveis
e como sexo até mesmo como idade como
variáveis discriminantes em seus modelos
Porque isso pode ser o problema muito
grande e que não vai discutir nesse
vídeo nós pouco desse vídeo Se você
quiser mais informações deixa eu
comentar aqui que a gente já coloca
todas as diferenças em relação a essa
parte de ética aqui tá mas por até por
questões a educacionais eu vou remover
essas variáveis desse conjunto de
Treinamento como a gente vai fazer isso
primeiramente gente vai tirar da nossa
base de dados da ali a gente vai
converter Nossa variável calote para
defrontar a passarela como Factor deixa
eu dar opção melhor depois da
posteriormente em dia ver que ela
trabalhava de por aqui já tá como
dicotômica tá que tá como binária
digamos assim tão depois disso a gente
vai fazer a divisão do nosso conjunto de
treinamento aí noventa porcento para
treinamento 10 por cento para teste
usando Sprint frame no corrente a passar
o nosso. Rex aqui rádio a gente vai
determinar é o quanto que vai ser para
treinamento quanto você tá teste duas
nesse caso aqui
e a gente vai colocar noventa porcento
para treinamento e o Nosso Cid randômico
que no nosso caso a gente parametrizou
42 Então vamos chamar o nosso espírito
firme aqui criamos nosso objeto do tipo
split E agora o que que a gente vai
fazer esse objeto explique esse produto
ele tem: o primeiro food é a parte de
treinamento e o segundo foi o papo te
botar aqui e o segundo foi hoje é a
parte de teste certo então nossa
variável dependente que a variável que a
gente vai tentar prever aqui o calote no
nosso caso não é chamar aqui deixou né E
vai estar dentro desse essa variável
chamado estão aqui vai ser o depois e as
variáveis Independentes não se é real as
informações de pagamento as informações
de transações por aí vai tem um vídeo
somente essa parte de longe de dados por
exemplo recomendo que vocês vão lá nesse
vídeo aqui eu explique algumas das
variáveis a ideia do vídeo aqui não é
falar sobre kit higiene with Streisand
nada disso mais fazer o árbitro dentro
do modelo do mundo Force usado
Ah tá então de novo aqui eu vou usar eu
vou tirar a variável sexo ou gênero
digamos assim da minha do meu do meu
objeto x eu vou também tirar a idade
aqui também a que eu não quero fazer
nenhum tipo de discriminação nem tua
idade nem por sexo aqui então essas vão
ser as minhas variáveis Independentes
Então vou voltar aqui o x deixa eu não
sei se eu odeio isso também então vou
rodar os dois juntos yx atribuídos então
ele vai passar para a parte do
treinamento de modelo e novamente a
gente quiser saber todas as variáveis
todas as funções
ah ah ah ah em relação a cada um dos
algoritmos jogadores ó só colocar?
H2o.ai o nome da função nosso caso aqui
o ano Force tá E ele tá aqui tem toda a
descrição de todos as variáveis aqui do
nosso modelo tá então tem a parte de
mactep por aí vai então a primeiramente
eu vou atribuir aqui a minha várias o o
o x não é que vai ser as minhas
variáveis Independentes o y que eu
chamei já disse inteiramente vai ser
nossa variável dependente treme treme
que vai ser nossa base de trem que vai
passar o vale deixou frame que é aqui só
por questões de conveniência coloquei a
base teste mas aqui pode ser qualquer
outro tipo de de base desde que seja do
objeto do objeto a Dori sofrendo e aqui
é uma coisa interessante conseguinte a a
gente pode fazer aqui já na parte de
treinamento é fazer a validação do
modelo em relação se ele tivesse
e vem com uma base roudaut não é que a
base isolada da parte de completamente
isolada de fazer a conversão e colocaria
aqui esse Vale deixa um frame O que que
significa imagina que vocês tenham um
pai que larga de Treinamento por exemplo
que é um treinamento contínuo no qual
vocês tem uma base que é presente
celular anotada por humanos sejam um ser
humano foi lá a Valeu aqueles casos são
casos digamos assim que é a fonte da
Verdade e aqui e aí nos treinamentos
desses desses modelos a podem ser feitos
validando contra essa base que foi
anotado por seres humanos digamos assim
então o algoritmo de já saio a
completamente digamos assim lá é bom não
é confiável de que ele já passou da
parte de da parte de validação com os
dados a totalmente separa do conjunto de
Treinamento tá então h2og da isso por de
por o número de árvores aqui é o vou
colocar a 105 anos colocar 150 colocar
900 árvores diferentes
o tribunal ver Fit tá a profundidade das
Árvores aqui eu vou colocar somente a
minha árvore vai ter como profundidade
10 Então seja se eu tivesse por exemplo
imagine aqui se eu tivesse uma árvore de
decisão a por exemplo né a profundidade
nesse caso seria com um olhar que nesse
exemplo então a nessa árvore de decisão
especificamente aqui eu tenho a 29 de
profundidade né então tenho esse
primeiro não aqui nós o teu a nossa raíz
o primeiro lote profundidade e o segundo
Norte profundidade aqui nessa nossa
segunda árvore é a grosso modo o que a
gente tá falando é o seguinte e é isso
essa é uma coisa que tem que ser que tem
uma dica e é esse atributo de
profundidade de de árvore dá uma
pergunta muito sensível a parte de
overfitting que eu quero dizer se se
você se sente se você como o sentido de
dados o engenheiro de machine learning
pular e fazer uma tribo
Oi livre Band decisão por exemplo com
300 com o nível de profundidade
presentes para homens você vai ter uma
árvore muito específica que ela vai
servir o seu conjunto de Treinamento só
que ela não vai se realizar quando tiver
casos a um pouco diferente daqueles
específicos tá então por isso que é uma
variável excessivo isso vai muito do
domínio do negócio e isso vai muita
decepção as variáveis certo eu voltar
aqui no RD novo vou colocar o meu máximo
da com 10 só preciso locacionais aqui
então um outro Luan se eu queria que eu
queria mostrar para vocês que é o
seguinte a partir modo agir uma das
coisas legais jogado só que a aqui eu tô
trabalhando com o Stand Alone mas
imaginando que a gente tem no celular um
câncer de H2 ou uma máquina gigante que
várias sentidos de dados têm acesso cada
experimento que eu faço cada
configuração cada setup se eu consigo
colocar o nome nesse treinamento Então
nesse caso aqui eu vou colocar a Random
Ford Model estatidados nascem em
[Música]
o engenheiro por exemplo qualquer pessoa
que tiver dentro do que você quiser
fazer o gerenciamento desse treinamento
Nossa já viu como que eu rodei Quais são
os parâmetros ela consegue identificar
justamente já com esse nome desse modelo
isso a gente vai ver Mais
especificamente no Flu tá base classes
que ele faz ele faz ele faz um um o
Perséfone da classe que tiver menos
existe ou seja ele faz uma super uma
super nosso superamostragem a vacância
que tiver menos representado O que
significa Então imagina que tem um
problema de fraude tá aqui não vão
trazer o nosso problema que no nosso
lehman Brothers na uma parte de de
empréstimo imaginando por exemplo que a
nossa casa o nosso banco lehman Brothers
da quente foi extremamente racional EA
gente sempre deu 99% sempre teve 99% de
pessoas pagando a os seus empréstimos e
a gente tem um por cento ali que ele que
geram
Ah tá e pode parecer transfigurado
também com um caso de fraude
o seguinte vou levar para curar-se é
propriamente dita se a gente voltar toda
hora se toda a tradição que a gente der
a gente tá é sempre é o caso da variável
que tem a maioria dos casos nesse caso
aqui no nosso caso aqui é o caso de não
depois tem as pessoas sempre pagam o
nosso algoritmo de sempre vai ter 99% a
dia certo o que Teoricamente Seria uma
boa coisa só que em todos os casos a de
perdição que a pessoa entrou em calote
ou no caso de fraude por exemplo o que
houve uma fraude teve um prejuízo
financeiro esses casos que é os que são
os casos que dão a maioria dos prejuízos
a o ambiente não conseguiria prever
então que colocamos o ele faz aqui ele
ele fala assim para ele ele faz o
seguinte a tua cara eu vou ver eu vou
olhar a distribuição dos seus dados e a
classe que tiver menos representada
e eu vou é criar mais amostras para que
ela fica equilibrada para que realmente
me o poder de discriminação de uma de
uma de uma de de um caso tá basicamente
é isso tá bom a a documentação da do só
não não dá muito certo como que essa
distribuição é feita e se houver sempre
um efeito se é 50 50 60 40 tá mais o
olhar nos olhos já trabalha com essa
implementação em outra coisa que eu
queria pegar aqui da documentação que eu
queria mostrar para vocês essa métrica
que te toca o metro que eu vou chamar
ela aqui eu vou chamar essa métrica e
vou colocar como a Deixa eu escolher
aqui eu vou quero fazer minha unha
métrica de parada o ao centro tá fica o
que que só o que que esse Stop metro que
fala
e Geralmente os os algoritmos o Alison e
trabalho nesse trabalho trabalham com a
métrica de parado de treinamento né de
outro controle de convergência para se
dizer geralmente pelo log-loss ou seja
pela taxa de perda a em relação à parte
do modelo de treinamentos só que aqui
Salesópolis a gente pode colocar como
critério de parada não logo logo mas por
exemplo uma métrica a digamos assim mais
digamos assim a gente consiga entender
mais como estatístico com matemática
como cientistas de dados né que não
nosso caso é você mais se tivesse
trabalhando por exemplo com a regressão
poderia ser por exemplo RMS RMS ll e
como a gente tem a gente tem variações
muito grande nos conjuntos da gente não
quer fazer uma penalização muito grande
ou o próprio RMS E por aí vai tá então
essa meta que a gente pode usar como
critério de parada Tá bom então em vez
de usar um logo logo a gente pode dizer
que a gente fala assim para o algoritmo
é chega no resultado ideal para mim
quando você atingir uma
é de parada de aprendizado quando você
não consegue ter uma performance melhor
por exemplo tá e uma outra variável que
eu queria a colocar aqui é a variável
distri bution deixa craquinho distri
bution que eu vou colocar como No Lita e
deixou só campeão nome para não cometer
um papo a que é a distribuição dos dados
da minha variável A Dependente e aqui
uma coisa que nos que que o Alison faz o
seguinte tu deixou a distribuição da sua
variável categórica no meu caso aqui
a nossa casa aqui do lehman Brothers é
hora de forma variável dicotômica então
tô usando aqui é beroni tá se fosse um
problema se eu consigo se o orgasmo só
com o olhar nos olhos a alto ele ele faz
ele tem três escolhas por de forma se
vocês escolherem alto
é tipo uma variável dicotômica como eu
tô usando aqui nesse caso que ela deixou
ele vai trazer a distribuição Panini tá
a que vai ser distribuição padrão se for
uma um problema no carro que a gente tem
multiplas digamos assim a múltiplas
fiquei chance a gente tem vários
destaques ao invés de 01 a pode ser por
exemplo presidência em problemas que tem
mais de mais de duas variáveis por
exemplo eu pego tem que prever por
exemplo entre a b c d e e classes por
exemplo ele vai tomar como de fogo a
distribuição multinomial e se forem
dados numéricos por exemplo prever um
saldo a bancária por exemplo depressão
turma de regressão digamos assim que a
variável dependente variável numérica
ele vai assumir como padrão que a
distribuição gaussiana Então essas
coisas que assim Se vocês entenderem
qualquer pode deixar no alto ou agora o
jogador já consegue compreender mesmo
mas ele vai é
e somente essas três distribuições estão
imaginando que você está no problema de
regressão no qual a distribuição por
exemplo é uma alma possam por exemplo
distribuição dos dados é isso teria como
você teria que ser parametrizado aqui
dentro da parte do treinamento do do
h2zone tá
bom então rodando aqui vamos rodar o
nosso treinamento tá falei demais já um
pra São tá treinando aqui a gente vai
agora para o flor tá vou voltar aqui
para o flor e agora a gente vem aqui no
nosso flor local roxo 22.5 4 3 2 1 a de
mim duas testados nosso clã se está
operacional está rodando tem quiser
acompanhe o nosso treinamento a gente
vem aqui admin Jobs e a gente vê o nosso
experimento rolando aqui tá como Running
e aqui a hora que ele começou a hora de
não terminou ainda tá como Lone se eu
quiser saber o que que ele tá fazendo
por debaixo do capô aqui RF modo está te
dado sem fio tio Juninho que automodelo
quem está treinando eu clico aqui nele
ele já acabou já rodou em 24 segundos e
seja quiser saber por exemplo é esse
aqui é o que é o nome do modelo né então
aqui já tem vários experimentos que já
tinha feito então eu tenho um
experimento aqui com o gbm que eu tinha
feito anteriormente e algumas
transformações E por aí vai se eu quiser
saber
e aqui dentro do flor essas informações
em relação a esse experimento é só
clicar nessa nessa opção aqui a é a at
Once aqui nesse nesse ícone chamado viu
e aqui eu já tenho todos os parâmetros
todos paramos modelo de todo o histórico
desse treinamento Então essa é só uma
das vantagens do h2oc se eu tiver dentro
do Câncer aqui no meu caso eu tô
começando a bom mas imagino que a gente
tá no cluster é que tem que eu tenho tô
fazendo tratamento com Derm 20 sentido
de dados diferentes e cada um tá rodando
experimento esses experimentos já tem o
seu o seu registro a tanto registro do
seu treinamento dos a
e a dos seus resultados na parte de A
métricas de variação de modelo quanto
também todos eles já deixam disponíveis
aqui por exemplo os objetos Mojo bojo
aqui são objetos exportáveis já que
podem ser aí a direcionado para os
desenvolvedores da plataforma Java ou a
o escala por exemplo embutidos esses
algoritmos dentro da suas plataformas
por exemplo ou se a gente quiser somente
gerar um modelo aqui e se realizar esse
modelo a pra rodar dentro do Erre por
exemplo é só clicar nesse botão aqui
download de Agenor ler módulo da que
esse modelo já vai estar ser realizado a
tudo isso aqui na interface de comandos
tem nenhum tipo de código tá vamos aqui
para parte de modelo então se o seu
maximizar aqui então aquele já tá dando
para a gente é o que que foi que foi
executado Então esse aqui é o nome do
modelo as variáveis que ignorei aqui
então variáveis dia variar o sexo a
variável idade o ignorei o número de
árvores a profundidade a e a métrica
eu usei tô nesse caso aqui eu usei o a
você e a nossa o nosso se dinâmico e a
distribuição a que foi que foi
selecionado aqui tá a nesse caso aqui
com nesse caso aqui tá com o último
avião tá aquele tem já dá os gráficos
por exemplo de do Logo logo né então ou
seja de como foi a convergência a do
modelo tá e aquele já dá os gráficos por
exemplo na parte de Treinamento ou foi a
o resultado da área abaixo da curva tá
então ele tá dando aqui como 10 81 e
contra a base de validação né que eu
coloquei aqui no próprio h2oh como não
vale deixa o friend e de novo Até outro
usando a base de teste só por
conveniência mais a gente poderia
colocar isso por exemplo a uma base
totalmente roudaut dentro de um outro
caminho desde que a gente fizesse o
conversando com outro Rex também tá e
aqui tá dando como 77 Então esse aqui a
gente já tem todo esse gráfico aqui tudo
gerado sem nenhum tipo de código a mais
é a importância das variáveis Então tá
daqui pra gente então a gente vê que os
parques as variáveis de pagamento no
pagamento das parcelas digamos assim são
as variáveis mais importantes aí que
como preditores digamos assim se a
pessoa vai entrar na estação de de foram
não tenha também a pó para árvore de
confusão aqui também tá aqui já dá toda
a parte de glicol uma parte de prestígio
tá tanto para a parte de Treinamento
conta a parte de validação também tá
isso é importante a algumas aulas tem
boa também e a deixa eu ver alto
trimetrix tá aí a gente tem algumas
outras informações também aqui a a parte
treinamento eu vou voltar aqui para o
para o r-studio tá que todas as
informações a gente pode tanto gerar
usando somente essa função Nativa do
lado só que é o samba então se eu rodar
os ama ele dentro do meu do meu do meu
objeto de Treinamento que nesse casa que
o RF módulo tá voando
e ele já tá todas as informações que a
gente já viu lá no flu na interface mas
aqui dentro do somente textual também tá
aí vai vai de cada um mas quando Como
que eu faço uma previsão como que esse
objeto de pressão a gente vai chamar
essa função perder que é o que é o a
função rapper padrão do H2 uma para ele
fazer previsão de todos os modelos então
aqui nesse caso a gente vai usar lá no
posto mas pode ser por exemplo redes
neurais pode ser por exemplo glm GPM
tudo mais uma corrente só tem que passar
dois parâmetros objeto.no deira o objeto
vai ser o modelo de capa de treinar e o
dela vai ser a nossa base de teste outro
usando aqui somente só pra pins de
conveniência mesmo em que vai rodar esse
rapper aqui do pedir que estavam jogar
dentro desse essa variável para isso a
gente for dá uma olhada fazer uma
expressão nessa variável pra daqui a
gente pode olhar que ele já tem o
presidente Então já da classe para gente
aqui a 1001 então não deixou não
a e deixou aqui por exemplo e também já
dá para gente as probabilidades né então
se ele quiser é usar a parte de
probabilidade aqui também lá em vez de
dar um número seco dá uma prova da gente
consegue emitir também só uma coisa que
eu queria falar para vocês que é o
seguinte se vocês foram usar a parte de
probabilidade de altitude de modelos
dentro da suíte do h2oh Eu recomendo
fortemente que vocês usem essa essa essa
essa propriedade que chamado calibrei
que moro tá E é uma deixa eu colocar até
que a descrição da documentação que eu
acho que isso aqui é extremamente
importante fale para ele que moram tá
que é que vai fazer que vai fazer a
parte de calibração dessas probabilidade
está a e a gente vier e outra coisa
também na axia o calibre de modo estiver
com outro é a gente Obrigada passam
calibration frame também tá certo eu não
vou entrar em detalhes aqui se vocês
quiserem mais informações
o olhada nos dentes que vão estar aqui
na descrição do vídeo também tá mas para
parte de probabilidade vocês quiserem
retornar probabilidade usem a parte eu
recomendo fortemente que vocês usem a
parte de calibração do h2oh da Porque
ele leva algumas algumas em consideração
algumas informações como a distribuição
a priori por aí vai tá bom mas esse não
é o foco nesse vídeo aqui então eu já
vou do nosso prédio aqui eu vou dar vou
pular essas partes essas informações
aqui Todas aquelas informou se a gente
colocou pegou havia no summer né que a
gente o do anteriormente a gente pode
pegar as mesmas informações por exemplo
rodando Opa rodando confio já Mix gente
pode ter somente confio geométricas
isolado a importância das variáveis
também no modelo e geram o nosso pote
Zinho aqui dentro do próprio estúdio
para a importância de cada uma das
variáveis tá chamando aqui se barba
importância seguir aqui também a e a as
informações também do AOC mas Flávio
o modelo eu quero colocar modelo nesse
modelo da do exame produção Como que eu
faço isso beleza pessoal e vou fazer
primeiramente aqui eu vou colocar o
caminho tá do meu bicho só colocar aqui
do caminho do meu diretório raiz tá
então eu estou rodando oh2 lá então se
eu vim aqui no modo whatsfake esse é o
caminho que eu vou passar os modelos
então seu vinho
e aqui na minha pasta por exemplo Paulo
chopp aqui o caminho
bom então por exemplo vem cá daqui para
minha pasta posso perder a Ah tá não tá
entrando porque eu não tenho vou fazer
Live aqui só se dedo do documento hip
hop as cidades h2ol Agora sim eu tô a
gente está na aula de anda forte que 05
vender Force uma aliança aqui e é assim
menos um ele aparece aqui que eu só
tenho só esses dois escritos daqui para
minha pasta aqui tá bom então eu vou
rodar esses aí ó esse seis mora aqui que
é um lá porque ele faz ele que ele salva
qualquer tipo de modelo da dois ovos que
eu tenho que passar duas variáveis para
ele tá um objeto aqui que é o modelo de
predição aqui no nosso caso é que eu RF
módulo e o caminho que nesse caso aqui
vai ser esse arquivo até né que é esse
caminho aqui da pasta do espaço dados
que a gente tá rodando aqui tá bom pro
som voltar para brigar
e o pato nesse menos um tá deixa mental
a fonte AC mudar de novo é
e pronto e eu vou salvar dentro desse
caminho vou salvar esse esse modelo Ou
pegou ele vai trazer uma porcentagem
aqui acho que foi rodou um rápido quem
mudou a porcentagem esse eu vou dar aqui
novamente eu já tenho esse novo objeto
aqui que é o nome do nosso modelo que é
o estatidados RF modo Eu sempre tive GNV
por exemplo mas suave se eu quiser vamos
de sonso porque eu tô querendo que eu
peguei esse modelo de algum outro
sentido de dados eu quero fazer
avaliação como que eu faço a carga desse
modelo dentro do é fácil inicializa o
próximo novamente carrego h2ovos E aí a
gente vai chamar essa essa função aqui
no outro modo a gente vai passar o mesmo
caminho do objeto Então a gente vai
passar o caminho no meu caso meu caminho
é esse esse cara aqui a aqui é claro que
o documento que chama está te dado no
meu forte/o nome do meu objeto aqui
então esse é o meu objetivo também que
não modelinhos
ó e vou fazer a carga dele dentro desse
sempre de modo aqui então no momento
roda Esse comando do lodo modo ele já se
arrumou já tá instanciado aqui na minha
memória esse server no modo se eu quiser
fazer uma edição com esse modelo que foi
salvo por exemplo vou chamar o meu o meu
lábio do produto não corre vou ter que
passar o objeto que vai ser o serva de
modo que é o modelo que acabei de fazer
a carga e os mil Beira que são que aqui
no meu caso é que eu tô passando somente
à base de teste só para conveniência tá
mas aqui pode ser qualquer outro tipo de
dado então se eu rodar
e esses comandos aqui no meu moda por
exemplo eu mandei esse cara e Sião se
Posso rodar tanto frente Quanto eu posso
dar o ele direto aqui no próprio estúdio
eu já tenho já o resultado do meu por de
tarde todo toda minha base de teste aqui
então deixa eu colocar aqui no comecinho
de suco Vamos lá então eu perder que tá
aqui então ele tá dando uma classe se
for a classe somente né tá dando não
deixou não deixou de foi assim
sucessivamente ou também as
probabilidades e a gente quiser para
caramba os registros também tá bom mas
só a viu você falou no primeira aula
sobre sobre a parte de sinalização para
Mogi hoje para quem quiser embutir isso
dentro de aplicações Java ou escala onde
faz isso mesma coisa então a gente vai
chamar essa
e se essa função aqui download Mogi não
pode tem que passar somente o modelo que
a gente vai se realizar tá o caminho que
nesse caso que tá com morte fato pé e
ele vai gerar o o o ponto usar também
então seu isso a gente rodar aqui deixa
não cria novamente se eu vou dar uma ele
é se menos um aqui esses são os objetos
que eu tenho na minha na minha pastinha
agora tá bom mas se rodar esse download
Mogi ele vai fazer ele vai fazer a ser
realizações Então se a gente vai pegar
esse modelo da memória vai transformar
um objeto e salvarem diz que tá esse eu
vou dar aqui novamente vou dar um Clear
LS - 1 e aqui eu já tenho o meu h2oh
defenderei moda. Já e também eu tenho
Zip então com esses dois arquivos aqui é
só passar para o seu desenvolvedor de
água a escala que a que essa esse
desenvolvedor essa desenvolvedora já
consegue embutir esse esse algoritmo em
produção também tá bom isso a gente
quiser fazer aí
o modelo novamente Tá eu vou passar só o
caminho aqui do ponto Jardim então
preciso falar pessoalmente passa-se
ponto de ar então o desse peixe aqui
vocês saberem que esse ponto já então é
todo o caminho que eu tinha passado aqui
fora está te dado sem feature a ponto já
então se eu colocar aqui o meu caminho
tá a andar Force aqui RF Model sempre
tio Denir. Gênero modo generator nesse
caso aqui fica pronto já tá bom vou
fazer um Import desse modelo importa o
modelo por modelo hoje nesse caso que eu
tô usando aqui e se eu quiser fazer uma
predição né usando aqui o perder que eu
vou chamar esse importa o modo que eu já
voltei aqui não importa o Joaquim vou
chamar importa moram novo conjunto de
dados e um bordão a predição e já vou
salvar ele inteira forma também tá E aí
esse modo por dentro importa fazendo as
predições aqui com o modelo que eu
acabei de importado. Mojo tá então aqui
tudo transparente tudo a ser nenhum tipo
de cachorro careta
Ah tá bom então aqui no shopping
Acredite quem já rodou gente vai ter a
aqui os casos de não ter fundo onde for
the full e as probabilidades também a
certo pessoal então é isso nesse vídeo
agora a gente falou um pouquinho da
parte de treinamento aqui de alguma
sítios da parte de Rondon Force Tá parte
de classificação a toda a parte de em
relação flor também que a gente tem uma
olhadinha aqui a parte e todos os
gráficos podem ser exportados e até
mesmo a parte de várias de importância
de variáveis então a e todos os jovens
eles são striking dentro aqui do posto
não é tanto é que o experimento anterior
que eu tinha feito aqui na Gêmea ele tá
aqui no no registro aqui do próprio
plaster tá em todos eles são auditáveis
né pode entrar em qualquer e qualquer
parâmetro pode ser digamos assim revista
Tá bom então é isso pelo vídeo de hoje o
pessoal então até a próxima novamente
deixa o joinha aqui no vídeo bastante
importante em frente a colocar esse cor
e relacionais aqui no algoritmo do
YouTube também e se você não é inscrito
no canal se inscreve no canal também tá
bom é isso aí valeu e até o próximo
vídeo
E aí