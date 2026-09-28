# Lesson 00 - Introduction - Applied ML with a Market Perspective

- **URL:** https://www.youtube.com/watch?v=THLsiPq2C4Y
- **ID:** THLsiPq2C4Y

## Transcrição

Olá, estudante, seja muito bem-vindo ao
curso Machine Learning aplicado dos
dados da decisão. Eu sou professor
Daniel Cadota e eu vou est te guiando aí
nessa jornada onde a gente vai aprender
o que que é o modelo de machine
learning, como ele funciona na ciência
de dados, quais são os fundamentos que
você precisa aprender para fazer seu
modelo, os dados que vão alimentar ele,
então toda essa parte de manipulação,
análise e tudo que vai envolver aí a
parte também de eh implementação dele e
como você vai poder ter boas práticas
com relação a versionamento e afins.
Bom, deixa eu passar aqui pra gente
colocar nos slides para falar um
pouquinho mais detalhadamente sobre a
nossa agenda,
beleza?
No geral essa daqui é a nossa agenda,
OK? Então, da gente começar aí a aquecer
um pouco nossos motores, a gente vai
trazer uma introdução a conceito de
machine learning. Então, o que que é o
machine learning? Basicamente, né? a
gente vai fazer esse overview
fundamental para entender esse conteúdo.
Eh, o que, quais são os problemas que
ele resolve, é claro, também é
importante falar sobre isso, quais são
as etapas de um ciclo de vida de um
projeto marketing learning no geral.
[roncando] E uma vez que a gente tiver
isso bem fundamentado, a gente vai pra
parte de dos dados, né? Então, onde a
gente começa ali a parte de trabalho
realmente das coisas, né? Um pouco mais
da mão na massa. Então, a gente vai
aprender um pouquinho dos conceitos de
TL. Então, basicamente, extração,
transformação e carregamento das
informações. Então, quais são as fontes
que eu posso usar? O que que eu tenho
hoje eh que pode alimentar o meu modelo?
Então, a gente vai fazer essa coleta no
geral, amostragem, que são algumas
técnicas ali do que que estatisticamente
falando vai fazer sentido para você
separar pro seu modelo. E a limpeza de
dados, basicamente é um pouco da
formatação ali dos tipos de você começar
a mexer um pouquinho com essa parte de
entender o que que é um dado válido, o
que que não é no geral, principalmente
falando em formatos um pouco mais eh
técnicos, né? Então, o que que é um
nulo, como que você trabalha com ele?
Eh, tem horas que você vai poder
substituir, tem horas que não. Então,
toda essa parte de limpeza inicial dos
dados a gente vai estar trazendo nesse
tópico. Bom, logo depois a gente vai
falar um pouquinho sobre análise
exploratória. Então, uma vez que a gente
tem esses dados limpos, a gente vai eh
debruçar aqui sobre a mesa pra gente
entender o que que eles estão falando
pra gente. Então, quais são os padrões
que eles refletem. Eh, falando um
pouquinho de regra de negócio, o que que
reflete no dado dentro da qualidade que
a gente tem, o que que não reflete,
porque muitas vezes eh a empresa ela tem
ali alguns dados que podem ter de
refletir alguma coisa, né, mas por
alguma questão um pouco mais de
qualidade ou às vezes coleta dessas
informações, ela não tá refletindo ali.
Então, basicamente a gente entender o
que que ele tá falando pra gente dentro
do escopo que a gente tá trabalhando,
tá? E aí dentro desses dados que a gente
tiver analisados, entendidos, feita ali
nossa análise, a gente vai um pouco pro
fit engineering. O que que é o fit
engineering? É o primeiro passo ali pra
gente começar a entender o que que vai
entrar no nosso modelo, quais são os
padrões que a gente quer que ele
reconheça e como que a gente pode
representar isso. Então, eh, sem, é,
claro, né, sempre tomando um pouco de
cuidado para não ser redundante e não
fazer com que o modelo acaba eh tendo
muitos tem tenha muitos vies, né? Então
vamos trazer um pouquinho sobre isso
também nessa parte de fint engine. Bom,
eh dito isso, a gente tendo isso bem
fundamentado sobre os dados, sobre tudo,
essa essa primeira parte basicamente que
vai ser a parte mais importante, que é
sobre o que que vai alimentar o nosso
modelo, né, a gente começa a parte de
introdução à modelagem. Então, a gente
vai falar sobre a parte de modelos mais
fundamentais, então os modelos mais
lineares, os modelos eh que vão
introduzir aí você nessa parte com
relação a entendimento do que que é um
modelo de machine learning, todas as
etapas que a gente vai ter que fazer de
fit, predict, quais são os
funcionamentos desses modelos mais
básicos que vão ser super importantes
esses conceitos pra gente poder
fundamentar depois as nossas técnicas
avançadas. Então, depois quando a gente
for falar de otimização, quando a gente
for falar de da parte de modelos
interagirem entre si, eh, que é a parte
que a gente chama de de ensembling, né,
a gente vai conseguir trazer um pouco
mais esses fundamentos com um pouco mais
de calma para não ter que já começar com
coisas extremamente avançadas e depois
explicando as mais básicas, tá? E depois
que a gente tiver muito bem explicada
essa parte no geral desse overview de
modelos, né, de como eles funcionam, o
que que eles são, a gente vai falar um
pouquinho sobre o deploy desses modelos
e como você pode implementar eles em
produção. Essa etapa, ela tá sendo uma
coisa bem diferente e interessante,
porque hoje é um grande diferencial eh
os cientistas de dados que trabalham com
modelo de machine learning e sabem
colocar eles em employ. Por quê? No
geral, quando a gente desenvolve o
modelo de machine learning, a maioria
das pessoas e cientistas, eles sabem
criar um modelo. Eles entendem, né, a
parte toda fundamental ali de limpeza de
dados, de análise.
Mas legal, uma vez que você termina seu
modelo, ele tá lá no seu notebook, que a
gente vai apresentar um pouquinho melhor
depois numa das nossas ferramentas que a
gente vai utilizar, realmente é o
Júpiter. Mas uma vez que você tem esse
modelo, o que que você faz com ele? Como
que você faz paraas outras áreas de
negócio, pro pessoal de engenharia de
machine learning, pessoal de engenharia
de dados, conseguir integrar esse modelo
com o que tem em produção, né? Então,
como você transforma esse modelo que
você criou em consumível? A gente vai
falar um pouquinho sobre isso, tá? E
muito mais sobre isso, né? Eh, pô,
legal, eu tenho meu modelo, eu quero
fazer uma melhoria nele, eu quero criar
uma nova versão, como que eu faço esse
versionamento de modelos? A gente vai tá
trazendo também. E além disso, claro,
monitoramento, né? Então, uma vez que eu
tô com o meu modelo lá em produção, como
que eu vou fazer para analisar se ele
continua sendo efetivo com relação ao
que eu quero trazer? Então, essa parte
basicamente vai falar um pouquinho sobre
a gente colocar esse modelo lá na
prateleira e a gente ficar olhando para
ele para ver o quanto que ele ainda tá
sendo respons, quanto que ele vai eh
resolver nossos problemas, o quanto que
ele ainda tá fazendo sentido ou quanto
que ele exige uma segunda versão ou um
retreino, né? Então é é um diferencial
que a gente tá trazendo ali no geral, tá
bom? E claro, tudo isso a gente vai
alinhar conceito e prática. Então, todos
esses tópicos, eu vou trazer um
pouquinho dos conceitos para te
apresentar como que funciona no geral
essa parte de eh conceitual
[limpando a garganta] no geral para você
entender como funciona, o que que
acontece ali por de trás. Depois a gente
vai um pouquinho pro código para você
botar a mão na massa. Vamos trazer
alguns exercícios para você pensar
também um pouquinho sobre como você
resolver alguns problemas com as
respostas, claro, mas trazendo um
pouquinho de provocação também para você
ver se você entendeu o conceito para
você conseguir aplicar ele. Beleza?
Legal. Bom, se você parar para pensar, e
esse daqui é um diagrama que a gente vai
discutir muito ainda ao longo do curso,
tá? E esse diagrama que a gente vai
discutir ao longo do curso, ele se chama
o Crispdm, que é basicamente o ciclo de
vida de um projeto de dados. E por que
que eu trouxe ele aqui na nossa agenda?
Porque se você for parar para olhar,
basicamente comparando o a nossa agenda
com esse ciclo, toda nossa agenda, ela
foi pensada nesse ciclo de vida do
projeto. Então, pra gente entender
certinho eh como funciona um ciclo de
vida, a gente vai passar por todas as
etapas deles. Então, foi basicamente
nessa ideia que a gente trouxe eh para
poder trazer essa sequência. Então, a
gente vai falar um pouquinho sobre
entendimento de negócio, entendimento
ali dos dados, preparação deles, como a
gente tinha falado ali no fit
engineering, a parte de modelagem,
avaliação também, super importante pra
gente ver se o modelo ele realmente tá
responsivamente,
né, como eu comentei com vocês, a
implementação desse modelo em produção.
Bom, então basicamente eu só trouxe ele
aqui, a gente vai secar ele com calma
depois e para mostrar porque que essa
agenda foi pensada basicamente nessa
sequência, beleza? Show.
Bom, e para finalizar essa primeira aula
aí, vamos trazer para vocês a introdução
do que que é um conceito, né? O que que
é o que que é o machine learning, né? O
machine learning no geral, trazendo em
poucas palavras, ele é basicamente uma
subárea da inteligência artificial que
ele envolve uns conceitos um pouco mais
relacionados à estatística
e a [limpando a garganta] parte
matemática. Bom, então vamos pegar esse
esse esse diagrama que a gente tem aqui
e tentar desse carar ele um pouquinho.
Essa primeira
essa primeira parte que a gente tem é a
inteligência artificial. O que que é a
inteligência artificial? A inteligência
artificial, basicamente ela tenta
mimetizar, né? Então ela tenta imitar
alguns comportamentos humanos dentro da
computação. Então a gente tem diversos
algoritmos que não necessariamente são
machine learning, muitas vezes são
algoritmos um pouco mais automáticos que
eles tentam replicar um pouco sobre o
comportamento humano ou o aprendizado
humano dentro do computador. E aí dentro
disso a gente tem uma machine learning,
que é essa subárea que basicamente ela
vai funcionar para conseguir aplicar
estatística, para conseguir resolver
alguns problemas, né? a parte de
estatística e cálculo. E dentro da parte
de machine learning, a gente tem as
redes neurais, que é uma parte um pouco
mais avançada com relação a esse
conteúdo, eh, que ela é bastante
complexa no geral, mas ela acaba
envolvendo muito os fundamentos de
machine learning. Então, toda essa parte
que a gente tá conversando sobre dados,
a fundamentação deles, a organização
dessas informações, se você eh quiser já
aprender sobre redes aprender sobre
machine learning primeiro é extremamente
fundamental, porque os conceitos que
baseiam o machine learning vão ser os
conceitos que baseiam as redes neurais,
tá? Então, eh, se você se interessa
muito sobre a parte de LLMs, né? Então,
basicamente, a parte dos assistentes aí
de de chat GPT e afins, eles estão ainda
dentro de uma subárea das redes neurais,
que são essa parte de grandes modelos,
tá? Mas basicamente esse é o conceito
geral do machine learning que a gente
vai estar aplicando aqui, beleza? Então,
vou parar de enrolar e já vamos começar
aí pras próximas aulas, beleza? Até o
próximo vídeo.