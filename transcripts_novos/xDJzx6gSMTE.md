# Parte 1 - Random Forest - Competição Codenation - Previsão da nota de matemática do Enem 2016

- **URL:** https://www.youtube.com/watch?v=xDJzx6gSMTE
- **ID:** xDJzx6gSMTE

## Transcrição

oi meu nome é gabriela eu tô aqui pra
mostrar pra vocês um artigo que eu
publiquei no médio sobre mach nani que
ele foi feito para resolver no caso
mostrar os resultados e passo a passo
para resolver o desafio do coi de nation
o artigo ele está aqui no médico se
vocês quiserem e me adicionar que gabi
ano mas eu vou mostrar pra vocês
a versão do ranking do fórum no notebook
no caso eu fiz ele aqui no jogo de
notebook ficou mais interativo e eu vou
falar pra vocês aqui né sobre a
resolução desse desafio bom que esse
desafio pra que ele foi feito e foi
feito para prever nota de matemática do
enem de 2016 ea gente tem aqui né no
hosite coordination não falar um pouco
sobre o que ele traz vários desafios
ele tem várias opções de desafios na
área de ciência de dados em várias
outras áreas
você pode acessar aqui cody neste ponto
com ponto br acessar os desafios e aí
você pode escolher aqui é que tipo de
jornada que você está querendo
no caso ele serve para você adquirir
experiências na na confecção de projetos
fazer projetos você pode colocar esses
projetos no seu portfólio a gente vai
olhar aqui no caso estou fazendo
o desafio da área de eficiência de dados
a gente tem aqui vários desafios no caso
para reconstruir novos anéis melhores
colocados e aqui eu estou fazendo o que
prevê a nota de matemática do enem é eu
já tenho um desafio aberto aqui quando
você acessa passar a página do desafio
você vê todas as informações que você
precisa para resolver este desafio e já
indicam quais as bibliotecas que você
deve usar do do python né que seria de
regressão scalambrini ea pandas no caso
você vai treinar essas
text eles é fazer o desafio já tem todos
os requisitos que você precisa
já dão todos os detalhes e como que você
deve enviar o arquivo de resposta né
o arquivo de resposta é é através da
forma que eles vão utilizar para
verificar o seu acerto quantificar
quanto você acertou
é desse desafio quando você conseguiu
prevê nem usando o seu modelo
nesse desafio
então é essa resolução eu consegui
acertar 67%
é uma pontuação ainda que não está muito
boa mas eu vou melhorar esse modelo
porém já me incentivou a fazer um
pequeno tutorial sobre isso até porque
fazendo esse pequeno tutorial fazendo
esse notebook eo artigo eu já consegui
alguns feedbacks muito positivos pessoas
querendo ajudar né incentivando a
melhorias e eu gosto muito de
compartilhar esses conhecimentos
acho que através da troca de
conhecimento a gente acaba aprendendo
muito mais né
agora vamos falar sobre a solução é
desse desafio nesse modelo aqui que eu
fiz e ainda vai ser ainda vai se ajustar
né
vamos falar sobre a solução é bom pra
começar esse desafio
a gente precisa de dois arquivos que já
vão ser fornecidos quando você começar a
iniciar o desafio já vou passar esses
arquivos de testes de trem e precisar
simplesmente desses dois arquivos vai
fazer a leitura desses arquivos e vai
conseguir fazer o modelo é pra poder
fazer esse tutorial eu utilizei alguns
exemplos e conceitos do tutorial feito
pela direita site que é produtor é muito
bem feito muito bacana que fala sobre a
previsão também de no caso eles
trabalharam com vinhos da taxa de 20
está a prever quais eram os melhores
vinhos
então ele trabalha com um é pré
processamento e vários conceitos que eu
vou mostrar aqui então tem várias
informações novas
vários conhecimentos que eu adquirir
através desse tutorial recomendo muito
esse é esse blog ele direita saias tem
muitos fatores bacana e agora vou falar
aqui sobre o desenvolvimento desse
desafio
então eu vou importar aqui todas as
bibliotecas que eu preciso eu vou salvar
as informações que eu tenho aqui dessa
série de trem e de teste em data frentes
para poder utilizar manipular essas
informações e vou salvar nem vou criar
na verdade um da frente pra poder salvar
é os resultados finais para poder fazer
esse modelo competitivo
o primeiro passo é ver com que estão
esses data 7
nem eu tenho data certa mas eu não sei
como eles estão aqui tão preciso
verificar antes né questão de
consistência que seria isso aqui vai
ficar se o datafolha 7 de trainee está
contido na sete de unidades da taxa de
teste está contido no processo de trem
porque eu preciso verificar antes né se
ele se chama se ele é uma parte desse
trem porque eu preciso testar com as
informações que estão contidas lá eu
preciso é pra proteger o modelo
preditivo bacana ver como é que esse
modelo está eu preciso testar com as
informações que estão contidas lá então
eu vou verificar é executado aqui ele
vai dar um ok olha ele é uma parte
simples
as informações estão contidas aqui então
eu posso é salvar que no caso o número
de inscrição que vai ser uma das minhas
respostas finais e vou pegar somente
para fazer regressão linear no caso para
fazer regressão eu vou
é pegar somente as variáveis que são
numéricas usar somente os números porque
pra fazer uma regressão só posso usar
valores numéricos e aí eu preciso
verificar qual a correlação desses
valores numéricos
eu escolhi algumas algumas fitas aqui
seriam idade
se esse aluno e trainer ou não as notas
das provas
eu vou verificar qual a correlação
dessas informações
verificando aqui é essas correlações eu
posso perceber que as notas têm o valor
é de correlação mais relevantes nesse
caso existem valores positivos e
negativos e que têm mais influência nem
pra poder prever esse modelo assim a
correlação maior com uma com a outra
então é mais interessantes são valores
mais interessantes para ser usados nesse
modelo
então eu vou separar que em uma lista é
o windows xbox esses valores por poder
depois selecionar somente esses valores
e vou representar aqui usando esse
endereço
a correlação desses dados eu posso
observar aqui que eles têm uma boa
correlação geralmente são valores acima
de 0.5 o que mostra que são valores
interessantes pra poder fazer essa
regressão eu consigo estimar essa nota
de matemática através dessas outras
notas antes de fazer esse modelo
preditivo eu preciso fazer um tratamento
e uma validação dessas informações o que
pode acontecer neste data 7 treino eu
vou verificar aqui que existem registros
cujas notas estão todas vazias
então tem aluno cadastrado aqui nesse
taccetti que saco todas as notas vazias
esse registro não é um registro bom para
trabalhar em cima dele ele pode
atrapalhar a performance do mesmo
preditivo então se todas as motos estão
vazias eu vou tirar
simplesmente vou remover esse registro
do meu data 7 é depois que eu fiz essa
remoção preciso verificar também a
questão das outras notas porque elas não
podem ser nulas não podem ser vazias
porque elas podem influenciar mal meu
modelo é ele não vai
o relator também não vai deixar de
trabalhar com valores nulos
então preciso resolver essa situação
antes de fazer o modelo não vou
verificar aqui nos 2 das sedes se
existem valores nulos
vou quantificar esses valores não
verifiquei que eu tenho provas com
valores vazios registros com uma ou mais
provas com vários vasinhos e aí eu
preciso tomar uma decisão quanto a isso
é preciso solucionar esse problema e eu
tenho aqui três opções para solucionar
esse problema no momento eu posso
excluir essas notas no caso excluiria
toda a linha o que não é uma coisa boa
porque é esse data 7 ele ainda está 7 um
pouco menor e vai influenciar no
resultado final a pagar as linhas
isso não vai ser uma coisa boa eu vou
perder alguns registros que por exemplo
podem estar faltando uma ou duas notas
só então eu não vou usar essa opção
eu posso preencher com zeros
é eu fiz alguns testes e não deu muito
certo não ficou um modelo modelo não
ficou muito bom e gerou resultados meio
complicadas assim os resultados ruins
é por exemplo 20 por cento de acerto e
então gerou um modelo muito bom e eu
posso preencher com a média das notas
encontradas que vai ser a opção mais
viável que vai ser usada nesse estudo
porque gerou é uma previsão melhor dessa
nota de matemática
no caso aqui eu tô preenchendo valores
né preenchendo os dados que estiverem
nulos né com a média desses valores
a média de cada nota no caso de cada
coluna e esse