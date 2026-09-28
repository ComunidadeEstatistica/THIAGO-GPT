# Part 3 - Logistic Regression - This is your chance! Now or never! - Prof. Adriana Silva

- **URL:** https://www.youtube.com/watch?v=dcsZsA_wipE
- **ID:** dcsZsA_wipE

## Transcrição

Olá a todos, já falamos sobre
regressão linear em outro vídeo e há
Duas coisas que eu gostaria de mencionar.
sobre o que foi dito sobre regressão
linear. Conversamos muito sobre o
correlação entre duas variáveis
numérica, que é a correlação de
Pearson. Um ponto importante, apenas para
comentário sobre o tema da minha camiseta no
vídeo anterior. Correlação não implica
causalidade. O que isto significa? Que
uma tem uma relação estatística
Com o outro não significa que um
causar o efeito no outro. Porque?
Existe até um livro muito engraçado.
chamadas correlações espúrias. Não
Lembro-me do nome do autor, mas é
Ele é um cara incrível, eu o recomendo muito.
onde mostrou correlações
estatísticas sobre várias coisas no mundo
. E uma delas é que quanto mais
Nicolas Cage faz mais filmes.
Pessoas se afogam. E existe um
correlação estatística nisso.
Então, o que isso significa? Vamos...
Ligue para Nicolas e diga: "Ei, vai embora."
de fazer filmes porque há muito
"Pessoas morrendo na piscina?" Não, não.
Existe uma relação de causa e efeito entre essas duas informações.
. No entanto, em números, há
uma correlação estatística. Então
Esse é um ponto importante. Outra coisa
que eu realmente gostaria de corrigir em mim mesma.
O vídeo anterior é o próximo. Quando
Escrevemos a equação aqui no
e coloquei o y estimado, ou seja, o
equação estimada que estou criando,
Eu escrevi beta 0 + beta1 x1 e isso
Poderia ter ainda mais variáveis.
aqui, beta p xp. Mas o que eu tenho que
O próximo passo é corrigir. É um
conceito estatístico e quando eu vi o
Eu disse no vídeo: "Caramba, eu tinha me esquecido do..."
"Chapeuzinho." No momento eu estou
Para estimar algo, estou usando o
parâmetros estimados. Então
Preciso colocar o chapeuzinho no
versões beta também. E então o nosso
A palestra de hoje é sobre regressão.
logística. Bem, nós conversamos sobre o
regressão linear, que usa isso
equação daqui. E esta equação é
muito atraente, muito importante, muito
Útil para diversas coisas. E então
Surgiram alguns problemas que não
Resolvemos isso com uma regressão linear.
porque o que eu recebo aqui é um
um número e às vezes eu não quero receber um
número. Então, por exemplo, eu quero
saber a probabilidade de um
Compra individual do meu produto. Qual
Minha variável de resposta, neste caso?
É uma compra e não é uma compra. Então,
Vamos pensar na mesa. Eu vou querer um, e esse...
Ele comprou e não comprou. Então, o
Um significa compra, zero significa não compra. E
Vou ter informações sobre isso.
indivíduo, a quem chamo aqui de X1, X2
e X3. X1 pode ser idade, X2 pode
Sendo o sexo, X3 pode ser a renda.
mensalmente da pessoa, pode ser
qualquer uma das variáveis ​​que ele cria
o que faz sentido para explicar o
Comprar ou não comprar. Mas vamos imaginar...
Em seguida, vamos imaginar que eu sou
observando aqui o salário de
individual, então meu X1 aqui é
salário. E há pessoas que ganham 1.000.
Há pessoas que ganham 2.000, há pessoas que
ganha 3.000. E eu quero saber se isso existe.
uma parceria entre estes dois
Informação. Se eu for representar isso graficamente,
O que vai acontecer? Eu vou ter o aqui
compra, que é a minha única, e eu não terei a outra.
compra, que é meu zero. E aqui está:
o salário. Muito bom. No momento de
Desenhe isso, o que vai acontecer? UM
um monte de pontos entre esses dois
linhas. Então, imagine que
Eu encontraria algo assim, veja.
Imagine que estou falando de um iPhone.
. Compre meu iPhone ou não compre meu iPhone.
iPhone vinculado ao salário
individual. E, olhando para isso, será que...
Consigo desenhar a famosa linha reta,
O que aprendemos na aula?
passar? Não faz sentido, não é? UM
Essa frase não me explica nada.
Exceto que estudiosos, gênios
Eles começaram a pensar: "Como posso eu
deixar este universo para se ajustar
Algo que explique este universo?
Então eles começaram a se perguntar, bem...
Aqui é zero e um, mas não é zero.
E, primeiro, é um fato, é uma compra e não...
compras. Nós simplesmente criamos um número.
para esse propósito, mas esse número não é um
Número, é um fato. Compre e não compre
compras. Então eles começaram a pensar,
O que devo fazer com uma variável categórica?
Hum, vou verificar a frequência. Uma vez
Eu calculo a frequência de uma variável.
categórico, também consigo pensar em
probabilidade. Então, o que é o
Qual é a probabilidade de compra? Eles começaram a
Pensar, uau, será que em vez de ser
um Y estimado, que é um número, não
Posso usar um P estimado, que é o
probabilidade? Tudo bem? Mas
Vamos analisar isso juntos. A probabilidade
De quanto varia? Bem, o
A probabilidade varia de zero a um.
Portanto, isso não vai resolver o problema.
problema. Porque vamos pensar sobre o
equação linear, este universo varia
de infinito negativo a infinito positivo e
Este outro aqui também é menos
do infinito ao infinito. Então, se
Quero fazer algumas transformações em
Terei que fazer de um lado, terei que fazer do outro.
também. Então, como posso?
transformar algo aqui que vai de
de infinito negativo a infinito positivo e que
É igual a isto? Então eles pensaram:
Caramba, a probabilidade já aumentou a minha
intervalo. Em vez de ser zero, será
entre 0 e 1. Mas ainda não foi resolvido.
Meu problema. Bem, então, já que o
A probabilidade não resolveu meu problema.
Vamos analisar as probabilidades.
O que é probabilidade (chance)? O
A probabilidade é p dividida por 1-p. Hum
. Quanta variação existe nessa probabilidade?
Essa probabilidade varia entre zero e
Mais infinito, uau. Então agora
Melhorei meu intervalo. Em vez de
modelo P que varia entre zero e 1,
Vou modelar a probabilidade de que
varia entre zero e infinito. Mas ainda assim
Não está resolvido, porque aqui é...
do infinito negativo ao infinito positivo.
Então eles continuaram pensando sobre o quê?
transformação poderia fazer no
probabilidade de poder chegar de menos
infinito a mais infinito e assim por diante
Reutilize esta equação. E então
O que eles decidiram fazer? Aplique um
transformação logarítmica. Nele
momento em que eu aplico isso
transformação logarítmica, estou indo de
do infinito negativo ao infinito positivo.
Então, o que isso significa? Agora
Vou modelar um logaritmo de p que será
exatamente assim aqui. E o logaritmo de p
O que isso me proporciona? Vamos isolar
o p. E assim cheguei a uma equação.
que é a equação de regressão
logística, onde P estimado é igual a
que. A 1 dividido por 1 + e elevado a a-
(beta 0 + beta 1 x1 + beta p xp). Oh,
Então, o que isso significa? Olhar
Que sensacional! Essas pessoas são muito
ardiloso. Começamos com uma regressão.
linearmente, eu fiz transformações.
para manter essa estrutura, porque
Já criamos algo; Por que eu faria isso...?
É muita filosofia sobre transformação e nada mais.
Talvez criar do zero. E então eu criei
Algo sensacional, o que será? Agora
Estou estimando uma probabilidade onde
Eu obtive este resultado. E com isso,
O que está acontecendo? Eu crio uma curva que tem
um comportamento diferente. Terá
Onde está esse movimento?
A linha vermelha representa exatamente isso.
probabilidade que estou gerando. E
Olha só que ideia genial!
. Baixas probabilidades, isto é,
que a compra não aconteça, eles são
capturando a maioria dos pontos
aqui e as maiores probabilidades
estão capturando a maior parte do
pontos aqui. Mas é claro que estou errado.
que eu estou errado. Todos os modelos
O estatístico está errado. Já está pago.
Cometer erros, mas cometer erros
menos que nossa cabeça, nossa
cérebro. Então, observe que o
probabilidades mais altas são
conquistando a maioria. O
probabilidades mais baixas são
Capturando a minoria, e eu estou errado.
Aqui, e há momentos em que duvido,
que é o que chamamos de ponto de corte,
Qual é o limite? Esta é uma decisão.
minha estratégia; Terei que definir
Como vou fazer isso? E isso se baseia em
Depende muito do orçamento que eu tiver.
Isso dependerá muito do problema.
de frente para. Então, regressão
parte logística da regressão
linear e caminha em direção a uma nova equação
onde consigo obter poder e extrair
informações agora baseadas em
probabilidade. Mas o que eu sou
A modelagem é a possibilidade, por isso é...
o logaritmo da possibilidade, onde
Consegui chegar a esta equação. Mas muito
bom. Então, onde está o grande?
valor das estatísticas além de
alcançar essa probabilidade? Está no
interpretação. Então, eu posso
te pergunto. Quando estamos
Na regressão linear, interpretamos
O que é isso, beta 1?
influenciando Y, que era o quê? Para cada
aumento de uma unidade em X1, eu tenho
um aumento em beta 1 no Y estimado, que
Essas são as minhas vendas no caso de pizzas.
contanto que os outros permaneçam
constantes. Então eu sei diretamente
a influência da minha variável x1, que
era o número de alunos, quantos
Aumentar minhas vendas. Mas e quanto a...
Agora? Como devo interpretar isso?
beta 1, visto que não é mais linear? E
As coisas se complicaram aqui.
Então, o que é feito para
Interpretar é o que chamamos de probabilidades.
razão. O que é razão de chances? É o
razão de chances. O que é uma múmia?
Essa é a razão das probabilidades.
Então, como interpretamos uma probabilidade?
razão? Vamos relembrar o exemplo típico.
que em todos os blogs você pesquisa
Você encontrará o aplicativo Titanic.
onde eles pensam comigo, qual era o meu
Qual era a variável de resposta presente no Titanic?
Ele morreu e sobreviveu. E eu quero
modelo. Eu sou modelo, Adriana, a
Parte dele sobreviveu. Então, o meu
Eis o sobrevivente. E então
Possuía variáveis ​​como a idade do
A pessoa que estava no barco tinha
a turma em que eu estava no navio,
se estivesse no nível mais baixo de
navio, lá no porão, ou se fosse
Em segunda ou primeira classe. Tive
a tarifa que ele pagou por esse transporte,
tinha o sexo do indivíduo. E se
Nós nos lembramos do filme, nós nos lembramos
perfeitamente o momento em que o
"O navio naufraga", dizem eles: "Primeiro o
mulheres e crianças”, que eram as
pessoas que seriam salvas. Quando
Realizamos uma regressão logística para
Para explicar esse conceito do Titanic, não...
Faz sentido querer usá-lo para
prever, porque para garantir que
Eu usaria este modelo; Eu precisaria ter
um navio com a mesma tecnologia
colidindo com um iceberg. Então
Eu aplicaria a minha equação. Como sabemos
Isso não vai acontecer, eu posso usar o
Estatísticas para explicar os fatos.
E é aí que eu realizo uma regressão logística.
modelando quem sobreviveu, que é o meu
objeto de interesse. E eu tenho as probabilidades,
que surgem juntos neste cálculo, o quê?
Você está me dizendo isso? Imagine que no sexo isso desse
feminino versus masculino, 12,5. Não
Lembro-me dos números exatos, mas é
Algo desse tipo. Imagine isso aos 18 anos
, que é uma variável numérica, resultou em
0,3. O que significam as probabilidades? As probabilidades,
como se trata de possibilidades, seu
ponto de referência para dizer que eles são
igual é um. Quando for menor que
Primeiro, o que isso significa? Esse meu
possibilidade de que o evento de
O interesse surge nesse público que
Estou analisando que houve uma diminuição. Quando é
Maior que um, o que significa? Que
Essa possibilidade aumentou naquele
público que estou observando. Então
, ao interpretar as probabilidades em
o resultado de uma regressão
logística para o caso Titanic,
Vamos supor que haja em feminino versus
O indivíduo do sexo masculino apresentou uma proporção de 12,5. Que
O que você quer dizer? As mulheres têm 12,5
vezes mais chances de sobrevivência,
Foi isso que eu modelei, esses homens.
Então, agora, minha interpretação em
relação com minha própria variável, como
comporta-se. Então, as mulheres
Eles têm 12,5 vezes mais probabilidade de
Os homens sobrevivem. Muito bom.
A idade, que é uma variável numérica, não
Tenho uma maneira de comparar um com o outro. ?
Como fazemos isso? Estamos fazendo um aumento
de idade. Então, o que é isso? Por
cada incremento de uma unidade no
a idade reduz minhas chances de
sobrevivência em 0,3. E daí
O que você quer dizer? Quanto mais velho fico, menos
É a minha chance de sobrevivência.
Sendo mulher, a probabilidade de
a sobrevivência é maior do que a de um
homem. E é exatamente isso que demonstra.
o filme. Mulheres em primeiro lugar e
Crianças, o que é o quê? Quanto mais
Sou jovem, então minhas chances de
sobrevivência. Então, minha proporção de chances
É um. Se houver um, significa que não há nenhum.
diferença entre ser homem ou mulher,
por exemplo, ou que aumente em um ano em
A idade não tem influência em nada. Mas quando
Essa razão de chances é diferente de um, não é?
O que eu percebo? Que eu tenho capacidade
de interpretação. E essa é a grande questão.
valor da logística para o negócio.
Eu posso contar uma história, eu posso
Explique e aplique. Porque? É
É ótimo criar algoritmos porque eles fazem
previsões, mas muitas vezes o
A empresa não está interessada apenas em
algoritmo que faz a previsão.
Eu quero você, cientista de dados,
Qualquer nome que você quiser, eu
Meu nome é Jedi, qual é? Me ajude
para administrar meu negócio. E naquele momento
É nisso que penso quando administro meu negócio,
Preciso de um intérprete. Regressão
A logística entra no grupo de
algoritmos que possuem interpretação.
Espero que tenha gostado. Muitos
obrigado.