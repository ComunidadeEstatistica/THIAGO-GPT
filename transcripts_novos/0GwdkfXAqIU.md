# Aula 05 – Plotando os gráficos de todas as ações normalizadas - Trading com Dados

- **URL:** https://www.youtube.com/watch?v=0GwdkfXAqIU
- **ID:** 0GwdkfXAqIU

## Transcrição

o que eu queria mostrar para vocês agora
e como que a gente consegue lotar todas
as colunas todas as Sensações não
gráficos Só se a gente fosse usar o
mesmo raciocínio que a gente usou aqui
usando lote imagina postar cada plotar
né cada uma dessas linhas separadamente
seria um trabalho gigantesco imagina
cada uma dessas meninas manualmente tem
uma outra forma tá então coloca aqui é
ser quiséssemos botar todas as colunas
é bem uma forma é usar função
é a função meltina da biblioteca
reshape2 como eu tinha falado para vocês
no começo porque eu consigo modificar
aqui o meu deita freio de tal forma que
isso fique mais factível então o que é
que eu vou falar para ele primeiro vamos
aqui a
a data como referência
o e vagabundo name vai ser Siri onde eu
quero chegar pessoal não tem um deita
firme novo vou chamar Sic DF eu já fiz
uma entender o que que eu fiz aqui e se
deitar frame ele pegou cada uma
uma das das ações né pegou as datas a e
transformou a paz com série temporal na
verdade ele pegou a os valores aqui ó
vamos voltar para o nosso dentro da
frente original
nós pegamos então para cada uma das
ações né pegamos os seus valores para
cada uma das datas e a gente mudou o
formato do deitar firme percebam que
agora eu não tenho mais ações em colunas
né agora percebo que tá tudo empilhado e
porque eu fiz isso aqui porque se a
gente usou a função José plot
e com ADF aqui dentro a gente vai passar
o esthetics dos dados o valor aqui nessa
seu próprio valor então tivesse velho tá
só que aí eu vou dizer para ele que na
hora de criar as linhas né Na hora de
fazer o diâmetro online
e ele pode usar né no estéticos a
separando né as linhas separando por
cada cor
e ele pode usar como referência aqui ó
e a própria coluna Siri veículo toda vez
que ele vê um siri diferente ele vai
atribuir né uma outra língua atribuir
uma outra cor Então faça serviço aqui e
a gente vai obter um gráfico obviamente
que não vai ficar a um gráfico Super
Fácil de visualizar né porque vai conter
tudo talvez até nem Apareça aqui para
gente mas a ideia é que vocês consigam
visualizar tudo isso não gráfico só e já
de cara a gente ver algo bizarro aqui né
Tem uma ação aqui tem um papel a que
caiu bastante até fiquei curioso pessoal
vamos ver que papel é esse né se a gente
voltou aqui para o nosso total
e vamos ver se aparece aqui para gente
i na data mas se sente o papel que mais
caiu os olha aqui bem rápido
E aí eu não consigo ver
é porque alguém me tira não mostra tudo
aqui mas aí já fica com exercício então
para vocês né se vocês tiverem
curiosidade quiserem ver com oq papel é
esse né que é ação teve esse
comportamento tão estranho aqui aí vocês
podem
e a
e vocês podem replicar essa análise para
encontrar esse papel para descobrir que
papel é esse como eu falei obviamente é
algo não é tão factível a gente colocar
tantas ações assim né 70 papéis no
gráfico Só para tentar olhar então a
gente pode fazer vamos pegar
e o nosso original que é o número total
eu vou fazer novo total
U2
É mas eu não vou Total E aí eu vou pegar
para facilitar Vamos fazer assim vamos
pegar a coluna Cadê a base no total bem
primeiramente eu ia precisar da coluna
de data né então candidata imagina que
esteja lá no final
e como novo Total tem 72 colunas tão
óbvia mente eu vou precisar da coluna 72
mais antes
eu poderia colocar dar uma 20 por
exemplo um a gente aqui eu tô
selecionando colunas aleatórias tá esse
aqui é totalmente arbitrário Vocês
poderiam selecionar a coluna que vocês
ações que vocês gostam né papéis que
vocês queiram analisar de fato
Ah tá então eu coloquei aqui cerca de 20
papéis e aí eu vou repetir o mesmo
processo vou pegar a estuda aqui
é só que ao invés de eu fazer com todas
as ações eu vou fazer com essas agora eu
trouxe tá mas tudo aqui continua sendo o
meu DF e eu vou gerar o novo gráfico com
Jefferson e aí percebeu que você com
gráfico bem mais fácil de ser analisado
né Vamos tentar pegar um pouquinho aqui
a ver que papel foi esse pênis
comportamento aqui a
eu acho que foi esse né pessoal b t o w
e três e aí ele pô subiu mais de 9 vezes
né
Ah então beleza existe uma outra opção
também é também usando a biblioteca Mel
também usando GG Cláudia Caso vocês
queiram colocar em prótese diferente por
exemplo então só presente ficar deixa eu
colocar aqui em vez de 20 colocar quatro
primeiros papéis por exemplo se a gente
colocar se todos eles no mesmo no mesmo
lote e sei a isso daqui não é um pote
bacana tranquilo de analisar tem outra
opção também tá que são blocos separados
para visualizar
G1
em lotes separados E aí o que é que
vocês fizeram fazer pega isso daqui a
gente só vai mudar alguns parâmetros
Olá neste comando tá
e o diâmetro Elaine Eu Deixaria vazio e
aí eu adicionaria esse parâmetro aqui eu
já já vocês vão entender fecha
Oi Cleane
e já tem um Grid aqui
Os seres.
bom então em vez da gente ter um plot só
com todas as ações no mesmo gráfico ser
teriam gráficos separados E aí depende
né Tem aplicações que você quer atender
esse formato a dependendo da aplicação
se eu tiver construindo fazendo análise
para você mesmo para sua carteira Talvez
seja melhor de todas elas não gráficos
só porque a sua os seus insights nessa
tomada de decisão fica bem mais fácil
bom então na próxima sessão a gente vai
ver como calcular correlação entre essas
ações e depois que a gente fizer isso a
gente vai fazer um breve exercício para
criar o nosso próprio portfólio e uma
vez que a gente criar o nosso próprio
portfólio a gente vai comparar esse
ponto fólio com o ibov e o spi Ranger
também é