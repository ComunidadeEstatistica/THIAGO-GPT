# Aula 14 - Frequências e Tabelas Cruzadas Parte 1 -  Curso de R para Finanças Quantitativas

- **URL:** https://www.youtube.com/watch?v=YAeG5qBYwJE
- **ID:** YAeG5qBYwJE

## Transcrição

[Música]
fala pessoal sejam muito bem vindos aqui
aos poucos e marketing meu nome é
leandro guerra hoje entramos na aula 14
do curso de r para finanças
quantitativas
onde eu vou fazer a primeira parte
ou seja a primeira aula sobre como você
extrai frequências e faz tabelas
cruzadas dentro do r estúdio
lembrando sempre todo o material de
apoio tal disponível lá no site no aos
pouco marcante pontocom na sessão do
curso de finanças quantitativas também
se você está aqui pela primeira vez
ainda não inscrito no canal se inscreva
agora deixo já aqueles eu li ke e vão
embora por r pra ver como que a gente
faz essa história de frequências e
tabela cruzadas porque esse tipo de
análise é importante porque você começa
a categorizar os seus dados
e aí você começa a fazer uma parte muito
relevante dentro da estatística que a
chamada estatística descritiva então não
só pegando as análises feitas com a
função samary mas agora a gente também
vai aumentar um pouco a complexidade e
eu vou mostrar pra vocês como é simples
fazer isso apesar de ser uma análise um
pouco mais complexa e desses dados você
pode extrair insights pensando já em
como criar as variáveis para as suas
análises quantitativas
então usando aquela base de dados e
aquele pedaço de código padrão para
carregar os dados do quanto modo bovespa
a gente viu na outra aula como a gente
trabalha melhor com os data frames e
hoje eu vou criar uma análise bem
simples aqui pra mostrar pra vocês essa
primeira história
vamos criar uma variável aqui que acho
que vamos chamar de medida do tamanho do
do kingdom
ou seja eu ou simplesmente pegar vou
criar uma variável aqui dentro da frame
bvsp chamada corpo
então eu escrevo aqui o nome da variável
eu quero faça atribuição que é o corpo
do kindle nada mais é do que
o fechamento - um valor de abertura
quando a gente executa esse comando aqui
ele vai criar pra gente essa nova maria
você vê que agora que ao invés de seis
nós temos sete com o nosso corpo
ajustado valores positivos ou negativos
dependendo do dia
vamos pegar a função o samba ele pra
gente tirar um insight
o primeiro insight dessa variável corpo
lembra que eu executei na anterior ação
maricón todo data frame eu posso a
executar a mesma função pegando uma
variável apenas se aí eu não preciso ter
aquela poluição se eu não quiser
analisar os outros dados então quando
pega função corpo eu tenho aqui aquelas
estatísticas padrão e eu tenho aqui uma
informação que eu vou querer pegar paulo
de hoje que é eu vou dividir essa função
corpo ou melhor dizendo essa variável
corpo do tamanho do kindle e você
paralela entre aquelas que são maiores
que 600 e menores que 600 porque 600 uma
análise arbitrária só que eu estou
fazendo pra te dar um exemplo e eu pego
aqui o terceiro
então o que nós vamos fazer eu vou usar
a função que eu mostrei pra você já doe
fiel se não vou fazer aqui bvsp corpo
jogar aqui dentro mesmo da da mesma
variável pra não criar ou melhor vamos
criar uma outra variável chamar corpo
categorias ou categorias
por que por que eu vou fazer o seguinte
se então o meu bebê sp corpo for maior
do que aquele número 600 ali eu vou
chamar isso de então vamos colocar aqui
terceiro com a grande senão eu vou
chamar é menor por exemplo do que o
terceiro o quadrante aqui ou melhor
dizendo o terceiro quarto eu criei a
minha variável corpo categorias vamos lá
no rio de novo você já tenha aqui
certinho pra que serve esse tipo de
análise
eu vou fazer uma mesma análise desse
tipo só que com um
lume vou repetir aqui então a função
samary vou colocar o volume e você vai
entender certinho porque eu estou
fazendo isso vamos pegar o mesmo
terceiro quartil ali para o volume então
vamos copiar e colar aqui para ser muito
fácil
só que ao invés de corpo categorias eu
vou colocar aqui volume categorias e
invés de medir o tamanho do corpo do
tamanho do volume vou pegar que o valor
do terceiro artigo e aqui vou colocar
ver e viver só para substituir vamos
colocar aqui até melhor colocar cd corpo
a gente fica bem claro que quer dizer
quando executo aqui novamente
acrescentei mais uma variável você vê
aqui não invadir a mente agora você tem
nove e agora vamos fazer a primeira
análise com a função nova download hoje
que é a função table quando executar a
função table que ela vai fazer
ela vai fazer o cruzamento dessas duas
informações que eu vou escolher no caso
eu quero tentar entender o
relacionamento do meu volume categorias
da vírgula o mesmo bvsp do corpo
categorias a aaa e isso vai trazer o que
ele vai me trazer a conta de quantas
vezes eu tenho essa informação cruzada
aqui então ele vai me dizer que 249
vezes eu tenho acontecendo um volume
menor que aquele terceiro é quartil e um
corpo também menor do que aquele
terceiro quartil e aí você começa a
entender as proporções de como o seu
data frame está distribuído ou como
aquelas características estão
distribuídas além do legal mas esse
número inteiro às vezes não diz muita
coisa perfeito não diz muita coisa como
eu posso trabalhar então com os números
relativos a gente pode usar uma outra
propriedade que é a chamada função
próprio table que é onde eu vou pegar as
proporções daquela tabela
só que eu tenho que passar a tabela ok
eu criei essa primeira tabela aqui na
linha 32 como tudo
eu posso atribuir uma variável certo
então vou criar uma variável tabela onde
eu vou passar essa informação do table
aqui quando você vê e executar aquela
tabela você vê que ele repete exatamente
o que a gente tinha na função toda
porque isso economiza linha de código
onde eu faço aqui o próprio table e ele
vai me dar a proporção em relação ao
percentual da base ou seja a minha base
em 437 observações nas quais 3 58% está
aqui dentro de si desse primeiro
quadrante aqui que é um volume é mais
baixo do do terceiro partiu e um como um
tamanho do corpo também menor que o
terceiro quartil legal as coisas começam
a ficar mais claras
eu também posso fazer essa própria hbo
de duas outras maneiras
a primeira é deixa o solo está aqui pra
vocês que aqui é a proporção proporção
total da da base eu posso fazer
a proporção por linha da base como assim
leandro
o que eu tenho que mudar você coloca
aqui próprio tempo tabela 1,1 significa
que você está pegando assim a proporção
por linha quando eu executo você vê que
eu pego por linha ou seja a soma não é
mais de toda a tabela dando por 100% da
sua memória da linha dando 100%
isso traz a informação referente ao
volume que é o que a gente escolheu pra
tá aqui nessa primeira coluna ou seja
77% das vezes onde eu tenho esse volume
menor
eu tô aqui um com o corpo do câmbio
também menor senão eu voltar aqui desse
outro lado eu também posso a não quero
analisar pelo volume que era analisar
pelo corpo então inveja da gente fazer
proporção por linha
você já pode inferir que a gente vai
fazer então a proporção por coluna e
ainda de um eu coloco 2 que a minha
informação da coluna você vê que agora
soma pra dar um percentual ela passa a
ser aqui na vertical além do legal
começa a ter uma noção e mais ainda não
entende por que que eu vou usar isso
pois eu vou mostrar mais complementos
sobre essa função porém aqui você já
pode começar a pensar poxa eu posso
criar categorias e variáveis para
modelos como eu disse no começo da alba
como se identificar percentuais onde eu
tenho uma chance maior de ter uma alta
uma baixa onde tem uma inversão na
tendência fazendo esse tipo de análise
e é pra isso que você faz essas análises
para pensar pra ter os insights você vai
jogar isso como categorias como novas
variáveis lá dentro do seu data frame ao
que lendo mais claro porém esse número
ainda vai número quebrado aqui como eu
deixo esse número um pouco mais arrumado
parecido com a porcentagem que a gente
conhece muito simples você pode usar uma
função chamada round que é tem
praticamente aquela mesma função do
arredondado excel onde eu vou passar
como hound vamos pegar aqui por exemplo
a proporção por coluna porque eu vou
arredondar isso quer multiplicar por 100
para transformar esse número aqui no no
formato percentual que a gente conhece e
eu quero pegar duas casas depois da
vírgula
então coloque outro parâmetro 1,2 quando
o executar
aí agora tem até uma proporção bem mais
arrumadinha porque a visualização de
dados também é uma coisa importante
beleza pessoal
reveja essa aula mais vezes e entenda
muito bem esses conceitos parece um
pouco complicado mas na verdade eu
queria aqui com vocês praticamente o
conteúdo principal da aula foram quatro
linhas de código
lembra que tudo não é recente é muito
simples basta você entender o conceito e
começar a aplicar teste pra outras
idéias que você tenha e não hesite de me
mandar nenhuma dúvida que possa aparecer
no meio do caminho
beleza pessoal um grande abraço e até o
próximo vídeo tchau tchau
[Música]