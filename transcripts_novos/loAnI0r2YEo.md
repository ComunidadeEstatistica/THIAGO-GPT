# R Avançado 04 - Agrupamentos  K Means - Professor Rodrigo Rosa

- **URL:** https://www.youtube.com/watch?v=loAnI0r2YEo
- **ID:** loAnI0r2YEo

## Transcrição

o olá pessoal rodrigo novamente com
vocês dando prosseguimento a nossa série
de vídeos a conceitos avançados do erre
né estamos trabalhando mais com a parte
de algoritmos né fazia tempo que eu não
postava vídeo aqui no canal agenda
andava um pouquinho apertado aí com as
aulas do mestrado mas agora dar uma
folguinha aí eu vou ver se trago pelo
menos essa parte aqui dos algoritmos de
agrupamento tá então o primeiro que a
gente vai ver hoje aqui talvez seja o
que demore mais vai ser o caminho está
que eu quero trazer umas coisas
diferentes para vocês tá a gente vai
utilizar aqui uma base que tá lá na uti
você ir cs desculpa mostrar aqui para
vocês tá então que um repositório que
tem diversos datasets lá a gente vai
utilizar isso aqui que era de vinhos tá
era não é né beijinhos então ele tem
algumas características aqui ó
os docinhos alguns atributos que destes
vinhos que é o álcool ácido metálico
tonalidade de cinza magnésio total de
fenóis entre outros tá online e alguns
dados que são de análises químicas e se
vim tá então esse algoritmo se vocês
verem aqui em cima ele é de
classificação tá a maioria desses
algoritmos que tensão da classificação
mas dá uma olhada nessa repositório aqui
que vocês vão encontrar os conjuntos bem
interessantes para texto tá então ele
tenta fazer uma classificação aqui a do
vinho baseado nessas características
aqui tá bem a como é que a gente vai
fazer aqui eu vou utilizar essa
biblioteca aqui ó o vídeo dele tá eu vou
fazer a leitura vou salvar no objeto
chamado vinhos fazer a leitura direto
com a url
e fica o conjunto aqui vocês podem ver o
rl ó tá eu tô pegando o início da tá lá
tem outro que
o que é um que sozinho informações do
dataset tá então fazer a leitura aqui e
já fez a leitura aqui vocês podem ver
que o objeto aqui para mim ó então eu
tenho 14 variáveis com 177 distâncias eu
posso clicar aqui em cima e olhar olha
como veio aqui em cima ó veio sem os
nomes ele vem nesse formato aqui ó na
verdade ele puxa só as informações que
tem nas colunas tá a olhando aqui o
conjunto aqui a gente pode ver os
atributos que tem ó só que o álcool não
é o primeiro golpe na verdade é o
segundo o primeiro atributo que vem aqui
é o tipo então neste caso aqui a gente
tem três tipos a gente tem um o dois
oi e o três tá no sino 77 estâncias tão
no total são 14 atributos a 177
distâncias
a a a gente pode ver a estrutura aqui
dele aqui mas só para mostrar né já já
vi o ali em cima como é que ele está
estruturado tá a aqui tá os nomes das
colunas tá ou nos atributos melhor
dizendo né o que que eu fiz eu chamei a
função call names aqui passei os nomes
das colunas tá então tipo álcool ácido
metálico e assim por diante tá se der um
viu de novo aqui está o nome da dos
atributos tá ah eu instalei uma série de
bibliotecas aqui se vocês não tiverem
vocês podem instalar maioria aqui para
mostrar os gráficos falar que vou gerar
os gráficos
e interessantes para a gente fazer uma
análise não é necessário para correr lá
para agrupamento né do caminho mas seus
gráficos bem legais a gente trabalhar tá
então vou estar lá aqui essas
bibliotecas tá lá não vou carregar elas
já tem instaladas mas se vocês não tem
outras podem carregar a
e essa função aqui tá é só para ver
mesmos vinhos ali tá que que eu vou
fazer eu vou criar um novo objeto agora
chamado vinhos um tá a partir de vinhos
com todas as linhas menos a primeira
coluna porque porque a primeira é o tipo
do vinho eu tipo aqui isso aqui não me
interessa eu vou agrupar eu vou fazer um
agrupamento tá a baseado nessas outras
características aqui nesses atributos tá
então isso aqui não interessa para mim
só que eu posso até utilizar depois no
final lá para fazer uma comparação tá
então vou carregar eu carreguei aqui um
novo novo conjunto então vinhos um eu já
que é o que a gente vai utilizar só um
13 variáveis e 177 observações teresa
atributos 187 a distâncias tá só para
mostrar aqui para vocês
o conjunto tá que bom ah eu tenho aqui
alguns gráficos para a gente fazer uma
análise prev na não tem o histograma
aqui
ah tá então a gente pode fazer uma
análise do histograma eu não vou passar
esse parâmetros aqui mas depois você dá
uma olhadinha tá a esse símbolo aqui tá
é de uma das bibliotecas que eu
carreguei que ele é para concatenar
diversas funções diferentes tá a grosso
modo que só para vocês terem olhada tá
então posso gerar aqui os histogramas
então eu tenho aqui os histogramas para
cada uma das observações tá você tem
para vocês quiserem fazer uma análise
mais criteriosa tá eu posso fazer uma
análise por densidade também
é a ao histograma por frequência aqui
seria por densidade tá então aqui de
todos os atributos
o que eu tenho no meu conjunto eu posso
fazer algum bloco splotch também tá
fazer uma análise e se eu tenho muitos
outlets no caso eu tenho alguns aqui tá
aqui eu tenho três altos pilares aqui
também tem uma baixo aqui que eu tenho
para cima ou para baixo que eu tenho
presa que eu tenho dois aqui eu tenho um
os outros não apresentam outline está a
eu posso fazer uma correlação aqui
usando a função corpo lote tá atestar a
ver a qual a relação desse nesses
atributos ele tem alguma correlação tá
então quanto mais próximo de 1
correlação forte positiva quando o
aumento outro aumenta correlação forte a
menos um né com a relação forte negativa
né quando um aumento outro diminui e
próximo de zero aqui que é o branco aqui
não apresenta uma correlação tá a gente
fazendo uma análise prévia aqui a gente
pode ver que o
o que nós
e a flávia nós favor me diz aqui tá tem
uma correlação bem forte aqui ó a gente
poderia fazer uma classificação baseada
apenas nestes dois aqui a atributos
também ah mas a gente vai utilizar todos
que o que geralmente ocorre né como ele
tem uma correlação boa só trouxe o
gráfico aqui a gente só para trabalhar
com alguns gráficos né então gráfico
aqui da reta de ajuste tá da e os
residuais para esses dois atributos tá
então a gente tem que o total de fenóis
aqui a gente tem o flavonoides tá
oi beleza
tá bom vamos começar a fazer o
tratamento nosso conjunto então a gente
tem nosso conjunto aqui ó tá se vocês
olharem aqui a gente tem aqui o álcool
então tá treze pontos 2013 ponto 16
13.37 a gente tem o ácido metálico 1.78
2.36 e assim segue para cada um desses
desses atributos a gente tem magnésio
que 100 101 113 tá eu não vou entrar na
teoria aqui de como que funciona o
algoritmo de classificação mas ele
trabalha baseado em distância cálculos
de distâncias tá e cálculo e trabalhar
com cálculos excesso de se do jeito que
tá esse conjunto aqui é complicado
porque ele eles estão escalas diferentes
tá então sempre que vocês forem
trabalhar com um conjunto de dados para
fazer análise de distâncias é bom você
fazer ele fazerem uma normalização
desses dados tá então que como
e faz uma normalização eu vou criar um
novo objeto chamando o vinho nome tá vou
criar ele como data frame tá vou chamar
a função sky like para botar tudo na
mesma escala ou normalizar os dados e
vou passar o quê que eu quero normalizar
o que é do normalizar vinhos um tá então
vou chamar a função normalizei então
vocês podem ver aqui ainda tenho 13
variáveis com 177 observações tá o que
que eu vou fazer agora eu vou sofrer um
objeto ser um aqui dando um plot no
conjunto original que era o vinhos um
aqui ó
o ok vou criar um vinho um c2q é o dos
vinhos organizados tá eu vou criar um
grito vende aqui só para mostrar os dois
quartos para vocês para vocês verem não
tem diferença de fazer a normalização
não aquela distribuição dos meus dados
normais se vocês olharem o conjunto
normalizado vocês podem ver que os
pontos estão exatamente nos mesmos
locais tá então a normalização para o
agrupamento é muito importante e ele não
interfere em nada na distribuição dos
pontos avental sol só para vocês terem
uma ideia de como funciona tá então como
que a gente executa o caminhos no erp tá
é bom você sempre usar em uma semente
geradora fixa né para não ter diferenças
nos os dados e vocês você pode usar um
dois três nesse caso que estou usando
1234 qualquer valor para não dar uma
diferença tá então robson aqui ó
e eu vou criar um objeto chamado vinhos
a vinho k2 tá eu chamo a função caminhos
caminhos ele já vem pré-instalado no é
que vocês não precisam instalar nenhum
pacote extra tá eu vou passar dois
parâmetros eu vou passar o meu conjunto
que eu quero fazer o agrupamento tá no
meu caso vinhos nome que o conjunto
normalizado e o centers vai receber o
número de centros né ou seja em quantos
grupos que eu vou fazer esse agrupamento
usando o caminho que seria o carro tá
então eu quero fazer esse agrupamento em
dois grupos a então passa o center igual
dois vou dar um controle entre aqui
e aí eu vou deixar script depois para
vocês lá no eu vou atualizar lá no kit
rubi né vocês podem pegar depois eu lá
tá eu deixei umas anotações aqui ó a
função camisa retorna um objeto da
classe caminhos com informações sobre a
partição algumas informações são cluster
que é um vetor de inteiros indicando o
clã separacao cada para qual cada ponto
é alocado a gente tem o centers uma
matriz de centros dos clusters tá que
são os pontos centrais e os sais é o
número de pontos para cada cluster tá
então vou chamar aqui ó a vinhos vinho
k2 câncer e a gente tenha nossos clãs e
daqui a gente separou em dois clãs eles
né então a gente tem que o primeiro foi
agrupado foi colocado no cluster dois o
segundo núcleo a ser dois o terceiro no
cluster 2 e assim sucessivamente e a
gente tem os outros aqui ó esse aqui
para já foi a grupo
a ser um depois o outro núcleo ser dois
depois o outro no cruzeiro 1 2 2 1 2 1 2
2 2 2 1 1 2 e assim sucessivamente então
o vetor que disso cada qual o elemento
né em qual clã será que ele foi agrupado
a gente também tem a nossa matriz de
centros né então para o álcool aqui a
gente tem o centróide para o cluster' um
centro procura ser um e centro popular
ser dois o ácido metálico porque lá ser
um clã ser dois esses seja sivamente
para cada um dos atributos tá é muito
importante aqui e os sais ele vai nos
dizer quantos elementos ficar em cada
planta neste caso aqui a gente tem que
ir no cluster a gente tem que ir um
classificou com 91 elementos e outro
ficou com 86 elementos tá
é bem pessoal também tranquilo né a
outras coisas além disso a função camisa
retorna algumas proporções que nos
informam com compacto é um cluster qual
diferente são os vários clãs seres entre
si a pra gente tem algumas parâmetros
que a gente consegue analisar então a
gente tem o hábito expe a sua mãe entre
os quadrados dos aglomerados e uma
segmentação ótima espera-se que essa
proporção seja mais alta possível já que
gostaríamos de ter lances heterogêneos
tá wilson está vetor da soma dos
quadrados dentro do útero um componente
do câncer e uma segmentação ideal
espera-se que essa proporção seja o
menor possível para cada criança desde
que nós gostaríamos de ter homogeneidade
dentro dos cânceres tá tokyo está que a
soma total dos quadrados dentro dos
lances e totvs que é a soma dos
quadrados tá
é mais parâmetros aqui então vocês podem
pegar os cânceres que vocês criaram aqui
né vinhos k2 e chamar esses parâmetros
tá tchau tchau beatriz eu posso chamar o
outro parâmetro íris tote with dots tá
eu não tenho eu consigo avaliar cada um
desses parâmetros tá a vocês estudem a
esses paramos porque é muito importante
tá alguns a gente vai utilizar agora
para determinar o número de crianças que
é isso que vocês podem estar se
perguntando né mas quanto quantos
quilômetros usar a gente utilizou dois
mas o ideal é dois bom para estudar
graficamente qual o valor de carro que é
o número de clusters aqui nos dá a
melhor parte são podemos plotar o beats
e tops e escolhas de cá tá como que a
gente vai fazer isso aqui eu vou criar
duas variáveis eu vou chamar o bicho eu
vou chamar bts
eu vou dizer que ela o médico então e o
pronto parâmetro eu vou criar o nome
dela vai ser tws eu vou dizer que ela
também numérica então vou querer essas
duas aqui criei outro você pode ver que
os eles foram criados aqui estão vazios
ou usar a mesma semente geradora e o que
que eu vou fazer aqui eu criei uma
instrução aqui tá que eu tô dizendo que
é um fora né que ele vai de um até dez
tá coloquei observação aqui ó para cada
caca okuribito excitantes ou seja para
cada a valor então para um dois três
quatro cinco seis sete oito nove dez
cada vez que ele passar no foro ele vai
pegar o valor tá vai calcular o caminhos
e com centers na valor do sucesso
baseado no wii que ele está a 1 2 3 4 5
e vai pegar o valor do beatles tá é a
mesma coisa ele vai fazer para o tio
está ele vai calcular o caminho do
conjunto normal que a gente tem com
centers e então vai pegar o centro um
dois três quatro cinco cada vez que
passamos laços e vai pegar o valor do
atributo o valor que tá nesse parâmetro
toktz tá e vai guardar dentro dessas
variáveis aqui que vão ser um dos
vetores também pessoal então vou rodar
esse laço aqui rodeio laço eu vou criar
um certeza aqui que é um que é plot tá
a praia para essas duas variáveis uma
para o bts outro para o tws tá então cê
dois vai separar o bts então você pode
dar um pausa aqui no no vídeo né para
pegar essa função aqui deixa até colocar
para baixo aqui ó
e aqui tá então a gente tem um certeza
aqui que o bts e o c4 aqui que é para o
tws tá eu vou dar um vou criar esse aqui
é plot aqui vou chamar minha função guri
de arranjo tá vou passar como parâmetros
e três e o c4 e o número de colunas que
são duas para mostrar aqui tá então eu
posso mostrar aqui para vocês então a
gente tem aqui para o número de clusters
tá a gente tem aqui a sua mãe entre os
quadrados e a soma total dos quadrados e
azul classe como que a gente faz uma
avaliação a gente pode ver aqui para um
cluster o valor tá lá em cima por dois
clusters o valor já diminuiu bastante
para três clãs sua tv uma diminuição
maior a partir do 4 a gente pode ver que
ele começa a diminuir com a intensidade
um pouco melhor
ah tá então o que que a gente vai fazer
a gente vai usar uma regrinha que a
gente chama que é a quebra do cotovelo
tá então quando ele tem um começa a ter
um desempenho um pouquinho menor do que
ele vinha tendo a gente que a gente vai
fazer a gente vai pegar esse valor que
indica a onde ocorre uma quebra dos
valores né que seria dobra do cotovelo
tá então como a gente viu lá nos
parâmetros que a gente espera que esse
valor seja o menor possível tá só que já
teve um uma queda bem grande aqui também
e aqui já começou a ter uma queda um
pouquinho menor tá que pode não dizer
que a gente vai ter um desempenho muito
melhor do que a gente teria a baseado
nesse nesse ponto parece os dois
gráficos aqui a gente pode ver que o
valor seria três aqui né
bom então vamos pegar esse valor três
aqui eu fiz uma anotação aqui ó
e eu coloquei assim ó qual o valor ideal
para cá deve-se escolher um valor de
classes para que adição de outro clã ser
não forneça uma partição muito melhor de
dados em algum momento ganho cair a
dando o ângulo do gráfico critério do
cotovelo o número de classes é escolhido
neste momento no nosso caso 13 é o
melhor valor apropriado para cá tá
baseado nessa teoria aqui que eu acabei
de falar para vocês então o que que a
gente vai fazer a gente vai fazer agora
o nosso clã ser agora com caminhos né
com preços com três centros né tá o quê
que eu vou pegar agora eu vou pegar
vinhos k3 que foi o que a gente criou né
e vou pegar ele salvar numa variável pré
disso previsão ok3 cluster tá então vou
salvar aqui eu tenho aqui a aquele
viator né com o agrupamento criado né
e vocês não tá primeiro aí colocou no um
segundo e colocou para um e assim
sucessivamente tá eu posso ver a média
dos valores para cada câncer tá eu
chamar função a great tá então eu passo
vinhos um quero meu conjunto que eu
tinha lá bailesti previsão ou seja tô
passando ok3 câncer que o guarda
imprevisão e do chamando a média tá
porque ele tá calculando a média para o
álcool para cada um desses cânceres aqui
tá calculando próximo da thalico por
cinza tonalidade de cinza magnésio total
de fé nós e assim para cada um dos
atributos tá então aqui vocês consegue
ter uma ideia de como que ficou a média
dos valores para cada câncer tá o que
que a gente pode ver a gente pode ver
agora o agrupamento desses clãs ele está
a gente pode usar essa função pernas
aqui e pode ir colocar junto gg tá usar
a função
o pastor você pode dar um pausa aqui eu
não vou explicar essa parte do da função
aqui de pilotagem mas vocês podem dar um
help aí e consultar os parâmetros tá o
tema aqui é só para colocar o tema no
e no nosso gráfico nosso gráfico só
então está criando aqui o plot ó se
vocês olharem baixo aqui
e esperar criar
quem criou o nosso lote aqui
o e mostrou aqui na tela tá talvez aqui
fica um pouquinho a complicado de
visualizar mas acho que já dá para ter
uma ideia boa aqui né então aqui a gente
tem nossos agrupamentos aqui ó ele faz
uma relação aqui entre cada atributo com
os outros tá vamos podem fazer uma
comparação aqui como que ficou os
agrupamentos isso porque a gente tem
mais de dois atributos né geralmente
quando a gente está aprendendo
agrupamentos a gente trabalha só com
dois atributos né e tenta agrupar eles
baseado no número de clusters tá então
essa função gera um gráfico desse tipo
aqui até para deixa eu ver se a gente
vamos exportar ele aqui em salvar como
pdf não vou salvar na área de trabalho
ali mesmo
e vai salvar aí deixa eu abrir aqui para
vocês aqui na área de trabalho
eu quero ver onde é que salvou aqui
o whats que
é um abrir aqui vou dar um zoom aqui eu
tirar aqui
e dá um zoom e assim que ele monta
e o nossos agrupamentos tá então três
agrupamentos uma azul outro verde e
outro vermelho tá a gente pode mostrar
isso aqui de uma forma um pouquinho
melhor mas intuitiva de repente se você
não conseguir entender tá eu posso dar
um plot aqui tá então vou dar um plot em
vinhos na hora que foi aquele conjunto
que eu normaliza aí tá dos atributos do
de 1 a 13 com todas as linhas tá e a
curva o baseado nas previsões que são
aqueles três classes que a gente criou
tá então eu posso dar um plot aqui
e ele vai criar um pote parecido com
esse mas que talvez seja melhor da
identificar né então a gente tem que ir
para o álcool tem um álcool com metálico
a gente tem o álcool com as tonalidades
de cinza a gente tem o álcool com a
tonalidade do cinza a gente tem o álcool
com o magnésio a gente tem o álcool com
total de fenóis e assim funciona para
cada um desses desses atributos tá aqui
a gente tem a nossa matriz aqui de de
clusters tá bem pessoal você pode dar um
exportar aí a ser imagem também para ter
uma visualização melhor tá a gente poder
dar um pote nas previsões também tô com
a gente criou 33 clusters né a gente
pode ver os valores que ficou aqui ó o
primeiro por segundo e por terceiro
clans a gente pode ver até que teve
alguns valores do terceiro que parece
que estavam dentro da faixa do
eu tô segundo aqui né
oi e a gente tem também que ir para o
primeiro né aparece alguns valores o
primeiro que a vanessa da faixa do
segundo tá então a questão se analisar
esses pontos tá bem a outra bíblia até
que vocês podem utilizar é o clã se ele
está então se descarrega essa biblioteca
ela já vem na ativa e você vocês podem
utilizar crossplot tá então crossplot eu
vou passar o conjunto de vinhos
normalizados ou vou passar minhas
previsões que foi o k3 cânceres aquele
o valor que eu salvei em previsões né ah
eu vou deixar senha aqui só para vocês
verem uma coisa como ele já era o padrão
tá e tem vários parâmetros você dá um
help aí depois vocês vão ver esse
parâmetro sabe que ele gera um um
agrupamento que talvez fique melhor dele
ficar lá então a gente tem os três clãs
aqui ligados por linhas né
a gente pode chover até que algumas
linhas se sobrepõem aqui ó de repente
isso daqui pode ter sido aqueles aqueles
valores que ficaram dentro da faixa 1 do
outro tá é uma questão se analisar aí o
que que eu posso fazer isso aqui para
melhorar essa visualização aqui eu posso
colorir isso eu vou colocar color tu tá
se eu dar um controle entra aqui de novo
posso ver que já ficou melhor aqui de
visualizar de visualizar né ficou cada
um a cor vermelho o rosa eo azul
e eu posso tirar aquelas linhas ali
então lines
é falso pelas linhas vão ser eliminadas
tá uma coisa que eu posso fazer também é
leibols mudar o leibols dele está quase
lá com a lei dos = 5
e para vocês darem uma olhada
oi tom aa
ah deixou só finalizar aqui
o que então a gente pode ver que as
linhas foram eliminados é que a gente
tem os clãs eles a então eu tenho que eu
quando aquelas ter um cluster dois e o
pela ser três tá e aí fica melhor daí
vocês fazerem uma análise e visualizar
um dos cânceres e você está tem um
cluster dois também é que eu lembro os
dois é vocês inclusive os parâmetros
podem mudar esses
e as linhas e as colunas aqui tá o dois
o que que ele vai fazer o 2 se não me
engano ele coloca os valores aqui dentro
tá então vocês podem fazer essa
visualização aqui também tá quais
valores que ficaram
e dentro de cada cluster tá toque seria
um valores menores valores
intermediários e que valores maior está
bem interessante
tá tranquilo pessoal eu vou deixar cinco
aqui para carregar para vocês lá eu acho
que é o melhorzinho ali para fazer uma
visualização mais tranquilo 544 acho que
é porque o cinco acho que ele puxou
outra característica isso quatro eu
preciso dar uma olhada no leibo ali que
vocês vão entender ele vai de 10 ou de
folga né depois tem um dois três quatro
e cinco tá cada um monta o crossplot um
pouco com aparência um pouco diferente
tá tem vários outros parâmetros que
vocês podem mudar também
é porque eu só tinha um help aqui só
para vocês verem né bom eu posso criar
uma matriz aqui para fazer a comparação
do que eu tinha
oi para mim a previsão então se vocês
lembram o meu conjunto vinhos original
eu tinha uns tipos de vinhos aqui ó que
eu puxei de lá do site né eu tinha um
dois três quatro cinco seis a um dois
três desculpa sério três tipos de vinhos
que tinha a gente criou um agrupamento
com três clusters também tá então o que
que eu vou criar o grão a tabela tá eu
vou dizer que numa das linhas vai estar
ouvindo tipo tá que eu vou pegar vinhos
vou pegar só isso daqui e na outra eu
vou pegar as previsões tá que são muitos
cânceres que eu criei e que eu salvei
ali em cima tá então vou criar a gente
tem como se fosse uma crise de previsão
de uma crise é confusão aqui ó então tem
aqueles a aqui eu tenho o que que era do
conjunto original então um dois três e
aqui o quê que foi previsto
ah tá então tenho que ele acertou
classificou corretamente 58 que era um
65 ele classificou corretamente que era
o 2 e 48 ele classificou corretamente
que era um 48 que eram três lá e que
realmente eram aquelas como 13 que
realmente era um preço tá aqui a gente
pode ver que ele é ro 13 aqui ó tá que
era um dois e ele classificou como um e
a gente pode vir aqui também que levou
três aqui também ó que era um quer 12
também né ele que ela ficou com um preço
tá só teve um erro de 9 aqui como é que
a gente pode calcular esse erro aqui eu
posso pegar sua mãe se os valores que
ele errou né então três mais três na
verdade é essa aí ó
e eu tava fazendo outro teste aqui né
mas em todo caso fica seis e dividido
pelo número total de observações que o
número de instâncias que são 177 tá
então se vocês virem aqui os seus forem
até o final lá vocês vão ver que são 177
estâncias também pessoal a um
simplesmente aqui ó se vocês olharem
aqui ó 177 tá
e eu vou pegar o número d eus um número
de classificações erradas que ele teve
dividir pelo pelo número total de
observações tá então ele calcula ali ó
ele teve um erro de 0.03 então por cima
da mente eu vou três por cento tá como é
que eu coloco o acerto bom o acerto vai
ser um menos o erro tá então acerto ele
acertou em torno de seu arredondado aqui
para mais né seria 97 por cento mas ele
acertou aqui em torno de noventa e seis
por cento ponto 61 uma certo bem grande
por esse tipo de
é de algoritmo também pessoal bom vou
ficando por aqui porque acho que eu o
vídeo já ficou bem grande né aí espero
que você tenha gostado se que o básico
do caminho lembrando sempre que é
importante vocês estudarem um conceito
né saberem como que é feito todo o
cálculo de distâncias como que funciona
o algoritmo tá mas o básico para rodar
ele alguns parâmetros que vocês precisam
analisar a gente viu aqui tá então
chamar a função é bem simples caminhos
vocês passam conjunto e passa o número
de centros que vocês querem o número de
cá quando os agrupamentos vocês querem
fazer tá então cluster para gente
visualizar o saber a cada ponto para
qualquer lance foi alocado o centro e o
tamanho tá e aqui umas funções que a
gente pode utilizar aqui para determinar
o número de
é de cá ideal também pessoal então aí
vocês podem utilizar essa função aqui
fora para determinar o número de cá
ideal para utilizar no caminho tranquilo
bom a espera trazer vídeos mais
seguidamente a quem gostar dá like se
inscreva no canal compartilhe e ative as
notificações convido os colegas e nos
vemos no próximo vídeo valeu