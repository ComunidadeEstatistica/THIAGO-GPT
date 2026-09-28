# Introdução a Linguagem Julia - Prof. Romerito Moraes

- **URL:** https://www.youtube.com/watch?v=EbvVx0rb8g4
- **ID:** EbvVx0rb8g4

## Transcrição

um ok a gente vai fazer uma breve
introdução sobre a utilização da
linguagem júlia né mas especificamente
trabalhando com data frames tá então eu
vou só fazer o pequena demonstração aqui
tá coisa bem básica mesmo só para
mostrar alguns comandos tá muito similar
àquela aí aqui todo mundo faz e mostrar
algumas coisas do como trabalhar com
pandas né então bora lá eu já tô aqui
com meu diretório aberto aqui né
documento estava sete a gente vai
trabalhar com esse aqui eu aqui ele tem
105 megas a gente vai criar mouse no
notebook
é né então
e bora colocar aqui ó
e demos júlia languages on
e a gente vai carregar algumas
bibliotecas aqui a primeira vai ser ssv
né a gente vai carregar que data feliz
a e por último sua carregar que
statistiques
ah tá essa primeira que a gente vai
carregar o nosso arquivo de csv após
dizes que vai pode também colocar dentro
tá firme e a gente vai fazer alguma
demonstração de como tirar uma média uma
soma algo assim muito simples tá só
brincando é muito tempo pronto o
executar aqui
o wilson é basicamente a mesma coisa do
do importe do pai então né tá eu vou
solicitar aqui o meu diretório né
e aí
eu tô com meu arquivo aqui ó meu arquivo
e nosso arquivo de demo aqui do júlia tá
aqui que a gente vai fazer aqui nesse
caso é como eu tô no meu diretório aqui
padrão né então eu não preciso
basicamente setar o caminho de onde
estão os meus arquivos para poder fazer
o trabalha mas se fosse o caso a gente
teria que sentar aqui o nosso caminho é
algo muito parecido com o que
normalmente se faz lá no estúdio né você
certa o diretório de trabalho então caso
você esteja com seu arquivo de notebook
em outro lugar e o seu data certinha
outro então você pode sentar né utilizar
basicamente aquele endereço e aqui no
meio você vai colocar o barra plano
dental até chegar no diretório editar
seus arquivos túnel caso a gente não vai
fazer isso daqui tá então eu vou chamar
aqui o meu o meu data frame the books né
vou colocar aqui data frame
olá primeiramente eu vou colocar aqui
csv em pó files
eu vou carregar aqui nosso nosso data
set
o que que ele vai fazer ele com ele vai
carregar certinho aqui e antes de fazer
a atribuição eu tenho nossa nossa tava
firme ele vai fazer o que ele vai
converter isso daqui através de secar
aqui vai jogar aqui dentro
e aí
e pronto a gente carregou aqui o nosso
arquivo esse data esse esse conjunto de
dados aqui né foi o que eu peguei na
internet aí só para poder fazer uma
extração então ele basicamente por
padrão exibe as três primeiras colunas e
o restante do vídeo nesse caso ele tá
omitindo isso daqui tá se eu não
quisesse carga todo ele aqui na minha
lista eu poderia fazer o first no casará
ou foste ele é muito similar ao red lá
do podas e
ah tá essa casa que eu só coloco um
moves que coloca aqui o número de linhas
que eu quero que ele exiba para mim
e pronto tô exibindo apenas cinco linhas
aqui em qual meu definir certo para mim
sabia que por exemplo o nome das colunas
eu dou um denis bora ver que o nome da
nossas colunas de
e aí
é né muito similar também é o que você
utiliza lá não todas que é o seria um
movies.co longe né tô aqui para a gente
saber a questão do tipo de dado de cada
coluna no de cada coluna a gente utiliza
o erp
o ar type ponto aqui dentro vou colocar
desse jeito aqui
se você colocar aqui o nome do nosso
data frame
e prontinho eu tenho que o primeiro
cavaleiro sem inteira depois strenger no
caso ano no caso né ele tá dizendo que
além de conta algumas colunas ele
comprou o valor e outras ele não
encontrou a gente faz esse tratamento
aqui depois tá para saber o tamanho
desse desse conjunto de dados aqui a
gente basicamente utilizar os sais é que
seria o shape lá do pano aí né
e prontinho gente tem 53 1497 linhas e
14 colunas tá então o que que a gente
vai fazer a gente vai fazer algumas
modificações aqui né para a gente poder
trabalhar com seu daqui primeira coisa a
gente vai fazer a gente vai renomear
essas colunas aqui não era estão pulando
aqui um pouco estranho né esse datacert
aqui onde data sets de filmes italianos
alto até aqui então ele tem alguns nomes
estranhos aqui então a gente vai fazer o
quê que utilizar aqui o e name
e o inimigo né o nome do nosso data
frame 1
ah pois isso que que tinha fazer a gente
vai colocar aqui o nome das colunas tá
deixa eu tentar copiar tudo isso daqui a
gente vai mudar tudo mesmo eu vou
colocar bem aqui
bom né então fica acontece eu vou dizer
que esse aquilo e se chamar pé direito
vírgula
eu vou copiar aqui para gente ter uma
certa agilidade
e aí
é só para a gente ter uma certa
agilidade
e esse aqui eu vou chamar de título
apenas
e aí
o título vírgula esse aqui não vou
colocar nada vou deixar seu não porque
depois a gente não vai mexer com ele
mesmo a gente vai acabar removendo a
maioria desses campos aqui o gênero vivo
em tudo para andar meu problema
o durata e duração
a espécie o país
e aí
e registre é se não me engano é diretor
e pronto
o ature atores
o voto médio colocar como voto médio
mesmo depois a gente vê isso aqui ó
ah tá tô médio voto descrizione
descrição
a nota e por último aqui é melhor
comentário né
e m comentário vou deixar assim
e a gente vai dar aquela organizada
agora né para ficar uma coisa assim mais
decente
o potinho
é só um pouquinho pessoal eu gosto dessa
dessa parte aqui da organização ajuda a
gente entender melhor questão do nosso
código aqui
e aí
tá certo
e aí
e prontinho quase lá
e aí
e prontinho tá então eu vou colocar bem
aqui assim também o pa
e aí
e prontinho tá então o que que vai
acontecer aqui é cada coluna dessa
primeira aqui vai receber vai ser mudada
para o que está passando aqui na frente
então bora lá
o rodeio aqui o xin eu mudei aqui ó
haiti coluna no né então a gente vai vai
repetir esse comando bem aqui assim ó só
pra gente poder ver se realmente mudou
aqui né bora lá
e pronto vou fazer mais uma coisinha
aqui porque eu não quero esse monte de
informação que a gente sabe que ele fez
a mudança
bom então vai exibir só os primeiros 5
e aí
e por enquanto não vou deixar sobre
quatro modelito aqui então a gente vai
rodar aqui o mês e o que que vai
acontecer né como a gente utilizou em me
aqui na frente automaticamente é para
ele mudar o título mas não foi o que
aconteceu né então como é que a gente
explica isso é a função hennig né ela
tem basicamente a gente consegue
trabalhar entre as duas formas a gente
consegue basicamente renomear esses
dados apenas para apresentar aqui né e a
gente se a gente quiser também fazer a
mudança diretamente em cima do nosso
data frame a gente tem que passar o
sinalzinho aqui de exclamação tá é isso
aqui ó ó
ah tá ok exclamação né eu não tô
lembrado tá então o que que acontece
quando quando eu possa separar muito
aqui automaticamente o meu tá frio ele
vai sofrer essa mudança
ah tá então depois que aplicar isso
daqui automaticamente né eu vou
realmente aplicar toda essa mudança essa
mudança vai ser real e cima do nosso
bota fé tá mas se você não quiser fazer
isso daqui você pode também fazer isso
daqui ó você pode criar um novo
dataframe a por exemplo x né vocês
encontra aqui o x da vida aí aqui
embaixo no chão esse pronto você
consegue pegar o que era só sem problema
nenhum só que nesse caso aqui eu quero
trabalhar com essa alteração diretamente
no nosso pra frente né próprio é isso
aqui basicamente seria equivalente
àquele comando in place que você utiliza
lá no pandas né para poder fazer
operação em cima do próprio da frente
então a gente já rodou aqui ó mudou aqui
esse a gente também vir aqui coloca o
nosso ambush
e pronto ficou muito bacana a gente
conseguiu fazer aqui é a questão da
nossa operação tá só que a gente não vai
querer todos esses caras aqui né a gente
vai querer apenas alguns campos aqui no
caso né é só isso que a gente vai
precisar então quê que a gente vai fazer
a gente pode utilizar select tá select
né então basicamente vai ser a mesma
estrutura que a gente é pegou lá em cima
só que a gente vai fazer a mesma coisa
agora pegar aqui na sacolinha né coloca
aqui ó ó
e-books tá notes
tá certo e aquilo not a gente vai passar
o que você passa aqui na nossa você tem
uma liçãozinha daquilo que a gente não
quer que venha nessa seleção
bom então pop é o que eu não quero que
apareça para gente é projeto comentário
descrição nota atores diretores país não
a duração gente vai precisar gênero
e aí
e pronto a gente não vai querer
e aliás muito pelo contrário né
e você está fazendo errado aqui
e a gente tem que deixar aqui aquilo que
a gente não quer tá então é
a nota e volto média gente vai precisar
duração gênero ano
oi e o título tá
um pontinho então a gente só quer esses
cinco caras aqui né assim também como
antes você também se quiser fazer
alteração diretamente ou criar uma
variável a parte disso você pode ficar à
vontade hein
ah tá certo então deixa só uma vez aqui
que eu tenho essa esta manhã de
programador curtinho você acha que bem
alinhado
e aí
é só que aliado aí em cima
é perfeito pronto eu também vou fazer
alterações em cima do meu dataframe aqui
então automaticamente
e a gente vai fazer o quê vai selecionar
apenas essas coisas aqui tá se eu rodar
esse cara aqui também basicamente ok
pronto ele fez alteração que a gente
precisava lá
e agora que que a gente vai fazer né a
gente vai a gente vai fazer aqui uma
média né
eu pesquisei por exemplo ver a média
para a gente faz aqui ó a gente pega
aqui a nossa casa como lobos né ponto
duração agora vai ser seu nome mesmo
e esse aqui no caso adoração só que a
duração aqui no caso ela tem minuto só a
gente vai ter que depois dá um jeito de
fazer o quê de converter de criar um
novo campo
é né para dizer aqui ah tipo assim a
quantas horas né quantas horas e quantos
minutos devo por exemplo sempre 103
minutos né tiver que isso aqui dividir
por 60 e vai dar uma hora alguma coisa
então essa é a ideia tá aqui média a
moda você coloca a morte
e mude não acho que eu não tô lembrado
a chover mídia mídia mud eu não tô
lembrado qual é o nome do outro
tu acha que as um para fazer a soma né
são o total
e é isso que basicamente não vencer o
sufoco agora isso aqui a gente vai essa
questão da água e demais essa questão de
estatística a gente vai ver no outro dia
depois se nós se ver já vai acabar
ficando muito grande tá tá e agora a
gente faz o seguinte gente vai na minha
nossa vai fazer um sorte aqui na nossa
nossa tá firme né a gente vai fazer
ordem pelo ano aqui no caso né então a
gente base que a gente vem aqui é um
colocar sorte tá coloca aqui no luz
vírgula e o campo a gente vai fazer isso
é o ano
a prova está pegando mais antigo né por
mais atual e pra gente também fazer né
alteração em cima coloca aquele carinho
ali aonde ser eu agora que que a gente
vai fazer a gente vai aqui existe muito
muitos valores faltantes né então a
gente vai rodar um comando aqui em cima
né moço igual a própria iniciem
o drop 1100 ele aponta para o nosso da
frente tá depois do documentação você
estuda melhor como é que funciona o o
troca mi-100 como é que faz o tratamento
de dados faltantes outra coisa é só
mandar mensagem sou muito rápida tá
certo então ó a gente tinha isso aqui né
então algumas leis diz realmente
desapareceram aqui agora a gente vai
bora lá e já fazer o seguinte a gente
vai fazer alguns filtros aqui no caso é
então bora lá alguns filtros bem simples
aqui em cima do meu tá tá frame eu quero
por exemplo é exibido na tela todos os
filmes onde o gênero bíblico colé então
basicamente utilizar o piercing
o ponto né o colocar aqui bíblico mas
você também pode colocar um pedaço da
informação não tem problema nenhum muito
similar a questão do contains né lá no
pano está bem você pode ficar à vontade
de poder mexer nisso aí aí eu coloco
1movies.to e coloca aqui o nome do campo
né e eu a júlia vai ter que fazer aqui
essa questão da alteração pronto fechei
aqui
é só moleque e
e aí
ah tá bora ver o que que tá faltando
bíblico mons
e aí
e o corsa c
e deixa eu a vi não tem isso daqui né
pronto né ele retornou 52 linhas né
somente filtrado que pelo campo de
gênero no caso
ah tá agora a gente vai fazer o
agrupamento por esse gênero felizes no
grupo e bye
e no que bairros né e a gente vai passar
nossa coluna aqui né
o gênero
e aí
é só que é diferente do agrupamento do
pandas o que que o que que esse
agrupamento do júlio faz ele basicamente
fez o fez 28 agrupamento baseada no
gênero então ele fez por exemplo aqui
uma aqui por esportivo né tá vendo aqui
ó a passo a esportivo aí depois como que
passa como está mais informação ele vai
fazer por bíblico vai fazer para cada
agenda de vai fazer agrupamento então
para gente não é interessante também não
é muito claro então que a gente pode
fazer a gente pode fazer o agrupamento
que diferenciava né a gente pode
utilizar que bye
eu vou colocar aqui movies movies
vírgula para colocar aqui gênero
o gênero tá depois de renda que a gente
coloca aqui ontem né já te disse que a
gente vai fazer aqui uma uma média e
aqui chama vai fazer o quê vai colocar
confirmou-se novamente tá
e colocar aqui
ó e vai é tão gente vai fazer isso
agrupamento aqui
é pelo voto médio né
e pronto agora a gente conseguiu fazer
um agrupamento total né pegando aqui a
média de todos os votos e fazendo
agrupamento gênero a gênero eu quero
é a gente também pode ir por exemplo lá
eu quero ver apenas um campo aqui do meu
dataprev em é o que você faria lá no
plano das assim né e colocarei aqui nome
do carinha aqui
e para que você pode fazer a sério ponto
então bora colocar aqui por exemplo o
campo de título aí a gente conseguiu
basicamente exibir todos os títulos aqui
ó
ah tá ah como a gente mexendo assim a
gente vai querer fazer o que a gente vai
pegar essa coluna aqui e a gente vai
poder tem horas tá é só uma divisão
comum é lógico que precisa é a nossa
hora que você for criar uma nova coluna
né a partir de uma informação de
existentes você tem que fazer tudo um
tratamento para não ter nenhum problema
nisso daí então a gente vai fazer assim
ó uma nova coluna a gente coloca aqui
esse parâmetro que
ah tá e o nome aqui tá nova comando para
colocar aqui duração 1h né barra m da
escola consigo fazer assim agora colocar
aqui no oração hm seria hora e minuto é
só uma ideia e aqui a gente colocar
ponto ponto igual como a gente o nosso
campo largo de duração a gente fazer
assim ó ó
eu posso calcular de duração
e aí
o ponto duração
é dividido para 60
e pronto né a gente saber se realmente
e funcionou esse nosso cômoda aqui a
gente só vou na basicamente o que é um
bolso e
ah tá então gosta mais com ele tá lá no
final né então a gente não não vai
conseguir enxergar esse cara aqui a
gente pode fazer isso aqui ó ó
e bora passar aqui uma lista com essas
colunas a gente vai pegar aqui
basicamente só título
e no filme bora pegar aquele duração
eu ia colocar a gente acabou de criar
essa coluna keep on
o próximo eu
bom então é tem algumas coisas aqui que
não vou fazer sentido mas por exemplo
agora é só descer aqui basicamente deu
120 minutos né que vale é duas horas de
filme é isso aqui você tem um minutos
uma hora 18 e por aí vai tá certo é
lógico isso aqui é só uma demonstração
tá agora a gente pode fazer aqui também
a gente ir para excluir uma coluna daqui
é basicamente utiliza a mesma coisa que
a gente fez lá em cima a gente nos que
um select
e aí o canto que a gente não quer a
gente só coloca selfie 1.1
e como a gente basicamente já já não vai
precisar de ser tempo de duração é um
exemplo a gente volta aqui assim ó a
gente em três coroas ou metido né se eu
pegar esse comando aqui enrolar
novamente
a parte aqui na escola rosa novamente
agora pegar esse cômodo aqui
ah tá
oi ó eu rodei aqui então basicamente a
gente quer naquela mesmos não são eu não
eu não toquei né isso é uma data frame
então basicamente quando a roda aqui vai
dar erro porque uma coluna ela não
existe mais é então a gente tira esse
para quê
e prontinho agora aquela coluna não
existe mais para se certificar você
daquele ontem nem me
o moço prontinho agora ele só tem que a
duração horas
o minutos tá agora tinha fazer uma
pequena filtragem pegando aqui pelo ano
oi gente coloca aqui malucos
e vai colocar aqui
e colocar isso para almoçar aqui
e aí a gente fecha esse cara aqui
vírgula pa aqui dentro a gente vai fazer
o que a gente fazer aquela voz né vai
pegar aqui o nosso campo ano ponto seu
maior
é né então bora pegar aqui para o
intervalo pequeno de filmes né agora
pegar aqui do ano 2000
bom né mudou novamente torrent repete
baixo como é que si mesmo para me
tranquei e
é só que nesse caso o menor bom ele não
achou nada né bora aumentar aqui para
2002
e pronto a gente tá pegando aqui o
intervalo de filme entre 2001 tá
2001/2002
a alice também pode pegar o valor aqui
você tá o campo aqui com uma informação
específica por exemplo eu quero saber né
e onde o alemanha o maior do que 2 mil
ou igual a gente pode colocar aqui mas
eu quero saber o seguinte eu quero pegar
aqui a duração eu quero pegar aquela
oração e eu quero dizer o que eu quero
que ela seja igual a por exemplo 2
é né pronto então aqui basicamente né
dois não vai colocar um só para saber
quais filmes é com a data maior do que 2
mil é o ano 2000 tiveram uma hora de
duração da é um exemplo
e aí
e como evitar o like na questão da
coluna é só faça o seu daquela né bem
escreva vou pegar aqui só um
a porta aqui título virgula não né
oi e a duração né que é o nosso campo
aqui em questão
eu não tinha olha todos esses filme aqui
basicamente tiveram uma hora de duração
tá então é isso pra finalizar a gente
vai exportar o nosso arquivo né e de
fato você realmente ele tava precisando
geração que essas alterações que a gente
fez a gente basicamente utilizar online
né a gente para colocar aqui o
e como filmes com sucesso ver aqui eu
não preciso me preocupar com a questão
do ims moço vírgula e eu coloco aqui o
apendicite igual a celsius né o apetite
é eu determino um símbolo arquivos ele
vai ter uma coluna ou não é nossa coloca
alguma show aqui no caso que que vai
acontecer ele vai mostrar para mim que
não tá calor coluna aliás né colonial
perdão é o renda no caso né o cabeçalho
do méxico dunas laca
tá prontinha então tá aqui ó aqui no
nosso arquivo csv desce eu dei aqui por
exemplo red
o rsb a gente exibir aqui as primeiras
colunas
e aí
e prontinho tá vendo aqui pra gente
realmente se certificar se realmente
isso aqui funcionou bora lá nosso data
sete horas tá vendo aqui ó tá terminando
eu só 2 megas em comparação a 115
e o basicamente eu vou abrir esse cara
quê
é só para gente realmente ver
e se a gente conseguiu exportar ele com
pronto tá tudo certo aqui olha a gente
deixou só o ano o gênero tá bom pessoal
espero que vocês tenham gostado se que
foi uma breve demonstração de como é que
eu tive eu me chamo de breve né isso
aqui foi só um mal uma arranhado zinho
da coisa né mas só que já dá uma
basicamente a visão para vocês né de
como é que a gente pode trabalhar júlia
é uma ferramenta é uma linguagem
programação fantástica nos próximos
vídeos a gente vai lógico que trabalha
muito mais com ela né então até mais