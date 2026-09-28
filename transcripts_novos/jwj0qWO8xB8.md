# Understand why you should create a model - Prof. Adriana Silva (JEDI)

- **URL:** https://www.youtube.com/watch?v=jwj0qWO8xB8
- **ID:** jwj0qWO8xB8

## Transcrição

[Música]
oi pessoal
agora já fala quem sabe pra que a gente
faz modelo mas antes de entrar nesse
propósito eu queria fazer um comentário
que eu falei nos vídeos anteriores
se vocês votarem nos outros vídeos que
eu fiz participação e no blog do thiago
eu falei sobre o lance da correlação e
casualidade a gente viu que se não tinha
nada a ver uma coisa com a outra e eu
comentei de um livro que chama com
relações espúrias
só que eu não lembro o nome do autor na
hora que a gente estava gravando agora
eu tô aqui na minha casa fica mais fácil
eu peguei um livro então esse é o livro
do das relações espúrias é um livro
super interessante muito engraçado do
tyler e aí aqui dentro tem várias
relações que são às mentirosas que não
tem nada a ver com casualidade mas que
estatisticamente existe uma correlação
então este foi o livro que eu indiquei
da vez passada mas enfim vamos pro
tópico desse vídeo de agora o que a
gente vai falar é todo da faems ele quer
sair desesperadamente aprendendo um
monte de técnica ele vai lá em estudo um
monte de coisa mas ele deixa uma coisa
super importante para trás que é
entender o propósito do modelo entender
o negócio que significa entender o
negócio é saber conversar com o pessoal
que vai usar esse modelo e entendeu pra
que ela quer esse modelo como ela vai
usar esse modelo e qual é a proposta
dela em se fazer esse modelo adriana não
dá pra sair pra que eu preciso aprender
isso cara
se você não sabe conversar com o
indivíduo que vai usar esse modelo você
não consegue tomar decisões importantes
durante o processo de modelagem
no último vídeo a gente falou sobre
treinamento validação e teste que a
parte lá para evitar over feet momento
que tem que fazer uma escolha do melhor
modelo na validação eu preciso saber que
métrica olhar e aí então eu preciso
saber pra que o negócio vai usar esse
modelo com a proposta deles porque
normalmente o modelo pode ser feito para
três coisas 1 decisão eu quero saber se
é ou não é
2 a estimativa qual é a probabilidade ou
qual é o número que eu estou buscando
três ranqueamento o indivíduo mais
propenso a fazer aquilo
adriana como eu tomo uma decisão do pará
que o meu modelo
às vezes isso não é tão fácil
identificar e às vezes você tem que
fazer uma combinação entre duas
possibilidades por exemplo mas não
entendem então o que significa cada uma
dessas três coisas que eu acabei de
dizer hoje estou fazendo um modelo que
tem a proposta de ranqueamento aí a
gente vai entrar em histórias de negócio
para mostrar o que me faria tomar essa
decisão por escolher ranqueamento
então vamos lá imagine o seguinte eu
trabalho numa empresa e essa empresa vai
fazer divulgação de um produto para
fazer a divulgação de um produto ela tem
que investir dinheiro que significa
investir dinheiro a ela vai pagá-la uma
cartinha para enviar para as pessoas ela
vai mandar um brinde para as pessoas
ou ela vai mandar um e mail independente
do que ela foi fazer tudo tem um custo e
se o meu custo é restrito
eu preciso fazer o que é bom se ele quer
saber quem tem chance é quem tem a
probabilidade de compra é mais
interessante eu falar os indivíduos que
têm maior probabilidade de compra então
se eu tenho que falar os maiores eu
estou ordenando a probabilidade estimada
por algum algoritmo que nós já vimos
então no momento em que eu estou
ordenando e vou pegar o teu esta ordem
eu vou pegar os primeiros então todo
maior pormenor
isso aqui é o meu objetivo é
ranqueamento normalmente eu estou atrás
de um objetivo ranqueamento
quando eu tenho é verba restrita quando
eu não tenho muito espaço alcance
eu preciso limitar então vou pegar os
que têm maior probabilidade de fazer
aquele evento certo rankeamento que que
é um objetivo decisão eu preciso saber
se é ou não é
ele pode ser usado para o mesmo objetivo
de impactar alguém mas agora não tenho
restrição financeira
adriana todo mundo que você me disser
que vai comprar eu vou impactar então
ótimo
não importa mais a probabilidade me
importa assim a decisão do modelo que na
maioria das ferramentas o ponto de corte
automática 05 então se eu estiver em uma
probabilidade maior do que 0 5
as ferramentas vão dizer que aquele
indivíduo faz um evento que estou
buscando aqui no caso contra
então é para interessante eu posso ter
um objetivo de ampliar porque tem alguma
restrição financeira tem alguma coisa
num negócio que me impeça
de pegar todo mundo que eu decidi que
faria aquilo então esses dois andam
juntos eles são provas de que o terceiro
é estimativa que significa estimativa
pensa em um banco um banco ele tem o
banco central que regula o banco então
ele não pode sair emprestando dinheiro a
porta de saída emprestando dinheiro para
todo mundo
ele não pode uma série de coisas é o
mais importante e eu coloquei um milhão
no banco eu sonho em um dia eu chego lá
se eu coloquei um milhão no banco e eu
quiser sacar amanhã em um milhão o banco
tem que me devolvesse 1 milhão na hora
que eu pedi porque ele não pode dizer eu
não tenho esse dinheiro agora vou te
entregar depois então o banco central
regula e cobra eles o que você tem que
poupar dinheiro suficiente e deixar ele
parado sem rendimento para que você
possa devolver o dinheiro para qualquer
um que vier pedir só que pensa um banco
ele ganha dinheiro como pegando dinheiro
de um emprestado pra outro então ele te
dá menos juros e cobra muito juros e aí
assim que o banco vive na maioria das
coisas vão fazer muita coisa mas ele
ganha muito dinheiro com isso
então pra ele não é inteligente ter
dinheiro parado aqui esperando você
pedir porque o dinheiro parado é perder
dinheiro que ele faz com o dinheiro que
colocou ele guarda um pouquinho ea gente
vai ver o que seria então a estimativa
eo resto ele empresta para outras
pessoas ele está assumindo um risco em
cima disso o banco central regulamentou
aqui o quanto que ele tem que ter
guardado pra atender qualquer chamado
que venho aqui pedir pra ele
só que para ele fazer isso vamos pensar
o seguinte temos duas pessoas aqui temos
a adriana e temos o joão o joão pegou um
milhão emprestado do banco mas o joão
sempre foi um bom pagador
ele é compromissado e ele pegou um
milhão para investir na empresa dele que
está indo super bem e que vai trazer o
rendimento de volta
adriana ela pegou 15 reais emprestado 10
reais emprestados ea grana não paga
ninguém
eu falando mal de mim mesmo e andré não
paga ninguém então o que se faria se eu
tenho que guardar o dinheiro normalmente
as pessoas caem na média a 1 milhão mais
r$10
veja aí quando vai dar média 500 mil r
500 mil
segurando de que vou ter essa galera não
tem sentido porque se o joão é um bom
jogador e ele vai me pagar ele não me
oferecem riscos
se ela é uma má pagadora e não vai me
pagar ela me oferece riscos então eu
tenho que ter ficado preocupada com ela
mas ela só pegou dez reais
então qualquer ideia vamos entender e
criar uma probabilidade de deixou qual é
a probabilidade desse cara deixar de me
pagar qual é a probabilidade era deixar
de pagar
e aí uma vez que eu tenho isso eu
multiplico pelo valor que ele me deve e
aí então é o pedaço é o ponto quanto de
dinheiro que tenho que me preocupar
então no caso de adriana que foi dez
reais se a probabilidade dela é tão alta
dela ficava devendo então eu vou guardar
nossos reais para garantir que está tudo
sob controle no dele a probabilidade de
ele pagar é muito alta então eu vou
guardar o que 100 mil reais e não
humilha e não 500 mil
reparem enquanto que o banco ganhando
com isso queriam deixar dinheiro parado
ele vai lá empresta para os outros então
no momento em que eu estou buscando a
probabilidade daquele evento acontecer
para multiplicar por um valor
aí eu estou buscando que a probabilidade
tem que ser precisa
a minha estimativa tem que ser precisa
então nesta situação uma situação
semelhante a essa objetivo estimativa é
muito importante e aí porque eu tenho
que saber pra que o modelo está sendo
usado para ranqueamento decisão
estimativa porque é baseado nisso que
você vai escolher a métrica para dizer
qual é o seu melhor modelo
então vamos lá rankeamento ranqueamento
estou ordenando a probabilidade do maior
ou menor e vou pegar uma fatia disso
quais métricas que contemplam isso todas
as métricas e ordeno então é muito comum
as pessoas falarem de curva rock o rock
ordena então é uma meta que pode ser
atrelado a esse pedaço
qual outra métrica que eu adoro é o lift
que no anos acima lift num fps chama
ainda que o porquê porque ela vai medir
o quanto que naquele pedacinho que você
tá pegando que tem maior probabilidade
enquanto que a taxa de resposta aqui
dividido pela taxa de resposta
pede então ele me mostra quantos ex eu
sou quanto fora do meu modelo é então
métricas de ranqueamento tem as suas
medidas
ou seja tem as métricas específicas para
ranqueamento quando é decisão
aí vai muito atrelado no canto acertando
o quanto estou errando e aí vem o tal
domingo fiquei o que eu particularmente
não acho que a melhor médica mas ela é
muito utilizada para a decisão
junto com ela vale a pena estudar
precisão e recall que são métricas
interessante também para essa parte de
decisão e no outro caso a gente está
falando de estimativa estimativa eu
preciso ter a a qualidade suficiente o
meu modelo para que a probabilidade seja
mais correta porque se eu souber estima
essa probabilidade
eu vou multiplicado pelo valor que está
me devendo pelo valor que eu emprestei
então o que vai acontecer eu vou deixar
de poupar vou deixar de investir então
ficar guardando dinheiro desnecessário
a probabilidade eu tenho que ser muito
real neste momento existem métricas pra
isso por exemplo é ver escreveu eu vou
simplesmente fazer a diferença do real -
o estimado e eu vou verificar o quão
distante ou daquilo
e aí tem várias métricas para cada um
desses qual você vai escolher é uma
decisão de quem está criando esse modelo
ea métrica que faça mais sentido para o
seu objetivo então sempre pensei nisso
nunca nunca se esqueçam de conversar com
quem vai usar o modelo sempre pensei no
negócio porque é ele que define a
qualidade de seu algoritmo então se você
vai começar agora na vida de datas a
gente começa também entendeu porque
leram histórias vejam aplicações de
casos reais pra que você começa a
visualizar forma de caminhos e
abordagens diferentes não se fixa em uma
métrica única todas as métricas são
úteis nas suas particularidades e entra
cada problema pode ser que se escolha
uma métrica diferente exatamente porque
os modelos têm propostas diferentes
porque o negócio exige coisas diferentes
então espero que vocês tenham gostado
que tenham entendido que o modelo serve
tanto para ranqueamento quanto para a
decisão enquanto pra estimativa mas que
vai depender da proposta de negócio do
objetivo do problema que estou
enfrentando para tomar uma decisão de
qual dessas três vão utilizar e sabendo
qual é o meu propósito eu consigo dentro
d
escolheu uma métrica que faz mais
sentido para definir qual é o melhor
modelo
espero que ele tenha entendido que
tenham gostado se precisarem de alguma
coisa fique à vontade para me procurar
muito obrigada
[Música]