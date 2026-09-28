# Aula 10 - Seu primeiro algo trading - Curso de R para Finanças Quantitativas

- **URL:** https://www.youtube.com/watch?v=HYUxeDpf9KY
- **ID:** HYUxeDpf9KY

## Transcrição

[Música]
fala pessoal sejam muito bem vindos aqui
aos pouco é marketing meu nome é leandro
guerra hoje chegamos aula 10 do curso de
r para finanças quantitativas fico muito
contente por todo o apoio quantidade de
inscritos subindo cada vez mais dúvidas
contatos sugestões que estão chegando
realmente muito obrigado a todos pelo
apoio pelo suporte em prover esse curso
pra vocês como eu havia prometido na
aula 9
hoje eu vou ensinar vocês a fazer a
primeira estratégia de 3d baseado no r8
todas as aulas anteriores
você que não sabia nada de programação
se você pegar aula até aula onde você é
totalmente capaz de executar o código
com que eu vou mostrar pra vocês hoje
aqui na aula 10 e aula 10 é sobre o seu
primeiro álbum o trading
o plano é uma expressão diferente que
nunca tinha falado antes algo aprende é
a capacidade de você fazer três dias
utilizando alguma estratégia
desenvolvida algorítmica mente ou seja
automaticamente tão pouco algoritmo que
a gente executa nada mais é do que um
conjunto de regras que vão ser seguidas
por um computador
essa é uma definição muito simples para
o que é algoritmo o que ainda não
expliquei pra vocês nas aulas anteriores
eu só faço uma observação é a biblioteca
com timóteo eu até já citei comentei que
ela é utilizada para trabalhar com dados
financeiros não erre vou fazer aula 11
específica dessa biblioteca
porém é preciso usar ela um pouco aqui
pra poder capturar os dados então se
você não entender logo de cara o que é a
biblioteca com timóteo não se preocupe
assista ao onze que eu vou explicar
exatamente o que ela faz então aqui eu
só vou rodar para capturar os dados do
ibovespa que é onde a gente vai fazer o
teste da estratégia da barra anterior
não é uma estratégia inventada por milla
já existe há muito tempo no mercado é
bastante difundida e o que ela faz
se o preço de hoje a subir e romper a
máxima do preço do dia
teor a gente entra com prado se ele cair
e um pé a mínima do câmbio do dia
anterior ou do período anterior melhor
falando você entra vendido é uma
estratégia bem bacana pra você começar a
se aventurar nesse mundo é claro que
aqui é uma versão simplificada sem
contar o spred custos operacionais lhe
peixe porém para você entender muito bem
o que faz esse código para você ser
independente não depender de mais
ninguém para criar as suas próprias
estratégias
então vamos mudar esse primeiro trecho
do código onde eu executo chama
biblioteca quanto mole
faço as datas iniciais e finais do meu
período de análise que o ano de 2017 até
o dia 12 de setembro de 2018 e coloquei
aqui dentro dessas variáveis que ensinam
o que é uma variável start e em direito
seleciono a variável aqui no caso do
ibovespa que é a otca que eu vou
utilizar e coloco dentro da função
ghetti símbolos tudo isso é da
biblioteca com timóteo então eu passo
bovespa aqui como tickers a fonte é o
yahoo finance onde esses dados são
coletados nesse from que é o período
inicial até o período final que a gente
definiu aqui em cima então eu roda isso
aqui também você pode acompanhar perdão
não tinha rodado típicas ainda
você pode acompanhar toda a criação
desses dados aquino invariavelmente
então você vai ver que ele rodou aqui o
i já criou pra você a informação do
governo como um objeto xts leandro que é
um objeto xts objetivo da aula de aulas
posteriores porque aqui eu vou focar
mais nesse trabalho do indicador
ok o da biblioteca com timóteo e permite
que você crie gráficos de uma maneira
mais elaborada voltada para o mercado
financeiro e você pode ter o seu famoso
gráfico de kindles desse período que a
gente selecionou utilizando a função
chatices que pode ser tanto utilizada
normalmente como na escala logarítmica
nesse intervalo pequeno de tempo a gente
vai ver que não dá muita diferença no
gráfico com intervalos maiores com
variações percentuais maior
aí o logaritmo faz mais sentido ok
pessoal então isso aqui foi só para
capturar os dados e mostrar pra vocês
como criar um gráfico no estilo que a
gente conhece nas plataformas de trading
vamos criar a estratégia então da barra
anterior e aí eu vou introduzir também
novos conceitos aqui dá aula 10 para
você aprender então a primeira coisa que
a gente tem que fazer é ajustar a máxima
ea mínima dos preços para a comparação
lembra que esses dados aqui do bovespa
foram capturados eles vêm no formato xts
a gente vai converter para a data frame
que é o formato que a gente aprendeu na
aula quatro haja trabalhar
então quando eu executo essa linha você
vê que ele muda é o dataprev que você
conhece seu clique em cima ele vai abrir
a visualização e você tem aí a abertura
máxima minha fechamento volume o preço
ajustado do ibovespa
ótimo passo porém passa um completo que
a gente vai fazer eu vou criar aqui uma
nova variável nessa linha 38 que vou
chamar de máxima shift que a máxima
deslocada
onde eu vou atribuir primeiramente como
um só uma primeira passagem a massa
inicial quando roda esse código ele vai
aparecer aqui no invariavelmente a sua
nova coluna raio xe fitch que nada mais
é uma cópia da coluna ray atual
aí o que eu vou fazer mo executar esse
comando aqui embaixo da linha 39 para
deslocar a ela para que eu faça a
facilmente a comparação entre um e outro
então o que eu vou fazer
dentro dessa coluna raio xe fsmt eu vou
fazer um deslocamento que é onde eu uso
o que menos 1 da quantidade de linhas em
relação à quantidade de linhas que eu
tenho aqui no ibovespa que são 429 ok
a primeira linha eu vou colocar um em
lei que significa que é um valor nulo
quando eu executo aqui esse código o
prefeito que eu quero te repare aqui eu
coloquei na primeira linha o enem e
desloquei e aí você comparar ray shift
com raiva você vai ver que a alta aqui
era 6227 a alta que a gente tem aqui
agora é 6227 só que está deslocado em um
porquê porque o que eu quero fazer
eu quero saber se o dia seguinte que
essa alta aqui por exemplo de 61 1815 é
maior que a alta do dia anterior se é 60
mil 227
eu acho esse jeito muito mais fácil
porque está na mesma linha do data frame
basta fazer e se comparado com esse aqui
então por isso que eu faço esse
deslocamento
esse deslocamento é feito exatamente
nessa linha de código 39
faço a mesma idéia já que eu também
quero fazer para as mínimas cálculo a
cópia da variável low em low shift e
fácil deslocamento de luchetti então de
modo análogo eu vou ter uma nova coluna
chamada lutfi deslocando em um elemento
a coluna low como a gente pode verificar
exatamente aqui ótimo essa é a base para
você poder fazer as regras de compra e
venda e aí sempre toda hora você aprende
uma coisa nova hoje vou ensinar para
vocês a fazer uma comparação condicional
que é se o valor da massa atual superar
o valor da mínima o valor perdão da
máxima anterior
eu vou entrar comprando senão eu vou
entrar vendido
ok só que qualquer diferença que eu vou
fazer só pra ficar muito claro a
explicação eu vou criar com uma nova
variável chamada bull que é touro
comprado no mercado e não uma outra
chamada bear aqui então o que eu estou
fazendo
o comando para fazer essa comparação das
variáveis chama e hell's que a função se
então e aí você vê que o r
o estúdio já sugere sim então o teste
que você vai fazer
qual é o resultado que você vai retornar
sim e qual é o resultado se você vai
retornar que não
como é isso qual é o meu teste eu quero
testar se o valor da alta é da máxima de
agora ele é maior que a máxima anterior
entendeu agora porque eu coloquei tudo
na mesma linha é preciso ficar
trabalhando com
uns se complicar o código então eu faço
esse teste
se for maior que é o primeiro argumento
que eu passo o que eu vou fazer
bem eu entrei comprado certo então eu me
eu espero que feche mais alto do que o
valor que eu comprei
então se ele for maior eu vou fazer o
quê teria sido eventualmente o meu lucro
ou prejuízo que é o fechamento - o preço
que eu comprei porque eu comprei naquela
máxima anterior
ok e x 0.2 onde esse 0.2 ele é o valor
em centavos a cada ponto do governo se
você tiver trabalhando com o menino só
pra ficar um pouco mais real o valor
financeiro
se nada disso acontecer ou seja se não
superar a máxima de hoje não superar a
máxima do dia anterior retorna zero ou
seja não fiz três nenhum culpado nesse
caso o rock
qual é a segunda coisa que você está
aprendendo na aula hoje também é uma
outra função que é chamada de nei
lembra que eu expliquei aqui que o enem
é quando a gente tem um dado um nulo na
do brasil tá
o que eu vou fazer se eu tiver um lado
vazio
eu vou fazer isso retornar 0 então eu
pego aquela minha nova variável bom que
eu rodei
eu faço um teste dentro dela que é se é
nenê de a variável bull onde ele e nenê
ele vai retornar uma 20 então roda que
esses dois livros de código
vou ver de novo ali como tal mandato a
femme tem a coluna boa adicionada e tem
e mentalmente quanto os valores em reais
você teria ganhado nos dias que deu três
então naturalmente tende a positivo e
negativo e dia que você não fez trading
que é o 10 que você retornou na função e
fiel se mesmo raciocínio para a função
quando a gente vai fazer é a entrar na
mínima que vendido se então a mínima de
agora tá foi menor do que a mínima do
dia anterior
eu vou entrar vendidos eu entro vendido
espero que ela feche mais baixo do que
aquilo que eu vendi multiplico 02 e se
não cometer seu esse
mexe eu retorne 10 mesma história com o
exonerei entrou aqui e veja o meu
gráfico ok
os resultados da posição vendida bem
estão aqui ótimo vamos agora somar para
ver os resultados para ver se essa
estratégia está sendo lucrativa aqui no
nosso teste como que eu vou fazer
a terceira lição da onde hoje existe uma
função que a chamada função com um sonho
que é como se fosse uma soma acumulada
daquelas duas variáveis seja tanto
button quanto bear e vou retornar ela
dentro de uma outra variável voltou
criando que é bovespa resultado porque
eu vou usar essa com essa função aqui de
soma acumulada com um som porque ele vai
calcular exatamente tudo acumulando para
todas as linhas não preciso ficar
calculando linha por linha somando com a
linha anterior tem uma função específica
que faz isso executa que a soma
acumulada dos resultados
vamos lotar os gráficos que você viu lá
na aula 9
então o que eu vou fazer eu vou fazer um
plot do passado os elementos que eu
tenho aqui nuno bovespa results com os
dados principais que eu tenho no bovespa
results que eu coloquei aqui lendo não
entende nada não se preocupe a função
index que a quarta coisa que você está
aprendendo na aula de hoje que ela vai
trazer simplesmente o número das linhas
1 2 3 4 5 6 até 429 porque lembra esse
primeiro elemento é o nosso valor de x
do gráfico que é o que vai ficar aqui
embaixo
o cordeiro da bovespa results e vai
pegar simplesmente o valor principal ali
da função é de valor acumulado que você
fez lá em cima que são os elementos aqui
somando os resultados ótimos o tipo de
gráfico de linha eu vou colocar uma cor
azul que vou colocar aqui um título o
eixo o nome do eixo x no nome do eixo y
e vai ser o plot que você aprendeu na
aula anterior cara muito bacana você vê
que naturalmente como toda a estratégia
tem um certo grau down lembrando que
aqui não tem spreds níveis de custo
operacional
é só um resultado teórico você fala poxa
fiz uma estratégia lucrativa posso
começar a testar nos meus três reais na
minha conta de mama por exemplo para ver
se isso funciona ótimo vamos aprender
mais uma outra coisa na aula de hoje
para fechar
é como eu posso fazer uma anotação
dentro de si gráfico lembra que na aula
9 eu mostrei como você cria linhas
adicionais hoje eu mostro como você cria
texto muito simples uso a função text
vou passar nessa função text o que eu
vou passar a posição no eixo x que eu
quero que esse texto seja escrita ou
seja o gráfico ele tem aqui o eixo x
quando eu escolhi os 175 significa que
aqui mais ou menos no na parte do centro
onde é a altura do número 175 do x eu
vou posicionar esse gráfico na posição
também do eixo y é o segundo número aqui
2 mil ou seja mais ou menos nessa altura
aqui onde está o mouse aqui agora em
amarelo
eu vou cortar o meu texto que texto
texto retorno total eu vou pegar o
último número
na minha variável bovespa os outros como
eu pego sol o último número de tudo isso
que você está vendo aqui na terra
embaixo se eu pegar só esse 12 mil e 81
eu uso uma outra função chamada tenho
que a cauda ele vai pegar lá o resultado
final só um número ou executar só estou
aqui por exemplo você vai ver aqui nem
12.080 1.2 tão roda essa linha do teste
olha só o que ele pilota aqui pra você
como eu fiz tudo pra colocar tudo junto
número e o texto eu uso essa função
peixe
lembrando o pessoal preste bastante
atenção em todos os conceitos que você é
capaz de fazer tudo isso sozinho dúvidas
me escreva avancem um pouco mais na aula
de hoje justamente para você sentir a
potência sentir todo o potencial que
você pode usufruir quando você realmente
começar a dominar o r
e você já pode fazer isso a partir de
agora adiciona aqui só os créditos
depois do
outro ponto que é marketing e o link lá
pro pro facebook beleza pessoal de novo
agradeço muito a todos pelo apoio que
estou recebendo pelo curso aqui o ensina
a fazer essa estratégia a prenda sozinho
tente fazer sozinho com outros ativos
utilizando outras regras também para a
compra e venda fique livre para testar e
eu estou aberto a esclarecer todas as
dúvidas de vocês
um grande abraço e até o próximo vídeo
tchau tchau
[Música]