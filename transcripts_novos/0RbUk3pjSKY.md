# Demistificando Séries temporais - Fernando Amaral

- **URL:** https://www.youtube.com/watch?v=0RbUk3pjSKY
- **ID:** 0RbUk3pjSKY

## Transcrição

olá pessoal aqui é quem fala é fernando
amaral tô aqui então de novo no canal
está de dados para a gente falar um
pouquinho de séries temporais em um
pequeno tutorial de séries temporais
primeiro vamos falar que o que é uma
série temporal que caracteriza uma série
temporal com a característica é que são
dados coletados intervalos regulares e
tempo esse intervalo pode ser qualquer
um milissegundo hora de a minha semana
ano qualquer tipo de intervalo de tempo
ea esses dados eles têm uma dependência
com a ordem da então eles têm que ser
analisados observados de acordo com a
ordem se você mudar a ordem é você não
tem as mesmas propriedades então existe
esta dependência
se você analisar por exemplo o modelo de
classificação de doenças você tem
sintomas do paciente em uma classe que é
uma doença
nesse caso você não tem características
de série temporal porque não existe uma
relação com o tempo não existe uma ordem
existe uma dependência com o tempo
também é a principal característica de
uma série temporal existe é uma uma eu
diria se o medo né e até com preconceito
com séries temporais que as pessoas
entendem que o assunto é muito complexo
é muito difícil
é isso tem um motivo você está vendo
aqui uma das primeiras páginas do livro
de análise só saem senhores de crist
atilde o que é um clássico da área de
séries temporais
já nas primeiras páginas que você está
lendo aqui você vai ver formas enormes e
a maioria das séries temporais são assim
então isso torna o estudo no assunto um
pouco intimidador
normalmente as pessoas desistem de
estudar séries temporais por isso e na
verdade você pode compreender séries
temporais é analisar essa temporada
explora certa pra gente foi que quer se
de séries temporais análise provatórios
enfim sem ter que se a aprofundar
pelo menos inicialmente nessa matemática
toda e é isso que eu quero mostrar um
pouquinho aqui neste neste vídeo neste
tutorial
então quem está vendo uma um exemplo de
uma série temporal é então a gente está
vendo aqui existem dados coletados né e
esses dados são coletados até 1978 e eu
quero fazer uma previsão não quero
prever de 78 por exemplo até 1980 em
séries temporais assim como na china ele
existem várias técnicas existem vários
algoritmos que você pode usar pra nós é
a previsão então pego rio a roda alguns
algoritmos para fazer a previsão dessa
série temporal mesmo para fazer esta
população é de 78 até 81 1º ao marítimo
que o roda né ele me traz como previsão
a gente está vendo aqui previsão a esta
linha vermelha ainda simplesmente parece
ele pilotou uma linha reta não é pra
fazer a previsão ok
enquanto um segundo o ritmo aqui e aqui
a gente tem né a previsão então vejo que
aqui a previsão ela tem as subidas e
descidas assim como a parte anterior a
ltda da série temporal os dados os dados
originais roda uma terceira um terceiro
a origem de previsão aqui que ele também
ele bota uma reta mas é inclinada aqui é
decrescente
se você é vamos supor que esses dados a
que fossem dados importantes para o seu
negócio e você tivesse que pilotasse
você tivesse que decidir tomar uma
decisão importante que pode definir por
exemplo o futuro da empresa baseado numa
dessas previsões qual nessas previsões
você ea escolher então vou daí
um segundo enquanto vou falando para
você escolher nem a você iria pegar
previsão a previsão mail a previsão se
então tem um pouquinho qual que você ea
escolher
bom então eu imagino é que você iria
escolher essa que me a previsão b porque
é mesmo sem saber nada de séries
temporais intuitivamente a gente ia
pensar que a previsão bem mais correta
bom simplesmente porque a previsão b
ela parece seguir o padrão dos dados né
ela é a gente vê que existe um padrão
nas subidas e descidas ea previsão aqui
ela parece é acompanhar esse padrão
então aparece que detectou esse padrão e
ela faz uma previsão acompanhando esse
padrão agora a previsão a não nela tem
parece ele tem uma linha reta e aqui a
previsão ser é uma linha inclinada
então na verdade foi que c'est de séries
temporais na previsão de séries
temporais extrapolarem aprender pra
frente
nada mais é do que tratar de compreender
os padrões da série temporal se ela
apresentar alguns padrões é a gente vai
ver que existem séries temporais que não
apresenta um padrão nenhum né mas é
assim mantém detectar esses padrões
entender esses padrões e projetar esses
padrões para o futuro é isso que o
marítimo de séries temporais têm que
fazer em que padrões são esses é quais
padrões que as séries temporais
apresenta bom
existem três principais padrão padrões é
que essa sazonalidade a a tendência e os
ciclos
então aqui a gente está vendo uma série
temporal e aqui a gente está vendo a
decomposição de compor uma série
temporal é extrair a alguns desses
padrões da série
então vejo aqui o primeiro na
decomposição a gente tem uma se a série
original então
este gráfica que nada mais é do que a
representação nesse aqui por inventar
demais mais estreito
esse segundo gráfico aqui ele extrair
uma sazonalidade
então vejam que a sazonalidade ela tem
um padrão altamente definido irregular
aqui né é um interessante aqui ó que a
gente está vendo aqui o padrão sazonal a
turné ele está atingindo de forma pura
aqui no gráfico original a gente vê que
existe em picos né mas ele está junto
com uma uma tendência é uma reta de
inclinação aqui não é o o objetivo aqui
de decomposição eles traiu na saída
temporal apenas a sazonalidade e um
outro padrão que a gente tem aqui é a
tendência então é semelhante aqui há uma
a uma a uma previsão de ser de regressão
é linear é onde a gente tem uma reta que
pode ser inclinada né
de acordo com algum ângulo e depois aqui
o último elemento é o que a gente chama
de o assombra o ruído são aqueles é
elementos aqueles dados da série
temporal que não puderam ser explicados
matematicamente então provavelmente eles
estão ali devido a algum fator que a a a
equação matemática que foi aplicada na
decomposição da série temporal não
conseguiu explicar então normalmente uma
série temporal
ele vai ter o que a gente chama de ruído
ou uma uma sobra o restante é que não é
nem um efeito sazonal
nem tendência o outro padrão que séries
temporais apresentam que não estão
representados em que graficamente a um
ciclo da então ciclo são exemplos que
ocorre esporadicamente mas são
diferentes do padrão sazonal o padrão
sazonal ele se repete em determinados
betão por exemplo o clima não têm
padrões sazonais é eu por exemplo aqui
eu moro no rio grande do sul
o o os padrões de clima que eles são
mais acentuados né
mas eles se repetem a cada ano né eles
são eles são é repetitivo é o ciclo são
padrões que ocorre eventualmente por
exemplo um efeito climático como eu nem
ele é um círculo e ocorre eventualmente
então o que é uma um foguete de 7 para o
faz é detectar os padrões no
comportamento do fenômeno que está sendo
analisado e ele tenta projetar isso para
o futuro
agora é claro que assim como em qualquer
outra área de negócio você não pode
eu diria assim se basear exclusivamente
no o marítimo é você precisa conhecer o
seu negócio e você precisa fazer um
balanceamento diria sim entre o alto
ritmo e o mundo real
então eu tenho um exemplo é vejo aqui
essa essa previsão né
então a gente vê que essa série temporal
ela tem uma tendência muito forte de
crescimento o que é oferecido tem que o
o marítimo que fez ele projetou esse
crescimento daqui pro futuro se eu
fizesse uma previsão aqui é mais pra
frente provavelmente essa reta que ia
crescer ao infinito
agora o que acontece vamos supor aqui
que seja um crescimento de um negócio
não há uma empresa que deu muito certo
bom a gente sabe que nenhuma nenhum tipo
de negócio vai crescer internamente né
de forma a expor potencial continua pra
sempre né então por exemplo quem tivesse
usando aqui uma técnica de flor e c'est
ele ia por exemplo usar uma técnica de
amortização por exemplo então a gente vê
que em vez de crescer é ao infinito o
uaw o crescimento é que ele foi
amortizado
a organização claro que o marítimo mas
não sabe de que tipo de negócio se trata
então ele não vai aplicar por si só
amortização então eu digo que assim como
em outras áreas da ciência de dados tem
que existir em uma um balanceamento
entre o mundo real é o negócio a
compreensão do negócio e a estatística
ea gente falou que uma técnica de flore
cast ela tem que usar ela tem detectar
padrões de fazer uma projeção desses
padrões para o futuro e quando a gente
não tem um padrão nenhum é você vai se
você começar a trabalhar em setembro
você vai ver que existe é muito comum
saída temporária e não tem padrão nenhum
é sempre agendados financeiros por
exemplo em bolsas de valores e enfim fiz
uma série de tipos de dados do mundo
real que não apresenta um padrão nenhum
é o chamado rendam ao que o passeio
aleatório então obviamente que aqui não
existe como você detectar um padrão
existe o marítimo que vai detectar um
padrão e fazer um filme crash futuro
porque o padrão não existe o que se faz
nesse caso o montillo se você quiser
fazer uma uma previsão aqui você vai
usar uma coisa mais simples por exemplo
como uma uma média você vai aplicar a
média você pode aplicar à média de um
peso maior para as últimas observações o
tempo você vai aplicar uma técnica mais
simples
uma outra questão importante aqui com
relação às séries temporais é que é
existe as medidas de tempo é criadas por
nós humanos que são baseados obviamente
na natureza do do ciclo da terra mas só
que a série tem paraense ela não tem
conhecimento do que quer um dia o mesmo
ano isso é um erro que se comete quando
se tenta fazer uma análise uma
decomposição temporal até temporal ela
não entende ela não tem internamente
a apreensão por exemplo de dia o
entendimento dela o que ela precisa é
ter fé em noção e ciclo e freqüência
então ciclo é o período de repetição do
fenômeno então ele é parametrizado
através da frequência na série
então vou dar um exemplo aqui pra vocês
é é às vezes eu eu vejo as pessoas fazem
a mas eu tenho dados coletados de hora
em hora qual que a frequência mas ele
entende se você tem uma linha de
produção por exemplo o ciclo o ciclo
pode ser um dia então a freqüência seria
24 horas porque o fenômeno ele começa a
se repetir o ciclo do fim do do negócio
começa a se repetir a cada um de quatro
horas
agora por exemplo se você está estudando
o clima é e você está coletando dados de
hora em hora da mesma forma que a linha
de produção o ciclo aqui já é um ano
é como o processo ele começa a se
repetir ea freqüência ingleses e 24 900
1736 só pra citar alguns
alguns exemplos não existe muitas muitas
diferentes técnicas de forecast previsão
de séries temporais
o animai a sua organização esse
potencial são as mais utilizadas e uma
de minhas sensações mais robustas mais
eficiente não pode dizer que uma é que
um é melhor que a outra né e depende
muito da série temporal existir séries
temporais em que uma vai ter uma
performance melhor que a outra mas a ou
ainda com certeza é mais popular o que
mais existe é é bem comum acontecer caso
em que a aplicação das organizações
potencial tem uma performance melhor
então as organizações podem salvar tem o
princípio básico que as observações
passadas possuem peso e quanto mais
recentes observações maior os pesos para
as previsões
isso é uma coisa é eu diria assim bem
intuitiva
então imagina que você está estudando um
fenômeno você quer fazer uma previsão
para o futuro
vamos supor que você queira aprender
esse intervalo é que essa janela é é bem
eu diria assim é bem intuitiva você
imaginar que quanto mais longe os dados
menor a influência deles nessa previsão
porque porque o mundo muda mesmo um
mundo natural mundo real mundo de
negócios ele muda então é previsível é é
é o diretor criativo supor que quanto
mais distante na previsão maior o efeito
sobre a previsão inicial esse é um
princípio básico das organizações
potencial já há algum outro princípio
diria sim importante que está falando de
the fury teste de séries temporais é que
quanto mais longe e aprender
quanto mais longe e fizemos a previsão
maior é a variação eu tenho que esperar
porque é pelo mesmo motivo de que quanto
mais longe da previsão um é o menos é
mais incorreta deve-se influência porque
enquanto o mundo aqui né está andando né
moto o as coisas acontecem no mundo muda
as coisas mudam então ah ah ah
normalmente as previsões aqui elas
aumentam aos as margens de erro quanto
mais distante você quiser a sua a sua
previsão a outra técnica importante aqui
com relação às séries temporais é o
arrimo né
o animal é composto por três elementos
que é o que o ney eo p
o que é a ordem da média móvel o deu
grau de diferença de diferenciação que é
obtida através de um teste de estacionar
idade e o pl ordem na parte alto
regressiva então a ordem da média móvel
geralmente usa um gráfico aqui
o acs pra obter essa ordem
o grau de diferenciação e faz um teste
de personalidade eo pp a hora da partida
e merecia a gente geralmente vê através
do clássico chamado a cef o alimentam
ele pressupõe que a série seja
estacionária ou seja que ela fruto em
torno de uma média constante se ela não
for estacionário não significa que você
não pode usar a língua você precisa
transformar estacionária é este elemento
aqui eu deu grau de diferenciação
o objetivo da diferenciação é
transformar a série em estacionária está
começando a estudar as séries temporais
pode ser bastante intimidador definir se
esses três parâmetros é o que pedem o p
mas a boa notícia é que existe o o o
erre por exemplo ele tem o alto lima ele
escolhe o melhor modelo a melhor
combinação de modelo pra você
ele usa métricas de performance para
testar a combinação que tem o melhor
desempenho é e muitas vezes é o alto
anima é ele consegue uma combinação de
parâmetros ali bem mais eficiente bem
mais acertada do que alguém que já tenha
alguma alguma experiência no uso de arma
de séries temporais a desvantagem do
doutor lima que ele é como ele vai
testar as combinações de de modelos né
desses três parâmetros ele pode demorar
um pouquinho até até a criação de um
modelo do modelo um pessoal então é isso
espero que tenham gostado é no próximo
vídeo então eu eu faço eu apresento uma
aula prática da icon forecast de séries
temporais até mais e obrigado