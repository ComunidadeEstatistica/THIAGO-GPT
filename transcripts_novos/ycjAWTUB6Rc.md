# Aula 9  - Construindo Gráficos no R - Curso de R para Finanças Quantitativas

- **URL:** https://www.youtube.com/watch?v=ycjAWTUB6Rc
- **ID:** ycjAWTUB6Rc

## Transcrição

o pessoal sejam muito bem vindos aos
poucos em marketing
meu nome é leandro guerra hoje é dia de
curso de r para finanças quantitativas
vamos começar a aula 9 como uma sugestão
que que eu recebi lá no canal pra falar
pra vocês como é possível criar gráficos
no r
só para recordar se você ainda não
inscrito se inscreva no canal também
daquele likes e todo o conteúdo do curso
fica disponível gratuitamente lá no meu
site o www pontual tipo que market
pontocom lá na área do curso de r pra
finanças quantitativas
vamos lá pro r fazer gráfico ou
construir ou qualquer tipo de
visualização de dados melhor dizendo é
uma das partes fundamentais quando você
cria ou quando você desenvolve a sua
estratégia de trading ou o que é
atividade na qual você queira mostrar
corretamente o qual que seja aquela
saída seja um projeto que está fazendo o
seu trabalho seja uma ideia é de um novo
produto ou no caso aqui pra gente as
estratégias de trading
então ela é a visualização de dados lan
é uma parte fundamental no rs existem
diversos mundos de você construir
gráficos existe o a um modo mais simples
que é o que eu vou mostrar na aula hoje
porque a gente está no curso
introdutório também existe uma outra
biblioteca que a chamada gp lote 2 que é
excelente e tem a biblioteca também
chamada quanto mode que te ajuda a fazer
gráficos mais voltados para o mercado
financeiro voltou a dar também esses
outros assuntos no curso mas hoje é a
nossa primeira aula de gráfico então
vamos mostrar exatamente como funciona
etapa por etapa para você pilotar um
gráfico no r
então vamos plantando o gráfico você vai
simplesmente executar a função plot
e qual é o parâmetro que você vai passar
para esta função
no caso a gente quer fazer o gráfico do
fechamento da nossa base de uma hora do
euro
então eu vou carregar a biblioteca vou
carregar base de dados como a gente já
viu é quando a gente carrega a base lá
no invariavelmente e mococa plot colocar
eu e fechamento close quando executar o
comando ele vai gerar esse primeiro
gráfico aqui que é bem feio diga se de
passagem não dá pra entender muito bem
não está bem configurado como que a
gente melhora esse gráfico o que você
precisa fazer é passar mais elementos
para a função plot então a gente vai
repetir aqui o blog do euro close que é
o nosso objetivo e o que a gente vai
fazer bem primeiro vamos mudar a cor
então a função para mudar a cor é
chamado de qom onde ela recebe o nome da
cor
simplesmente não vou colocar aqui azul e
ao invés de pilotar esse gráfico com
esses pequenos círculos para cada ponto
vamos colocar um gráfico de linha então
eu coloco type que é o tipo do gráfico
como online basta um l
feito isso eu roda esse comando opa já
está bem mais agradável aquilo que que a
gente quer ver certo porém ainda falta
um título faltam as legendas aqui vamos
deixar isso melhor novamente como eu
disse antes você precisa passar mais
parâmetros para a função então a gente
repete isso você não precisa ficar
repetindo a pessoal todas as linhas e
deixo aqui só pra para fins didáticos
então você cria o seu gráfico no plot e
passa o parâmetro o título ele tem a
função chamada de nem o atributo meio
onde você escreve que você quiser então
vamos por exemplo colocar gráfico euro
dólar e aí eu vou colocar o nome do eixo
x que recebe x leve e ver que ele até
começa autocompletar isso é legal vocês
entenderem
e quando você estiver em dúvida use a a
própria informação que o estúdio da e
ele mostra o que você precisa executar
ele então aqui a 1 x ldu vai mostrar que
você vai colocar um nome para o eixo x
se você ainda precisa de ajuda adicional
você aperta f1 e ele vai te levar para o
help do então vou colocar aqui x hleb eu
vou colocar tempo e no eixo y o nome que
eu dava esse é preço feito isso eu vou
rodar novamente e aí a gente tem sim
agora um gráfico um pouco mais decente
do que aquele primeiro quando você vem
aqui nessa área prótese aquino r você vê
que todos os gráficos gerados
anteriormente eles ficam disponíveis
então você pode avançar aqui pelas setas
para ver o que você fez ou não tal o
primeiro gráfico a gente vira bem feio a
gente mudou um pouquinho agora está no
gráfico melhor aqui eu posso dar um zoom
que quando eu mostro aqui pra vocês um
modo maior e eu também posso exportar
esse gráfico salvar ele como um pdf
carregar na área de trabalho ou salvar
com uma imagem
eu também posso é remover esse plot
atual eu posso limpar todos os pilotos
que eu fiz então se eu limpar a todos
não tem mais opção não tem gráfico nem
tão só para voltar àquele gráfico
melhorzinho aqui na tela o que mais eu
posso fazer eu possa adicionar linhas
neste gráfico nem escrever textos e
qualquer o princípio disso bem o
primeiro como eu escrevi uma linha que
vamos tentar entender qual que é a
tendência de se gráfico dinheiro é muito
simples lembrando que a gente já fez na
outra aula eu crio aqui um vetor de
sequência taquri um x de 1 até o número
de linhas então errou da nossa base euro
e ele vai criar um vetor x de 11 a 21
2245 exatamente a mesma dimensão porque
eu estou criando esse vetor porque eu
quero adicionar uma nova língua nesse
fico então chama função a belém onde eu
vou chamar uma line é uma regressão
linear
lm do euro não se preocupe entender
regressão linear agora que vou fazer uma
aula exclusiva pra ela eu só quero
pilotar linha pra vocês
então vou fazer a regressão linear do
fechamento do euro em função um número
de linhas que a gente tem aqui pro x que
eu chamei só como uma variável auxiliar
então você coloca nele euro close em
função de x coc e aí você vai cuidar um
acordo com essa linha eu vou colocar uma
linha vermelha então com o desculpe qual
recebe rede feito quando rodar esse
comando ele adiciona lá no nosso gráfico
a linha que representa a regressão do
euro então a gente tem que nesse período
a a tendência majoritária foi de alta
como dá para perceber ou não você também
pode portar linha prateada auxiliar na
visualização a função e bellini ela é
bem interessante porque eu posso como
vocês viram coloquei a função da
regressão mas eu também posso fazer
outras porque eu quero uma linha
simplesmente horizontal para representar
por exemplo um suporte uma resistência
ou simplesmente uma outra função como a
média dos fechamentos
então se eu fizer a média do euro close
e vou colocar a cor como um preto aqui
por exemplo black
eu rodo ele coloca lá no preço médio que
a gente viu na anterior que a gente pode
pegar da função quando eu executo tão a
média 11 e 13 ele pilotou ea linha preta
pra gente ali num e 13 beleza pessoal
esse é o conceito e as noções básicas do
gráfico porque eu cheguei até aqui a
gente já está na aula 9 eu introduzi pra
vocês diversos conceitos e na próxima
aula na aula 10
a gente vai usar simplesmente tudo o que
a gente aprendeu até agora coisa que
você não sabia nem a programar no começo
e já na aula 10
eu vou mostrar pra vocês como eu criei a
estratégia da barra anterior
utilizando apenas os conceitos vocês até
agora não é nada muito complicado se
você ainda não tá bem fixado mãe para
mim as suas dúvidas
assista reveja as aulas e só para vocês
terem uma noção
lá eu vou falar um pouco começar a
introduzir a biblioteca quanto mode como
você descarrega os dados diretamente no
no r
o grande ponto é essa estratégia da
barra anterior
é uma estratégia bem bacana uma
estratégia bem lucrativa
nesse período de 2017 até r 10 de 1º
janeiro 2017 até 10 de setembro de 2018
ela teria dado ali não envolve
considerando 20 centavos por ponto 11
mil e oitocentos reais
a reta é essa daqui tá então eu vou
ensinar a vocês com os conceitos que
você sa que você sabe até hoje pelo
curso como criar essa estratégia beleza
pessoal
um grande abraço deixe suas dúvidas seus
comentários e até o próximo vídeo tchau
tchau
[Música]