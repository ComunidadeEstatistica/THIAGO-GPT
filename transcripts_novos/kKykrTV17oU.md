# Tratamento de dados no R para elaboração de Dashboard em PBI do Censo Escolar - Marco Milanez

- **URL:** https://www.youtube.com/watch?v=kKykrTV17oU
- **ID:** kKykrTV17oU

## Transcrição

é bom pessoal eu chamo marco antônio né
mas o que eu só não conhece mais uma
máquina mês já fui aluno do tiago que eu
te ligando para te dados olha eu aprendi
maior parte do conteúdo mr que hoje eu
vim tesouro cada vez mais no meu
trabalho que eu vou mostrar para vocês
nesse vídeo aqui no trabalho em cima de
microdados do censo escolar 2018 mais
específico aqui com a base das escolas
hoje eu vou mostrar para vocês o
processo aqui de exportação
transformação e depois que
posteriormente como que salve certo já
trabalhado no meu diretório bom
e para iniciar a gente vai precisar quem
carregar esse arquivo me cold que ele
foi salvo que foi o utf-8 então vem aqui
em fail
e riu kiu em coaching é isso selecione
utf-8 aí ele vai abrir os arquivos da
maneira correta sem aqueles erros mas
nomenclaturas aqui bom depois disso só
vem utilização quieto w dele para
verificar o diretório
e lembrando que aqui essa parte é
importante porque o a base que você vai
trabalhar precisa tá nesse momento
diretório caso não esteja você pode
utilizar essa função 7w de definida que
o dia da torta depois disso a gente vai
precisar utilizar quatro pacotes odiar
data ponto table multiplay ar em e o
open xlsx in
e como eu já instalei esse pacote tipo
nem carregar aqui só a sua biblioteca né
é
é feito isso ele já estão prontos para
utilização o essa é a primeira posição
que eu vi de ar eu vou usar para salvar
o arquivo sub-7 que foi trabalhar daqui
a pouco tempo eu vou usar a função f it
que emoção que tem que fazer importação
unidade de maneira rápida do de playa
que eu vou usar para transformar uma
base né fazer toda aquela mudança parte
mais grossa do de transformação dos
dados e o open xls x para carregar um
arquivo que está em xls
e aí para fazer as junção de duas de
dois arquivos aqui bom depois disso eu
venho e carrego aqui com data set que eu
quero trabalhar se alguma escola de
pontos sv usando a função f week mas
para isso de no mínimo
é um nome né pressa
a pressa básica do carregar dá um rango
aqui
oi e ela já carregou aqui embaixo
o centro do scooby-doo
é bom para verificar se está tudo ok vou
dar um viu né antes de hospedar lá
ah e não dá uma olhadinha aqui para ver
se tá tudo ok
e a princípio tudo aqui
e para dar multa conferida a gente pode
usar a função mendes
em 98 na tv todos
e as colunas que tem a ver se dá certo
pessoal agora que
e a gente carregou a base
o que que a gente vai fazer agora você
vai selecionar somente aquelas colunas
da base que a gente tem interesse então
aqui eu fiz algum coloquei algumas
colunas que eu tenho interesse
e ir através da função de praiar eu vou
selecionar apenas essas colunas e vou
colocar um sub 7 e cola dono de nome
nesse subir escolas
bom então rodar
e depois a gente vai dar um monte
e se vira agora que o o subject só tá
com um as colunas que eu selecionei
através da função de pra cá
o futebol
eu vou fazer um vou usar a função dinho
para ver afastar de mim né quando sair
de colunas eles têm total de 386 e 14
linhas e 51 colunas
e aí
o prefeito de segurança costume salvar
nesse subset um diretório para casa
depois eu queria fazer uma transformação
depois disso eu quero selecionar
e entrou em
e aí
eu quero selecionar
e somente
é o que diz respeito ao rio de janeiro
ao estado do rio de janeiro
bom então aqui eu te fiz o filtro
e esse filtro te iluminando e que eu
quero só
o código 33
o que traz a informação e somente do
estado do rio de janeiro
ah então não vou dar aqui
e depois vou dar um ver o resto para
verificar se realmente fui selecionado
somente
é o que diz respeito ao rio de janeiro
saber que já temos aqui né somente está
desligando
e a poesia isso eu vou precisar carregar
uma outra tabela que me traz ainda
informações com código município marco e
macrorregião
é porque eu estou carregando essa essa
outra tabela aqui porque no nosso suco
nosso bisset que é convidado das escolas
e eu não tenho eu não gostar eu não
quero trabalhar na verdade com esses
códigos eu quero eu quero saber qual
município é qual
nós podemos diretamente identificando
atravessando a minha fatura
bom então o que que eu vou fazer com
isso é como se eu tivesse usando o
próprio z
é é é
o aspecto usando para que vem no excel
que eu vou fazer com base em
e deixa eu carregar aqui academia a
e a tabela primeiro eu vou verificar
para ver se tá certinho tá certinho
e o que que eu quero fazer ou se fosse
um próprio meio quando estava falando
através do código
e no nosso substrato de escolas
e eu faço um próprio ver utilizando essa
mesma coluna e trazendo os jogos o nome
do município e o nome da mata região
questão de informações que eu quero
desta tabela então eu vou utilizar um
left join da base sub escolas
é através
e selecionando
e essas informações que eu quero
o meu
é feito isso
e eu
se transforma
e eu digo né na verdade que o código
município é igual o código de bcaa 1
bom então através dessa forma aqui ó
e eu faço como se fosse um próprio dele
eu já consigo fazer os nomes dos
municípios nome na macrorregião sem não
tem que fazer mal à mão digitando o
código código
e depois disso eu vou dar vou utilizar a
função names
e no final do filtro que eu fiz para
verificar assim deu certo
tô precisando de uma chuva que eu também
não rodei né eu vou dar aqui ó
eu mandei
e agora vou usar a função nenhum isso
como vocês podem ver aqui embaixo
o que já tá trazendo as informações dos
municípios e macrorregião e o daqui
também um head on
tu quer ir para vocês podem ver aqui
municípios trouxe os nomes e a
macrorregião também todos os homens e
e depois disso eu vou renomear essas
duas colunas a primeira município no
simples e máquina região
bom então eu vou fazer essa mudança aqui
tirando do assunto de municípios
g1
e aí
e tirando o tio de região
o doutor ponto feita essa mudança de
leite prossegue para transformação de
dados
e aqui pessoal tem um ponto importante
também toda vez que você a trabalhar com
microdados geralmente se tenho
dicionário de identidade por exemplo
aqui como vocês podem ver nessa fórmula
é um todo registro um
nós vamos bater aqui para vocês
em todo o registro um tp dependência
significa que a escola é federal todas
registro dos significa escola estadual e
assim vai dar um assunto toda a coluna
ela vai estar algumas colunas na verdade
não tá em número
bom então você precisa desse dicionário
para você conseguir converter isso
nomenclatura correta da informação do
dado a
bom então aqui a gente vai fazer a
transformação a gente vai selecionar
e a coluna dependência e transformar
e nada musculatura correta né o que é um
vai ser federal o que há dois você
estadual que há três vai ser municipal e
assim vai lá
ah tá bom daqui
é a mesma coisa vou fazer para categoria
da escola privada
eu tô trazendo stg2 esse servidor de
casas aqui só como exemplo
e é mais certamente você poderá fazer
isso em outras colunas nas formulações
químicas consideradas informações que
você vai utilizar no trabalho
e depois de transformar os dados eu vou
dar um seu ret
é para ver se a mudança foi feita o que
vocês podem ver
o que foi transformado tp dependentes em
privado
g1
e aí agora vou dar um
o mizuno aqui
dá para ver se
se está tudo de acordo com ele é
e a gente quer né
é ele que dependência que ia tá trazendo
na nomenclatura certinha
bom então vamos aqui para conferir
a e trazer o dimensão
e esse amor é o resumo das informações
com base nas transformações que a gente
fez então agora a gente tem total de 16
o 1101 101 ninhos e 53 pulmões feito
toda essa transformação das informações
exemplos que o quis trazer para o meu
sub-7 eu vou salvar através da função
dry dissesse viu não demais não sei se
ver
e eu vou salvar ele kombinet escolas
2018 com cécile o
um copo com esse arquivo lula trabalhar
transformado trabalha aqui que a gente
eu não disse isso a gente pode utilizar
esse arquivo
e ir começar a montar uma coisa mais bem
elaborada de visualmente através do fora
de área
o e através do foi velho você também
pode utilizar o hélio
e mais particularmente para esse
trabalho eu usei o r-studio salvei a
pode transformar o arquivo eu salvei ele
no diretório e depois eu carreguei no
barbear já transformados e não tão
pesado quanto o arquivo original o que
facilitou o trabalho da montagem dos de
xbox no por viagem então eu vou abrir
para vocês aqui vou enviar e pra vocês
verem como que ficou o trabalho
lembrando aqui aqui eu não não soltar a
base as escolas mas também traz
informações e matrículas e dos
professores
e o pessoal que eu queria mostrar isso
se for uma coisa muito rápida mas
a mulher era só passar mesmo que pode
ser feita através do enem para facilitar
o trabalho dentro do pop ar e o olho ou
em outra ferramenta de visualização e
espero que vocês tenham gostado aí
e essa espanaçao básica e meu muito
obrigado pessoal e até a próxima