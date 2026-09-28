# Alteryx - Join - Aula 14

- **URL:** https://www.youtube.com/watch?v=xQCjNNnBjCs
- **ID:** xQCjNNnBjCs

## Transcrição

e agora a gente vai falar da ferramenta
de Johnny também uma ferramenta que se
usa demais para você conseguir juntar
dados de duas tabelas diferente também
existe a versão que você dry multiple
que essa aqui em que você consegue
juntar diversas bases ao mesmo tempo
taça uma ferramenta que ele tem um
pouquinho mais cuidado que a gente vai
falar de ônibus ou só duas bases que
vocês junta tá então quê que a gente vai
fazer aqui eu vou arrastar sua
ferramenta de olho em você vai ver que
ela tem uma entrada Leste metade da
entrada White E aí você vai entrar com
uma base de dados em cada uma dessas
cada uma dessas entradas dela eu vou
pegar aqui a entrada do Thai ou que a
gente teve da aula Thai ou em que a
gente tem essa base aqui e vou entrar
aqui na leste
eu vou colocar também a minha entrada na
minha entrada Hit agora aula anterior
que a aula de fórmula e que eu vou ligar
aqui para minha saída para mim entrar
drive e aqui dentro da minha ferramenta
de Johnny o que eu vou fazer é falar
para ele qual é a chave que vai servir
para conectar as duas tá ou seja qual é
o campo que existe em comum entre as
duas tabelas para que eu consiga juntar
as duas tá então eu consigo falar para
ele que colocam para minha tabela na
esquerda E depois Qual o correspondente
na minha tabela da direita Então posso
pegar aqui por exemplo Generation e veja
que Como existe já uma coluna com o
mesmo nome Generation na minha tabela da
direita ele já até coloca
automaticamente se por algum motivo não
for correta você pode alterar aqui mas
você é ele já tenta te indicar qual é a
provável de ser correta
o
é só que olha que legal diferente de
outros remete a uma coisa para Excel que
muita gente vai lá e faz o vê-lo Cap e
que inclusive confundem muito essa
ferramenta desenvolvê-lo Cap que eu peço
atenção porque não é a mesma coisa já
vou mostrar porque então assim é com uma
coisa boa é a mais em relação ao vê-lo
carb por exemplo aqui É que geralmente
quando vai fazer um colocar você vai ser
não tem um campo que já é uma chave
única para você você precisa Construir
aquela chave única de alguma forma faz
um concatenation ali de alguns Campos e
constrói a sua chave no joinha e você
não precisa disso do dia Olha você
consegue depois que você já falou um dos
Campos você consegue beleza OK esse
campo é um dos que serve Mas além disso
eu preciso que outros Campos estão bem
sejam iguais então além do Generation eu
posso falar que nessa linha de baixo um
outro campo eu vou pegar por
o n2 eu vou falar para que ele pegue em
relação a name da minha tabela da
direita agora o que eu tô dizendo para
ele para o joinha aqui é que só as
linhas entre os Generation do meu Leste
foi igual Generation da direita e além
disso o meu baby 2 seja igual ao name da
direita só nessa situação em que ele vai
juntar as duas favelas se não for igual
dos dois não foram iguais ao mesmo tempo
ele não vai juntar
e outra coisa importante é você reparar
que aqui embaixo ele tá colocando para
você como se fosse uma ferramenta de
select a que você consegue fazer a
escolha de quais Campos que vão estar na
sua saída e você consegue também mudar
nome você consegue aqui mudar deitar
Type você consegue fazer algumas coisas
e aqui a gente vai mexer apenas
retirando a Generation e vamos retirar
também aqui a name para que a gente não
precisa ter isso aqui que aí a gente vai
ficar só com a Zeli eu vou tirar um não
que significa também que é qualquer
Campo Novo que entre ele já vai deixar
desmarcado Ou seja já não vai entrar na
já não vai sair dessa ferramenta quando
você se scalco novo entrar na ferramenta
tá outra coisa legal de se reparar é que
ele já te deixa uma colinha aqui caso
você não entenda de união de de junção
de tabelas o que que é um leque que é um
High Kick Winner Joy tá outra coisa
interessante também além de você juntar
a através de Chaves né como você vê aqui
no Jereissati também você também pode
juntar pela posição então ele não vai
ligar para chave
é simplesmente pegar o o a primeira
linha de um ele vai juntar com a
primeira dia do outro segunda linha vai
estar com segunda linha e aí ele já vai
juntar Independente de chave isso
funciona quando você tá juntando dados
aí que você sabe que a posição já já é
uma já uma algo relevante já um
definidor para você a junção existem
esses casos tá nesse Então mas nesse
caso aqui a gente vai usar essa chave
aqui e vamos deixar só esses campos na
saída
eu vou dar um lá
bom então na minha saída eu vou ter aqui
no na minha saída J todos os campos que
foram é em que tiveram essa chave no
como um todo a gente tiver essa chave
comum o que for da minha entrada da
esquerda que não teve nada em comum com
a direita vai sair aqui nesse nessa
saída aérea e tudo que tinha na minha
direita que não tinha nada em relação
nada relacionado à esquerda e vai sair
aqui na minha saída R tá E aí que vai
entrar a questão que eu quero que vocês
se atentem
e não necessariamente essas três saídas
vão somar quantos dados você entrou na
no seu joia porque porque isso aqui não
é um meu WhatsApp para você entender um
pouco melhor é isso aqui que acontece
são duas tochas a gente pode ver aqui
primeiro caso se você tenha só fonte ar
Chaves únicas em relação a essa fonte b
o que vai acontecer a uma saída certinha
realmente vai fazer ele como se fosse um
vê-lo caído Então o que era da minha
chave x ele achou com a chave de X aqui
itally juntou o arco você e ficou
certinho mesma coisa que eu já vi Y B
com de você teve aqui na saída o beijo
dele mas se você tem em uma dessas bases
mais de uma linha que se relacione com a
outra base você vai ter um problema se
você ficar aí pensando que é um ver
locado tá então se você tem aqui uma na
base na fonte aqui uma chave
Ah e você tem mais de uma ocorrência
dessa chave x na sua fonte b o que vai
acontecer é que na sua saída ele vai
pegar a fonte a e vai repetir essa fonte
a por tantas vezes conto ele é chá é
Chaves iguais nessa fonte bebê então se
eu tenho duas ocorrências da chave x
aqui na minha fonte b que vai acontecer
é que ele vai pegar essa essa chave a
essa chave x na minha fonte ar e vai
repetir duas vezes uma vez para cada
ocorrência que ele encontrou na minha
frente B E aí o que vai acontecer que
você vai ter gerado mais linhas na sua
saída do que você tinha lá na sua
entrada onde você tava achando que ia
fazer um velocar então fica tendo com
até por isso é outra ferramenta que essa
assim é igual a um vê-lo cabe é a sagge
é um Place é outra ferramenta a joy em
algum
que serve para fazer isso mas sempre
toma cuidado aí então sempre presta
atenção no que está saindo aqui nos
dados para você ter certeza que tá
saindo realmente a relação que você
precisa