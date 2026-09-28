# Aula 04 – Normalizando o preço das ações - Trading com Dados

- **URL:** https://www.youtube.com/watch?v=oiGD7UBLpmc
- **ID:** oiGD7UBLpmc

## Transcrição

e vamos agora para nossa Seção 3
e nessa seção
Bom vamos lá seção 31 V
e como normalizar
e o preço das ações é um conceito
importantíssimo como eu falei na seção
anterior e uma vez que a gente normaliza
o preço das ações a gente consegue
compará-los entre si vocês vão observar
que agora elas vão começar no mesmo
ponto elas não têm um ponto comum e
dessa forma Então você consegue comprar
todas elas e a gente vai entender a
importância dela
é perto da gente fazer a normalização de
fato uma coisa que é importante a gente
fazer também é utilizar
os índices índices de referência no
mercado financeiro Quem disse são esses
são aqueles dentes usados nas bolsas de
valores ao redor do mundo para medir em
mais ou menos é um termômetro de como
aquelas bolsas estão performance as
bolsas estão indo para cima para baixo
por isso que eles usam os índices na
nossa bolsa o índice utilizado não mas
famoso obviamente é o ibov e eu uso
bastante também né na bolsa Americana a
gente tenho SP Fire Hunger que já já vou
mostrar para vocês como pegar para pegar
esses índices é tranquilo a gente vai
seguir aqui o mesmo raciocínio que a
gente usou para pegar as ações lá em
cima então eu vou pegar aqui a mesma
fórmula essencialmente gente não precisa
mudar nada
Vou colocar aqui só que ao invés de usar
o que quer de uma ação eu vou usar o
ticket de um índice nosso caso como a
gente quer o ticket né da do ibov ou tem
que ter esse aqui pv-sp data de início
já definimos latas de tinta definido
também o benchmark continua sendo o
próprio bvsp a pessoa o pequeno está
tratando do mercado brasileiro então o
benchmark tem que ser o mesmo então se a
gente executar este daqui
bom aparentemente deu certo temos
os dados só vou aqui na verdade Qual o
nome
o mal errei aqui né eu coloquei eu
deixei o dados ação aqui vamos tirar
esse daqui agora sim agora eu posso
executar
o ibov perfeito temos Então como a gente
abrir anteriormente ele sempre nos dá
uma lista né com dois deitar Friends no
caso só preciso do segundo então vou
fazer assim ibov é igual o próprio bove
e eu quero e se deitar frame aqui eu não
quero os dois vamos ver se deu certo é
perfeito então eu tenho as datas de 2016
até
em 2020 bacana
Oi e a gente tem aqui as variações do
nosso e bov
e vamos ao mesmo raciocínio próximo
Cliff hanger qual é a diferença pessoal
é que aqui o ticker diferente tá aqui é
gspc Opa e reparem que eu vou usar o
próprio tica da sempre faz Ranger como
benchmark por quê Porque agora eu tô
olhando para o mercado americano eu já
não vou usar mais o índice brasileiro
como referência então para isso eu tenho
que trocar pela sentir Ford Ranger Então
se executar isso daqui eu vou ter que
nem fui boa vou ter uma lista com dores
deita frente também vamos dar uma vez
guarda uma lista com dois deitar frente
defe control the hitchhiker's eu quero
sol segundo
eu só vou mudar isso que é
Oi e aí sim temos 1207 observações com
10 horas vezes temos aquele começando em
2016 e indo até 16 de outubro tá pessoal
Ah então beleza já temos tanto o ibov
quanto é sempre faz Ranger agora a gente
vai fazer uma transformação parecida com
que a gente fez com as ações lá atrás
lembram que do deitar firme inteiro das
ações eu trouxe apenas a coluna seis e a
coluna 7 que eram as colunas que tinham
a data EA coluna que tinha o preço
ajustado respectivamente Então dessa
mesma forma eu vou trazer apenas essas
colunas porque são as colunas que
interessa antes disso vamos só dar uma
olhada aqui no formato do ibov temos
referente deixe temos pressa Justin o
que que eu vou fazer agora eu acho que é
válido
e a coluna seis e coluna 7 é válido a
gente mudar os nomes Porque como a gente
vai juntar com o deita Femme que a gente
fez anteriormente é interessante que tem
um nome muito claro depois para a gente
não se confunda Então vou colocar com o
name de envolve para coluna 6
O que é data mim Playboy e para a coluna
7 é a própria data isso Vai facilitar o
meu entendimento depois quando eu cruzar
com outras bases Então vamos perguntou
Então beleza eu tenho o imóvel tinha um
valor mais uma vez o valor de Bob
ajustado EA data perfeito vou fazer algo
parecido
Oi para o Oeste five hundred
e eu tinha verdade s&amp;p 500
o prefeito E agora o que que a gente vai
fazer
e a gente vai selecionar apenas essas
colônias porque depois quando a gente
for cruzar com os dados das ações vai
ser apenas isso né que a gente vai
precisar a data e o valor do próprio
Bose e o valor da sente ferrando então
vou fazer assim e Bob vai ser o próprio
ibov
o e as colunas eu quero apenas sete dias
6
bom então vamos ter esse formato aqui
e olha quase que eu fecho contigo não é
para fechar Então vamos lá estamos aqui
E aí
o s&amp;p 500
o s&amp;p 500 aqui também e aí temos apenas
duas colunas são as colunas que
interessam e agora que a gente precisa
fazer pessoal basicamente trazer né o
imóvel é sempre faz Ranger e cruzar Ele
eles né com os dados das ações aquele
dele tá chovendo que a gente montou
Vamos então primeiro fazer um novo deita
frame fazer aqui um deita frame ebov
assistiu 500 em que eu vou unir né esses
dois que a gente acabou de criar que é o
ibov e o s&amp;p 500 e eu quero que ele faça
esse Johnny esse cruzamento pela coluna
de data
bom então quantas colunas ele conseguiu
ele Manteve 1164 observações então
perfeito essa estrutura que a gente
queria a gente vai pegar agora esse
deita fêmea que acabamos de criar a
gente vai juntar e se deitar frame qual
deitar forma de ações que criamos o
atrás que é esse daqui com as ações de
mobi então eu vou chamar ele vamos tomar
de total para facilitar nosso
entendimento total é uma rede de
a ação
e eu vou até começar na verdade Qual o
próprio boxe sp-500 para ficar mais
fácil da gente ver essas colunas do
Deita firme ação vai
e deita e esse vai ser aqui o nosso
Total conseguimos manter então 887
observações né não veio todas as
observações provavelmente pelas razões
que a gente já tinha visto antes então
percebem que o IBOPE isso aqui é sempre
faço Ranger tô aqui e as outras ações de
morre estão todas aqui agora Então
pessoal é que a gente pode entrar na
parte da normalização porque agora a
gente já tem os dados que a gente
precisa né o que a gente faz para
normalizar
é como eu falei para vocês a
normalização ela é um conceito
importante porque ela vai permitir que
todos esses ativos Eles começam no mesmo
lugar então quando eu for analisá-los
eles vão ter um mês no início eu vou
poder analisar a rentabilidade deles
todos juntos pano realizar o que que eu
preciso fazer eu preciso que todos eles
comecem do valor um se eu quero que
todos eles começam no valor um vocês
concordam comigo que eu preciso usar o
valor inicial como referência de tal
forma que esse valor seja um para
Estação por exemplo esse valor aqui seja
um para esta ação aqui e assim
sucessivamente Então como que eu posso
fazer eu posso simplesmente dividir
todos esses valores aqui dessa ação por
exemplo pelo primeiro valor vou pegar
essa ação aqui também da mesma forma vou
dividir esses valores aqui pelo primeiro
valor se eu fizer isso para todas as
nações eu vou normalizar todos esses
preços vamos ver como
E aí
em primeiro lugar a gente precisa ver
que a data não pode ser normalizado a
data não tem um formato de preço não tem
o formato numérico ele faz sentido
normalizada alta Então por enquanto a
gente deixa a data de fora tão que a
gente pode fazer vamos criar um novo
deita frame chamado normalizado
e em que normalizado vai receber o meu
Total sendo que por enquanto eu vou
deixar a coluna 1 a coluna de data fora
bom então vamos ter esse daí tá firme
aqui né que não tem mais longe da ALCA
então a gente já consegue em tese já
consegue normalizar para normalizar
pessoal a gente pode fazer o uso da L
apply da função ele apoia porque a gente
queria uma função Zinha que já aplicada
em todas as colunas de uma vez Então quê
que eu sugiro Vamos fazer assim ó função
L apply
de dentro dessa função vou passar o
deitar frame né que eu quero normalizar
E aí eu crie uma função a função super
simples em que essa função ela recebe 16
e o que ela faz ela dividir esse sim
pelo primeiro elemento daquela coluna na
verdade ela pega né os valores de uma
coluna e dividir pelo valor inicial
daquela colônia com dessa forma estaria
não realizando aqui só para me assegurar
aqui isso aqui vai virar um deita frame
que o romance que eu quero eu vou passar
isso aqui dentro da função deitar frame
E aí eu posso chamar isso de vamos
chamar ele de novo total
e a gente não se confunda com esse deita
frame aqui então novo Total recebe
normalizado a gente vê de todos os
valores das colunas pelo valor inicial
de cada coluna respectiva e então vamos
ver se deu certo
eu percebo então que todos os ativos
aqui todas as colunas estão começando
com um quero que a gente queria
é tão perfeito deu certo percebeu também
pessoal que depois de um tempo para cada
um desses ativos a gente vai ter uma
ideia mais ou menos de a de
multiplicação né de conta que ele ativo
subiu no período por exemplo então por
exemplo se eu pegar aqui bebê se é três
né a brasilseguridade né se eu não me
engano vocês vem aqui que ela tá como
1.18 antes ela tava com valor um ela
começou com valor ou seja nesse período
aí ela subiu dezoito por cento percebam
aqui ó b3sta três ação da B3 Olha onde
ficou por mais de três vezes ela começou
com o valor um agora ela tá em 3.17
então é bacana a gente usar esse formato
normalizado porque permite que a gente
tira essas conclusões logo de cara é até
elas são aqui ó subiu quase 4.7 vezes
desde aquela data Inicial lá que a gente
viu E aí pessoal uma vez que a gente tem
esses dados normalizados né
Oi Total luz em um gráfico só e fica uma
visualização bacana porque mais uma vez
que eu falei Eles vão todos começar do
mesmo valor antes disso eu vou só
funcionar coluna de data final gente não
pode perder a referência da nossa data
eu vou pegar aqui a data que estava no
deita firme Total data e aí adicionamos
a coluna data aqui no deitar frame novo
Total queijo pode fazer agora enfim a
gente pode plotar vários ativos várias
ações normalizados para facilitar eu vou
pegar esse daqui esse código que já
estava feita para plotagem Vou colocar
aqui vou chamar ele de algum outro nome
e a e agora pessoal eu vou usar ações de
um outro setor vamos tentar usar ações
do setor da construção Que ações são
essas né Vamos até ver se as ações
constitui o primeiro novo Total aqui não
total no total no total
o primeiro ver se as ações estão aqui né
então ações de construção por exemplo
que eu acompanho temos aí Zetec temos
MRV né mostrar bastante conhecida vou
ver se tem que MRV temos Cyrela
é só vir ela três e aí a gente pode
agora então adicionar a os índices né
que a gente vai usar para fingir
comparação
bom então temos um board eu vou confiar
mais uma linha aqui para colocar aqui
embaixo
e a gente faz um Android e naturalmente
não podemos esquecer de mudar né os
rótulos Então é isso que você usa Tec
a MRV
a Cyrela se aqui vai ser o nosso gov
ó e aqui teremos o SP
me faz muito bem
a beleza é isso então podemos enfim
comparar todos eles num lugar só e temos
aqui o nosso gráfico bem bacana das
ações de construção um ver se a gente
consegue já até alguns insights né
e a gente ver o que ação da setec ela
teve um uma subida expressiva né as
ações do setor de construção elas também
ali seguem mais ou menos o mesmo padrão
sendo que ezetec parece que que ela tem
uma volatilidade muito maior negócio se
lá muito mais ela subiu muito mais caiu
muito mais
e a Cyrela mais ou menos ali em segundo
lugar eles não conseguiram recuperar
completamente os patamares de preço que
tinha antes da pandemia mas o que que é
interessante ver que eu só se a gente
pegar por exemplo índice americano que
ela sente ferrando percebam que a gente
faz um arranjo ele fica praticamente
esquecido né gente mal consegue ver que
vai sentir falando da rentabilidade dele
se ele te ver a comparada né quando você
relações tem no Brasil é é bem baixa mas
ele é muito mais estável né E aí talvez
seja um site interessante para vocês
pensarem Quando vocês tiverem analisando
e compondo a carteira de vocês o que é
que vale a pena tem na carteira Será que
vocês conseguem vamos ver suportar né
consegue ter esses ativos aqui tem essas
grande volatilidade que só vem muito mas
eventualmente também sofrem muito ou
vocês preferem ter algo como assim faz
Ranger por exemplo
O que é muito mais suave muito mais
estável né mas ao mesmo tempo PC bom que
ele teve a rentabilidade bem menor nesse
período depois pessoal ainda nessa
sessão eu queria mostrar para vocês mas
no próximo vídeo né Eu queria mostrar
para vocês como que a gente pode
modificar um pouco o formato de se
deitar frame de forma a exibir todas as
colunas não gráficos só obviamente que
como tinha falta para vocês talvez não
seja opção mais factível de análise né
vai ter muita muita linha nesse gráfico
mas eu acho bacana que vocês tenham essa
opção se um dia vocês quiserem ser um
dia vocês pesquisa precisarem né Se um
dia vocês precisam em vocês vão ter aí a
opção de colocar todos esses ativos
todas essas linhas não gráficos só um