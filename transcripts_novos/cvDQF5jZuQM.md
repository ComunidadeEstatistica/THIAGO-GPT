# Aula 08 - Xgboost Classificação - Prof. Flávio Clésio

- **URL:** https://www.youtube.com/watch?v=cvDQF5jZuQM
- **ID:** cvDQF5jZuQM

## Transcrição

Com certeza tá aqui é o Flávio traz de
novo e hoje a gente vai falar um
pouquinho de Mach Lane a no R usando o
h2oh certo então primeira coisa gostaria
de pedir para vocês para quem não é
inscrito no canal se inscreva no canal
conteúdo de altíssima qualidade ciência
de dados a estatística avançada E por aí
vai a e também a o todos os códigos essa
série que a gente está falando de uma
celular no H2 olhos estão aqui nesse
repositório da mente exame chamado está
que dados traço h2oh certo se você é
usuário do kit é só fazer o forte desse
repositório ou se você não usuário do
guichê que apenas a fazendo download do
desses códigos só clicar aqui nesse
ícone download se botãozinho verde e
escolher essa opção download Easy acerta
Então bora para o r-studio novamente
Então deixa eu aqui com a estúdio Tom já
fiz o forte eu vou entrar essa pastinha
número 06 aqui e eu vou deixar só apagar
esses modelos antigos de Elite
E ai e abrir o a questão da gente
bushing para classificação tá tanto os
códigos de classificação quanto à
regressão estão dentro do a do
repositório
bom então a primeira coisa que a gente
vai fazer é fazer a carga do fazer o
molde da biblioteca da h2oh e travando
essa semente randômica nosso cide a
número 42 para prato garantir a que os
meus resultados que eu tenho aqui da
minha minha máquina vocês tenham na
máquina de vocês também tá bom então é
logo em seguida deixar o saque Unity
para conectar no nosso no nosso costume
do lugar dois ovos então a gente já
rodei aqui dessa falando aqui meu
consertar tá conectado a 6 dias ao nome
do clã inteiro o total de memória que
vai ser utilizado e volto e vai usar
todos os 12 cordas para saber o mais um
pouquinho sobre o quê que cê nit O que é
o câncer tudo mais é um sugiro que vocês
vão a primeira aula a que fala sobre
sobre arquitetura advogado do Sol e
sobre o que que é o Closure h2oh E por
aí vai tá o vídeo aqui hoje é mais para
falar sobre as expõe gradient boosting
the
o alto então a gente vai continuar com a
nossa base do lehman brothers aqui tá
que foi a primeira do que tá lá no nosso
vídeo de dentro a Lurdes tá então deixa
até abrir aqui para ficar transparente
para todo mundo aqui nessa tem um rld1
de uma base de dados que estão na mente
Vamos então a variável que a gente vai
tentar aprender aqui você vai lá chamado
de fou tava sem Nossa variável
independente e essas outras variáveis
aqui uns assuntos variáveis
independentes
bom então já fiz a carga do nosso do
nosso h2oh frame aqui nesse ponto Rex
esse eu vou dar o Summer que é uma
função de fogo do próprio R ele traz
aqui todas as estatísticas descritivas
aqui básicas na mediana média terceiro
quartil máximo e mínimo para todas as
variáveis a eu vou a gente vai mudar
aqui a variável de for pra categórica e
também avaliava a variável de educação e
de casamento aqui na emerj a lixo rodar
um samba de novo só para checar se ele
se fez a conversão Então nossa variável
de fogo aqui já tá
e como binária aí então tá nossa
variável education quanto maior já aqui
estão como como categórico porque a
gente usou aqui se aspecto então a
novamente a gente vai a gente vai pegar
o nosso frame do h2oh só daqui a gente
vai pegar o nosso frame do h2oh vai
transformar em um objeto chamado Sweet
friend
e a outra que isso eu te perguntar
executado no qual gente passa nossa base
nós h2oh frame a aqui a gente vai passar
dez porcento a parte de teste e noventa
porcento a parte de treinamento e os ide
vai ser o sigilo do nome que a gente
colocou lá em cima naturalmente aqui é o
número 42 tá aí é quem chama a função do
sub frame ele gera esse objeto do tipo
Split no qual esse objeto split tem dois
furos tal foi número 1 número 2 ou fugir
número um vai ser a base de treinamento
e vai conter os momentos os 90 porcento
os dados e o fogo de dois é a parte de
teste que a gente já estabeleceu a
anteriormente a como ele tinha falado
então daqui nossa base nesse lá em um
Brothers a o nosso a gente vai chamar de
y é a coluna Nossa variável dependente
tá que alguém gente vai tentar prever se
vai entrar numa situação de calote ou
não
eu ia baixo a gente vai colocar as
nossas variáveis Independentes aqui né
então a educação informações de
pagamento por aí vai e a pessoa casada
não o limite de saldo e por aí E por aí
vai tá então a gente tem uma Sushi nosso
y e agora a gente vai entrar para
acredito no nosso função da questão da
gente Bush então a gente saber tudo que
qualquer função no h2oh faz é só de
colocar? H2oh. E o nome da função nesse
caso aqui a gente tá chamando o mundo a
gente boot ele tem algumas opções aqui
que traz a gente pode ver aqui no
próprio rapper a do do rstudio tá então
vou passar aqui
em algumas opções A então primeira coisa
então primeira coisa que a gente tem
aqui a gente tem tanto as colunas nossas
da nossa variável as variáveis
Independentes né que aqui tá com um x os
eu vou dar um X aqui vai aparecer todas
as variáveis a
a independência e o Wilson que a nossa
variável dependente instante vai a
colocar que vai estabelecer aqui nessa
nessa nesse valor chamado estão aqui
stop métrica é a meta que a gente vai
usar para fazer o controle de da perda
dos modelos né então geralmente é por de
Fortaleza ele vai trabalhar na
implementação da questão da gente Boost
Nessa versão que eu tô trabalhando aqui
agora a com um lado nós né mas ao invés
de ter uma métrica por exemplo como
lógico que ela que ela trata mais ou
menos do peso do a penalização dos pesos
ao longo do treinamento de um dos assim
e a cola 2l deixa também trabalhar com a
comércio de parada então a gente pode
colocar aqui por exemplo uma métrica se
maximizada ou minimizada no caso aqui eu
tô usando o a área abaixo da curva né
Uai você que é para maximizar sua
métrica né então a mais por acaso não
tivesse utilizando outras métricas de
mim para regressão por exemplo como MS
eu como uma RMS por exemplo aí seria a a
essa função de perceber para mim isso é
esse valor então o treinamento correria
é até até um até os rounds que essa
métrica que a gente colocou aqui como
estoque métrica tivesse no seu valor
mínimo tá me deixa eu ver algumas
algumas outras informações aqui tá essa
uma uma opção interessante essa
categórica uncle Jack O que é a que o
h2oh ele ele por padrão na ele ele pensa
e como alto né de café de Coaching
categórico mais nada mais é do que o
galo isso ele faz ele ele ver a
distribuição da variável ele tem isso é
totalmente
é baseado algumas heurísticas do h2hop
na qual ele trata as variáveis as
variáveis categóricas e e determina-se
por exemplo se qual que vai ser a
estratégia de tratar essas variáveis
Então deixa eu colocar aqui cadê
categórico em coaching coaching não dá
uma olhada aqui no rapper isso aqui
então tem essas opções então tem desde
opções para binário e aqui uma uma uma
uma informação importante que o binário
Ele só faz quebras é até até uma
variável que tem no máximo trinta e dois
valores diferentes Então se passou de 32
valores diferentes analisam não consegue
trabalhar com binário por exemplo Então
a gente tem que eu tenho uma uma
variável categórica que tem três letras
a b e c como valores né então a vai ter
eu vou ter mais uma coluna chamada a
quem vai ter o valor 01 coluna B que vai
ter um uma valores era um e uma coluna
601
o pai disse isso dessa coluna por
exemplo de letra eu tiver combinações de
letras que serão 32 entender os valores
né aí o H2 ou não consegue fazer a essa
quebra E aí a melhor opção é usar essa
essa one-hot a internou aqui a minha mãe
já tem algumas outras também mais essas
duas são as mais suas mais utilizadas
aqui o número de árvores é o número de
árvores que a última gradient boosting
vai vai criar né ah Lembrando que é um
dos princípios fundamentais do sistema
da gente Bush em aquele une ele ele une
o conceito de Randy forsey a de
Gradiente por cima garganta e
concentre-se nesse caso aqui gente tá
usando
e é de uma forma com que é a tem alguma
primeiro com o algoritmo console
trabalhar com com dados esparsos isso a
primeira característica segundo a ele
consegue também trabalhar com o comício
em velhos aqui na com com valor só o
antes e o terceiro ele aplica um fator
de regularização muito grande nas
árvores conforme as músicas mais
complexas tá então a isso significa que
a gente pode colocar um volume de
árvores aqui a um pouco mais alta desde
que a gente controle Quem esse cara aqui
que é o Max Deco Então seja a gente pode
ter muitas árvores a porém ou forma a
gente vai aumentando o número de árvores
o ideal é que o profundidade dessas
armas não seja não sejam muito não seja
muito profundo né porque aí pode pode
causar o caso de overfeat Então nesse
caso aqui como é mais para efeitos e
demonstração e eu quero deixar ele
rodando um pouquinho aqui então vou
colocar nossas árvores o Max Depp a
profundidade das Árvores
e as árvores vão ter mais de sete níveis
a por exemplo acaba de me um pouco
colocava seis tá a me Rose aqui é o
número mínimo de de registros que eu
quero na folha a E por que que eu
coloquei explicitamente cinco aqui a
porque os Eu não eu não tenho muito dado
essa base que ela tem mais ou menos uns
30 mil registros e tem acho que segue de
300 300 e poucos então a no momento que
uma árvore lá tem até uma folha não
nossa terminal digamos assim eu quero
que domínio a esse novo terminal ele
tenha cinco ele tenha 5 registros senão
ele fica no ele fica no nível
imediatamente anterior a ti vão ter mais
registros vai pegar um pouco mais a
precisão mais não dá aqui a gente
elimina o risco de ter um overfitting tá
por causa desse desse número mínimo de
Boa tarde dígitos não folha o World Race
aqui vou colocar como 10.2 um pouquinho
alto também tá mas eu deixa o capa Punto
fica mais a como a gente tem bastante a
árvore aqui a 101 Tá OK mas conforme se
eu tivesse menos árvores por exemplo
seria legal colocar por exemplo 10.50.1
mais até que a gente tem bastante a
árvore não tem como fazer o
e o Palito em cada uma dessas dessas 900
até a gente vai colocar um lembrete alto
mesmo que não que não tem problema tá
essa opção aqui de cá Liberty módulo é
interessante que o h2l tem ele tem por
de fou à a featured fazer modelo de
classificação da mente né fazer a
calibração desses modelos né De acordo
aí com a distribuição das classes tá
nesse caso aqui eu não tenho uma Não não
quero fazer a calibração Então estou
colocando aqui como falso mas se
presente se a gente tivesse uma base a
vítima de roudaut né o a base totalmente
fora do conjunto de treinamento em que
usaria somente para fazer essa
calibração então de colocar esse Kale
Break Model falso e colocaria esse
calibration friend aqui em colocaria
celular calibration. Rex e que seriam
uma base de dados por exemplo que a
gente ah sei lá algum humano fiz
alocação entre e todos os casos
contribuintes
se você A então a gente colocaria tanto
essa opção aqui como outro né como o
verdadeiro e o calibration frame aqui
que saíram E aí Aqui tem que ser uma
base do próprio h2oh a calibration pouco
reto nesse calibration firme aqui mas
esse caso como eu não vou fazer a
calibração Então vou tirar essa essa
linha eu vou colocar com muito falso
porque não vou passar nada e se lambe
daqui é opção em relação ao
regularizador que a gente vai usar Então
nesse caso a gente tá usando o
regularizador a a laço né que é o que
usar um essa opção aqui do bec enche é
interessante porque o ainda natação do H
2 o a isso tanto dentro do Erre quanto
no Python ele leva em consideração e ele
procura a saber se tem poder fone é por
CPU então ele
e usando todos os meus processadores mas
se porventura eu tenho é por exemplo uma
uma GPU na minha máquina a me que é uma
placa gráfica que ajuda na acelerar
esses treinos principalmente com um alto
alta frequência computação então o h2l
tem essa opção de que se tiver se tiver
uma GPU ar disponível a duplas ter o
naquela máquina e aqui no meu caso o
rodando Stand Alone né então tô rodando
numa máquina só mas se porventura se
existe uma GPU no cluster o h2oh ele vai
usar essa
a nossa GPU para acelerar o treinamento
não que aumenta EA possibilidade de
modelos na dado que a computação vai ser
um pouco mais acelerado a e aqui a gente
tem a última enfrentam
esse é o nosso o nosso lehman Brothers.
Trem aqui quem está chamando quem quente
estabeleceu no começo aqui do escrito e
Vale deixa um frame que nesse caso só
porque senão de conveniência eu tô
usando a base de teste mas aqui também
pode ser uma base totalmente separada do
conjunto de treinamento e teste tá desde
que lógico seja um frame do próprio da
dois ovos e para saber o que que é o
frango jogadores jovens como ele vocês
vão para aula de arquitetura tá que acho
que a primeira o primeiro vídeo dessa
série que lá eu explico o que que é
ch2oh frame Quais são as vantagens e
desvantagens e o que que ele vem a Supre
no lugar da da implementação original do
do próprio é tá E os ide vai ser o nosso
cide a randômico aqui que a gente vai
usar para a garantia
e a reprodutibilidade desse desses
experimentos acerto a deixa eu ver se
tem mais alguma outra opção aqui tem
mais algumas outras opções mas
porventura eu vou deixar vou deixar
somente somente essas opções vou dar o
treinamento EA gente vai lá no flor para
monitorar esse treinamento então vou
deixar 900 árvores aqui de novo aliás
deixa o caminho árvores
é um de novo galera objetivo aqui não é
fazer nenhum tipo de infecções de Niro
New Fit Street não é nada é mais mostrar
implementação do H2 ó tá então não tô
falando um monte de modelagem tudo mais
e nem de como fazer faine Taine mais
discutir um pouco mais sobre as opções
jogado só a então eu vou rodar aqui
olhar o sono então já está processando
se eu quiser saber se ele tá no flor vou
abrir aqui o meu navegador no local
rosto 54321 que é o endereço do meu no
meu câncer ao ver aqui no caos testados
tá operacional a gente tá vendo Verde
aqui tá operacional e se eu quiser ver o
que tá sendo executado vem aqui no Jobs
ele vai trazer aqui o todos os jovens
que estão em execução agora tá então
deixa eu ver qual que é o nome do nosso
Job aqui tá rodando 27 por cento vamos
ver se consegui identificar esse cara no
flor ele provavelmente vai tá aqui com
status de urn ou pa achei aqui esse
ciúme da gente post modo então é que tá
em mim e aqui no próprio flor a gente
consegue acompanhar
E aí como que tá o andamento do
treinamento do modelo né então a gente
imagina aqui tá nossa tá dando aqui o
quantas vagas estão sendo construídas né
então 529 de 1000 a porcentagem o nome
do modelo Então se a gente quiser se a
gente quisesse colocar o nome do modelo
Ah e a gente conseguisse para a gente
fazer o tracking a visualizar o nome
desse modelo aqui no Flor da sua gente
vir aqui no modelo e colocasse na minha
opção Model Model Heidi colocar o nome
aqui por exemplo aí te buscar Boost está
pintados por exemplo mas como eu não
coloquei ele para colocar nesse nome
randômico aqui e aquele a gente consegue
monitorar o Diogo né E como ele tá
rodando tá se ele tivesse um clã ser
distribuído ele aqui ó
E aí a tem formando a gente aqui que
esse que esse de obra está sendo
executada de forma distribuída Então já
tá quase terminando e a qualquer dia do
forro de novo né mais a gente tem uma
interface né no qual a gente consegue
ter todos os treinamentos então aqui a
foram todos os treinamentos
transformações que eu fiz das aulas
anteriores então a qualquer experimento
que eu queira a verificar aqui qual foi
o o h2oh frame que foi usado para
treinar os parâmetros modelo todos eles
vão estar aqui tá Então é isso garante
para gente é uma maior transparência e o
e o maior a o maior registro dos
experimentos que a gente pode fazer tá
então terminou nosso Job aqui eu vim
aqui nesse no etnocêntrico nessa opção
viu
Oi e a primeira coisa que a gente pode
ver que eu moro amora para menos aqui
que elas são os param desse modelo no
qual ele já traz para por exemplo
algumas informações como algumas as
colunas que alguém orei como a gênero e
idade a a métrica de parado aqui nesse
caso forró você a distribuição
e não foi foi bem dele a que foi que foi
escolhida pelo próprio h2ovos mexer lá
no alto o número de árvores e por aí vai
então o que a gente tem toda a parte de
do experimento né inclusive com síndrome
a aqui no modo para mim ver se a gente
for pro a score History né então a gente
vê a em relação do Logo logo então ele
tem aqui de acordo com o número de
árvores a qual que foi a perda do modelo
na em relação à a função de pega então a
gente pode ver que depois da 24ª árvore
aqui a praticamente não teve mais nenhum
tipo de pelo então praticamente muito
amante de texto deve ter acontecido
alguma alguma situação de overfitting
aqui tá E aqui tem isso aí como a gente
pode ver não nem tinha visto o gráfico
antes mas a gente pode ver gráfico né
então aqui na vó se da base a de
treinamento né e
o interessante do flor que ele traz
tanto a parte os gráficos de treinamento
e os gráficos de teste dentro da mesma
interface tá usando aquele aquele Edson
Sá e aquela opção viu como ser por vocês
nos reunimos aqui ou se forem Que
história e aqui a recurso pode ver Muito
provavelmente o caso de o ver City a 97
por cento de probabilidade se onde são
overfitting aqui no canal pra você tá na
parte de treinamento aí se a gente for
ver aqui a parte de validação né que a
base que estava fora a do conjunto de
Treinamento a gente tem aqui há 75 por
cento né 74,75 por cento tá então o
próprio o próprio flor já traz todos os
gráficos que a gente pode que a gente
pode visualizar cada um dos dos
treinamentos né E também ele traz as
importância de cada uma das variáveis
nem tão e aquele já traz a gente chama
de Escher em porcos né então ao invés de
ter um
o cabalístico lá zero. 3,25 25 outro
número de baixo no na soma desses
números não tem uns cem porcento por
exemplo o próprio flor ele faz esse essa
ele faz esse skin de novo desses dessas
variáveis na entrada aqui a importância
delas Então as variáveis aqui de
pagamento do pagamento que foi feito a
é tudo o que foi feito no primeiro mês
do acho que aqui é o pagamento de
entrada próxima dica sua base e as
variáveis menos importantes aqui que são
education a educação e casamento também
tá então o horários hoje atrás deles
para gente e além de das métricas de
aquele traz a matriz de confusão tanto
por se juntado de Treinamento a quanto
de conta da parte de validação né teste
e quanto as informações aqui do Recall
também tá então a gente teve um e coque
de 57 Por exemplo quando obter quando a
e tenta virar variável que chama de de
pouco quando teve o calote então
situações que teve o calote o e qual a
que ficou ficou muito baixo Ah então
beleza vamos voltar de novo e que tem
umas outras métricas quanto como neste
treino por aí vai vamos voltar aqui para
o próprio estúdio e agora e todas essas
essas E aí a normalmente não coisa que
queria falar para vocês aqui os modelos
do h2oh todos e essas informações que a
gente viu no flow é todos eles estão
disponíveis a gente for da sua função é
Nativa do próprio RNA chamado Summer
sobre o modelo que a gente acabou de
treinar no nosso caso aqui é o modelo
anda score a x g x GBA GBA XV a e todas
as métricas a todas as informações do
treinamento a vão estar aqui dos métodos
de validação então aqui a gente consegue
a pegar por exemplo informações do
doações cor a
a especificidade o mcc a matriz de
confusão ao coeficiente de Gini por
exemplo se a gente quisesse se a gente
quisesse a buscar seu médico também e
algumas outras informações em relação do
do modelo em relação ao número de
árvores por exemplo tá a isso a gente
quiser fazer uma predição que a gente
tem que fazer só chamar o h 2 o ponto
preditivo corrente vai passar como o
nosso modelo como objeto e a nossa base
de teste né a alemã: teste como líder
aqui que vai ser os dados que vão ser
passados para o modelo tá dentro a gente
chama essa função e armazena dentro
desse prédio já recebo e já te mando pra
tu isso a gente rodar esse prédio aqui
somente ele traz aqui um meio que um
reto top top 6 aqui aí desses valores
então aqui a gente tem a variável
dicotômica nesse caso está trabalhando
né 01 então
e não entra em calote da entrou em
calote entrar calote Mas tente quiser
também a gente pode extrair as
porcentagens né dp0 Ipeúna e
probabilidades e a um número é a
probabilidade ser um também tá bom a tem
uma e todas as informações tanto de da
Matriz de confusão a importância das
variáveis é todas elas podem ser
extraídas usando esses objetos aqui
então olhar os órgãos genitais a por
exemplo sobre o sobre o modelo a
importância das variáveis também então
isso já tem a gente consegue até mesmo
ter um plot dentro aqui do próprio do
próprio estúdio e algumas informações em
relação à a curva roc por exemplo da
doença doença entre a verdadeiras
positivos e falso positivo está a Mas e
aí como que a gente coloca esse modelo
em produção né então o que eu vou fazer
aqui agora deixa está aqui em vários
então a isso aqui a deixou e aqui
terminal
em 306 AC cima da gente bucha tá então
se eu colocar por exemplo aqui eu tenho
esses dois aquivos que são os mesmos
dois aquivos critoriano aqui no meu no
meu A rstudio então só por questões de
conveniência eu vou criar aqui um
diretório tá o caminho do diretório lá
nesse caso eu tô chamando a sua
biblioteca aqui para ele pegar o
diretório raiz da onde que eu tô rodando
o próprio o atitude esse projeto
dinheiro aqui é uma constante né que vai
ser o caminho que eu tô usando a área
que tá o repositório do estatidados E
esse foi o pet aqui no final ele só vai
fazer a concatenação desse caminho tá
então deixa eu rodar tudo aqui que fica
mais fácil é isso eu forneci a arquivar
pé aqui eu vou rodar esse cara ele vai
trazer o caminho ele vai trazer o
caminho completo onde foi o outro que
vai ser exatamente seu colocar aqui o PW
dele ele vai trazer todo esse caminho
e a na minha máquina local aquilo só por
questões de conveniência eu fiz isso a
concatenação que aí pode ir para vocês
na máquina de você só substitui esse
caminho ou se vocês preferirem só pegar
o caminho completo onde vocês tiverem lá
para o diretório e colocarem diretamente
aqui nesse peça a aqui no nessa função
do servir moda que eu vou falar agora tá
então para salvar esse modelo como a
gente a ver nas aulas anteriores então
gente vai usar essa função servir modo
tá no qual deixar passar o objeto que
vai ser salvo né então vai ser o modelo
que a gente só vou lá em cima do cima da
gente Boost o caminho que vai estar como
esse aqui Aperta aqui que ela esse
caminhão que está aqui no console do a
dois homens e o forte como true é só
para ele a salvar o modelo in the
positive algum outro modelo na pasta ele
vai sobre a escrever e Vai forçar que
esse modelo mais atualizado aqui ele ele
fique salvo tá e aquele já como ele pode
vir aqui no próprio estúdio ele já
salvou para gente toques
em 12 set que o exatamente o horário que
eu tô aqui agora tá então ele já pegou
ele já salvou esse modelo aí se eu for
aqui no meu terminam por exemplo né
Assim menos um eu tenho já esse modelo
do Xperia gente busque ser realizado
também tá certo então beleza do Flávio
modelo das realizada então se eu quiser
testar para ver se esse modelo ele tá
funcionando não eu vou nesse modo eu
perto o objeto aqui que é o que é o
mesmo caminho que eu coloquei
anteriormente né do seis módulos só que
vai estar o nome do nosso modelo que foi
salvo aqui que é esse a segunda a gente
curte Model r o final 188 que é esse
caminho aqui mas de novo aqui no mundo
mas vocês podem passar um caminho direto
tá do da máquina de vocês usando o outro
modo e eu vou colocar eu vou fazer a
carga do modelos nessa nessa variável
que coloquei Como servir de moda Então
vai pegar vai fazer a carga nesse modelo
Se eu por exemplo quiser vou dar um
Summer aqui
o
o que Afonso e novamente uma função
Nativa do RS cima do meu servido moda
para chegar se chama modelar não a gente
consegue fazer aqui ele já traz todas as
variáveis todas as informações do
treinamento a gente tinha visto
anteriormente desde a matriz de confusão
o próprio ao cd74 1,65 por cento e por
aí vai tá certo tudo isso só usando o
outro modo nem se eu quiser fazer uma
predição o quem tipo tem que fazer aqui
é só usar o novamente nas objeto perdido
no qual a gente vai passar novamente
nossa base de teste como New Beira mas
só que no objeto aqui que seria o nosso
modelo a gente vai passar esse sem
demônio aqui que foi modelo que a gente
acabou de carregar tá E vai transformar
só para dar a forma que só falam questão
de inconveniência mesmo e vamos
armazenar tudo dentro desse modo eu
perdesse aqui tá então se eu entrar aqui
no próprio estúdio clicar no tempo
depois ele vai trazer aqui para mim a
coluna acredita que vai ser a pressão no
modelo tá e a probabilidade de ser
e da classe a zero ou da classe um bom e
novamente vocês tiverem trabalhando com
probabilidade Eu recomendo fortemente
que não use nessa maneira que eu tô
usando aqui agora mais usem as a Fiat
relativa a parte de calibração também
serve a e a gente quiser salvar se
realizar esse modelo né tanto para
arquivos a Mogi hoje né no qual a gente
consegue embutir esses modelos direto em
produção em plataformas que trabalham
com escala em Java a única vez que a
gente tem que fazer que é só chamar só
essa função chamada a download do bojo
no qual gente tem que passar o modelo
que a gente está fazendo sua realização
o caminho que nesse caso aqui é o nosso
as paterna que a gente declarou
anteriormente e aquele vai gerar o ponto
já para para nós também então salvei
aqui o modelo e aquele já gerou esses
dois esses dois a registros aqui Opa
deixa os eles
eu não tava virtude que tá como h2oh G
Nobel e tem um outro modelo que ele vai
estar com o nome a o mesmo nome do
modelo ser realizado anteriormente só
que como o ponto Zip então com esse até
falta aqui a única coisa que precisa ser
feita só fazer se entregar esse esses
dois arquivos a para os desenvolvedores
a escala e já leu do backend da sua
aplicação que esse modelo já vai estar
pronto para ser embutida dentro essas
plataformas tá isso a gente quiser
importar esse esses modelos né presente
do H2 então eu tô colocando só esse
peixe aqui para ele fazer a concatenação
do caminho do de onde está o dia Onde
está o modelo né Então deixa o seu Rodac
moda pegar já a peça então ele vai ter
sempre esse caminho teu que é porventura
o mesmo deixando aqui LS - 1
O que é o caminho no qual vai estar esse
esse cara que esse esse ponto Zip não
faz eu tô passando já isso no caso eu tô
pegando só o zíper aqui então pegando
ovo tá ele vai fazer esse caminho aqui é
o mesmo que eu determinei usando esse
módulo já tá Não precisa de novo fazer
essa conta concatenação aqui do jeito
que eu fiz vocês podem colocar o caminho
direto no modelo de vocês e aí eu vou
fazer se importa o bojo tá então a praça
vão modelo a gente usou função download
Mojo para fazer a carga de cima durante
a usar o importa o bojo no qual a gente
vai passar o caminho do nosso do nosso
nosso nosso já tá por causa que eu tô
usando tô usando os então é um molho e
aqui eu salvei ele como importa o modo e
novamente se eu quiser salvar o seu
chegasse essências aqui vão modelo esses
ipe eu roda a função Nativa do Summer do
do próprio É sobre o modelo né que eu
chamei importa e manda ele traz
as formações Táticas do modelo aqui
então tá trazendo o procurar você tá
trazendo a matriz de confusão e por aí
vai então a quem tiver na outra ponta e
isso pode ser tanto dinheiro de macho
mar Enquanto o outro sente desse dados
até mesmo time de plataformas que vai
embutir essas informações é alguns que
algumas algumas variações de testes na
de integração que me chama engenheiro de
software a pode considerar por exemplo
que o modelo ele só vai entrar em
produção se ele tiver a por exemplo
assim um auxílio acima de 80 porcento na
base de validação por exemplo então e aí
se não tiver esse modelo não entra em
promoção não é promovido para a produção
né Ah mas isso é um outro papa o palco
de sofre GNV é um papo de a integração
contínua e depois nós continua não é o
foco nosso vídeo aqui mais para a gente
o nosso foco nossa vida só mostrar como
salvar esse modelo aqui e como ser
alisar ele e deixar ele pronto para
produção também tá E tem que quisermos
há uma previsão de se importa de modo
que a gente fez aqui do ponto nojo aqui
no nosso função do H2 aprendi que é só
agente passar ele como como objeto aqui
e por conveniência a gente vai passar
nossa base de teste aqui com o olho
Beira tá então e aqui novamente a gente
só eu tô colocando só como dele à frente
só pra gente conseguir visualizar nem
farms do rstudio então se eu peguei
pegar e rodar esse cara aqui
a cena que vai estar como modo perder
Que importante que é esse camarada aqui
é serviço aqui ele já traz tanto A
petição do modelo né em relação a
variável de que eu tô que a gente tem
conta probabilidade de ser a classe
número zero e a classe número um que a
nossa classe de forma certo então é isso
a nossa próximo vídeo de hoje a espero
que vocês tenham gostado deixe o joinha
aqui no vídeo se vocês não são inscritos
do canal se inscreva no canal aí e até a
próxima Tá certo tchau tchau tchau
E aí