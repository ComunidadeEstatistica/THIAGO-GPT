# Aula 05 - Glm classificacao treino - Prof. Flávio Clésio

- **URL:** https://www.youtube.com/watch?v=BZl_c8LKqNI
- **ID:** BZl_c8LKqNI

## Transcrição

e colocar mais ativados tudo bem aqui eu
flávio clésio e agora eu vou falar um
pouquinho sobre glm a na parte de
classificação mas antes de mais nada
para quem não é inscrito no canal se
inscreve no canal agora conteúdo de
altíssima qualidade a estatística
avançada abrir a saenz visualização de
dados mach lane por aí vai tudo em
português na faixa totalmente e
altíssima qualidade que não deve nada
para nenhum tipo de conteúdo gringo tá a
e a segunda coisa que todos esses
códigos todas as historias estão com no
kit rubi nesse nessa nesse endereço aqui
para quem é já é usuário do kit rubi só
fazer o forte do repositório e tá quem a
quer fazer apenas o download só clicar
aqui nesse botãozinho verde clone o
download escolher a opção download z tá
certo então vamos pôr em estúdio fui
a coruja lm no modelo de classificação
da antes de mais nada que ele é
ressaltar aqui que a toda parte de carga
de dados desse vídeo e de todos os
outros vídeos subsequentes vai ser eu
vou dar só no escrito só vou dar muito
rápido a devido ao fato de que o foco
nosso aqui vai ser trabalhar com h2oh no
r&amp;b realizar esse modelos em produção ao
invés de fazer repetir o mesmo processo
de carne de dados tá certo então vou
passar aqui rapidinho vou fazer a carga
biblioteca h2oh nossa semente a do homem
que vai ser de 42 eu vou inicializar o
pós ter o nosso cluster está
inicializado e só chega aqui local host
em 5 4 3 2 1 ou não flor já está
operacional aqui o meu curso nos status
o status nossos ter a costura
operacional tudo certo vamos por código
e como a gente já viu na parte de carga
de dados vamos pegar nós url aqui do
nosso banquinho a digitar nossa base de
empréstimo do lehman brothers vamos
chamar aqui o objeto a o método spotify
vamos carregar o nosso os nossos dados
do lehman brothers aqui no nosso ponto
aqui no ponto rex tá então aqui tá barra
de progresso sem por centro a gente já
tá com o nosso rex a faro aqui do nosso
lehman brothers o contexto aqui vamos
executar somente a base e a gente tem
que todas aqui a gente tem uma entrando
sunrex aqui né os primeiros registros da
base da área então tem as variáveis
categóricas o que a as variáveis
contínuas e o nosso só variável de fosse
se a pessoa entrou na situação de
inadimplência ou não tá a primeira coisa
que a gente vai fazer aqui para o nosso
só para nossa base de dados vamos passar
a essa variável de fotos
se conectar onde vai usar a o método as
teclas e tudo é e deixa redação sobre a
que a funcionar ativa do erp só por um
double check e depois ver que nosso
deixou aqui já tá com 101 então já tá
reconhecendo com sua variável categórica
e posteriormente a gente vai agora fazer
divisão na nossa base de dados entre dez
porcento para base de teste e noventa
porcento para base de treinamento usando
o objeto o método a explique friends and
quiser saber o que esses picture em paz
ponto de interrogação seleciona o método
executa e a gente vai ter aqui todas as
informações a da descrição do que faz
então esse aqui esse esse método serve
só para fazer a importação dos dados
dentro do classe do h2oe esses dados vão
tá a totalmente distribuídos dentro do
câncer no meu caso estou usando uma
máquina stand alone mas se ocupa
nem parece mais duas três quatro
máquinas a gente de computação do h2oh
faria distribuição desses dados para
saber mais sobre arquitetura pode ir lá
para o primeiro vídeo que lá eu explico
em detalhes como que funciona a parte
arquitetura interpretador e o que que o
h2 with por debaixo do capô nesse caso
aqui eu vou criar um objeto split
bom e no primeiro na primeira do
primeiro objeto espírito a primeira no
primeiro fogo né desse desse desse
objeto eu vou terminar a base de
treinamento aí se eu vou dar aqui uma
base de treinamento tem 26 mil registros
com 5 colunas e se eu pegar o segundo
fogo eu tenho a minha base de teste tá
no qual a minha base de teste eu vou ter
a pouco mais de 3 mil registros a minha
variável dependente aqui para o programa
de problema de classificação vai ser a
variável de fogo e as variáveis
independentes vai ser aí vão ser aí na
limite a gênero da pessoa está pegando
empréstimo education a nível educacional
né no caso se a pessoa casada ou não a
idade e as informações a relativas ao
crédito esse para saber mais sobre essas
variáveis de crédito recomendo que vocês
vão por para o vídeo de download que lá
eu dou explicação
é do quê que é a cada variável aqui
nesse vídeo a gente vai especificamente
tratado dos algoritmos então a gente vai
rodar que nós variável dependente e
independente as várias independentes e a
nossa variável dependente então seu ter
só fazer um double check vou dar o y
você minha maravilha de fotos eu vou dar
o meu x10 em várias independentes eu vou
ter aí as minhas as minhas variáveis
aqui como vocês vão ter no brasil são os
nomes das colunas então aqui a gente é
uma parte do treino do modelo então o
primeiro modelo que a gente vai treinar
aqui é o modelo de classificação de glm
primeira coisa galera vamos ver o que é
se método glm faz então ponto de
interrogação no método rodar e não ver a
descrição aqui ele fala que ele vai
fazer o ajuste de um modelo linear a
analisável ea que a gente tem alguns
parâmetros né então a gente tempo para
outro xy ac3
o nosso caso aqui nós treme treme a
gente vai usar a base em uma blog trendy
treinamento e algumas outras variáveis
aqui eu não vou explicar todos acho que
a a ideia aqui é muito mais pegar
algumas variáveis mais importantes
explicar para vocês rodar uma coisa que
eu recomendo para vocês que estejam
trabalhando não somente com h2 órgão
qualquer implementação de uma churn
evitem a usar a variáveis de fou da
maneira que eu estou fazendo aqui tá
aqui é somente contar com os com esses
atributos de for aqui nesse caso aqui eu
clico a qual as vale deixa rodas como tu
aqui próxima ele deixa eu perdi uns como
falsa a porque a isso é uma boa prática
porque se essa vamos imaginar tem que tá
usando os valores de show para cada para
cada tipo de algoritmo e aí por algum
motivo seja por alguma correção na
biblioteca seja por uma mudança diversão
oi gente tem a mudança do parâmetro hd
full por exemplo equivale a nesse caso
aqui vou subir uma variável aqui a alpha
por exemplo que a coluna que vai
controlar a regularização do modelo
a segunda aqui igual funk por esse pediu
para 0.5 se o meu modelo ele depende se
a de que esse valor esteja comum e tem
essa mudança a os resultados eles não
vão ser reproduzir vez de uma versão
para outra e aí eles são os grandes
problemas tanto com a linguagem enquanto
que o python que existem os valores de
fogo geralmente não são os mais
utilizados e geralmente a mudança esses
valores então o ideal é que esses que
esses que todos os campos que a gente
está vendo aqui a da do método esse eles
sejam declarados eu não vou declarar
aqui só por questão de simplicidade e
manter o código a pouco mais a um pouco
mais fácil para leitura mas o ponto é
que vocês tem que se atentar preciso
detalhes tá certo então meu torn frame
aqui vou chamar o lehman brothers trem o
meu x vai ser as minhas variáveis
independentes e meio y vá
a variável dependente a family aqui né
então a gente tem um família family
então family que a família de modelos
então aqui a gente tem a para
classificação né a como o logística
reversa e para variáveis dicotômicas né
resultado 01 ou binárias né a gente pode
usar tanto a loja creations como a gente
pode usar por exemplo o binomial e por
aí vai o the full desse nesse modelo
aqui é o galícia né que é porque é para
tratar de variáveis pontinha o nosso
caso como está trabalhando com variável
eu te conto no que a gente vai usar a
família e não me ao aqui como family tá
o alfa que a segunda variável que a
nesse caso eu vou usar a como eu quero
escolher a para usar a regularização ela
acertar ah então não vou é um meio termo
entre entre a laço e entrará ruidor
brecha eu
o ponto cinco aqui como alfa tá a mais
de novo isso aqui é muito mais a forma
que vocês vão estar com dados de vocês
eu não quero colocar uma penalização
muito forte eu quero fazer meio termo
ali para até mesmo ter todas as
variáveis no final aí com alguns
coeficientes a padronizados de magnitude
tão e o sítio obviamente aqui o sítio
vou deixar a os ide 42 como é que já
definiu no começo do skate então eu vou
rodar aqui o trem do modelo
é aquele tá fazendo treino do modelo a
gente pode aqui no flor por exemplo a e
a gente pode ir no job como já tinha
falado no na parte de arquitetura ela no
começo a nossa playlist cada vez que a
gente manda uma tarefa por para o a dar
o sol ele que nem um jovem então nesse
caso aqui a gente tem um gelo em modo tá
que esse módulo com acabei de executar
aqui no colo e levou aí mesmo meio
segundo para para ser executado e se a
gente quiser ver aqui no flor todas as
informações a do modelo em relação à
performance tudo mais é só a gente vir
aqui nesse actions clica aqui na opção
viu e a gente tem primeira coisa
parâmetros do modelo então aqui tem o
nosso cid tem todos os parâmetros o alfa
que nós escolhemos o lâmpada o número de
interações e por aí vai o score do
modelo então histórico então como que o
modelo convergiu através da de cada uma
das interações e aqui a gente tem a
parte de
é a da curva roc no modelo né nesse caso
aqui está tendo a área abaixo da curva
de pombos 72 que não é é melhor que
aleatório mas não é tão bom assim
e a gente tem um gráfico aqui em relação
à os aos as magnitudes dos coeficientes
de magnitudes padronizados né então a
gente tem o que tiver azul aqui tá como
um sinal positivo então é mais significa
que está influenciando de uma forma
positiva lá no na probabilidade final
nós da classe lá no caso 1
e aí o laranja da classe negativa né
então a gente pode ver aqui que a
variável que tem mais importância aqui
nesse caso o pênis ir né então o
primeiro pagamento é o que vai
determinar aí a grande parte das vezes
não grande parte das vezes mais tem um
grande a preditor de gamas assim se o
cliente vai entrar numa situação de
inadimplência ou não e algumas outras
informações aqui como por exemplo a o
pagamento aí o a malte pagamento nos
primeiros nos primeiros meses e a o
principal né ao sol do principal da
dívida a depois o primeiro pagamento e
aí tem vários outros a fatores
preditores aqui para que a gente pode
ver aqui de acordo com os coeficientes a
aqui tem um gráfico de algumas métricas
de treinamento né no caso a parte dj
militar né isso a gente quiser por
exemplo a ver o out do modelo né em
relação ao aos vá
bom então é uma modelo de categoria
abdominal né aqui tem algumas
informações aqui do holanda no do melhor
lambda
me chame de chover aqui algumas coisas
então como eu tinha colocado
anteriormente momento eu coloco o alfa
de 05 ele automaticamente ele leva em
consideração que eu tô usando uma
regularização do tipo elástico aqui é um
meio-campo ali entre o meu ter uma linha
entre a laço né que o hélio nosso l1 e o
rígido acham que é o nosso l2 tá no caso
laço ele tem uma penalização a um pouco
mais forte né porque ele pega a o valor
absoluto do coeficiente e o luigi ele
tem organização um pouco mais branda
porque ele tem ele não faz pelo valor
absoluto ele faz por um o valor relativo
da variável em relação a importância
dela no modelo tá a então a gente
consegue ver tudo isso a dentro aqui do
do flor né e de novo né como eu tinha
falado na parte de arquitetura né a
partir do momento que a gente faz um
modelo a dentro da suíte do
oi e a gente tem por exemplo a
plataforma java plataformas escrita em
escala a gente pode somente transpor
esse código aqui e os engenheiros de
software consegue implementar a esse
código direto na sua na sua plataforma
de produção que a imagina que em vez de
ter um serviço a uma espiã que os
cientistas de dados ou seja ele de uma
celular e teriam que manter essa
plataforma o sentido de dados aquele
treinar esse modelo a engenharia e cadê
aqui nessa nossa opção aqui a proibiu
cuja que é o objeto java que é gerado
que uma classe java né que nesse caso
aqui já teria todas as informações das
variáveis por exemplo do nome do modelo
o número de classes que tá sendo a é
resultado essa petição lá no no caso e
como a variável dicotômica é 1001 então
a gente tem duas classes e aqui todas as
informações aqui de como que vai a vão
ser os cálculos de cada um
a pacientes que a vão ser multiplicados
ali a os valores que foram passados os
modelos então é somente estrangeira
sobre esse bojo e o engenheiro de sofre
já consegue embutir esse esse modelo
dentro dessa aplicação em produção
botando aqui de novo para o nosso r
então a gente aquele nosso modelo a
gente consegue ver as mesmas informações
que a gente viu no flor a rodando saint
mary em cima desse modelo então a gente
pode ter que deixou só fazer os trolls
para cima então a gente tem nosso modelo
aqui o nome do modelo a modelo binomial
regularização elástico né las kinect na
número de variáveis independentes 23 na
esse aqui é o nosso trem firme porque a
gente quiser ver se esse treme treme por
exemplo a gente pode a e nos jobs para
deixa eu vou para quê
e aí
e nos jovens a gente consegue a
encontrar aqui dentro nosso modelo aqui
frame né então deixa eu pegar aqui a
flashy sports pack pode ver aqui esse
som as informações modelos parâmetros e
por aí vai voltando aqui a nosso caso
como a gente tá rodando uma uma
classificação lá então para gente que o
mais importante aqui no caso ó se a
gente tem as informações tanto de vida
confio jumento não é de da matriz de
confusão a dos verdadeiros positivos
posso positivos e ea relação entre entre
essas métricas a
e em relação à ao f1 score né por cada
uma das classes que a gente tem aqui que
a gente pode conferir o histórico das
interações o histórico das interações na
conta nesse tempo o score né a de acordo
com o negativo ao blackwood a e também a
parte de a importância de cada uma das
variáveis para proteção né então aqui
como a gente haviam anteriormente lá no
flor a gente tem aqui o pé mente zero eu
amar um último ano um p a mão número 2 e
assim sucessivamente e as variáveis que
tem menos importância o pagamento patro
o principal né o saldo remanescente da
parcela seis e da parcela as seis a
também tá certo então tudo isso a gente
consegue pegar somente usando o samurai
os ovos ea gente quiser fazer as
predições nessa gente quê
o valor quem pode fazer é usar esse
objeto aqui o perfect né que o objeto
perdido do h2olhos vai precisar somente
do objeto que nosso caso objeto vai ser
o modelo e do conjunto de dados que a
gente vai passar aqui no nosso caso aqui
vai ser o teste né vai ser nossa base de
teste que a gente vai a armazenar tudo
de dentro dessa dessa deixa objeto
prédio então deixa eu voltar aqui e se a
gente fizer uma verificação rápida no
nosso próprio objeto aqui ele vai trazer
para nós é somente os primeiros
registros né e vai prever aí de acordo
com os registros da então primeiro
registro não vai ser um caso de forro o
segundo não vai ser o terceiro vai ser
um caso e vai ter a probabilidade do
zero e do um aqui que no caso do do
nosso zero aqui do primeiro registro
você tem é quase setenta e nove porcento
de chance de não haver etana
e vocês não teu the fold e somente 21
por cento a de probabilidade que vai
estar no nosso o nossa classe um que no
caso vai ser a parte de inadimplência a
e todas aquelas métricas que a gente viu
no samba a gente pode tirar dentro
usando esses objetos por exemplo com
fingimentos por exemplo então h2.com
physiometrix e a gente chama nosso poder
a mesma coisa de importância de variados
chamando o método varimpplot
bom então a gente consegue ver o plot a
dos dados aqui tá isso que tem os
objetos pelas mãos era a e também a
curva roc chamando aí a pouco já ter
formas passando o nosso modelo em nossa
base de teste e o tipo de gráfico que a
gente vai a selecionar aqui vai ser o
gráfico de curva roc que é o mesmo
gráfico que a gente viu lá no flu então
todas as essas informações a impedir
modelo a gente pode tanto pegar que via
programação quanto isso vai ficar dentro
do histórico a do flor em relação ao
treinamento desses modelos a na medida
que a gente vai testando e vai e vai e
vai apurar esses modelos a gente tem
mais registros de óbitos a gente pode
ter o histórico tanto dos paramos quanto
dos resultados desses modelos certo
a a a gente tem também as informações da
perda de modelo e informação do voz e da
área abaixo da curva que é de pão dos 70
agora quero passar por um ponto aqui que
que eu acho que é importante que a parte
de salvar o modelo em produção mas eu
vou fazer isso no próximo vídeo para
ficar um pouco mais claro esse consertar
certo então eu espero vocês no próximo
vídeo