# Análise dos dados da Covid19 - Parte 1/3 - Prof. Dr. João Igor

- **URL:** https://www.youtube.com/watch?v=aZTJd0y0KDw
- **ID:** aZTJd0y0KDw

## Transcrição

e aí
o olá meus amigos seja bem vindo meu
nome é joão igor eu sou professor de
análise de dados da data consagrada quem
quiser conhecer nosso trabalho segue lá
no instagram por gentileza amor
e essa aula que eu vou trazer para vocês
hoje é direcionado para quem deseja ter
a formação de cientistas de dados mas
não sabe muito bem como é que funciona
então eu vou então eu elaborei essa alma
bem prática sobre o assunto que tá em
alta que é o coronavírus nessa aula
prática nós vamos estudar como é que tá
acontecendo o aumento do carro aumento
dos casos no coronavírus a nível
internacional e no final da aula mas nós
vamos tentar prever quando é que vai
haver o achatamento da curva aqui no
brasil ok pessoal pois apertem os cintos
que hoje vai ser água vai ser muito
legal
o primeiro eu peço que vocês baixem é o
banco de dados que está no site do
google nesse link só colar esse esse
link no navegador de vocês que vocês
podem ter acesso inteiramente grátis a
partir depois do cadastro no banco de
dados que eu vou estar utilizando ok a
primeira coisa pessoal que eu passo para
vocês é carregar e as bibliotecas juiz
de extra gg plot a terra dplyr as
funções que nós vamos utilizar nesse
tutorial todos hoje está nesses pacotes
ok pessoal primeiro eu vou utilizar a
função 7w dele que é sete work diretório
para sinalizar po r em qual pasta o
nosso banco de dados está salvo no meu
computador eu vou salvar o banco de
dados nesse diretório e
14 ok agora eu vou fazer a leitura do
arquivo csv para os dados do passo dos
pacientes que recobrar que recuperaram
sua saúde os pacientes que morreram e o
número de pacientes que tinha que foram
confirmados pessoal eu vou visualizar
com a função viu é o nosso banco de
dados como é que o nosso banco de dados
está organizado
o primeiro o estado segundo o país
quarto terceiro quarto é a latitude ea
longitude daquele país ou daquele estado
pertencente àquele país por exemplo
austrália ele trouxe vários estados da
austrália é você está consegue enxergar
e a partir da quinta coluna é o número
de pacientes confirmados começando do
dia 22 de janeiro de 2020 até cinco de
mayo de 2020 estão enxergando e o banco
de dados têm o mesmo formato só que me
traz para banco de dados de pacientes
confirmados que vieram a óbito e
pacientes que se recuperaram ok pessoal
a primeira coisa que eu vou fazer é
cálculo alvo é total
o que vale do primeiro dia até o último
dia do nosso data certa deixa eu limpar
aqui limpei contra o l de leão para
limpar eu temos aqui o dia primeiro até
o dia último ok vamos aqui ver que nós
temos 105 dias de jogo de comer é tam
nós estamos utilizando a função aécio
ponto de que indica que nosso banco de
dados está a salvo no formato data aqui
ó data ok a dimensão é 75 né perdão não
é dimensão é comprimento já que nós
estamos trabalhando com o vetor é deixa
eu apagar aqui que veio duas vezes ok e
aqui eu tô acusando o formato do data
frame estou aumentando a precisão do
nosso banco de dados ok
olá pessoal o que é o o primeiro
problema que nós temos que enfrentar é o
seguinte
e deixa eu visualizar o banco de dados
de novo vocês estão conseguindo enxergar
por exemplo o afeganistão tem só os
dados do afeganistão só os dados da
albânia só que a austrália tem o país e
tem os estados que formam aquele país de
maneira semelhante para o canadá tem os
estados do canadá você só consegue
enxergar e dentre outros países
eu falo que quero fazer por exemplo eu
quero somar os números de casos em todos
os estados da austrália e falar que o
saldo total da austrália ex vocês vão
conseguir enxergar eu quero deixar a
mesma granulometria eu quero dar número
de casos por país eu quero eliminar os
estados para isso utilize a função de de
ply eu quero números com números
confirmados por país e o sumário o
sumaré soma pessoal o que é que eu tô
fazendo eu quero fazer esse procedimento
para casos confirmados eu quero fazer
isso que você dimento para o número de
mortes e quero fazer esse procedimento
para o número de pacientes que
recuperaram vamos ver como é que fica o
nosso banco de dados depois dessa depois
de nós aplicar
a função
e lembrando o pessoal que eu vou estar
disponibilizando o banco ou o script
para vocês ok o afeganistão ok como nós
não temos estados ele não fez nada mas
por exemplo austrália eles tomou todos
os todos os
em todos os casos de todos os de todos
os estados da austrália e colocou em
apenas uma linha ok pessoal esse comando
que eu que a gente fez antigamente foi
para isso foi passou mal número de caso
para cada estado e colocar o saldo no
nome do país ok vamos calcular a
dimensão a dimensão nós temos 108 187
linhas que é o número de países com 106
colunas e no caso é o nome do país e 105
datas de monitoramento ok pessoal a
primeira coisa que eu quero fazer com
esse banco de dados do meio informação
eu quero extrair desse banco de dados
e eu quero ver o husky e o que é o husky
eu vou pegar a primeira coluna que é o
nome do país ea última coluna que é o
número de casos confirmados número de
mortes e número de pacientes que
conseguiram recuperar a saúde e vou
pegar apenas a primeira e a última como
é que eu tô fazendo isso deixa eu
mostrar para vocês como é que fica
eu não consigo enxergar que eu peguei só
a primeira e a última coluna que é o
número do é o nome do país e o número de
casos na última data de coleta e eu tô
colocando em ordem alfabética dá para
enxergar só que eu não quero em ordem
alfabética colocar em ordem crescente
para isso nós utilizamos a função order
para cá que eu tô fazendo isso pessoal
eu tô fazendo isso que eu quero ver a
ordem de gravidade por exemplo é o
número de casos confirmados os estados
unidos tá bem na frente não é com ethan
o milhão e 200 mil casos seguido da
espanha da itália do reino unido da
frança da alemanha da rússia turquia e
aqui temos no brasil o que pessoal vamos
ver agora o número de casos de morte é
e os estados unidos lá na frente com 71
mil óbitos seguidos do reino unido ok
pessoal e aqui número de casos
recuperados é estados unidos espanha ok
pessoal é vamos lá agora eu quero ver o
ranking o brasil tá num site 9 dá um
total de 187 para os casos confirmados
no brasil tá 181 para o número de mortes
de 187 e por último casos recuperados o
brasil tá 179 num total de 18 7 tem
pessoal ea dimensão é 87 como usar o
meia como nós já havíamos mostrado pois
é isso pessoal a estatística descritiva
básica desse problema é esse
hoje eu vou estar terminando a primeira
parte da aula aqui para não ficar muito
extenso ok na próxima aula vai ser um
pouquinho mais interessante fazer uma
recapitulação deixa eu botar um jogo da
velha aqui o pai de carro nós acabamos
aqui aqui é onde nós damos dar um hoje
nosso banco de dados aqui nós estamos
carregando os pacotes aqui nós estamos
mendo nosso banco de dados é que nós
estamos visualizando nosso banco de
dados aqui nós criamos um vetor time com
a primeira data até a última data de
coleta aqui nós que não estamos
calculando as uma nós estamos eliminando
os estados nós estamos dizendo que o
país leva a soma de casos de todos os
estados pertencentes aquele país para
nós fizemos esse pau número de casos
confirmados número de dados de morte e
o número de de pessoas que recorda que é
a viram né sua saúde recuperado sua
saúde perdão é que nós visualizamos o
nosso banco de dados novo que tem países
que no caso é a soma dos casos por
estados do primeiro até última data
demônio pagamento
e aqui nós temos calculamos um ranking
né pegamos a primeira e a última coluna
e calculamos em ordem crescente nós
temos que o brasil ocupa é se esse antes
1798 1797 brando que está em ordem
crescente e aqui nós temos a dimensão do
nosso banco de dados 187 que é o número
de países por 106 no caso a primeira
coluna é o país e as demais são os
números de casos por
e por dia começando primeiro perdão
começando do dia 22 de janeiro indo até
os cinco dia cinco de maio ok pessoal os
dados são bem recém e é isso pessoal
próximo a alma nós vamos começar com a
parte de graça ok eu espero vocês na
próxima aula espero que vocês tenham
gostado ok pessoal grande abraço tchau
[Música]