# Cluster Analysis

- **URL:** https://www.youtube.com/watch?v=nzbCJ3iJ8ek
- **ID:** nzbCJ3iJ8ek

## Transcrição

Olá, meus amigos, sejam bem-vindos.
Hoje teremos nossa quarta aula de
análise de agrupamentos. Recordando
que a primeira foi a PCA, a segunda a RBA,
a terceira CCA e hoje vamos entrar em
cluster, que é uma técnica que, no meu
Na minha opinião, é a mais simples. Muito
Então a aula de hoje será muito
rápido. Primeiro, um pouco sobre mim.
formação acadêmica, minha trajetória profissional e
alguns canais de comunicação. ?
Caso alguém tenha alguma dúvida ou
sugestão? Primeiro, o que é o
análise de agrupamentos? Eu gosto muito disso.
Esta definição é do Professor Júnior.
César da P, que os grupos agrupados
objetos, de tal forma que os objetos
em um grupo são semelhantes ou
relacionados entre si e diferentes ou
não relacionado a outros objetos
grupos. Em outras palavras, vou tentar.
Explique isso a eles por meio desta imagem.
. grupos de análise de cluster
elementos com características
diferentes que, neste caso, são
Eles exibem cores diferentes: azul,
verde e laranja. E também identifica
o ruído, que neste caso é isso
pontos cinzentos, que são elementos que não são
Eles não possuem características semelhantes.
sem nenhum outro grupo. Então surge
A questão: como são os
indivíduos semelhantes? Para uma técnica
muito variado, eu uso principalmente o
Distância euclidiana, porque se
Ao observar esta imagem, os elementos de
O mesmo grupo está por perto. Nesse caso,
uma das maneiras de determinar se o
Os elementos são diferentes ou semelhantes?
otimizar a distância euclidiana entre
eles. Então surge a pergunta: o
A distância euclidiana é a única maneira.
para determinar se os elementos de um
Os grupos são diferentes ou iguais? Há
outras maneiras de analisar a distância
entre dois grupos ou elementos contidos
no mesmo grupo, e eu gosto muito disso.
utilize essas quatro metodologias que
Eles calculam a distância entre elementos ou
grupos, certo? O caminho de
representar os grupos formados para
por meio de uma regra de agrupamento é
utilizando um dendrograma. Pessoas, não
Eu poderia te dizer com certeza se o
O nome é dendrograma ou dendrograma.
Até agora não encontrei nenhum.
literatura que alcança um consenso.
Eu só queria mostrar que isso especifica
os elementos, agrupando aqueles que são
Aproximar e separar o que é diferente
por meio deste recurso gráfico chamado
dendrograma. Agora, pessoal, vamos colocar as mãos no
trabalho, no qual vamos trabalhar em R. Preparados?
pessoas. Hum, peço que você baixe o R e
R Studio, que é o que estou lhe dizendo.
exibindo. Peço-lhe antecipadamente que
carregar esta linha que irá colocar
disposição do banco de dados ou SS.
Este banco de dados está disponível em
o pacote de conjuntos de dados, que já vem
nativo em R. Este pacote oferece 50
observações, que são os estados
Americanos por quatro variáveis,
que são tipos de, digamos, crimes
urbano. É mais ou menos assim. Nesta
Nesse caso, vamos analisar nosso banco de dados.
que mostra os estados americanos
com a taxa desses crimes por cada
100.000 habitantes. Neste caso, é
A primeira coisa que farei é calcular o
resumos mostrando o mínimo,
primeiro quartil, mediana, média, terceiro
quartil e número máximo de ocorrências para
os 50 estados. Neste caso, trata-se de
de estatística descritiva. Segundo
Vou calcular a função Pairs com o
linha de tendência para ter um
visão macro do que é
acontecendo. Podemos ver aqui que
assassinato e agressão
Eles estão fortemente correlacionados, é isso.
quase uma linha reta. Provavelmente
Muitos ataques se transformam em
Homicídio resultante de roubo com violência.
Esse não é o foco da análise, mas
É para que você tenha uma ideia do porquê
Eu fiz este gráfico de pares antes
para chegar à análise de agrupamento.
Então, amigos, peço que carreguem
A biblioteca ggpairs para quem não a conhece.
ter. O primeiro passo é calcular o
distância entre os elementos de um
matriz. Neste caso, a matriz de
A distância pode ser calculada de várias maneiras.
formulários. Neste caso, listei quatro.
maneiras de calcular a distância entre
Os elementos de um conjunto. Eles são os
média, bairro, centroide e métodos
mediana. Se você tiver alguma dúvida, aqui
Existe um menu de ajuda para isso.
função para estudar como funciona e
Veja alguns comentários adicionais em
sobre o qual não entrarei em detalhes. Esse
Certo, pessoal? Para gerar o
dendrograma, vou usar a função
hclust, que é a ferramenta R que
produz os dendrogramas. Aqui estamos
Eles mostram alguns detalhes e também
Outros métodos que podem ser utilizados.
Se você quiser usar esses métodos,
Fique à vontade. Por agora, considero
que esses quatro são suficientes. ?
Certo, pessoal? Vamos. Primeiro
Vou calcular a matriz de distância do
banco de dados USArrests e eu farei uma estimativa do
método da média. Primeiro calculo o hc.
Então eu o coloco através disto
comando. A função de suspensão é usada para
alinhar todas as observações nisto
eixo. Por exemplo, eles estão assistindo ao
dendrograma. Se eu remover esse atraso, será igual a
-1, tudo ficará pendente. Você está me dizendo isso?
vendo? Então, deixo a suspensão igual a
-1. É o fator que lhe confere parte de
espaço. Então vou calcular o
mesma matriz de distância, mas para o
O método de Ward, uh, para o método
centroide e para o método da média. Em
Neste caso, vou calcular quatro.
exemplos. OK. Mídia, centroide, bairro e
média. Muito bem, pessoal, quero que vocês tenham
Anotado, vou dar uma passadinha rapidinho, porque
cada metodologia de distância de
O cálculo entre os elementos me dará um
cobrança diferente. É aí que surge a questão.
Qual destas opções é a mais próxima de
resultado mais confiável? Para isso, existe
uma função em R que é a
correlação cofenética. Isso diz isso
Em seguida, calculo uma correlação.
entre o vetor cofenético, entre o
matriz cofenética e a distância do meu
banco de dados. Aquele que mais me dá
Isso proporciona a melhor parceria. Eu vou para
Escreva aqui. Correlação mais alta
melhor distância usada no cálculo
do cluster. Certo, pessoal? A quem
Nesse caso, vou limpar isso e vou
calcular a correlação cofenética
para essas quatro associações. Nesta
Nesse caso, foi difícil. O vencedor foi
Foi ele quem ganhou, deixe-me ver.
Aqui, a média foi mostrada.
como a melhor configuração porque
atingiu minha correlação mais alta
cofenética. Certo, pessoal? Nesse caso,
Se você quiser decidir qual é o
metodologia que utilizo para produzir
O dendrograma, eu aconselho você.
calcular a correlação cofenética. E
Por fim, resta a última lição de
Esta aula. Deixa eu instalar o ar condicionado aí.
Você viu? Preparar. Eu quero saber
Quantos grupos poderei formar?
por meio deste programa. Pessoal, isto
A análise é muito subjetiva. Primeiro
O que eu quero que você perceba é que Carolina
O norte e a Flórida são muito
discordando dos outros.
Eles formam um grupo completamente único.
heterogêneo, um grupo completamente heterogêneo
diferente dos outros estados. Ei,
Eu mencionei anteriormente que isso se chamava
barulho. Portanto, tudo indica que
Flórida e Carolina do Norte, por exemplo
se relacionar com todos os outros
estados ou relacionados de uma maneira muito
distante, provavelmente é isso.
barulho. OK? Então, neste caso,
Vou gerar a média novamente, a
dendrograma médio e eu vou usar
Este comando. Com este comando eu posso
Escolha quantos grupos eu quero e qual deles.
Esta é a cor que vou usar para
Indique esses grupos. Neste caso, de
Eu escolhi quatro aleatoriamente, ok?
Então, neste caso, vamos...
Execute este comando. Você está assistindo?
que a Flórida e a Carolina do Norte formam
um grupo completamente antagônico ao
demais? Lembrando que eu posso escolher
Quantos grupos você quiser. Nesse caso,
Vou colocar cinco grupos aqui e vou
Coloque azul. Muito bem, pessoal. Bom, é só isso.
. Hum, existe uma técnica muito fácil. Apenas
Peço que se concentre nos cálculos.
na busca da melhor metodologia para evitar
para obter um resultado diferente daquele
Isso realmente acontece. Pessoal, é isso aí.
Muito obrigado pelo seu
participação, ok? O próximo
A aula será sobre o fatorial. Um ótimo
Acolho e conto com suas dúvidas para
enriquecer minhas aulas.