# Lesson 1 - Relational Database - SQL for Data Strategy

- **URL:** https://www.youtube.com/watch?v=jLFwWmsu2F8
- **ID:** jLFwWmsu2F8

## Transcrição

Olá,
pessoal, tudo bem? Vamos dar início na
nossa aula dois, tá bom? Vamos ver como
é que essa aula ela foi organizada, tá?
Para ela não ficar muito extensa, tá?
Porque aqui tem bastante assuntos a
gente estar falando.
Quebrei ali em três etapas onde nós
vamos começar falando sobre a definição
de database
e depois nós vamos começar a navegar um
pouco no nosso database relacional.
Vamos ver o conceito de instância, como
que ela
ajuda na organização dos objetos dentro
do SQL Server.
Vamos fazer a criação de um database.
Vamos ver como é que a gente pode fazer
para excluir. Vamos ver a questões de
permissão, né? Por exemplo, qualquer
usuário pode criar um banco de dados?
Não, não pode. Não é qualquer um. Tem um
tipo de permissão que a pessoa pode ter,
tá? OK. Vamos ver na etapa dois, rotina
de manutenção, né? Algumas delas, tá?
Nós vamos falar principalmente nesse
momento sobre backup, resistório, os
tipos de backup, tá? E depois vamos
também dar uma olhada assim superficial
sobre a arquitetura do SL server para
conhecer os databas de sistema, tá bom?
Vamos lá,
vamos iniciar a etapa um. Então, vamos
lá. Caiu na tua prova essa seguinte
pergunta: o que é um database? Aí você
pensou assim: "Ah, tá, um database é um
sistema organizado para armazenar,
gerenciar e recuperar informações de
forma eficiente."
Aí o professor falou assim: "Pô, muito
bem, poxa essa sua definição, porque se
você olhar por um outro olhar, né, você
vai falar assim: "Ah, tá, eu tenho
informações de cliente, informações de
vendedor, produto, loja, forma de
pagamento, venda. Como que eu armazeno?
como é que eu gerencio e como é que eu
retorno essa informação quando eu
precisar. Por exemplo, seu gestor chegou
e falou assim: "Gabriel, eu preciso
saber, preciso de um relatório de venda
da loja do Shop XPTO.
Beleza? Eu sei quais são as tabelas, sei
que as informações elas ficam
armazenadas dentro de tabelas. Então eu
vou lá, consulto,
beleza? consiga entregar esse relatório.
Agora imagina que você não tivesse esse
relatório.
Todos esses objetos que eu te falei no
seu universo,
eles estariam armazenados também de em
forma de arquivos,
onde o gerenciamento não é simples e a
recuperação dessas informações também
não é nada simples. Imagine que você tem
um Excel para cada informação dessa e
você precisa montar um relatório.
Quantos pro V você vai ter que fazer
para entregar esse relatório? Ao ponto
que dentro de um banco de dados essa
informação ela é muito simples de ser
manipulada. Tá bom? Agora, segunda
pergunta da tua prova, quais são os
tipos de database? Aí você pensou e
falou assim: "Ah, tá, são dois tipos, os
databases relacionais
e os databases não relacionais, onde os
relacionais é onde os meus dados estão
armazenados nesse cenário que eu acabei
de falar com você, né? Eu armazeno tudo
dentro de tabelas.
Essas tabelas elas possuem linhas e
possuem colunas. outras informações a
gente vai abordar no tópico mais à
frente quando a gente estiver falando
sobre tabelas, tá bom? Agora, quando a
gente já olha para um banco de dados no
cicle,
esses arquivos, ou melhor, essas
informações, elas não estão
eh
muito arrumadinhos, porque os formatos
eles são flexíveis. E a tipagem ela não
é feita, então assim, é bem diferente de
um relacional. Então esse ponto a gente
vai ver um pouco mais à frente, tá bom?
Vamos focar nesse momento num database
relacional, tá? OK. Agora eu queria
falar para com você sobre
como funciona, né, essa nossa,
digamos assim, organização, né, como é
que o nosso database relacional ele
organiza essas informações, tá?
Vamos olhar para essa
para essa imagem que eu vou trazer aqui
agora,
onde a gente vai falar um pouco sobre
alguns objetos do nosso SQL C, tá? OK.
Então, pensando assim naquele primeiro
tópico que tem ali na nossa
apresentação, é o quê? A nossa
instância, tá? Mas o que que é uma
instância dentro de universo do SQL
Server? Uma instância você pode associar
como uma instalação.
Então você tem o seu servidor e você
pegou o software do SCAD Server e fez a
instalação desse seu servidor. No
momento que você faz a instalação, que
que você fez? Você automaticamente
já
criou uma instância.
Tá bom? Aí, beleza. Eh, depois que você
cria a sua instância, você tem outros
dois níveis,
eh, que eles diferem
um pouco,
eh, digamos assim,
do nosso universo de outros database,
que é o quê? No SK Server a gente tem o
conceito de login,
tá? E a gente tem o conceito de usuário.
Login é o quê? Login é isso aqui.
Você
loga na instância. Isso aqui é uma
instância.
Então, quando você informa o nome do
servidor,
né, barra e na verdade contra barra e a
instância,
isso aqui você logou no seu servidor,
tá? Você tá apto a acessar um database?
Não, para você acessar um database,
você precisa ter isso aqui.
Você precisa ter um usuário, tá?
Aí entra naquele ponto que a gente
estava falando, as permissões,
tá? Eu posso liberar a sua permissão
para você acessar
o database
ou eu posso liberar
a sua permissão.
Desculpa. Aqui você acessa a nível de
database e aqui você acessa a nível de
servidor, tá? é um pouco diferente. Aqui
eu vou conceder permissões para você, ó,
dentro de um banco de dados específico.
Aqui eu tô liberando a sua permissão
aqui, ó, onde eu crio para você, ó, eu
tô liberando a sua permissão nesse
carinha aqui, ó, na sua na nossa
instância. Então, por isso que a gente
fala que é uma permissão a nível de
servidor, tá? Aí, beleza? você quando já
tem a permissão
eh para acessar
o database, né, você já tem um login que
você acessa
o servidor. Aí você pegou, criou um
usuário e associou esse usuário a um
login. Aí eu falei assim: "Agora eu vou
liberar pro Gabriel o acesso ao quê? a
um database, porque ele já tem um
usuário. Então, eu primeiro crio o login
e depois eu vinculo o login a um usuário
e
associo uma permissão. Essa permissão
ela pode ser a nível de servidor ou pode
ser nível de database, tá? OK. Aí aqui
entra algumas informações que eu vou
tava falando para vocês. Quando nós
falamos sobre o conceito de database,
que que nós falamos aqui? é um sistema
organizado para armazenar.
Beleza? O armazenamento tá aqui. Então,
quando você cria
esse rapazinho aqui,
você automaticamente fala: "Ó, ele vai
tá nesse local". Então, quando a gente
acessar esse diretório,
você vai tá fazendo o quê? Você vai est
acessando as informações
do banco. Não, você não vai est
acessando informações. Você vai est
fazendo o quê? Você vai est definindo
onde que os dados vão estar sendo
salvos, tá? OK. Aí quando a gente entra
no database a gente tem a seguinte
informação. A gente tem um esquema,
não é nada mais nada menos do que uma
forma da gente organizar
os nossos objetos dentro do nosso banco
de dados. Aí depois entra o conjunto de
objetos. Esse conjunto aqui ele é até
maior, tá? Opa, esqueci o índice de for
aqui.
Então, esse conjunto ele é até maior. Eu
só trouxe alguns objetos para cá, tá?
Então, como é que a gente organiza as
nossas informações dentro de um banco de
dados SQL Server? Essa organização, ela
vem servidor,
instância, database e esquema. É uma
escadinha, né? Servidor. Opa, ficou
muito grande. Servidor
instância
database
e esquema, ó. Servidor,
instância,
database
e esquema. Aí aqui dentro do esquema a
gente tem todos os objetos. Isso é, por
exemplo, para ficar mais fácil para você
entender, pensa da seguinte forma. Você
tem um único database, tá?
Onde esse database
eh possui
dados, né? dados,
tabelas
que pertencem ao RH, a gente tem tabelas
que pertencem ao financeiro, a gente tem
o tabelas que pertencem ao time de
supply, tabelas que pertencem ao time de
suprimentos. Como é que eu organizo isso
para isso não ficar tudo misturado? Como
é que eu vou saber de forma rápida e
precisa quais são as tabelas do RH?
Aí você vai me falar assim: "Ah, beleza,
eu posso criar a tabela começando com
setor, por exemplo, RH_line, alguma
coisa ou TB_line RH, TB_line supply,
beleza? Pode fazer dessa forma. Só que o
esquema ele foi feito pra gente também,
porque além dele auxiliar na
organização, ele vai ajudar também na
questão da permissão. Não vou entrar
muito nesse assunto porque nós vamos ter
um tópico só para abordar a questão dos
esquemas, tá? E a gente finaliza essa
parte aqui falando o quê? falando sobre
algumas rotinas que a gente pode estar
criando dentro do nosso database, que
são os jobs. E a gente pode criar, por
exemplo, um job para executar uma
procory, para enviar uma notificação,
para fazer uma rotina de manutenção e
por aí vai, tá? OK. Agora vamos voltar
para cá
na nossa apresentação aqui. Vamos lá ver
aqui, ó, instância. Beleza, falamos.
Agora, como é que a gente cria o nosso
database? Tá aqui a gente tem duas
formas de fazer isso. Já tenho o script
pronto aqui que eu trouxe para auxiliar.
Na verdade, vou abrir até
até aqui
o roteiro. Eu botei um arquivinho aqui
de roteiro pra gente saber eh como é que
nós vamos caminhar, tá? Então vamos ver
aqui o roteiro. Primeiro é o quê? Vamos
falar sobre a criação, tá? Eh, a gente
tem duas formas
de criar o nosso database. Pode ser
três, porque você pode falar assim, eu
posso restaurar um backup e tal, beleza?
Vamos dizer que são apenas duas, tá? OK.
A forma mais simples, eu coloquei aqui,
que que é isso, né? Forma mais simples é
esse script aqui, ó. Olha como é que é
simples.
Create database e você dá o nome do seu
database. Se eu pego isso daqui e
executo,
clico aqui em cima de database e no
botão atualizar, tá lá o database foi
criado. Ele é simples. Por quê? Porque
que eu coloquei
o nosso roteiro, né? aqui,
criação simples. Ele é simples pelo fato
de que só teve a necessidade de passar
eh uma única linha.
Não concorda que é simples? Agora
imagina se você tivesse
que fazer um script desse daqui para
criar o banco de dados.
Tem nada simples, né? Então, o que que
acontece? Como é que
que eu crio esse script? Ah, Gabriel,
foi você que que digitou tudo isso? Não,
não foi eu que criei.
Eu gerei esse script a partir de um
banco de dados criado, ou seja, desse
nosso script simples.
Eu fiz, eu cliquei, eu vim aqui no meu
canto esquerdo, tá? database. Peguei o
database que eu acabei de criar, cliquei
com o botão direito dele,
escolhi a opção script database as
create tool e definir o que para ele.
Abre uma janela nova para mim com
script. Mas eu também poderia falar para
ele, ó, gera salva esse script para mim
dentro de um arquivo. Ele vai falar
assim, pô, beleza, de boa. Mas não, eu
cheguei aqui e falei para ele: "Abre
aí".
Aí ele falou assim: "Ih, deu ruim". Por
que que ele deu ruim aqui? Ah, tá.
É porque
vamos ver aqui o que que ele fez.
Vamos ver aqui o que que tá acontecendo.
Tá beleza.
Tem que cortar esse pedaço.
Então, como é que eu faço para poder
gerar aquele script? Eu clico aqui com o
botão direito,
create
é script database s create to e clico
aqui para ele poder gerar e aquele
script ele é gerado pra gente, tá?
Então assim, aqui eu tenho o script
simples que eu só digito create
database.
Eu posso criar um database a partir de
um script. E como é que eu faço para
excluir o meu database? Pô, é difícil
excluir um database. Vamos ver.
Eu posso chegar aqui, ó.
Drop database.
Vamos clicar aqui no drop database.
Vamos ver se ele vai funcionar.
Provavelmente, como ele tá executando
assim muito tempo, ele tá encontrando
alguma conexão aberta. Provavelmente. Ó,
ele deu erro, ó. Eu não posso gerar
por
porque eu tenho
uma conexão, tá vendo aqui, ó? Em uso.
Aí, que que a gente faz aqui? Tá, eu
posso simplesmente
clicar com o botão direito no database
e gerar o script de drop. Só que quando
eu faço isso, ele vai gerar o mesmo
script que tem lá.
Uma outra forma que eu posso estar
fazendo para escolir também, por
exemplo, clicar no botão direito, clicar
em cima do database,
delete
e clicar aqui em OK. Repara que ele vai
apresentar o mesmo erro
que gerou no na outra execução de
delite, tá? Aí nós vamos ver como que
nós vamos contornar esse problema, tá
bom?
Ele vai executar um pouquinho, ó. você
clicar aqui, ó, em cima da mensagem, ele
vai falar a mesma coisa, ó, porque ele
tá em uso. Que que a gente pode fazer? A
gente vem aqui, ó, e clica nessa nessa
opção aqui, ó, close exist.
Aqui eu tenho duas opções. Eu posso
gerar,
eu posso mandar o comando pelo OK, basta
clicar no OK. Eu posso clicar aqui, ó,
no script. Vamos ver o que que ele vai
fazer. Olha o que que ele tá fazendo
aqui. Ele ao antes de executar o comando
drop, que que ele vai fazer? Ele vai
trocar
a configuração do nosso banco de dados.
Quando ele faz isso, quando ele joga
para single user, ele fecha todas as
conexões que estão em aberta. Então, a
gente pode executar por aqui. Vamos
executar esse comando por aqui.
Tá vendo? Ele foi.
Vamos clicar aqui em database. Vamos
matualizar. Ó, o nosso database foi
eliminado. Da mesma forma que a gente
poderia estar fazendo, clicando aqui no
botão OK. e ele estaria fechando todas
as conexões e eliminando eh os o nosso
database. Hum. Atente-se para essa opção
que tem aqui, ó. Delete backup
restor restor, que que ele vai tá
fazendo aqui? Se você deixar isso aqui
marcado e mandar eliminar
o seu arquivo, todos os backups desse
database que estiverem armazenados no
seu no seu servidor, ele vai apagar
também, tá? Então, presta muita atenção
com isso daqui.
Vamos voltar aqui na nossa apresentação.
Então, ó, nós já vimos o conceito de
instância, já vimos as duas formas de
criar o nosso database, tá? Já vimos
como é possível excluir e agora a
questão da permissão, tá? Vamos fechar
essa janela daqui,
essa aqui também que tá aberta
e vou abrir esse script daqui.
Que que eu vou tá fazendo aqui?
Eu vou criar um usuário, né? Como eu
falei para você, eu crio primeiro, vamos
voltar lá na nossa telinha aqui, ó. Eu
crio primeiro o login,
tá?
E depois
associo a um usuário. Eu crio um usuário
para o login XPTO. Então, tá vendo?
Primeiro o login, depois o usuário.
Então, vamos lá. Só que aqui, olha o que
que ele tá fazendo. Ele tá
criando esse usuário
dentro do database.
Como nós eliminamos o nosso banco, ele
vai dar erro, tá? Então o que que eu vou
fazer aqui? Eu vou voltar aqui no nosso
script, vou recriar o nosso banco, ele
vai aparecer aqui novamente,
tá? Vou voltar pro nosso script de
usuário. Agora aqui tem um ponto
importante que eu pulei. Quando eu crio
o login, o login ele tem sempre que ser
criado no database master, tá? Já o
usuário
você associa dentro do banco de dados
que você quer permitir o acesso, tá?
Então, primeiro eu vou fazer o quê? Vou
marcar isso aqui tudo e vou mandar
executar.
Ele foi e criou o meu usuário. Então, se
eu clico aqui, ó,
desculpa, ele criou o meu login. Então,
se eu pego aqui
e atualizo,
o meu usuário ele tá criado,
tá vendo? Ele ele não tem permissão de
servidor e ele também não tá associado a
nenhum banco de dados. Agora, o que que
eu vou fazer aqui embaixo? Eu vou
associar
esse meu usuário ao login dentro desse
banco de dados.
Eu vou executar aqui, ó. Beleza? Agora,
se eu voltar aqui nesse cara, quando eu
clicar aqui em usernaps, ó, ele já
associou o usuário para esse banco de
dados. Mas tem esse ponto mega
importante
diferente. Vou clicar aqui
para garantir que a gente tá nesse
database, tá? E aqui, repara o seguinte,
ele não tem nenhuma permissão no meu
banco. Então assim,
eu só coloquei o usuário dele lá, mas
ele não tem permissão para nada, tá? OK.
Então aqui, que que eu vou fazer? Eu vou
pegar esse outro script aqui e vou
conceder uma permissão para ele. O que
que eu tô fazendo aqui? Eu tô permitindo
que ele crie banco de dados.
Então, por exemplo, quando eu executar
esse script aqui e retornar aqui no
usuário,
repara que aqui eu não tenho essa
permissão
DB Creator. Eu vou ter essa permissão
onde? A nível de servidor.
Então, o que que eu faço aqui, ó? Vou
pegar esse daqui
e vou executar. Quando eu retorno aqui
nele e clico aqui no server holes, ele
já tem o quê? Ele já tem a permissão de
criar um banco de dados. Então eu
concedi para ele nesse momento autonomia
para ele criar qualquer banco de dados
dentro da minha instância,
tá? OK.
Então pessoal, para finalizar, eu trago
para vocês as versões que nós temos hoje
no SQL Server, tá? Então assim, a gente
tem a Enterprise, é a versão mais
completa, tá? E aqui a gente tem uma
versão gratuita.
Ah, detalhe, ela é a mais completa,
mas ela também é a mais
cara de todas, tá? E eu tenho a
developer que ela é idêntica
Enterprise, tá? Ó, possui todos os
recursos da Enterprise, porém
desenvolvimento e teste não pode ir para
ambiente de produção, tá? Então, se você
quiser baixar no site da Microsoft
uma versão completa para você testar na
tua máquina, você pode baixar developer,
tá? Tem Express, que ela é bem levinha,
com poucos recursos e com muitas
limitações. Tem a standar que a maioria
das empresas usam, tá? Nem todas rodam
na Enterprise porque ela é muito cara,
tá? Quando a gente fala da web, a gente
tem lá na EUR, tá? Você pode estar
usando ela dentro da nuvem da Microsoft
como uma plataforma,
tá? OK. Eh, então
já entramos na nossa etapa mão na massa
e por hoje finalizamos aqui a nossa
primeira etapa. Vamos iniciar em poucos
segundos a etapa dois.
Então, pessoal, encerramos aqui a nossa
etapa um, tá? OK.
Conto vocês na próxima. M.