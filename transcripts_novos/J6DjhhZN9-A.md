# Lesson 3 - H2O Introduction to Data Manipulation (First Model) - Prof. Flávio Clésio

- **URL:** https://www.youtube.com/watch?v=J6DjhhZN9-A
- **ID:** J6DjhhZN9-A

## Transcrição

e fala pessoal do canais 7 dados tudo
bem meu nome é flávio clésio eu vou
falar um pouquinho para vocês hoje sobre
a parte de manipulação de dados dentro
h2óó algumas funções nativas nos quais o
h2l consegue fazer uma uma interface
legal com r antes de mais nada gostaria
de pedir para quem não é inscrito no
canal se inscrever aqui no canal sempre
tem controle de qualidade dele é sai se
masturbando estatística avançada a
visualização de dados e já deixe joinha
no vídeo também que o feedback de vocês
é muito importante a então dando
continuidade do que a gente falou da
última vez então esse aqui é o nosso
repositório beterraba então esses se
todos os códigos da nossa playlist aqui
vão consultar saldos aqui nessa nessa
url para quem é usuário do kit e quiser
ter o código somente da o clone aqui no
repositório ou se você quiser somente
fazer o download para sua máquina local
só clicar aqui em download zip esses
esses códigos não tá montar aí na
disponível na sua máquina o meu caso
aqui
e eu já fiz o download desses dados na
minha máquina local eu vou abrir aqui
hoje a gente vai falar de abelha
manipulation tá certo eu vou abrir esse
script então antes de mais nada eu vou
só verificar né se o andador ele está
instalado não se ele não tiver vai e vai
fazer a instalação para mim e vai a
fazer a carga aí da da live aí vai fazer
o load da biblioteca então está com galo
isso aqui a gente vai estabelecer uma
semente randômica certo só para a gente
precisar fazer treino de modelo alguma
coisa do tipo a gente vai usar esse cid
para ter a mesma garantia de
reprodutibilidade então vocês podem ter
o mesmo resultado que o que eu estiver
tendo aqui na minha apresentação lá na
máquina de vocês aí partida agora parte
do próprio h2zone então tudo começou
mandado só com a gente tem precisa
instanciar o nosso costura né que a
gente falou no primeiro na primeira aula
o cluster ele pode ser tanto stand alone
e aqui o que você vai ser a minha
máquina local há quanto pode ser também
é um conjunto de várias máquinas né
então vamos dá uma olhadinha aqui nesse
método init né então ele fala que olha o
esse mestre ninja que ele inicializa o
conecta dentro de uma instância do h2 lá
dentro de um cluster do h 2 ohms e esse
é o comando aqui esse vai ser o
principal comando que a gente vai usar
antes de qualquer tipo de experimento a
ou de qualquer tipo de manipulação de
dados dentro horários a gente precisa
acessar o posto e depois fazer a
manipulação de dados não a gente não
consegue por exemplo fazer tudo no l
depois passar por h2oh é o ideal que a
gente estuda o que você faz operações
todas dentro do h2 óculos porque o da
dois ó ele vai fazer todo o
gerenciamento de memória para gente
nesse nosso caso aqui nessa nossa
primeira
e a aula aqui eu vou somente inicializar
o nosso cluster com esse n traz que é o
número de cpus número de corsa na
máquina que vai estar disponível com
menos um ter e os atores então no meu
caso aqui eu tô eu tenho 12
processadores na disponíveis então eu
vou dar menos um aqui ele vai usar todos
os processadores disponíveis então então
deixa executar o comando e aqui ele fala
que inicializou então o tempo que o meu
clã será que ele tá ele tá em pé faz
mais ou menos 15 minutos fala a região
que eu tô aqui o nome do cluster o
volume de memória que o closure vai
trabalhar isso aqui são paramos de pouso
e aquele fala que olha então é tem 12
cores disponíveis e os 12 cores
disponíveis de olhar nos olhos vai
trabalhar com todos os cortes a que
estão disponíveis então essa é uma das
principais diferenças é por exemplo do
rna ativo no qual é você
a escolher quantos volume de cpus o
volume de memória no qual vocês vão
trabalhar e sempre trabalha com o máximo
possível esse é um conceito que chama de
igor comp urina é uma a computação na
digamos assim que faz o uso a massa a
marca a maximização do uso de recursos
da no qual aquele escritos aquela
aplicação está sendo processado a e aqui
no alisante consegue controlar isso né e
a ele falar que era a versão do henrique
que eu estou usando e aqui duas
informações principais que é a porta dp
que eu estou usando e o ip e ip que eu
tô usando para colete dito nesse caso
aqui eu tô em local moço eu tô em cinco
na porta 5 4 3 2 1 e que eu tô falando
isso uma um dos principais vantagens do
h2oh é que toda a parte de monitoramento
de cluster e acompanhamento dos jogos
ela pode ser feita através de uma
interface ao chamada de flor e a gente
vai acessar esse flor aqui então deixou
e fechar aqui essas janelas que não
importante agora então a gente tá aqui
local roxo que é uma endereço de ip tá e
hoje tá porta 5432 um ele vai trazer
aqui essa essa interface do h 2 o qual
eu tenho esse flor aqui a gente pode
falar disso uma outra aula mas
basicamente flor é como a gente pode
criar modelos de mach lane usando
praticamente sem código usando somente
uma interface e todo metido browser né
então se eu abri exemplo esses exemplos
aqui do flor vai ter aqui para mim a por
exemplo gbm eu vou fazer hoje do
notebook ele vai ter que como fazer a
carga dos dados ao parcelamento dos
dados treinamento do modelo isso não é o
nosso objetivo aqui hoje o que a gente
vai usar nesse curso aqui
majoritariamente vai ser a parte de
idiotas que como eu falei na primeira
aula todo toda toda vez que a gente
manda o comando é para o aparelhinho de
computação do h2 a realizar a pontuação
ele transforma em
e esse jovem esse jovem vai ter algumas
estatísticas vai ter algumas informações
de processamento comunidades para ele
vai acontecer status né que a gente pode
até dá uma olhada aqui agora que vai
trazer por exemplo há informações se os
tentar operacional desse caso que tá
operacional tá verdinho aqui a porque eu
tô numa máquina single-node mas imagine
aqui se eu tivesse uma chance com ela lá
30 máquinas por exemplo dez máquinas
cinco máquinas de uma das máquinas não
tivesse ok esse estado seria informado
aqui e aqui a gente tem algumas
informações por exemplo a do volume
máximo aí de memória que tá disponível
largura de banda que está sendo
utilizado na rede então lembrando de
novo né que o h2 ou se ele tiver
naquelas tempo várias máquinas ele vai
usar alguns recursos de rede e tem como
monitorar esses recursos aqui a para
saber até mesmo como que tá o andamento
do treino quanto tempo de falta e por aí
vai tá vamos voltar de novo para o nosso
a studio
bom então e chave aqui com nosso curso
está inicializado e uma alguma coisa
legal dá dois ok assim como o r nativo
toda todo o método ele tem ele ele tem
toda a documentação então nesse caso
aqui eu tô chamando esse esse método de
lm coloca um ponto de interrogação como
que é o a forma padrão esse doente
trabalhar com isso que aqui ele fala
algumas informações né então aqui é o
modelo de gnl que a gente tem hoje nosso
a nossa nossa se utiliza nossa nossa
variável dependente e alguns parados a
gente vai ver se paramos mais para
frente então mas isso aqui é uma coisa
legal que toda vez que a gente quiser
ver alguma informação sobre algum método
específico do h2ol a gente é só colocar
esse ponto de interrogação e eu rodar e
ele vai retornar aqui para gente aqui a
as informações do mestre a documentação
e o significado de cada um dos
parâmetros pode ser de modelo pode ser
de manipulação de dados por aí vai
e o nosso caso aqui eu vou fazer a carga
de uns dados aqui né a gente vai falar
um pouco mais pra frente a que é do
banco de dados que eu chamei de leilão
brothers né irmãos leigos digamos assim
no qual é o csv está esse se vê está
acessível para qualquer pessoa na
internet então é um teste padrão aqui
delimitado por vírgula que eu tenho uma
de algumas informações socioeconômicas
aqui volume de pagamentos e uma variável
de ficou eu não vou explicar o que
significa cada uma dessas variáveis
agora e só ficar por uma outra aula tá
mas aqui o ponto é só eu vou carregar
essa url nesse objeto e aqui eu vou
começar aqui começa a ficar interessante
a parte olhar nos olhos todo o objeto do
do h2oh é como eu falei na primeira aula
da arquitetura ele é um objeto chamada
h2off frame na índia chamada de frame +
h 2 o creme que é um tipo de dados
o jogador só esse tipo de dados
específico diferentemente de um csv por
exemplo de um banco de dados que tem
todos os dados dentro de um de um de uma
só máquina ou de um só arquivo o h2oh e
como eu já tinha falado no na parte
arquitetura então se você precisa essa
parte e recomendo que você vá no
primeiro vídeo dessa playlist e assista
esse vídeo para entender um pouco mais
como funciona debaixo do capô a ideia
não é explicar isso
é mas aqui é todo todo todo todo tremido
h2oe vai vai ter seis deixam chamada
ponto rex e aqui nesse caso né a gente
vai chamar esse método spotify então
vocês quiser ver as informações assim
como a gente fez viu apparuit a para o
método init a gente pode colocar um
ponto de interrogação na frente e vai
documentação então esse import farol é
um método que ele tem algumas
informações que importa arquivos dentro
do cluster do h2 ah tá então e aqui uma
coisa importante né aqui é um detalhe
que o h2oh ele tem um módulo de fazer o
parse de fazer essa essa tradução de
tipagem de forma automático certo então
essa coisa que a cientistas de dados aí
tem que estar com isso na cabeça que a
tem que fazer uma checagem dos dados
depois com a gasóleo e faz esse
parcelamento certo para o nosso caso
aqui a gente faz filmar esse objeto
spotify no código de precisa passar a do
o primeiro é o pé a gente vai passar o
nosso rl e a gente vai passar o nosso
adjetivo fremd né que vai ser o
jogadores à frente que a gente vai te
chamar aqui também de lembrar brothers
aponto rex então se a gente for daí a
gente tem o nosso o nosso e tá
carregando aqui agora já tem o nosso o
nosso frame racks a devidamente
carregado e sentiu dessa função nativa
do enem por exemplo summer ele já vai
trazer aqui para gente deixa eu só
diminuir aqui importa mais votação é a
mesma finalização é que a gente teria
por exemplo se eu tivesse passando um
objeto do rna então essa é uma função
nativa do é que a gente tá passando no
objeto vagar dois ó então aqui fica
muito claro um ponto que eu tinha
discutido anteriormente que
oi uedia somente um interpretador que
vai passar uma requisição para a gente
comprar o seu navegador só que vai fazer
tudo trabalho pesado e de novo galera
para saber um pouco mais sobre
arquitetura recomendo que vocês vão na
primeira aula dessa playlist deu uma
olhada na parte da prefeitura que é bem
interessante a ideia que é mais brincar
um pouco mais com o com esses objetos
outro outra a outra função né que a
gente pode usar por exemplo essa função
de histograma na que a gente pode ver o
que ela faz aqui então o sente chamar
h2au polish nossa senhora vai calculam
histograma que você precisa passar
alguns parâmetros aqui break spot por aí
vai tá o nosso caso aqui a gente vai
rodar alguns de olhar nos cantinhos aqui
pela idade e aí a gente consegue ter
tanto o descritivo aqui dos coaches né
não nosso console quanto o gráfico aqui
então a gente tem uma a gente pode ver
que até mesmo funções nativas do r a
gente pode
o carro dar em cima de objetos de h2oh e
algumas outras características por
exemplo então a gente vai rodar um grupo
bairro então nesse caso aqui gente pode
ver o que se vai vai executar de forma
performa agro passo um agrupamento
semelhante ao de doderlein então nesse
caso aqui a gente vai passar os dados o
nosso ponta da rex e a variável que a
gente vai fazer o grupo vai estar nesse
caso a gente vai dar um caught vai
trazer para essa para essa variável ele
o queixo estates
oi e aí vocês quiser agrupalto os dados
nossa base do lehman brothers por
educação então a gente vê que a 14 em
estância estão com education um como 0 a
10 mil comum e assim sucessivamente
então a gente consegue rodar até mesmo
alguns algumas formas específicas de de
agrupamento de dados manipulação de
dados nativos do h2oh é todas as
referências e todas as documentações
estão aqui no próprio escrito então
vocês podem usar e testar os dados de
vocês aí é que é muito mais a fazer uma
brincadeira e mostrar algumas algumas
características do h2oh então você
quiser fazer um treino treinamento bem a
bem simples aqui então aqui eu passo de
um modelo de mochila no nosso caso aqui
a gente vai passo vai treinar sobre um
algoritmo glm tá então a gente vai te
chamar esses plate frame que é um objeto
do h 2 o que ele vai fazer
a previsão de base de treinamento e
teste para nós na quente que que a gente
vai fazer que basicamente vai ser passar
o nosso aqui no na no argumento da vou
passar a nossa o nosso o nosso frame
h2óó o rádio vai ser aqui setenta por
cento para treinamento em trinta por
cento para o teste e o nosso cid
randômico aqui vai ser o 42 que a gente
já tinha esterilizado aqui no nosso
começo do script então vamos rodar vou
dividir como criar esse objeto aqui
split guardar dois ovos e objeto split
ele vai ter a duas a duas argumentos não
vai ser tá dividindo duas em duas partes
a parte 1 vai ser a parte de treinamento
esse objeto frente a parte 2 vai ter a
nossa parte de teste site então aqui
basicamente como se fosse um tivesse
usando o nosso por exemplo tem outras
tantas clipe do
e a por exemplo do sector nesse caso
aqui a gente tem isso nativo do próprio
h2ovos a nossa variável dependente aqui
vai ser de pouco né então vai ser a
probabilidade do cliente a entrar na
estação de de fogo não eu não vou
explicar os lados aqui agora e só ficar
para a próxima aula e as nossas
variáveis a independência então aqui vai
ter saldo vai ter o gênero da pessoa ao
grau de escolaridade e algumas outras
variadas então deixa que eu vou colocar
dentro desse objeto ache só deixou de me
deu um pouquinho aqui então carreguei o
meu x meu isso então se eu vou dar o y
téo de fogo e o meu x vão ser essas
variáveis independentes e aqui eu vou
trazer o meu modelo do glm então se eu
quiser opa tudo errado se quiser saber
os parâmetros do glm só vem aqui colocar
um ponto de negócio do método ele
as informações nesse caso aqui o treino
spring frame o chamar somente a parte os
setenta por cento dos dados que é
chamado aqui de trem o x tem aqui aqui
para gente vai ser as nossas as nossas
variáveis independentes e o y que vai
ser nossa variável dependente no nosso
caso é de fogo a como eu tô fazendo uma
predição de 01 então a família aqui
desse desse modelo vai ser binomial né
tem algumas outras a opções aqui por
exemplo como o alto clipe detechta a ou
até mesmo gaussiana se formar uma
variável contínua e distribuição possam
se fossem gama e por aí vai tá a copo de
05 aqui só para aquela de for mesmo e os
ide é que a gente vai treinar esse
modelo vai ser o mesmo ssid que é o
nosso 42 que a gente tinha usado
anteriormente então e a gente vai
treinar esse modelo vai colocar dentro
desse objeto lá em um blog os pontos de
lm
o modelo aqui tá treinando e agora a
gente vai voltar aqui no flor a gente
vendo aqui no flor deixa eu tô dizendo
que colocar aqui local rostos em 4 3 2 1
não dá uma olhadinha no flor aqui sem te
ver aqui no admin ele vai trazer um top
e olha que interessante ele tem aqui
duas cargas de dados então seja tá
carregando aqui no nosso arquivo ponto
rex de choco que aumentar para vocês e
ele tem aqui para gente por exemplo os
cortes que a gente tinha realizado a
rodada se correntes e a parte do nosso
treinamento de lm
bom então funciona demorou dois segundos
o palco faltam 10 segundos porque ele já
está sendo executado estados está que
você toma e já tá tudo executado então
se a gente quiser ver aqui e o modelo no
próprio frozen explica aqui no viu a
gente consegue ver por exemplo a moro
para mim ir se por exemplo todos os
paramos que nós escolheram escolhemos
esse caso vai ser 42 e algumas
informações por exemplo aqui do número
de interações o score então quê que
indica para a gente convergência do
modelo e a curva roc do modelo também
nesse caso que o a área abaixo da curva
tá de 0.72 e algumas informações
interessantes aqui dos nossos
coeficientes da então os outros
coeficientes as magnitudes padronizados
os coeficientes aqui dedicam aí a de uma
certa maneira quais são os os
coeficientes que são mais importantes
para o resultado final há algumas
informações aqui de ganho líquido do
modelo que a
e aqui agora e algumas informações por
exemplo de altitude do modelo né então o
rms a área abaixo da curva o coeficiente
de determinação a perna do modelo que
ele sente de higiene por aí vai no
coeficiente gini essas métricas aqui
seriam mais se fosse um monte de
classificação que é o nosso caso aqui tá
a
oh e vamos voltar de novo para o nosso
código né e aqui uma e aqui se ele
quiser vir por exemplo informação no
modelo a gente pode usar uma função
nativa do é então summer né então aqui
no summer a gente já consegue por
exemplo te a as interações com modelo
todas as informações que a gente viu no
flor a gente consegue ter essas mesmas
informações aqui no samba então ele fala
a por exemplo a família do modelo ah ele
tá usando aqui o elastic net como eu
usei o alfa de 05 ele entende que é um
que é o modelo acho que net não laço né
o ide a ele traz aqui algumas
informações já os cenotes que a gente tá
fazendo classificação aos e a gente vai
mas nós estivéssemos fazendo a
a regressão ele tá itália para gente
aqui por exemplo ao coeficiente de
determinação tempo e até mesmo a prova
pronto rms e a matriz de confusão para o
nosso caso aqui já tá calculada e
algumas métricas interessantes de da
performance do modelo né então aí traz
aqui para por exemplo f1 f2 a querer-se
mais precisam de acordo com qual é com
e a com a classe do modelo
especificidade e algumas informações do
score do modelo né como que foi a
convergência ea o número de interações e
o ea duração é de cada uma das
interações a e aqui ó os meus
informações do quem chama de várias bom
importa se na importância de variáveis
para ele traz aqui para gente na mesma
forma que a gente viu lá no flor a gente
tá vendo aqui né o pênis ir e assentos
variáveis sucessivamente a flávia mas
isso a gente quiser fazer uma predição
desse modelo né fácil só a gente chamar
esse essa essa essa função h2oh parede
que a gente vai ver aqui só colocar o
ponto de interrogação executar e ela
fala assim olha então é para executar
uma previsão do modelo do h2oh então que
eu tenho que passar aqui é um objeto e o
beira nesse caso aqui a gente tá se como
usando como objeto o nosso modelo glm né
que o nosso modelo lehman brothers
e os dados aqui a gente vai passando
nossos dados de teste gente vai
armazenar só tipo ti nessa nesse nesse
nesse objeto chamado prático então ele
já rodou aqui a pressão a gente vir aqui
nos jobs
e ele traz aqui a nossa a nossa
transformação aqui também não é do nosso
jérémy moda para se dizer tá então tá
trazendo aqui a 8904 colunas e esse
verdadeira forma e tem três colunas a
gente pode tanto fazer o download desses
dados como só clicando aqui nesse nessa
função download e a abrir csv nesse caso
aqui deixa eu abrir o nosso csv aqui no
sublime para ficar transparente para
vocês então no nosso caso do meu modelo
aqui tá como transformation para trás
aqui ao predict então a classe 01 e a
probabilidade né então probabilidade
está na classe 0 e na probabilidade
antanáclase um lá então aqui tudo
totalmente transparente ele pode fazer
isso pelo flu ou a gente pode fazer isso
também pelo pelo próprio r nesse caso a
gente pode ver alguns sumária a
e dá um objeto depressão nos casos tô
pegando a sua mente a variável p1 nada
porosidade da primeira classe ea que a
gente pode executar as mesmas coisas que
nós vimos no subway a gente pode filmar
esses objetos como por exemplo que o fio
gmail porque só vai trazer a matriz de
confusão para gente a a importância das
variáveis da que vai fazer um plot aqui
para gente já e as informações de curva
roc usando esse h2oh a performance que
ele vai fazer um cloth só também o mesmo
pode que a gente viu lá no flor a gente
consegue ver também aqui no h2zone a
única coisa que precisa passar no
performance é o objeto que nosso caso
vai ser o glm e a nossa base de teste
o e automaticamente o esse objeto perth
vai ter as características de uma curva
ló que a gente consegue já fazer o fazer
o geração do do gráfico né a outra sente
usar esse std 4 lote a gente consegue
ver os coeficientes padronizados de novo
da mesma forma que a gente viu no flow
ver aqui na própria web studio e a gente
quiser ver a performance do modelo né de
uma maneira geral a gente pode rodar a o
h2 uma performance novamente e executar
esse dono desse projeto surf ele vai
trazer a mesma coisa como se a gente
tivesse usando o summer também a o
volume de perda do modelo então quanto
que qual que é qual que é o volume final
de quanto que o modelo tem de perda
então isso aqui é uma meta que indica a
o grau de convergência do modelo então
quanto menor melhor tá e se ele quiser
ver as informações a da área
e nesse caso pratique 0.82 tá então é
isso pessoal foi bastante corrido muito
informação que eu sugiro para vocês pega
o script tenta executar a passo a passo
tá com dúvida em relação ao que cada
função faz os parâmetros ponto de
interrogação no método executa e dá uma
olhada na documentação é a ideia nosso
vídeo aqui é muito mais fazer um outro e
dá uma olhada tanto no código quanto no
flor e entender um pouco como funciona
uma da dois ovos a por baixo dos panos
depois vai tá na próxima na próxima aula
nossa e já falar um pouquinho da carne
de dados um pouquinho do nosso dele
frame e depois dessa dessa aula a gente
vai começar pegando fogo na parte de
algoritmo está certo então de novo se
inscreve no canal se você não é inscrito
e deixa o joinha no vídeo também tá bom
muito obrigado até o próximo vídeo