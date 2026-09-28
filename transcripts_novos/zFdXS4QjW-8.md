# Linear Regression: Interpreting Coefficients in Simple and Multiple Linear Regression Models

- **URL:** https://www.youtube.com/watch?v=zFdXS4QjW-8
- **ID:** zFdXS4QjW-8

## Transcrição

Olá pessoal. Hoje teremos um
conversa detalhada sobre o
interpretação dos coeficientes em
regressão linear, especificamente
em contextos como a inclusão de
covariáveis ​​ou quando realizamos
procedimentos para verificar
mediação e moderação. Então,
Antes de prosseguirmos, vale a pena
revisitar alguns conceitos básicos,
como o conceito de espaço amostral.
Nós o denotamos usando este ômega
Aqui, em letra maiúscula. Este conjunto de
pequenos eventos, representados aqui
Para este pequeno ômega, será
nosso espaço amostral. E cada um
Uma variável aleatória pode ser definida como
uma função que associa um evento, algo
do nosso espaço amostral, para um
número real. Então aqui está, para
Por exemplo, posso trabalhar com o
intuição de ter a altura, de ter o
peso e ter outra medida corporal
humano, talvez o perímetro do
circunferência da cabeça. De
Em todo caso, o que acontece quando
Devo criar um modelo linear? Eu descrevo um
relação entre essas observações,
entre essas covariáveis, usando um
equação de uma reta. Não necessariamente
Uma linha reta, pode ser um plano,
dependendo do número de dimensões
que você está usando aqui, mas a ideia
É um espaço plano geométrico
e algebricamente, onde você fala sobre um
combinação, de uma soma. Então,
Definimos o nosso resultado, que seria
Isto e aqui. Usando alguns
parâmetros, teríamos um erro
associado a cada observação, um
coeficiente linear, que será
associado ao mínimo, o valor inicial,
e um coeficiente angular, que
descreverá verdadeiramente esse relacionamento.
entre a variável dependente e nossa
variável preditora. Em geral, o quê?
O que fazemos é observar a característica.
desta versão beta, desta versão beta1. Então,
Por exemplo, se beta1 for positivo,
Isso significa que você está em um relacionamento.
direto com seu x1. Se o seu beta for
negativo, isso significa que você tem um
relação inversa. Isso é mais fácil.
Vejamos se analisamos o gráfico. Por
Por exemplo, aqui teríamos nosso eixo.
E, o nosso eixo X. E então, ajustando o
modelo linear baseado nessas observações
É evidente que temos uma interceptação.
, que seria o nosso coeficiente linear
, que beta zero. E como o
À medida que os valores de x aumentam, o valor de um
estará aqui em cima, enquanto o
O valor de dois estará aqui embaixo, o
Os valores de y também aumentam.
Isso indicaria, portanto, um beta de
configuração positiva. Então,
Formalmente, o que estamos fazendo?
aqui? Estamos tomando isso e,
descrevendo-o através de um
regressão linear. E para avaliar seus
relação com x, como ela varia quando
A outra covariável varia, nossa
Para prever o comportamento, calculamos a derivada parcial.
disso e com relação a x1. Qual
O que vemos aqui é o seguinte: beta0 não
Depende de x1, e não depende do erro.
Então, só nos resta esta.
termo e, usando a derivada de
polinômios normais, nós terminamos apenas
com beta1, que é o nosso coeficiente.
de inclinação. Em geral, não é
Não é necessário falar sobre derivativos ou sobre
Esses conceitos são usados ​​para falar sobre isso.
associação. Basta verificar se é
uma linha reta. Então, se você tiver
Com um beta positivo, podemos dizer que
A maior, B maior. E quando você tem um
beta negativo, podemos dizer que um
Quanto maior A, menor B. Seria uma relação.
reverter. As coisas estão começando a ficar complicadas.
um pouco mais quando pensamos em mais do que
um preditor. Por exemplo, aqui
Temos o e, além do
parâmetros que havíamos usado anteriormente,
Começamos a usar um beta2 e um x2.
bem aqui. Então, este foi o
equação da reta que tínhamos
antes, incluindo este erro. E agora
Adicionamos um termo que
Multiplique a por 2. Agora temos o
três covariáveis ​​que nós estávamos
Observando: y, x1 e x2. Nesse caso,
O que acontece é o seguinte:
A interpretação continua sendo muito
semelhante. Então, se antes tínhamos
Esta linha reta aqui, agora passamos a ter
esse. Além deste termo, o que mais?
O que acontece é que o termo que
multiplicado por x1, que seria este beta.
Primo, isso vai alterar o valor dele, algo assim.
. A tendência é que isso continue.
semelhante, mas a introdução de
Uma covariável modifica sua estimativa.
. E com isso costumamos dizer que somos
controlando pelo efeito deste outro
covariável que introduzimos. Então,
Por exemplo, neste primeiro modelo
Estamos utilizando regressão linear.
entre altura e peso, uma vez
Introduzimos uma segunda covariável,
por exemplo, a circunferência do
cabeça, dizemos que estamos analisando
a relação entre altura e peso,
levando em consideração a circunferência de
a cabeça. Quando falamos sobre isso
procedimentos, mediação e
moderação, casos especiais estão incluídos,
porque além de executar o
Para regressões simples, executamos três
modelos auxiliares para verificar
algumas premissas. Em que se baseia?
Onde se encontra esse conceito de mediação? O
A ideia é que você tenha um estágio intermediário.
Aqui, e o exemplo proverbial é o
Café, câncer e cigarros.
Se você tentar analisar um relacionamento
direto, talvez você o encontre entre os
Café e câncer. Mas a maioria de
os estudos acabaram descobrindo
que, na realidade, havia um
intermediário; O café não é lá essas coisas.
carcinogênico, mas está associado
ao hábito de fumar, que seria
por meio dessa associação. Então,
uma vez que incluímos isso no modelo
covariável do tabagismo, essa via
existe uma ligação direta entre beber café e ter
O câncer simplesmente desaparece. Então
que meu primo beta se torna próximo de
zero, enquanto meu beta anterior era
diferente. O que fazemos então é
simular esses modelos individualmente
entre X e Y, entre X e o mediador,
entre o mediador e Y, e então fazer um
Modelo completo. E com base nisso
Comparamos esses valores beta antes e depois.
. Nesse caso, eu ainda posso falar.
de derivadas parciais do mesmo
forma, pensando em termos de constantes. Porque
se eu calcular as derivadas parciais com
Com relação a x1 e x2, o valor para x1 será apenas...
beta primo, que é uma constante, e o
x2 também será beta2, que
É também uma constante. Nesse caso
minha interpretação dessa relação
Entre duas variáveis, como Y varia?
Com relação a X? É a mesma ideia que
Tivemos isso aqui desde o início. Quando X
Aumenta, e aumenta. Isso sempre em um
uma proporção bastante constante, sabe? Em
Moderação é quando as coisas
As coisas começam a ficar um pouco complicadas e é
É aí que vale a pena pensar sobre isso.
Conceito de derivada. É por isso que
Trouxe isto aqui, não apenas para entender o
moderação, mas também acredito que
Entender isso facilita a compreensão.
dos casos mais comuns. Então, em
moderação, além da
Os termos que usamos aqui, reciclados, são reciclados.
Na nossa notação, removi os betas e
Estou lidando apenas com esses alfas.
Aqui, alfa 0, alfa 1, etc. Então,
além da equação que tínhamos
anteriormente, que levava em consideração um
coeficiente linear e dois coeficientes
angular, cada um multiplicando um
covariável, terei outro termo que
É um termo multiplicativo. Esse
O termo entra multiplicando x1 por x2,
e também terá um coeficiente. E
Isso torna nosso modelo muito
diferente do que era antes. Por
que? Quando eu for calcular agora o
derivada parcial em relação a x1, não
Só terei este termo aqui que
depende de x1. Este outro termo
O multiplicativo também depende de x1 e
não será uma constante quando
Vamos aplicar a regra da cadeia a
Obtenha a derivada desse polinômio.
Tanto a derivada parcial em relação a
uma x1 como a derivada parcial com
com relação a x2 será dado por um
em linha reta. Não é uma linha constante
como aquela paralela ao eixo X de antes
. Por exemplo, temos um beta principal
constante aqui. Agora o nosso
inclinação, nosso coeficiente de
variação, depende do outro
covariável. E é aqui que eu trago o
Intuição da tributação progressiva.
Vamos considerar o seguinte: se um
Uma pessoa ganha menos que outra, paga
impostos mais baixos de um ponto de vista
absoluto. Se você ganhar 1.000 reais,
pagará menos impostos do que alguém que
ganha 100.000. Mas, além disso, há o
Conceito de imposto progressivo.
Então, quem arrecada mais dinheiro?
também pagará uma proporção maior
dessa receita. Portanto,
Quanto maior a quantidade, não apenas o
O valor absoluto pago é maior, mas
que esse valor absoluto representa um
uma proporção maior da receita arrecadada.
Fazemos algo semelhante aqui, só que
usando um dispositivo que é este outro
covariável. Então, em vez de
Sua faixa de imposto muda ao longo do tempo.
que sua coleção está progredindo,
Fazemos a ligação com uma segunda covariável. ?
O que isto significa? Por exemplo, eu posso
Ajustar de acordo com a etnia. De acordo com o
circunferência da cabeça, isso pode
significam uma etnia diferente e que
modifica a relação entre altura e
peso. Pensando de forma simples
em antropometria, que na verdade é
Como surgiram esses problemas?
regressão com Galton. Além disso
situação em que temos uma covariável
E a interpretação é que algo muda.
Também posso lidar com um caso.
especialmente, que é quando esses termos
Eles têm sinais diferentes, alfa 2 e
alfa 3, ou alfa 1 e alfa 3. E isto
Isso acontece da seguinte maneira. Quando
Tenho uma observação aqui e a
módulo, a magnitude deste termo,
é maior que o deste outro, o valor
as alterações derivadas. Então, para
alguns valores de x2, eu posso ter um
relação positiva entre o
covariáveis. E para outros valores de x2
ou x1, posso ter uma correlação
relação inversa entre as variáveis. Aqui
Seria mais ou menos o caso de que
Até mesmo alguém que ganhasse muito pouco passaria.
para receber dinheiro. O valor do seu
A receita se tornaria positiva em
em vez de ser negativo sobre
impostos. Acho que conseguimos ver
Do começo ao fim, esses conceitos, como
Isso fica um pouco mais difícil.
interpretação da relação entre
covariáveis, e formalmente sempre
Precisamos pensar em derivativos.
parciais. Essa questão de
que na ciência de dados, trabalhar nisso
sem uma base razoável em matemática
É complicado e pode levar a
interpretações errôneas. Queria
abrir uma exceção em relação a isso
questão dos modelos matemáticos
em contraste com os aspectos filosóficos, que
Isso é o próximo passo. Aqui estou me dirigindo a
puramente qual é a relação entre
as quantidades que estamos estudando,
puramente entre as magnitudes. PARA
desde o momento em que começo a
Para falar sobre causalidade, sobre
modificação de efeitos e mais
experimental, surgem outras questões
o que pode não ser necessariamente
corresponder ao que aqui o
A matemática está dizendo. Por exemplo
Aqui descobrimos que a derivada de
E quanto a x1, foi dado por isto
linha reta e vice-versa em relação a x2 era
conforme indicado na linha abaixo. Observe que
Assim, a derivada em relação a x1 é
semelhante à derivada em relação a x2.
Apenas o termo que está sendo alterado.
multiplicando aqui. E eu poderia dizer
Por exemplo, que isso está associado
causalmente a Y ou que isto é
causalmente associado a Y. Mas todos
Depende muito das condições do local.
que eu realizei esses experimentos.
Portanto, quanto mais você se purificar, mais cedo.
Para coletar e processar os dados, melhor.
. Quanto mais começamos a complicar o
quanto mais modelo matemático, mais difícil será.
a interpretação. E, finalmente,
Gostaria de recomendar um artigo aqui,
que é um artigo interessante sobre
Este tópico, que aborda o
diferença entre esses conceitos que
Estamos promovendo a moderação.
mediação e qual seria a diferença
entre eles. Deixe-me entrar aqui. UM
pedaço. Aqui está. Então mostre
O que seriam essas ideias de ter um
rota direta, uma rota de modificação
, usando setas aqui, relembrando um
poucas categorias. E aqui está.
aquela equação que eu trouxe. Você vai
Para ter um coeficiente linear, o
angular multiplicando cada variável.
E aqui está o termo multiplicador de
interação. Você tem até o Alpha 3.
Ele usou a mesma notação que nós.
Usamos e isso está multiplicando ambos E
bem como Q, que são as duas covariáveis
que você está usando aqui. Bom, espero que sim.
que agora ficou mais claro. Obviamente
Esta não é a maneira mais fácil de
observe essas relações entre
variáveis ​​na regressão linear, mas
É um processo rigoroso e, especialmente,
para esses casos especiais de
moderação e mediação, uma
ponto em que acho que fica mais fácil
Para falar sobre rigor matemático, sobre como
Aí reside o derivado, que tentar
Traduza isto usando linguagem natural e
cair em algum tipo de armadilha. UM
abraço.