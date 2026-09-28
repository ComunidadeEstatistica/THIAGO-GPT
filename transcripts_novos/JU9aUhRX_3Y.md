# Aula 1 - Números e vetores - Curso de R para Finanças Quantitativas

- **URL:** https://www.youtube.com/watch?v=JU9aUhRX_3Y
- **ID:** JU9aUhRX_3Y

## Transcrição

[Música]
fala pessoal sejam muito bem vindos aqui
aos poucos e marketing meu nome é
leandro guerra
seguindo a nossa seqüência de vídeos
sobre o quantitativo de finance
hoje eu começo no canal uma playlist
específica onde eu vou trazer pra vocês
um curso sobre introdução à estatística
e probabilidade utilizando o r
então isso que vocês estão vendo aqui
agora na tela é o estúdio que eu mostrei
no vídeo anterior para vocês que deixo
aqui um primeiro comentário como fazer a
instalação e como criar um prémio no
primeiro programa
porém eu vou abordar agora numa
sequência de de aulas exatamente como
você pode aprender o r e os elementos
fundamentais de estatística e
probabilidade
então se você está vindo aqui no número
canal pela primeira vez peço que você se
inscreva já deu coxa aqui no vídeo
ativos notificações e dá uma conferida
no todos os vídeos que que eu já
publiquei todo o conteúdo gratuito que
você tenha também pode acompanhar os
arquivos e todas as publicações lá no
meu site
o www.segs.com.br jamais assumirá
responsabilidade passar para vocês o
conteúdo é que está aqui nesse material
que eu deixo também disponível lanotte
porque market pontocom e vou explicar
aqui o passo-a-passo em português para
vocês e também disponibilizar os
arquivos exemplos do r b leza pessoal
então vamos pôr a mão na massa depois
que você instala o estúdio só você
entrar no site r estúdio pontocom baixar
fazer o download da versão free não tem
a menor necessidade de pagar seguir a
instalação é realmente simples e você
vai ter que andar de cara que já com o
primeiro ambiente
ele é dividido da maneira que está aqui
em quatro partes principais
essa 1ª região que você está vendo aqui
é o seu script é onde você vai realmente
inserir as suas linhas de código o seu
algoritmo esse janela que está aqui no
canto onde a gente tem um vai na mente é
um deviam ser listados todos os seus
objetos todas as variáveis que você vai
trabalhar aqui dentro do seu código não
se pergunta que eu vou mostrar também os
detalhes
ao longo do curso aqui na esquerda em
baixo a gente tem o console ele mostra
os resultados da dos cálculos realizados
pelo seu código em cima e no canto
inferior aqui a direita você tem uma
outra a área de ajuda onde você se
tornar um gráfico vai ver a saída por
aqui
você também pode ver os seus arquivos
listados nos seus territórios
os pacotes que você tenha instalado pode
também ter a ajuda do r&amp;b uma visão
adicional vou deixar que o pote com um
padrão de beleza pessoal
então o que é assim o elemento básico de
de uma linguagem de programação é aquilo
que a gente chama sintáxi o que é a
sintaxe à sintáxi modo na qual você
escreve assim como você fala português a
um norte americano fala a inglês o
italiano fala italiano cada linguagem de
programação tem a sua sintaxe que é o
modo na qual você escreve os comandos
que você vai dar pra maquina certo então
essa primeira linha que a gente que eu
inseri aqui pra vocês seguida dodô rech
é um comentário o que é um comentário em
um código um comentário é apenas um uma
forma de você documentário de você é
inserir alguma observação naquele código
quando você o executivo executa ele não
tenha feito nenhum e até por isso que
ele vem aqui destacado em uma outra cor
então por exemplo eu coloquei aqui o que
essa é a parte do script que é onde você
insere as suas linhas de código e o
objetivo da aula de hoje é mostrar pra
vocês uma introdução à mãe
lação de dados com números e vetores
estádio por falta de acentuação um
teclado não tá é configurado para o
português no r
a estrutura mais simples de dado é
aquilo que a gente chama de vetor
ok então se eu fui pegar 11 uma variável
x o que é o conceito de variável então
lembrando o pessoal que uma variável ela
é como se fosse uma gaveta é como se
fosse uma caixa em que você pode inserir
algum conteúdo lá dentro
e esse conteúdo pode justamente é mudar
de valor ao longo da execução do seu
código então por isso que que a gente
chama variável se ele for um valor fixo
a gente vai então chamar é de constante
certo então como que a gente declarou o
primeiro valor
então a gente tem que o elemento x ea
esse xis eu vou fazer uma atribuição ou
seja vão colocar alguma coisa dentro
dentro daquela caixa dentro daquela
gaveta um r a atribuição ela pode ser
feita por esse sinal é do menor seguido
pelo iphem ou ela pode ser feita é por
exemplo com um sinal de igual
particularmente eu prefiro seguir é esse
primeiro aqui do sinal de menor com
hífen porque depois ele não vai
confundir com os operadores lógicos ok
mas se você quiser também pode fazer um
sinal do uol
então a estrutura mais simples ela é um
vetor e o vetor ele pode assumir o
seguinte formato então você sempre
começa com atribuição um valor xis e
você vai colocar um vetor que é o vetor
o vetor é um elemento em que você pode
inserir ali dentro diversos valores que
pode ser apenas um ou pode ser vários
então por exemplo 2.2 1.36 10
então o nosso valor de x
ele vai receber é aquelas componentes
como o que eu sei primeiro quando eu
aperto control entre a porta após ter
escrito essa linha de código você vai
ver que aqui em baixo no console ele
executou aquela linha de comando no seu
ambiente
provavelmente você recebe que você tem o
x
ele tem um tipo numérico ou seja tenho
um livro e valores apenas médicos ali
dentro que vai de 1 até 3 porque eu
tenho três elementos aqui dentro e os
valores que eu tenho nele 2.2 1.36 e 10
então se eu executar o xis aqui
novamente
você vai ver que ele aparece um bom
resultado aqui em baixo que é o que eu
tenho exatamente ali dentro do x
repare que o o or&amp;ccedil é que esses
entre bush minúsculo que foi o qual
atribuir ele vai ser diferente do x
maiúsculo segunda 1 x maiúsculo aqui ele
vai dizer que aquele objeto não foi
encontrado porque eu não fiz nenhuma
atribuição a uma variável ou não criei
nenhum outro vetor chamado the x
maiúsculo ok pessoal porque é relevante
você saber se essa primeira é essa
primeira coisa introdutória que às vezes
parece um pouco sacal você começa a
aprender programação mas é que isso é o
que vai facilitar a sua vida na frente
se você não tem essa essa clareza num a
sua vida na frente vai ser muito
complicada para coisas muito simples que
você precisa fazer oque com os elementos
de um vetor
você pode fazer manipulações né de um
modo geral inclusive cálculos
aritméticos tá não erre não é diferente
no excel e você tem com operadores é de
cálculo mais ou menos a multiplicação a
divisão é então dentro daquele vetor
você pode por exemplo criar um novo
vetor y que ele vai receber o vetor x x
2 o que ele vai fazer ele vai
multiplicar todos os elementos dentro de
x por dois e ele vai colocar dentro do
estado então a gente executa aqui e ver
que o y é exatamente o dobro naquele
valor
2 se eu tenho um vetor muito longo eu
não vou conseguir ver tudo aqui na tela
ok então como eu faço por exemplo pra
tentar entender algumas coisas básicas
alguns operadores elementares algumas
medidas básicas
um elemento ou de um vetor então vamos
supor por exemplo que a gente queira
saber a média e jogou aqui em colocar no
inglês mim então eu posso por exemplo
fazer média do y e ele vai me dar 9.4
que é a soma dos 3 / 3 vai me dá a média
9.4 eu posso pegar esse valor da média
criar uma outra variável chamada média e
atribuir a média de y
então aquele 9.4 vai ser representado
aqui e agora dentro a variável que é a
média de y ok pessoal outro elemento que
você precisa saber agora para começar é
se eu quiser fazer a soma de todos esses
elementos aqui então eu posso da mesma
forma e fazer a soma de y e o bacana do
r que ele é muito intuitivo estão soma
de y vai te dar a soma de todos aqueles
elementos além da soma
você pode fazer o que é o tamanho
daquele vetor
ok então se você fizer o o cumprimento
de lente é exatamente da mesma forma
você vai ver que ele o resposta você
aqui embaixo três elementos e lembrando
que sempre tudo isso é pode ser
atribuído à novas variáveis que essa é a
grande diferença flexibilidade de várias
linguagens mais uma coisa
particularmente legal que você tem aqui
no r b leza pessoal
então esses são os componentes básicos
para você começar a introduzir no r
esse vídeo foi um pouquinho mais longo
porque é a primeira vez que estou
falando desse assunto mas eu quero
sempre trazer para vocês um conteúdo um
pouco mais rápido para quem no seu tempo
livre você possa aproveitar e começar a
aprender tudo o que eu venho passando
aqui no canal pra vocês
deixe o seu comentário aqui em baixo com
suas dúvidas suas sugestões se inscreva
no canal um grande abraço e até o
próximo vídeo tchau tchau
[Música]