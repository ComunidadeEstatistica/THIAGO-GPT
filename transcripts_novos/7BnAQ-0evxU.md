# Aula 11 - Introdução à Quantmod - Curso de R para Finanças Quantitativas

- **URL:** https://www.youtube.com/watch?v=7BnAQ-0evxU
- **ID:** 7BnAQ-0evxU

## Transcrição

[Música]
fala pessoal sejam muito bem vindos aqui
aos poucos e marketing meu nome é
leandro guerra hoje é o dia da aula 11
do curso de r pra finanças quantitativas
será a primeira vez que você tá
aparecendo por aqui se escreve agora no
canal também já deixa o seu link para o
vídeo para ajudar o canal a crescer na
comunidade do youtube e na hora de hoje
como havia prometido na aula 10 quando
expliquei como criar o seu primeiro
jogo-treino em eu vou dar mais detalhes
para vocês sobre a biblioteca com
timóteo que é um pacote pr que vai te
ajudará a ter informações mais complexas
para os seus modelos de finanças
quantitativas se você quiser adiantar já
algum assunto depois da aula
convido vocês a visitarem o site da
biblioteca onde mode pontocom e lá tem
bastante exemplo a uma documentação para
você seguir na aula de hoje eu vou
aprofundar os conceitos que mostrei na
primeira aula que na verdade eu sou
capturar os dados e protegendo gráfico
hoje eu vou mostrar mais funcionalidades
da biblioteca então começando a gente
carrega a mesma chamando o comando lab e
colocando com timóteo
essa é a primeira vez que está rodando
ela não tenha instalada roda a função
está o pec-g se coloca entre aspas o
nome da biblioteca quant mode e vai
fazer a instalação como eu já tenho não
preciso rodar esse código aqui então
executou um livre e faço a função
principal que é a função ghetti symbols
que vai me trazer os dados históricos do
ativo que eu quiser pegar então por
exemplo tem aqui os dados históricos do
google ea fonte que é a abreviação aqui
de sons
a gente vai colocar o rio porque a rua
porque antigamente até oa com timóteo é
pegava os dados do google finance também
mas o google descontinuou serviço então
agora funciona apenas o yahoo
quando eu executo é esse comando ele vai
criar aqui um objeto com os dados
históricos do google nem vai no momento
quando você abre pra ver o que tem
abertura máxima mínima fechamento volume
eo preço ajustado detalhe eu não
especifiquem aqui nenhuma data o que a
função automaticamente faz por padrão
era pego dado mais antigo 3 janeiro de
2017 até o dado mais recente que vai ser
o dia né fechamento de ontem porque hoje
dia 18 ainda não acabou então vai até 17
dos 109 ok mas eu não me interessa dado
assim tão antigo eu quero restringir o
período de análise
então vamos criar o nosso período de
análise customizado como você vai fazer
você cria uma variável qualquer chamado
aqui de estar aqui dentro e atribui a
data que você quer pescar o dado mais
antigo então vou colocar aqui é se deite
pra gente converter a data por exemplo
de 1º de janeiro de 2017 e aí o formato
é ano mês e dia você estabelece a data
final daí vamos chamar the end the date
onde eu vou colocar de novo é evidente e
vou colocar até o dia de ontem pelo
mesmo dia que eu gravei este vídeo que é
setembro de 1817 de setembro de 2018 com
um pouco complicado pensar que editais
para frente nesse formato
mas ok então vamos arrumar um nome aqui
está tudo do jeito que a gente roda
esses dois valores
e agora a gente chama novamente a função
ghetti símbolo para restringir o período
de análise porém você não precisa pra
cada vez que for chamar um ativo fazer
diversas funções gap símbolos o que você
pode fazer é fazer uma seleção dos
ativos para análise
então você pode passar um vetor que a
gente aprendeu nas primeiras aulas já
com as informações dos tickers então eu
crio uma variável chamada ticker uso um
vetor criado aqui por isso sim e onde eu
vou ter
assim foi muito as informações por
exemplo do índice bovespa que é o acento
circunflexo entre aspas vou pegar também
aqui a informação do bitcoin com o dólar
só pra gente ver uma coisa um pouco
e vou pegar as informações da petrobras
então coloca quipedro quatro pontos se a
esses títulos são assim porque é assim
que eles estão disponíveis lá no yahoo
finance por isso é diferente
provavelmente ainda sua corretora roda
críticas e agora sim eu vou capturar os
dados de uma forma mais ampla
chamando novamente a função guedes
symbols porém agora como parâmetro eu
passo a variável tickers coloco a fonte
o yahoo com certeza só que agora tenho
mais a facilidade de além da fonte
especificar from que aí eu vou colocar
start leite e tio que é a nossa and
desde quando eu juro que jett symbols
ele te gera um homem dizendo que a
informação do da bovespa ontem alguns
valores me sem isso acontece devido a
fonte dos dados não ser a melhor de
todas que é o yahoo
porém você vê que já tem aqui os outros
objetos além do google bitcoin bovespa e
petrobras feito vamos ver como fica isso
num gráfico então eu vou chamar aqui
os gráficos a função principal é a
função chamada charice lewis onde você
vai passar simplesmente o nome do ativo
tal qual está aqui no embalo ambiente
repara que aqui no tic do tipo que se
chama chamar bovespa com acento
circunflexo porém aquino invariavelmente
ele não tem então eu chamo aqui no chat
senhores da mesma forma simplesmente
roda o comando
tenho aqui o gráfico do ibovespa de 2017
até o dia 14 por exemplo que é a última
informação é disponível se eu der um
zoom você pode ver um pouco mais detalhe
não é um gráfico interativo ellison mais
informativo mas já dá pra você tenha uma
noção do que está acontecendo legal como
a gente pode até mudar um pouco esse
gráfico aqui pra ficar melhor
a gente pode chamá a função chats e
redes colocando por exemplo as cores
então
de novo para a bovespa só que eu vou
usar uma função que chama um parâmetro
perdão que chama muito com que ele te dá
até quatro padrões definidos de cor onde
eu vou usar como verdadeiro esse
parâmetro aqui e vou chamar esse tema o
haiti que é o tema com o fundo branco
então exatamente o mesmo gráfico muda um
pouco porém ainda está meio fim o dever
eu particularmente aqui vou preferir o
tema anterior
então o fato só pra mostrar pra vocês
como funciona
esses dados estão no diário se você tem
uma série muito longa pode te complicar
você pode passar o gráfico semanal por
exemplo ou para um mensal vamos fazer um
exemplo aqui no mensal onde eu vou
chamar de novo chávez se isso porém
agora vou colocar um outro parâmetro pra
esses dados um parâmetro to mantle onde
ele vai transformar aquela série diária
numa série mensal
aí eu posso também customizar para
deixar mais bonitinho que o kindle
quando for de alta então coloco aqui a
collor com a ponto com como a cor de
quando é alta e vou colocar brin e
quando for baixa aí você coloca que dá
um ponto com o ok e aí você coloca o que
você quiser aqui por exemplo vamos
colocar o haiti quando for baixo só pra
você vê a diferença
tá não fica um gráfico aqui é verde e
branco
já para o semanal veja a diferença do
gráfico anterior que a gente tinha para
o diário está mostrando isso aqui só pra
vocês verem a capacidade de customização
o que a gente tem dentro da biblioteca
com timóteo
o que mais dá pra fazer você pode
adicionar os tão falados em famosos
indicadores técnicos
só que pra isso você precisa chamar uma
outra biblioteca que é a biblioteca ttr
que é a biblioteca que contém já
construído
como funções nativas esses indicadores
técnicos então vou chamar a biblioteca
carrego ela e vou colocar aqui
shaq se eles vamos colocar agora a
petrobras como um exemplo
mo chamar do jeito que é padrão só vou
fazer uma coisa diferente esse volume
aqui às vezes pode criar um poluição no
gráfico então coloca o volume como no e
isso vai fazer o quê quando eu coloco
tea é igual a no isso vai retirar um
volume lugar ótimo fica um pouco mais
legível do que anteriormente
o que eu posso fazer agora coloco a
função a de sempre m a c d e e adicionar
nesse mesmo gráfico quando você executa
assim em seqüência
vou colocar o mcd no gráfico além do mst
no gráfico quero colocar aqui uma banda
de bolinha e vou colocar também um cc
são aí três dos principais indicadores
que que existem então seu gráfico aqui
fica completinho já um pouco mais
bacanas e começa a haver coisa diferente
bem legal né pessoal saber que poucas
linhas de códigos alguns minutos de aula
você já consegue desenvolver um negócio
que parece até a uma melhor na verdade
que muito bronca por aí beleza pessoal
essa foi à aula de introdução na aulas é
na próxima aula 12
eu vou mostrar como você cria já 13
desses tem tendo como vantagem esse
cálculo automático ak dos indicadores
que fica bonito pra caramba
espero que vocês estejam gostando do
curso um grande abraço deixa escrito
aqui embaixo nos comentários qualquer
dúvida qualquer sugestão e até o próximo
vídeo tchau tchau
[Música]