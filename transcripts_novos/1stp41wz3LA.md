# Análise de Sentimentos em menos de 10 minutos - Parte 1 - Utilizando o Framework Orange

- **URL:** https://www.youtube.com/watch?v=1stp41wz3LA
- **ID:** 1stp41wz3LA

## Transcrição

olá pessoal tudo bem
meu nome é nicolas conceição só
programador de bi e analytics uma
multinacional farmacêutica informação
estatístico
sou formado em ciências da computação
mas venho trabalhando com analytics
martin milani e inteligência artificial
mais ou menos uns três anos
vou terminar esse ano agora 2019
o programa do sas de datas as vem
acompanhando o trabalho do professor
thiago luiz tatit fisco achando bem
bacana e aí resolvi gravar ele pediu
para gravar esse vídeo é uma nova
ferramenta que tá me ajudando no meu
dia-a-dia chamado horas de toque
essa ferramenta hora de ela você
consegue colocar no google hoje data mas
só consegue fazer o download
ela vem também no pacote da anaconda ok
e essa ferramenta é uma ferramenta muito
bacana eu estou utilizando no meu dia a
dia tá é iniciante ou pra quem já
trabalha com algum tempo porque é uma
ferramenta bem visual de arrastar a
importar dados tal e ajuda no nosso dia
a dia tá aí se tutorial vou falar um
pouquinho de análise sentimentos
trazendo do twitter
espero que vocês gostem desse tutorial
está ok beleza e na parte esquerda aqui
a gente tem o que a gente chama que de e
tabelas que a gente tem os widgets aqui
então o tratamento de dados
tá tem uma parte de visualização com os
quatro potes distribuição box pote
decidiram proibir uma série de coisas
os modelos então a gente tem aqui desse
jeito e redes neurais é nojento que
regressam linné relaxa sbn então a
ferramenta ou pensou se pra quem está
iniciando para quem quer fazer alguma
coisa muito rápida
ela serve bastante tem a parte da
evolução particionamento teste scorpion
edição matriz confusão análises rock
lift tá que a gente vai aprender agora a
gente vai mostrar pra vocês como faz um
sentimento análises conectando no
twitter e trazendo o que que as pessoas
estão falando no determinado tema tá bom
a gente vem aqui em táxi online
arrasta-o widgets propor o fluxo que a
gente chama e aqui a primeira coisa que
a gente tem que fazer a gente tem que
ter uma conta no twitter tá eu já não
tenho uma conta aqui de teste pra
mostrar pra vocês que nós venhamos vamos
aqui em twitter a pique
lá você vai pegar esse código lá e vai
jogar a achava eu sei que para habilitar
isso aqui tá começou santista
logicamente eu vou puxar um pouquinho de
sardinha para o meu lado
por favor vamos demonstrar os twitters
que estão falando nosso novo técnico no
são paulo a gente vai colocar aqui
naquela ou desiste
são paulo em são paulo tá então o que eu
quero aqui trazer eu quero trazer o
conteúdo tudo que foi em português
dos 250 últimos twitter tá
não quero apenas e twitter e não quero
coletar resultados
então tá falando aqui para incluir o
conteúdo e vou deixar desabilitado aqui
o autor do script on e vou mandar buscar
esses 250 twitter lado do twitter
notem que ele está buscando aqui opa
após atingir 120 twitter nos últimos
tempos pra cá a chamada com o nome de
são paulo ok beleza gostoso os 120
twitters
então vamos dar uma olhada aqui como
está o corpo socorro desses twitter está
bem aqui em corpos viu para ver como
está a estrutura desses twitter
e aqui ó então temos aqui os 120
twitters e aí a gente tem o autor o
conteúdo a data a língua que ele foi
escrita número de likes é o status dele
latitude e longitude então tentará da
mente todos os twitters aqui tá bom
primeiro passo aqui vamos dar uma olhada
aqui na nuvem de palavras que a gente
chama a então qual são as palavras que
estão sendo mais utilizadas aí nesses
120 twitter saque com o contexto de são
paulo lhe nota em que ia a palavra ou a
letra mais usada 139 vezes é o que a
gente precisa fazer nesse nessa etapa
precisa fazer um pré processamento para
tirar as palavras ou a do dar assento
risada uma série a arroba uma série de
coisas que o pessoal coloca no contexto
do do do twitter tá então a gente vem
aqui nesse o indígena do processamento o
que nós vamos fazer aqui a gente vai
fazer um pré processamento então o que
eu faço eu coloco todas as palavras em
letras minúsculas
tá remova assentos tirou html remova url
está então a gente vai fazer toda a
limpeza de estepe 11 que nós chamamos tá
então a língua que a gente vai chamar
aqui em português
e aqui você perceba que estou tirando
tudo o que é mais - assento uma série de
nomenclaturas que está aparecendo lá na
nossa nuvem de palavras tá
uma vez feito isso vamos comparar
a primeira nuvem com a segunda nuvem a
morte é muito fácil você arrasta aqui
para o fluxo conecta o
widgets no que você está querendo e aí a
gente consegue fazer a comparação entre
duas entre as duas nuvens de palavras
está como era e como tal o outro
perceba que agora já apareceu em são
paulo e 124 vezes vai técnico colocará
são abel t
então tá mais limpo ali as palavras pra
gente utilizar bacana tem um trânsito
aqui a tabela
vamos retirar sp aquino também aqui no
processamento e na última a palavra que
você fez barra invertida
automaticamente ele já vai retirar
aquela ip
de lá de novo percebeu que já subiu e
beleza
não há segredo aqui você deixar o mais
limpo possível dessas estão piores
para você ter uma análise de sentimentos
do do twitter o mais real tá então o que
nós vamos fazer agora o próximo passo
depois que a gente fez a limpeza desse
top world
a gente vem aqui em sentimentos análises
tá então que em sentimento análises ele
vai fazer aqui ele vai pegar ele vai ter
um sentimento de cada documento né do
twitter é de 120 twitter utilizando o
módulo sentimentos que aqui a gente eu
vou te mostrar pra vocês
o valor da da biblioteca do pai tom
henning
tk uma biblioteca sentimento amares
bastante famosa para quem mexe com o
sentimento de análises né então ó topo
utilizando a vaga era aqui e ele já vai
fazer sentimento análise
então o que ele faz ele vai lá no
servidor vai buscar esse sentimento
análise pelas palavras e vai trazer pra
gente aqui ok então depois que nós
fizemos isso a gente vai lá naquela
série de bibliotecas que nós temos e
vamos fazer uma seleção de colunas
porque é uma seleção de togo colunas
porque lembro que eu mostrei pra vocês
eu tenho uma série de colunas latitude
longitude aqui ó autor mas eu não quero
utilizar esse essas colunas esses campos
então que eu vou deixar aqui vou deixar
o positivo eo negativo que o contexto do
o contexto do do texto vou deixar o
texto com pessoal digitou no no twitter
toque
olha que bacana uma vez que a gente já
jogou o sentimento análises e já cria
quatro colunas pra gente
análises positivas negativas e neutras e
aqui um peso que lhe dá pra essas
análises aqui tá ok então vamos dar uma
olhadinha que o que ele está mostrando
aqui pra gente a gente vai pegar aqui
uma vaga no módulo de visualização e vai
pegar aqui o raid mep como funciona a
rádio mep inep
ele vai fazer o quê
uma distribuição não vai fazer uma
separação né
pela média de caminhos e vai mostrar que
tudo o que é positivo negativo em eu tô
pra gente
conforme ele for mais azulzinho mais
negativo ele é tá
e agora a gente vai colocar um cortes
pra ver a análise sentimentos que eles
porque estão falando do são paulino
o novo técnico do santos no twitter
vamos fechar aqui algumas coisas abertas
e se não tá tá com um problema vamos ter
aqui vão colocar uma tabela só pra ver
que eles estão falando aí
recentemente análises vamos jogar uma
tabela é aqui que quero aqui nós temos
aqui lembro que eu falei pra vocês então
ele criou é os sentimentos positivos
negativos e neutros né
e eu deixei filtrado o conteúdo como ver
aqui o que ele fala de positivo do povo
são paulo então você percebe que a gente
consegue filtrar do maior para o melhor
então falando positivo aqui pra ele não
me mata do coração meu amor fala logo
sobre o são paulo então quer dizer ele
está classificando como o twitter
positivo ou negativo para mim faz
sentido 26% né a probabilidade disso é
um twitter negativo
então são paulo e pede e victor ferraz
permanecerá no santos o são paulo tem
interesse no lateral
ah então aqui na verdade a probabilidade
negativa no elenco do santos e são paulo
são paulo o interesse de contratar o
victor ferraz e parece que são paulo e
pediu pra ficar lá no ficar no santos
então isso aí não é uma coisa bem muito
legal pro são paulo mas é bom
melhor ainda né então teoricamente
questão de 56 minutos a gente consegue
fazer um sentimento análise do twitter
então você imagina você pode colocar o
nome da sua empresa pode colocar temas
atuais pode colocou colocar uma série de
de temas do twitter que ele vai fazer um
scrap dessa nesse tema e aí você vai
melhorando e vai fazer um sentimento
análise nesse desse nesses twitter que
você tem o objetivo de analisar a ok
outra coisa bacana