# Aula 13 - Explorando os dados e missings - Curso de R para Finanças Quantitativas

- **URL:** https://www.youtube.com/watch?v=AvYuZ9A0b8Y
- **ID:** AvYuZ9A0b8Y

## Transcrição

[Música]
fala pessoal sejam muito bem vindos aqui
é outro pouco é marketing
meu nome é leandro guerra e hoje
chegamos ao número 13 do curso de r para
finanças quantitativas
onde eu vou mostrar pra vocês com mais
detalhes como explorar uma base de dados
dentro do r
e como trabalhar com aquilo que a gente
chama de de valores ausentes ou os dados
que são mysims depois de tudo que a
gente viu da introdução conte molde e
também do transe system e das funções
essenciais nessa segunda etapa do curso
vamos dizer assim eu vou ensinar vocês
melhor essa manipulação de dados porque
para qualquer análise um pouco mais
sofisticada que você queira fazer é um
conhecimento essencial para si te embora
lá pro r a estrutura inicial da aula de
hoje vem dos códigos que a gente já viu
anteriormente para a gente conseguir
carregar uma base de dados
ok e nós também já vimos a função samary
que faz a descrição básica da dos dados
presentes no data frame e também faz as
frequências em algumas estatísticas
elementares não é só para recordar
mínima psi é um valor numérico
o primeiro que a gente tem no primeiro
quartil a mediana média e assim por
diante se for ou se forem variáveis
categóricas ele vai mostrar por exemplo
a soma ou a quantidade de cada uma das
classes presente naqueles dados aqui
repare que de propósito eu carreguei os
dados da cotação da bovespa porque tem
aqui o nosso carinho dela de hoje porque
é também um ponto que são os anéis que a
gente tem aqui sete informações faltares
então quais são as outras funções
adicionais para fazer a exploração de
dados
a primeira coisa é o editor de dados
então se você chamar a função edith
e chamar o datafolha m você vai abrir
essa outra janelinha que ao executar o
comando que ela vai conter os dados que
estão presentes ali no 'data frame a
lenda mas qualquer diferença dessa
função edith de quando a gente faz por
exemplo viu data 7 clicando no nome dele
dentro do do ano vai ao médico
a diferença principal é que a gente vai
ter é que aqui com o nome sugere você
pode editar
então se você perceber que tem algum
dado errado ou se você quiser mudar o
nome de alguma variável vai funcionar
mais ou menos e com o excel
então eu venho aqui mundo por exemplo
essa primeira informação aqui tá
acumulou nem eu coloco por exemplo como
data com do aqui em ter o ok e fecha o
editor
ele já vai mudar e aí você vai ter
aquela primeira coluna que era as datas
como o primeiro elemento do data 7
então essa é a diferença do editor a
função viu é também simples de você
inserir novos dados então se você tem
alguma outra variável adicional que
querem ser adicionada que ou se você
quer adicionar uma outra linha lá no
final do data 7
como eu disse funciona exatamente como o
excel
feito isso existe uma outra função que a
chamada str que ela vai te mostrar a
estrutura do da frame a diferença ela
vai se parecer muito com aquilo que a
gente faz aqui mano vai do med pegando e
clicando aqui nessa setinha azul então
ela vai mostrar os dados que você tenha
os elementos presentes o seu tipo e aí
uma primeira ideia de quais são os dados
ali disponíveis
leandro quero saber
só os dados só o nome das informações
que eu tenho as suas variáveis que eu
tenho aquele da frente então eu vou usar
a função names que a gente também já viu
porém hoje eu quero deixar muito claro
pra vocês como você trabalha melhor com
ela
repare aqui por exemplo que a gente tem
na execução names abertura máxima amena
fechamento mas ele está seguindo aqui
desse bvs
é um pouco chato você foi ficar
digitando toda vez então com que você
muda
lembrando que tudo r pode ser atribuído
o manipulável como uma variável você
pode fazer o seguinte eu quero alterar
que o names do bovespa
ele vai receber um vetor de ao contendo
extinguisse com essas novas informações
então posso fazer com que roupa
ae e vou repetir exatamente a mesma
quantidade os nomes que eu quero dar
aqui então mínima close esqueci de
colocar aqui entre aspas
vamos colocar também por último aqui o
volume e por fim esse valor ajustado um
choque de ajustado mesmo quando executo
isso você também no que eu tô
atribuindo-a os nomes da bsp exatamente
esse vetor aqui quando eu executar e
rodar o names mais uma vez aqui sozinho
você vai ver que automaticamente já foi
mudado isso é muito bacana pra fazer
seleção de variáveis nem pra você ter
controle exatamente o que você tem ali
além do tenho data site muito grande eu
quero ter uma idéia do que tem nas
primeiras linhas
é muito simples você usa a função head
daquele seu data set e aí ele vai te dá
as seis primeiras linhas presentes ali
se você quiser você pode deixar a função
rede um pouco mais complexa colocar um
parâmetro nela como por exemplo n igual
a 10 e invés das seis primeiras linhas
ele vai mostrar as dez primeiras linhas
pra você já ter uma primeira ideia do
que é aquela informação disponível
conseqüentemente você tem a função tenho
de cauda que ela funciona de maneira
análoga só mostrando as últimas linhas
presentes no data 7 da mesma forma você
pode manipular a função tenho pra saber
exatamente qual é o número de linhas que
você vai mostrar que estão ali presentes
ao final daquela base rock como eu faço
uma seleção de dados simples você vai
poder fazer da seguinte forma
lembrando sempre que você tem o seu data
frame para você acessar um conteúdo
específico ali dentro
por exemplo eu quero acessar a linha
número 35
na variável que está presente na coluna
número 5
sempre que você fizer esse trabalho aqui
com os data frames você coloca entre os
colchetes mais ou menos aqueles
princípios que nós vimos ali na aula 10
o que voltando no código para você ver
quando a gente criou aquela variável do
deslocamento para poder identificar
qualquer o nosso alvo
você faz exatamente a mesma coisa entre
pio x
e aí o que você quer eu quero ver por
exemplo as primeiras dez linhas em
substituição a função rede você coloca o
primeiro argumento de um dos dois pontos
vai simular de 1 até ea linha que você
quer que a linha 10
certo então esse primeiro conjunto
representa as linhas
quando você coloca vírgula entre as
colunas aí eu quero ver todas as colunas
ok
deixe em branco então você tem lembrado
este é o primeiro argumento
representando as linhas que você quer
o intervalo de linhas e aqui você deixa
em branco porque você quer pegar todas
as colunas mas não se esqueça da vírgula
eu executo isso ele me dá exatamente a
mesma informação que o head 10
porém a flexibilidade como eu disse é
você trabalhar isso pra ver qualquer
outra posição dentro ali do seu data
frame
então você pode ver por exemplo eu quero
saber o valor presente na linha 15 e na
coluna 1 234 por exemplo é o fechamento
então eu coloco ali quatro eu vou pegar
exatamente aquela única informação do
fechamento disponível
lembrando que isso também serve se eu
fizer a atribuição aqui e colocar um
outro valor qualquer 6666
por exemplo e eu vou ter atribuído
naquela posição e se eu executar aquela
posição novamente eu tenho aquele dado o
ok
como a gente vai trabalhar então pra
fechar a aula de hoje com os miis a
presença de mísseis é um pouco chata
porque várias funções no rn não vão ser
executados se você não fizer o
tratamento adequado dessas informações
faltantes
ok então a primeira coisa é você
entender se você tem ou não me senti
naquele data 7 como você faz isso
de uma maneira muito simples você pode
contar o seu número demissões usando a
função com o santos
okay do que o que eu vou querer fazer
então estou somando aço
as colunas tá e eu vou usar a minha
função para checar se e nem leitão é em
nenhum e nem daquele meu data frame
quando eu executar isso ele vai mostrar
por coluna o número de mísseis que você
tem que é de forma análoga aquilo que é
a função sonora e já te trazia leandro
quero me livrar desse cnas porque como
você mesmo falou eles complicam a
execução de determinadas funções
você vai simplesmente fazer uma nova
atribuição uma variável qualquer ou
repetir o nome para não ficar poluindo o
meio ambiente e vou usar a função e nem
ponto mit
quando eu uso essa função e nem
compromete do governo israelense
cancelei todos aqueles e nes se eu
executar novamente aquela soma das
colunas por colunas eu ver que agora é
zero
existem outras formas de tratar os miis
em seu introduz hoje pra vocês o
conceito e conforme a gente for nos
exemplos práticos e mudando cada vez
mais detalhes beleza pessoal
muito obrigado por assistir o vídeo se
inscreve no canal compartilhe com seus
amigos um grande abraço e até o próximo
tal
[Música]