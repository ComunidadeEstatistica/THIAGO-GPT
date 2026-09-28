# Sapevo - M (Simple Agregation of Preferences Decision Making) no R - Prof. Thiago Marques

- **URL:** https://www.youtube.com/watch?v=V0Bwas6UZ2k
- **ID:** V0Bwas6UZ2k

## Transcrição

tá bom então vamos lá pessoal sejam
todos muito bem vindos aí vou
compartilhar aqui com vocês
o hotel do meu computador somente nho
nhu
me manda o último ismart
e aí
os trabalhos só uma dúvida vocês estão
vendo aqui só tutorial tá vendo a parte
aqui tá aberto aqui certo
é isso isso diretório no aberto aí o
diretório beleza tá bom agora esses veio
pt né
e já
e não abriu o pt ainda não não
bom então eu não compartilhou a tela com
ele
g1
e como eu vou te compartilhar aqui ó
e aí
a apresentação
g1
eu vou botar na apresentação aí conforme
for eu vou direcionar então agora vocês
estão vendo o restante né
ah sim agora sim beleza então pessoal a
gente vai falar aqui no método sap vu-m
tá que na verdade ele não método que foi
generalizado para multicritério né
múltiplos decisores tá mas ele já existe
há bastante tempo o meu professor lá do
instituto militar de engenharia para o
celular custos junto com o professor
simões ele conseguiu generalizar para
múltiplos decisores e introduziu também
uma normalização para a gente vai ver
ele tem esse nome aqui né parece já deve
ver que é uma coisa legal né é pelo nome
simple agreguei sofrem espécie de bairro
de não vectors multi de cisneiros e esse
tá peso enem então vamos começar aqui
então tem uma breve agenda aqui da
apresentação elementos do processo
decisório do madrid
o viés cognitivo de heurísticas análise
multicritério a decisão método ordinal
né só que rua introdução à linguagem r
algumas coisas que a gente vai passar né
porque isso aqui é um minicurso de 8
horas tá então a gente vai se até aqui
ou as coisas mais importantes né essa
essas três primeiras para aqui elementos
do processo decisório tomada de decisão
e viagens cognitivos e heurísticas a
gente vai passar a gente vai direto aqui
para análise multicritério aqui é mais
de elementos do estado da natureza
tomada de decisão objetivos
oi como é que você toma decisão né e aí
tem aqui aquelas teses do daniel
kahneman né que é o nobel de economia né
na verdade ele é um psicólogo né mas a
teoria dele é fantástica para baseada em
tomada de decisão né heurísticas e
vieses cognitivos e
bom então a análise multicritério tomada
de decisão e métodos multicritérios
tomada de decisão eles surgiram como
meta de apoio né estão ferramentas e
matemática existe cazes e não largamente
ainda utilizadas no mercado de trabalho
mas na pesquisa infelizmente né porque
eles resolvem muitos problemas tá por lá
no i-mid teve problemas no resolução de
drone para para poder usar em para
reforço policial teve escolher viatura
navio né então é tem tem grande
proporção é bem legal esses métodos de
pesquisa pesquisa operacional né eu como
ainda tô aprendendo muito né eu
desenvolvi esse algoritmo na disciplina
lá do instituto militar de engenharia né
e eu conheci um pouco mais desse mundo
de pesquisa operacional mas não sou
especialista né os livros
o que é a qualquer coisa que eu peço
desculpas se houver algum arquivo porque
eu não sou especialista no tema né o
pessoalmente desenvolveu um algoritmo né
e também aprende um pouco lá no
instituto militar de engenharia mais
longe de ser especialista na área tá
então é a gente vai ter aqui
é um método que foi proposto por gomes e
santos nem 2018 tá é uma nova versão do
nessa do sapeiro de 1997 né como eu já
falei mais antigo né e que ele
generaliza para múltiplos decisores tá e
introduzir um processo de normalização
né e matriz de avaliação implementar na
sua consistência e aí a gente tem lá os
métodos de pesquisa operacional mas uns
agrados né mas a gente tem na escola
americana tem o toddy o todinho ou hp
não alguns descem conhecia isso vocês
fazem engenharia de produção sobretudo
né e método saida da escola francesa é
teu prometer e não está pelo os apeme
ele ele é um método da escola francesa
nega arranquei a né as opções a gente
vai ver isso
a beleza e aí como é que consiste tem
que consiste o método não eu quis
avistei um pouco da parte matemática
para nós estar vocês na próxima querer
ir embora né aí eu coloquei aqui o o
básico mesmo para a gente direcionar
então primeiro passe transformação
original da preferência entre critérios
né ea expressa por um vetor
representando os pesos dos critérios tá
segundo passo transformação original da
preferência entre alternativas dentro de
determinado conjunto de critérios a
pressa por uma matriz de avaliação então
primeiro a gente avalia os critérios e
depois as alternativas tá no caso de
decisões que vão avaliar tá e finalmente
o resultado da preferência de três
alternativas aliexpress pelo retorno
resultante da multiplicação matricial
entre o vetor peso do escritório ea
matriz de avaliação das alternativas
ah tá e as alternativas são ordenadas em
ordem decrescente dos valores numéricos
como falei a método da escola francesa
então a gente vai ter um ranqueamento tá
mas antes
ah beleza então vamos dar uma olhada
aqui se se tá gravando silver tá tá
gravando beleza tom vamos passar próximo
então a gente tem aqui um case né onde
tinha tinha que ter uma ordenação de
equipamentos de freezer e uma
panificadora do rio de janeiro tá e aí a
gente tem aqui dois desses olhos né que
o renato e a branca tá que são
especialistas lá da panificadora e aí os
critérios que a gente leva em
consideração então capacidade custo de
aquisição e custo de manutenção tá
e ir o escritório os ajustes várias
alternativas que a gente tem a gelopar
metalfrio ou frilux tá são os tipos de
lá de freezer eles têm tá
oi e aí a gente tem uma relação entre as
opções e critérios né na escala numérica
tá os decisores eles vão ver essa parte
aqui tá eles não vão ver os números tá
mas eles vão falar vão fazer comparações
pareadas né entre os critérios eles
alternativas também tá e aí vai falar é
absolutamente pior é muito pior é
equivalente é melhor muito melhor
absolutamente melhor e com isso a gente
vai estar atribuindo absolutamente pior
menos três né até equivalente zero né e
absolutamente melhor três então vai uma
escala aí de menos três a três né uma
escala likert de sete pontos tá uma
coisa interessante aí que a gente
trabalha muito bem com o número 7 né que
a gente tem sete dias minha semana sete
maravilhas sete horas agora não vou
lembrar exatamente
e tem uma série de coisas que tem uma
número 7 né a gente trabalha bem com
essa escala de sete números tá
que legal
oi e aí a gente tem um decisor um com o
renato né e aí ele vai a gente vai
apresentar para ele umas comparações né
aí a gente vai ter aqui nas linhas ou os
critérios né capacidade custo e custo de
manutenção custo de aquisição e
manutenção né mas colunas a gente repete
também a capacidade custo de aquisição
continuar a intenção aí a gente vai
perguntar para o renato por exemplo se
capacidade ela é muito maior é pior ou
equivalente a capacidade então é só que
não precisa nem perguntar né porque
porque a mesma mesmo critério como é que
eu comparo do hospitais né a gente parte
do pressuposto que a equivalente certo
bom então se eu comparar capacidade com
custo de aquisição né e aí ele vai falar
beleza eu acho que a capacidade é melhor
do que o custo de aquisição tá e aí a
gente atribui um de peso tá capacidade e
custo de manutenção ele falou que é
muito melhor tá ainda ruim detrimento do
outro ele botou dois e assim por diante
ele vai dando as comparações não custo
de aquisição capacidade menos um repare
que quando ele pergunta capacidade com
custo de aquisição e o custo de
aquisição com capacidade vai ser o
simétrico dele né para fazer sentido da
gente parte do pressuposto que ele ele
vai responder simetricamente tá e quando
eu comprar o curso de aquisição com
jacques de som equivalente e assim por
diante tá absolutamente melhor ou pior
absolutamente melhor equivalente e
e a gente tem uma forma de fazer o quê
contabilizar como é que a gente faz a
gente soma as linhas né a zero mais um
mais dois deu três é um somatório aqui
para capacidade de três para curso de
aquisição - 1032 aí custo de manutenção
- 2 - 30 com menos cinco tá e aí a gente
normaliza não analisa de que forma a
gente pega ó o elemento rj que essa
dessa coluna aqui tá aí pega 3 - -5
horas que é o mínimo desses caras aqui
que há 32 - 5 não me não é menos cinco
aí fica 3 - 5 / o que pelo máximo menos
o mínimo o máximo é 3 e o mínimo é menos
cinco então vai ficar 3 - menos cinco né
vai ficar 8 / 8 dá um né beleza e aí
e a gente faz isso para o segundo
tamanho a2 - 5 / 36 - 5 aí dá 0875 e o
menos cinco pega ele tiro diminuir do
mínimo e dividir pelo máximo menos o
mínimo aí aqui de 10 tá só que que
acontece ele não pode ficar com pesos é
ah tá e aí a gente tem que normalizar a
gente tem que fazer aqui um artifício é
o seguinte quando de 0 a gente pega o
subsequente um por cento dele tá então
só ficou um aqui 0875 e como for zero eu
pego o subsequente do zero que 0875 e
faça um por cento dele que de 100 875
beleza até aqui todo mundo ok
e todo mundo acompanha aqui comigo
tá tranquilo
e eu tô vou ver se eu consigo abrir o
chat aqui ó
a música do chat
e aí
e eu não estou conseguindo ver o chat
alguém pode me falar o alisson depois
paulo chat aqui consegui tá beleza
consegui agora o flávio sim tudo ok ok
beleza então beleza vamos prosseguir
então vou minimizar aqui vamos
prosseguir beleza então relembrando a
gente está dentro dos critérios para o
decisor renato né e aí vamos lá e agora
a gente vai para segunda decisório aqui
é a branca a gente vai fazer a mesma
pergunta para ela as meio capacidade com
capacidade é o que que valente
capacidade de custo de aquisição muito
melhor
a capacidade de custo de manutenção
melhor cuja aquisição capacidade muito
pior e assim por diante tá ela também
fez a resposta dela né
oi e aí a gente faz a somatória das mim
ficou o que zerar umas duas mais um meu
3 - 2011 - um damos um exame eu nos dois
e aí vamos normalizar três quase que
pega o elemento tira o mínimo e dividir
pelo máximo menos o mínimo 3 - - 2 / 3 -
dois de 15 por cinco de um beleza faz a
mesma coisa - 1 - menos dois e vai
normalizando vai ficar um 0,2000 de novo
beleza não pode não pode porque essa não
pode ser e aí a gente faz o que faz um
por cento do na nova ou subsequente po02
0,002 repete cara aqui ficou 110 2008
beleza e aí a gente 6 plus
e séries né e agora a gente pode pegar e
somar por exemplo capacidade do renato
né que ele deu ir a branca aí ficou dois
o qual é o peso o peso ficou dois do
custo de aquisição era 0875 e da branca
o custo de aquisição era 02 ficou 1,075
tá renato custo de manutenção 0,008 75
branca 0,002 então a gente ficou com
dois 1,0 75 e 0,010 75 então a gente
conseguiu já os pesos do método só pelo
que foram arbitrados pelo próprio pelos
próprios decisões concordo a gente fez
uma uma quantificação da subjetividade
da escolha dos
um dos decisores a
o início a gente agora tem os pesos né e
agora a gente vai criar matriz de
decisão como é que a gente faz agora a
gente antes de comprar os critérios
agora a gente vai comprar as
alternativas aqui ó nas minhas a gente
tem as alternativas gelopar metalfrio tá
estão as alternativas que eu tenho três
ação de três vezes né e aí a gente tem a
decisão um renato dentro do critério um
capacidade tá e aí joga para congelar o
pai equivalente gelopar metalfrio o
renato falou que é equivalente para ele
também não tem diferença para ele tá já
gelopar com fluxo é muito pior
o metal frio com gelopar é equivalente
por simetria aqui né para manter a
coerência metalfrio vai ser equivalente
pior metalfrio confio no que você acha
pior metal frio looks com gelopar muito
melhor para o lux comentar o frio melhor
e frilux confirmou que você equivalente
para manter a coerência e aqui é o
simétrico né pior é melhor né é o
simétrico aquela metal free lux trilux
metalfrio a beleza e aí a gente faz a
mesma coisa só mas ninja 2 - 13 e aí a
gente vai normalizar - 2 - o mínimo
dividido pelo máximo menos o mínimo né
então ele ficou só que agora eu posso
ter zero porque eu não estou mais no
peso agora é a comparação das
alternativas tá eu só que não é mais o
peso
o que é para a gente criar uma atriz a
avaliação ea esposa 0021
o melhor e aí foi perguntar para branca
capacidade jogou par congelou para o
equivalente joga foco metalfrio - 1 e
mesmo estou indo né tá mesma coisa vai
só mais nem fizeram - 1 - 2 - 3
e aí 10 - 2 - 12204 vai normalizar aí
aqui deu 00285 743/1
e ai o renato vai falar agora do custo
da aquisição aí mesma coisa vai fazer as
comparações né vai normalizar vai ficar
008 751
a beleza agora branca vai falar do custo
de aquisição então
nós vamos fazer uma normalizar vai ficar
011 beleza muito demais agora o renato
vai falar do custo de manutenção ou seja
vocês estão vendo que eu tô indo decisor
critério desses outro detalhe né então
eu tô adentrando dentro dos critérios
para cada nesses outros tá então o o
renato custo de manutenção ficou 01 a 08
é a branca custo de manutenção ficou 01
e 08 também
bom e no final a gente tem agora a
pontuação aqui na capacidade a gente tem
a matriz de avaliação tá então a gente
olha desculpa a gente vai ter uma matriz
para casa para cada custo né para cada
critério desculpa e dentro do escritório
agora a gente vai formar a nossa matriz
de decisão como é que se faz essa matriz
de decisão né
se você pega aqui
e os critérios não ficou 00485 7143 e
dois né e aí ó
10478 712 né tá é virou aqui a coluna né
e aí essa coluna aqui do pontuação do
custo de aquisição virou a outra coluna
da matriz de avaliação tá
a pontuação do curso de manutenção onde
virou a outra coluna da matriz de
decisão e com isso a gente formou a
nossa matriste de avaliação alguém tá
com alguma dúvida até o momento
e eu tô passando rápido demais você que
está indo legal thiagão tá dando para
pegar tá tranquilo né beleza show
que legal e aí do momento que a gente
tem a matriz avaliação a gente pega a
matriz avaliação e faz o cruzamento né
um o vetor peso tá e aí a gente obtém o
nosso ranking tá e o nosso ranking ele
vai ser dado que a gente viu aqui ó que
o frio lux ele ficou com a maior
pontuação 6,16 72 o metal frio ranking
dois 3,00 85 o gelopar ranking três
ficou cozinhar aqui tá então a gente viu
que segundo os decisores né renato e
branca o free lux ele ficou bem superior
aqui aumenta o frio né tá
e no não sabe eu vou a segunda é melhor
alternativa foi o metal frio né e aí a
gente pode ver também dentro do da
importância tá eu vou mostrar no como é
que a gente faz então tira só uma
introdução aí né mas eu acredito que
você já já tem uma ideia ah eu vou
passar
só para não esquecer lugar muito aqui
oi e aí aqui foi foram desenvolvido
então 4 algoritmos da linguagem r tá com
input manual ou automático tá você pode
fazer manualmente ou botar para ele
gerar o input para você da função a o
objetivo de facilitar o entendimento de
problemas complexos de tomada de decisão
envolvemos critérios na multi decisões e
da celeridade as suas aplicações sejam
elas qualitativas ou quantitativas a
gente pode incorporar aqui tanto a parte
qualitativa quanto quantitativa sejam
elas as dívidas de qualquer esfera
pública ou privada disseminando assim a
aplicação dos métodos de pesquisa
operacional e tão úteis e pouco
utilizados ainda no brasil tá sobretudo
nas empresas tá os mesmos foram locados
no kit rubi para ser utilizados
publicamente nessa adolescência é mais
tipo é a mais tranquila de todas e cabe
ressaltar
o último desenvolvidos têm limitações
números decisores critérios tá a serem
incluso manualmente respectivamente até
10 decisões e dez critérios você
consegue botar até das decisões das
critério já as alternativas quantas
foram indesejados e quando eu for geral
do automaticamente as funções têm
limitações até cinco alternativas e
cinco critérios tá bom
a culpa e aqui então a gente entra como
é que a gente faz isso não é ruim né
então para utilizar o as funções
adequadamente a gente vai ter que estar
lá
e o débitos tá tchau por meio dele que a
gente consegue instalar o pacote viu kit
rubi tá porque ele tem a função está
houve derrame tá tem o comando live
débitos para carregar né sempre quando a
gente está no pacote a gente tem que
carregar a biblioteca tá e aí a gente
tem que estar lá o sapateiro em ponte
peço para ele gerar os pesos automático
em gerais entradas dos pesos está pronto
para utilizar na função satevo em
portugueses a um eu também tenho a
função as funções de sapé 20 rank né e
os apego ranking quer para você você
pode usar tanto manual quanto você pode
usar automático também a gente vai sair
comentei isso na prática e aí
basicamente tem que fazer isso aqui tá
eu sei que só se você na verdade você
precisa para poder botar um curtir aí
e como é que fica mais faro tom uma vez
instalado e devidamente carregar os
pacotes a gente vai começar a inserir o
nome do projeto os nomes decisões
alternativas e têm de avaliação tá então
como a gente viu o projeto é o que
panificador tá quem são os decisores
renato e branco
e quais são os as alternativas gelopar
metalfrio que está a gente coloca um
formato de vetor não é aqui capacidade
custo de aquisição e custo de manutenção
tá aqui a gente está gerando manual tá
está colocando manualmente a gente vai
virar uma opção que ele vai botar
automaticamente para a gente esses
recursos aqui tá então é só para
contextualizar aqui a gente tem lá a
comparação pareada entre os critérios né
aí a gente tem o decisor renato ele quer
dizer ao a gente quer gerar os presos né
e aí que que a gente coloca a gente da
entrada da matriz aqui de avaliação do
renato aqui parece pintar a uma ele
entrou aqui ó 01 2012 - 103 - 2 - 30 ou
seja é exatamente que tá aqui ó 012 -
103
o -2 -3 exame
ah tá e aí aqui
o agente gerou a primeira entrada né aí
a branca vai gerar também a a matriz
dela de comparação né e aí ó ficou 02
1021 - 2011 - 2011 - 1 - 10 - 11 - 1 já
tá
oi e aí ó a gente faz o que seleciona
todos os ninhos e aperta contra o gente
tá e aí a gente vai gerar o out vou
tipo tiver me dizer isso aqui ó ó o nome
do seu projeto é panificadora mas
alternativa de seu projeto gelopar
metalfrio hilux os critérios do seu
projeto capacidade de custo de aquisição
e custo de manutenção e os pesos do
método essa tv 62 1,075 e 0,010 75 né
para que a gente fez lá a gente tomou
todas as minhas fez as normalizações e
depois a gente criou a gente tomou para
cada decisões né a pontuação para chegar
nos pesos ele fez isso aqui é automático
para gente tá
e esse aqui foi o papel peso que você
tem que gerar o peso para jogar no tá
pelo ranking para ele conseguir fazer a
sua função eu coloquei passo a passo ou
para dentro para justificar o passo a
passo e ficar mais claro na tua cabeça
que tem que ser nesse passo a passo tá
eu poderia fazer uma função com tudo
junto né seria mais eu tinha eu tinha
menos tempo né seria mais difícil de
fazer e também seria menos eu acho que é
um pouco menos intuitivo de você fazer
isso aqui que botar muita coisa junta e
eu preferi primeiro gerar os pesos para
depois jogar no sapê romântico tá e aí ó
é o primeiro passo é colocar os vetores
resultantes de avaliação das
alternativas está agora está comparando
já dentro das dos critérios tá antes a
gente só gerar os pesos agora decisão um
renato critério num capacidade a gente
vai comprar agora as alternativas né ah
tá aqui a 00 - 200 - 1210
oi e aí aqui ó a mesma coisa só para o
ranking você vai botar as mesmas coisas
lá dos a pelo desapego peso botou o
projeto os decisores aí aqui você entra
corretor peso o vetor peso ele é gerado
automaticamente pula pela função quando
eu gero isso aqui eles não vieram o peso
na memória para mim tá e aí eu vou
colocar o vetor peso aqui tá e aí eu
coloco aqui ó retornar tá desse soro um
critério um eu desse soro um critério um
igual que 00 - 2 né que foi aqui ó 100 -
200 nos um aqui no primeiro passo né aí
dentro do segundo passo que a branca né
a branca vai gerar o dentro da
capacidade as notas dela e aí você vai
colocar aqui ó 0 - 1 - 20 - 22 anos
oi tá custo de aquisição do renato 00 -
3 - 20 - 3 - 230 - 1210
oi e aí eu vou colocando assim por
diante 0 - 3 - 3300 300 né que a branca
desse ano falando ah o custo de
aquisição renato com o custo de
manutenção sempre botando aqui ó desse
soro um critério dois desses dois
critérios dois desses ou no critério
três e decisor dois critério três e aí
eu formei a minha matriz na bruxa pelo
ranking e aí eu faço o quê selecione do
controle mente no momento que eu dou
controlar a gente ele me dá o nome do
seu projeto é panificadora me dá as
mesmas aí desde saveiro ap ro n né ele
repete aqui até o peso e aí além disso
ele me da matriz de avaliação do projeto
é aquela 00485 720 1,875 dois né tá e aí
ele me dá a pontuação do escritório qual
foi para cada critério né então a capaz
e ela teve dois pontos 4857 de pontuação
custo de aquisição teve 3875 e de
manutenção 3,6 então o custo de
aquisição foi o mais votado dentre os
decisores né sendo que o ranking do
projeto entre as alternativas o frio
looks se ele foi 6.016 que a gente viu
né primeiro no ranking o segundo a
metalfrio e o terceiro ou gelopar tá e
aí ela além disso a gente consegue ver
que dentro do não sofre lux ele foi
melhor como o custo de aquisição teve
maior peso na decisão do frio looks por
exemplo tá isso é bem legal só que
repare quando eu tô fazendo isso aqui
manualmente quanto quanto mais decisões
eu tiver imagina que só que vai ser a
esposa eo né imagina o número de
combinações possível né cada decisor
cada critério né cada uma eu vou ter que
eu vim aqui concordo isso é meio chato
isso é meio complicado com quadro você
vai ficar fazendo isso não tempão até
aqui todo mundo todo mundo ok entendeu
legal me dá me dá um joinha aí que que
tá tá tranquilo de entender tá beleza
beleza gelado falou aqui ok então a é
isso aqui vai explodir né é um cada de
cada decisão que eu acrescentar
alternativa
eu botei aqui ó uma tabelinha não só
tempo terça se eu acrescentar
alternativas eu não vou modificar a
função mas se eu botar tá critérios eu
vou ter carnaval entrar nas minhas já
existentes e mais caro entradas para
cada linha adicional imagina você mudar
10 decisório dez critérios e ideias
alternativas ou como é que vai ficar
essa coisa louca né você vai ter que
voltar esse na mão ia ficar um negócio
muito louco né então tu passa a vida de
vocês que que eu fiz
e eu criei uma função que gera simples
automático tá e aí como é que funciona
isso o nome essa peso input peso né que
você bota lá só teve input peso da
control entre e aí ele vai perguntar
para você olha qual o nome do projeto
qual o nome do projeto é você botar
panificadora aí decisório do projeto
qual o nome é você vai botar aqui ó você
vai ele a segunda entrada que ele vai te
dizer nem vai perguntar qual o nome do
projeto qual os quais são as decisões aí
você botar renato vivo a branca tá e aí
ele vai perguntar beleza mas quais são
as alternativas gelopar metalfrio hilux
qual é quais são quais são os critérios
do projeto capacidade e custo de
aquisição e custo de manutenção legal e
aí ele vai pedir para você avaliar os
critérios segundo o primeiro desses o
renato né aí beleza renato para posse da
diversos cursos que a 15
e o renato show era só absolutamente
pior muito pior pior equivalente melhor
melhor e aí você vai colocar eu botei
aqui não beleza renata achou que é
melhor aí capacidade versus custo de
manutenção o que que eu tenho que o
renato achou
a 2 o 2 é o que tem algo muito melhor
e aí renato custo de aquisição desses
custos de manutenção e que ele achou ele
achou o 33 chegar o que há três
absolutamente melhor tá e aí liberou
aqui o input para função só pelo peso
está que é esse cara aqui ó 012 - 103 -
23 aqueles eu tô concentrava manualmente
é ele que gerou e aí ele vai perguntar
avaliar os critérios para branca
capacidade vezes custo de aquisição e
você bota aqui dois muito melhor a
cidade versus custo de manutenção um
quer melhor e aí você vai falar com isso
daqui são custo de manutenção para
branca vai ser o quê
o melhor e aí depois que você faz todo
tudo isso aqui ele vai botar para você
olha os função sofrendo pesos em cultos
são esses caras aqui tá e aí como é que
eu vou colocar ele na ele gera isso aqui
também tá ele vai lá no canto superior
direito lá do erre você vai ter aqui ó
um vetor final né uma lista aqui com o
simples né as alternativas do projeto
salvas aqui os decisores projeto e aí
você vai botar o que nós sabemos peso e
vou botar o projeto que ele gerou aqui
automático decisões critérios
quem é e aí vetor sinal um eu é o índice
que tá aqui em cima tá eu tô afinar um
ver o final do chico um pouco vergonhoso
aqui tá porque para trabalhar com lista
então eu não consegui fazer uma coisa
mais simples mas você tem que colocar o
que tá logo aqui em cima tá ó o entre
parênteses 1 e 2 e aí o que que ele vai
gerar ele vai exatamente o teu output
que foi gerado lá manualmente 21075
0,010 75 tá e aí aqui você geral os
pesos né e aí a gente vai para o rank
que ele vai gerar as entradas para o
rake né mesma coisa tá você vai entrar o
nome do projeto desses olhos
alternativas e critérios avaliados
alternativas né agora a gente vai tá
valendo as alternativas
e ainda antes a gente ela olhava o que
escritórios agora a gente vai avaliar
gelopar vs metalfrio o que que o renato
acha em relação à capacidade a ele acha
que valem beleza e aí você vai avaliando
avaliando né e ele vai criando aqui os
inputs que nem lá no seu peso peso mesma
coisa vai avaliando curioso input
e no final ó no final ele cria todos os
inputs para você tá e o que que você
precisa dar para ele você precisa desses
índices aqui de cima para colocar lá
então lá que que eu preciso para botar
no seu tempo rank projeto desses hoje
alternativo escritórios o vetor peso e
aí aqui eu vou botar vetor notas desse
soro um critério um eu tô afinal de voto
o que o que tava lá na aqui ó aqui em
cima tá esse aqui são os teus índice
para que ele conseguiu entender de forma
automática lá tá então você vai botar os
índices
oi e aí ele vai gerar para você o sabe
eu vou rank 15 ti tá a história 00482 o
fluxo foi 6.16 32 e assim por diante
a beleza e aqui foram referências é que
são os artigos originais né e algumas
referências que foram utilizadas lá no
tutorial tá ficou ficou difícil de
entender como é que ficou tranquilo que
vocês acham
com o joaldo falou que o cara excelente
algum mal humorado falou que já rodeio a
legal que rodou direitinho
e sem problemas ah que legal tá show de
bola vou dragão fala aí me conta uma
coisa é eu não ficou muito claro para
mim no começo esse modelo ele foi
desenvolvido com base em algoritmos você
já existem é uma abordagem em
customizada criada pelo pessoal porque
né pergunta se ele já era um algoritmo
um tradicional de pesquisa operacional
né foi desenvolvido em 1997 né pelo
gomes é vamos lá deixa eu ver aqui só
para não falar besteira é gomes mesmo
acho que é isso é é um corpo bonito é
isso mesmo e aí que acontece esse método
ele era para um desses ovos só né e ele
não e ele gerava pesos negativos né
então imagina peso negativo que que é
isso né decide
com certeza que eles fizeram ele se
generalizaram para múltiplos desses
olhos né porque pô você pode usar para
mais decisores né esse método e ia legal
né porque porque esse método ele só que
só vou responder essa pergunta depois eu
falo isso é então ele se generaliza para
múltiplos decisões né e ele introduz
essa normalização que é pro costelas e
não ficarem negativos né porque não faz
sentido para essa negativo tem 10 né
então ele introduzir essa normalização
justamente para isso para acabar com os
pontos negativos eo zero tá e isso aí
foram as professoras lá do m que tem
algum paper disso publicado é o link vou
botar no lado de lego o lab levo é um é
um site que é uma compra com ele é uma
cooperação entre vá
olá tudo pá a instituto militar de
engenharia uff o lado de lá descer lá da
de petrópolis também a lncc né pessoal
lá de supercomputação também e esse lab
lego aqui ó tem todos os artigos lá que
foram utilizados no do meu professor
também tem o meu tutorial em tem os
novos artigos que inclusive tem os
métodos que a gente vai falar que depois
por exemplo no dia nove agora o
professor max instalador hp top 5 de
dois anos né correto do recente também
desenvolvido e ele vai falar aqui com a
gente e vai mostrar também uma solução
computacional tá para fazer o método e
tem nessa página aí você encontra muita
coisa tem as fotos lá também do pessoal
lá dos eventos tenho do lado do hímen
também profissão botão usando lá que
quando eu tava lá na disciplina isolada
lá para só botou lá
o segundo boladão lá demonstrando o
teorema de beijo é fumar engraçado da
foto lá ele botou você postou você
postou essa aí pois é aí foi uma
engraçado esse esse grupo é de pesquisa
é muito legal cara que tem muito
trabalho publicado né e tem como muita
coisa que tem livro aqui de graça para
vocês também tem muito muito muito muito
eu lembro que na live ele falou desse
desse desse site exata só vi ele aqui
uma vou mandar aqui o vou mandar o link
do kitsch do que eu desenvolvi já tá até
aqui né deixa eu pegar aqui em cima eu
só não deve ter visto ainda entrou
depois
tu tem whatsapp e aí você pode baixar o
tutorial né mas e se você tinha falado a
então o que que eu fica falando ia falar
aqui esse método ele é interessante
porque né porque imagina quando você tem
por exemplo numa estrutura militar né às
vezes o mais antigo ou que manda né
vamos assim né mas empresas é o que o
[Música]
aquela live do denis lá do o rico né o
raio-x page possam o pneu não estou mais
bem paga na empresa né então é tem
dessas coisas né nas empresas e tal e e
esse método ele é uma forma de você
conseguir ter opiniões distintas né de
pessoas de níveis hierárquicos distintos
né eu quero dar um pode ser feito por
exemplo um no computador né você pega lá
salvar depois de você conferir os
resultados né cada um faz separadamente
as opiniões deles e você
o pila a opinião e aí você pode usar
isso por para ele coisas por exemplo rh
rh difícil pra caramba você selecionar
um candidato né e aí será que se eu
pegar celular quatro especialista de rh
e fazer o método de se e falar para o
cara olha você não foi escolhido por
causa desse método aqui ó é muito mais
interessante do que você falar
simplesmente que ele não for para tua
cara né ah não você não preencher a vaga
porque não é do perfil da empresa tá não
olha só você foi avaliado por quatro
especialistas dentro desse método aqui
científico e eles chegaram a essa
conclusão aqui isso é sensacional né
tira totalmente o viés né o efeito
manada né de ter autoridade não do cara
aí de acordo com quem tem mais
autoridade nesse tipo de coisa né então
você acaba tirando essas limitações es
viagens né e tem uma uma coisa mais
justa né mas a justiça ali no critério
de decisão baseado em algo científ
ah tá então acho que era isso eu eu
fiquei feliz que deu bom aqui porque foi
demais demais acho que essa abordagem é
super interessante uma coisa que eu
percebo que é que é legal e todo esse
caminho aí desses dados estatística é
que ao longo do tempo dessa jornada aí
você vai vai passando enxergar as coisas
de forma sistêmica e estatística então
você vai falando eu vou pensando é só
hoje que eu posso usar isso né então
quando você vê um conceito novo
algoritmo logo abordagem nova você já
consegue mickey entender como é que você
vai usar isso isso é legal ai faz
sentido porque tem coisas que a senhora
foi caro não entendi não é que essas
hoje não entendeu não vejo sentido de
usar isso é mas é só um motivo bastante
cara para procriar essa essa função aí
que sabe que ele falou falou olha se
você desenvolver s
e não erre e a biblioteca não é aí né eu
utilizo da prova eu falei opa agora aí o
motivo motivação que eu precisava aí eu
com cargas inha né falei na outra vamos
lá né que legal bem legal eu vou ler os
peitos aqui tentar entender um pouco
melhor e por causa assim não foi
desenvolvido a melhor forma possível né
assim eu sou meio programador de
botequim né não tem não tem muita
prática com programação assim né eu sei
orientado a dados cinemais programação
de programação mesmo né eu sou um pouco
falha é eu não tenho tanta habilidade
assim então ficou bem nervoso na mas o
negócio daí assim se fosse colocar no
clã com certeza de rejeitar ele não tá
não tem por que não confere cheio de
regra né eles têm umas regras bem
rigorosa né eu tava conversando com o
júlio trecenti inclusive
o pacote né no clã e eles têm uma regra
super rigorosos para colocar o pacote no
crédito do mais né assim para você
desenvolver e porque aqui como tinha
muitas muitas entradas eu eu teria que
fazer algo com listas né e tentar fazer
menos possível né tentar botar mais
enxuto por cima mas acabou ficando um
pouco grande né não ficou melhor forma
consigo não ficou tão otimizado mas
assim tá gerando rápido né então acho
que tá tranquilo tá assim eu achei legal
também fica bem simples objetivo se
fosse aqueles manuais ia ficar fora
imagina 10 decisões da escritório quanto
está saindo digitando como eu já fiz
automático então beleza já fica mais
tranquila né você pode usar para 10 vai
até cinco né porque
e o número de combinações é absurdo
assim inclusive quem quiser pegar o
algoritmo aí tentar otimizar para
aumentar o número desses olhos é válido
também né eu consegui esses imputes
automático acho que foi para as cinco
decisões 5 hectares e cinco alternativas
se eu não ligar mas o manual se pode
botar quantos quiser não tem uma
alimentação lá de 10 desses olhos eu
acho daqui pede e alternativa pode à
vontade tem alguma coisa no crie um
tutorial você tem lá é mais expansivos
né mas é mais nervoso de você colocar de
manualmente né são muitas combinações
então já já ajuda bastante aí e também
tem uma outra alternativa que a foi
desenvolvida a biblioteca também no
quarto né só que não foi foi para
interface web né que a gente fez aqui
com
e o frederico ele que desenvolveu
inclusive é
o apego é vou botar para vocês também
parece que tá fora tá né essa não não eu
botei aqui o que é que tá fora
o que passar na hora que você manda ele
geral resultado ele tá dando erro aonde
tá falando é
a peça está qualquer cadeia decisão aí
manda gerar resultado resultado agora
foi não agora foi é porque eu testei com
quem mais cedo tava dando erro ah tá bom
beleza então então é esses apego é daí
ficou bem simples tá eu ganhar uma
interface bem amigável para você colocar
a livre desses hoje quem quiser fazer lá
também fica à vontade né quem quiser
usar o r também tem alternativa que tá
então acho que era isso aí minha
contribuição já que a professora aline
teve problemas aí com a internet dela
infelizmente ela está falando aqui com a
gente já nós multivariada aí eu vim
apagar o fogo aqui de última hora né fez
o conteúdo aí de primeira mão para vocês
porque eu não tinha feito ainda essa
essa hora aqui lugar nenhum eu vou fazer
no final do ano lá nós come né que eu
congresso logístico da marinha né mas eu
não tinha feito com
e fala aqui tava tranquilo que foi muito
legal foi muito legal gostei bastante
que bom legal que bom que vocês gostaram
o flávio falou aqui bom demais maldonado
meus parabéns joabe grande tiago os
preparativos para o big brother brasil
game show de bola cara preparativo tá a
mil né eu vou dar um curso lá dia 21 e
22 quem quiser prestigiar lá é um curso
de introdutório né de estatística
aplicada no r a gente vai estar falando
dr em seu estado da artística vai ser
bem legal
o show de bola obrigado cara legal que
bom que você gostou da aula tão pessoal
obrigado aí pela presença de todos valeu
pessoal boa noite até a próxima então
boa noite valeu tchau tchau
em qualquer coisa qualquer dúvida é só
mandar valeu