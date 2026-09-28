# Aula 05 - Glm classificacao producao - Prof. Flávio Clésio

- **URL:** https://www.youtube.com/watch?v=kXnBTf0pRfA
- **ID:** kXnBTf0pRfA

## Transcrição

e fala pessoal destaque lados tudo bem
então aqui a gente vai fazer a nossa
serialização do nosso modelo de eliane
que a gente treinou então se você não
sabe a como fazer o treinamento do nosso
modelo o sujeito que vocês voltem na
aula anterior e veja forma que a gente
fez o nosso treinamento modelo foi uma
por um pouco mais a detalhado em relação
aos parâmetros do glm aqui a gente vai
pegar o nosso modelo e vai gerar um
objeto que a gente pode usar em produção
posteriormente comente vai ver um pouco
mais à frente tá certo antes de mais
nada a gente continuar esse vídeo para
quem não é inscrito no canal sugiro que
vocês se inscrevam aqui no está te dados
tem muitas coisas interessantes e
estatística avançada visualização de
dados mach lane essência de dados então
assim no canal clica queen subscribe ou
como escrever e deixa o joinha no vídeo
também para aumentar a amplitude desse
desse conteúdo aqui de qualidade para
sendo
é oferecido aqui para que mais pessoas
têm acesso a esse conhecimento tá certo
então a gente fez o nosso treinamento do
modelo então só voltando dois passinhos
atrás aqui a gente fez o nosso o
treinamento nosso modelo glm aqui usando
a nossa a passo nosso banco lehman
brothers e com esse modelo treinado né
então o seu rodar se summer aquilo o
modelo vai estar distanciado ele mora
aqui no qual tenho importâncias das
variáveis eu tenho histórico tem todas
as métricas a de qualidade desse modelo
e também se eu vim aqui no flor né então
eu não tenho tanto objeto java que é
somente copiar esse esse esse objeto em
passar para os engenheiros de software
embutido na plataforma quanto também as
informações modelo quantos fumar então
assim dicas que eu usei uma elástico
mete os gráficos de importância isso
tudo fica salvo no histórico não precisa
se preocupar não precisa a la pucha
suave mais um treininho modelo eu não
sei como que foi o resultado quais são
os parâmetros quais foram os dados o
h2oh ele armazena todas as informações
dentro do cluster isso é muito
importante então uma vez que você
treinou você não perde histórico do
treino e principalmente você não perde
os dados que você usou para treinar esse
modelo então isso aqui é
reprodutibilidade total certo pessoal
então a gente entra no nosso modelo
então a gente vai agora para fase de
serialização esse modelo então a gente
vai salvar esse objeto esse esse como um
arquivo binário que
e usar isso para colocar por exemplo uma
app introdução a então nesse caso que eu
tô na pasta do grm então aqui eu tenho
os dois scripts de classificação e
regressão a gente está num de
classificação eu vou pegar o diretório
raiz tá isso aqui é só uma forma prática
para eu não ter que colocar tudo o
caminho a manualmente então se eu
tivesse que entraram na minha no meu
diretório então eu teria que entrar
documentos o documento seguinte humps
para te dados src glm entrar aqui na
pasta então não quero digitar tudo isso
quero pegar esses caminhos
automaticamente a aqui dentro do é tão
peguei o meu diretório raiz e esse vai
ser o diretor do meu projeto tá e hoje
que eu vou eu vou usar esse esse método
facilitar a e vai concatenar o meu
diretório raiz com diretório do meu
projeto nesse caso tô usando glm aqui e
ele vai gerar um caminho que
o caminho do artefato no whatsapp né que
ele vai dar para mim aqui está te dados
assim ser aqui é o caminho da minha
máquina onde que vai tá nesse espaço que
a gente já tá visualizando aqui certo
então para salvar os modelos no h2omem a
gente chama o objeto chamado seis
módulos então eu vou colocar o ponto de
interrogação aqui e ver o que esse mais
faz 10 documentação dele então querendo
a documentação ele tá falando aqui ele
salva um modelo do h2 um disco e o que
ele precisa somente do objeto que vai
ser o modelo do h 2 o nosso caso é aqui
a gente tá usando já li n a e o pef ele
vai trazer para gente aqui o caminho né
eu disse que a gente vai salvar no nosso
caso aqui o arco até três e no lugar que
a gente vai só modelo que vai ser dentro
aqui da pastinha do está te dado tá
então vou tirar o ponto de interrogação
aqui e vou só vão o nosso modelo tem um
branco e olha que aconteceu aqui a gente
pode ver que o meu modelo glm que ele
foi criado tá vendo então a gente pode
ver que um objeto a foi criado o aqui no
nosso disco tá se eu quiser ver se o
caminho então o caminho desse objeto vai
ser o mesmo caminho do diretório raiz
mais o diretório no qual estou
trabalhando agora junto com o nome desse
desse objeto mais suave puxa agora a
gente tem esse esse arquivo binário mas
como que a gente faz uma previsão nova
com esse arquivo simples vamos vamos
esquecer tudo que a gente usou até agora
que ele só fez o load do h2od a gente
iniciou o plástico certo
é o que a gente vai fazer a gente vai
chamar esse método load model vamos ver
que ele traz a documentação dele aqui o
método modo ele vai simplesmente só só
carregar o modelo né então a gente já
passaram binárias do modelo h2óó a para
esse crescimento ele vai influenciar
esse esse modelo de memória então a
gente vai pegar e qual que é o morreu
que a gente vai passar aqui vai ser esse
módulo pé que é o mesmo caminho com o
mesmo modelo que a gente acabou de
treinar alguns segundos atrás então eu
vou fazer a carga desse desse modelo
para trabalhar na chamada server de
modão
o seu executar somente sabe modo aqui
ele vai rodar o modelo para mim não vou
dar o modelo né treinar mas ele vai
trazer ao objeto então falou é um modelo
glm aqui tem os parâmetros físicos ou z
que tem esses coeficientes porém vai ele
se eu quiser fazer uma predição como
dentro carregado em memória a eu posso
chamar esse a esse método chamado
predict no qual a preciso passar um
objeto que nesse caso vai ser não vai
ser o nosso o nosso glm moda por quê que
formando eu que a gente treinou a gente
vai trazer o save do móvel e os dados
que a gente vai passar por esse modelo
vai ser na da nossa base de teste né
então a gente vai chamar esse método
permite a gente vai colocar aqui no
daily frame só para ficar na formato
bonitinho a converter cadeira firme e
vamos jogar dentro desse modo eu por
dentro e jogando aqui dentro do produto
e a gente tem a esse conjunto de dados
já carregou aqui então se eu clicar aqui
em cima aqui no enfarma na nesse modo a
poder eu vou ter que ir à para cada uma
das minhas vou te 001 então se vai
entrar e se não vai entrar depois você
vai entrar em levou isso a gente
quisesse um pouco mais por isso a gente
pode pegar a probabilidade para cada uma
das classes na qualidade para quase zero
e probabilidade para a classe um certo a
mais suave isso aqui se eu quiser
carregar o modelo não erre mas como que
eu faço para gerar o arquivo bojo por
exemplo o bojo que são os arquivos de
serialização e de novo galera questão
essas pessoas de serialização e o que
significa cada um desses modelos e qual
a interesses e qual que são os objetivos
desses arquivos a gente pode eu
recomendo que vocês vão lá na lá saúde
arquitetura que lá gente fala no detalhe
tá e aqui para gerar a serialização a
não dos arquivos
e nem como a gente tem aqui a esse esse
aqui no binário mas para gerar os
objetos java a gente vai usar esse
método chamado download mocho tá a
deixou o local ponto de interrogação
como ele já viu gente minha documentação
do método kauane fala que vai fazer um
download a do modelo nesse mogi o forma
né que é o que é o formato do h2óó que
já tá pronto praticamente pronto para
ser usado em produção e que vai pedir
compararem para que ele vai pedir o
modelo né então nosso caso aqui vai ser
o gelinho ele modo mais a gente pode
usar o seguinte modo usual sempre model
aqui só para a minha vez de para termos
de simplicidade mas vou deixar hoje ele
mesmo o caminho que vai ser o caminho
que a gente vai salvar esse objeto nosso
caso em jaqueira e salvar na mesma
pastinha gln então seu executar somente
o arquitecto aqui ele vai trazer o
caminho da pasta glm quem
e agora isso ele vai gerar usar ou não e
o que ele sujar aqui é somente um objeto
a em java não é um um arquivo já no qual
as aplicações java pode fazer uma
integração mais fácil com esses arquivos
e aqui a gente pode a por exemplo se a
gente quiser passa somente treinar e
passar esses dados para os engenheiros a
desmanche morna os dinheiros de de só
ter a sua mente embutir essa essa
aplicação dentro do da pregação de
produção deles é só gente passou esse
ponto já que já está tudo resolvido
bom então a gente vai executar esse
script modo fácil e se a gente fizer o e
flash aqui no nosso faro aqui no nosso
da nossa aba a gente pode ver que tem
mais um a na verdade mais dois objetos
criados aqui né que foi a um objeto
ponto zip né e o objeto ponto já que é o
arquivinho a que pode ser lida tanto em
java quanto escala que já vai estar a
100 porcento pronto para aplicações em
produção tá
e a isso a gente quiser por exemplo
importar esse esses objetos né então
para fazer em porte desses objetos para
o então vamos imaginar que eu sou o
segundo cientistas de dados que eu tô
pegando esse modelo eu quero ver como
que esse modelo tá se comportando não eu
não tenho o binário não tenho código o
que eu posso fazer aqui a sua mente a
fazer a carga nesse modelo né então na
verdade isso aqui é só uma concatenação
no caminho né então vou pegar esse ponto
zip dentro do meu caminho que é um eu
vou chamar de modo jor tá e aí digamos
que eu sou um segundo cientistas de
dados eu tô fazendo algum teste com esse
modelo não tem o código não tem um
binário ah mas eu quero ver como que
esse modelo se comporta eu quero fazer a
carga desses desse modelo de novo no é
então é só pegar o caminho desse aqui no
já e usar como esse importo bojo aqui no
qual eu só passo o
o bojo favor peça a esse caminho aonde
isso arquivo ele tá salve aqui eu vou
ter o meu a importa demoro tem já
importou o modelo para mim ele fez a
carga do meu a arquivo a ponto zip né
que é um que o nosso bojo e aí se eu
quiser fazer uma predição como modelo
recarregado eu vou usar o mesmo objeto
por dentro vou usar somente odeio afirma
aqui em cima só para deixar os dados com
a carinha tabular e como objeto eu vou
usar o importa que módulo que eu acabei
de criar aqui ou seja o modelo crê
originário a do arquivo a mocho
bom e como a novos dados e vou usar
minha base de teste para você que tá
snippet
eu fiz a minha perdição
ó e aqui eu já tenho a minha base aqui
modo eu acordei tem corta
o que é o resultado que vai ser que vai
dar o mesmo o mesmo o mesmo modelo nada
menos objetos todas as predições aqui tá
do meu odeio a perna deixo sócio de um
pouquinho só para ficar mais fácil de
visualizar e aqui a gente tem production
passa 01 ou a probabilidade nós faz
fizeram para o lugar de na classe um
certo a então esse é todo ok tude como
fazer esterilização serialização de
modelos de produção do glm transpor um
pouquinho algumas variáveis e a gente a
salvou esse modelo e fez a carga desse
modelo tanto em relação ao binário
quanto arquivo bojo e em relação a
questões de arquitetura de com esses
arquivos realizados eles se relacionam
com a parte de produção e o surgiram que
vocês vão o primeiro vídeo daqui da
série que explica no detalhe o que cada
componente de esterilização faz e por
que que a gente está se realizando esses
binários e arquivos mogi pojos e
a gente consegue ver a todas as
informações a dos jovens então tudo isso
que a gente tá fazendo treinamento aqui
transformações a gente tem em todos os
jogos para que esse dia na moda por
exemplo é o modelo que a gente acabou de
carregar então se ele quiser ver por
exemplo os parâmetros modelo então tudo
isso é totalmente ao ditado então a
gente tem a chave do modelo por exemplo
o caminho físico ao trailer frame e
algumas outras informações como número
de interações exatamente da mesma forma
que a gente treinou tudo bem então é
isso por hoje pessoal a se você gostou
do vídeo deixe o joinha se inscreve no
canal e eu vejo vocês no próximo vídeo
tá bom até mais e tchau tchau