# As 3 Etapas Para um Bi Perfeito - Parte 3 - Prof. Grimaldo

- **URL:** https://www.youtube.com/watch?v=NzvL__kBsic
- **ID:** NzvL__kBsic

## Transcrição

terry pode ser em qualquer tipo de dado
como eu falei em planilhas em banco de
dados e arquivos de log arquivos de
texto mas você tem que fazer essa
importação mãe não importa onde esteja
após feita a importação você vai criar
tabelas periféricas também os auxiliares
as tabelas da área fria e chamadas
também elas estejam em área
depois que você cria as tabelas
estagiária
você cria tabela dimensão a gente está
falando em tabelas não tá falando em
mais nada não estou falando aqui no
processo de tl que é daqui a pouco vai
importar os dados você vai trazer isso
para estudar engenharia e vai trazer
três dimensões
depois você vai criar a carga dessa
estagiária depois que você já viu as
tabelas estão fazendo sefaz a carga que
vai trazer os dados da área da empresa
para dentro do tatame house então se
cria uma capa que chama de carga esteja
depois e vai querer a carga que chama de
dimensões ou seja eu já tenho as tabelas
construídas eu comece a construir as
cargas passa um processo de carga é um
processo dentro do banco de dados você
extrai dos arquivos operacionais para
dentro do natal
depois que você já tem três de cágado a
dimensão carregada
você cria tabela da faca ou seja pela
tabela de métricas
você só cria a tabela um a tabela criada
você cria a carga da fato de você
consegue completar todo o ciclo enquanto
o sonho do animal
o isso aqui construí dos dados já estão
inseridos
o banco é centralizado e os dois começam
a consumir as informações
então este é todo o processo que você
precisa saber compreender da conjunção
de nota realça
mas existem minutos existem etapas antes
que isso possa ser feito seja um sucesso
como é que eu atingir essa meta com
sucesso
bem uma coisa é levantar os dados que
vão interessar construção até legal pra
isso você tem que fazer uma interação
com gestores
existem diversas formas
uma das mais comuns é que você vai
encontrar na literatura fazendo
entrevistas você entrevistamos gestores
para que eles possam dizer o que eles
desejam encontrar no data em house
possivelmente retirar informações no
processo de enviar bem pra fazer isso
desenvolveu uma técnica que hoje é
largamente utilizada nos meus projetos é
a técnica de matriz de necessidades é um
documento que é criado onde eu sento com
gestor e aí pergunto a ele que você quer
ver no projeto me inscrever todas as
informações que você quer trabalhar
tanto métricas como descritivas
então eu monto um diagrama esse diagrama
é feito em uma planilha eletrônica e ela
serve para que eu possa descrever todos
os escritores e as métricas do negócio
do gestor e aí eu vou perguntando essa
métrica se liga ao escritor de negócio
se sim o marco x nessa informação o dom
sinal no finalzinho de hockey e faça
referência ao gestor no final eu vejo
todas as informações que se cruzam
fica bem simples bem fácil de você terá
jeito o formato é mais ou menos esse eu
descrevo aqui a minha faca ou seja minha
tabela que vai aguardar as métricas e
todos os dois escritores que eu vou
trabalhar e aqui eu venho marcando
então eu sei que no meu exemplo aqui
os dados sobre as diárias de um hotel
vão cruzar com as informações do
hospital o tipo do quarto da clássico e
quando ele entrou no hotel seja vou
guardar informações de ano mês cimércio
bimestre
eu necessito ensino e aqui eu digo é
necessário guardar histórico dessas
informações
ou seja se você quer saber quando ele
veio se hospedar na cidade de são paulo
por exemplo e agora ele mora em salvador
quando ele veio quando morava em são
paulo agora quando ele mora em salvador
então você marcar essa informação com
histórico e um data warehouse e vai
fazer esse controle
ok
toco então você pode construir a matriz
de necessidade uma vez levantado toda
essa matriz e hoje estou identificando
aquilo que ele quer de no projeto
você vai ter que partir com a parte
operacional da empresa ou seja aqui no
caso do hotel e lá falar com o bebê
álcool na mistura do sistema onde a
questão esses campos dentro das bases de
dados
e aí você vai precisar construir um
outro documento é um documento chamado
fonte de dados
na verdade ele levanta identifica tudo
que é necessário que foi levantado na
matriz das cidades que existe hoje nas
bases transacionais da organização a
gente descreve isso de formas
diferenciadas os descritores em seus
relacionamentos você descreve um modelo
específico só para escritores ea partir
de metas que são os indicadores nos eua
escreve um outro modelo mas é bem
simples eu vou explicar como funciona
ok você vai mapear todo o relacionamento
que existem entre as chaves primárias e
as chaves estrangeiros esse mapeamento é
necessário porque na construção do hotel
vai precisar disso as cargas de tani ok
interessante é que você vai conseguir
com esse documento a avaliar quantos dos
escritores e quantas métricas você terá
no seu dw e vai ficar mais fácil uma
coisa bastante interessante lá na matriz
o gestor pode pedir alguma informação
que não existia nas bases
então é uma forma também de documentar a
não existência de um determinado tributo
que pode ser implementado futuramente
vou colocar um exemplo aqui das fontes
de dados no caso das dimensões
exatamente como estava na matriz not eu
vou lá na base de dados dentro das
tabelas e captura dos campos
caso tenha algum relacionamento para ser
feito e coloco na aba relacionamento
aqui no caso de hóspede
a cidade está em outra tabela então eu
faço essa junção e vai identificando o
caso do país também assim sucessivamente
ok são padrões e só precisa fazer um
link entre a data que eu coloquei lá que
vai ser utilizada para capturar os dados
ea tabela de tempos com uma tabela que
você constrói e ela é construída
uma vez só uma vez de uma única vez
você faz um modelo com as dimensões que
você cria um modelo para fato a fato
como a gente já sabe a gente vem falando
aqui no vídeo são os campos que contém
as métricas tudo que estava lá
determinada paz e métrica eu vou lá
dentro das tabelas que que vai ser
campeã da tabela que vai ser candidatas
é fato
identifico ela criou aqui as junções das
dimensões pelas chaves artificiais
lembra games lá no nosso modelo multi
dimensional
então eu coloco aqui a chávez que vou
utilizar ou seja esse mesmo modelo ele
tem quatro dimensões e 3 métricas e
coloca também o relacionamento entre
elas entre a dimensão ea tabela que
contém os dados na foto
então eu faço essa construção eu acelero
drasticamente o meu projeto de bi à ok
por fim eu tenho na verdade três
documentos super importantes que a
construção da matriz necessidades
a construção da fonte de dados nacional
este é o principal e você precisa
conhecer o projeto possa ser iniciado
nos próximos vídeos
a gente vai fazer um exemplo do hotel
destacando aquilo que foi levantado
pelos gestores
então vou simular uma entrevista que ser
feita com gestores e vou destacar tudo
que desejo a gente vai construir esse
documento passo a passo a futilidade da
mesma coisa
vamos abrir um modelo de dados da
empresa e vamos construir passa passa o
relacionamento daquilo que foi
determinado pela matriz e por fim vamos
utilizar uma ferramenta case para
construir um modelo multi dimensional ok
espero que você tenha gostado do vídeo é
esse vídeo que dá origem a mais três
vídeos é uma série de vídeos e caso você
tem interesse é só escrever pra gente
aqui está o nosso contato você escreve
e eu lhe respondo
quem um grande abraço espero que você
tenha gosto