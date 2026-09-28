# AM T1 THIAGO MARQUES TEIXEIRA DE OLIVEIRA - CEFET RJ - Aprendizado de Máquina - Prof.Eduardo Bezerra

- **URL:** https://www.youtube.com/watch?v=qgRZ04QTJwU
- **ID:** qgRZ04QTJwU

## Transcrição

Olá nesse vídeo vamos falar sobre a
tarefa um da disciplina de aprendizado
de máquina do Professor Eduardo
Bezerra bom para começar a tarefa um a
gente precisa importar as bibliotecas né
e aqui eu detalhei eh cada cada
importação né associada a cada questão
que a gente utilizou né então todas as
bibliotecas aqui que foram utilizadas
estão aqui por questão Ok beleza na
questão Um né foi nos dada uma base de
crédito né então credit trin credit
teste né então uma base de trin uma base
de teste em TXT né separado por eh
espaço em branco né e não tinha o nome
das colunas né então foi necessário
colocar os nomes das colunas e importar
aqui usando read csv Beleza beleza
Eh logo abaixo aqui a gente visualizou
os dados né e vi olhando os dados a
gente vê a necessidade de fazer um
transformar as variáveis categóricas em
dames né que elas não tão aqui
exatamente transformadas né algumas
delas tá E aí que que a gente fez aqui a
gente olhou né qual é o a proporção do
target né então aqui
47,6 tinha pagado a dívida né e
52,4 não pagou a dívida né então são os
rótulos lá da nossa base de dados tá a
gente viu só as proporções aqui beleza
então a gente conclui que é um um
dataset que não é desbalanceado né Ele
é razoavelmente aí balanceado né então a
gente não não precisa aplicar técnicas
aí para trabalhar com dados balanceados
beleza bom transformamos as variáveis
categóricas né então Ó o estado civil
aqui a gente transformou para poder
trabalhar tá
legal eh a gente ajustou um modelo de
regressão logística né Então esse foi
ajustado aqui na base de treino né
transformando aqui as devidas variáveis
né para fazer aqui a a padronização das
variáveis né para tirar o efeito de
escala
né então aplicamos na base de teste para
dados não vistos né E aí a gente obteve
aqui uma acurácia de
88.72 né como o dataset ele é balanceado
né a gente pode usar a acurácia como uma
medida
é boa né para poder mensurar a qualidade
de ajuste né mas claro né a gente também
pode olhar o Recall Precision F1 score
né baseado aí no nosso negócio também né
vou comentar um pouco mais à frente né
aqui a gente tem a saída né que é a
matriz de confusão né então na diagonal
principal são os que o modelo acertou e
na diagonal secundária né tem os faos
positivos falsos negativos tá então a
gente vai fazer isso para cada algoritmo
que a gente trabalhou né então aqui vou
já mostrar um resumo aqui do que a gente
fez né então Ó então como temos uma base
balanceada né que nem a gente falou né a
classe negativa é
52.4 a classe positiva o nosso target
47,6 né então a gente pode usar acurácia
como métrica para determinar o melhor
algoritmo né e assim foi feito também e
só deixando uma dica aqui também né que
a mrica Recall seria interessante aqui
para minimizar os falsos positivos né ou
seja classificar aqueles que honraram a
dívida quando na verdade
eh perdão classificar que não honrou a
dívida quando na verdade ele honrou a
dívida né então isso é bom pro para esse
tipo de negócio aqui né porque aí
você ia saber que a pessoa de antemão
ela honraria a dívida né então você
faria o empréstimo né né então ó
comparando as acuras dos Testes então
foram testados aqui árvore de decisão
Gradiente bushing Floresta aleatória
regressão logística e carers
neighborhood né então
90.80 aqui a árvore de decisão ganhando
aqui no critério ja acurácia né
Gradiente boosting ficou com 90.10 ali
né atrás depois Floresta aleatória com
8941 regressão logística com 8872 e
carest neighborhood Ficou ali na
lanterninha com 86 28% né Beleza então
foi a questão um né a segunda questão
era um dat set de Diamante né então era
um problema de regressão né Eh nesse
primeiro foi de classificação né Beleza
então a gente importou aqui usando re
csv também né que era um csv tá o que
foi nos dado aqui né só que esse não foi
dado treinamento e teste né então a
gente vai ter que fazer esse split né aí
a gente vai ver mais à frente beleza
aqui um dicionário né de que que é cada
tipo de variável e tudo mais então tem a
claridade do diamante a cor né O a
profundidade enfim tem várias
características aqui do diamante que
poderiam ser utilizadas para fazer essa
precificação do diamante
né Beleza então vimos aqui
estatisticamente o resumo também né aqui
a gente viu Quais são as variáveis
categóricas né e trouxe de forma
automática aqui para fazer a
transformação das variáveis né e
transformar aqui a gente usou o critério
de dames né mas também seria
interessante usar o Label Encoder para
ver como é que ficaria essa estimativa
né porque e como a gente tem variáveis
ordinais também aqui dentro né Por
exemplo a claridade do diamante a
claridade ela importa né então a ordem
Vai importar aqui né então seria
interessante a gente usar o l c mas
acabou que eu a gente quis ser eh mais
conservador e usou o get dams mesmo né
criou dams para a gente trabalhar aqui
Tranquilo
então a gente usou aqui uma abordagem de
holdout né 8020 né então a gente
selecionou 80 para treino e 20 para
teste né então rodamos aqui vários
algoritmos né então fizemos um loop aqui
né E aqui saiu o resultado mas aí aqui a
gente fez de uma forma mais bonitinho
trouxe aqui e comparou com as métricas
de regressão né Então quais foram as
métricas que a gente utilizou a gente
usou o score R2 né que mensura o quanto
da da variável resposta tá sendo
explicada pela variável pelas variáveis
explicativas do modelo
tá a gente tem o score MSE o min Square
eror também quanto menor o score melhor
é o modelo né e o map ele vem em
percentual né o quanto que ele é Rui
percentual né a gente
pode ver aqui que o R2 né o maior R2 né
que ou seja o maior poder de explicação
do modelo foi do rom Forest regress né
aqui é tem duas linhas repetidas né mas
na verdade isso não não impede aqui a
nossa comparação Tá mas eh os outros
algoritmos aqui estão direitinho né
então ficou em primeiro lugar aqui o r
for regresser né então tanto no critério
de MSE como no map e R2 né ele se
sobressaiu sobre os demais né né o Car
neor Hood ficou aqui na lanterninha na
lanterninha não ficou em segundo lugar
né o
95 p79 né de explicação aí do
R2 o o map né errou aí 12% o nosso
campeão errou só 7% né então
e
beleza gradient Bush regressor ficou em
terceiro né decision regressor laço e
linear regress logo em seguida né E
também não foram ruins né foram 91 89 aí
né de de explicação né da variável
resposta né também não foi ruim apesar
do do ral Forest né ter aí tido uma uma
diferença aí significativa né mais seis
pontos percentuais aí né na na
explicação aí do do R2 Tá beleza então
na três nós temos aí conjuntos de chuva
né precipitação né Então temos várias eh
Estações né E aí comparar esses dados né
E eles são desbalanceados né então a
proporção entre a na na target né pro
pro treinamento e pro teste você vai ver
que os exemplos são muito menores né na
essa proporção é muito desbalanceada n
muito diferente entre si tá aqui a gente
tá importando os parqu né então para
importar os pars a gente usou read
Parque
tá
beleza aí importamos todos os arquivos
né que geram da extensão picle né aqui a
gente só tá vendo os dados né
informações das variáveis aqui é o nosso
target né que é a precipitação que é uma
variável contínua né E aí a gente que é
o volume de chuva né no caso né E que a
gente vai transformar para poder fazer a
classificação né que foi solicitado aí
na na parte um da questão
né Beleza então codificamos aqui usando
NP né E aí quando foi zero né a variável
target a gente colocou zero caso
contrário botou um né então a gente fez
isso para todos os as bases né de
precipitação aí que foram dadas
tá beleza aí
depois a gente treinou os modelos né
então aqui a gente fez para cada caso o
a 2 a estação a602 né aí aqui a gente eh
fez o o o treino né E aí a gente já usou
a variável transformada e claro né
tirando né todo o target né Para para
que o modelo não use né na quando for
aplicar no para dados não vistos para
que ele não use as variáveis
eh target tá então foi transformada e
também Foi retirada a original né para
poder fazer essa esse trabalho né aí a
gente transformou fez a padronização né
para deixar na mesma escala depois a
gente usou aqui um Gradiente bushing com
100 árvores né no nosso ensemble né e e
depois a gente aplicou para dados não
vistos né obteve um Recall de
84.3 né aí aqui a gente pode ver aqui O
legal é comparar o F1 né porque como a
gente tá com dados balance
desbalanceados né o F1 ele produz
resultados que são mais interessantes né
que é uma média harmônica do Precision e
Recall né então mais interessante pra
gente trabalhar aqui né para ver a
métrica que melhor performou né o modelo
que melhor performou legal e assim foi
feito para todas as bases tá então o o
gradiente boosting foi aplicado para
todas elas né com 100 árvores né mesmo
quantidade de de Hiper parâmetros também
no modelo né
beleza
Eh e vamos ver aqui no final né o
nosso deixa eu ver aqui se eu comparei
Ah é eu vou falar pro casa a casa aqui
porque eu não cheguei a fazer um resumo
aqui mas vamos lá então o F1 score daqui
foi 91 foi 91% né 091 tá da da 602 né da
621 no Gradiente bushing foi 095
né do
627 foi 092 também do
636 foi 094 né e do
652 foi 096 né então os scores aí bem
bem interessante de F1 né E aí agora que
que a gente vai fazer e só destacando
aqui que houve também falsos positivos
né claro né Beleza então o que que a
gente vai fazer agora a gente vai
aplicar técnicas
de balanceamento né então para trabalhar
com oversample a gente vai tentar
produzir de forma sintética né
observações para que a gente consiga
melhorar né Essa estimativa aí do R2 e
ver as métricas aí né células melhores e
tudo mais né a varredura dos dos
limiares a gente não não acabou não
conseguindo fazer aqui tá aí beleza
então nós transformamos aqui a gente
aqui a gente usou as variáveis
transformadas né só puxei aqui só para
para ter novamente aqui para ficar mais
fácil aqui de gravar o vídeo né mas a
gente já tinha transformado
antes Beleza então a gente fez aqui o o
over sample né e comparou então Ó
igualou aqui as classes né ó
ã ó antes a gente
tinha
9366 pra classe negativa e para cá
positiva 9914 né E por meio do Over
Semple né a gente aumentou isso para
9366 E 9366 então a gente balanceou o
dataset né E aí vamos ver se produz
resultados melhores né então basicamente
eu já adianto aqui né que todos os casos
produziram resultados piores F1 score
0,70 todos ali abaixo né se você for
lembrar todos foram acima de 90% ali em
cima né aqui foi tudo 0,70 e pouco 0,80
e pouco né então nenhum deles produziu
F1 scor melhores né então
eh não não não foi útil né Essa técnica
para fazer essa
eh esse trabalho né então todos os
resultados foram piores quando criados
dados sinteticamente por meio do Over
sample né comparando tanto as métricas
de acurácia como também o F1 né então
também a acurácia também né a gente pode
ver que não melhorou tá beleza então
Eh conjunto de dados de balanceados
parte dois né então aqui foi pedido para
fazer meio que uma regressão condicional
né Então primeiramente a gente
fez a codificação né então quando foi
zero a gente colocou um e quando foi e
quando foi E caso contrário foi zero né
então a gente inverteu o que a gente
tinha feito antes né que foi solicitado
então a gente fez isso para cada base né
transformou as variáveis né aí logo
depois a gente criou um um um um v0 né
que é um um modelo de inicial de
regressão né com os dados contínuos
mesmo né da variável original né a gente
fez lá e aí o r o R2 deu 0.02 né um R2
bem fraquinho né a gente sabe aí quanto
mais próximo em módulo de um né mais
próximo eh eh mais mais poder preditivo
tem o modelo de regressão né o map Foi
bastante grande também né por
consequência né porque errou muito né e
o min Square erro também né Beleza então
Eh vamos vamos ver
aqui vamos aqui a gente vai criar uma um
modelo de classificação que a gente
escolheu aqui regressão logística né E
aí a gente classificou né E todos os
resultados que deram um né independente
dele ter acertado ou não né ou seja o 18
ele acertou né Então ele acertou o 18
mais 15 ele errou né então
eh a gente pegou todos esses esses 33 né
então todos esses 33 foram e a gente
pegou aqui né para poder a gente pegou
os índices deles né na a gente fez a
predição do modelo né pegou os índices
que correspondentes à linhas né do data
7 depois a gente pegou isso e treinou o
nosso regressor né então para cada caso
em que a gente obteve um no na predição
a gente obteve aqui o nosso regressor em
cima dessa dessa análise aqui que a
gente fez né então a gente obteve um R2
negativo né que quer dizer que o modelo
Tá pior do que a própria média né então
fazer a média aqui né ou fazer o modelo
tanto faz né o modelo tá melhor
Inclusive a média tá melhor do que o
modelo né então nem nem É aconselhável
fazer o modelo aqui nesse caso né então
não houve uma um aumento da da poder do
Poder preditivo do modelo e assim foi
feito para todos eles né E também né Ó o
R2 foi 003 na na estação 021 né e depois
de ter feito o regressor condicional foi
para
-7.5 também né todos eles ficaram
negativos após a a regressão condicional
né então Ó 0.02 depois foi para esse no
caso é o 627
né foi
para -13 né e assim por diante né então
ó 0.02 também foi para na na última né
que é
o Cadê Deixa eu ver aqui 636 né foi para
-23 e o 652 de 007 007
0,007 também foi para para negativo aqui
né então ó -
2.09 tá então a gente viu aí que não não
deu muito resultado né fazer essa
criatividade aí
beleza calibrando calibração de modelos
aqui então na cinco né então a gente fez
aqui o o calibration Curve
né e a gente aplicou né só que a gente
tinha criado com Gradiente Bush né como
o professor pediu com Gradiente Bush só
que o gradiente Bush ele já vem
calibrado né então já era se esperado né
que ao fazer uma calibração né que a
gente fez aqui com a regressão a
regressão logística né usando sigmoid
aqui ó calibrate classifier né
Eh
a
gente não obteve ó grandes melhoras né
claro né não tem almoço grátis né
aumentou aqui o Recall né e o F1 mas a
precisão né
ela diminuiu né então eh não tem almoço
grátis né se seu problema de negócio for
interessante né você maximizar o Recall
né seria interessante você calibrar né
caso contrário não né
Beleza validação cruzada alinhada aqui
na seis né então a gente pegou o
diamante a base do diamante também né E
aí aplicou aqui a a a validação cruzada
alinhada para dois algoritmos né que é o
laço e o renult Forest né e o laço a
gente usou o hiper parâmetro Alfa né com
esse essa configuração aqui dos
parâmetros né da grade para ele buscar e
o o a da árvore né a a profundidade da
máxima da árvore né então também aqui
baseado aqui na documentação do C kit L
os parâmetros os hiperparâmetros né que
são necessários aqui pra gente trabalhar
para ver qual é a melhor configuração né
aí a gente aplicou aqui e aí o resultado
né a gente comparou aqui nos três alfold
né as métricas do msr né E aí aqui em
média né né ó ele teve
menos 3 mil
32580 né e o laço ele
teve uma média
de menos
[Música]
eh não calma aí é é aqui é 30 30 milhões
325 não eh 3.
32580 aqui é 6
6175 180 né então foi então foi menor né
o do laço né Portanto ele foi o melhor
modelo né ele teve o melhor MSE né ele
teve a melhor estimação do erro de
generalização né quando a gente fez aí o
cross validation né e o hiper parâmetro
selecionado foi o alfa iG 10 né a gente
produziu a gente fez a segunda abordagem
né a gente fez o o
aqui
o o Grid search você v né a gente
aplicou o search e depois a gente fez o
Fit do do final regressor né então a
gente aplicou a abordagem dois
aí que foi ensinado aí pra gente né
então o melhor modelo escolhido foi o
laço com hiper parâmetro de 10 e o erro
de generalização foi esse aqui né bom
então é isso né a gente termina aqui o
nosso a nossa tarefa um né Vamos pra
próxima valeu Professor tchau
tchau