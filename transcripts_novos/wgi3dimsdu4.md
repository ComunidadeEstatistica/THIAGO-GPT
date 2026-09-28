# Aula 01 - Machine learning - Introdução a Regressão Linear em Python

- **URL:** https://www.youtube.com/watch?v=wgi3dimsdu4
- **ID:** wgi3dimsdu4

## Transcrição

olá nessa aula
vamos aprender sobre como funciona a
regressão linear a regressão linear é um
algoritmo de marcha e lane usado para
fazer predições a regressão linear
utiliza um algoritmo do tipo aprendizado
supervisionado
esta é uma técnica que consiste em uma
equação linear que usa valor de entrada
para predizer valos de saída
essa equação utiliza o coeficiente que é
aplicado que são aplicados para predizer
saídas regressão linear trabalha com
dados numéricos apenas os coeficientes
também pode ser chamado de pesos e esse
é o nome que a gente vai adotar
nem todo o curso os pesos são
atualizados conforme a função que
minimiza os erros então com a regressão
linear o pessoal é um algoritmo do tipo
aprendizado que utiliza aprendizado
supervisionado né
então essa técnica a partir de uma
equação linear que utiliza valores de
entrada que seriam as nossas fitness né
a gente quer predizer valores de saída
que seria valores reais né valores das
nossas classes
então essa técnica é muito utilizada
quando a gente quer para dizer valores
de imóveis
a gente quer predizer valores de ações
da bolsa de valores e algo assim
tudo que envolve a predição de valores
reais
a gente pode trabalhar com a regressão
linear
lembrando que a regressão linear
trabalha com dados numéricos apenas por
conta das equações matemáticas que ela
utiliza pra a ajustes dos pesos e preto
são a gente vai ver mais detalhes como
como funciona a frente vamos ver aqui
uma representação de como essa regressão
linear funciona então imagine que os
dados de entrada são x 1 x 2 x 3 no
valor de saída é o valor isso é a
variável isso vamos usar essa mesma
notação né de variáveis x 1 x 2 x treze
e saída que seria às nossas classes
o vamos representar com a variável isso
teremos a estrutura como o seguinte x 1
x 2 x 3
é igual a isso né então 6 x 1 x 2 x 3
são as nossas entradas ou seja os nossos
vítimas né
e isso é a nossa classe
ok queremos uma função que estima o
valor de y
ou seja a gente quer um função que acho
que é aprenda a predizer o valor de itu
para novos exemplos onde não temos esse
valor ou então seja a partir dos dados
de treinamento a gente vai treinar
algoritmo ele vai criar um modelo que
vai aprender a predizer o valor de y
ok a regressão linear utiliza os pisos
para aprender uma representação que se
aproxime o máximo dos dados de
treinamento então ou seja com os pesos
com os dados de entrada que a gente tem
x 1 x 2 x 3 e o valor de y é que seria
às nossas classes
a gente vai usar esses dados para criar
um modelo que crie que aprenda criar uma
representação não é que se aproxime o
máximo dos valores de treino então ele
aprende através dos dados de treino nem
a predizer valor de y e vai mensurando
isso né vai bem vai ajustando os erros
dele até que ele consegue criar uma
representação modelo que uma
representação que consiga predizer valos
de saída para o exemplo anterior para
cada filme teríamos um piso associados
que são os coeficientes que a gente
falou anteriormente aqui eu vou tratar
os coeficientes com peso às mais simples
de entender então para cada filho gente
tem três filhos né features x 1 x 2 x 3
a gente teria os pesos pesados o p1 p2 e
p3 você fala comigo assim poxa mas
fizeram porque fizeram né não seria só
pergunta e 2003 não perder 0 é um peso
usado para controlar a direção da reta
direção da nossa regressão linear
então a gente vai ver mais na frente que
o peso 01 peso que inicia com valor né
ele vai ajustando à medida das
interações p1 p2 e p3 são pesos que só
associada às nossas fichas estão para
cada feature a gente tem um peso
a fitch x1 tem um peso de 1
a fitch x 2 são peso psp2 ea fitch x3
tem um peso pt três então já falei é que
o peso pp 0 utilizar para controlar a
direção da reta um valor fixo é que ele
vai ele inicia a gente consegue definir
o valor de zero ea medida das interações
esse valor vai se ajustado os pesos são
aplicadas aos dados para prender um
representação dos dados de treino então
à medida que a gente treina o algoritmo
o que com o modelo vai fazer é
multiplicar os pisos em aplicar os pisos
aos valores de treino aos valores das
nossas fitness pra criar uma
representação que é uma forma de
aprendizado para predizer novos valores
então o que a gente tem o exemplo e 0
mais de 11 vezes x1 mais p2 vx2 mais p 3
vezes x3 é igual a y&amp;r ou seja um valor
é igual valor preditivo no nosso modelo
o resultado de saída é então culpa
comparado ao valor real de y
essa é a diferença é chamada de erro de
impressão
então como a gente disse anteriormente
aqui em cima da nossa classe pessoal
então isso y é o valor real dos nossos
dados y ie é o valor que o nosso modelo
a diesel
ok então nosso modelo para dizer um
valor chama coloquei que tem da variável
e y é né
mas o valor real né é o valor que está
dentro de y que a gente precisa fazer é
encontrar a diferença desses dois
valores que seria o nosso e vamos em
frente
vamos a um exemplo pra vocês entenderem
como funciona a regressão linear aplicar
dados de mercado financeiro
nada de de valores de algumas ações
imagine que o nosso objetivo é usar
regressão linear para predizer o valor
de fechamento da ação da petrobras em um
dia específico
então temos os seguintes dados
queremos prevê o valor de fechamento do
dia
então a gente tenha variável gente tem o
valor de abertura que é 12 30 o valor da
máxima do dia 12 35 o valor da mínima do
dia 12 e 20 ea gente quer predizer o
valor de fechamento do dia o valor que a
ação vai fechar no dia né vai finalizar
o dia d de operação com esse valor
os dados de abertura máxima e mínima são
dados que temos então aplicamos a
regressão linear para tentar predizer o
valor de fechamento
aqui a igreja não linear aplica os pesos
nos dados como a gente falou
anteriormente que seria 10 p 1 p2 e p3
imagine os valores dos pisos a seguir
então a gente tem um valor de 0 a 1
o valor de p1 e 0.7 o valor dp 20.06 o
valor dp três seria 0.08 esses são
valores aleatórios pessoal
só a título de exemplo mesmo que a gente
vai fazer é aplicar os valores a equação
né anterior
então a equação anterior diz que a gente
prende o valor a gente tem que colocar o
valor de 0 mais de um vez x 1 que seria
o nosso preço nem empresa abertura do x
1 né
voltar aqui x 1 seria 12 30 x 2 seria 12
35 e x3 cc 12 2010 mais de 11 vezes x1
mais p2 vezes x 2
mas p 3 vezes x 3 com isso a gente tem
um valor de 0 1 pp 10.7 vezes 12 30 é
que a nossa abertura confirmar que nossa
abertura 12 30
mas 0.6 é o valor de p2 vezes 1235 que
dos 35 ao valor de da máxima do dia mas
0.08 que é o p3 vezes 12 2012 e 20 ao
valor de a mínima pt isaac 008 ok
com isso a gente tenha resultado de 12
55 o resultado de pressão nosso modelo é
pra dizer o valor de 12
85 ser o nosso y e seja lo de modo
modelo 1255 voo um valor que o modelo
para diesel e seria o valor de
fechamento da ação pedida pela regressão
linear então nosso modelo de regressão
linear prevê esse valor
o próximo passo é melhorar o idp edição
o valor real do fechamento do dia foi 12
33
então temos que calcular o erro em que
seria se eu seria a diferença do valor
predito 12 55 eo valor real 12 33 e
ajustar aos pesos novamente ou seja teve
um erro né
a gente precisa entender o valor desse
erro é calcular o valor desse para
reajustar os nossos peso e isso a gente
vai fazer é a agressão vai fazer de
forma interativa a cada linha do seu da
de treinamento ou seja vai fazer os
cálculos o modelo vai fazer os cálculos
vai comparar com dar real vai calcular o
erro e vai reajustar os pesos e fazer o
carro novamente até que o erro mingo do
seu modelo eu seja o mínimo então vamos
ver agora como funciona essa atualização
dos pisos ok
e esse processo é feito durante todo o
processo de treinamento no algoritmo
então após a nossa predição seja se a
gente fosse protásio uma luz que não
haja regressão linear previu
a gente tem uma reta ou seja um valor
pronto um valor que outro valor que onde
essa reta seriam os ossos nossos valores
preditos né 1212 alguma coisa 2.1 talvez
2.8 até 12.8 que nem seria nossa reta
nossos alunos preditos e os pontos aqui
pessoal serão os valores reais então que
seria um erro nosso e seria a diferença
entre o valor real valor preditivo a
diferença entre o valor real vôo predito
e assim por diante e foca a gente vai
ajustando é uma regressão lendárias e
ajustando essa reta para ficar mais
próxima possível do cdos dos dados reais
né
vamos em frente
pra fazer a atualização dos pisos a
regressão linear utiliza um algoritmo
chamado
gradin de centro esse algoritmo é usado
para minimizar o erro dos pesos do
modelo
então esse algoritmo que é o responsável
por fazer a atualização dos pesos
através da minimização desse erro
o objetivo dele é fazer com que os erros
sejam minimizados através da dos valores
que são recalculadas dos pisos gente vai
ver um exemplo entender melhor esse
algoritmo utiliza o erro médio quadrados
entre o valor preditivo o valor real
esse algoritmo utiliza todos os dados de
treinamento de forma interativa até o
menor possível
é preciso para metrix ao valor da taxa
de aprendizado
esse parâmetro controlo nível de
aprendizado a cada interação do
algoritmo o que essa taxa de aprendizado
faz é definir o nível de aprendizado a
cada interação então o usuário consegue
definir essa taxa de aprendizado de
forma que se o usuário definir um valor
muito alto
significa que você quer com o algoritmo
tente aprender o mais rápido possível e
tenha menos interações então seja você
vai
o modelo vai permitir fumar mais erros
em troca de menos internações em troca
dele vai convergir mais rápido vai
chegar ao final mais rápido porém ele
você está dizendo que você pra você
aceita um determinado tipo de um
determinado valor de quando a taxa de
aprendizado é muito baixo significa que
o ritmo vai aprender de forma mais lenta
ou seja ele vai inteirar sobre usar de
treinamento muito mais vai gerar mais
épocas ou seja vai gerar mais interações
porém ele vai ficar mais ajustado aos
dados de treinamento logo ele vai
permitir menos erros
ok vamos ver um exemplo para entender
como funciona um exemplo de como
gratidão é sempre funciona
imagina os seguintes valores o valor a
gente temos o valor de p1 tp 0 a 1
o valor de p1 e goza 0.9 o valor de x 1
é que seria nossa primeira filha revela
que seria talvez na cidade de abertura
1231 valor real dessa dessa instância
seria 12 3633
nossa equação agora seria vamos agora
jogar isso na equação assim então o
valor pedido seria yyy e desculpa é
igual a um mais peso e p1 vezes x 1 e
seria um mais 0.9 né que seria o p1 aqui
vem existe sun que seria 12 30 com isso
gerou valor de 12,07
o valor pedido foi 12 07 agora vamos
calcular o erro
o eu seria 12 007 - 2033
então a gente tem um ivh de 0 e menos 10
26 com ele de predição né
os pesos são atualizados para tentar
minimizar novos erros
vamos ver agora a atualização dos peso a
gente já encontrou erro na instância é
quem tem unhas de - 0 26 anos seja nosso
algoritmo período prévio 12,07
porém o valor real era 12,33
então a gente tem um yield - 0,26 com
esse erro a gente agora é atualizar os
peso para minimizar novos erros
então como é que funciona a atualização
de peso a partir de a para a taxa de
aprendizado vamos chamar de alfa
então lembre que eu falei que a gente
tem um valor que a gente tem que definir
quem é que a nossa taxa de aprendizado
vamos calcular esse padrão vamos
utilizar esse parâmetro né
vamos chamá-lo de alfa objetivo é
calcular um novo novo valor dos pesos
pesados pergunta é tão para alpha no
valor de 0.01 temos zero é igual a zero
o valor anterior - alfa vezes erro ao
valor de erro - que o valor de r - 0.26
ok então temos de zero ou a um que é o
valor de reserva - 0.01 que é o valor de
alfa que a gente definiu é nec vezes - 0
26 que o valor do euro que a gente
encontrou na sauna
anteriormente o ok o novo valor de
pesaro agora 0.25 com o novo valor de pi
zero vamos com alguma hora agora
calcular o valor de p1
o que seria o outro peso né a diferença
aqui é que agora o valor de entrada é
usado na equação pois o valor de p1 deve
ter influência no valor da fitch é
associada a ele
então o que acontece o vaio p 1 é um
valor é um peso que está associada a uma
feature pessoal neto associada à fitch x
1
então essa fitch x um valor dela é entra
na equação para atualização do peso
concorda porque esse peso ele associada
a um filho tão valor dessa feature tem
que influenciar o valor do piso nessa
atualização do piso
então a equação fica o seguinte valor de
p1 - alfa né vezes o erro vezes x 1 com
o valor da fischer fala o gp um é igual
a zero ponto 9 que é o valor de p1 e
definir lá no início valor de alfa 01 -
0,01 calor e ao funk - o erro que é -0
desculpa vezes - 0 26 que o erro vezes
12.030 que é o valor de x 1
logo a gente tem um valor de pergunta
0,93
ok então a gente encontrou o valor do
piso 0 e agora a gente tem um valor de
piso g1
com isso o grady decente vai atualizar
os valores no valor de 10 antes vamos
entender que o valor do que fizeram
anteriormente né
o valor de pesar ao ter a mente era um
toque
agora o valor de 0 10 ponto 25 certo eo
valor de p1 era 0.9 depois esse cálculo
o valor de 1 e 0 ponto 93
ok então com isso grande deficiente vai
atualizar vai inteirar sobre todos os
dados de treinamento e vai recalcular os
pesos em como a gente fez por peso e zé
pedro p 1
seria a mesma coisa o peso e dois por
peso p3
aqui eu coloquei só o plp um pano pra
ficar mais simples
a equação a gente entender de forma mais
rápida o grade é decente repete todo
esse processo a cada instância do treino
até que os pesos se ajuste com o mínimo
de erro
o grupo completo damos o nome de época
então cada vez com o ritmo interna sobre
todos a de treinamento e cálculos pesos
a gente dá um nome desse ciclo neste
ciclo é uma época a gente diz que foi
executado época ok então a imagem assim
nessa imagem aqui né e lúcio o processo
é possível observar que após várias
épocas se consegue chegar no ponto
mínimo de então imagine que aqui é o
nosso erro
ok à medida que a gente termina a época
um e se eu vim pra cá época dois agentes
chegou é will foi mudando até chegar
nesse valor
na época três ou seja depois de mais uma
interação de todos até a mim
a gente já consegue atualizar se e sei
para quê ou seja tem um valor de huck e
na época quatro ou seja na última época
né
ou seja ele convergiu significa que ele
chegou com ele um ponto mínimo
ok então a gente começou com erro aqui
né
vou atualizando foi interessante sobre
as apps
nesse exemplo na época quatro né ele
conseguiu chegar no valor mínimo de erro
com isso o algoritmo conseguiu chegar a
um valor mínimo de ele para de atualizar
os pesos é ele concluiu o treinamento do
algoritmo seja ele gera o modelo final
porque nesta aula vimos sobre os
conceitos da regressão linear nas
próximas aulas vamos aprender a aplicar
esse algoritmo um exemplo real
ok vejo você em conjunto e notebook
aberto
um grande abraço