# Vídeo00-Hand´s On-Conhecendo a base de dados do ENADE(Exame Nacional de Desempenho de Estudantes)

- **URL:** https://www.youtube.com/watch?v=OxVpeyHyMMM
- **ID:** OxVpeyHyMMM

## Transcrição

fala galera tudo com vocês estamos aqui
pra mais uma nova aula
dessa vez a gente vai estar fazendo
agora um revisão tatu que a gente
aprendeu até o momento estatística
descritiva a gente vai estar aplicando
aqui tá só que a gente vai estar
evoluindo ainda aprendendo um pouco mais
porque a gente vai adentrar na não nos
pacote base do ar então a gente vai
adentrar nos pacotes que são da ótica
thai de vacina é que são os melhores
pacotes que a gente tem no momento está
desenvolvida pelo maior parte deles pelo
rádio week a beleza e aí a gente tem de
boyle está com o estado da arte de
manipulação de dados a gente vai
aprender isso a gente vai aprender como
é que importa o arquivo do enade
e aí você consegue estender isso para
outros tipos de arquivo também tá é
bastante simples a gente vai entender a
estrutura e aí vocês vão conseguir
aplicar para outros tipos
então primeiramente aqui a gente está no
site do inep está inep.gov.br microdados
estava a ensinar pra vocês como é que se
fazem para baixar de base que a gente
vai trabalhar a gente tem aqui os
microdados tá do inep
e aí vem aqui o censo da educação
superior senso profissional a distância
escolar
o enade tem em seja nem tá tem muito
dado legal aqui para vocês trabalharem
tá
a gente vai trabalhar hoje com o enade
tá então entra aqui em nad ali já puxa
que o 2004 a 2007 está que foram os anos
que foram realizados no enade no brasil
thá e o que venha a ser o enade né
o enade ele é o exame nacional de
desempenho dos estudantes está ele
avalia o rendimento dos concluintes dos
cursos de graduação em relação aos
conteúdos programáticos suas habilidades
e competências adquiridas na formação
que a pessoa fez já então ele é um exame
que avalia os cursos de nível superior
tá ele é obrigatório é a situação
regularidade
dantes no exame deve constar em seu
histórico escolar
beleza a primeira aplicação do enade
ocorreu em 2004 ea periodicidade máxima
de avaliação entre nao ta de três em
três anos
beleza e objetivo avaliar o desempenho
dos estudantes em relação aos conteúdos
programáticos como a gente já falou está
previsto na nas diretrizes dos cursos
beleza então a gente vai vai estar
estudando é que como é que a gente
importa essa base nem vai conhecer um
pouco mais dessa base da primeira coisa
que é baixar a base como eu faço para
baixar né
a gente vem aqui em 2017 a gente já
trabalha com os dados de 2007
clique aqui em baixar ele vai demorar um
pouquinho porque ele é grande está o a
base do nada ela tem mais de 537 mil
linhas tá então uma base grande tá então
vou parar aqui o download
mas se você eu vou mostrar os arquivos
para vocês quando você baixar se
acontecer isso aqui ó botar aqui que
vocês vão ter como vocês baixarem se vão
ter essas três pastas aqui vai ter um
consolidado aqui um e rapta e aí você
vai ter um leve impulso de idade está
aqui no no leme
a gente vai ter o dicionário das
variáveis está ele vem tanto em open
office como também no excel tem aqui o
manual do usuário que vai falar o que
tenho nos arquivos está e tudo mais
o questionário do estudante de
licenciatura isso aqui são só para os
cursos de licenciatura tasso não são
perguntas específicas e aqui tem o
estilo eo questionário de estudantes que
eles respondem pra gente montar essa
base de dados
tá então eu separei aqui na janela
a gente vai abrir aqui o questionário do
estudante ele está aqui já o
questionário do estudante 2017 está ok
esse questionário possui constitui um
instrumento importante para compor o
perfil sócio econômico e acadêmico de
participantes do enade e uma
oportunidade para avaliá-los
diversos aspectos da formação tá beleza
e aí ó primeira variável que qual estado
civil não é só ter casado separado eo
qual é a sua cor ou raça né branca
amarela má para o indígena não quero
declarar um aspecto importante aqui é
que essas variáveis aqui não viu
bonitinha no banco está porque porque
isso aqui é ocupam muito espaço de
armazenamento está então é muito melhor
você botar cão solteiro é um casado há
dois anos separada 3 que o número ocupa
muito menos espaço do que no stream itá
então um conjunto aqui diz trindade
beleza então a gente vai ter sempre os
números nem aí a gente vai ter que
traduzir isso para poder fazer uma
análise descritiva né porque pô não a
gente não pega aqui a variável estado
civil e vem 12 3 por mais que é um que
quer 2003 né
então vou ter que em algum momento
traduziu um para o seu terceiro o 2 por
casado ea gente vai aprender como é que
a gente faz isso tá pra poder analisar o
dado é transformar as variáveis tá então
a qual só cor ou raça com nacionalidade
então aqui vocês vão ter todas as
variáveis possíveis de serem trabalhadas
com a base de henna digitar a gente vai
trabalhar com algumas não todas
vou fechar aqui minimizar a beleza que
mais vocês precisam todo o banco de
dados e precisa ter um dicionário tá que
vai te dizer a posição da variável do
tipo de variável que ela é tá aqui ó
aqui é o dicionário de variáveis
microdados enade edição de 2017 tá tem
aqui o número da variável o nome no ano
como vai aparecer no banco exatamente
está por isso que é um dicionário está
explicando que ao banco tá tipo numérica
a item categórica né
se for se fosse 30 e tudo mais
tamanho é o tamanho que ocupa no banco
naquela
é quantidade de caracteres que cada
variável ocupa no banco
a descrição ano de realização do exame a
uma breve descrição desenhar na beleza
ensino ano que é o ano de realização do
exame e o que está lá dentro da variável
que está lá dentro da variável é 2017
porque é um ano de 2010 site ta goiás é
o que código da instituição de ensino
superior
tá ele varia de um a menos 19 mil 739 tá
e ele a identificação das instituições
de ensino superior conforme o mec
tá e aí aqui é uma descrição do que
estava no banco nem por exemplo a gente
viu lá o solteiro casa nem vai ter
número aqui né por exemplo aqui aí ó não
vai ser centro federal de educação
tecnológica que vai aparecendo no banco
porque isso ocupa muito espaço então
eles colocam o número 10 0 19 essa
qualificação é centro federal de
educação tecnológica
10 01 20 centro universitário essa
quantificação ela vai estar lá no banco
beleza então assim por diante então a
gente precisa conhecer um pouco do banco
para poder trabalhar variável está então
é desejável que todo o banco de dados
vem é junto com dicionário tá pra poder
te dizer o que é o banco beleza legal
então esse aqui tá bonitinho e ele outro
arquivo que vai vir quando você baixar
só assim putnam ele daqui os impulsos
pra você pronto já do é do site e do
spss você pode trabalhar com o que ele
já traz pra você tá e aqui vem os dados
né microdados cenário em 2017
tá aqui eu já abri se você clicar aqui e
vai demorar um pouquinho que tem 500
mais de 537 mil linha está dependendo da
velocidade de seu computador vai demorar
um pouco
eu já estava aberta aqui então eu posso
mostrar tá aqui ó
como é o formato dele a separação dele a
ponto e vírgula também no ano e você
repara que a gente tem aqui ó
o nome das variáveis é um nome já feio
feio né a gente não tratou ele ele está
como veio exatamente no dicionário
tá e aí eu quero que isso vire o
cabeçalho então quando a gente foi
importar pr por exemplo a gente vai
dizer que o cabeçalho existe ou seja r
head né de cabeçário e god oh tá então a
gente vai ver isso dentro do r b leza
então dito isso eu coloquei aqui no avaí
pra vocês
já há algumas variáveis que a gente pode
vir a trabalhar tá aqui ó catega de
código da categoria administrativa daí a
10 da área do curso não é que é o tipo
do curso arquitetura urbanismo
tecnologia em análise e desenvolvimento
de sistemas ads né gestão de produção
industrial rede de computadores
matemática licenciatura bacharelado e
assim por diante né
a iacc a região não do curso
aí se fuma norte do nordeste a gente
precisa saber isso tudo depois que a
gente vai traduzir num vai virar norte
dois no nordeste e assim por diante
tá anuidade é a idade do inscrito tá no
na data do exame
varia de 10 a 95 tá aí aqui tipo de sexo
masculino feminino da graduação latino
expertinho integral noturno é que venha
um dois três quatro e assim por diante
já então aqui a gente conhecer um pouco
mais do nosso banco para poder trabalhar
tá e no próximo vídeo a gente vai está
começando aqui a trabalhar com uns
pacote está agora não mais
a gente vai trabalhar tanto com os da
base da argentina vai trabalhar aqui com
os da base mas a gente vai usar mais
aqui
a ótica dos pacotes melhores do rk mais
otimizado né que são da ótica tarde
willians beleza e isso inclui o world
player
o gg totti o próprio lhe então o reader
né então tem vários pacotes
a gente vai vai trabalhar beleza então
pode abraçar pra vocês e até a próxima