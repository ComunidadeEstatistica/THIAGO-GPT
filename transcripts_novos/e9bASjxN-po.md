# Lesson 1 - What is Power BI? - Power BI: From Ingestion to Storytelling

- **URL:** https://www.youtube.com/watch?v=e9bASjxN-po
- **ID:** e9bASjxN-po

## Transcrição

Tá, eu falei sobre cubo, sobre data
visas, ferramentas de BI, né? O que que
isso tudo significa? Vamos começar aqui
falando sobre o cubo, né, para vocês
entenderem um pouco do conceito, né? Eh,
imagina que eh quando eu falo de uma
venda, por exemplo, num contexto de
venda, eh
uma única venda, ela é um dado, né? A
partir do momento que eu tenho
uma tabela, eu já tenho ali eh pelo
menos duas dimensões, né? Eu posso ter a
venda e a data, por exemplo. Tenho a
quantidade de vendas que eu fiz ali em
cada data. Eu tenho uma tabela. Quando a
gente fala de cubo, eu tô falando de
três ou mais dimensões. Então, assim,
além de ter a venda, a data, eu posso
ter
eh a região, o cliente, o produto, eh
diversas outras dimensões que explicam
aquela venda, né, que são eh caminhos
diferentes, né? Se você pega a data, por
exemplo, você tem ali o dia, o mês, o
trimestre, o ano, a semana, a hora, né?
Se você pega
a parte regional, por exemplo, eu tenho
o ponto da venda, eu tenho a cidade, o
bairro, o estado, país, né? Eu posso
ter, por exemplo, a moeda que foi
vendida, eh, posso ter uma dimensão,
eh, produto, agrupamentos de produtos,
segmento, categoria, né, eh, eh,
eh, ramo de atividade, talvez, porque
não, né?
Eh, então assim, sempre que eu tiver
falando de cubo, eu tô falando eh de um
conceito que ele é um pouco mais
complicado do que uma tabela única, né?
Ele precisa ter mais do que duas
dimensões
para você conseguir
ter todas e esse tipo de informação, né?
E aí por isso que três dimensões a gente
chega no cubo, né? Existem várias
maneiras diferentes de se organizar um
cubo, tá? Ele pode ser extremamente
transacional, como a gente tem nesse
exemplo aqui da esquerda, né? A gente
tem
aqui algo transacional em que cada
caixinha dessa daqui ela é uma
transação, é uma venda, né? Então, cada
caixinha dessa daqui, ela tem um,
ela tem um, um uma data, uma região, um
cliente, um produto, uma rota, um uma
hora, né? Tem várias eh tem a sua
descrição
do dado em si da forma mais granular,
né? Você tem uma outra abordagem que
pode ser mais agrupada também, né?
Quando a gente olha aqui o desenho da
direita aqui, eh, o meu dado, o esses
quadrinhos em branco aqui, eles podem
até ser mais eh
mais transacionais ou não, né? Mas o o
mais importante aqui são esses mais
escuros e coloridos, porque eles são
agrupamentos, né? Eles são
aqui na na parte do produto, por
exemplo, eu tenho aqui eh mobile, AC, TV
e são. Então eu tenho o total de todos
os produtos armazenados na mesma tabela,
né, ou no mesmo cubo, no caso aqui, né,
eh, o a data ali também eu tenho
primeiro q, segundo q, terceiro q,
quarto q, ano inteiro, né, o país, eu
tenho aqui, ó, Índia, Estados Unidos,
acho que é França aqui e mundo inteiro.
E aí eu tenho ainda uma coluna aqui que
é todas as datas, todos os produtos,
todos os países, né? Então, então assim,
esse cara aqui ele já tem o é como se
você tivesse uma tabela ali com
subtotais, por exemplo, né? Isso daqui
facilita bastante na hora de você ter
resultados mais rápidos, tá? Eh, se
você, eu sempre vou consultar o total
por país, por exemplo, faz sentido eu
armazenar o total na minha tabela. ou no
meu cubo, né? Cada ferramenta vai ter o
seu estilo, tá? O Power BI trabalha
muito bem com as duas aqui,
mas o o Power BI ele vem
de uma de uma base bastante robusta,
multidimensional,
né? Então ali quando a gente fala lá de
2010, mais ou menos, 2012,
eh
a Microsoft trabalhava muito com modelos
multidimensionais,
né, que eram cubos bem robustos, né, e
mas aí com um tempo o Power BI foi se
atualizando, atualizando, ele passou por
isso daqui, hoje ele tem um modelo bem
mais flexível. ív, né? Você consegue ter
granularidades diferentes até eh níveis
de agrupamentos diferente, né? Então
você consegue
eh ele não é mais essa estrutura sólida
aqui do cubo, né? Isso aqui é mais um
conceito pra gente entender de onde que
tá vindo, né? Mas hoje ele tem um um
desenho que nem dá para mostrar o
desenho aqui, né? Eh, você consegue ter
granularidades bem diferentes, né? e
você consegue ver o mesmo dado eh em
diversas
dimensões diferentes, né?
Eh,
então, eh, hoje ele se assemelha muito
ali quando você for tentar criar essa
essa visualização aqui. É, é legal você
ter essa ideia, né, da visualização do
cubo na cabeça, né, na hora que você for
montar o o desenho ali da modelagem ali
no Power BI, né, mas vai ver que ele vai
se assemelhar muito mais a um modelo
tabular, né, que é conectado ali, eh, a
as tabelas são armazenadas de forma
separada e elas estão conectadas e essa
conexão também é armazenada de uma forma
separada, né? Eh,
mas assim, para passar um conceito
geral, o cubo, eh, eu diria que ele é
uma forma inteligente de se armazenar
blocos
para uma consulta otimizada.
Ou seja, o que que isso quer dizer? Eh,
eu vou pegar todos os dados da minha
empresa. Isso pensando em um um cenário
utópico aqui, né? num cenário real, eu
não não vou concentrar todos os dados da
empresa num cupo, né? Mas num conceito
utópico, você pega todos os dados da
empresa e organiza eles da melhor forma
para que ao mesmo tempo ocupe o menor
espaço possível e tenha a leitura mais
rápida possível, né? Então eu eu preciso
ocupar o menor espaço possível porque eu
tenho custo de armazenamento e eu
preciso entregar o mais rápido possível
porque eh eu tenho a questão da
performance e do da experiência do
usuário, né? Se você fizer uma consulta
no se você tiver carregando um visual no
Power BI, ele demorar 2 horas para
abrir, ninguém vai usar o PowerBI, né? E
tem que ser sempre, sempre mais rápido,
mais rápido, mais rápido, sempre. É, é
uma premissa dele, né? E sempre
armazenando
eh cada vez menos espaço, menos espaço,
menos processamento. Quanto menos dado
trafegar de um dado pro outro, sempre
mais barato vai ser, né? Então o
conceito dele é
bastante em cima disso, tá? Então, só
para recapitular, a ideia disso aqui do
cubo é como que eu armazeno os dados de
uma maneira inteligente para ocupar o
menor espaço possível e responder do
jeito mais rápido possível, os dois ao
mesmo tempo, sem um excluir o outro, né?
Então esse aqui é o nosso conceito de
cubo, tá bom? Ele vai ser bem importante
na hora que a gente tiver fazendo o
desenho do nosso modelo de dados ali das
quando a gente tiver eh colocando as
tabelas para dentro do nosso modelo, do
nosso estudo de caso.