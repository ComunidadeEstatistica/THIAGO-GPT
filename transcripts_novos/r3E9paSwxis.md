# AM T2 THIAGO MARQUES TEIXEIRA DE OLIVEIRA - CEFET RJ - Aprendizado de Máquina - Prof.Eduardo Bezerra

- **URL:** https://www.youtube.com/watch?v=r3E9paSwxis
- **ID:** r3E9paSwxis

## Transcrição

Olá nesse vídeo vamos falar sobre o
trabalho de aprendizado de máquina do
Professor Eduardo Bezerra do cfet do Rio
de Janeiro Bom primeiramente precisamos
importar as bibliotecas necessárias né
então vamos começar aqui importando as
bibliotecas né logo depois aqui nós
carregamos né as bibliotecas para nós
trabalharmos tá ah
engenharia de features né nós fizemos
aqui a a comparação né com o primeiro
trabalho né de machine learning tá
E vamos avaliar né se a questão né de
trabalhar com a variável dam né
utilizando a regressão logística que foi
um modelo utilizado né se vai ser
impactado ou não né por meio da
engenharia de features né então a gente
vai usar aqui
dois duas transformações né que é o
target encoding tá E aí a gente usou
aqui ó o target
encod por meio aqui do Encoder né targ
Encoder
e
vamos fitar aqui o nosso modelo para
comparar né esses resultados né e aqui a
gente obtém né oado do nosso modelo e lá
logo à frente a gente vai Comparar as
duas abordagens né aqui a gente tá
fazendo um ordinal encoding tá então
aqui usando o ordinal Encoder né então
dando uma a a ordem né a gente tá
considerando ordem na nossa variável
ordem categorias né que a gente criou
aqui
tá Para Para quê Para fazer um Encoder
da variável estado civil tá aqui a única
variável necessária aqui do banco de
dados que a gente precisa trabalhar né
assim como a gente fez na dam a gente
fez no tard Encoder né a gente fez aqui
também no ordinal Encoder
agora e aí vamos comparar esse
resultados né então basicamente ó com
dam encoding né que foi o do feito no
trabalho no primeiro trabalho né a gente
ficou com 90.80 de acura né com target
encode também 90.80 de acura e ordinal
encoding também 90.80 de acura então não
houve né mudança né na performance né O
que já era um pouco esperado por conta
da da acurácia ser muito alta né então o
modelo realmente ficou muito bom né E aí
é mais difícil né no caso eu falei aqui
o o regressão logística mas na verdade
foi a árvore de decisão tá a árvore de
decisão é a que performou melhor né a
que antes a gente só replicou os
resultados que estavam l no trabalho um
né então a gente fez para todos os que
foram trabalhados ó árvor de decisão
regressão logística Floresta aleatória e
a árvore de decisão foi o que melhor
mostrou performance tá então só fazendo
essa correção zininha aí beleza bom
vamos pro segundo item então né então o
segundo item né Agora não mais a gente
vai trabalhar com a variável de forma
binária né então essa primeira a gente
trabalhou com ela binária né agora a
gente vai ter categorias né e de que
forma né então
o foi nos requisitado né que o zero
seria não né o 0 a 5 seria o weak né 0 a
25 moderate 25 a 50 strong e Extreme de
50 infinito né basicamente a gente botou
0 1 2 3 e 4 né então respondendo essas
características né E aí a gente criou
aqui ó
um uma transformação de variável ó
transformamos Aqui as nossas variáveis
né criando né os compartimentos os bins
né solicitadas E aí então a gente
eh criou né ali o nosso modelo né da da
da melhor forma possível ali né então ó
aqui ó treinamos né o modelo testamos né
tiramos o o rótulo né da do do target
para não não ter problema ali na hora de
estimação né do modelo V o target né E
aí o o fitamos o gradient Boost tá então
a gente vai analisar não só o resultado
né para cada base né a 602 627 até a a a
652 né e
Eh vamos também analisar as curvas de
aprendizado né
então aqui a gente plotou as curvas de
aprendizado né então o que que a gente
pode tirar aqui a gente vê né e a medida
que aumenta aqui a quantidade de
exemplos né o o erro ele parece
estacionar até aqui uns 4.000 exemplos
né Mais ou menos né e depois ele sobe
lentamente aqui né A partir aqui de
6.000 5000 exemplos né ele sobe
lentamente e se a gente for isso no
treino né na validação né ele sobe né à
medida que eu aumento o número de
exemplos né mas chega aqui em 5.000 ele
dá um ponto de inflexão aqui e começa a
descer né E esse cenário ele configura
um caso de underfit tá então o modelo aí
se sob ajustou né beleza legal e e a
gente pode comparar também ó as
categorias né então o F1 score por
categoria né Ó o a categoria zer foi
0.91 aeg categoria 1 foi 0.35 né as
demais foram zero aqui né do F1 score né
e aqui tem toda a análise aqui da Matriz
de confusão né que agora não é mais e
bidimensional vamos dizer assim né e
agora a gente tem várias dimensões aqui
porque a gente tem mais de duas
variáveis na categoria target né beleza
legal então a 621 né então vamos pegar
aqui fazer a mesma coisa né pro criar o
modelo e plotar Beleza então à medida
que os exemplos aumentam né no treino
parece subir lentamente até aqui 5000 né
no treino mas Em contrapartida né vai
descendo aqui ó na validação né e depois
dá uma estacionada depois sobe um
pouquinho né E esse caracteriza um
cenário aí de overfit tá beleza já no
627 curva de aprendizado
ó sobe um pouquinho aqui né o com a
medida que aumenta os o treinamento no
treino né aí depois dá uma estacionada
né depois cai um pouquinho e aqui também
não tem muita diferença né ele cai um
pouquinho depois dá uma estacionado e
cai mais um pouquinho depois então
cenário de underfitting aí né sob ajuste
né já no outro foi sobre ajuste aqui né
do do de overfit né
Beleza já aqui
à medida que os exemplos aumentam tá tá
subindo um pouquinho aqui o nosso erro
né já no na validação o tá permanece ali
constante né Tá e aí e isso configura
underfit também tá E esse outro cenário
aqui né também muito próximo né daquele
de estacionário ali também configura um
caso de overfit underfit Tá beleza então
comparando os resultados né conclusões
aí né de todos que foram gerados para
cada base né então em tentando comparar
com a abordagem binária anteriormente né
a gente consegue comparar ali a classe
zero né então a gente olha o F1 lá que
foi produzido antes né na no trabalho um
e agora produzido aqui também no
trabalho dois na abordagem multiclasse
né e a gente vê que só houve mudança
aqui no 627 basicamente né então
aumentou aqui um ponto percentual né no
627 nos demais não mudou né então
eh não não tinha tanta necessidade né da
gente fazer
essa essa classificação multiclasse né
Beleza e e a gente comparou esse somente
porque como é que a gente vai comparar
os outros não tem como né A gente só é
só essa categoria que foi que permaneceu
né
basicamente Beleza então olhando aqui o
shap Vales né pra gente tentar entender
o comportamento a gente gerou um
Gradiente regressor né E aí comparando
aqui as features né que foram
demonstradas importantes aqui né então a
gente olha aqui no Chap value a medida
que fica azul né os valores são menores
e a medida que fica vermelho os valores
são maiores ou seja a contribuição é
maior né e a gente vê uma contribuição
bastante alta aqui da da umidade
relativa do ar né pra precipitação da
chuva
né E à medida que aparecem aqui valores
aqui do lado esquerdo né do eixo né
significa que tá tendo um impacto
negativo né E então teve muito mais
positivo do que negativo né E quando
essa extensão né Essa vamos supor essa
amplitude né dos pontos aqui na na na
horizontal né significa que ele teve
maior importância né então a umidade
relativa aqui se demonstrou bastante
importante aí na na estimação né então
foi ela our SC our concern e a
temperatura né foram as variáveis que
mais influenciaram aí na na predição né
do modelo tá
beleza já aqui ó Houve aqui uma inversão
né no no 602 houve uma inversão entre a
temperatura e o our Coast né o our Coast
estava aqui na segunda né Aí ele
inverteu aqui a temperatura tava em em
quarto e foi para cima aqui
né já
eh não Esse perdão esse aqui é 602 eu
cheguei a botar um nome aqui errada né
621 Depois eu mudo aqui 621 né aí aqui é
no
627 né aí umidade relativa teve o mesmo
comportamento que o primeiro né do 602
esse cara aqui ele mudou também a
temperatura com foi foi muito parecido
com o segundo né tá E esse cara aqui
ficou mais pare ficou mudou um pouco
aqui do ind Direction né que não tinha
aparecido nenhum deles aqui em quarta
posição né nem nas quatro primeiras né
agora apareceu aqui também né Então aí a
gente pode ver quais que contribui
positivamente negativamente né E aí
deixa de ser um
eh é um Black Box né vamos dizer assim
né porque é algo que a gente não
conseguia explicar tão bem e a gente
começa a entender um pouco mais né De
que forma que ele direciona né dados ali
né para pro modelo entender a ideia né
do da estimação Tá beleza então vamos
pro item quatro aqui redução de
dimensionalidade tá então aqui nós
aplicamos o PCA né E aí reduzimos né a
sete componentes principais né e
trouxemos aqui o resultado né então a
gente pode ver aqui que mesmo com menos
variáveis né ali trabalhando né a gente
vê que não não teve uma mudança
significativa né a gente vê que diminuiu
aqui ó cinco em cinco pontos percentuais
aqui né a a precisão da classe de nível
um né ó com essa classe aqui né aqui tá
0,56 aqui tá 0,51 né então 5 pontos per
uais somente mas os outros demais né
foram mantidos né então Faria fez muito
sentido a gente trabalhar com PCA aqui
né para reduzir né Essas componentes
mantendo a maior variabilidade possível
nos dados né então Eh traz um uma maior
celeridade né e tudo mais e isso foi
muito importante aqui né já na predição
conforme lá pros diamantes né A gente
pegou aqui os dados lá do trabalho
anterior né a gente viu que o lá o laço
tinha se saído muito bem né a gente foi
estimar aqui o intervalo conforme né de
predição
pro pro laço né só que eh aqui ó a gente
fez bonitinho aqui o código né trabalhou
aqui ó em cima né pegou aqui o laço né ó
com o o alfa de 10 né que foi o que
recomendou né quando a gente fez lá o
cross validation lá da da no no trabalho
um né E aí a gente aplicou aqui o map
regressor né só que
eh acabou que quando a gente foi fazer
essa predição dos intervalos ó estourou
a memória aqui do do CAB né infelizmente
a gente não vai conseguir fazer a
interpretação mas os códigos estão aí né
tá tudo bonitinho aí se tivesse aí uma
máquina mais potente geraria né esse
código aí a gente poderia interpretar tá
então é é isso beleza valeu tchau tchau