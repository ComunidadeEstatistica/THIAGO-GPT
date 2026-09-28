# Point and click graphs (Drag and drop) - esquisse R - Prof. Antônio C. da Silva

- **URL:** https://www.youtube.com/watch?v=KXoy005kYls
- **ID:** KXoy005kYls

## Transcrição

olá pessoal aqui fala junho
primeiramente eu quero agradecer ao
teatro pelo convite e dizer que é uma
satisfação poder compartilhar um pouco
do que aprendi com vocês
bom então vamos começar hoje pote 2
é o principal pacote do e para a
visualização de dados
ele foi desenvolvido com base na
gramática dos gráficos inclusive quem
nunca ouviu falar
acho que vale a pena pesquisar um
pouquinho sobre o assunto é no entanto
por mais que o gecoc dois têm uma
sintaxe fácil de compreender
ela é um pouco nervosa o que faz levar
um tempinho até o usuário conseguir
pegar fluência com a sentar se e isso às
vezes complica a vida do pessoal menos
experiente já que é bem chato ficar toda
hora pesquisando como montar um gráfico
de expressão como mudar a cor de uma
linha como colocar um título no meio da
nossa análise né
isso quebra é a um pouco a linha de
raciocínio
então pensando nisso o tema desse vídeo
é falar de um recurso bem bacana do r
que tem um como intuito de agilizar o
processo de criação de gráficos do
geipot 2 e esse recurso é o pacote iscsi
que a gente está aqui na página da
documentação dele inclusive essa aqui é
a url
quem quiser acessar fique à vontade
então a proposta do esqui se conforme a
própria documentação diz é permitir que
a gente escolhe os dados rapidamente
para extrair informações ela foca nessa
idade né
só que ela alerta que só é possível
criar os gráficos mais simples é que não
é possível por exemplo criar escolas
personalizadas um fazer uso de todo o
poder do getafe 2
mas a gente já vai ver isso com mais
detalhes mas de forma mais prática
tá é uma curiosidade é que a palavra e
disse que se ela tem origem francesa e
significa esboço e se a gente for
comparar o logo do esqui se como o do
jean todt dois a gente vê que a idéia do
lobo também
é ser um esboço do logo do geipot 2 e no
final das contas na prática um esqui se
ele também pode ser utilizado como um
esboço do geipot 2 como assim é por mais
que lewis que se não permita o uso de
todo o poder do geipot 2
então quando você tem a necessidade de
criar um gráfico com mais elaborado mais
complexo e você precisa de tempo
você pode agilizar esse processo criando
toda a estrutura no esqui se a parte
mais nervosa você vai criar e arrastando
e soltando mas quis o iscte permite
exportar o código ea partir desse código
exportado você implementa os detalhes
que você precisa né então isso acaba
sendo bastante interessante também para
o pessoal mais experiente não só para os
iniciantes
então um é bom começar essa aqui só
dando uma prévia é a página do da
documentação do dois que se tem aqui
informações de como fazer a inflação e
tem o que fizemos aqui dando alguns
detalhes como inicial iscsi é a gente
vai ver isso é é a eu já ia esquecendo
se você utiliza o mec pode ser que seja
necessário utilizar é instalar o ex
participar
então fique atento a isso na hora de
fazer é o uso 2 15 ele reclamar
pode ser que a causa seja a falta da 2
do ex corde está instalado beleza é
então vamo traz estúdio é aqui no
estúdio inclusive coloquei aqui os links
eu vou disponibilizar esse script com
vocês também através do it web
vou começar então esse aqui é o comando
do conforto a documentação um comando
padrão do rp a instalação de pacotes
então eu comentei aqui porque eu não vou
fazer instalação já que ele já está
instalado na minha máquina mas faça a
instalação caso ainda não tenha feito
beleza e o comando leiber a gente
carrega o skis beleza então para inicial
skis
existem algumas formas né é é por
exemplo a mais simples de todas para
quem precisa de agilidade não quer ditar
nenhuma linha de código é vir aqui no
menu do estúdio e chamá aqui
o gg pote 2 builder beleza uma vez que a
gente chama o o o comando para iniciar
às 15 m aqui essa essa interface
vou fechar aqui sempre festa no couto
não vem assistindo aqui pra não dar nem
conflito
ok beleza então por padrão o esc se abre
essa interface que a gente pode ver mas
você pode preferir abril iscsi no seu
navegador
ok então basta passar na função esquecer
esse argumento aqui passando ele vai
abrir o navegador beleza mesma coisa tá
aqui fechando aos poucos voltando lá ou
eu posso abrir o esqui se aqui nada viu
e do estúdio pra mim não faz muito
sentido isso é porque a minha tela é
pequenininha mas talvez pra você faça
então fica aí a dica se quiser abrir
mais 15 directo aqui no navio beleza ou
fechar aqui sempre no colo e também
através de do domino da função options é
possível definir um padrão é de onde é
que se vai abrir né
o padrão é aqui é a opção da alog ok
beleza mas a gente poderia utilizar a
opção pm como exemplo que é pra abrir a
aba viu a opção browser para abrir o
navegador aqui eu gosto de abrir um
navegador porque eu acho que a definição
fica mais mais bonita
então vou executar um óptimo agora toda
vez que eu chamar
sykes tanto pelo menu como por linha de
comando ele vai abrir um navegador
então tá uma vez que eu chamei os 15 e
não passei como argumento nenhum batata
7
ele abre nessa telinha aqui é de seleção
de data 7
só que quando eu não tenho nenhum da
frança encarregado de memória eliminar
como opções
alguns data 7 do próprio getafe 2 mas eu
vou mostrar pra vocês então como
trabalhar com data 7 específico e não
com esses aqui o team fechado que então
por exemplo eu vou carregar o que lhes
aparece aqui no meio ambiente está no
comando
o que aconteceu aqui ele apareceu aqui
pra gente tá uma vez que sendo que o
selecionou eles algumas informações aqui
por exemplo que foi carregado com
sucesso
as observações conta as variáveis têm a
selecionar algumas variáveis não quiser
contar com essa com essa ele pode tirar
o meu da minha análise ele traz aqui uma
legenda é do tipo de variáveis discreta
contínua tempo a id
ele também permite a fazer alterações de
tipo nas variáveis também em ti
selecionar variável piscina pra qual
tipo a gente quer converter e executa
ok mas eu vou voltar lá ainda deixou
fechar aqui porque existe uma outra
forma de carregar o esc se é passando
como argumento o o nome do meu data 7
beleza então poderia que pegar executar
ele já vem direto
que tá não tá só aquela tela de seleção
de de variáveis aquela terra legal pra
caso você queira fazer uma conversão de
tipo eliminar uma variável né e se eu
tiver mais de 1 da séti carregado por
exemplo fazer aqui só pra fazer uma
brincadeira com vocês eu poderia ter um
outro a 7
eu não me lembro quais as espécies a
gente tem um deles
então tá
vou pegar aqui a beleza criei aqui um
outro o outro data frame vamos chamá-la
o exquis aqui ele aparece tudo que eu
tenho memória beleza então isso aqui é
interessante também você tem a opção de
selecionar e fazer algumas customizações
no da set antes de começar a trabalhar
com ele
beleza então vamos colocar nossa agora
aqui chamar aqui o 15 como íris beleza
pra mim
se a gente observar é temos quatro
variáveis contínuas e uma categórica tá
até voltar lá conferir a beleza tac ou
quatro variáveis numéricas contínuo e
uma variável categórica então a cor da
legenda é interessante também na hora de
fazer a sua análise na anp é fácil 2 15
beleza então vou começar arrastando uma
variável contínua para o eixo x então
automaticamente o esqui se entendeu que
com esse tipo de dado a melhor
visualização histograma
também funciona é sugerindo a melhor
visualização para o para o tipo de dado
que você tem no momento
né mas eu também não fiquei trabalhando
nisso eu poderia vir aqui e escolher
apresenta um gráfico de intensidade tal
mas eu vou falar num o histograma então
tá
uma vez que você tem um determinado lote
na tela
no menu opções você pode customizar
algumas coisas específicas com o tipo do
gato por exemplo é um programa possa
aumentar ou diminuir o número de linces
por exemplo tá
depois do vídeo não ficar muito extenso
de uma explorada e mas enfim a idéia
aqui poderia mudar a cor aqui por
exemplo a idéia é que no gp pode você
teria que ficar digitando códigos né e
se você não tem tanta afinidade que tem
para pesquisar ou se você tem pressa
você quer não quer interromper sua linha
de raciocínio então pode ser uma boa
utilizar pesquise aqui
é aqui em data que poderia fazer filtros
nota 7 então posso aqui um range posso
eliminar alguma espécie específica enfim
é opção de fazer filtros novela das sete
ok então eu poderia por exemplo arrastar
uma outra variável contínua para o eixo
y e ele automaticamente aqui plantou um
gráfico de dispersão tá eu poderia
escolher um outro tipo por exemplo aqui
ó
esse objetivo aqui mas vamos voltar pro
gráfico de dispersão tá então no menu
aqui eu posso aumentar o tamanho dos
pontos
eu posso alterar a cor eu posso
adicionar eu possa adicionar uma curva
não paramétrica enfim opções específicas
do gráfico de dispersão
ok eu poderia
bem agrupá uma espécie então
arrastando-a que a variável espécie para
o grupo é uma variável categórica ele o
grupo aqui o meu gráfico pela pela
espécie na da flor é o poderia também
talvez de agrupar eu poderia criar
facetas é então ele criou três concelhos
aqui baseada nas espécies que a gente
tem
em outra nota 7 a não está legal não
conseguimos ver aqui onde termina onde
começa vamos mudar o tema como aquele
tema por exemplo clássico do gp lote
então agora ficou de forma mais clara ou
seja tudo isso aqui a gente fez apenas
arrastando e soltando sem perder tempo
com com digitação de código e poderia
também arrasta uma variável contínua
para o bloco sai citam os pontos
começaram a acompanhar porporcionalmente
o tamanho o tamanho dos pontos começou a
acompanhar proporcionalmente o valor da
variável que eu adicionei box size
enfim tem muita opção legal é muito
bacana é explorar toda essa facilidade
do esse que se a gente pode por exemplo
trabalhar
poderia por exemplo
enfim pra cá uma variável categórica
para o eixo x e eu tenho aqui um gráfico
de barras é é um poderia arrastar uma
variável contínua para o eixo y e ele
automaticamente se transformou num
gráfico boxe lote a mas eu não quero
blogspot eu quero um outro tipo qualquer
aqui eu quero voltar pro na barra
então na verdade ele vira um gráfico de
coluna
gilot 2 o gráfico de base ele faz
contagem de observações e o gráfico de
colunas você tem um eixo y o valor que
mostrou que vai refletir o tamanho de
cada barra tá então vamos voltar lá pro
troubles plot a gente criou um bom
esporte aqui eu poderia arrastar a
espécie para o bloco com um fio e com
isso as cores foram tocadas em função da
espécie da variável categórica que eu
arrastei poderia alterar por exemplo
aqui a paleta um presente
enfim é uma série de de customizações
que a gente pode fazer é de forma bem
prática e ganhar bastante tempo aí na
nossa análise aqui nesse primeiro menu a
gente pode e colocar o título né
[Música]
então ele já está montando aqui pra
gente a nossa nossa customização posso
da rosa do eixo x exemplo né eu posso
fazer uma série de de customizações aqui
por exemplo
enfim aqui fica a seu critério explorar
a funcionalidade estourar tudo o que ele
tem para oferecer mas é bem claro que
não têm muita dificuldade basicamente é
arrastar e soltar e experimentar algumas
coisas aqui o mais legal de tudo é que
deixei para o final é que ele dá o
código do g pode depois pra você copiar
certo qual é a opção de exportar também
há o gráfico mas enfim foi aquilo que eu
falei no começo do vídeo
você pode copiar esse código celebra o
seu estúdio por exemplo
jogar aqui e se a gente voltar à quadra
fez uma bobagem porque eu não encerrei o
resquício da forma correta agora ele vai
a óbvio que eu não carreguei decote 21
carregamento aí e agora vamos executar
novamente beleza aqui meu gráfico show
de bola
vamos dar um zoom aqui então a gente viu
que através do 112
se a gente consegue exportar o código e
trabalhar depois aqui no meu ano na
nossa e enfim colocando implementando o
que a gente deseja por exemplo há
inclusive se você tiver um teve algum
problema com o erro na hora de plantar
em função dessa função aqui é pode ser
que seja necessário fazer a inflação do
[Música]
desse pacote tem relação com essa paleta
de cores ou então se a paleta de cor num
interessante é só ela volta ao normal
aqui ok então você pode por exemplo 115
gráfico enfim fica a seu critério e fica
a sua necessidade as modificações que
você vai deseja fazer
o importante é pensar que o esqui se
existe para agilizar o processo
beleza pessoal então eu espero que esse
vídeo tenha sido bastante útil que vocês
possam fazer proveito
é aqui que eu disponibilizei alguns
links é aqui o repositório subterrâneo
que esse script
eu vou eu vou subir secret
aqui é o link do de um artigo que eu
publiquei no linkedin falando sobre isso
que esse aqui tem um grande estátua de
dom do crânio também para quem quiser
seguir é bem curtinho mas é interessante
a gente sempre tira informação relevante
desses dessa documentação e aqui são os
meus contatos têm um e mail linkedin e
derrube tem a minha página que é nova
que eu estou criando mas já tem algum
material interessante lá eu pretendo
mantê la
atualizada com bastante coisa legal e é
isso então mais uma vez foi um prazer
participar do istat dados em qualquer
dúvida estou à disposição um grande
abraço a todos valeu