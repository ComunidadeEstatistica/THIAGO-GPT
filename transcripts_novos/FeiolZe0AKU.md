# Prevendo doações de sangue - Prof. Vinícius Galvão

- **URL:** https://www.youtube.com/watch?v=FeiolZe0AKU
- **ID:** FeiolZe0AKU

## Transcrição

fala pessoal vinícius aqui novamente
mais uma vez eu quero agradecer ao
professor tiago pelo convite para
compartilhar aquele roteiro com vocês e
alguns meses atrás eu conhecia as
ervilhas é uma startup que utiliza a
data site para ajudar bancos de sangue
em hospitais a diminuir em falta de
sangue e economizar é através de
decisões dinâmicas com base nos dados
mas entendem melhor o problema é que
eles estão resolvendo e eu vi que a
previsão de suprimento de sangue é um
problema sério e recorrente
para o gerente de coleta de sangue e só
para você ter ainda havia quantidade do
ministério da saúde 2018 um regular e 6%
da população brasileira doa sangue
isso significa um índice de 16 jogadores
para cada mil habitantes e assim esse
porcentual de doadores está dentro dos
parâmetros da oms que ele estabeleceu de
pelo menos 1% da população embora a
gente esteja dentro desse padrão de
doação é recomendado administração
trabalha para ampliar o número de
doadores principalmente de doadores
regulares
só para você ter uma idéia a anvisa
divulgou idade que mostra que
aproximadamente 43% das doações que em
2007 foram da primeira vez em 42 por
cento a gente fala de repetição e 15%
foram explorados são exatamente os
doadores regulares que mantém um banco
de sangue estabelecidos ao longo do ano
então como é que a gente pode aumentar o
número de doadores e não só aumentar o
número de doadores mas também reter
esses doadores possível solução é
prevê-se um doador vai voltar a doar
novamente e criar estratégias baseadas
nestes dados nesses sites dessas
informações
e hoje eu quero trazer para vocês um
projeto onde a gente vai prevê que é
provável que um doador de sangue doe
novamente nesse projeto a gente vai
trabalhar com dados coletados do banco
de dados de doadores no centro de
transfusão de sangue da cidade de taiwan
você pode encontrar tanta fé é um
repositório de aprendizado de máquina
acessam por este link
mas enfim ele possui informações de 148
doadores nossa tarefa é prevê-se um
doador de sangue vai fazê lo do sol
dentro de uma determinada janela
de tempo vão começar carregando nota 7
visualizando as cem primeiras linhas
deles e além do formato dele para a
gente ter uma noção melhor de como é que
a gente está se tratando aqui
bom aqui vejo que a gente tentar a 7 com
cinco colunas
a primeira traz a referência que é a
quantidade de meses desde a última
doação
a gente tem informação da freqüência que
é o número total de doações que esse
doador fez depois a gente tem um valor
monetário que monitore e dady que a
quantidade total do sangue doado por
esse doador
depois do tempo em meses desde a
primeira doação e por fim há informação
se o doador feijão boston e março de
2017
e se você já trabalhou na área de marco
de um projeto pronto você já escutou
falar ea rfm que a junção das três ilhas
recência freqüência e monetária w
e essa técnica permite que você entenda
melhor o seu cliente vai ficando com
apoio de uma compra dele
quantas vezes ele comprou e o quanto que
gastou com sua empresa trazendo para o
nosso problema com esses dados a gente
consegue entender melhor o doador para
que colombo foi a última doação dele
quantas vezes ele do que o quanto de
sangue que lhe do caso e se nós tanto
assédio a gente tem uma variação da rfm
é o rrm etc
quero ser um tempo ea taxa de
rotatividade mas nosso foco aqui nessa
hora é criar um modelo capaz de prever
se um doador irá voltar a doar novamente
nessa janela do tempo estipulado
então vamos começar pressionando algumas
informações no nosso time para a gente
começar a utilizar o método info
vamos ver que todas as variáveis são do
tipo inteiro ele não possui idade
faltante nossa neta frei
agora vejo que nossa última coluna que
possui um nome muito grande então vamos
alterar esse nome para algo mais simples
como targa por exemplo
para isso a gente pode utilizar o método
no name e passar um dicionário para 1
para 8 colo vai ficar dessa forma aqui
então como eu disse que a gente passou
de cenário para o método cloud contendo
o nome da coluna em seguida o nome que
você deseja colocar ou sem ritmo o
método in place para que a operação seja
feita no próprio da free beleza agora
vão visualizar a proporção das pessoas
que doaram e de pessoas que não doaram
no mês de março de 2017
para isso a gente pode utilizar o método
vale causa dessa forma
e é que a gente configurando para 8 não
mais em quatro
a gente faz com que ele retorne os
valores em porcentagem
não vejo que 76% dos dois não doarem
mais 2007
a gente pode visualizar isso em forma de
gráfico de baixo também apenas usando um
método próprio
dessa forma
ele agora tem um gráfico de idade
representando essas porcentagens classe
zero representando um sinal do ar é
fácil representando apresentam os
doadores que doaram em março de 2007
fazer um segundo aqui e vamos separar
numa coisa de idade entre 13 e 10
utilizando mais de 30 split
e aqui vai só a gente passa da frame
excluindo nossa como eles ainda como o
primeiro parâmetro e passará longe de
sair da escola de resposta como o
segundo para 18 com segundo argumento o
tamanho do conjunto e teste como
terceiro argumento que eu configurei
para 25%
em seguida também da aleatoriedade que
configure a 42
e esse é um argumento vai fazer com que
todo o conjunto treino conjunto de teste
tem a mesma proporção de doadores e
odores ou seja todo o conjunto treino
enquanto de testes terão 76% e
inovadores e 23% e doadores
pronto agora a gente tem na cidade
prontos para serem passados pra nosso
modelo
neste caso ele utilizou logística grécia
e para a gente entender mais a fundo
como funcionou a gente gosta na hora
daquele cidadão que eu fiz pra gente
entender aquilo que a gente tem a
informação da freqüência de boston onde
cada doador o xixi ea classificação
informantes ele doou em março de 2007 um
problema de classificação binário ea
gente uma atrocidade a gente vai ver que
todos os dados montar em 0 ou em 1
agenda digital a reta representa na
função linear que discrimina cidade
assumindo o limiar de 0.5 por exemplo a
gente consegue fazer um trabalho até
razoável e aqui para você entender como
é que funcionários classificador a gente
tem um valor de freqüência de doação com
valor de entrada ou seja um valor xis
aqui no gráfico ea gente faz uma reta
perpendicular à x até tocar o washington
com isso a gente teve um valor único que
vai estar entre 01 e valor de y formal
quiser 1.5 praticado faria uma predição
que o doador irá doar novamente em março
de 2007
já sei como enoque 0 com cinco agora que
o classificaria o doador não olhe
novamente em março de 2007
então praticamente que ele está fazendo
aqui é que dá uma outra freqüência eu
vou ter um valor de r 70 em um esse
valor for maior que zero pontos cinco à
força o vasco sabe que o doador irá doar
novamente em máxime 7 foi menor 0 com
cinco e não ir à doha mas aí a gente tem
mais na questão
é alterar a nossa cidade a hotelaria é
um dado que o valor muito distante de
todos os outros beleza e perceber que
agora veja como é que fica o gráfico com
malte lá é perceber que agora a gente
tem doado com a freqüência bem alta
comparado com os outros já é com a
justiça que está representando a
freqüência doação e como essa moça bem
pra direita quer dizer que ela tenha
freqüência bem alto bem assim um bem
maior que os outros doadores e como ele
está aqui em cima representando a classe
1 ou seja que é ligado à imagem 2007
porém se a gente usar essa mesma
abordagem com a cabeça explicar por
exemplo nome é de classificação livre
por cinco agentes de todos esses
jogadores aqui seriam classificados como
da classe negativa tá bom então por
exemplo essa linha veja aqui que a gente
pode chamar de fronteira decisão é uma
peça na fronteira decisão não altera a
decisão bem melhor nessa linha amarela
porque ela está conseguindo separar bem
os que doaram que não doaram e aí que a
regressão logística em cena e para lidar
com valores dos relevantes à regressão
há gente que usa a função sigmóide eu
não vou entrar muito a fundo como essa
função funciona mas ela tem uma forma de
s com essa cara aqui fazendo o resumo da
obra agora utilizando agora foi
conseguir mole pra ficar noiva lojas a
gratificação é que a probabilidade de
saída positiva o maior 50% então a morte
classificada como positiva ou seja a
pessoa seria classificada como uma
pessoa com grande chances e doar
novamente em massa mistério mas chega de
teoria e vão botar a mão na massa vamos
treinar nosso modelo de negócio
e é que por ter um modelo de saque
telefone em seguida cria uma nova
instância - cresce ea gente tem um
modelo com nossos dados de treinamentos
stream e entrei agora formais e nas
pressões coisa de teste
o objeto chamado y clube
pra isso eu te dizer o método permite um
modelo ajustado
agora vamos valorizar mas teve confusão
pra te ver como é que o nosso modelo
está performando para isso vai utilizar
o módulo médico não consegue chillán
vg que utilizam mais do corpo médico do
do pacote médicos e passei as respostas
verdadeiras respostas pedidas em seguida
o visualizar uma teve confusão aqui
caso você não lembra o que significa
cada um desses valores fica tranquilo
que eu vou plantar um diagrama aqui para
aceitar nosso entendimento o melhor
técnico de lune teme que a gente pode um
diagrama que facilita bastante a nossa
vida e olha
então vejo que as amostras aqui no canto
superior esquerdo fez verdadeiros
negativos vocês doadores que não doaram
num período de 2007 e foram
classificados corretamente mas a mostra
do quanto é sério o direito só espera de
dispositivos ou seja os que doaram e
foram classificados corretamente
já os amantes do canto superior direito
são os falsos positivos ou seja que não
doaram mas foram classificas
incorretamente e as amostras enquanto
inferior esquerdo são os falsos e
nagasaki vocês são os doadores que
doaram mais qualificada prejudica eles
não doaram vejo também que a gente teve
um alto número de falsos negativos e
aqui eu quero levantar a discussão vocês
com a situação que você considera mais
crítica para essa aplicação aqui um
classificador que tem mais falsos
positivos
o mais falso negativo agora pensa comigo
o falso negativos e os doadores que
votaram do imax m7 mas modelo prévio que
eles não viriam logo a seguir doações
das pessoas seria um plus não é assim
já os falsos positivos como eles são
jogadores que não voltarão a atuar em
mais de r 7
mas o modelo previu que eles voltariam a
então se gere coleta de sangue estavam
contando com as situações ela não
ocorreram e isso pode ter trazido muito
mais problemas pra eles
então eu acredito que é muito mais
aceitável que a gente tem muito mais
fácil enganar filho o que faz positive
sendo agora mais como gerente de coleta
que você acha que poderia fazer com as
informações aqui é dinheiro olha só
porque a gente tem informações de
contatos de cada um desses doadores que
a gente poderia fazer parte desse já
dizia que a componente personalizados
para esse grupo que a campanha
segmentada ao grupo que tem a habilidade
do a novamente para algo que tem uma
nova unidade pois a gente conseguiria
montar uma estratégia para aumentar o
número de doações em um período
específico de um ano por exemplo
além disso pode permitir um maior
planejamento no quarto e gestores
facilitando o controle de estoque
diminuindo desperdícios bom pastor acho
que é isso espero que vocês tenham
gostado mais uma vez agradecer o
sorteado pela oportunidade
se você quiser conhecer o trabalho no
canal do youtube que você vai encontrar
muito mais conteúdo como esse abraço e
até mais