# Luiz Paulo Fávero (Professor titular de DS e Business analytics na FEA/USP) - Modelos Multinível

- **URL:** https://www.youtube.com/watch?v=7SOV3GRl5kg
- **ID:** 7SOV3GRl5kg

## Transcrição

o começo a gravar aqui então beleza
então pô sou suspeito aí para falar do
nosso flávio né já eu conhecia aí por
meio da adriana geday adriana silva né
que eu conheci no linkedin perturbando
ela lá na depois eu vim a conhecer ela
lá no big data brasil dele e aí foi
quando ela me falou do professor fábio
né muito muito muita coincidência depois
ele veio conversar comigo com o mestre
douglas também lá da mantiveram né para
falar comigo lá pô você não quer ser
conselheiro lá na mão tiver e tal com o
gosto do seu trabalho mas eu falei pô
caramba fiquei muito lisongeado imagina
cara e cara da catedrático assim como o
spaulo fazer nesse falar assim do meu
trabalho faço mais então fiquei muito
honrado né e com a gente já teve aqui
uma live que foi sensacional também né
mostrando a
a estatística hoje o tema é um pouco
mais avançado né bem bem bem uma
residência na minha qualquer pessoa que
consegue fazer uma aula desse tema né
que realmente é complexo mas acredita aí
que o mais fácil ele vai descomplicar
ele para gente por favor é humildemente
aí se apresentar falar um falando um
pouco aí da pode falar da mão tiver
também né na tua consultoria de
treinamento também fica à vontade por
favor seja bem-vinda mais uma viola
obrigado tchau e boa noite boa noite a
todos o áudio tá bom tiago tá ótimo tá
ótimo tá bom boa noite a todos meu nome
prazer mexer novamente convidado para
participar da live no canal e santidade
com thiago marques o tiago que realmente
faz um trabalho inestimável é de trazer
conhecimento compartilhar um trabalho
turno dia a dia postando
tô fazendo aquela vez mais pessoas e
compartilhando conhecimento e se
realmente essa todos nós enquanto lá são
né todos nós ganharemos então parabéns
tiago pelo melhor minha honra pode
sempre contar comigo tá admiração
respeito e admiração respeito e são são
recibo fizemos com você bem colocou uma
live sobre introdução estatística e
várias métricas e o brasil sobre as
técnicas né alguma coisa em torno de
seis meses atrás a funcionamento de mais
ou menos mais fiz mais ou menos isso né
ou tiago me convidou para falar sobre
modelagem multinível eu me em curso e o
professor marco charneski também está
aqui e também quero transmitir os meus
agradecimentos e um enorme prazer uma
grande honra viu marcos aqui tô puxando
experiência e aprendizado com você o
marcos me convidou jo o
e também respondeu passagens curso lá
naquela ocasião a gente oferecer um
recurso com aplicação estimação os
modelos em r hoje ainda não chegaremos
nesse ponto de estimar de abrir o r
estimar é porque a gente vai falar sobre
todos os conceitos mas o tiago já
adiantou que eu vejo a vontade a
intenção desejo era poderemos partir de
uma live 2 que é justamente abril r
comandar uma planeta códigos costas
podem ser distribuídos anteriormente etc
para que a gente possa mostrar com
exceção dos cursos é de códigos
inclusive bastante recentes e modelagem
multinível na plataforma r como lado do
asteca glm.nb e é uma biblioteca muito
recente que estima meu nome é bonita
hein é grande assim g larga glm.nb
biblioteca
há um ano dois anos de existência na
avenida de publicação para aqueles que
têm interesse mais acadêmico e uma
avenida a gente alimentação de modelo de
tomada de decisão para aqueles que tem
um pé é no mercado também eu vou dar
alguns exemplos inclusive de aplicações
reais é do que a gente tem feito com
técnica no mercado instituições
financeiras modelagem de risco de
crédito por exemplo e alocação de
recursos segundo alguns exemplos eu fiz
uma palestra na embraer agora dois meses
atrás e o cara não é o nosso certamente
foi carnaval acho que uma semana do
carnaval em várias áreas na comunidade
de dados da embraer e
a cidade fantástica recente instante
inovadora também então realmente muito
obrigado eu vou aqui tomar um banho a
liberdade thiago por favor de
compartilhar por favor pode compartilhar
e antes eu queria só queria saber se
você vídeo lembra alguma possibilidade
de usar de utilizar essa técnica para
estimar por exemplo aí a taxa de
crescimento do coronavírus então é sim
desde que algumas premissas sejam
estabelecidas por que qualquer modelo
preditivo é e uma delas multinível ela é
é uma técnica supervisionadas mach lane
em vou contextualizar ele daqui a pouco
mas ela também usa fundamentos de um
super vai ser mach lane porque você
precisa ter algum celular em que a gente
vai atualização seja costumo dizer que a
onde as técnicas relacionadas é é um
beijão
e as técnicas não supervisionadas esse
beijo e dá na modelagem multinível então
adiantando sim é possível é mas desde
que algumas premissas estabelecidas
porque como nós vamos modelar também
processo estocástico eu vou falar já se
a estocasticidade os termos de erro
forem superiores a qualquer premissa
estabelecimento de estimação de
parâmetros thiago como é o caso de
qualquer série temporal para detecção de
comportamento de evolução por exemplo
desta doença é aí você precisa ter
alguns critérios de estabelecimento de
plantas por exemplo os países inclusive
para que a gente possa ter uma melhor
acurácia de aderência entre os valores
reais valores fixos e tô querendo dizer
o seguinte lá que a curva brasileira vai
ser a mais parecida a deus por aqui não
a curva italiana ou será que ela se
aproximar mais a cultura chinesa logo
japonesa agora
a mariana que poucos falam mais tarde
como sempre volta tragédia no milan etc
então quais são os prêmios para que a
gente possa modelar os interceptos entre
nações aleatórias e consequentemente
respectivos termos de erro mas vamos
falar um pouquinho mais conceitualmente
sobre sobre esses esses esses pontos
beleza show de bola show de bola tá
vamos lá eu vou compartilhar aqui você
tchau é bomba quando você então dá pra
tá vendo minha tela sim sim tem que só
maximus beleza
ó tá vendo tudo bem sim sim tudo aqui na
verdade é bom então vamos começar a
melhor como está vendo está você não
tira essa dúvida também tá vendo a sua
cara em cima do meu powerpoint não
eu tô vendo a direita né
essa é a direita oposicionista que isso
tem que uma opção na via óptica aí você
escolhe sai de sair ele vai sair do
molde acho que você se você desmarcar eu
acho que ele eles são eu já agora acho
que já tá tudo certinho concordo de
beleza boca então já falar um pouquinho
aqui você não tem roupa qualquer momento
eu não tô mais te vendo tá te ama tá bom
sobre os modelos é conhecido por glmm
virar laje alinhar multilevel model
também conhecidos por modelos apenas são
somente com deus multinível modelos de
hierárquicos ou rpm random questions
modem o modelo de consistência criatório
nomes que aparecem na literatura
modelagem multinível é glmm modelagem
hierárquica e modelos hierárquicos ou
modelagem ensaiado cobre o outro mônica
aparece mais frequente ela é é o onix
models
ah tá entendeu porque já já tudo bem
ah beleza então vamos falar um pouquinho
hoje eu já falar sobre a fundamentação
teórica os modelos multinível e os
conceitos e algumas aplicações quem
quiser então eu fico alguns segundos não
tinha nessa tela para você poder mirar o
seu celular sua câmera não sei o que ela
ficou de ir a outro tá mas fone para
poder baixar essa apresentação
a beleza pessoal já quem é que ainda não
tinha baixado pode pode por favor
apontar eu telefone ou também clicar no
link que está aqui no chat tá o mestre
antônio botou aqui
e aí
olá tudo bem só
o ok pessoal já gravações da
me dá um ok aí quem não tinha já baixou
baixei hoje cedo antes da lá e viu ok ok
ok ok ok ok ok ok
e vamos seguir o jogo então beleza
beleza bom só como está uma historinha
ele não só contar uma história rapidinho
sobre a filosofia de modelagem muito
rapidamente na verdade como está os
modelagem para geralmente parâmetros
para fins produtivos a gente vai
costurar são alguns conceitos alguns
critérios e quando eu gosto de preparar
essas guide essas aulas eu sempre me
recordo um conto do jorge luis borges o
jorge luis borges um poeta escritor
argentino está enterrado lá em genebra
na suíça ele escreveu um conto chamado
dele rigor dela ciência o rigor da
ciência vale a pena ler o conto muito
muito curtinho choro e ele fala o
seguinte de a capa né da bíblia onde
está com
e como que entre outros é exatamente
essa foto está no meio da tela e são
sábios mensurando o império por quê
porque tinha o imperador nessa
localidade imperador pele chama os
sábios e fala assim eu quero que vocês
emerson queria e mapa do império
avaliado como é que está questão
recursos agricultura segurança saúde etc
então se vocês frio mapa do império os
sábios foram para o campo e conversar
com o teodolito médio para cá né de
falar pena e vai e volta aqui lá e
constou a criança é demais né mas
constrói aí o o mapa o mapa instalar um
pramil
e aí eles voltam para o empregador volta
um mapa uma folha enorme não pensei que
tomar um caldo grosso assim para aí mas
cadê aquela árvore que tá aqui do lado
do castelo cadê a cobra ponte do castelo
a gente agora vamos aquela go to shower
ramos a gente volta para o campo voltar
campo e começar a detalhar mas só que
eles perceberam que me dá uma estação
para mim agora eu chamo bracinho aí
pegaram nosso lençol king size
gigantesco que instalar um para sem
colocaram a árvore colocar lá ponte
colocar outras coisas voltaram o
imperador imperador falou assim poxa
vida mas cadê o formigueiro fácil saber
aquele aquele cupinzeiro tem lá cadê ah
ah aquele aquele arbusto já
a feira hoje vai falar pedra que eu
sento do lado do rio que eu vou meditar
vou resumindo ele vai para casa do outro
flamengo mexer brincadeira com a gente
né voltar para o campo e falar bom não
tem jeito a gente só consegue colocar
tudo e operador tá pedindo se tiver um
mapa quanto te amo 1 para 1 aí eu
pergunto qual que é utilidade do mapa
inteiro um para um esticão um super mega
lençol gigantesco em cima do império e
desenha um carro e devolve na mão do
imperador nenhuma utilidade ou seja todo
e qualquer modelo todo e qualquer mapa
em qualquer equação refere-se a
aproximações frente a premissa de uma
determinada realidade isso é o rigor da
ciência tudo bem beleza porque eu tô
falando porque eu tô falando isso
em conta do que está aqui na tela e
conta-lhe que tá aqui na tela saiu um
artigo muito interessante na mexer é a
revista mexer um pouco menos de cinco
anos atrás quatro anos e pouco atrás
final de 2015 neste dois autores silva e
humano que eles levantaram dados sobre a
quantidade de cartões vermelhos e
amarelos dos jogadores da champions na
europa e levam durante o campeonato
então jogador cristiano ronaldo jogava
no real madrid o messi no barcelona o
neymar não sei quem entra e quantidade
de cartões vermelhos amarelos em função
de características do time
eu gostei não tem características dos
jogadores de disciplina pedra um
características também eu do valor do
passe etc tudo isso e também
características do juiz
olá tudo bem que já é considerado mais
rigoroso não e eles passaram a estudar
sete horas para umas 15 ou 16 equipes de
ciências atividade 16 universidades
americanas então clube havia etc outras
velocidades e perguntaram jesus olha só
essa pergunta só essa pergunta escuta
agora não existe relação entre
características do jogador do time e do
juiz é características e quantidade de
cartões vermelhos e amarelos que se
jogador leva ao longo do campeonato
acredite
a 16 equipes 16 modelos diferentes
e o acurácia preditiva as diferentes 11
inclusive fizeram modelos não primitivos
apenas tão somente diagnóstico técnicas
e os por baixo e clusterização ipca
outros fizeram modelos de regressão
linear múltipla outra se deram modelos
de correlação canónica etc outros e
começaram a implementar o símbolo móveis
sbeghen embuste mas não force pedra mas
todos eles chegaram a respostas
parecidas olha meu ninguém nega que o
jogador x ele é mais violento mesmo e o
site viram lá que joga na juventus da
itália e toma cartão jogo jogo não
existe mas a capacidade preditiva dos
modelos é que foi realmente alterada
eles concluem dessa forma com esse
parágrafo taí na tela diferentes
pesquisadores a partir de uma mesma base
de dados podem estimado diferentes
modelos e consequentemente obtendo
diferentes valores previstos ficar
velhos
se você nome no estudo objetivo então
este mal modelos que embora as
simplificações da realidade ou seja
tiago mapa não estarão para um modelos
embora simplificações da realidade
apresenta melhor aderência possível
entre os valores reais em valores
preferido tá então a capa da mente a
capa da 10ª edição da leite essa aqui ó
pode ir lá depois pode baixar na
internet ele tem essa estampa aqui de
mármore e o cd apresenta os dados deia
levá-las pesquisadores olha isso aqui tá
pintando como salvador dalí esse outro
de um foco na mão esse aqui parece
desenho do meu filho de 5 anos essa aqui
no seu dia a gente levar um pau nela
hoje é os modelos né os modelos
é logicamente que ele está dizendo isso
aqui ó graficamente o que está dizendo
era da missa aqui você tem no eixo y
valores previsto ou seja quintas velhos
do nada desligado modelo seja um vídeo
chapéu alex é isso um chapéu e no eixo x
nas abcissas o y o valor real do
fenômeno está estudando então a y chapéu
contra a y o melhor modelo do mundo é
aquele em que todos os pontos vão estar
em cima do que dessa reta tracejada que
é uma reta 45 graus
e você conseguiu capital sem ordem sem
por cento ou só vídeo é melhor dos
mundos e conseguiu marcar um para um é
essa roupa para chegarmos princesa de
uma dele qualquer cientistas de dados
qualquer genes mach lane em são paulo
que é estatístico qualquer a gente
tomadores de decisão a partir de
modelagem a partir de processos de
análise de dados analítica pedra já
pensa consciência o pão distante estão
os nossos fita de velhos em relação aos
valores reais ou seja a modelar os erros
em gema achar que você vai ser quando a
mosca por isso que assim que não aparece
na área de finanças por exemplo a criei
um novo modelo de precificação de
derivativos eu sei quanto vai estar o
preço da soja na bolsa de chicago daqui
a seis meses em janeiro ninguém sabia
cortar o preço do barril brent em
londres de petróleo o mesmo hoje
e por quê porque se os fenômenos
exógenos que apresentam muitas
estocasticidade isso faz com que
efetivamente os pontos assim muito nesse
mapa não com deus ai meu tá claro tudo
bem aí você cima do terminal do modelo
atual tecido azul é bom fecha a boca né
meu amor ou seja é isso muito muito
grande né isso é uma distância muito
grande valor previsto ou gerais aí vem
aqui o outro modelo cor-de-rosa melhorou
né tá melhorando aí vem você thiago e o
professor marcos santos e time esse
laranja melhorou aí só com multinível
mesmo então vamos ver se tá certo ou
seja esse modelo laranja tem rego tem
erro para mim lá na mosca mas a gente
começou a criar premissas e critérios e
fundamento
a imagem efetivamente você consiga
tentar aproximar o máximo os valores
previstos para os reais o critério só
conselho só com fundamentos em mágica
não é black box vamos abrir a
caixa-preta maior black box eu vou fazer
uma rede neural com múltiplas camadas né
por vários meios roda aprende o código
você quiser fechar o abrir o código só
uma deus que também escreveu sobre isso
aqui dormir de fora essa semana de aula
algoritmo de pelo contrário mas aí o de
são essência de base está entendeu que
para por trás do código fundamento
porque depois o resto é código não
precisa facilmente mas o resto código
vamos lá
eu não sei o que apareceu só reta as
ruas hoje é
quem visita né então aí ficou verde meu
deu ruim aí calma aí ó
quem é
é ruim não não me no problema não é
conexão não problema imagem tá verde
fazer minha tela vou parar de
compartilhar compartilhe de novo pa
eu falo o que falo beleza tá bom é
porque ficou verde ou segundo beleza
um chá me fala agora por favor
e o para outro lugar agora é só só
maximizar falar o
em jofre
é só um adendo mestre olha quem tá aí
para te prestigiar a gente vai abrir tá
aí para te prestigiar caramba que legal
obrigado muito bom então dentro das
contexto que a gente está falando de uma
hora aproximação de acurácia entre os
valores ficam os valores reais e o
chapéu com y eu queria contextualizar
onde se encontram os modelos multinível
então humildemente o presente anote o
livro e é o colégio
o hyperloop era participar o senhor em
2017 a partir já nas horas vagas chave a
minha esposa então é possível que está
chupando basicamente além além das
técnicas variadas estou em qualquer
exploração em relação o destrinchar de
uma variável média moda e o padrão e
certo intervalo interquartil o cálculo
deixar mostrar ao teste de hipóteses
paramétricos e não paramétricos entra e
política mas esse técnicas operatórias e
são em outras palavras usadas por baixo
mascherano é as técnicas desta natureza
como por exemplo terem tca anápolis mca
escalonamento multidimensional que são
técnicas efetivamente que é você não
consegue criar um modelo preditivo para
outras motivações não presente na moto à
frente de você
a rodar de novo caso alguma oscilação
vence corrida aquela mostra que já era
coisa do homem os por vai sair do modelo
não se pressionado que você não usa as
previsão determinado observação naquela
mostra para fazer petição para outras e
depois você tem a caracterização das
técnicas o modelo supervisionado
primitivos de mach lane por exemplo os
capítulos de glm que são os modelos de
objetivos ou agressivos com
caracterização logística logística
multinomial probit modelo plano de
contagem modelos concretização o assunto
que usa muito é a crédito também não
ensinou não não começou mas a quantidade
de pessoas que vem esse de crédito
algumas posição por exemplo mensal e os
modelos binomial negativo caracterização
do nome é o negativo e aqui também já
aqui os modelos para eventos raros
pessoal do banco central uso
e por exemplo para infecções cloud esses
modelos muito raros que uma base por
exemplo de 4 milhões de pessoas
jurídicas pequenas e médias determinado
mês você tem 15 pj sim decidir algum
comportamento só doente ou seja os
modelos tradicionais não consegue
capturar essa mistura de uma seleção
bernoulli uma distribuição para sombra
no meu negativa então é onde os modelos
logísticos beijão de modelos ela nos
contagem tudo isso dentro do que está
ali nesse quadrado aqui nessa nesse
retângulo glm generalized linear models
e depois a gente fala sobre essa mesma
situação mas agora em perspectiva
multinível ou seja os modelos em painel
multinível como eu falei os modelos
também podem ser chamado de modelos
mistos modelos hierárquicos modelos de
petições aleatórios
oi gente vai criar multilevel model o
mestre perguntou aqui se tem previsão
para lançar uma nova invenção r é não
tiver né é assim vamos lá esse esse
livro que tá na tela um 2019 e a gente
pensou ele totalmente em inglês no mundo
todo e chamado ele é site para-brisa
nesse realmente neste livro com
capítulos de p e não que não tem aqui
nesse livro então a gente passou quando
eu servia é demanda global o ano passado
e agora eu estou nesse mês assim
vestimos tá borra nem abriu acho que
ando com ela tem sido global para lançar
o livro
o marshmallow mr era um veículo também
inglês isso vai ser para ler ao julho
agosto de 2011 mas vai baixar inglês
sensacional
e eu amo todos então o antônio perguntou
antônio mais um ano mais 15 meses
aproximadamente deus quiser tá saindo do
forno torta tá bom então o foco dessa
apresentação é o pai laranja aqui glmm
tudo bem beleza beleza o que são afinal
modelos multinível esses dois monstros
que estão na terra o steve robin busto
sobre ônibus digitar água brinquedo
estampa ele tem um livro muito legal
muito bom chamado dirá que tal limiar
modo 2002 um plástico e não tem mais 60
mil citações no google escola eles
afirmam os seguintes modelos multinível
são modelos que reconhecem a existência
de estrutura multinível ou hierárquica
nos dados que o que nós vamos porque
aqui o que de fato significa existência
multinível no data set
nós vamos fazer uma brincadeira lúdica
tá vendo o mapa mundi aí tiagão sim sim
tá bom então imagina que ele tem a
seguinte situação eu tenho aqui 3691
empresa eu vou aí coletar dados dessas
11 empresas tomar cola apple e american
airlines que tem a maior parte do seu
capital estrutura de capital
norte-americano vai miniatura embraer e
bora no seu 100 porcento brasileiro
também como a capital nacional billabong
tantas australianas toyota mitsubishi
empresas moro de capital japonês muito
bem eu não vou tá certo eu tenho
característica de uma empresa por
exemplo quantidade de funcionários por
exemplo retorno sobre patrimônio líquido
da empresa naquele período da empresa
diferente a época da américa eu tenho
por exemplo
a cidade é o valor dos ativos da empresa
de empresa nível de satisfação dos
funcionários colaboradores pedra seu
características biológicas cabelo sobre
as empresas que estão no mesmo contexto
por exemplo brasileiro então a taxa de
juros da economia um sido igualmente
sobre a embraer a vaga na cura o índice
de desemprego no brasil incide direta ou
indiretamente nas operações todas as
empresas atuantes aqui em brasília você
achar duas rodas que falam sobre
variáveis de contexto né que diferem das
variáveis em lojas americanas de
contexto a taxa de juro a diferença
entre cama e assim sucessivamente eu
tenho variáveis nível empresa e
variáveis penível olhos nesse exemplo ou
seja olha pro tela
e aí
e eu espero características nível mundo
é tipo jogo dois países de origem ok
muito bem graficamente exatamente isso
que a gente tem aqui na tela agora foi
agora que não tenha mais aquelas 11
empresas foi até sem preço quando cada
pontinho preto aqui na tela na empresa
eu coletei dados do desempenho por
exemplo retorno sobre o patrimônio
líquido holly da firma e o amarelo de
firma por exemplo quantidade de
funcionários observe chama outro você
pode ser pode ser alguém do gás com ele
sim tá bom muito bem sim geralmente mas
é o que noventa e nove porcento das
vezes que faço por isso que análise
gráfica importante o pessoal tinha este
modelo aqui ó ó
o meio de uma hora iso-1 nos para das
ordinários meio um modelo repressivo que
às vezes não é uma ali essa é uma
regressão quantílica lidiana presente no
encontro eu tenho esse modelo aqui
estimado e este meu essa minha reta é
representa os valores de y chapéus fica
de velhos nuvens jogos sair e comer a
boca e comer a boca porque ficou minha
boca porque tem três classes aí porque
as distâncias entre os valores reais
valores previstos dados pela
verticalidade
e aqui ó isso aqui é chamado o que era
uma de erro se for um ls isso a soma
desse começo para baixo para baixo da
cima para cima para baixo para cinza a
soma da quanto zero ea soma dos
quadrados de dois quadrados de cada um
desses erros é o mínimo possível para
não apresenta o creme que o muito bem eu
estilo esse modelo e eu tenho erros
muito grande comparativamente ao meu
filho do velho como consequência vou ter
um valor de reparado baixo e central
consequência mais do ponto de vista
preventivo eu tenho uma perda
substancial porque a pessoa é uma lupa
esses dados eu vou nem que eu tenho que
observações empresas de quatro países
diferentes atletas eu falei três é esse
quarto eu não vi não é
é mas muitas vezes é difícil você você
enxergar sem que a postagem favor esse
tipo de análise né então a gente tem
dados aqui do brasil da austrália japão
e dos estados unidos e se eu permitir
junta estimação a cor dessa forma
e eu vou verificar para ter quatro
modelos distintos bem simples e sempre
transformada do outro mundo daqui a
pouco vão colocar em sua perspectiva
econométrica de modelagem mas não tem
dificuldade nenhuma entender essa
caracterização ou seja olha como os
girinos em cada um dos custos foram
diminuídas eu já tinha erros monstruosos
agora eu tenho eles cada vez menores
nesse objetivo e e mais que isso perceba
aqui por e sexo vamos aqui estou o
brasil não consegue estados unidos vai
estados unidos eu tenho interesse certo
e uma inclinação diferente entre os
estados unidos em relação por exemplo o
japão eu tenho outro inter certo e uma
outra inclinação e é por isso que os
modelos multinível são chamados modelos
de coeficientes aleatórios eu vou testar
aleatoriedade dos interceptos e das
inclinações
a chuva vamos falar um pouquinho já para
não falar que surgiu uma curiosidade
aqui existe existem modelos de
multiníveis contigo e com os tipos
práticos os cantinhos em vez de vezes
ele na e vermelho glitter modelos
multinível de todo e qualquer natureza
por isso que buscaram mesmo na mesma
lógica do gmm então existe modelo
multinível com transformação do boxee
box no limiar modelo multinível
quantilico com o percentil que você
quiser existe isso da uma flexibilidade
absurda né
e olha na verdade você começa a enxergar
que já ele ele é um caso particular do
multinível
e o ms o caso particular particular
particular dentro do multinível dentro
dele e aí você tem a participar da
glória é tão grande guarda-chuva é o
multinível então existem modelos
multinível logístico cenários logísticos
multinomiais probit multinível usarem
freitas multimídia palavra aquasol
utilizo no meu negativo depende da
dureza y
o exame alterado então vamos a função
com quem agora uma parte não percebe
difícil mas talvez a parte mais é
algébrica de assim da apresentação bola
para tela e que nós vamos fazer aqui ó
a cada um daqueles quatro modelos beleza
beleza então vamos criar uma ação
primitiva y ok de cada uma das
observações da gene cluster cluster um é
um beta 0 eu não ter certo gostei não
mas não vai tá 1 x 1 para cada
observação do clã temos mais um termo de
erro e assim plástico que é um termo de
erro r no nível irmã
o mesmo vale para os dois meses vale
para as três meses valeu aí país quatro
imagina que não tenha e firmas em quatro
países se eu tiver inspiro assim dj
países em j contextos modelo multinível
mais geral ainda o caracterização
lineart elas têm nós vamos ter
perguntado e ainda com apenas e tão
somente uma única variável x e daqui a
pouco eu posso x1 x2 x3 car pelo tá na
tela beleza beleza beleza agora agora
separa os homens dos meninos as mulheres
das meninas aí
o gráfico jornal da países apresentam
beta 0 inter certo brasil diferente
japão é diferente da austrália estados
unidos será que os beta zeros os
interceptos são diferentes entre firmas
provenientes de países distintos
em função de características dos países
só que o beta 0 que o inter cep do
brasil tá lá embaixo que o desemprego é
assim e o beta 0 japão tá lá em cima
porque o desemprego a sabão ou
vice-versa ou seja eu posso tirar uma
equação para sempre imperfecto desse
mais provenientes de países distintos e
perceba aqui aqui eu coloco uma variável
próprio porque dobre não x thiago
é porque só tem isso não sei eu tenho
subscrito j ou seja uma variável de país
que incide homogeneamente sobre todas as
firmas provenientes daquele país a no
varia entre firmas varia entre países
porque 10 e sempre olhos o mesmo que
seja isso não tava aqui e além disso tem
o pênis aleatórios de intersexo será que
essas diferenças os interesses entre
irmãos provenientes de países distintos
ocorrem de maneira aleatória ou seja eu
tenho um termo de erro de nível 2 de
interessado o mesmo vale para a gente
nações lembra tchau tchau inclinação
pela mais acentuada em constante angular
5 gente angular menos assim pagos será
que existem diferenças nas inclinações
que modelam o comportamento de firmas
os irmãos provenientes de países juntos
eu coloquei a mesma variável dado aqui
só pra gente morrer não ficar muito
tenso para podia chamar outra aqui para
o dia sensação é que podia ser taxa de
crescimento do pib para o nível país
inconsequentemente efeitos aleatórios no
nível país sobre distintas entre nações
legal que é o nome desse rj é o gente
assim plástico é o erro no nível firma
como é que é o nome desse 10 j efeito
aleatório de interseto mais como é que é
como é que é o nome do j efeito
aleatório da inclinação no nível anos
substituindo agora é só o bico portanto
não é mais beta 0 é um grande 100 mas
deu na 01 que é o que a taxa de
crescimento
e-book interchange usando prefiro mais
provenientes de países distintos todos
somente em uma unidade esta variável no
nível país o crush aumenta a imunidade
essa variável de país é o término uma
unidade a taxa de crescimento da
variável no nível firma entre firmas
provenientes de países destino se eu
substitui aqui embaixo roberta zera o
que é esse trambolho trambolho aqui
nessa rua aqui é isso é um bolinho aqui
de noite tambor um resistir mas rj
portanto essa equação tá aqui embaixo só
tem uma variável x de firma e uma para
ajudado de país já outra equação aqui
embaixo que meu é aquela alegria são que
a gente está acostumado só com ele chama
ao sol mais grande tá cheia é verdade
isso
é só que esse alpha ele apresenta inter
certo com efeitos aleatórios esse
alfabeto da xuxa fralda esse alto
apresenta intercepta os aleatórios por
quê porque sobre ele incide variáveis de
contexto e faço não precisar faz esse
beta 0 uma coisa sejam diferentes entre
si mais provenientes de países distintos
o mesmo vale para o beto porque a gente
chegou no simples só tem uma componente
de ano né nesse aí você tem uma para
cada nível né aí sim uma regressão
simples por ls tem sol ele disse gótico
agora você tem o erro de assim tráfico
nível fila e parâmetro de persistentes
aleatórios de inter certos ea de
inclinações porque você tem que ficar
mais provenientes de países distintos ou
observações provenientes de grupos
distintos contextos distintos
oi beleza beleza beleza ou seja para
colocar na mesma cesta comportamento
diferente sejam comportamentos sociais
comportamentos demográficos
comportamentos infográficos é
comportamento de facilitar o que você
quiser
e isto foi financeiras hoje bancos é
investem milhões em bases de dados de
personas
e leva em consideração a eventualmente
até caracterizações de trigo
e eu posso ter mais parecido com o tiago
que tá vou treinar raro na igreja com
por exemplo eu também tem não tem mais o
dono exemplo uma outra vale deixa então
o final de semana a gente sai para
halley pega a estrada e vai tá campos do
jordão eu sou muito mais parecido com o
tiago nesse aspecto os seus
comportamentos implícitos e o modelo
tradicional vai consertar então eu tô
falando disso porque a gente tá aqui
apresentando uma fase de álgebra e
conecta mas nós implementamos estimamos
modelos ninja hoje em diversas empresas
porque você melhor naturalmente desde
que você consiga os assim enxergar o
contexto que muitas vezes aconteça não
observável né separar o certo é
observado melhor homem separar porque
ele futebol me faça perguntas para o
flamengo ou o vasco torce para o
fluminense torce para o são paulo tudo
bem agora comportar
e não observáveis dos determinados
observações próximo cair em clusters
distintos daqueles que inicialmente você
imaginaria isso faz com que aumente
profundamente a capacidade de curitiba o
teu modelo permitindo que sejam
deferidos os termos aleatórios
intercepta de inclinação nós vamos
entrar nesse caso se você considera uma
linear simples por exemplo você já tá
entrando erro né já tá jogando todos
esses efeitos no erro né você não ia ter
como como separar né mas simples
exatamente exatamente isso dinheiro que
se faz tiago eu que se faz 90 consegue
às vezes meu então vamos só brincar aqui
mais um pouquinho de áudio vou fazer a
propriedade distributiva aqui tá eu vou
multiplicar não vou fazer em casa eu vou
mudar de lado as coisas aqui então
namoradinha o que era eu que eu vou
chamar de frente o fluxo é o que não tem
componente de erro o que tem efeito
aleatório lembra o zé ela tá aqui
e o zero aqui para usar aqui 101 e a
gente faz um belo tem j desistir mais
cinza aqui
já tá feito esse é o componente efeitos
aleatórios antônio tá para nascer o cara
thiago e vai fazer uma consideração de a
propriedade multiplicativo a variável
explicativa é de variáveis de inglês
diferente eu vou multiplicar a
quantidade de funcionário da firma pelo
pib do país e aqui aparece uma interação
entre variáveis de nível 1 e nível 2
mesmo mas eu consigo vamos te perguntar
se o código que multiplica todas as por
todas beleza bem tudo componente efeitos
fixos
é porque além disso você tem mais
interação entre componente efeitos
aleatórios a gente variável de carne
sentaria tório né ou seja o erro é
naturalmente heterocedastico ele não tem
que levar em um que você permite aí
quando você da cidade nesse caso você
permite que os erros entre contextos
essas organizados e a gente aprende que
uma das os preços valor premissa tá
falando tá errado premissa os modelos de
regressão é a eliminação direta ser a
cidade é traz felicidade você não
elimina você tenta reduzir incluindo
variáveis anteriormente é o horário de
relevantes que anteriormente não foram
consideradas no modelo original quando
você coloca variáveis relevantes no
regional você tenta capturar melhores
esse concorrente heterocedastico e aqui
você permite
o que é tenso na cidade é por conta da
existência de diferentes contextos no
que diz respeito aos efeitos aleatórios
não tava aqui de inclinação olha que vai
ficar nossa árvore goldstein outro
monstro da escola britânica da
universidade de bristol ele é o
coordenador de um negocinho aqui lá em
cristo chamado centro modelagem
multinível olha os cães tão doce tem
várias aulas do rádio gostar da equipe
dele é free na internet vale a pena
assistir inclusive milhão eu tive a
oportunidade de fazer um curso com ele
eu quero muito legal e assim ele começa
a falando isso ele ensina um pouquinho
de ali ele e fala mesmo para que o caso
particular lá vamos ver o caso mais
geral e precisos para acontecer isso não
acontecer já consegue a isso fica com gm
é sério quando ele fala então muito
legal 2011 tá multilevel statistical
models os modelos tradicionais regressão
demoram as interações entre variáveis no
componente de efeitos fixos e também
demoram os tradicionais as integrações
entre em termos de erro e variáveis no
componente de efeitos aleatórios
oi tudo bem beleza
e aí zero a tabachnik e linda chinelo
também as suas fantásticas da califórnia
efeito inverso e as duas acabam se
aposentar diferentemente professor é
muito grande para esse livro a cerca de
seis ou sete anos e use multivariate
statistics ela fala o seguinte se as
variâncias dos temas aleatórios o zero
no mundo volta mariane seu desse cara tá
vendo thiago sim e deixe cara se as
variâncias foi estatisticamente
diferente de zero procedimentos
tradicionais de estimação dos parâmetros
como por exemplo mt o não cheiram
adequado portanto a primeira
recomendação que a gente faz você tem o
datacert
se você não investir da é de maneira
explícita o plástico no grupo contexto
ainda assim vamos falar para vocês como
é que dá para você artificialmente e
esses contextos para rodar um trilho
segunda tá certo a gente faz isso tudo
que ele tá fazendo isso tudo quanto é
projeto
há 70 cassete roda primeiro a modelagem
multinível e avalia significância das
variantes estatísticas das variâncias
dos temos relatórios intercepta de
iluminação e elas não se mostraram
estatisticamente diferente de zero aí
vamos com gln aí vamos com o modelo
tradicional para encontrar o modelo
multinível vai dar fácil fácil diálogo
um palmo de lyme
e aí fechando essa primeira parte a
sophie hard reset e o escondam a
respeito de banco e o escondam de boquim
e do instituto de saúde pública da
noruega aliás diga-se de passagem ao seu
final direct é um monstro da publicação
modelagem multinível ela é assim as
pessoas que mais contribuem com
modelagem um tiro no mundo essa mulher é
simplesmente sensacional e a nova
ajudante brilhante adoro a sofia me
resta fala que eu te chamo que está
pensando assim a virar farra você tá
falando coisa aí de contexto não sei o
que lá que países não é pode colocar não
tem problema nenhum
a perna vai recepção de damas de grupo
não capturarem os efeitos contextuais
justo que não experimente aqui é porque
se separassem os efeitos observáveis não
observáveis sobre a parada do império ou
em outras palavras se amam adami em
interessaria pés tão somente um
componente efeito simples perdão o
componente efeito fixos mas ainda assim
você não posso peca curar a gente lidar
com a divindade dessa
heterocedasticidade no campo além de
efeitos aleatórios
se você consegue até mudar as
inclinações né projetos mas a
variabilidade associada ali você não vai
conseguir pegar das interações entre
diferentes níveis por exemplo né
perfeito no componente acertada
católicos
é o mesmo foi aqui ele consegue capturar
verdade mas aqui você colocar só da
gente não vai ter 10 não vai ter um não
vai ter vai ter só um ele não sem graça
o meu firma
oi beleza beleza e aí agora sim para
fechar essa parte mas antes dia
algébrica e como métrica venho do que é
o cujo esse cara também para quem quiser
começar a estudar modelo argentine vale
a pena ler o daniel cujo elenco gelo é
também o outro cara genial júnior ele é
estatístico filósofo e demógrafo
presidente do ibge da frança de gama da
silva instituto nacional de estudos
demográficos da frança não é e ele
lançou um livro chamado metodologia e
epistemologia da análise multinível e
consegue acreditar thiago primo dele não
tem quase que uma fórmula é só maizena
não imagina filósofo pa pa
é mas eu também estatístico meu e
deixe-o
é só filosofia do pensamento multinível
porque se você começar a reclamar eu
admiro muito a essas pessoas assim são
que nem é você adriana silva também
consegue passar o negócio é muito fácil
né professor marcos antes também então
vocês conseguem passar sem forma né
então facilita muito
o tiago mostrei algumas sim é começar a
refletir isso você começar a enxergar
que o mundo naturalmente é multinível o
comportamento das pessoas é um nível
comportamento dos preços das ações segue
caracterização contextual e começa a
enxergar os fenômenos e construir
modelos que uma perspectiva multimídia
olha o daniel cujo fala dentro de uma
estrutura de modelo com equação única
por exemplo glm por exemplo ls parece
não haver conexão entre indivíduos da
sociedade em que viveu nesse sentido o
uso de equações em níveis modelagem
multinível permite que o pesquisador
pule de uma ciência para outra alunos
escola famílias e bairros irmãs e países
a ignorar essa relação significa
elaborar análises incorretas sobre o
comportamento dos indivíduos igualmente
sobre o comportamento dos grupos somente
o reconhecimento dessas recíproco as
influências permite a análise correta
dos fenômenos
eu gosto muito daniel conjuntamente e
agora já jogo da onu para reta final
digamos aplicações e modelagem
multinível é
e bora
olá pessoal tem alguma blusa aí só para
só para perguntar se pessoal tem alguma
dúvida alguém quer perguntar alguma
coisa então momento não nos segue aqui
a beleza é o vitor falou que eu quero
fala aí mandei pode falar pelo chat ou
fala pela áudio aqui tranquilo
me manda aí mandei
e aí
é rapidinho rapidinho existe trutura
multinível horizontal
oi eva boa uma boa colocação na verdade
é uma boa pergunta é a verdade assim nós
vamos falar um pouquinho disso daqui a
pouco a gente falar sobre sobre as
vantagens da novela a gente nível mas só
adiantando neste contexto que está
apresentando aqui a modelagem multinível
ela requer um dado acerte-o com um
perfeito neste caso é o melhor plano
perfeito alinhamento de mim meu não não
é com ele não é a linha mente a minha
mente nesta olha o outro nome que
aparece na temperatura nesta de móveis
modelos aninhado significa isso o joão a
escola lá e a maria na escola b joão não
tá lá
se você já tem o joão o joão pedro e o
cléber tomar a marisa o antônio e a
cleusa automabi então você tem
características de um indivíduo e
características de escola que eles
tinham agendamento sobre todos devido
atlético não sobre a cleusa fica na
outra escola agora existe também tudo
que está falando tiago não só a
perspectiva hlm tá ligado que alinhar
móvel existe uma perspectiva ea questão
da universalidade hcm temerário que tão
próximo assim falhas model hcm tiago
quando chegasse e me o gente chegasse
para
e quanto a estrutura do processo quem
perguntou foi o antônio já foi o heitor
heitor heitor agora em todo o que o que
o que o que faz copiada por negativa do
usufruto de cada uma dessas técnicas é
justamente a caracterização da para sete
ou seja você viu que eu tomei o cuidado
de não colocar afirma acontecido lá com
país né beleza agora precisa colocar no
fio a com setor também beleza nem eu
realmente perfeito por exemplo vale
setor mineração bhp billiton setor de
mineração não cito aviação tampas citou
aviação latam tá no mesmo setor que a
planta a bhp billiton tava mesmo setor
que ela vale agora se tem o que já
colocar junto aí nosso o nosso cinema se
eu quiser
o fruto você por é país vamos lá a tampa
onde brasil é o que é admiração a canta
está hoje na austrália mas é minha mas é
mas é aviação também a vale no brasil
junto com a tam mas a mineração ea bhp
então tá junto para as plantas já
austrália hora mas estar junto com a
janice já me enrolei toda trás muito
trabalho que a menina acha você entendeu
é classificação cruzada irá que eu
trouxe fosse farelo horizontal na
vertical ou cê continente existem besta
quem sabe quem que é a desenvolvedora
não código do r1 do bairro etc tem o do
estátua quem a desenvolvedora algébrica
matricial para estimação ou seja e o
pelas verem o professor marcos porque na
verdade é uma função de verossimilhança
que eu vou tentar maximizar e estimar
parâmetros que estão as varáveis decisão
para maximizar sua função dela
semelhança você já é pior aveia altura
do do desenvolvimento algébrico
econométrico para estimação de
parâmetros de modelo hcm que é um peito
é que brincavam na econométrica é uma
professora chamada sophia robb rapper
aquela monstro acabei de mostrar
pensando espanhol só assista e sete no
status é um tipo de modelagem multinível
só sim ou não agora você perguntou lá
é é é o x7 é simplesmente para você no
status para você definir é o o a
caracterização temporal ea
caracterização dividual xt entrada de
conexões t7 firma a mês então x o tênis
de sete é um código para você desde os
meus parentes no painel porque o
multinível também pode ser temporal
posso ter o joão ao longo do tempo a
maria ao longo do tempo pedro ao longo
do tempo seja no mês 1 eu perdi o marin
pedro no mês dois joão maria e pedro no
mês 3 de uma limpeza mesmo que eu posso
até me xingar viu então nesse caso ela
evolução temporal do super-set nível 1
ao tempo o nível 2 é a continuação
pessoa o afirma etc eu posso largar ele
tem caminho de santiago
oi gláucia gláucia depósito hen3 o
painel é com medidas repetidas e três
livros tempo firme e país por exemplo
posso ter sempre marinho
ah beleza então vamos seguir beleza aqui
que o jerry ntn-d do erre também captura
bem exatamente o que o x7 paiva paletes
ter saído sozinho não faz nada você só
definir viu gláucia depois você precisa
rodar um xp tag oxe segue ou os códigos
específicos para modelagem multinível é
como o sistema mixer do xtn ela gente
xtn r&amp;m berg que é o multilevel effect
explicativo nordeste fazendo estrada
você tem todos os códigos para fazer a
cada uma das modelagem multinível seja é
a fundamentação teórica ela vem junto
com o binômio caracterização da natureza
variável y porque se ela for um arame
por exemplo os outros modelos logísticos
etc e além disso há o reconhecimento do
contexto bastante
e aí beleza tudo bem beleza vamos seguir
então é
e aí beleza
tá bom aí eu fiz uma pequena a
brincadeira aqui né eu peguei aplicações
no estoque journals esse aqui na hora
que as crianças vão dormir não tem que
fazer na minha mente assim você fica
criando o robozinho o algoritmo para
poder preencher essas tabelas e aí ó
eu estou no rank google escola ela acaba
nariz só que isso mesmo a carolina
ferraz júnior tirou remédios as pedras
nos últimos cinco anos cinco anos qual
percentual de g l m n ou seja de
modelagem multinível em relação ao total
de modelo supervision of 10 por cento ou
seja esteja só se você for para a área
filtrar as finanças o outros teológicos
a parte - 5
e se for para contabilidade questões
tributárias aquela não tem tá que sejam
bem forte tá número opa já está usando
maior porque ele tá usando porque é
eu acho
o ponto de vista estimação os códigos
que eu tô na literatura tem mais mas são
todos recentes viu num eu como eu fui
fazer uma palestra na embraer agora
tenta de 40 a 50 dias atrás eles pediram
para eu fazer o mesmo mesma tabela para
a área de engenharia aeronáutica
aeroespacial
e esse aqui não mostrei lá no lado isso
pessoalmente amor então tá eu peguei o
estoque sem juros na área de engenharia
aeronáutica aeroespacial um cento nos
últimos cinco anos eram os modelos que
leva em consideração a caracterização
preditiva modelos pressionados rn entra
fazem alguma algumas utilização para
inclusão de efeitos aleatórios de
interruptor de inclinação nos níveis
superiores porque isso porque tá um
pouco aí vem esses dois aqui ó o lado
chegar e é o diretor do instituto de
estudos políticos de paris hilton's my
dears o outro segura de oxford
é porque muito porco instalar isso livro
deles e já tem aí quase quatro anos mas
ainda recente é muito leva network
analysis com deixou dos seus sonhos
teoria métodos e aplicações porque
primeiro eles falam e aí é humildemente
não concordo muito eles falam estrutura
dos dados
e muitas vezes segundo eles o data set
não tem um contexto você tem dados de
filho ou não tem dado de ir para ir se
tem dado de cima não tem nada não tem
dado setor ponto beleza e
olá tudo bem mas quem disse que os
contextos precisam ser observaveis por
exemplo você pode pegar aquele data set
que você tem com variáveis x1 x2 x3 pode
falhar com a esterilização né
masterização você pode fazer uma
customização e criar um contexto dois
que é um cluster' para os seus amigos
demais e permitir que existam efeitos
aleatórios intercepte e inclinação entre
o contexto que você acabou de criar
tiago acredite você passou a ser
imbatível por isso que eu falei no
começo da apresentação ea super vai vir
tomar chimarrão técnica de avanço por
baixo mochila dakine ela se beijam na
modelagem multinível e acredito acredite
em algumas empresas do setor financeiro
na área da saúde mineração e uma uma
empresa de seguradora
oi amor estamos fazendo sua forma ou
incremento considerável do ponto de
vista de linguagem de cabelo inicial
entre os filhos os valores reais então
contexto de vida hidrata né você você
imagina que realmente ajuda demais né
muito muito então a sua reduzida
dimensão né ou a mesma pessoa né o mesmo
oficial se consegue depois que está se
fica um indicador da policiais
especialmente borba com aqueles dois
mesmo que você não tem a maravilha de
plantas mas não vão ter varejo w de ter
só um relaxa você não precisa ter
variado w eu sempre mentir só o efeito
aleatório intercepta de inclinação mesmo
se não tem nada a ver não você vai ver o
incremento o que eles fala e aí eu
concordo que não tem caracterização da
natureza multinível nos dados aí sim aí
não tem cara não considerou e por mês da
capa
e funcional e suficiente pode parecer
besteira hoje em dia mas não o número da
principais for piso desse geralmente o
livro que eu achei com a patrícia o ano
passado no mundo todo em inglês alguns
modelos tiago eles levavam 12/13 horas
para ser estimados no estatal no rs
setra porque o câncer de muitas
variáveis x e muitas análises w a as
interações são profundas né mas você
deixa lá se bota para rodar a noite vai
dormir reza antes de dormir na sempre
acorda veja mais um pouco vai olhar no
computador deixa computador rodando a
noite inteira quando você ver você
analisa vez peguei home código você
chora falando que não faz parte mas
nossa empresa se a gente está fazendo
assim também por conta da
e aí você vai ter que ter as coisas
profundas eu vou citar dois exemplos
rápidos como é que eu faço tempo aí te
chamar
e assim a gente começou já umas meia
hora né depois né então já tenho 1:21
acho tá tranquilo tá tudo tá tudo bem tá
beleza como é que eu tenho uma hora uma
hora uma hora uma hora 9:20 é minha
beleza então falar na hora ótimo tá
tranquilo tá ótimo é uma hora e 20 isso
aí mesmo beleza tá beleza bom esse esse
paper eu pegar aqui como eu peço perdão
mas eu não posso transitar do conta dndn
suas empresas não posso ajudar os reais
que a gente faz no mercado mas tu trazer
o dados que eu peguei reais de papers
que já foram publicados a gente poder
replicar e a gente ficou então o
primeiro paper wallpaper é publicado na
organizacional instante neto e é uma top
diurno tá naquela lista lá que
e o short katinguelê e a matilda
diretora escritora o esse preto se
coletaram dados da universidade de um
órgão com custa arte global 2800 de duas
empresas
a 348 setores no período de sete anos
tem um tempinho já mas fica aqui ó a
parte de idade quase 16 mil observações
eu perceba a glaucia perguntas foi o
[Música]
motor aqui não tenha a classificação
cruzada elias eu colocar os países junto
com setor mas eu tenho período nível 1
firma nível 2 setor nível 3 então hl3
lhe chamar for sector e paga férias
únicas formas using random coefficients
modeling modelagem consistência
aleatórios um modelagem utilize óculos e
aí eles vem com duas perguntas suas
hipóteses de pesquisa existe variando-se
a significativa no desempenho medido
pelo retorno sobre os ativos
é mais provenientes de um mesmo setor e
dos irmãos que eu ganhei esse chá por
existir a liquidez corrente das firmas
param de firma é estatisticamente
significantes para explicar a variação
desempenho e existem diferenças entre
firmas provenientes de setores
distímicos primeira coisa que ele faz é
o que a gente chama de modelo não
condicional modelo número não tem
variável x nenhuma rua mj ele tem um
perto estou apenas totalmente um beta e
esse beta varia entre setores ou seja
modelo não tem vários x e nem w
o quê que vai ser um avaliar tiago
significância estatística desse cara
aqui ó efeito aleatório de intenção tá
internação que não tenho falado oxe só
tem que ser ainda então jesus diferenças
travesti de cinco setores ou seja
avaliando-se a decio 0j é
estatisticamente diferente de zero eu
mandei um e-mail zinho como eu falei né
da minha noite só sei que a gente não
tem o que fazer né eu mandei o
nenenzinho para a matilha de toalha e
falei matilda por favor eu tô meio sem
ter o que fazer você me manda os dados
já tá mente ela mandou agora deixa rodar
né tiago a gente rodou rogamos que
obtivermos o seguinte a rua
o componente efeitos fixos olha o gama 0
aqui ó grama 00 cor por aí já tá
explicado ea variância nos quais os
componentes existentes adoro o zero e rj
todos os só fez apresentam nessa forma
tá uma partida out six eléctrica
particular não é chefe e se vale a pena
vale o r vale para o python vale
puxá-los vale do spss
é bom e aí a gente faz aqui uma
combinação e chegamos a conclusão 84 por
são as duas as duas trabalho ânsia é meu
primeiro e o que você está no exame a
variância de efeito aleatório de inter
século foi estatisticamente diferente de
zero a noventa e cinco porcento
confiança e eu cheguei à conclusão que o
comportamento dos rolos 84 por cento é
devido à característica de chima mais
meu quinze por cento quase 16 é devido a
diferenças entre os setores
características de setores
eu não entendi isso
e agora vem com isso aqui essas
características de firmas uma bela já
liquidez corrente translation da firma
como aparece uma variável x aqui thiago
aparece o que parece o betão eu posso
colocar o que efeito aleatório de
inclinação você só que existem
diferenças nas inclinações e nos
intersexos sempre firmas provenientes de
setores distintos aqui chegamos a
conclusão que sim aqui o processo
intenso parâmetros já fez sexo e aqui as
variâncias dos componentes aleatórios
erro sintático efeito aleatório de
interseto efeito aleatório depilação
todo mundo estatisticamente diferente de
zero
o motivo fazer isso baixo negócio esse
aqui é o tipo shino software olha aqui
igual se isso aqui ou não teve está
dessa não é um copo muito boa noite
fashion vip setor campeonato porque isso
aqui é o seu território de inclinação do
nível as windows 7 por e aí isso eles
não mostram no peito agora vou puxar a
sardinha né tinha visto que não gostam
olha aqui o que é um teste de razão de
verossimilhança entre as duas logo ai
que hulk fronteiras entre as duas
funções dela se nessa questão das
funções de pesquisa operacional lrps
versus o modelo de regressão linear
o modelo são paulo modelo tradicional
chinês sonhar vocês não fizeram ou seja
fizeram corretamente né não te ligo mas
que eu resolvi fazer para comparar
e aqui está o gráfico os dados contra o
modelo multinível com os dados da
sporting de lisboa a reta a 45 graus a
reta tracejada modelo multilaser rosa
modelo ls não consegue captar os
contextos ou seja fica para fazer esse
degrau aqui ó um é o modelo tradicional
de aqui sensacional
oi e aí nós pegamos o outro paper esse a
gente vai jantar praticamente o aceito
enfim para vencer o clássico você fala
poxa fábio é só trazer um tempo em 1995
não meu é um tempo em plástico tem mais
de 25 mil citações e tem pensou eu para
criticar pelo amor de deus mas como a
gente sabe que não vai cruzar com eles
né marcos nos congressos replications em
que ele passa pela gente ainda não vai
cumprimentar a gente ó o rojão de gales
eles são professores da universidade de
chicago nos estados unidos o rojão foi
agora recentemente inclusive ministro
das finanças da índia ou para chicago
agora eles são professores de cabo e
esperam pessoal estrutura de capital e
publicado só juro de uno fire dados
e aí
com 4.557 empresas dado da compostagem
global e do modem stricta wind 95 anos
37 88 89 90 91 e aí só para esse sete
países
o que são países considerados
desenvolvidos estados unidos japão
alemanha frança itália reino unido
canadá e eles propuseram esse clássico
modelo tem um modelo mais aceito hoje
para isto um grande cartão e monitora
alavancagem financeira da firma em
função da posição dos ativos tangíveis
na relação entre o valor de mercado e o
valor contábil é do cristo as ações da
fala do lixo afirma uma ritmo natural da
receita de vendas e horror entrando como
variável x aqui esse é o modelo deles
meu a gente ficou olhando para este
modelo e falou assim cara poxa vida mas
sem camisa aqui meu amigo
e vamos tentar fazer uma modelagem
multinível os dados estão abertos na
internet nós roubamos os dados deles e
eu tivemos mesmo tipo tudo isso aqui só
que tá aqui na tela ela tem visão
motivar no pé também aqui isso aqui é
uma regressão glm coloquei jotinha aqui
tiago não subscrito só a firma firma
firma firma meu como eu falei isso não
tem muito o que fazer então que o modelo
de cima é o modelo dele a3 em gales o de
baixo é o nosso que quem te fez nada só
colocamos jotinha jotinha jotinha
jotinha e jardim
e permitimos permitimos que houvesse o
que efeitos aleatórios de intercepto da
dá uma nas inclinações tá vendo que são
quatro variável x
é mas agora a verdade o fábio eu
confesso não tava muito afim eu não fui
eu não fui lá eu podia pegar alguém
falar meu levanta para mim quanto que é
o pib dos estados unidos japão da
alemanha gente pediu no a inflação a
carta de judas semana a gente conseguiu
relaxa não vou colocar para ajudar
porque se não é transporte vai comprar
uma banana com você aí é doméstica quero
pegar o mesmo modelo deles só permitindo
efeitos aleatórios contextuais de
intercepto de inclinação esse modelo
aqui debaixo 12 níveis tá vendo tijolo
sim e rogamos e modelos
é tudo era muito parecidos com os piores
são os sinais de cada um dos betas em
relação ao modelo o ms deles mas nós
percebemos que ocorreu o que uma
significância estatística e todos os
efeitos aleatórios de intercepta que
ovar consulta dos 4 minutos nações para
casa umas 4 levar a vestir um dessa
variável um da outra um décimo dessa
esse é 10 esse é o rj descobrimos que
3367 por cento da avaliação da
alavancagem financeira das firmas é de
fato devido a componente firma porém 33
devido à variação entre países e olha o
like erro duration teste e a gente fez
e aqui ó e aí aí garoto
é sensacional quem pediu esse gráfico
foi o parecerista tá ele falou não estou
convencido que vocês não é replicando
razões engasgos nessa altura do
campeonato esse mandar para ele não
ficar chateado né a gente mandar para
eles pode ser que eles não nos
cumprimentem no congresso mas como a
gente não vai encontrar aqui no brasil
tá assistir tá meio chateado me livre
xvii mas faz parte do jogo esse a
maturidade ea tabela rica científica aí
todo mundo é só assim a gente vai
realmente conseguir transformar esse
nosso indice no país né eu muito bem e
aí curte por conta disso olha aqui tiago
esses gráficos são gerados tanto estatal
quanto no r7 lá se houver interesse
exposto fazer uma outra live só
estimando tudo isso aqui no r1 ou estaca
onde vocês quiserem mas a tia sabe que
fica para cada um país
tá certo aquela positivo negativo e as
implicações protege doações para
marketbook para alugar em si natural das
velhas e que o rua são quatro efeitos
aleatórios bem inclinação que simpatia
maravich enfrentar a tua vida sempre
hora que o império entre países para
você faz um endereço janeiro e
tradicional você consegue capturar luz
oi e para finalizar eu reproduzo aqui o
slide com autorização do delmo tive o
prazer de assistir uma você aluno dele
assistir uma conferência com ele eles
têm lá em columbia em nova york marcos
santos e tiago e todos vocês estão vendo
ele tem nenhuma uma conferência anual
não é uma coisa nova york eu estou em
várias localidades chama multilevel com
seu rosto pesquisa você vai ver acontece
aquela do eu falei anual perdão perdão
edinho enable edelman é um cara
fantástico também o andrew gelman é que
tá em colômbia e pública bastante na
área de modelagem multinível e esse foi
o slide que ele mostrou para finalizar a
palestra dele eu com autorização dele tô
replicando aqui é para vocês
os desafios atuais e modelagem
multinível primeiro eu senti na pele se
sente toda hora interações profunda de
capacidade que vocês somente você tem
muitas variáveis x junto somente com
muitas variáveis w método de estimação
dos parâmetros estão surgindo alguns
métodos massagens mais rápidas url já
incorporou por exemplo que é o iml os 30
estimation of maximum likelihood muito
utilizado para estimação de parâmetros
de modelar i&amp;d variantes de referência
da glória de modelagem multinível e
melhora muita capacidade computacional
do sistema de maneira mais rápida
inclusive girl não é o torno de uma uma
proposta de estimação de parâmetros te
mandar mais rápida mais eficiente do
ponto de vista computacional e olha que
o ghelman coloca-la tiago duas
finalização da nós
o mesmo quando seja não observar viveu
porque a estimação de modelos com a
melhor aderência possível em valores
reais e valores previstos não tem
conversa sensacional eu vou finalizar
fazer uma brincadeirinha que é o
seguinte falou de fundamentos nada não
quem te falou aqui foi pasta preta você
consegue estimar esses modelos na mão um
tempo de pensamentos bancos já
quantidade de variáveis e logo nós se
não faz musculação zinha pega um banco
de dados pequenininho 10 linhas duas
variáveis se você cortar uma função de
verossimilhança no hotel você roda
multinível por meio do show ver
significa você construir seu modelo te
amo pero de chão sabendo das coisas bem
leva ele pacote
o espelho sabe hoje as pessoas estão
muito mais é preocupados não todos por
favor mas não precisa implementar o
algoritmo do outro mundo porque porque o
banco tá o tempo lamentando ou também
efeito manada o código que sobrepõe a
técnica os fundamentos pelo amor de deus
se você for mudar a modelagem multinível
qualquer hora essas plataformas que eu
mencionei sem ter os fundamentos não
sabe nem por onde começar com seus
códigos eles vão pedir o seguinte tem
que aceito fixo tentação de efeito fixo
e receita relatório que nível o que
nível 2 e de frente aleatório intershop
que cada um dos níveis tipo efeito
aleatório de inclinação e cada um mundo
que não soubesse assim banana portanto e
afundamento porque depois o código sai
que nem manteiga sempre sacolas pelo
amor de deus mas é que é o processo
natural de formação cientista de dados e
consequentemente que o processo de
tomada de decisão na compra da conta
porque só sem ver esse
a é retroalimentado mas siga essa
ordem você se perde porque amanhã esse
código essa plataforma quando ele vai
deixar de ser utilizada amanhã vamos
fazer isso júlia vamos fazer isso não
sei aonde beleza problema você tem o
chumbamento então gosto desse slide e
esse estava com um artigo que o thiago
eu escrevemos essa semana né tiago tem
ficado lá no twitter fórum 265 e fala
que não vai ter baixo da perna
pernalonga da estiva
bom imagina a cenourinha aqui que vai
ter esse outro tá até meio triste ali né
só tô sem aprofundar e olhar de perto
os horários os aumentos fazem que você
tem a solidez muitas vezes para modelos
mais para simone osos você sabe para
fazer quando o meu outra chance é
fantasioso vence técnica não porque eu
descobri que tem o modelo assim a roda
mais longa com base em fundamento senão
vai ser que taxa vai ser
o show tudo bem pessoal o antônio falou
aqui que meu arquivo sensacional foi uma
honra aí o convite do mais fácil aí para
escrever esse artigo
eu acho realmente que é muito importante
né você ter ideia da dessa concentração
em detrimento a você rodar código né eu
acho que você tem que entender o que
está por trás né porque como uma parte
do professor fazer um inscreveu no
artigo é o seguinte o que a tecnologia
ela muda né ela volo e com o tempo mas o
conceito fica né conceito não muda então
se você tiver o conceito se aplica em
qualquer tecnologia que surgir
tecnologia a gente se adapta você não
pode correr esse risco os pentei
conserto porque senão a contar ela tá
muito ruim a estrada do ponto de vista
de solidez agora você tiver com vocês
fundamentos poxa vida você é imbatível
se você tiver os conselhos estão bem
implementar você é um unicórnio entrego
todos nós estamos precisando o código
o código é fundamental mas que a gente
percebe muito é que as pessoas querem
pular etapa então quero saber o código
mas eu não sei mudar uma pc ao lance
emagrecer são os fundamentos da álgebra
linear os fundar é o gelinho os
fundamentos do tipo na veia o que é uma
água e é professor marcos santos o que é
uma simulação a diferença com o processo
de utilização é programação dinâmica
programação inteira programação de malha
áudio da econometria isso só um né sul
da mentais porque você tem erudição
essência de dados essa algumas
referências que eu menciona ao longo do
da apresentação para você ter que
digitar daí também esse é o nível também
estou a gente lançou ano passado ele
traz surpresas desse já make acadêmico
pra fazer vídeos de cambridge e eu
finalizo com uma frase dita pelo ilustre
melhor é
bom e quando eu vi essa frase eu falei
isso aqui é totalmente lisa mensagem uma
mensagem multinível porque nós devemos
expandir o círculo do nosso amor até que
englobe todo o nosso bairro do bairro
por sua vez deve deslocar-se para toda a
cidade da cidade para o estado e assim
sucessivamente até que o objeto nosso
amor e o acordo nosso planeta tá
precisando né e todo o universo chora
essa frase eu enxergo uma hrm-5 hahaha
sensacional sobre o tiago para quem
perdeu o começo o brigado o que a cold
tá aí no final também explica ver um
postinho brasil incrível incrível muito
obrigado por você sensacional pessoal tá
falando aqui sensacional obrigado então
é tio só vir aqui é o p
a gláucia falou que ela que ela tá
fazendo ela fez no status mas ela não
consegue fazer no r aí então ela curtiu
ele a ideia da live dr e tem outras
pessoas aqui falaram também r
e com certeza e tal pessoal qr tem um
tempo pra pergunta do pai também depois
se puder responder eu parei de
compartilhar e tô olhando agora o chefe
que não estava olhando chateada não que
eu tô vendo aqui ao senhor perder alguma
vocês me fala por favor tô vendo aqui o
antônio carlos falando com o nome da
biblioteca do erre eu posso escrever
aqui e daí só vamos ver gente fica à
vontade lm mcphee desse jeitinho aí ó
olha como é que eu faço tem que mandar
para todos né desculpa eu fiz gln mvo
live install package glm.nb depois vai
berinjeli tmb já li mmnb tudo bem então
é
a imagem que faltava falando eu tô
quintela perguntou sobre o ruan tá
python
eu tenho te conhece alguma olha legal
quinta lá olha só como quando você tem
os fundamentos quando não há um código
agrotec específica você programa que
gera aquele código então é eu e dois
colegas nós criamos o algoritmo a
rodando em python porque não tem o meu
pé que especifica principalmente para lá
modelos é multinível não lineares at
alguém conhecer eu peço desculpas mas
dentro da nossa humilde nosso muito
conhecimento aqui eu nunca encontrei já
pesquisei bastante por exemplo modelagem
é multinível contagem de nominal
negativa com 10 enfeite no item no
estado tem no python não encontrei então
a gente criou porque conhece a forma a
função objetivo gente conhece a função
de logo aquele rude e aí a gente escuta
lá e
e os mesmos parâmetros do coco só a
imagem também então se você responde
aqui em tela mas sim é possível rodar
isso no final tom quando estivermos
utilizando modelos multinível estamos no
sgt overfitting dependendo da quantidade
de categorias de dois níveis um ritual
perguntou a boa pergunta também na
verdade dependendo da quantidade de
tranquilidade dos virgens você tem a
restituição tamanho do dota 7 é só na
verdade não há o problema do orifício em
porque é a gente não faz isso fruto de
amostra de validação de trem um teste
você na verdade está usando toda a
amostra e estima embalagem uma função de
verossimilhança aberta nos vestimos
parâmetros então é a alma alimentação
maior ainda com
e do banco de dados que mais parâmetros
estimados e se não tem só por exemplo se
eu tiver duas variáveis x duas variáves
w e dois grupos e um grupo nível 1 nível
2 dois grupos por exemplo eu vou ter os
dois parâmetros das variáveis x 1 x 2 os
dois paramos aparece um w e w2 as
interações nos efeitos aleatórios e
inclinação para cada uma das variáveis
x1 x2 e sejam 32 parâmetros eu não fiz
ponto alto aqui você vai ter oito ou dez
oramos então alimentação para o tamanho
bota sete não há problema de overfeat
para o modelo a modelo multinível
empréstimo feito ao se volta aqui não
sei que perguntou agora você tá falando
aqui ó os pacotes é ml meme4 são bons
também pegar o glaus tão bom
o porém online1 ele não mostra a
significância estatística meu já já
passei tanta raiva com isso é muito bom
mas ele não mostra significância
estatística dos efeitos aleatórios ou
seja tem uma variância lá do zero do
estética aquele cara é significante ou
não é
a entender entendeu então quer dizer é o
gl mnt mb é mais recente e incorpora
todas essas restrições são iguais do
ponto de vista de estimação dos
parâmetros mas é mais completo de ntn-b
ele ele ele mata ele engloba os outros
dois e mais moderno já passei muita
raiva com m é com n lm entrega m4 tempo
e as vantagens também você você não
lembro agora mas eu tenho impressão que
não faz um frente acho até impressão
posso até depois confirmar e depois
passa thiago thiago tem seu contato e
também vocês podem ficar à vontade para
mandar um e-mail porque no final da
apresentação tem no e-mail e respondo
todas as vezes às vezes eu demoro um
pouco mas só última fechar então que a
gente já tá assistindo aqui o pouco eu
te ouvir aqui professor você me ensinou
que é uma boa pra
esse é o primeiro modelo multinível
antes de utilizar o gml tradicional é
usual o modelo multinível para um
problema de classificação binária
regressão logística há muito muito tempo
a chover aqui tá perguntando para ele
foi uma mestre antônio aqui
o dono outra excelente pergunta também
como todas é na verdade na logística
você vai estimular uma função de
probabilidade que é uma zig mande né por
west na multinível vocês bem ser uma
estima uma sigmóide para cada contexto
fica muito legal a gente faz isso isso
também é uma simbiose para cada contexto
é uma função que uma visita e
consequentemente idosos baixos para cada
para cada contexto não só para binária
mas para multinomial que eu não todo sim
o jerry ntn-b ele incorpora já essa
classificação no não erre porque não dá
para fazer para a árvore também né
também também não pegar um negócio sobre
isso tiago não é modelagem é filosofia
contexto né fundamento você começa você
começa a fazer para você quiser entender
os contextos para
a geladeira agência diante do
comportamento dos dados no j7 antônio
seu hoje igual a nossa também também
também são inscritos muito obrigado
pessoal tá agradecendo aqui então fui
obrigado aí mais uma vez mestre então
vamos ver se a gente marca essa dr aí
mais para frente beleza então então eu
agradeço aí mais uma vez brigadeiro pela
presença de todos professor marcos
santos aí obrigado pela presença também
eu que agradeço só eu pago de volta
sensacional aí querendo hoje não
apresentou essa mais uma certeza
incrível né e a bola a sua live quando
mexe marcos né mas amanhã é ruim de bola
então pessoal estamos lá em juízo para
vocês o marco santos mas se faz
orientadas devidamente convidado isso
poder participar o tiago me inclui para
um livro para que eu receba o link do
sul eu quero assistir amanhã com certeza
também os legal hoje nós as 99 beleza
mando com certeza com certeza é qual o
tema da laje é artigos escrever arremate
falar sobre os artigos é excelente esse
jogo né começa a escrever um artigo né
só que legal que é carreira acadêmica
ficar meio perdida né vai começar a
minimamente estrutural na precisa pessoa
que tem uma ideia na cabeça mas não sabe
o como carregar organizar ela no papel
não é verdade né tudo sabe fazer uma
regressão sabe fazer uma uma como é que
eu coloco o seu papel é mais ou menos
para começar a
é louvada deixa amanhã você estar de
brigar show de bola valeu então psol
tivesse ligado mestre galinho belo
horizonte pessoal obrigado o prazer
nacional aí parabéns tchau tchau tchau