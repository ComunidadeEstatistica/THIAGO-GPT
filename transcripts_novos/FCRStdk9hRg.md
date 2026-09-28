# Artificial Neural Networks - Basic theoretical and practical concepts - Matheus Pussaignolli

- **URL:** https://www.youtube.com/watch?v=FCRStdk9hRg
- **ID:** FCRStdk9hRg

## Transcrição

Bem-vindos a mais uma aula aqui na [nome da empresa/empresa].
Dados estatísticos. Bem, em primeiro lugar, eu gostaria de...
Obrigado a Thiago Marques pelo
chance. Sou um estudante de graduação.
Engenharia de energia na Unesp
sobre Rosana e hoje vou falar um pouco sobre ela.
em redes neurais artificiais,
alguns conceitos teóricos e
práticas básicas. Bem,
basicamente os tópicos da aula
Elas serão a introdução ao neurônio,
Em outras palavras, vou explicar como funciona.
um neurônio biológico. Vou falar sobre um
pouco sobre redes neurais
artificial aplicado
computacionalmente, isto é, como é que
Eles realizam os cálculos para uma rede.
perceptron neuronal, que é o mais
simples. Vou dar alguns exemplos.
valores numéricos para esclarecer o
Entendo e vou comentar um pouco.
sobre o aplicativo que estou fazendo no meu
iniciação científica, que é a
previsão de carga ou vários
Energias renováveis ​​brasileiras, é
Em outras palavras, a aplicação da máquina.
Aprendizagem no cenário energético
Brasileiro. Certo, então.
Basicamente, antes de entrarmos no assunto...
redes neurais de uma forma mais, digamos,
Especificamente, precisamos entender
Como funciona o neurônio biológico.
Basicamente, neurônios biológicos
São compostos por dendritos, um
corpo celular, um axônio e o
terminações axonais. Basicamente,
Sabemos que nossos cérebros são
composto por vários neurônios. Ei,
basicamente o conhecimento de um
de um neurônio para outro, ele é transportado para
através das sinapses que entram e o
O conhecimento entra através do
dendrito, e então passa pelo corpo
o celular é transportado pelo nosso
axônio e atinge a extremidade do
terminações do nosso axônio.
Portanto, vale a pena destacar aqui o porquê.
Criamos uma rede neural artificial.
Computacionalmente, basicamente para
melhorar a transferência de conhecimento
que nossa rede criada terá e assim por diante
para poder ter maior precisão no
que queremos determinar, se para
Prever ou classificar. Bem,
Então, o que são neurônios?
neurônios? Nosso cérebro usa o
neurônios para processar informações,
Ou seja, todas as informações de cada um
No dia em que você faz algo, seu cérebro
usa neurônios para transportar
essa informação. Ah, os axônios
transmitirá as mensagens de um
neurônio para outro, isto é, eles são os
que irá transportar o conhecimento. ELE
Eles lançam substâncias químicas no
sinapses e entram através dos dendritos. É
ou seja, o conhecimento de um neurônio
será passado para o dendrito do outro
neurônio através da sinapse, como
Conforme já foi dito. Ah, e a última.
A observação a ser feita é que o neurônio
Será acionado se a entrada for maior que
um número definido ou não. Esse
Essa afirmação ficará mais clara em breve.
próximos slides, quando
Mostrarei que com um determinado valor,
Você poderá ativar ou não o seu
neurônio, isto é, para transportar o
conhecimento. Bem, de uma forma mais
Em resumo, representamos aqui.
uma rede neural, uh, perceptron de
uma camada, onde temos as entradas X1
Uau, X1, X2, X3 até Xn. Ter
Nossos pesos W1, W2, W3, WN. Ter
a função soma, que é a função
mais simples do que uma rede neural pode
ter, e a função de ativação.
Vale ressaltar que podemos ter
diversas funções de ativação e
dependendo da aplicação que
Use um; Um pode ser melhor que o outro.
Então, como uma rede aprende?
neuronal? Basicamente você tem o
entradas, que são as variáveis ​​do seu
modelo, que você será
incorporando, multiplicado pelo
pesos. com i variando de 1 a n, que
Depende do número de inscrições.
sendo armazenado em sua variável soma.
Para deixar mais claro, temos um
exemplo numérico onde temos três
Três sinapses, certo?
Esses seriam os nossos pesos. E nós vamos ser
Aplicando a função soma. Então,
aplicando a função soma, neste
Por exemplo, temos 1 x 0,8 + 7 x 0,1
+ 5 x 0 resultará em 1,5. Uh, usando o
função degrau, que é a mais
simples que uma rede neural pode ter
, temos a função degrau, que
Diz que se a soma for maior que zero,
Nós conseguimos um. Então o neurônio
será ativado, portanto o
O conhecimento será transmitido, a partir do quê?
Caso contrário será zero, então o
O neurônio será desativado. Bem,
Então, aqui está uma maneira mais simples:
As redes se comportam da seguinte maneira:
maneiras. Os pesos são as sinapses de
nossa rede neural. Então, é
Em outras palavras, como afirmado anteriormente,
Nossos pesos são o que simulam um
sinapses em nosso cérebro. Os pesos
amplificar ou reduzir um sinal
entrada, ou seja, quanto maior o
Quanto maior o peso, maior o valor que você tem.
Você receberá. E quanto menor for, menor será.
o valor. Ou seja, pode amplificar ou
reduzir seu sinal de entrada. E o
conhecimento de uma rede neural
Isso dependerá exclusivamente de seus pesos.
Em outras palavras, se você tiver o melhor
configuração de peso, terá um
Precisão aprimorada em sua rede neural.
Agora, vamos dar um pequeno exemplo.
Mais complexo, mas ao mesmo tempo simples.
Vamos aplicar a função soma e a
função degrau também para ver o que
Acontece. Neste caso, temos x1 e x2,
que são as nossas variáveis, e é isso que
Queremos fazer previsões. Então faremos x1
por peso 1. Então 0 vezes 0 mais x2
devido ao nosso peso 2,0 vezes 0, que
resultará no valor zero. Ou seja,
Ele acertou o primeiro recorde. Nele
Em segundo lugar, temos 0 vezes 0 mais 1 vezes 0.
o que resultará em zero. Então, no segundo
O registro também estava correto. 1 por 0
0 mais 0 vezes 0 é igual a 0. Portanto,
no terceiro disco também
Estávamos certos. E no quarto registro
Temos 1 vezes 0, que dá zero, e 1 vezes 0.
que é igual a 0. Portanto, falhamos porque
Queríamos comprar um e não compramos nenhum.
. Então, neste caso de
Na configuração, obtivemos 75%.
sucesso. Isso levanta a seguinte questão:
como ajustar os pesos para melhorar o
aprendizado? Sabemos que o erro de
uma rede neural ou qualquer
algoritmo que aplicamos, seja ele uma árvore
A decisão, seja tomada pela KNN ou por outros, será a
Resposta correta, que é a resposta
que queríamos obter, menos o
resposta calculada. Em outras palavras, para
Atualize os pesos para o menor valor.
Se possível, faremos com que o peso seja n + 1.
ser igual ao peso de n mais o nosso
taxa de aprendizagem. pela entrada,
devido ao erro. Deve-se notar que a taxa
O valor de aprendizagem será um valor fixo.
estipulado pelo usuário. Então,
Retomando o registro onde falhamos,
Calcularemos o erro. Qual era o
erro? Era 1 menos 0, porque queríamos
Para prever um, queríamos obter um.
mas não conseguimos nada. Então, o erro
É um. Estipular uma taxa de
aprendizagem de 0,1. Vamos fazer a solicitação.
nossa fórmula para experimentar
Atualizar peso. Então, nós temos
que p de n + 1 será igual ao peso
anterior, que era 0, mais 0,1,
que é a taxa de aprendizagem, por 1,
que é a entrada, por 1, que é
Foi um erro nosso. Então obteremos p
de n + 1 = 0,1, que será o novo peso
Em todos os casos. Então, tipo
Temos 01, aqui ficará
01, aqui também se tornará 01
e todos os outros pesos que tínhamos
Eles se tornarão 01. E lá você terá
para realizar todos os cálculos
novamente para ver se o resultado é
correto. Então você não precisa ser
Eu acertei, já coloquei o valor aqui.
fim. Assim, com um peso de metade,
Alcançaremos uma taxa de sucesso de 100%.
Como você pode ver. 0 x 0 0 x 0 0 + 0 0.
Então, o primeiro registro foi
correto. 0 x 0 1 x 2 0 + dará que é
menos de um. Portanto, é zero. 1 x da
0 x resulta em 0. Portanto, somando os dois
Isso dará metade, que é menos que um.
Portanto, é zero. 1 x da, 1 x da metade.
Então, a soma + resulta em 1. Portanto, estávamos certos.
todos os registros. Então, uh,
Falando um pouco sobre a aplicação de
uma rede neural perceptron multicamadas
no setor energético brasileiro,
Vou falar um pouco sobre a minha iniciação.
científico, mas muito pouco, apenas para
para motivá-los a estudar o
redes neurais. Redes neurais
Podem ter diversas aplicações. Em
Este gráfico aqui, eu coloquei... uh... um
gráfico da velocidade do vento por
datas. Minha intenção é prever o
velocidade do vento e para isso
Eu utilizo dados de temperatura e umidade.
ar relativo. Hum, basicamente o
etapa principal para realizar um
previsão ou classificação é a
processamento dos seus dados. Thiago fala
Há bastante disso no canal, onde
Basicamente, você precisa saber como lidar com isso.
seus dados, aplique vários, uh, digamos
Assim, as partes estatísticas precisam ser capazes de
Obtenha maior precisão do seu
modelo. O que diferencia uma rede?
perceptron de uma rede MLP? A rede MLP
Terá várias camadas. Então
Você terá uma camada intermediária entre seus
camada de entrada e sua etapa, e sua etapa
função, não, função de ativação,
VERDADEIRO? Bem, então eu gostaria de
Obrigado, Thiago, pela oportunidade.
de ter compartilhado um pouco de
conhecimento sobre redes neurais com
todos. Espero que tenha sido útil.
Até a próxima!