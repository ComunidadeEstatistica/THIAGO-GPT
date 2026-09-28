# Parking Space Monitoring - A Deep Learning Application

- **URL:** https://www.youtube.com/watch?v=gw0S0aPey24
- **ID:** gw0S0aPey24

## Transcrição

Olá a todos, meu nome é Otávio.
Souza. Estou aqui a convite de
Thiago apresentará um projeto
que eu criei, que é um detector de vagas de estacionamento.
estacionamento. Vamos verificar
se uma vaga de estacionamento estiver ocupada por um carro
ou não. E usaremos apenas a visão.
computação e aprendizado de máquina para
esta tarefa. Hum, vou fazer uma revisão com
Vocês todos têm o código, passo a passo.
através dos passos que tomei, explicando
O que eu fiz e por que o fiz.
OK? Hum, vou gastar um pouco
Primeiro os slides, só para que
Vamos aprender as etapas. Então, eu vou
Mostre aqui, uh, um slide de
Os passos que seguiremos agora.
Basicamente, seguiremos estes passos.
Aqui estão três etapas, que consistem em selecionar o
região de interesse, o ROI ou os ROIs
Nesse caso, hum, o que seria o
regiões de interesse? Seriam eles os
Lugares que queremos analisar, certo?
Então, nossa região de interesse
São os quadrados. Depois
Selecione-os, vamos extrair o
características da região do
ROI. Hum, o que extrairia o
características? Extrair algum tipo
característico daquela região,
Essas podem ser bordas, cantos, densidade de
pixels, usaremos algumas técnicas
lá para realizar essa extração. Ah, e
então pegamos essas características
e os passamos para o algoritmo da máquina.
O aprendizado que vamos usar aqui, que
Será SVM. Primeiro, precisamos...
faça o treinamento, depois
Faremos testes para verificar o nosso
precisão, e é aí que podemos fazer isso
Previsão, ok? Certo, então vamos lá.
Agora, vamos ao código. Então,
Basicamente, eu faço algumas coisas aqui.
importações e então eu carrego o
Vídeo usando OpenCV, certo? Ei,
Aqui podemos ver um muito
Esse ponto de partida é interessante. Esse
O ponto crucial aqui é uma variável que
Você poderá ativar ou desativar esse recurso aqui.
Este "se", esta função "não", este "se". Ei,
o que habilitará esta função aqui
O que podemos ver está vindo disto
pacote aqui, imagens. Se formos
Analisando aqui as importações.
Ferramentas é outro módulo que é
com você no diretório raiz de
a pasta. Então podemos ver aqui
que dentro de ferramentas.py existe um
classe chamada imagéis. E aqui haverá
Algumas funções, por exemplo, uh,
Esta é a função que vamos usar.
usado para detectar os pontos que
Queremos analisar. Vou executar isso aqui.
para que eles possam ver. Então, para
Vou executar o comando e habilitá-lo aqui.
Tipo um, tá bom? E eu vou administrá-lo.
agora. Você pode notar que um deles se abre.
imagem. Então podemos usar isto
função para escolher os pontos que
Queremos analisar. Vamos formar um
Retângulo, certo? Então eu vou
Clique aqui na imagem. 1, 2, 3,
4 pontos. Ele já gera esse retângulo.
aqui para mim. Essas coordenadas.
Você pode vê-los aparecendo abaixo.
Então, basicamente, eles podem
Selecione a região desejada. e
Copie. E isso ficará aqui no
pinturas. Certo, como eu já havia feito,
Não farei isso novamente. Pode
Selecione-o novamente e ele será exibido.
de novo. VERDADEIRO? Como faço para cancelar aqui?
Por isso ocorreu um erro. Mas você
Eles podem levar esses dois, esses dois.
pontos, ou até mais se você quiser,
Basta defini-los aqui para que
para que possam analisá-los. Como eu já os defini.
Vou zerar isso, tudo bem?
bom? E ele não passará mais por aqui.
Então, estamos presos num ciclo vicioso, não é?
Não? Então, enquanto eu, que começa em
zero, ser menor que o número de
Pinturas, continuaremos aqui. Esse
Isso significa que, quadro a quadro,
Vai passar por todas essas etapas, imagine
Um fotograma do nosso vídeo. Tudo certo?
Então, primeiro, fazemos a captura.
da pintura e redimensione essa pintura
com a largura que desejamos. Hum, depois
Convertemos esta imagem para escala.
Escala de cinza e aplicamos o filtro aqui,
apenas para suavizar a imagem. Todos
bom? Então, aqui definimos
nossas caixas que queremos analisar,
Nossos espaços, certo? E apenas
Então, o que estamos fazendo aqui?
de novo? Do pacote de utilitários,
Estamos usando a função get rotate.
retângulo Isso nos ajudará a redimensionar e
girar nossa imagem. Porque
Vamos fazer isso? Porque para
passá-lo para um classificador, neste caso.
SVM, as imagens devem estar no
mesmo formato, na mesma dimensão e
mesmo formato. Então isto
Essa função nos ajudará a fazer isso.
Está aqui novamente nas ferramentas.
pi e terá a função de rotação
retângulo Tudo certo? Aqui definimos o
largo. Então, basicamente aqui
Ele realiza essa rotação, gira e redimensiona.
nossas imagens. Vou executá-lo.
Aqui você pode ver o que tem lá.
fazendo. Você pode ver que ele está tirando
os dois espaços aqui e eles são
Ajustando à mesma escala. Eles conseguem ver
que são quadrados, né, do mesmo
tamanho, certo? É isso aí.
que a função está fazendo aqui
para nós. Então, nós conseguimos.
redimensioná-los e eles chegaram aqui para
esta variável. Agora que terminamos...
Redimensionamos e rotacionamos estes
imagens, vamos extrair o
características dessas caixas, de
esses espaços. E novamente estaremos
usando o pacote aqui na classe de
utilitários tools.py Vamos lá
Olha, haverá uma função chamada
extrair características. Esta é uma parte que
Considero isso o mais importante. Há
Diversas técnicas podem ser usadas para isso.
maneiras que você pode fazer
diferente. Hum, eu usei alguns
Aqui, muito simples, muito simples em
Na verdade, só para ver se funcionava.
No fim, funcionou, então deixei como estava.
. No entanto, existem muitas técnicas.
mais avançado, por exemplo, o
Extrator HOG, né, SIFT, SURF, ORB,
São todos extratores, né, técnicos?
que eles podem usar para alcançar um
Melhor extração de características.
Não se preocupe. Hum, usei algumas bem simples.
que é basicamente o histograma.
Então, eu uso o filtro Canny para
detectar bordas e passar a imagem
Também está completo. E um desses três
imagens, o histograma, detecção
das bordas e da imagem inteira, tudo em
o mesmo vetor. O que é isso?
Isso acontece? Eles podem, eles podem perceber que eu sou
usando esta função de achatamento aqui
Em todos os momentos. O que ele faz?
Essa função se achata? outro slide
aqui. A função de achatamento,
basicamente converte uma imagem ou um
Um vetor que é uma matriz, com licença,
que é em duas dimensões, para um
dimensão. Assim, eles podem ver que
Estamos transformando esta matriz aqui.
que tem linhas e colunas em apenas
uma coluna e várias linhas. Não se preocupe
? Então estou transformando vários
colunas em apenas uma coluna aqui
para deixá-lo em um vetor, que não mais
Não uma matriz, mas um vetor.
Então podemos ver que estamos
fazendo isso o tempo todo. Então
Pegamos o histograma e aplicamos
achatar. Detectamos as bordas do
As imagens são convertidas para formato vetorial. E
Capturamos a própria imagem e a passamos para
vetor. Então pegamos todos esses
três vetores. Então, teremos três.
vetores destes aqui e o
Vamos colocar um abaixo do outro, como
se estivéssemos entrando em um abaixo do
mais um para que tenhamos tudo isso em um só.
filtro global, ou seja, um extrator
global. Tudo certo? Então iremos.
adicionando cada imagem a uma lista
suas características globais. Igual a
Essa é uma estratégia muito simples.
Muito simples mesmo. E nós já conseguimos isso.
para obter alguns bons resultados.
Você pode tentar principalmente
Com HOG, que é um extrator muito bom,
ou podem experimentar outras técnicas que
Acho que eles vão produzir um resultado muito melhor.
melhorar. Fiz isso apenas para experimentar e
No fim, funcionou. Então eu fui embora.
Este algoritmo, como você pode ver
aqui. Tudo certo? Então,
Extraímos suas características, e
O que vamos fazer agora? Vamos
prever o que é isso
as regiões significam, se elas tiverem o
Posição ocupada ou desocupada. Mas é para isso que eu tenho.
para treinar nosso classificador.
Primeiro, podemos ver aqui que estamos
Usando SVM, estamos usando a função
Previsão por SVM. Este SVM aqui, veja,
Então, estamos importando de
SVM, importar SVM. Este SVM é mais um.
módulo que está no mesmo
Eu já tenho o diretório de arquivos.
abra aqui, e ele basicamente faz
Toda a seção sobre SVM está aqui.
Portanto, tem a função de
treinamento, tem a busca por
parâmetros, tem a função que
Salvar o modelo, quais testes e o que ele faz.
a previsão. E esta função aqui,
Basicamente, carrega e prepara os dados.
E aqui chamamos isso de "nós executamos".
o treinamento; Chamamos isso de
funcionar de acordo com tudo
preparados e nós também fazemos o
função de teste. Vou dar uma passadinha.
cada etapa, e a primeira etapa que
O que precisamos fazer é treinar, certo?
? Então, para treinar aqui, vamos lá.
Para usar a classe chamada SVM. Primeiro
O que precisamos fazer é carregar nosso
banco de dados, carregue-o e prepare-o.
Basicamente, esta função
Aqui está carregando o
Imagens, certo?, do nosso banco de dados de
dados. Eles podem encontrar a base de
dados aqui neste diretório e eu sou
ajustando-o com base nos dados de treinamento
e dados de teste, atribuindo o
rótulos. Então, se o quadrado for
Se estiver ocupado, receberá zero. Se o quadrado
Se for gratuito, receberá uma nota um. Então
, esses parâmetros. Se o nosso
O algoritmo prevê zero.
O espaço será ocupado. Se for um,
Será gratuito. Tudo certo? Aqui está
onde desempenhamos a função de
treinamento. Basicamente, é o seguinte:
Carregamos e preparamos os dados. Então
que temos nossos bancos de dados de
testes, treinamento e nosso
também etiquetas. E nós também temos
para extrair as características de
Esta imagem é para fins de treinamento. Hum, isto
Esta etapa aqui também é muito importante.
porque devem ser os mesmos passos que
Você costumava treinar, aqueles que você deveria
Também podemos prever sobre o quê?
Entendeu? Então estamos usando o
a mesma função que será desempenhada por
mesmas extrações e também vem
daqui, a partir de tools.py. Portanto
Portanto, essa mesma função será utilizada.
para treinamento e também para previsão.
Tudo certo? Então eu chamo aqui de
função de treinamento do nosso SVM. Aqui
Carregamos as funcionalidades e o
rótulos de treinamento e teste.
Vou passar agora para a nossa turma de
treinamento. Então, basicamente
Quando eu chamo essa aula, ela começa
nosso SVM. E aqui eu realizo o
treinamento. Tudo certo? Então,
Você pode ver que aqui, na área de ajuste, nós estamos
realizando o treinamento com X de
treinamento e treinamento Y.
Em seguida, avaliamos sua precisão com
os dados de teste. Tudo certo? Ei,
Eu já realizei a busca de parâmetros.
Mas se você também quiser
Para fazer isso, eles podem basicamente executar
esta parte do código. Então,
Basicamente, eles têm que descomentar.
Esta parte e comentário sobre esta outra linha
daqui. Em seguida, você removerá o comentário.
pesquisa de parâmetros e você executará
o programa. Então, ele executará o
Pesquise e encontrará o melhor resultado.
parâmetros para classificar sua SVM.
Leva bastante tempo, então não...
Vou executar o teste aqui. Então, primeiro
Vou apenas conduzir o treinamento.
que é rápido. Para executá-lo,
Basicamente, definimos isso aqui.
função e vamos executá-la. É preciso
execute-o diretamente neste
Módulo SVM.py, porque só aqui, veja
Só funcionará se esta for a
diretório principal, o arquivo
execução principal. Então,
Nós treinamos, nós realizamos o treinamento.
Aqui foi bem rápido, tipo
Como vocês podem ver, obtivemos 89%.
precisão com dados de teste e
treinamento. e obtivemos 84%.
precisão nos dados de teste. Pode
Para melhorar isso, mas para o nosso caso,
Vai funcionar aqui. Então eu já fiz isso.
Já realizamos o treinamento aqui.
Já fizemos o teste aqui, já
Fizemos os testes aqui e agora.
Podemos fazer a previsão. Como eu disse
Você pode experimentar outros tipos.
de filtros para melhorar a precisão
do algoritmo. Principalmente, isto é
A parte que considero mais importante.
Assim, eles podem experimentar outras coisas.
técnicas, eu até recomendo porque
A técnica que utilizei é muito simples,
Muito simples mesmo. E agora eu vou para
Execute o comando aqui para ver o nosso
resultado. Você pode ver aqui que eles são
os dois espaços. O primeiro espaço
Está resolvido, certo? O carro não vai a lugar nenhum.
Vamos lá. No segundo espaço aqui
Agora poderemos vê-los todos.
redimensionado. Quando o carro partir,
registra a partida, o cronograma de
saia e o espaço fica verde
indicando que ele está sendo libertado. Isto
Eu fechei antes da hora, por isso deu erro.
Mas acho que é só isso. Este é o
Primeira videoaula que eu já fiz.
. Espero que gostem.
Peço desculpas por qualquer inconveniente. Eu não sou Thiago
Mas tento fazer o que posso para
Transmita o conteúdo para eles. O projeto
A versão completa está no meu GitHub, o link é este.
Estará aqui na descrição. Ei,
Lá você encontrará todos os passos para
continue com as instruções de como executá-lo no seu
máquina. Será que as livrarias terão isso?
Eles precisam instalar. Tudo certo?
Então, dê uma olhada lá. Eu vou para
Deixe meu link abaixo também,
Caso alguém queira se envolver
contato. Então é isso, espero.
Espero que tenha gostado. Até mais,
pessoas.