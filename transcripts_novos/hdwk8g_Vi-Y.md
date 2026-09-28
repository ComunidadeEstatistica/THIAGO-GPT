# Aula 4 - Ler Arquivos e Data Frames - Curso de R para Finanças Quantitativas

- **URL:** https://www.youtube.com/watch?v=hdwk8g_Vi-Y
- **ID:** hdwk8g_Vi-Y

## Transcrição

[Música]
bem-vindos novamente aqui aos poucos e
marketing e hoje nós temos a aula número
quatro do curso de r para finanças
quantitativas
meu nome é leandro guerra se você ainda
não está escrito no canal já se inscreve
agora deu lhe que faça todo aquele
ritual do youtube você ajuda aos poucos
e marketing eu posso trazer cada vez
mais conteúdo mais acesso pra mais gente
só para vocês entenderem como como eu
estou planejando um pouco a dinâmica
agora dos vídeos no canal todas terças e
quintas feiras
eu vou subir aulas do curso de r e aos
finais de semana é mais precisamente aos
sábados à tarde fim do dia eu vou subir
a aula do conteúdo aí tradicional do
norte pouco marcante onde eu falo de
trade em geral liberdade e finanças
beleza pessoal o que eu tenho pra vocês
não há quatro de hoje vou aumentar um
pouquinho a complexidade para tornar o
curso cada vez mais interessante e hoje
vou mostrar pra vocês como é que a gente
lê um arquivo externo para dentro do r
e como a gente manipula um novo tipo de
dados que a gente vai chamar aqui de
data frame nas aulas anteriores a gente
tinha trabalhado bastante explorando
como funciona a estrutura de dados que
as nossas chamamos de vetor e hoje o
foco é nos data frames
primeiro nós vamos trabalhar com um
arquivo com histórico de cotações do
gráfico de uma hora do pará euro o dólar
já sempre voltado aqui propor o universo
de trading e como que a gente faz é para
colocar esse arquivo aqui dentro do
então eu sempre queria uma variável é a
base para tudo o que a gente tem e eu
vou usar uma função aqui dentro do rn
específica pra ler arquivos que é
chamada de jeff bridges existem outras
funções como a ride csv entre outras
coisas mas eu gosto bastante porque ela
é muito rápida pra carregar
principalmente quando você está
trabalhando aí com arquivos maiores mas
se você conhece outra pode também usar o
tem problema nenhum então essa função e
freed ela vai receber como parâmetro o
nome do arquivo que eu já me lembro aqui
que é euro sd h um ponto csv certo
o arquivo tem header ou seja ele tem o o
nome da coluna em cada um então a
propriedade header o argumento regra vai
receber um td true como a gente viu na
outra aula também poderia ter escrito
entrou
dessa forma e os campos estão separados
com um ponto e vírgula né então nosso
separador é o ponto e vírgula aí se você
tirar o comando assim do jeito que está
você vai perceber duas coisas a primeira
de todas é que ele não conseguiu
encontrar a função é free digo porquê
porque não é você tem uma coisa que nós
chamamos de pacotes ou laborais né ou o
do tempo em inglês
a coty ele é um conjunto de funções já
pré programado por alguém que ele contém
já dentro dele outras funções que podem
ser muito úteis então pra que você não
tem que escrever do zero uma função que
valem um arquivo de texto por exemplo
existe um pacote chamado data ponto
tempo que é um dentre vários utilizados
para poder fazer esse tipo de ação
como provavelmente você está no pr pela
primeira vez como que você faz a
instalação de um pacote é muito simples
você usa o comando install ponto taques
o próprio registo já sugere aqui pra
você e aí você coloca o nome do pacote
que você quer instalar entre aspas então
data ponto table e aí você executa esse
comando
como eu já tenho aqui instalado nele ele
vai instalar por cima até busca uma
atualização e disse aqui que foi
instalado com sucesso
não basta instalar uma vez instalado
isso só precisa ser feito uma vez vou
até comentar aqui porque já está feito
nós temos que carregar o pacote né então
você carrega pela função livre e aí você
coloca o data ponto tempo sem as aspas
duplas
aí você vê aqui que é foi carregada a
essa versão que é hoje onde estava
instalada e aí ele foi construído pra
outra versões anteriores do r também e
aí agora quando você voltar e executar a
função e freed você vai se deparar com
um novo problema que ele não vai
encontrar o arquivo e por que ele não
vai encontrar o arquivo werre tem um
negócio que ele chama o diretor o
diretório de trabalho né que pra eu não
tenho que ficar escrevendo aqui todo o
endereço do arquivo então ser dois
pontos barra documentos etc
tá você pode sempre encurtá esse
trabalho se você é trabalhar com a
configuração desse diretório de trabalho
e é muito fácil você vem aqui em sessão
você vem aqui em sétimo adair hector e e
aí você pode escolher o diretório como
você bem entender então eu vou vir aqui
tenho o curso de finanças quantitativas
selecione o arquivo e agora eu tenho o
direito ao selecionado ouvir o que você
também pode usar esse comando que ele
mesmo sugere aqui que é o sétimo working
da ect e aí você coloca um endereço
a gente faz quando respondi porque é bem
mais simples agora sim finalmente eu
carrego o arquivo e aí você vê aqui não
é invariavelmente que o seu carro
arquivo foi carregado com sucesso
note que diferentemente do vetor e aí eu
vou escrever um vetor aqui só pra gente
é ver como é que é realmente essa
diferença
você já pode primeiro notar que quando a
gente tem um vetor
ele vai ser chamado aqui dentro do
invariavelmente de velhos quando a gente
tem uma estrutura de dados tipo da
tráfego e ele já minc como data e repare
que ele tem agora que uma setinha azul
tá porquê porque eu não tenho só uma
linha de informações eu tenho várias
colunas
então quando eu clique na setinha e abro
eu vou ver tudo o que eu tenho ali
dentro do da femme que é uma coluna
chamada date hopper hi-low em close que
são as informações aqui referentes ao
euro se eu clico aquino nome zinho do
euro ele vai me abrir parecido ali com o
excel pra você dá uma
olhada aqui em antemão como essa
estrutura de dados se parece beleza
pessoal essas são as principais
diferenças que você já pode notar entre
um vetor que a gente vinha vendo ea
estrutura do data frame vamos conhecendo
melhor
esse da femi uma das características que
você pode usar é uma outra função
chamada tu és pra você ter certeza do
tipo de dados que você está trabalhando
há então essa nossa variável euro que na
verdade nada frame a classe dela é um
data termo data frame ok porque também
usei o importante pela função a data
tentou porém eu quero um data frame puro
então eu vou retribuir essa minha classe
euro e usar a função é data frame para
converter a minha base euro apenas em
data frente nós lenta meio complicado
isso não isso não é complicado é sua
primeira vez você está vendo é você tem
que trabalhar os dados deixaram da
maneira correta para você não tem nenhum
problema futuro nuno código então agora
se você girar de novo aqui o comando
classe você vai ver que agora sim eu
tenho um da femi puro então isso é essa
ação que a gente tinha aqui que é
convertendo para o data frame bora
conhecer então essa nossa base de dados
que foi carregada uma função bacana que
vai ser muito útil é o que a gente chama
de mim e ela vai trazer o que com a
estrutura de seu da fema então eu tenho
aqui do é 21 2245 e linhas que a
primeira informação por cinco colunas
além do mais essa informação tem ali no
invariavelmente têm invariavelmente mas
quando você trabalha aqui com a função
de você pode pegar esse número por
exemplo que vai servir para uma
integração futura
quem mais pode ser útil para você
conhecer a sua base de dados bem eu
posso querer saber quais são os nomes
das colunas dos campos que eu tenho
então eu uso a função names e do nome do
meu data frame e aí eu vejo exatamente o
conteúdo que eu tenho aqui porque que
isso é importante por exemplo se eu
quiser renomear a coluna coisas que a
gente vai ver mais para frente eu
consigo acessar dentro da função names
um campo específico tá então vamos ali
na outra parte acessando data sets eu
repeti neles porém usar o colchetes pra
pegar o primeiro elemento de names o que
vai vir tem vindo desde então esse é o
valor
se eu quiser daí mudar esse nome é certa
você vai poder fazer também
você pode usar esse mesmo raciocínio
falar poxa se eu quiser pegar o primeiro
elemento desse data frame então eu posso
fazer euro 1 alcançou o primeiro
elemento é a coluna inteira desde já a
aleandro eu não quero a polônia inteira
como que você faz então você repete os
colchetes porém você vai usar as suas
duas dimensões sempre começando com
linhas e sempre começando com colunas
então se eu faço euro 1 eu pego o
primeiro elemento da primeira linha da
primeira coluna que é essa data que se
eu mudar isso daqui e quero pegar o
primeiro elemento da segunda coluna qual
é a nossa segunda coluna lembra lá da
função nem sou você pode verificar aqui
também é o que então você tem aqui o
valor dessa primeira abertura a leandro
quero saber qual quer um valor ali da
linha da ess em tom valle coloca o seu
sem coluna 2 você tem ali um ponto 18
337 beleza pessoal presta bastante
atenção nessa aula entende muito bem
esses conceitos bem simples porque eles
são a chave para a gente começar a
manipular essa estrutura de dados que é
uma das principais quando a gente vai
desenvolvendo o nosso primeiro modelo
mas lá pra frente
um grande abraço qualquer dúvida me
escreva no telegrama deixe um comentário
aqui também no youtube e responda o mais
rápido possível
um grande abraço e até o próximo vídeo
tchau tchau
[Música]