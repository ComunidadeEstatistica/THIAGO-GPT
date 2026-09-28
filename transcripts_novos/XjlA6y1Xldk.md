# webinar - Inteligência Artificial - Regressão Logística com Diogo Picco

- **URL:** https://www.youtube.com/watch?v=XjlA6y1Xldk
- **ID:** XjlA6y1Xldk

## Transcrição

fala galera
beleza pura da cotidiano como começar
mais um binário
esse é o cenário é um hinário preparação
para o nosso hackathon que acontece
agora de ver dia 21 de setembro sobre de
glam e inteligência artificial
a gente vai ter a presença do diogo
daqui a pouco ele pra vocês é
infelizmente nosso rock então já está
fechado fechou alguns dias atrás as
inscrições de esteve bastante aderência
acho que pelo menos umas cinco equipes
vão participar de 45 pessoas
então vai ser bem maneiro mas todo mundo
fica convidado pra quem quiser ver a
premiação participar com os jurados ver
os pits dodô que vai ser apresentado no
dia 23 às 4 horas na indy house beleza
vão passar por diogo de um trabalho de
inteligência artificial tem dez anos é
consultor do banco do brasil é fez
estatística na estrada estatística da
terminando o doutorado agora em finanças
também mais voltado para a estatística é
tem uma empresa também de de consultoria
chamada é inferir estatística é
construir treinamento é professor do
iesb ea tecnologias disruptivas é tem
alguns projetos como mentor também é de
startup né principalmente nessa área de
har claro é e modelagem matemática mas
ele escreve em análise de dados
modelagem modelagem e principalmente ea
identificação de padrões e é isso fica
com ele agora que ele vai entrar pra
vocês como calcular o risco de
inadimplência de um cliente na hora de
tomar um empréstimo bancário beleza
olha a galera vocês
valeu galera tudo boa noite
quem fala é o jogo tava vendo todo mundo
bem todo mundo tranquilo
manda ver beleza ego
boa noite pessoal estava internet como
da personagem estava pegando aqui mas
agora não sei que estão me ouvindo o
jogo era trazer para vocês aqui uma
análise é uma
o método de análise de usando a
regressão logística para risco de
crédito como o bruno acabou de falar pra
vocês
bom eu vou me apresentar eu sou o
estatístico trabalho no banco do brasil
e tem uma consultoria nessa área de
estatística trabalha muito tempo na
nossa área de inteligência artificial
condenar de matemática ea me impressione
ser estática como bruno acabou de falar
pra vocês também têm treinamento aqui e
é o nosso é o nosso papel é esse
inicialmente webinar agora que cotidiana
acelerador e é isso gente
vamos lá vamos primeiro passar para
vocês o que seria uma regressão
logística e como funciona eu vou
projetar na tela do meu computador
compartilhar com vocês a apresentação
que eu fiz pra vocês pra vocês terem que
seguir também depois vou mandar pra
vocês apresentação em um programa em que
a gente vai estar utilizando a calma e
sorte aqui está parecendo uma
apresentação antiquada de bronze
agora acho que foi agora pra vocês não
sei se está todo mundo vendo bem aí bom
saiu de novo
andando pra ver tranquilo agora foi
vamos lá o objetivo da da nossa análise
né
é objetivo da nossa marca tentar
encontrar um modelo que explica o
sucesso ou não de uma campanha de
marketing que é a base da tim que a
gente vai usar ou mesmo de um modelo de
risco de crédito vai identificar se o
senhor futuro cliente do banco inglês do
banco
ele vai entrar em the flow ou não como
caso de uma campanha de sucesso de
marketing é se o cara vai essa pessoa
sou cliente vai contratar um determinado
produto ou não
resumindo objetivo em geral como a gente
trabalha com regressão logística sempre
objeto pode ser sempre um objetivo
binário o caso de sucesso um caso de
fracasso é o risco de crédito que a
gente trouxe como premissa para essa
aula ele é um caso bem emblemático
quanto a isso a gente calcula qual a
probabilidade de um determinado
indivíduo de ira de faltar com bank quer
de falta de fogo né
ouvira de faltar um banco é vir a se
tornar inadimplente ter um atraso de uma
empréstimo e mais 90 dias
então esse é o objetivo principal
a gente vai trabalhar nessa nessa
pequena aula é identificar a
probabilidade de um indivíduo atrasar o
pagamento com o banco ou mesmo uma
campanha de marketing também a variável
de marketing equipe ia fazer sucesso ou
não quem está na nossa base de dados
a base da adição dados públicos estão
disponíveis na página mais detalhados na
nesses locais que eu tenho aqui comigo
pra você é não sei pq essa base de dados
da base da chamada bank
ela tem dado de 400 e poucos mil pessoas
e algumas variáveis algumas
características variáveis
então vamos começar a quem quiser também
meio-médio buffery ponto com.br para
tirar qualquer outra dúvida o
eventualmente tentar alguma coisa quer
saber
vamos a algumas definições no primeiro
antes de começar a aula vamos definir
algumas coisas algumas características
é eu acho que está passando bem lenta e
pra vocês eu tô falando para aqui pra
mim já passou e agora estou vendo que
está isso agora vamos lá algumas
definições
os erros causados por dados inadequados
são muito menores do que aqueles devido
à sua falta ocorre devido à falta total
de dados
charles baby baby disse isso é isso é
importante a gente é sempre melhor você
tem um modelo mesmo que seja inadequado
que tem ausência de informação é sempre
melhor você tem alguma coisa para você
explicar o que está acontecendo
vamos lá vamos entender o que a gente
vai fazer
tá nós temos a nossa base da algumas
informações sobre campanhas realizadas
a gente tem algumas avaliações de
informações de clientes
nós temos algumas características
intrínsecas do negócio
essas variáveis que têm essas três
características nós vamos juntar las nós
vamos fazer como vocês a batedeira e tá
te deu o nome the machine lan
nós vamos juntar las e vamos mensurar
uma probabilidade de um determinado
indivíduo vira de faltar ainda ficou com
um banco ou mesmo ter um sucesso uma
campanha do banco se eu preparei dois
tipos de modelos aqui pra vocês uma
definição
o de classificação eles usam informações
teóricas de estatísticas para isolar os
efeitos das diferentes características
dos clientes quando ocorre a situação de
controle estão tão você se passaram aí
pra a página parece também lento aqui
está acompanhando aí então sempre até
porque está travando aqui e não sei se
estavam tava trabalhando não dá pra
acreditar na página definição
a beleza é então a modelo de
classificação das informações teóricas
estatísticas para isolar o efeito de
diferentes características do cliente
quando ocorrem situações de controle é
mais ou menos um definição de modelos
classificação tão qual é o objetivo que
a gente quer fazer aqui agora com esse
modelo é classificar
vou ter que definir se um
verifica se um cliente se ele vai ser um
cliente que vai entrar ainda foi um
banco ou seja não vai pagar humano com
aquele cliente que vai pagar ao banco
eu vou misturar estes ea partir desse
risco eu classifico em uma categoria a
ou numa categoria b esse é o principal
objetivo da regressão logística de uma
forma geral o modelo de pressão estão
muito utilizado quando se pretende
modelar relações entre variados
na hora que eu vou usar variáveis é de
variáveis e cinco de informação
informacionais que vai usar aqui dá seja
do produto seja a característica do
cliente seja da forma com que ele
consumia que ele consome o produto usa o
crédito são variáveis que são
relacionadas ou entre si em relação à
variável resposta no caso agora é deixou
então o que a gente vai encontrar no
modelo de regressão seja uma digressão
neaci de uma delegação diz que o modelo
de agressões em geral procuram relações
variáveis explicativas são aquelas
variáveis x que a gente chama
normalmente estatístico em relação sobre
a resposta muitas vezes define como a
variável yk sua variada responde então
vou ver aquelas variáveis são capazes de
me classificar a variável y e 01 deixou
ou não deixou em 10 no caso de uma
depois ela não deixou barato resposta
apresenta apenas duas respostas 01 é
muito usual usava uma técnica chamada
regressão logística e por que que ela é
usual é a redução logística
diferentemente da regressão múltipla ou
a regressão linear que a gente diz ela
tem menos pressupostos as pressuposições
são menores a a maneira de você
construir um modelo ele é muito mais
fácil você não tem que respeitar tantas
regras mas mesmo assim não tem algumas
regras que devem ser respeitadas
a regressão logística é uma técnica
estatístico que tem como objetivo
modelar a partir de um conjunto de
observações a relação logística entre
uma variável resposta antigo tônica ou
seja 0 1 e uma série de variáveis
explicativas numéricas podem ser
contínuas ou discretas ou mesmo
categóricas tá então qualquer tipo de
você pode utilizar para uma regressão
logística
agora por que não utilizar uma regressão
linear nesses casos de classificação
uma primeira razão é que a variável
resposta é binária e não é contínua ou
seja um atraente ele vai entrar deixou
ou não
ou seja ela vai ser 0 1
quando temos um modelo de eleição linear
usual né
o cálculo de probabilidade de sucesso
ele pode levar valores pedidos de
probabilidade fora do intervalo de 01 um
parecer menor quiser e moro q1 e nesse
caso não existe probabilidade negativas
e propriedades acima de 1 seria semana a
certeza então modelo linear não é muito
bem ajustado esses limites entre 01 e
não são respeitados na hora que a gente
usa uma diversão linear
muitas vezes uma grande reunião também
assume que tanto tendo em conta os
valores das melhores aplicativos agora a
resposta é uma discussão normal
companhia constante ou seja a variável y
vai ter que ter uma discussão normal ea
aliança dela tem que ser constante a
gente tem que ser o morcego das tic que
a gente chama o que não é o nosso caso
novela nessa variável resposta ela só no
caso de sucesso ou fracasso é do tipo
que nela é do tipo de nome ao néel
perdoa-lhe essa variável responde tabela
blumenau é soma de bernoulli então se
você não tem uma variável normal seus
erros também não vão ser normais modelos
de agressão não cabe uma redução linear
tudo expresso poste é na qualidade dos
erros é mais um motivo pra você não
utiliza um modelo de inversão linear com
você quer classificar indivíduos em duas
classes ou está a apresentar uma
digressão logística de duas classes
mas existe um modelo de gestão logística
multimodal que você pode classificar em
mais de duas classes
o presente exercício a gente vai fazer
aqui só vai pacificar em duas hipóteses
então voltando para uma redução linear
não é satisfeita no modelo binário
então eu já tenho dois pressupostos
selecção é violados
há uma semana a cidade da criança a
criança não é uma cidade que os erros
não são normalmente distribuídos
então com essas duas hipóteses violadas
você não deve fazer uma digressão linear
sobre a outra hipótese está sobram
outros métodos de que você poderia
utilizar você pode utilizar modelos de
regressão logística um método que também
classifica entre dois grupos a ou b ou
10 nesse caso você pode usar um método
chamado não só este você pode utilizar o
método maxsports vetorial sbm
você também pode utilizar a rede neural
você pode utilizar árvores decisão se
utilizarem métodos de classificação
só que o método de regressão logística
ele já é muito massificado muito é muito
utilizado tanto na área médica conta na
área de crédito para a banda
o modelo chamado creche escola modelo ao
antigo já em muitos sedimentado no setor
bancário
então hoje em bancos em geral para
marcar risco de crédito de um cliente
nós utilizamos regressão logística e por
esse fim
muitos estudou sobre a emissão a gente
tem muitos parâmetros para se comparar o
seu agente que também tem outras
facilidades a interpretação dela também
é muito boa
se feita você consegue relacionar a
interpretação dela como que você não
consegue fazer por exemplo uma rede
neural profunda a interpretação é um
pouquinho mais confusa e é necessário
principalmente mudou numa área bancária
muitas vezes o cliente solicitar a
aplicação por causa do empréstimo você
pode explicar o motivo do empréstimo uma
regressão usando métodos redes neurais
isso não é possível muitas vezes você
não sabe o porquê da rejeição do crédito
ou não não tem várias características
que o chile tornam a regressão logística
um metro é muito utilizado como a
requisição a gente ela tem para ter
respostas a apenas dois valores elas
queriam apresentar aqui era a umidade
estava em dois valores possível que o
sucesso ou fracasso viver ou morrer
aceitável aceitado qualquer problema que
você quer uma classificação como
resposta é a probabilidade classificar
no grupo ao no grupo b
você pode utilizar uma regressão
logística se é se esses dois valores são
01 a média é a proporção de uns programa
de sexo ou seja dos eu tenho dois classe
na área 01 calcular a média de sucesso o
projeto certo e nada mais
vai ser que a proporção de um dentro da
sua mostra com em observações e
independentes temos uma economia é a
soma de distribuição bernoulli secar uma
descrição binomial é parte um pouco da
parte tática
a expressão logístico ele é um recurso
que nos permite estimar a probabilidade
associada à ocorrência de determinado
evento
então faça um conjunto de verdades
exploratórias ou seja eu posso calcular
a probabilidade de um indivíduo viver ou
morrer dá algumas características do
indivíduo se ele fuma se ele não for uma
qualidade dele qual é o peso é se ele
faz atividade física
então você tem uma característica que
seriam suas várias são as variáveis
exploratórias no caso das variáveis
explicativas querendo estimar a
probabilidade de um indivíduo viver ou
morrer assim também vale por banco
se o cara vai entrar deixou não vai
assim também segue com uma campanha eu
vou ter sucesso naquela campanha ou se
vou ter um fracasso naquela campanha
então qualquer caso guinar uma regressão
há gente que pode ser ajustada
o resultado da análise fica contido no
intervalo a série então sempre a
resposta da regressão logística vai ser
uma probabilidade vai ser a propriedade
daquele indivíduo sucesso naquele caso
por exemplo da propriedade daquele
indivíduo vira de saltar com bancos a
propriedade foi associada 08 adotar um
critério dia classificar aquele
indivíduo deixou ou não deixou
e assim vai bom a onde podemos aplicar
regressão logística
a emissão a gente pode aplicar em
diversas opções
a gente pode a aplicar regressão
logística no cálculo de risco
literalmente o risco é uma probabilidade
então tudo que você quiser calcular na
propriedade você pode aplicar uma
regressão logística na área médica é tem
muita área médica utiliza muito esse
método de eleição a gente se você vai
fazer compras se você não vai fazer
compras ou se fosse propriedade acertar
um alvo não assentam alguma campanha no
carro né
você tem diversos locais que diversas
maneiras diversas formas de se aplicar
uma regressão hoje diversos problemas
você ficava na mesma noite
muitos problemas às vezes você quer ter
um salário de alguém você pode repartir
esse problema é um problema de cotonu
com a probabilidade da casa de vidro
receber mais do que cinco
reais por exemplo e deixa a acertar o
salário dele você pode mudar o seu
programa e de saber exatamente quanto
recebe a chance dele seria mais um
determinado valor limiar se transforma
isso uma resposta de cotonu então
qualquer variável contínua resposta você
pode transformar uma variável econômica
está quente é só uma breve introdução eu
falo com a aac o grande estoque a gente
depois passar para o programa grego
exemplo melhor para vocês
bom qual a vantagem de utilizar
regressão logística
a facilidade para lidar com variáveis
independentes categórico é muito fácil
você lidar com essas variáveis no modelo
regressão logística
ela fornece resultados em termos de
probabilidade que também é bem tem legal
ou seja seu resultado é uma uma
exposição contínua de propriedade em 10
né
a facilidade de classificação divididas
em categorias
o número de exposições na regressão
linear que está falando um pouco tempo
atrás você tem 10 pressupostos ou seja
só deve aplicar um 6 a 10 mínimos
quadrados ordinários seja respeitado
dessa hipótese
a regressão logística têm menos
hipóteses são menos premissas são
pequenos números de suposições que deve
ser feito eo alto grau de confiabilidade
então são algumas das vantagens de
utilizar regressão logística bom na
edição de hoje que a gente pode ter
apenas dois níveis na ces 2011 é a
proporção na agressão nem a simples nós
levamos a média da variável resposta y
como função linear da variável
explanatória ou seja me levam a 0 mas
aumentar 1 x 1 com a regressão logística
interessa-nos modelar a média da
variável resposta p
em termos de uma variável exploratória x
nós podemos relacionar p
dessa forma linear pe-60 mais detalhes x
no entanto isso aí poderia tirar
resultados acima de 10
por isso em nome dessa repressão chamada
gestão logística essa é a função está
descrita a linha baixa prioridade
bom é igual a 1 sobre o mais velho é
para menos fdx onde é de x é uma
digressão percebe que salvará respostas
e um y agora ainda não é direta no teve
uma transformação foi feita a
transformação não existe só esse tipo
essa transformação logística como se
chama regressão logística de moda trans
achei a província dá um nó no 9º de mim
e me prometi e tráfego está assim
existem outras tá vamos lá aqui então no
caso da variável dependente y la somme
apenas dois valores possíveis 01 e haver
um conjunto de variáveis independentes
de x 1 da xp como de reversão da lógica
pode ser feito da seguinte forma como
está escrito aí abaixo do islate bom
os coeficientes meta zero vai libertar p
são estimados a partir de um conjunto de
dados pelo método de massa magra
semelhança é bom dizer que esse método
mas um número semelhante à aplicada à
regressão logística ela não tem uma uma
função fechada ou seja você não tem
cálculo na mão você não consegue
calcular a segundo ele vai embora mas
ela não tem um resultado fechado
o áudio da melhor aí gente
estão vindo melhorou pessoal
então a gente tá tá tá não é que tinha
gente reclamando que o áudio é porque
teve um ataque de uma baleia tinha mais
voltou com o doutor beleza gente como
continuar aqui
a forma de estimular esses beta s coisas
quentes estão de cara chamado método de
vária máxima era semelhante a esse
método você faz o produtor da função
seria igual a zero
para achar o ponto de mim nessa função e
se trata se de cada um dos betas
associado x tem um ponto de mim essa
função ela não tenha integrado aqui e
otimiza ou minimiza esse ponto através
de métodos de integração numérica
então sempre quando você for utilizar um
bonito seja no país seja no r
você está usando jardim online está
usando métodos de integração numérica
tá eu não tenho uma integral definindo
tem uma fórmula finita clientes e
calcula merda somatório e ii é uma forma
você não tem essa função fechada você
faz por integração numérica
bom a culpa logística é da dis formato
era ter um comportamento problemático no
formato da letra s
onde quando fdx aumenta muito ou seja
vai para o infinito
o resultado da propriedade e são sem
igual entende a 1
e quando a fx a índia - infinito a
problemas decidi não sei qual vai para
zero
resumindo o domínio da fx ela pode ser
de menos infinita mais infinito então
não tem mais nenhuma limitação de 0 a 1
entretanto y é ele transformada e fica
sempre entre 0 e 1
é uma função continua nesse formato de l
bom os impactos no coeficiente
influenciam a razão de chances
os coeficientes beta da regressão
logística ele não são interpretados de
forma direta e são razões de chance tem
que calcular o potencial daquele
coeficiente para se saber o impacto
daquela variável na probabilidade de
ocorrência do fato que está estudando a
50 cent positivos aumentam a chance
ou seja aumenta a probabilidade de
ocorrência do evento
conscientes negativos diminuem a chance
a razão de chances e diminui a
probabilidade de ocorrência naquele
momento
a regra básica para a discriminação em
dois grupos quando a gente usa esse é
uma regra deixou eu vou mostrar
instalações do local porque a gente pode
mudar isso
a propriedade y ser igual a gente sempre
associar y é deixou ou não deixou o
sucesso ou insucesso sempre que a
propriedade de cada indivíduo fosse uma
de e mail que seria isso
imaginemos nós temos um indivíduo que a
gente quer calcular a probabilidade de
ele não vir a pagar o empréstimo junto
ao banco e à propriedade esse indivíduo
não vir a pagar esse empréstimo e 0,60
usando esse critério se acima de e mail
dizendo o seguinte este individo ele é
um de fofura banco mesmo antes de
ocorrer se classifique como um ou seja
unidades acima de meio podemos
classificar comum e probabilidades
abaixo de meio classificamos com 10
bom esse seria um critério que a gente
vai adotar para classificar o indivíduo
entre 01 agora já um breve histórico do
que a regressão logística já que nosso
tempo é curto não dá pra falar muito
sobre isso vamos direto com a aplicação
de r
tá bom gente vamos lá eu vou abrir aqui
é pra vocês vão ver na tela do
computador aqui tá se conseguem ver
direitinho o programa é muito pequena
eles querem aumentar a fonte ele pode
responder
no site oficial de vocês pelo que assim
como a gente eu vou utilizar é para quem
está familiarizado com r esse ambiente
cabe aqui o estúdio apenas poderá tela
de fundo manter a cor preta é mais fácil
para você não dá cansaço na vista
aconselho sempre você vai trabalhar pela
tela branca
aquele brilho causa muito cansaço na
vista
então eu sempre procuro botar o fundo
preto fica mais fácil
então pedi a ela você compara enorme
macho pata é que no rio tudo aquilo que
a empresa então vamos lá eu vou usar
algumas libras aumentar um pouquinho a
fonte que tem gente pedindo 5º lote
[Música]
anda disse que não puderam contar aqui
abaixo tarefas por mais aqui em baixo
não vai ser necessário não a gente vai
usar mais a parte de cima
enfim se estão conseguindo ver agora
melhorou
sei que ela é pequenininha não é ruim
mas melhorou pra vocês
o programa curto e só 300 linhas de
código então se é rápido ea gente tem
mais de meia hora né
eu acho que dá tempo de passar bom esse
é o estúdio não estou usando é indireto
usando no estúdio e eu vou usar algumas
libras do r está a usar seu livro é 1071
é brincar
o gg pote 2 começam os pacotes que estou
falando de xl porque na base da estátua
em xls xlt excel
o display o gemol soçaite e só selection
são algumas das bases que algumas das
libras que a gente vai usar sem quiser
instalar nesse pacote de r já está
familiarizado com r pode instalar este
pacote vamos começar a rodar seus lábios
eu sempre carrega os lábios primeiro ou
a gente usa aquele r mls e limpa toda
base mas como já está tudo limpinho aqui
no programa já deixei preparada para a
aula
eu preciso da função para limpar toda
sua área de trabalho que é sempre bom
vocês usarem tá que o r carregado na
memória tudo que se fez nos últimos
trabalhos estão a pagar
então vamos rodar essas lágrimas
moradora de uma vez carregando agora vai
importar base da vaidade sobre a
validade de bem tá ela já trabalhada no
meu nome eu dei aqui chamado de dados
eu já trabalhei um pouco então vou trazê
la para vocês e vamos abrir um pouquinho
aqui vai passar um pouco das variáveis
para você tá essa base desse programa a
gente vai passar pra todo mundo depois
tá eu vou usar agora que para a obra
daqui a pouco passa pra todos
é nessa base da diz que a gente tem nela
também que as variáveis elas estão três
em forma de pequenas não pode trabalhar
com nomes cumpridos de variados mas eu
preparei um um dicionário de variáveis
porque olhar essa variável assim sem
usar um dicionário é complicado
é muito ruim a gente sempre procura
utilizar um dicionário de dados só tem
que ser militar
acho que tá aqui seis estão conseguindo
ver o dicionário de dados
bom esse dicionário de dados é um
clássico e vê uma tv 16 eo y variável y
está a variável e y não é deve ser assim
um depósito a prazo ou não na verdade a
variável ysl ficou truncada mas agora a
informação de vôo bom que é variável 11
é a idade a vo2 emprego ou seja um tipo
de emprego é um dado categórico a
variável 3 seu estado civil também é
categórico se a pessoa casada de você
ainda é solteiro e assim vai
a marvel 4 a educação ela tem uma
categoria desconhecida tem a categoria
primário tem sua informação primária
média e terciária no caso de nível
superior tá com essa base da rússia lei
americana e usa um primário secundário e
terciário que ele como tradução né
mas o nível superior pra cá há variáveis
seja o saldo mel média em euro não é que
está utilizando da pessoa avaliada 17s
tem um empréstimo habitacional ou não de
oito e tem crédito o crédito pessoal sim
ou não também é binária então todas as
variáveis e categórica gente já
transformou essas categorias não erre na
nossa base e vai ver assim o o número 15
10 3 23 vou passar todo esse dicionário
de base pra você também é eu só
recategorizada e deixar escrito no texto
ao eu deixei elas numéricas tá bom
são variáveis relacionadas disse que o
relacionamento era relacionado ao último
contato da copa da campanha atual
eu tinha umas outras variáveis que foi
do contato que aconteceu na campanha
ou seja se tem algum tipo de contato é
breve o v9 é se a pessoa receber um
telefonema uma ligação telefônica do
telefone fixo ou via celular ou se você
não tem essa informação que é
desconhecido então não é o 10 é o último
dia do contato
qual foi o dia do mês que teve contato
braga 11 é o mês do último contato
janeiro e fevereiro mas até dezembro a
ver 12 é duração do último contato em
segundos ou seja ver dois é o tempo que
a pessoa que recebeu o contato ficou no
telefone é o falando com atendente
durante a campanha
a variável é da variável 1911 a gente
não deve utilizar nós como está na base
da deixou escrito aqui pra vocês
a variável de 13 identifica o número de
contatos realizados durante a campanha
para aquele mesmo cliente ou seja se o
cliente x o cliente um recebeu 15
campanhas vai aparecer lá o número 15 é
o número de contatos que ele recebeu
durante o período de campanha e pode ter
recebido mais do que um contato
a variável e 14 é o número de dias que
passaram depois que o cliente foi
contatado pela última vez a variável e
15 o número de contato realizado antes
da campanha você tenha o contato durante
a campanha ele tem contato antes da
campanha dessa base dado tem dois tipos
de compasso trabalhava 16 o resultado da
campanha de marketing anterior
na campanha anterior eu tive sucesso ou
fracasso outro resultado e um resultado
desconhecido e na variável e seu y é seu
de falta na verdade é que não é senão um
depósito a prazo de aposta para salvar a
vida de hef e voltei lá que variaram de
5
é esse o dicionário de base da base de
dados é importante entender antes de
sair fazendo um modelo bom é a primeira
linha de código também alegre r3 x l é
célebre ele permite usar essa função
aqui ride excel word e excel estou
botando um caminho aqui do meu de onde
está a base de dados quando roda essa
função quando eu quando faço a função a
gente puxa a base bem que para o nosso
movimento aqui do lado direito tá é se
vocês forem aquino copiar o endereço é
um interessante trabalho está se eu
pegar esse endereço aqui copiar colar no
r
até invertida se você colocar 5 a barra
invertido entre as quais ele não desse
formato aqui e não vai funcionar direito
então só inverte a barra
bota o finalzinho o trabalho traz o nome
do arquivo você puxar o seu arquivo do
seu explore e onde tiver pra dentro do
domínio do é beleza
bom o viu bank é uma função para você
ver só para abrir sua base de dados
ela agora quem consegue consultar lá de
cima deles variável que tipo de variável
que talvez valha a verdade está numérica
variável ocupação ela tá numérica todas
as variáveis são numéricas aqui que eu
transformei para número excel
só que nós sabemos que a variável
ocupação ela não é numérico era do tipo
fator é o tipo fatura uma categoria que
o indivíduo ele está num tipo de
trabalho lembrando que o tipo de emprego
dele que a ocupação ou é o cara é
desempregado cada gerente uma empregada
doméstica o empresário e estudante
o autônomo pois então é uma categoria
então cada número destinam número é
representa uma categoria
nós temos que formar para o r que
variáveis são categóricos a função que a
gente usa para dizer que vai haver essa
categoria essa função chamada é facto
isso é muito importante também na hora
que for fazer uma análise fatorial tá
tenha muito cuidado trabalhar - o fator
e não foi numérica
se você tem que informar ao ocorre que
variáveis são categóricos todas as
variáveis que eu voltei aqui ocupa de
ocupação oeste é de estado civil e duas
de educação o df é é um depósito a prazo
que recebeu não fim de financiamento
empréstimo
o caos se não me engano foi contato né
foi o resultado da campanha com o
resultado anterior à campanha e outros o
contato de comunicação da verdade real e
comunicação
a gente vai rodar diz cada uma das
variáveis e pode apertar comprou inter
em cima da linha a linha está havendo
aqui embaixo do rodado cada uma das
linhas
as outras variáveis a variável y eu vou
usá-lo como inteira tá variava entre 01
tudo bem que a marcação se ele fosse não
é mas eu usava como inteiras interpretar
sejam venho porque depois a
variabilidade é
é ela a contar também é né e controlar o
outro possa continuar beleza
antes de começar a fazer uma análise ou
construir um modelo seja ele qual for
é muito importante que façamos uma
análise descritiva na nossa base de
dados
nós precisamos conhecer nossos dados
então aqui vai fazer a função tempo bem
que cifrão y só para tabular a
quantidade de y que eu tenho ou seja a
quantidade de fãs ou não deixou que eu
tenho nessa base de dados
é para eu estar aqui em baixo na sua
coluna aqui embaixo
eu subi isso aqui aqui está o número de
zero tem 39 1922 zero ou seja 39 922
pessoas que não lhe faltaram e cinco mil
duzentos e oitenta e nove pessoas que te
faltará quem entrar em default
é importante a gente tenha essa análise
descritiva e é aqui por enquanto ele só
tabuleiro variável resposta a gente vai
usar essa variável essa lebre dia d pág
r pra trabalhar agora as variáveis
numéricas e fazer gráficos 20 também em
análise gráfica saber como é que a
instituição seus dados como é o
comportamento dos dados cruzar variáveis
então essa análise descritiva é
importante ser feita inicialmente até
porque ele já conhecer algumas
características da população estão
trabalhando
vamos lá pessoal você carrega essa livre
dia d pág r embaixo eu fazer um um
graaaande da idade
esse gráfico vai aparecer o seu lado
direito inferior
ele está jogando ainda não carregou já
acabou de rodar e aqui a gente pode ver
mais ou menos a distribuição eu estou
ampliando aqui da idade em função de
cada categoria
observa que a maioria das pessoas que
não me faltaram tem muita gente que não
deve faltar foi 39 mil pessoas
ela está bem também concentrada na idade
de 25 até mais ou menos 60 anos de idade
aqui também a maioria das pessoas que
faltaram entre o que a categoria 1
também está entre 25 e 50 por exemplo
pode ser aqui em cima você tem muitos
muitas pessoas mais velhas
esse gráfico ficou muito legal então por
isso a gente fez um outro box plot box
pode a gente usa é o próximo gráfico
isso vale também para a idade pra
identificassem outline ou não existem
diversos testes para casa o classical de
lalo um box pote é visual e é um teste
inicial para você capturar ou não a
presença de alte lá e então é
interessante você dá uma olhada no vox
lote
vamos construir esse voto escondido
embaixo com a mesma variável
vamos observar ela ampliá lo aqui
observa essa linha do meio no boxe lote
é a mediana das cidades
essa linha superior é o terceiro partido
da cidade
essa linha inferior o primeiro partiu da
cidade não reparasse o primeiro artigo
3º do artigo essa distância entre os
cortes de dar uma idéia da distribuição
da concentração dos seus indivíduos se é
para que o gráfico das pessoas que não
lhe faltaram as cidades elas são mais
homogêneas ou seja elas então ela tem
muita dispersão porque menor entre o
primeiro e terceiro artigo entretanto
você tem mais outline saque em cima
já as pessoas que faltaram você observa
que o terceiro quarto está mais distante
da mediana que essa linha do meio do que
o primeiro no artigo você tem uma
dimensão maior da cidade de quem faltou
no gráfico ôôôô da cidade das pessoas
que faltaram no índice amarelo do que o
vejo ele e também tem bastante outline
gente algumas premissas da regressão
logística que são bastante importante
que a gente tem que observar se não seu
modelo pode ficar visado é a presença ou
ausência de outlight seja outline onde
reúne dimensional ou seja é o que a
gente está fazendo de uma única variável
um outlet é multidimensional onde você
faz uma normal multivariada a gente pode
analisar variável eo variável aqui nós
temos três variáveis
mas alguns modelos ac de saldo
analisando em variados individuais
eu vou dar uma passada porque senão a
gente não vai ter muito tempo de ver
todo o modelo mas a idéia é que se faça
essa análise gráfica para todas as
variáveis numéricas em comparação às
variáveis
já a sua barra resposta e isso é uma
análise cruzada que é importantíssima
ser realizada antes de tudo tá bom é e
quais são as premissas desse modelo de
agressão a gente tem que ficar atento é
muito condenar idade entre as variadas
respostas que isso interfere na marcação
dos seus betas a presença ou ausência de
alte laia seja outline unidimensional
como multidimensional e o tamanho da sua
mostra é é alguns autores falam que você
usa cada variável resposta que você
utiliza no mínimo de 10 e observações
ainda muito não tem um teste específico
para classificar isso mas é você precisa
só a base da anac tem 45 mil clientes e
só duas variáveis a gente não tem
problemas tamanho de amostra
mas é muito complicado o tamanho da base
que vai utilizar na hora que você foi
construir um modelo então esses três
postos multicore na verdade a presença
ou ausência de outline e tamanho de
amostra importantes modelos de regressão
logística é para que eu não falei na
normalidade dos erros até porque os
erros não são normais então se têm menos
hipóteses ou menos premissa de que o
modelo múltiplo linear tá bom vamos
continuar aqui a análise há a próximo
grave que eu fiz foi em relação à
variável saldos e observou então
qualidade temos outline e eu fiz assim
para várias outras variáveis tá aí pra
fazer mais uma porção preciso observar e
depois vou colar as outras variáveis
canto numa do código pra você escolhe
também comentado ou distribuir bem
direitinho aqui pra vocês darem uma
olhada na variável saldo
você percebe que tem uma concentração
muito grande não só no próximo de zero
não é e observa esses pontos aqui
dispersos aqui em cima certamente deve
se ao chile na hora que foi construído
box lote estão muito discrepantes em
relação aos valores da maioria das
pessoas através de uma mediana no caso
do pop rock titãs é inter com arte fica
né
certamente esse ponto deve ser o titular
então existem alguns pilares dessa base
de dados
a gente não vai tratar o chile neste
exemplo agora mas fica fica
para melhorar esse modelo deve se tratar
assim outline e de algumas variáveis
contínuas que está utilizando
existem algumas outras técnicas que
muitas pessoas utilizam é que ao invés
de tratar otila e você categorizar as
variáveis na hora se recategorizada
variável numérica e variável categórica
é uma maneira de você tratar o titular e
você não vai observar a presença de
outline essa não é uma das melhores
maneiras mas é muito utilizada no meio
financeiro
tá bom
fez mais uma análise aqui pra variável
duração e será variável duração do
contato também uma variável numérica é
não só vendo a destruição em relação à
variável y dos algo aqui embaixo
construir um programa de cada uma das
variáveis é importante dar uma olhada no
programa porque o programa vai te dá a
distribuição picada uma das variáveis
a gente pode observar que a duração como
o próprio nome diz não imaginamos
duração com o tempo negativo então
sempre duração vai ser positiva e vai
começar do zero então dificilmente
estado variável duração teve uma
discussão normal se observa que ela tem
basicamente ela tem um pico de
distribuição até aqui no início dos 100
e pode ser um decaimento exponencial
aqui nela até próxima da de milho nem os
segundos 2000 segundos a a linha em azul
se eu não me engano eu botei a mediana
ea linha em vermelho até a média observa
que a média mediana estão bastante
distante entre os dois dados do que que
mostra a instituição não é simétrica a
instituições continuem médicos como
normal a média mediana ea moda ela fica
localizada sempre o mesmo bom você tem
uma simetria aqui quando você tem um
deslocamento da média em relação à
mediana eu cortasse a moda que também
certamente teria deslocado à moda
certamente vai ser aquele ponto tem uma
freqüência está em torno da ac seria
menor ainda do que a mediana
então é essa distribuição ela é
assimétrica conhecendo muito bem os
dados ou as variáveis explicativas a
gente tem mais ou menos as idéias de
como vai se reportar em relação à
variável explicadas no caso de fogo
ok é importante conhecer o padrão de
cada uma das variáveis é entende com o
padrão
um portal momento é a distribuição de
uma variável quando a gente for falar o
comportamento de uma variável
eu dou muito exemplo quando você está se
está em casa sem a pessoa que se conhece
bastante sobre o comportamento dela
vocês sabem que ela não gosta de the
last caiu durante a noite à lactose você
não vai comprar um chocolate pra ela que
tem a lactose para intolerantes já
conhece o comportamento sabe que a
pessoa não vai comer então conhecer o
comportamento de algo de da pessoa que
facilita o trato com ela é a mesma coisa
que a gente faz um modelo matemático que
a gente conhece o comportamento de cada
uma das variáveis que ele está
analisando a gente sabe mais ou menos as
relações que a gente vai encontrar
beleza
essa seria uma análise descritiva
inicial
fiz também outro gráfico aqui pra o
salário médio e não vou passar esse
grupo aqui também fotografa para a idade
após essas análises
agora repare que todas as variáveis que
estão cruzando aqui são variáveis
contínuas gente vai fazer um gráfico de
dispersão histograma com variável
contínua não fiz nenhuma variável
discreta as variações discretas que
estou usando aqui ocupação estado civil
educação é fazer uma análise tabela
cruzada usando no pacote de modo tem uma
função chamada cross table essa função
nos permite cruzar duas variáveis e traz
um formato que a gente quer se forma que
botei em dois tipos de formaturas tabela
o formato spss informados a esse formato
só quer dizer respeito com essa saída
que seja observada em baixo
a categoria que o item de uso ocupação
ela tem 12 categorias então fica uma
tabela muito fácil você ver tabela
tabela é enorme mas eu vou usar uma
variável que ela só tem duas categorias
ele fica mais fácil a gente vê a renda
variável y é uma variável deixou uma
variável não têm financiamento
imobiliário não tem a gente observa que
pessoas que não entraram deixou 5 83%
que não entendeu ou não têm
financiamento imobiliário e das que não
entendem de fogo
nós temos 90% alta de 3 mil e 16 mil
para sentar aqui desculpa a gente fala
percentual errado pra vocês
o percentual dos que é da linha somente
voltar aqui me ver o hol presente como
peça de total percentual total que a
última tá
51 por cento das pessoas que não entrem
de fogo têm financiamento imobiliário é
isso tem muito a ver no mercado
financeiro que o trabalho trabalho no
banco do brasil a gente observa bastante
que pessoas que têm financiamento
imobiliário
dificilmente atrasam algum outro tipo de
empréstimo deixou seu nome sujarem spc
ou serasa nesse sentido o próprio banco
então o financiamento imobiliário as
pessoas que têm financiamento
imobiliário em geral têm risco menor de
atrasar pagamento com bons e têm muito a
ver com a nossa cultura no nosso país
está é 36% das pessoas que tanto que não
lhe faltaram também não têm
financiamento com o banco ou seja sabe
que 88% das pessoas não entrem de fui
dos que entrarem deixou a maioria não
tem financiamento imobiliário e apenas
4% têm financiamento imobiliário
a gente tem mais a mesma relação tão se
espera que pessoas que não lhe faltaram
tempo propabilidade as pessoas que não é
também deixou aquelas pessoas que têm
financiamento imobiliário desculpa tem
problema de menor e de faltar do que
pessoas que não têm financiamento
imobiliário
isso é mais ou menos esperado só na
nossa tabela cruzadas e tem uma
expectativa que vai só confirmar ou não
o nosso modelo mas aqui já te dá alguns
indícios
eu fiz um cruzamento aqui para todas as
variáveis ou mostrei uma pra vocês no
deixei que respeita todas as outras mas
não vinho não trouxe todas elas detalhes
aqui não se a gente vai perder muito
tempo
vamos continuar nos salários até agora a
gente não entrou no modelo logístico
está a gente estava não só uma análise
descritiva anterior a modelagem
outra coisa importante que deve ser
feito é a relação entre as variáveis
explicativas e explicada
então seja calcular com o índice de
correlação entre y e todos os x seriam
as variáveis explicativas é importante a
nossa variável explicativa se tem
variáveis numéricas que a idade saldo
duração e tem a variável categórica quer
ser o y é seu irmão edson não deixou uma
categoria e não é original é uma
variável que tinha uma variável nominal
a pessoa entre de fogo ou não entender
foi com relação de variáveis contínuas
com variáveis nominais
é uma correlação que a gente chama com
relação ao ponto b serial uma relação
específica
essa correlação ele calcula da mesma
forma que a correlação de espírito de
pizza é né
é o mesmo carro só o nome e querem ficar
com a vaga no méxico é correlacionado
eles falam américa são variadas e
contínuo relação de opção direto oi dá
uma segurada que a dança balé
agora tá melhor a aí não há há há
[Música]
a cortar essa desculpa pessoal mas é
realmente a internet teve acho que o
modelo é grande a cortar um pouco
[Música]
ah ah ah bom é é e sequer tentar dar uma
iniciada no toca de the red album coisa
assim a gente pode aguardar também
porque está trabalhando muito pessoal
não está pessimista conselho nem a sua
tela mas voa voa lo o conhecer pessoas e
só para guardar um pouquinho ele já deve
estar retornando é um notebook da dell
ele já tinha até comentado que parece
que está com problema na placa de rede
por isso que às vezes ela tá com essa é
esse problema de de cair mesmo o sinal
então tá uma baixada depois volta mas às
vezes não tem muito que fazer uma mesa e
iniciou o computador quando a gente fez
um teste antes e aí ficou bem tranquilo
então acho que é só aguardar mesmo um
pouquinho que ele já deve estar voltando
beleza
segurei um minutinho que já deve está
dando uma iniciada
o picadinho
se quiserem mandando algumas dúvidas
também que que forem aparecendo é mãe
pelo chá pelo chat que o organismo modo
tudo pra ele ou no final a gente faz uma
sabatina de perguntas também se vocês
tiverem interesse
eu tô vendo gente tá
estava vendo
sim sim pega agora tá sem conectar já de
uma baladinha aqui no começo mas acha
melhor que agora antes de leandro
mineiro e dandão aceda joga tela
joguei aqui beleza foi foi
vamos lá pessoal desculpa aí a opção
mais a internet está também complicada a
net enfim acho que não só eu passo por
esse por esse problema e vamos continuar
a gente é e continuando com a análise
discutido antes mesmo de construir um
modelo após a gente deve fazer a vamos
recapitular nós devemos fazer análise
descritiva dos dados com a média mediana
moda da aliança essas características
queremos também fazer análise gráfica de
cada variável para identificar as
variáveis
existem uns testes específicos para
identificação de outline nessa base data
específica a gente trabalhando não tem
um míssil velho vocês não têm nenhum
valor faltante
então a gente não vai ter que trabalhar
um dado interessante vocês procurarem
uma informação sobre dados faltantes e
não simplesmente escolhi excluir os
dados como é normalmente feita com
relação às metas numéricas e categóricas
entre categóricas entre os médicos e
todos já fazem uma análise com relação
de todas as variáveis da base
depois ele toda essa análise descritiva
que a gente já fez até agora a gente vai
começar a construção do nosso modelo tá
então vamos começar a partir de agora
construir nosso modelo
então antes de construir um modelo nós
já vimos que nós temos 45.000 211
pessoas na nossa base de dados
hoje para construir um modelo de
regressão logística e para a gente ter
confiança nós modelo a gente não pode
construir um modelo direto em cima dessa
base de dados
nós vamos tentar fazer construir uma
mostra
nós vamos dividir nossa base de dados em
22 pedaços 70% da base da gente utilizar
para construir um modelo e outros 30%
pra gente vale da amoreira
está o seu modelo nas outras da outra
parte
então na hora que estou usando essa
informação aqui embutiu anos
eu estou pegando só na tabela bem
a variável y quando ela foi então se
separando a variar é um característica
quando avaliava y é um na tabela e
ultimas impossível separar y negócios é
tocando duas novas tabelas agora tem uma
tabela em um ano inclusive os uma
semente só para garantir a repetição da
minha mostra que eu conquistei uma
mostra a partir na parte de baixo é e
para garantir replicabilidade dela eu
crio uma semente que a partir dela não
se consegue reproduzir a sua mostra e
ela fica sendo calculada é novamente a
cada passo que sócrates nossa parte
disse apenas que a garantia de produto e
produtividade
agora nós vamos sortear uma mostra é na
mostra de tamandaré nas amostras das
pessoas que defrontarão a sede naquele
embutiu anos que só a morte das pessoas
que entrarem deixou eu vou que são cinco
mil duzentos e oitenta e nove pessoas eu
vou sortear uma mostra de 50 0 39 70%
dele
então esse pontinho anos usando a função
do tempo eu estou dizendo é o seguinte
do elemento 1 até o elemento último
elemento da tabela eo último ano ou seja
o cálculo é que o comprimento da tabela
eo último ano ou seja tinha uma 5189
pega 70% deles você vai sortear 70%
deles vai trazer então 70 65279 na
tabela de baixo usando só 10 é fazer a
mesma coisa
treinem não chamei de trainee e por
dizer o treinador também usamos o
toninho anos que eu tenho mas estou
renomeando tá eu soquei aqueles
elementos agora a ir lá na tabela e
curiosa vai pegar aqueles elementos que
eu tinha eu só tinha elementos um
elemento 0 agora os últimos da tabela
input o ano todinho aí o tato 10.1 e
depois transformar na tabela tem data
agora vou ter uma base de treinamento
esta tinha ainda
vai utilizar para contestar o modelo o
que sobrou para ser nossa área nos pés
data
nós vamos usar para testar a nossa base
de dados vamos fazer uma coisa que o fed
mantenha para que o quinto ano e voltei
- o futebol está em deus ou seja vou
pegar todos aqueles diferente do que eu
sou chique shine tanto pelos elementos
que eu não utilizei na base de
treinamento se passa é importante nós
continuamos então nossa tabela de
treinamento e nós da ted construir um
modelo nossa tabela de treinamento mas a
tabela nosso treinamento não só
construída tabela de treinamento a gente
precisa saber o seguinte nós temos quais
variáveis nós devemos utilizar é existe
uma um cálculo chamado valores de
informação que é o nosso e que calcula
essa função em v
ela te dá importância de cada uma das
variáveis para discriminar entre de vôo
e não deve faltar uma maneira de você
selecionar as variáveis que você vai
utilizar nossa modelo ao invés de você
colocar todas as variáveis e excluindo
variável avariado que não fosse
significativa
você pode antes de começar a fazer esse
modelo ver aquelas variáveis que estão
melhores para predizer o seu modelo seja
você pode calcular o valor de informação
de cada variável está a life i b e s m
bayne be nas variáveis também
separadamente as variáveis que são
fatores as variáveis que são contínuos
eu vou aguardar 90 chamada contínuos
votos
então você parar numa base mais
variáveis explicativas em variáveis
categóricas e variáveis numéricos ok
só que outro criando um vetor com o nome
de cada uma das variáveis mais tarde
espinar na tabela e vê df para fazer não
dá pra frente disso
ok onde eu vou guardar essas variáveis
quiser abrir aqui
você vai ver que tem cada uma das
variáveis estatística 4 e foi mesmo o
velho cada uma delas está zerada
é importante o início todo mundo tem a
mesma informação
agora vou pegar o trem data e dizer que
não dá pra frente isso é importante
porque a função que eu vou usar o sbs m
bairro
ela só roda treino utilizando uma matriz
é um vetor
ela não vai rodar então só posso ficar o
meu tinha data dizendo que ele é o
datafolha
ok essa função e agora a gente vai o vai
calcular ou e vai fumar há a information
velho das variadas categóricas ok
calculamos informalmente um velho dessas
variáveis categóricas agora foto também
calcular information velho das variáveis
contínuas pronto calculando simplesmente
um velho das variáveis contínuas
agora vamos colocar aquela trabalho a
quem chamou de ver df
o information velho de cada uma das
variáveis e vamos ver quais são os
informantes velho
vocês vão observar aqui em cima de cada
uma das variáveis a variável duração uma
melhor resultado anterior mais a
variação do ipca continuam antes de
informar o valor da informação de cada
uma das variáveis nos traz a você
observa cavalhada duração talvez tenha
um poder melhor explicação o peso maior
para você deverá ficar entre deixou e
não deixou e assistir silva mede quanto
é maior a importância dessa variável na
hora de você
discriminar a entre bons pagadores e
maus pagadores
então aqui já o modelo de cima de
seleção de variadas
só que a gente poderia utilizar cinco
primeiros variáveis por exemplo dá
unicamente tem poder de disseminação
maior
a gente vai usar cinco primeiros vocês
vão observar após e usar essas cinco
primeiros
o resultado é eu vou escrever aqui em
cima mode longe ti
vamos começar agora fazer a função a
regra tecnológica a função que fazer uma
regressão logística é a função de mlm
novidade gene kelly
estou lembrando que na hora que você
escreve que a optimus está utilizando
ela o pacote stacks utilizar a função
dele e eu vou querer ficar y em função
daquela vai premiar os que tiveram maior
de forma de y o tio compulsório é como
se fosse igual ea partir de agora em
diante cada uma das nossas variáveis
explicativas com um soma considerável de
mais votar dura nas cinco primeiras
somente da gente mas tem mais calmo mas
não antes
você deve informar também na gm qual
você vai utilizar a data vai usar a
tabela ainda né
estão utilizando pegar aqui ou em data
hoje começa a partir daqui o dinheiro
assim uma grande baixa é um modelo que
na prática da gentileza eu vou explicar
porque chegou nesse modelo a reforma da
função de lm informa qual é a capela ele
vai utilizar para construir um modelo
que a tabela de treinamento eu digo qual
tipo de família avalia a gente pode sair
para da família binomial e aqui eu digo
link de função ou seja se lembra que eu
falei para vocês antes do início da aula
que você tem alguns links de função tem
um link logística que está utilizando a
regressão logística
você tem um link probiti você tem um
link celog e você tem um link hoje seu
blog
como é que a gente pode saber quais
links de função existe nesse pacote
se você vir aqui escrever help função de
rn no seu canto direito
ele vai aparecer o help do pacote e aqui
aqui embaixo você tem um link de função
em algum lugar dava isso sai militar
aqui
a d link
é no limite de função
não tá aqui no jardim eu achei que
tivesse aqui e ali mas o link de função
que existe não são muitos têm disfunção
4 20 funções que esse link de função faz
basicamente lembrando uma de regressão
linear
o seu y é direto y é igual a zero mas
beta 1 x 1 mas beta 2 x 2 c para que
esse tom brady - infinita mas enfim o
link de função você pega essa variável
resposta y e você transforma ela se
lembra que a regressão logística que
está utilizando está utilizando essa
transformação aqui um sobre com mais
elevada - nyse fdx a questão y essa
transformação aqui é transformação logit
outro tipo e garante que sempre esses
números vão estar entre serginho existem
outros tipos de transformação e é
daquele tipo de link de função que você
muda esse tipo de transformação
nesse caso a gente não vai alterar o que
está fazendo uma beleza
vamos para que na hora que estou jogando
gm trabalhando com a informação do gm
dentro dessa variável chamada mobile
logit gémea guarda toda a informação do
mundo de longe ti e se eu quiser chamar
ele agora os da função citamos aqui em
baixo
um sabre mole de você vai saber todas a
produção mário modelos de regressão
como a gente vai analisar esse modelo de
emissão antes de mais nada a gente vai
ter que utilizar este canto aqui te diz
a probabilidade desse betas em que
calculou aqui deles é zero ou não ser
zero
se esse valor de probabilidade maior de
0,05 que ele está indicando que existe
uma dorzinha este beta associado a essa
variável e zon ti e lembra que o ici
última variável categórica
tóquio 22 a categoria do dia anterior
era de onde horizonte 30 categoria
quando no dia 31 cada categoria vai
aparecer assim ó horizonte 1 ela está na
própria modelo e aqui são os betas
associadas demais categorias tá vendo
variável categoria como ela aparece com
um número
isso quer dizer categoria que ela
representando se fornecedores são os
insetos ou três eu disse beto a mas se
for um desses 2011 já está no próprio
modelo então você não precisa
discriminar variável o senhor vai fazer
uma gambiarra olhe a é você tem três
categorias e faz mais danos e assim
sucessivamente tem quatro fases 3 e
assim sucessivamente a voltar aqui para
análise
se essa probabilidade foi acima de 0,05
que é o critério que normalmente utiliza
a gente considera que essa categoria que
não é capaz de discriminar entre bom ou
mau pagador que no nosso caso nós ue
trabalha na resposta
então a gente pegou cinco primeiros
variável se você observar se tem uma
categoria de melhor resort que não
discrimina tem uma categoria da avaria
no carro que não discrimina o sistema é
a variável no anti que também não
discrimina entre bom e mau pagador não
repara mesmo se utilizando aquela
information velho
mesmo assim existem variáveis que são
significativamente calculada pela
estatística da comissão velho que na
hora que você faz um modelo de gestão
logística ela não é capaz de discriminar
por isso constitui um modelo aqui de
baixo que vocês velho então esse modelo
aqui não vai ser utilizado
a gente poderia continuar utilizando a
variável duração ao horizonte com a seta
364 e só terei que recategorização vague
mas aqui eu já deixei um modelo pronto
utilizei outro
variáveis aqui vamos voltar lá pra nossa
variar nota informativa o velho
a duração parece que tem um ela é
significativa quando você rodou com o
demais variáveis civil que é bem
significativa hora do pezinho valor dela
próximo de zero
assim quanto mais tempo durar a
comunicação tá vendo como beto é
positivo maior deve ser a propriedade da
pessoa de faltar
se a campanha de marketing que foi de
oferecer crédito a pessoa interessada em
pegar o crédito talvez seja a
probabilidade maior de entrarem de fun
mas nesse essa análise serve para
qualquer outro tipo de análise não só
para a concessão de crédito está nós
podemos então utilizar variável duração
nós não vamos utilizar para os outros
porque temos categorias que não são
significativos
a variável tempo a gente viu aqui
embaixo também não é significativo
na verdade ela é significativo que a
gente pode utilizar é o temp a a
variável no anterior não é significativa
a caixa também não é fácil tirar daqui
não é uma categoria da gente mas como a
gente está preocupado com todas as
categorias aqui no momento é só uma
explicação inicial
vamos tirar ela do nosso modelo vão
utilizar próximas variáveis explicativas
seria fim ou seja se a pessoa tem
financiamento imobiliário ou não e seria
o saldo da pessoa então utilizar a
trabalhar no fim utilizando quatro
variáveis
lembre-se gente tem um critério muito
importante
o modelo de regressão se chama a tony
a idéia é linear pouco o número de bocas
seja capaz de explicar um evento neste
caso um exemplo o evento é o de som
então não preciso botar aqui seis
cristãos e vai aumentar seu r quadrado
da logística o mesmo poder de aplicação
do modelo imputando variáveis que não
são capazes de combinar muito bem e pior
o seu modelo corolla que vai implementar
esse modelo na prática você vai ter que
ter um acompanhamento desse modelo que
constantemente é a construção dessas
variáveis você vai ter construído a
implementar
não é complicada enquanto - variáveis é
mais fácil para você controlar
então sempre tem a parcimônia na hora
que você fizer modelo matemático
eu sei que hoje em dia a gente usa muito
machine lane e ea a gente bota logo faz
com que a gente fala e faz modelo na
força bruta bota tem qualquer variável e
vai excluir a medida câmera não é
significativa
isso pra construir um modelo pode ser
até bom eu não não aconselho mas pode
ser até bom construir modelos assim na
hora de implementar isso dá muito
trabalho e nem sempre é possível para
simone implementar uma organização da ok
então vamos continuar a nossa data é
vamos mudar esse modelo está tudo bem
com o qual a gente tá tudo bem onde caiu
todo mundo eu vivo há cinco assim a
beleza que estava tudo bem então vamos
continuar a gente fazer o nosso modelo
logístico tá vendo que a função é assim
só você olhar o gmm
só que após ver e rodou dnn usando a
função eu tenho uma discriminação que no
texto um pouquinho aqui acima é porque
tem dois forma de você usar previsão do
modelo também é que eu utilizei
construir um modelo na base de
treinamento e vou fazer a previsão do
modelo na base teste e nunca faça a
previsão é a mesma base que construir
existem duas formas você realizar
precisando ser modelo tem a função pelo
giz ou tem a função predict tá feliz é
saber a origem do pacote de na hora em
que você foi descrever a função aqui
pelo jeans e vai trazê-la para o pacote
está no limite vai trazer ao mesmo
pacote está eu costumo boca na frente
qual é o pacote sabe de onde nem a
função é é sempre bom se deixar cinco
menores e usa muitos pacotes é
importante saber de onde vem cada função
é pode ser que algum pacote tem funções
com o mesmo nome
isso é complicado porém tem duas formas
se você calcular previsão do seu modelo
você pode usar a função pelo des
o função preditiva eu prefiro utilizar a
opção pela gente mas eu deixei as duas
opções aqui pra você está a um cartão
que permite a usar a função pelo diz
achar prejudique dois de calcular e aqui
também usando outra função que a função
do presidente é para a gente depois que
ele que utiliza um modelo logístico ea
gente aplica na base desse teste que eu
gerei agora nessa previsão cada
indivíduo na minha base de teste e agora
tem a probabilidade de faltar mas essa
não é minha preocupação não quero saber
se o indivíduo a um problema de 0 80
necessariamente de entrarem de fogo
eu quero classificar aquele indivíduo a
é de fogo na de funk é zero é um então
você tem que utilizar um ponto de corte
uma propriedade de proibição de corte
padrão utilizado em geral é corte acima
de 0 5 ou seja se a probabilidade de um
indivíduo é ter sucesso nesse caso de
faltar com o banco foi assim vai dizer o
sim eu é o clássico aquele indivíduo em
um céu foi abaixo de 0 15 e plástico
aquele indivíduo 0 então detectar o
ponto de corte é importante para
classificar o indivíduo
outra forma de você terminar esse ponto
de corte é ideal é você utilizar essa
função é optimal crof ele otimiza o
melhor ou de corte para a sua
classificação como funciona esse
algoritmo ele vai ver aquele ponto de
corte que traz o menor erro de previsão
seria um erro de previsão eu já senti na
minha base de teste quem faltou quem não
faltou na minha base de teste eu
calculei o meu modelo previu também que
vai faltar o que não pode faltar então
vou comparar o que eu previ um que
efetivamente ocorreu
e aquele aquela relação tinha menor erro
vai ser o melhor ponto de corte esse
modelo específico essa base de idade
se você calcular isso aqui e se essa
função óptima crof militar é da
biblioteca chamada information velho ro
tá esse programa para utilizar se ela vê
que ele vai trazer o outro ótimo de
corte do ponto 1 porque realmente essa
base de dados tem que trabalhar um
pouquinho mais e melhor com um corte no
ponto zero ponto 1
mas nós vamos utilizar 1.05 mas a função
é muito boa a gente já usei ela há
diversas outras bases de idade
essa base específica que eu peguei para
risco de crédito não tinha que trabalhar
um pouquinho mais o selecionado mas um
pouco melhor
então eu não vou usar essa função para
usar o ponto de corte mas fica a dica de
usar essa função sempre que você quiser
saber qual o melhor corte para
categorizar uma variável
ok eu vou utilizar o corte de 0 5 como
pré definida em cima tá bom vamos
continuar fazendo a análise do nosso
modelo porque assim a gente definiu
agora qual é o ponto de corte
mas a gente não precisa fazer análise
nosso modelo não basta só você costuma
de logística
ele tem várias premissas e nós
precisamos seguir à china usando a
função sábado de novo modelo de cálculo
a gente vai perceber que a probabilidade
ou seja o poder discriminatório de cada
uma das variáveis repara as variáveis
que utilizam esse modelo dura temp se
tem financiamento imobiliário não tem o
saldo em conta bancária elas têm um
grande poder de explicação para prever
um de fogo não deixou do nosso nosso
cliente especificamente é para o cara
tem um financiamento imobiliário e
diminui a probabilidade de fogo uma
coisa estranha é se o cara tem um saldo
mais alto
ele tem a chance maior de não me pagar
não pagar o banco porque é positivo
porque falou no início da aula o sinal
do beta te dá uma ideia se vai aumentar
ou diminuir a chance de um cliente vir a
adquirir ou não ok vamos continuar aqui
analisa a gente viu que os betas que se
calcula todos são significativos
então a princípio parece que está muito
bom esse diagnóstico
aqui eu fiz um diagnóstico chamado teste
de rosa e michel
mas esse teste que vou fazer depois com
vocês vamos continuar na linha do samba
aqui esse teste é voltar pra vocês verem
porque eu voltar vou voltar depois
sempre que eu falei para vocês que
existem algumas premissas de uma grande
regressão logística que é muito condenar
idade
a presença ou não de antilla é quem já
viu um gráfico de boxe esporte para
identificá lo e depois tava da mostra
que a vida mostra bastante grande
a gente precisa ainda ainda assim fazer
teste de multipolaridade
por que é importante teste
multipolaridade existe mas a gente fez
aqui no cantinho dos betas elas só são
significativas
se essas variáveis não forem muito
culinários e que a multi core nariz se
uma variável explicativa não foi
altamente correlacionado com outra e
assim sucessivamente se elas forem
mutuamente com relacionadas a esses
betas calculados aqui ele tem um não são
visados ou seja valor médio deve estar
certo mas a variante é muito grande ou
seja este beta esse valor que está
utilizando aqui pode ser zero ou seja
essa regressão pode não ser
significativo
é um teste você pode aplicar sobre os
coeficientes esse teste de ver é do bife
que é velho e flecha factor que é o
bicho você calcula esse vídeo ele vai
trazer embate os valores dele também
se tiver um valor acima de 4 em geral
você considera que essas variáveis são
multi core lineares como todas as
variáveis que observou aqui está em
torno de 11 o o kotoko a eu repito então
eles não escutaram na parte se repete
[Música]
saiu do ar voltou a gente voltou a ficar
ou tossir
[Risadas]
[Música]
voltou voltou pode mandar ver pode é
porque não sei se vou ou não tava tenha
também na minha tela e tenho aqui tá
beleza gente vamos lá vamos continuar
então houve fila me dá muita qualidade
entre as variáveis explicativas valores
abaixo de 4 considero que as variáveis
não são múltiplas lineares e como a
gente pode observar que não teve uma
variável não teve muita gente não
apresentou muita qualidade nesse modelo
mas só olhar muita qualidade também é
pouco ainda a gente precisa ainda vê o
erro de classificação no modelo usar
essa função místicas classe erro ela me
dá é o erro de classificação o quanto o
clássico na base teste enquanto que eu
previ dessa variável que você vai ver
que tem 19% de erro de classificação ou
seja esse modelo de gestão logística
acertou em 80% dos casos mas quase 81
anos chegou cedo então foi tentar com 35
mas ele errou e 19% dos casos ainda tem
um erro relativamente ao então a gente
não sabe nesse modelo adequado ou não de
continuar analisando o vídeo ele disse
que o modelo é muito linear então é bom
então já é um pressuposto carvalho
a classificação tem 19% mas ainda uma
boa classificação não para risco de
crédito é bom mas não se fosse eu
tivesse trabalhado com dados da área
médica
esse erro dependendo do problema o erro
baixo
digamos que o problema seja o
medicamento ele é eficaz contra a dor de
cabeça ou não eu erro só 19% quer dizer
que 80 dos casos eficaz
então é um erro razoável outra análise
importante no modelo de operação
logística é o que a gente chama da curva
rock é essa análise é importante para
dar o poder de previsão do seu teste
aqui você é um gráfico seu canto direito
o gráfico rock e é a área ao rock área
de cana nessa área toda a baixa dessa
curva valores geoc acima de zero e
entre 0 8001 95 são valores muito bons
então esse modelo tem um valor bom tanto
e agora a gente só viu uma data viu que
o bife é bom ver o sonho de
classificação é alto porém não é tão
alto assim que o carro que deu que o
modelo é bom mas a gente ainda precisa
continuar analisando nosso modelo então
continuar na argentina calcula a
especificidade do modelo ea
sensibilidade do modelo são duas
características distintas
a sensibilidade ela está associada é
agora posso ir a confundir porque sua
sensibilidade e especificidade unta
relacionado à captura do erro ou seja se
o ciúme efetivamente é um ser o melhor
em sua especificidade seria tecido
específico meio de um predador de cabeça
ea sensibilidade é o percentual de
acerto quando saber se o cara realmente
não está com dor de cabeça e classificá
que ele não está com dor de cabeça à
especificidade é o cara tá com dor de
cabeça e tosse catarro dor de cabeça do
nosso exemplo é o classical não deixou
de forma correta como não deixou e à
diversidade seria o de fogo a ficar
exatamente como eu fui
ok é um concorrente bilidade
especificidade observa que há tanta
sensibilidade e especificidade estão
sendo razoavelmente alto 0 74 0 80
nosso modelo está aceitando bem mas
ainda não é suficiente a gente não vai
continuar fazendo análise a uma outra
análise é importante pra gente realizar
é quanto numa base de teste eu
classifiquei de bom e ruim aqui ó eu
tenho 1587 mais de 10 com deixou e
trinta e seis mil duzentos e vinte
pessoas não deixou na base teste
vamos olhar agora a nossa matriz de
confusão que é uma descompressão vai nos
dar
vai nos dar o quanto deixou observado
tem eo quanto o modelo estimou
ou seja se eu observei 1587 de fontes e
otite mail que a 77 de fonte das mesmas
classes modelo tá bom
a hora que a gente está dizendo aqui ó
eu acertei 1.189 de fogos e errei 398 de
fogo
aqui em cima é classes eram observada
esse aqui é o eu acertei o zero e aqui
eu acertei em um esse aqui é só diagonal
secundário estão seus erros está isso é
um erro de classificação do 1
você quer ouvir de classificação do zero
ok é a nossa matriz confusão vai te dar
mais ou menos o percentual de acerto é
como se fosse principal dar ok é só
somar essas duas categorias e dividido
pelo total de pessoas que tem que vai
ter um percentual de acerto da sua base
usam essa seria mais uma análise é feita
agora vamos vão interpretar nossos
coeficiente do nosso modelo está
presente em nosso museu usei essa aqui a
função hoje move ao nosso modelo
construído nessa tabela e depois vota se
for um coeficiente muita apreensão de
800 no modelo de cálculo do potencial de
cada coeficiente acaba calcular o
direito ou seja o impacto de cada
variável
ele está me dizendo aqui tá dizendo que
o aumento da duração de um minuto um
segundo do meu contato com cliente
aumenta a probabilidade de default 0,005
por cento ou seja quanto mais tempo
ficar no telefone com o meu cliente
oferecendo crédito
as chances desse cliente vira de faltar
comigo mas a observa variável finas fifa
enfim um tem financiamento imobiliário
observa que é baixo de 1 ou seja se o
cliente tem financiar e 2 ou menos 24
ou seja é a probabilidade dele é
reduzida em torno de 50
só do cara de financiamento comigo não
tem isso também faz sentido porque já
conheço melhor o cara tanto é que o
final oferecendo financiamento
imobiliário
bom é esse seria uma análise do nosso
modelo de gestão logística mas eu vou
voltar aqui atrás para trazer o nosso
teste rosa e michel se lembra que tudo
modelo está indicando que o modelo é bom
nosso teste de roger michell também é um
teste para a classificação do nosso
modelo é de uso de michel no pacote
aqui sim em novo corte e como uma grande
habilidade e sorte select esse teste
assim eu já vou deixar aqui uma
personagem determinar a saúde hoje é
separar nossa base da dis em 10 pacs ou
seja compartilhar esse jack the party
que estou fazendo e e vou testá las
vegas dez partidas - dez categorias e
modelo está classificando corretamente
olha como é que ele está dizendo que o
valor é muito baixo ou seja o modelo não
tá muito adequado quando eu olho ele em
percentis e não quando eu olho no geral
é para que toda a nossa conclusão até
agora está fazendo o modelo era muito
bom né
mas na hora que a gente foi olhar o
vacilo e michel também que o modelo não
é tão bom
olha só a característica do regime
ambiental isso aqui é o y 0 y é
observado o y r 70 eo ratinho é o meu
estimado
ou seja eu observe 704 pessoas quando a
probabilidade é classificada de 05 10 11
e modelo estava estimada em 684 tinham
37 de falls e modelo está estimando 66
de shows
então esse aqui é o conteúdo serviço é
contra este e mail se observa que tem
uma distância muito grande eu tô dizendo
tem mais de fogo e observando também
então o teste nós mesmos e chávez se
subdivide em sua base em idéias de
percentis e olha em cada um dos
presentes um acerto nele a gente pode
perceber que existem precedentes que
nosso modelo não está muito bem ajustado
mas existem outros recentes como o
percentil aqui em cima e parece que está
um pouco assustada o nosso modelo
então a gente tem que ter muito cuidado
a gente tem que fazer análise acima de
análise nosso modelo estava dedicando
até então que o modelo muito bom
ajustado com o percentual de rock 0 85
observa que a gente faz um teste mais
detalhado mais específico a gente vê que
pode ter muitas melhoras ainda não poder
essa função zinho aqui que eu fiz é que
o partido em 10 partes mas não podia
partilhar em 5 a 15 partidas fiz uma
função eu fui calculando o preço valor
de cada uma das partes à nação a partir
do momento que eu fiz essa parte será em
5 e técnicas fica significativo observa
que mesmo passando de 5 a 15
o teste oslo inicial continua me dizendo
que esse modelo é pobre que ele pode ser
aperfeiçoado
então gente fiz um modelo de regressão
logística com você pra estimado de fundo
os nossos clientes ou de clientes
bancários é uma base aberta e trouxe um
exemplo que parecia que o modelo era
adequado até o final mas a gente pode
observar que com mais detalhe que a
gente pode melhorar esse modelo ou seja
você pode trabalhar melhor essas bases
pode fazer uma análise de componentes
principais para categorizar variáveis
antes e pode pegar as variáveis
numéricas e recategorizada ela com o
atlético tem várias outras maneiras de
você trabalhar essa habilidade para
melhorar esse modelo se você quiser
continuar usando a regressão logística
você pode partir para um ano forte para
uma resposta vetorial outras técnicas de
inteligência artificial de washington
são basicamente técnicas estatísticas
atrás de todo esse método não são
métodos estatísticos
era isso que eu tinha pra trazer para
vocês espero que tenha aproveitado foi
meu login um pouco nessa 96 tal prazo tá
na hora certinha
se alguém quiser acompanhar a gente a
nosso site é www.pontofrio.com.br lá a
gente vai ter o nosso blog eu vou botar
essa aula no blog eu vou escrever melhor
votar o código no nosso blog você pode
se cadastrar no site que semanalmente
vai ter novas notícias no blog não tem
códigos nosso blog disponível teve como
eles gravados pra vocês vão fazer outras
unidades também com o cotidiano e da
nossa empresa também nós temos recursos
disponíveis para quem aqui de brasília é
a gente também tem pretensão de levar
esse curso para o rio para são paulo
temos diversos cursos que são alguns
cursos que a gente está em catálogo
agora vão ter cursos online quem quiser
seguir a gente também vão ter coisas de
graça vou dar treinamento de graças vão
lá ea blog é isso aí galera espero que
tenha gostado foi um prazer é só tirar
aqui na tela prazer é isso aí
obrigado obrigado cotidiano para essa
parceria a gente tá é no próximo apesar
de novo é isso aí gente tiver perguntas
do tipo a nível pessoal aqui agradecendo
bem é que nem é saber se depois fica
gravado de dinheiro e depois de acesso à
serra
eu posso lançar o canal também depois
ele pode escolher o canal dele também
mas todos os galhos potencial nele ficam
no nosso canal todo o conteúdo anterior
também muita coisa do que a gente
utiliza na aceleração inclusive fica lá
pra quem tem interesse conteúdos mas é
empreendedorismo e o ex não tem muita
coisa nacional ea gente possa sempre é
fomentando o conteúdo referente ó o
desenvolvimento do empreendedorismo
startup aí e beleza
agora a gente tem um bico de até 60
pessoas ao mesmo tempo que peço
desculpas pela pela conexão realmente
estamos progredindo no meio mas acho que
acabou interferindo tanto e ele ele vai
quem quiser tirar alguma dúvida também
deixou e meio dele no começo de 2011 e
mail dele e se alguém precisar dos
slides também o coração está tudo mudado
isso pode falar com o bruno pra você os
slides do programa tudo base da dívida
não quitada cotidiano de prejuízo no
site também se quiser avançar nem pra
mim me pedindo o passo no caminho para
ir pessoalmente à beleza
o nível aqui mesmo eu tinha a opção da
mídia pela galera encerrada