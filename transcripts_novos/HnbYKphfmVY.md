# PERMANOVA Theory - Multivariate Analysis - Prof. João Igor

- **URL:** https://www.youtube.com/watch?v=HnbYKphfmVY
- **ID:** HnbYKphfmVY

## Transcrição

Olá pessoal. Bem-vindo. De
Agradeço antecipadamente a sua presença.
todos. Bem, hoje vamos aprender sobre...
A técnica PERMANOVA, que é uma técnica
do conjunto de estatísticas
multivariada, utilizando o software R.
Dividi este tema em dois vídeos. Ele
Primeiro vem a parte teórica, e depois
Veremos outro vídeo com essa parte.
prática. Muito bem, pessoal, antes de começarmos...
O curso, um pouco sobre meu treinamento.
acadêmico; Meu nome é João da Rocha
Leitão. Sou engenheiro civil, com mestrado.
em engenharia mecânica, doutorado em
Sou formada em engenharia ambiental.
especialização em gestão de
Em projetos, sou o diretor da empresa M.
e cientista de dados. Quem quer que tenha
Se você tiver alguma dúvida, sugestão ou crítica, não hesite em nos contatar.
Por favor, envie um e-mail ou mensagem para
Alguns dos meus contatos. Certo, pessoal?
Você sabe? E isso é tudo. Vamos
lá. Ah, sim. Se alguém quiser
Para saber um pouco mais sobre o meu trabalho, estou
Eu e o professor temos alguns cursos.
Publicado no Hotmart. Então,
Qualquer pessoa que queira saber um pouco mais sobre
Para assuntos de trabalho, você pode acessar este site.
Certo, pessoal? Ou, desculpe, saka.com.
Pessoal, é isso aí. Vamos.
Primeiramente, antes de apresentar a PERMANOVA,
que é a técnica multivariada de
ANOVA, vou falar um pouco sobre ANOVA.
ter algum conhecimento
teórico antes de prosseguir.
Olá pessoal, o que é ANOVA? ANOVA é a
análise de variância. Você pode determinar
se a média de n grupos for
diferente. O teste F é usado para
verificar a igualdade entre os
médias. Então, pessoal, resumindo,
O que eu disse agora é que a ANOVA é a
análise de variância que é usada
para determinar se a média de n
Os grupos são iguais ou diferentes? OK?
E como isso é feito? Isso está feito
utilizando o teste F. O teste F que
Foi desenvolvido pelo Sr. Ronald
Fisher, de onde é esse cara aqui?
a foto. Certo, pessoal? Com antecedência, para
Usando ANOVA, quais são os três
instalações? Primeiro, as amostras são
aleatório, as amostras são aleatórias
e independente. Em segundo lugar, o
populações têm uma distribuição normal
e terceiro, variações populacionais
São iguais. Essas são as três premissas.
para que possamos usar a ANOVA para
verificar se as médias de
certos grupos são
estatisticamente diferentes ou iguais.
Certo, pessoal? Pessoal, quais são os
hipóteses que posso testar usando
ANOVA? Posso provar a veracidade do
hipótese nula, de que as médias
Os números da população são iguais. Em vez de,
Existe uma hipótese alternativa de
que as médias populacionais são
diferente, isto é, pelo menos um dos
As meias são diferentes das outras. Em
Nesse caso, lembrando que eu posso
Utilize ANOVA para dois ou mais grupos.
Ah, sim, pessoal. Hum, isto é importante.
. Se o valor P for maior que 0,05,
lembrando que 0,05 é o nível de
Significado mais comum. OK?
Há fortes indícios para aceitar
a hipótese nula. De outra forma,
Há fortes indícios de que
Rejeitar a hipótese nula. Certo, vamos lá.
lá. Digamos que eu tenha o efeito de
uma droga, as drogas A e B. Para
Para realizar uma ANOVA em R, preciso usar
a função aov. Se você executar o
Na função de interrogatório AOV, você verá o
menu de ajuda sobre como usar
Esta função. Lembre-se, se o valor
p é maior que 0,05, por exemplo, se
Se fosse igual a 0,7, haveria uma forte
evidências para aceitar a hipótese
nulo. Caso contrário, se for menor que
0,05, por exemplo, 0,03, existem.
fortes evidências para rejeitar a hipótese
hipótese nula. Lembrando que
Se rejeitarmos a hipótese nula, caímos em
a hipótese alternativa. Certo, pessoal
? Pessoal, ok, conversamos bastante.
Como funciona a ANOVA rapidamente
. Agora quero dar um passo além.
e depois estenda esse conceito para
PERMANOVA. PERMANOVA é a análise de
variância multivariada usando
permutações, uma análise de variância
multivariado. Podemos ver a MANOVA,
Qual é a ANOVA multivariada que começa?
partindo da premissa da distribuição
normal. Essa é a MANOVA. No entanto,
Estou usando PERMANOVA. O
PERMANOVA é uma análise multivariada.
para ANOVA não paramétrica, isto é,
Não pressupõe que o
A distribuição das variáveis ​​segue a
normal. Certo, pessoal? A PERMANOVA
É um teste estatístico multivariado.
não paramétrico, ou seja, não requer o
distribuição normal, que compara o
hipótese nula de que a dispersão
A estrutura do grupo é a mesma para todos.
Em outras palavras, a partir dessa perspectiva.
usando PERMANOVA, medindo o
dispersão dos grupos, eu sei se um
um determinado tratamento influencia ou não influencia
um banco de dados multivariável. OK,
pessoal? Pessoal, isso vai ser mais
Claro, mais tarde, mas inicialmente eles
Por favor, guarde isto, ok? O
hipótese nula. A dispersão do
Os objetos são iguais entre os grupos, é
Em outras palavras, um determinado tratamento não é
forte o suficiente, então
Em outras palavras, para criar uma grande variação.
dentro dos grupos. Isso é o
hipótese nula. Se o
hipótese nula, passamos para um
hipótese alternativa. A propagação
no caso de um tratamento específico
Isso varia entre os grupos, ou seja,
Existe uma diferença porque um
O tratamento tem o poder de alterar
nosso fenômeno. Certo, pessoal?
? Ou seja, se a hipótese nula for
aceita, o tratamento dado não tem
poder de alterar nossos dados. Em
Em outras palavras, se houver alguma
variação, aleatoriedade explica isso
comportamento, não o tratamento. Já
Se a hipótese nula for rejeitada,
nos enquadramos na hipótese alternativa: a
o processamento do nosso banco de dados é
forte o suficiente para
gerar um comportamento no
fenômeno que estou analisando. É
Em outras palavras, esse tratamento é de fato eficaz.
significativo. Vocês estão bem, pessoal?
Para mostrar como funciona.
permanova, eu quero usar esta imagem de
a fonte que aparece aqui em azul. ?
Como funciona? O Permanova calcula o
Soma dos quadrados entre grupos, SSA
. Eles estão vendo que eu tenho um grupo.
verde, um vermelho e um azul, e eu tenho um
centroide. Calcule a soma dos quadrados.
dentro dos grupos, desculpe, calcular
a soma dos quadrados entre os grupos,
OK? E dessa forma, analisamos se
Há dispersão, e se essa dispersão
É equivalente para todos os grupos.
Dessa forma, analisamos se o
O tratamento administrado é significativo ou não?
As estatísticas utilizadas são
pseudo-F para calcular a permanova,
para testar a hipótese nula de não
Haverá uma diferença nas posições de
os centroides das medições de
A dissimilaridade dificilmente se manifesta. Ou seja,
calcular essa estatística da SSA e
A partir do SSR, que é elevado ao quadrado, utilizamos
o F da permanova, neste caso o
teste de Fisher modificado, para testar
a hipótese nula de uma diferença
nas posições dos centros do
grupos. Assim podemos analisar o
dissimilaridade. Este pseudo-F é calculado
da seguinte maneira. G é o número
de grupos e N o número de amostras,
onde SSA e SSR já foram definidos
aqui. Vocês estão bem, pessoal? Vamos
lá. Eis a questão. Como
Devo realizar a PERMANOVA no R? Eu uso o
Permanova em R usando o pacote vegan,
que possui a função adonis2. Peço a você
depois de verificarem essa funcionalidade
Em R, isso está ok, pessoal? Pessoal,
Bom, é só isso. Eu só queria contribuir.
algum conhecimento prévio
nosso aprendizado antes de prosseguirmos para o
Parte prática. Mas, recapitulando...
Rapidamente, temos que a ANOVA pode
para analisar se as médias de um
As populações são iguais ou diferentes?
Temos estas três premissas para
utilizamos ANOVA, com a qual testamos
a hipótese nula. Se a hipótese
Se a hipótese nula for falsa, incorremos na hipótese nula.
alternativa. Então nós temos o
Valor p para duas condições, maior ou
menos do que uma determinada significância, que
Geralmente é 0,05. Desculpe,
Usamos 5% ou 0,05. Tudo bem,
pessoal? Aqui estão os critérios que
Acabei de mencionar isso para eles. Se o valor p for
0,7. Há fortes indícios de que
aceitar a hipótese nula e, se o
O valor p é igual a 0,03, existem
fortes evidências para rejeitar a hipótese
hipótese nula. Falando um pouco sobre
PERMANOVA não requer uma distribuição.
normal porque não é um método
paramétrico. Temos e vamos continuar a ter
Analisar duas hipóteses: a hipótese
hipótese nula e hipótese alternativa. ?
Certo, pessoal? E esta análise,
Este teste de hipótese é realizado
calculando a estatística F, calculada
com a soma dos quadrados entre os grupos e
dentro dos grupos. Tendo o
número de grupos e o número de
elementos de cada um, calculamos o
Estatísticas F. A partir disso
Obtemos o valor p e, assim, analisamos.
se a hipótese é verdadeira ou falsa.
Vocês estão bem, pessoal? Adonis2 é o
função usada para PERMANOVA que
Está dentro da embalagem, e só isso.
, pessoal. Alguma dúvida, sugestão?
Seja crítica ou colaboração, peço que
enviar um e-mail, um
WhatsApp, uma mensagem direta ou um
mensagem no...LinkedIn, que também é
João da Rocha. E se você quiser me apoiar...
trabalho, peço que você visite
siteadam.com. É isso aí, pessoal, e
Vamos começar a trabalhar. Até a próxima!
aula, que será a aula prática. OK
. OK. Um grande abraço para todos. Bye Bye.