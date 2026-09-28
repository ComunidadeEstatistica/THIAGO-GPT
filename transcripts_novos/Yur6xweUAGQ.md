# O que é Gradient Descent e como aplicar no R

- **URL:** https://www.youtube.com/watch?v=Yur6xweUAGQ
- **ID:** Yur6xweUAGQ

## Transcrição

o pessoal de volta aqui no canal está
assinado pra falar sobre grid decente é
no primeiro vídeo a gente falou sobre o
técnico pode chan
mas em termos conceituais obediente
senti ele deveria até ser abordado hoje
o que é aqui que está o berço dessa
questão de usar derivativos ao cálculo
diferencial para minimizar erros em hoje
desprotegidas o pioneiro aqui foi o caos
em alguns caos
a idéia é decente é uma agente otimizar
a funções a gente achar mínimo de
equações achar pólo de equações achar
zeros é fazendo os de cálculo
diferencial então um cálculo a gente
aborda isso será a cura ou a função ali
você calcular a taxa de variação do
valor dela em relação ao entrada uma
variável que tá tá sendo usada como
argumento o que acontece é que muitas
vezes não é fácil achar politicamente e
se nenhuma ir e qual foi o a sacada do
caos
então pensando também em astronomia e
você tinha uns copos em função de muitas
variáveis a taxa é analiticamente ele
pensou seguinte novo acho legal as
equações que definem essas expectativas
e você é saber o valor delas com base
nisso eu vou saber se essa derivativo
ela tá sinal negativo positivo se ela é
tão grande de voltar
tatá pequena e com base nisso é como se
eu fizesse uma estimativa numérica de
sininho
o ano pequenos passos eu vejo qualquer
dota quanto eu tenho que caminhar pra
minimizar esse meu erro nesse espaço de
dinheiros a mensagem desse foi esse
ele foi esse então assim ele define
parâmetros a que ele definiu como tétano
no original e ele vai com lanças
derivativos inter ano e terão terão até
que esse ingrediente ele minimiza
totalmente ele vê nisso e isso indica
que ele está estacionado ali fazendo uma
analogia mais o visual
a gente volta pra que ele desde está
caminhando num espaço que seria colocar
o ou a montanha do tipo uma piscina é
bom na banheira a dona um valor que você
tem que dizer então se você caiu de de
olhos vendados o que você pode fazer se
arrastava no país sabe se está inclinado
para cima ou para baixo
e se você pode por exemplo continuar de
ensino para chegar num momento em que
vai parecer que tapam o que você vai
voltar a subir vai vai mudar o sinal e
nesse ponto você assume que seria 10
o problema é que você pode ter um
terreno acidentado um espaço que que não
é conversa de judeus não é contra o
então você não vai ter nem global tão
fácil você pode cair nessas armadilhas
aqui ficar estacionado mas na maioria
das vezes isso não vai acontecer
especialmente quando estavam com
exemplos mais simples
então obviamente você vai ter uma
entrada que esse xis dimensões
a gente vai trabalhar com duas dimensões
com seus cumprimentos você tem um
afirmou ele está analisando qual seria o
cumprimento da lei onde uma pedra dessa
flor de uma célula ea largura dessa
mesma século
então com base nessas medidas a gente
multiplica pela matriz com dois pesos
tá
eu peso 2 e com base nessa saída nós
fazemos uma predição de qual seria a
espécie e essa é uma competência
com base nessa previsão a gente compara
com gabarito e aí que a gente brinca com
essa questão de derivativos
nesse caso aqui a gente assume a ideia
de que existe uma relação que está
trabalhando num espaço que vale uma
métrica euclidiano que significa é bem
parecido com o nosso emoção assim o
plano de trabalhar com a geometria
básica mesmo que trabalha em espaços
planos
por exemplo se eu tenho um ponto muito
preto um ponto que a cinza transpondo
isso pra essa idéia de um espaço com o
com essa métrica
eu pegaria um ponto ficaria com medidas
50 antes de coloração ao pixel subtrair
o conta com 150 e ele é levar isso ao
quadrado
essa é a nova e original mas com um
então com base nisso a gente vai fazer
esse cálculo e atualizar esses pesos de
que maneira eu pego minhas coisas atuais
e trabalho eles de maneira que eles são
atualizados sem o voluntário deles no
caso aqui o
os presos vão ter mais um chamar assim
está no momento que eles já foram
apresentados aos aos 20 observou
gabarito a gente vai atualizar a eles
conforme o valor desse delta aqui e se
der pra gente que é calculado com base
na soma da dívida ativa como vale
europeu deliberativa
a gente só fica um termo de normalização
que é o nosso e parâmetro esta é a nossa
taxa de aprendizagem
aí começa aquela questão assim como que
a gente ter fim e se separam metros
machine land mas também não é o o o foco
aqui neste vídeo o código que acabou de
explicar essa função aqui define a
classificação se o valor for maior do
que não quiser você trocar ele pra um se
ele for menor você tem aquele para -1
aqui a gente pega dimensões na entrada e
analisa a nossa mata de pesos e cria ela
e as nossas posições aqui a gente define
e 6 0
então a gente começa sempre a agente
sorteio e se essa o gabarito nosso
entrada e começa a atrapalhar suas
entradas sempre dessa maneira multiplico
perpetrada chama isso traz como a nossa
produção com base nisso a gente vai
calcular deliberativa como esse cabelo
relativo aqui já que não estava falando
em uma médica que diana a gente vai ter
o nosso erro no caso vai ser qual foi o
gabarito - qual foi nosso chute
a nova ação geralmente essa aqui e pelo
menos 20 não com chapeuzinho ao quadrado
o objetivo aqui sem se alongar muito
se a gente for considerar que isso aqui
tá também em função dos presos como é
aquele produto de chineses w
a gente vai fazer água do tempo pra cá
então sido szavay vai entrar
multiplicando o que tem um produto ea
gente vai também tirar essa derivativo
aqui em relação ao peso no livro eu faço
essas necessidades matemáticos com mais
calma com mais de gurupi tudo explicado
e é isso que a gente vai usar aqui no
nosso corpo tem um truquezinho e
certamente uso mas no final das contas é
pior
essa vai ser a nossa alternativa no caso
é talvez aquele preparamos o que foi
citado e hoje ele já estava explicado
por um meio então dois aqui da frente
sorriu a nossa negativa ea gente também
vai multiplicar pelo input que a deriva
de fx aqui esse é um w x o que você tem
que saber todos esses essas coisas de
costa essas continhas algébricas até
porque vão variar com o modelo que está
usando com a sua ativação cada problema
estou citando aqui pra manter um
rigoroso já tem material demonstrativo
então aqui a gente está imprimindo valor
final dos pesos
separamos aqui a as entradas a saída
desejado do dólares e rodamos ele aqui
com esse time tem as predições seria
certo e errado ea brincando também com
esse parâmetro você consegue respostas
maiores o pior especialmente não não
deve formar muito bem porque você vai se
ampliar eles são uma vez aquela mostra a
gente vai rodar o gradiente uma vez só e
tão somente cem passos
a gente trabalha com a rede como mostrou
o último vídeo a idéia é que a gente
facilmente isso apresente muitas vezes é
um dos motivos pelo qual a gente precisa
um pouco agitado como que isso é ótimo
no caso do jazz ipi que hoje o couch e
se deparou de não ter solução analítica
você pode chamar isso de gente decente
érico
os derivativos da função de erro e outro
o outro e quando a gente tem um acerto
muito grande então a gente faria um a
operação potencial gigantesco você pode
ser santo é ali pode pegar amostragem
daquele dado fazer algumas alterações
como que a derivativos espécie de
conversa em pouco tempo você vai chegar
na estimativa razoável
espero que tenha ficado bem claro ou o
conceito do evento e sente que tem
aplicação no link tem um tempinho nos
links abaixo se encontra o link do livro
e se tiver alguma dúvida ou quiser
entrar em contato nem metade disponível