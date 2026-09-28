# Aula 12 - Trading System com Quantomod Library - Curso de R para Finanças Quantitativas

- **URL:** https://www.youtube.com/watch?v=RiMXHcINcmY
- **ID:** RiMXHcINcmY

## Transcrição

[Música]
fala pessoal sejam muito bem vindos aqui
ao tronco e marketing sejam muito bem
vindos ao curso de r pra finanças
quantitativas
hoje a gente chega na aula 12 onde eu
vou mostrar pra vocês como construir um
primeiro trade system utilizando a
biblioteca conte molde que eu expliquei
pra vocês na aula 11
muito obrigado pra todo mundo que está
sim no canal documentários feedbacks
realmente fico muito contente de
contribuir para a comunidade
bora lá por r estúdio e vamos entrar
aqui no código para ver como é possível
criar em poucas linhas com tudo o que eu
mostrei pra vocês nas últimas onze aulas
essa estratégia utilizando a ponte móvel
então eu uso parte do código anterior
onde eu carrego a biblioteca com timóteo
aqui em cima
carrego a biblioteca ttr 12 indicadores
técnicos seleciono o período de análise
se você não está familiarizado com essas
expressões assistir à aula 11 que eu vou
deixar o código o link aqui no primeiro
comentário selecionam alguns ativos
o índice bovespa o bitcoin ea petrobrás
captura os dados e piloto os gráficos
então vamos rodar que esses primeiros
códigos você vai chegar exatamente a
esse gráfico aqui da petro quatro anos a
gente tem de 2017 janeiro até 18 de
setembro de 2018 um gráfico aqui de que
nós da petrobras com 1m aceder
um dos indicadores técnicos que existem
aqui na já disponível no gráfico então
um gráfico aqui bem bacana bem bonitinho
pra vocês como a gente cria uma
estratégia baseado nisso aqui vamos
fazer primeiro o seguinte definir tem em
mente o que é estratégia
uma das coisas que podem ser feitas
começam com m a c d e e que não estou
falando que
a única uma das várias que podem ser
feitas
é a gente criar uma estratégia onde se o
é o valor atual do mst foi menor que a
linha do sinal do msc de ou seja se o
valor
esse aqui que você está vendo no gráfico
em aceder for menor que esse valor
vermelho do sinal a gente entra vendido
e se ele for maior
a gente entra comprado eu vou usar essa
suposição pra fazer o trade
existem outras possibilidades e e
convido vocês a usar a criatividade com
um dividir aqui com a gente e quais são
as outras idéias que você possa ter pra
fazer um de this is it baseado nesse
indicador
então como que a gente faz isso primeiro
eu tenho que criar uma variável que vai
receber esses valores do msc de quando
eu fiz o ied é minha cd aqui em cima da
linha 22
eu apenas adicionei no gráfico mas agora
eu quero criar uma variável que vai
carregar essas indicações então chamado
aqui dia minhas e de onde eu vou chamar
a função e me a cd que ela vem da
biblioteca tr como você pode ver aqui no
próprio estúdio indicando e ele já tinha
mais ou menos a sugestão dos conteúdos
sempre repito pessoal sempre use a ajude
o suporte do estúdio quando você tem
dúvida porque ele explica exatamente o
que você tem então que ele já fala que
você tem o período da média rápida e me
festa igual a 12 o período da média
lenta e no slow igual 26 o período do
sinal 9 que geralmente são as
configurações de fogo desse indicador
então vamos usar isso e eu vou passar
como dado a nossa cotação de fechamento
da petrobras então quando eu clico aqui
na petrobras que a gente carregou os
dados
a gente vai ver que a gente tem os dados
de abertura máxima mini fechamento vou
pegar os valores de fechamento ok então
o msd vai receber os valores de
fechamento da pedra 14 s a
então eu uso como a gente viu nas outras
alas o o o indicador aqui do cifrão é o
sinal do cifrão para pegar o cruzeiro
que é o da dasju
momento e vou colocar os sinais padrão
do msc de então o período da média
rápida e manifeste ver que ele sugere
aqui pra você você economiza até tempo
digitando tão perto aqui em tnt fest vai
receber 12 o sinal a média lenta do mcd
vou pegar de período 26 e o período do
sinal da minha cd vai ser exatamente
nove e o tipo da média móvel então amy a
type eu vou escolher a média móvel
simples com a variação percentual que eu
não vou querer vou colocar como f de
falso quando executa essa linha de
código ele cria quem vai realmente o
sinal do mcd exatamente o valor do meu
cd que esse aqui do gráfico em cinza eo
valor do sinal que é esse em vermelho
porque tem enem nas primeiras
informações porque o mst só vem a ser
calculado só depois do valor da da média
maior aqui de mais longa que é a de 26
pilotos então só lá a partir do vigésimo
sexto dia ele vai ter os dados completos
aqui ótimo criado o indicador msci de eu
vou criar então a regra pra gente fazer
o trecho então vou criar uma outra
variável chamada the trade room onde
aqui eu vou usar a seguinte coisa lembra
que eu sempre expliquei nas aulas não
necessariamente só que no curso de r mas
nos outros vídeos do canal sempre que
você desenvolve um modelo você precisa
atrasar aquela informação para você não
fazer prevê tentar prever um 3d baseado
em informação futuro baseado na
informação que está exatamente agora
então não quero prever o dia de hoje
sabendo o que aconteceu hoje não tem o
menor sentido a mesma coisa jogar na
loteria sabendo o resultado
então eu tenho que atrasará as
informações para eu conseguir sem nenhum
viesse tentar entender o tal do futuro
então eu vou usar aqui uma função que
tem na biblioteca com timóteo e chama
leg elet significa atraso então ele vai
automaticamente atrasar aquele sinal pra
gente fazer isso na tabela então vou
usar alegre mas usa alegre do que
a regra de trade então lembra que eu
falei que a regra de três tem é se o
valor do mst foi menor que o sinal é o
medo senão eu compro então eu vou usar o
if é ou se que é exatamente fazer essa
condição que eu estou te falando então
se então que tal significa e fiel sintam
sintam-se o m a c d
o valor do m aceder certo for menor que
o sinal do msc de então chama m a c d e
e chamo o sinal tá aqui embaixo se essa
condição for verdadeira eu vou colocar
menos um que significa que aquele
retorno do dia foi vai ser negativa em 3
vendido
senão ele vai receber 1 e gero a nossa
variável tranqüilo quando eu vejo ela
tem oleg um funciona e aí a gente tem
aqui o preenchido com um e menos um que
foi seguindo a condição que a gente
colocou ótimo agora o que a gente vai
fazer lá no calcular o retorno da
estratégia e ver se ela perfumou
carleandro é só isso sim é só isso para
você avaliar esse tipo de estratégia
r é maravilhoso essa biblioteca é muito
legal pra fazer esse tipo de coisa
como você calcula os retornos bem como
criar uma variável chamada retornos
simples assim onde eu vou usar a função
que calcula esses retornos
automaticamente pra mim que é chamada de
rock
então essa rock ela vai calcular nem à
taxa de 1 de nerd mudança do top team de
uma série de um determinado período
certo então eu vou colocar eu quero
calcular essa taxa que é esse retorno do
nosso pec 14 s a
pegando o valor do fechamento
só que aí eu multiplicar esses retornos
pena a nossa regra de três que a gente
colocou o trade lo feito cara tá feito
você tem aqui criado em vários retornos
colocando-se um dos três foi bem
sucedido nada conforme a regra
feito isso o que eu vou fazer pra
economizar que o espaço e só pra mostrar
por exemplo o período de um ano em uma
das propriedades do da biblioteca eu vou
selecionar retornos novamente só que eu
vou pegar ela só do período de 2018
então como eu faço a tribo novamente
trabalhava o retorno dentro dela mesma
e aí eu coloco aqui entre colchetes o
período de tempo que eu quero utilizar
então eu vou pegar o retorno só de 2018
então coloco aqui 1º de janeiro de 2018
uma barra para separar o período final
que eu vou querer fazer aqui que é
setembro e até 2019
agora quando você abrir de novo a
variável que retornos você vai ver que
vem certinho a partir do dia 2 de
janeiro é o primeiro dia útil no caso
feito isso vamos ver como é o gráfico
desse setor no qual teria sido a sua
performance
obviamente aqui descontados não
descontados perdão com os valores de
custos operacionais etc
então eu vou chamar aqui uma variável
chamada carteira onde essa carteira vai
ver vai ter o quê
como estou trabalhando aqui com os
retornos eles são percentuais eu vou
pegar o exponencial disso aqui né que
ele faz o cálculo já trazendo pra mim
contou que teria sido ou a multiplicação
desses retornos de reforma composta
junto com a função de soma acumulada que
eu ensinei pra vocês lá na hora desce
ainda tem dúvida ou me deixa uma
pergunta aqui em baixo ou dá uma
olhadinha lá na aula 10 então somar o
que é emocionar os nossos amigos
retornos que eu calculei do fechamento
na petrobras
vou tirar menos 1 porque eu quero pegar
só o valor aqui absoluto desses retornos
feito isso cara tá calcular o retorno de
toda a sua carteira do período vamos ver
como isso fica no gráfico
você viu como fazer um plot já nas aulas
anteriores é simplesmente fazer o
gráfico você põe a função pode
chama carteira tá aqui esse é o seu
rendimento da carteira naquele período
então saber começou ali
já o primeiro teve um pouco mais bem
sucedido e aqui teria sido a performance
nesse período de 2008 e teria feito aí
um pouco mais de 60% que estratégia
legal para mais ou menos porque você viu
que você ficou um período de down
aqui praticamente sem nada e olha só
como varia essa linha tem que tentar ser
um pouco mais contínua porém lucrativo
porém extremamente arriscado além do
mais como que tirar essas conclusões é
arriscado ou não mesmo que putz fez 60%
tem como você fazer a avaliação da
carteira para fazer a avaliação da
carteira é introduzido vocês a uma nova
biblioteca que era chamada de
performance analytics
essa biblioteca ti permite facilmente
por exemplo as do cabelo do da unta
então vamos pegar aqui um tempo bom que
é o nome da função que você vai usar dos
draw dá uns que você teve e aí você se
foi curioso dá uma olhada em todas as
outras coisas que têm porém eu quero
pegar avaliar os graus que são os
períodos de baixa da minha estratégia é
pra ver quanto tempo eu fiquei aqui
nessa zona perdendo dinheiro
então eu chamo o grau do que dos meus
retornos
é simples assim só que aqui eu não quero
mostrar tudo eu vou pegar só os dez
maiores da all dawns então eu coloco os
top 10 executo isso você tá vendo como é
muito fácil é reputado repito isso
porque é muito fácil aqui ele já me traz
nessa tabela todos os meus maiores não
dá aos e aí o que é legal ele mostra
quando o dragão começou que essa
primeira linha embaixo quando ele
atingiu o ponto mais baixo
então esse grau que começou dia 17 de
maio atingiu o seu ponto mais baixo no
dia 24 de maio e ele foi até 2 de julho
você ficou aí mês e
pouco nesse período de draw da um aqui
há como você sabe bem eu sei porque ele
fala que o comprimento do down foi de 32
períodos ou seja no momento em que
atingiu um máximo até 11 momento em que
eu recuperei nessa saída daquela zona é
o perdão até o período que eu sou eu
fiquei tudo ali ele deu
trinta e dois períodos o comprimento
total ele atingiu o ponto mais baixo em
seis dias depois que ele começou o que é
isso significa essa segunda coluna e ele
levou 26 dias para recuperar o valor que
ele perdeu no total
qual é o valor que ele perdeu no total
27 pontos e 35 por cento cada andal eu
considero muito elevado o segundo maior
do modal ele durou 69 dias caso que
ficou 69 dias perdendo dinheiro e ele
levou 37 dias para recuperar
então você está entendendo que apesar de
ter sido uma estratégia lucrativa você
pode avaliando o down ver que ela não é
tão vantajoso assim é muito arriscada
não é aquilo é exatamente o que a gente
procura tem uma outra função que ela vai
se chamar table estava escrevendo aqui
embaixo vamos escrever aqui no código
pela chama table é dar um site risky o
que ela vai avaliar os várias medidas de
risco do seu retorno
então ela vai avaliá o desvio total dos
ganhos das perdas o que eu quero na aula
de hoje salientar com vocês eu quero
salientar o máximo do down que é de 27
85% obviamente ele tem que coincidir com
esses 2785 aqui do table draw naus
eu quero salientar outra coisa que é o
histórico vá o que é histórico o va é o
velho é o velho é triste que significa
que o que é a chance que eu tenho de
perder até 95% da minha carteira e isso
vai ser de quatro pontos 78 por cento
que é isso que a gente tem aqui então
existem essas outras medidas mas eu
queria enfatizar essas duas
paulo de hoje depois eu explico as
demais com mais calma e por fim além do
mais ficar vendo essas tabelas é chato
cara eu gosto de ver gráfico então vamos
colocar essa informação no gráfico você
chama função charts
e aí você faz o que é um sumário da
performance chamando performances amary
de quem simplesmente da sua variável de
retornos
quando você executa essa função olha que
legal
eu acho muito legal você coloca num
gráfico só os seus retornos acumulados
obviamente a gente é igual àquele ele
vai colocar pra você aqui os retornos
diário como variaram e ele coloca como o
seu dragão down oscilou naquele tempo já
coloca a data tudo direitinho
você tem uma análise completa da
estratégia que você montou em
pouquíssimas linhas de código
convido vocês a usar em outros
indicadores
essa regra de 3d que eu mostrei aqui
você pode criar qualquer coisa no
cruzamento de média uma variação de
qualquer outra variável e usar
exatamente as mesmas funções para
avaliar sua estratégia essa é a grande
flexibilidade não é só isso que estou
explicando aqui na al é qualquer outra
idéia que você tenha beleza pessoal
muito obrigado por assistir mais essa
aula se inscreva no canal se você ainda
não está inscrito daquele seu like.com
grande abraço e até ao próximo tal tchau
[Música]