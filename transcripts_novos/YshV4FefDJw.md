# Aula 08 – Utilizando médias móveis - Trading com Dados

- **URL:** https://www.youtube.com/watch?v=YshV4FefDJw
- **ID:** YshV4FefDJw

## Transcrição

e vamos dar continuidade ao uso da conte
morde agora
nós vamos colocar um outro gráfico
parecido com esse só que não formato
simples Então imagina que você não quer
trabalhar com quem você quer um formato
simples como você pode fazer pode fazer
uma forma bem parecida com a gente vinha
fazendo antes
é só que dessa vez a gente não tá
trabalhando né com o deita frente tá
trabalhando aqui terceiro né uma um
objeto XTR eu vou pegar esse objeto ou
passar aqui dentro das vezes lote
e o estéticos que eu vou colocar aqui
dentro vamos lá dar uma olhada nele
percebam que a data pessoal tá no
próprio índice do do do XPS né a data
não tá uma coluna específica só que eu
vou fazer para conseguir trazer a data
eu vou usar um ainda tá do próprio
chispita é isso vai estar aqui no meu
e no meu estéticos e eu também vou
colocar a coluna correspondente ao preço
de ajuste né o preço ajustado que nesse
caso aqui é a coluna e isso ou Nascente
Então tá correto perfeito Daí vamos
adicionar algumas outras características
ao nosso Vamos colocar um de omelete
Laine eu quero dessa vez vou colocar um
Dark Blue
e se vocês quiserem adicionar um título
também eu vou colocar um digitar e tô
colocar
a cotação de veg-d G1 de Janeiro 2020
vamos ver se daqui dá certo
é feito então era isso que a gente
queria né percebam que aqui é
essencialmente a mesma coisa Eu só mudei
o formato do gráfico tá PSOL é
basicamente a mesma coisa então vamos
agora para construção das médias móveis
e como que a gente pode construir
primeiramente né a gente vai pegar esse
xts aqui vamos adicionar informação de
médias móveis tanto médias móveis de 10
períodos médias móveis de 30 períodos
depois a gente vai pegar essa informação
de médias móveis e vai colocá-las no
Então vamos lá
e a primeiramente acho que vale a pena
mencionar uma opção que vocês podem ter
para manipular os dados de ações É uma
opção que eu uso bastante para filtrar
imagina que você pegou o sal de jegue no
intervalo muito grande só como é que
você pegou 56 anos e aqui você quer
reduzir estou aqui antes de fazer as
médias móveis você quer reduzir esse
intervalo como você pode fazer
e você pode usar a função sobre CEP
Ah tá
nós vamos pegar aqui os dados de WEG
quer que eu vou fazer
e pegar o índice não porque o índice
Onde tá a própria data e aí eu vou dizer
para ele que eu quero a partir de uma
data específica ao invés de pegar tudo
isso daqui Suponha que eu quero a partir
do final de Fevereiro que amo de mais ou
menos a gente começou a sentir ali os
efeitos da pandemia no mercado
financeiro Então eu vou colocar aqui
2020 fevereiro final de Fevereiro ali
mais ou menos dia 20 né então vou criar
reparem que eu criei aqui outro XPS ou
até abrir aqui um pouquinho para te ver
creio aqui um outro xts
Oi e ele começa exatamente um dia vinte
de Fevereiro 2020
e na até hoje então a gente fez 17 né a
gente fez um filtro nos nossos dados é
isso daqui que eu vou usar a partir de
agora tá que a gente trabalha com
intervalo de dados ligeiramente menor
Vamos então
e começará a construção das médias
móveis para a gente tirar as médias
móveis eu vou usar essa função aqui ó
home tá que vem da biblioteca Zoo vocês
tiverem dúvidas começa a função Sona
exatamente convido vocês aqui olha
a ajuda dela ela fala Exatamente isso
funções genéricas para calcular a a
médias né máximos medianas etc Então
essa condição que a gente vai usar que a
gente vai passar
e dentro dela eu vou especificar a
coluna de referência quais dados ele vai
usar para criar as médias móveis que no
caso aqui da WEG que a gente tá
trabalhando
Essa é a coluna seis correto dessa
coluna que eu quero criar a média móvel
de 10 períodos e a média móvel de 30
períodos
bom então eu quero a partir da coluna
seis média móvel de 10 períodos
o caso a ele encontre o mi5 você
determina qual o tratamento que ele deve
ter e online
the right One
e para especificar a se o índice o
índice do resultado deve estar alinhado
à esquerda ou à direita né frente a a
janela das observações beleza com isso
eu crio a média móvel de 10 períodos
aqui para criar uma média móvel 30
períodos só que deve ser 30 e agora
vamos dar nomes né então chamado de
média móvel de verg de 10 períodos vai
ser isso daqui
a média móvel de Jegue para 30 períodos
vamos só dar uma conferida para ver se
está tudo correto
e o prédio está tudo correto Então vamos
executar isso daqui então aqui ó ele já
criou objetos contendo as médias móveis
o que é que a gente precisa fazer agora
eu preciso voltar no xts de velho
tivesse dado dados velho infiltrado eu
vou criar uma coluna nele
e olha essa coluna vai receber o nome né
a coluna vai receber a própria
informação da Média móvel Então esse
daqui né a nova coluna que eu estou
criando vai ser igual a própria
informação daquela média móvel veja para
10 períodos vou fazer isso para 30
períodos
e também vamos dar uma olhada aqui em
dados pede filtrado
Eu percebo que as colunas com informação
de médias móveis já está aqui qual que é
o nosso desafio nosso desafio
basicamente agora pô tá isso também
então vamos colocar tudo isso não grava
mais uma vez o Jackson veja plot esses
aqui são os nossos dados Vão passar aqui
o step e o nosso x vai ser o index a
gente já viu porque vai ser o index an
a beleza temos o nosso x o que é que a
gente vai fazer agora Então pessoal
vamos adicionar linha pulinho né então
geometria online
é a nossa primeira linha vai ser coloca
aqui esthetics y = a nossa primeira
linha vai ser o próprio preço de Jegue
que a gente já tem aqui opressores tosa
e vocês podem terminar né a legendas
daqui vai ser Vamos colocar preço de
weg3
E aí
eu estou com a sensação que os
parênteses não é aqui para dar o dia
aqui
Ah beleza mas agora a gente vai
adicionar as linhas das médias móveis
então o y aqui não é 6
o Wilson aqui vai ser a primeira média
móvel que é dez de que a gente vai
colocar
a média móvel de 10
em períodos
é da mesma forma a gente pode copiar
esse daqui colar embaixo para fazer a
média móvel de 30 períodos
Ah então beleza temos o nosso Y que
basicamente isso tá pessoal é
essencialmente isso a gente vai
adicionar algumas características no
gráfico para que ele fique à visualmente
mais mais atraente mas é essencialmente
isso não é que característica a gente
pode adicionar ao nosso gráfico aqui no
local mais eu vou adicionar um rótulo no
x vou adicionar um rótulo no eixo Y
também preço
E aí Vocês poderiam tinha outras coisas
aí fiquem à vontade mas fica com
exercício aí para vocês alterar em cores
alterarem os padrões visuais mas é
essencialmente isso como que o pessoal
usa isso na análise técnica né Quem
segue análise técnica aí para fazer suas
operações no mercado financeiro não vai
encher eles acreditam que quando a
cruzamento de médias móveis esse esse
cruzamento pode ser um indício sobre o
comportamento do preço daquelas são tão
Vou tentar dar um exemplo aqui tá
e essa média móvel Verde aqui ela é
demais períodos Ela é maior ela é mais
suave somente quando o pessoal ver uma
média móvel que é de menos períodos o
média móvel menor cruzando essa média
móvel maior isso daqui seria um sinal de
venda então provavelmente aqui eles
falaram para você vender essa ação não
sou especialista análise técnica
obviamente não Tô pretendendo aqui a
dizer o que você tem que fazer mas é
mais ou menos esse raciocínio é muito
bacana a gente começar a ver que vocês
podem usar a programação para ajudar a
ajudar vocês a tomar decisão né Na hora
de investir nenhum motivo a hora a
melhor hora para comprar meia hora para
vender Então dessa forma vocês tem aí
uma ferramenta muito bacana que vai
ajudar na análise técnica
e para a gente terminar o uso da
biblioteca continua Hoje eu queria só
apresentar mais algumas funções que
facilitam bastante a nossa vida
comumente no mercado financeiro a gente
quer calcular retorno e risco como que a
gente calcula o risco normalmente
através da volatilidade né que não a
gente representada pelo desvio-padrão
tem funções prontas na biblioteca
continuo onde para fazer isso então por
exemplo se vocês quiserem os retornos
diários dessa são aqui vocês poderem
usar a função dele return e aqui dentro
vocês passariam ação que vocês estão
estudando no momento o causa que é dados
de Weg
e esse você executa isso daqui ele vai
dizer qual que foi o retorno né Com qual
qual foi o rendimento da ação de velho
de um dia para o outro então se vocês
olharem por exemplo aqui no último
pregão Ele tá dizendo que houve uma
queda bem pequena né aqui por exemplo o
preço da WEG subiu pouquinho mais de
dois por cento então aquele retornou
e os retornos diários Será que a gente
consegue outros períodos consegue da
mesma forma se você quiser se os
retornos semanais gostaria usar a função
wikle retorne monstro de semana a semana
é só que mensal a gente consegue
consegue na mesma forma Então manda ele
Victor altamente Foram poucos meses né
então a gente tem abril maio junho você
tem aqui O Retorno de velho por exemplo
nesse último mês tá bem expressivo
Observe que quase 25 porcento se a gente
quisesse O Retorno anual da mesma forma
tá então tem a função ele retorne E aí a
gente tem o rendimento de mais de
setenta por cento e se eu quiser o risco
vamo Aparecida você pode pegar a função
SD né que a Standard deviation desde o
padrão e calcula a no preço ajustado
obviamente tem valores me sim né Tem
alguns valores faltantes e pra que a
gente conseguisse calcular isso você
precisaria de alguma forma se livrar de
e aqui de uma forma bem fácil tá mais
prefeito da gente ver como calcula né eu
usei a função para omitir Os Mirins
então Enia Ponto Mix Aí percebo que essa
aqui esse aqui é o desvio padrão é
obviamente tem formas mais precisas
formas mais corretas a gente calcular o
risco tal pessoal mas aqui só para
efeito de ilustrar mesmo a facilidade
para a gente não erre eu calculei dessa
forma
E essas duas bibliotecas que a gente
idiota até agora a Bete Bete se envolver
a quanto molde mais uma vez nos permitem
que trazer dados de negociação de ações
né dados do preço a preço de abertura
preço de fechamento preço máximo o preço
mínimo e volume dessa forma a gente
consegue a ter mais dados Tem mais
informações para ajudar a gente na hora
de fazer uma análise técnica por exemplo
calcular correlação criar um portfólio
novo e compará-lo ao índice de
referência Só que até agora a gente não
viu dados fundamentalistas que a gente
viu lá no início do nosso tutorial que
também são importantíssimos para isso eu
vou apresentar uma outra biblioteca para
vocês que a última aqui no nosso
tutorial que a mulher DF deita que traz
dados fundamentalistas e eu vou
apresentar lá na próxima sessão então
Até já é
E aí