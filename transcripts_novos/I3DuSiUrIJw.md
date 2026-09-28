# Análise dos dados da Covid19 - Parte 3/3 - Prof. Dr. João Igor

- **URL:** https://www.youtube.com/watch?v=I3DuSiUrIJw
- **ID:** I3DuSiUrIJw

## Transcrição

e aí
o olá pessoal sejam bem-vindos hoje nós
temos nossa terceira e última alma que
nós estamos analisando os dados do
comitê 19 essa terceira e última hora
pessoal eu quero trazer para vocês
é uma estimativa que quando é que nós
esperamos que esse pico chegue né nós
querem nós estamos interessados em saber
quando é que vai ser o achatamento da
curva que são complemento do logia que
eu escolhei para estudar paga três ver o
achatamento da curva pessoal primeiro
tem uma função eu tentei encontrar uma
função é do seguinte da seguinte maneira
fdx ond os seis é um tempo e o y é o
número de passe número de casos de
pacientes infectados aí no caso eu
busquei funções que conseguir ficar
lembrar esse modelo eu fiz para o brasil
e página porque é que eu descobri a
china porque o convívio de começou lá
então eu achei justo
e é isso que eu vi a china pessoal eu
calculei o data frame china deixa eu
apagar aqui deixa eu mostrar para vocês
a china tem dia um 22 de janeiro dia
dois dias dia dois dia três dia quatro
até o dia sete e cinco e aqui nós temos
o número de casos no dia ou no dia dois
até um dia 105 você só consegue enxergar
e o nome ei ss data frame de paciência e
tempo ok e para a mesma coisa eu fiz
para o brasil deixa eu apagar aqui
contra o l de nós não mesma maneira fiz
para o brasil
e aí
não dá para enxergar que eu tenho dia um
dia dois dias três até o dia sete e
cinco o número de casa ok pessoal aqui
white ponto csv é o comando para eu
salvar esse data frame china e brasil na
pasta que nós comendo lá em cima ok
pessoal pessoal vamos não como foi que o
procedimento pessoal tem um livro que
tem bilhões de funções o que foi que eu
fiz eu comecei a testar a função parece
comer uma função para escolher a melhor
função que que consegui se casar com o
nosso banco de dados eu tenho eu testei
várias e várias e várias funções a que
eu achei mais ok que conseguiu calibrar
o cuidado da china foi uma função
exponencial simples desse formato da
linha 540 dá para enxergar escolhida a
função pessoal que eu escovei na base da
tentativa e erro eu utilizei a função
nrs não ganha não não linear oeste
square square para calibrar os
parâmetros dessa função como é que
funciona aqui tem a função pacientes em
função do tempo eu dou um chute inicial
dos parâmetros para o banco de dados
china feito isso pessoal eu tenho eu
tenho uma função que eu chamei de galo
que é que tem esse formato vocês tão
conseguindo enxergar os parâmetros ao
ter 160 aí eu fiz isso e calculei um uma
sequência de um a105 que são os dias de
comédia do que vai do dia um até o dia
sete e cinco aí eu fiz a plotagem dos
dados de fato vocês não consigo enxergar
do dia0 ao do dia 105 aqui estão os
dados observados agora nós vamos
utilizar a função gauss que eu chamei de
gauss para o dia um até o dia sete e
cinco que horas que eu armazenei no na
variável é o
e vocês vão conseguir enxergar que a
função consegue casar muito lindamente
com os dados observados agora eu vou
calcular eu vou colocar os dados do
brasil em cima de azul pegar o vou botar
uma legenda
e eu quero pessoal vocês podem vocês
podem ver que a china a partir do dia
zero já começa a ter muitos pacientes
infectados já o brasil somente a partir
do dia 60 alguma coisa que o número de
pacientes ou para o instagram que a
partir do dia 60 alguma coisa que eu
começo até o aumento do número de
paciência ok pessoal pessoal eu tentei
calibrar a mesma função com os dados da
china só que eu utilizei os dados do
brasil só que eu não consegui convergir
a função porque porque eu descobri que
essa função exponencial é particular dos
dados da china eu não posso eu não
consigo calibrar os dados da função
exponencial utilizando os dados do
brasil então eu tive outro trabalho
gigante para caçar qual é a função que
consegue casar
e os dados do brasil é um testei várias
e várias e várias e várias funções eu
encontrei uma função que o nome da
função é família extreme essa família
extreme tem essa função que tem essa
cara y que aí usei lembrando que eu
substituí esse z aqui se eu consigo
enxergar aí o carro com e a função
extreme
oi vocês estão conseguindo enxergar que
eu calculei os parâmetros da função
extreme aqui tem a função aqui tem um
chute inicial e aqui tem o banco data
que eu utilizei que o brasil tem o y0tu
xc e tem o w vocês eu consigo enxergar
perto da um y0 xc-w e arco do caso é
mical com os parâmetros ok pessoal mais
uma vez nós vamos calcular sair com esse
de um a105
eu não consigo chegar e agora nós vamos
plantar e calcular a função por cima
pessoal deu para dar para dar para
enxergar que aderência é perfeita que
nós temos um casamento perfeito entre os
dados em picos com os dados observados
que nós temos um ajuste e mais que
perfeito aqui é isso pessoal quero que
vocês vejam que a função extreme de
alguma maneira conseguiu ajustar muito
bem nosso banco de dados agora eu vou
utilizar a função curva para fazer a
curva da nossa função aqui nós temos a
função e eu quero fazer a função do
intervalo de 0 a 300 deixa o executar
aqui
o hino amar nós temos os números de
pacientes no y e o x nós temos os dias
ver se eu conseguia enxergar pessoal e
agora nós vamos localizar o pico
e a partir desse vocês eu vou marcar
aqui as coordenadas desse pico é o dia
229 e nós temos 175.000 infectado o que
pessoal que foi que eu fiz eu calo
entrei a função extreme e fiz uns
transformação eu estou há por aí para
até o dia 300 você consegue chegar aqui
até o dia 300 e a partir disso eu fiz
uma estimativa e mais ou menos quando é
que vai ser o pico é considerando que a
função streaming consegue calibrar os
dados do nosso modelo ok pessoal fazendo
recapitulação rápida eu gerei o data que
proíbe china gerei o data porém brasil
fiz o ajuste exponencial para os dados
da china que nós temos
e esses dados china brasil onde a curva
vermelha é o dado exponencial da china e
os pontos azuis são os dados observados
o brasil e utilizando uma metodologia
parecida eu achei a função extreme que
conseguiu casar muito lindamente com o
nosso banco de dados e partindo do
pressuposto que essa função é válida eu
fiz a estimativa do dia um até o dia
traz é e tentei fazer uma estimativa e
quando é que vai ser o nosso pico você
só consegue enxergar as coordenadas de x
as coordenadas y e é isso pessoal eu
espero que esse mini tutorial em três
partes tenham despertado o interesse de
vocês pessoal meu whatsapp é esse meu
instagram é esse meu amigo edinho é esse
meu e-mail é esse se vocês quiserem
a mensagem mandar um e-mail com alguma
dúvida sugestão qualquer coisa que possa
sanar as dúvidas de vocês o então
acrescentar eu sou todo ouvidos ok
pessoal eu conto com o retorno de vocês
e lembrando e por gentileza parece que
vocês curtam a o instagram data ponto
saga porque pessoal foi um prazer muito
grande estar com vocês aí espero que
vocês tenham gostado grande abraço e
tchau
[Música]