# Lesson 00 - Introduction - ML in Practice - Scalable Models

- **URL:** https://www.youtube.com/watch?v=epnbFxjJ9PI
- **ID:** epnbFxjJ9PI

## Transcrição

Bom dia, gente, boa tarde, boa noite,
porque eu não sei quando que vocês estão
assistindo esse vídeo. Meu nome é André
e essa é a primeira aula do curso de
ciência de dados, modelos na prática
aqui da CSD, comunidade de estatística e
ciência de dados do professor Thiago
Marques. Gente, esse aqui é um de
diversos cursos que a gente tá
oferecendo e como tá no nome, ele é
voltado para prática. Então, a gente vai
falar de ciência de dados na prática.
Nada de teoria sem aplicação.
Ao contrário, nós temos vários objetivos
com esse curso. Vocês podem ver essa
lista imensa aqui que vai ser
compartilhada como com vocês, assim como
todo o material do curso. Então nós
temos primeiro objetivo, capacitar
profissionais para trabalharem com
ciência de dados em empresas de qualquer
porte. Gente, tem empresa pequena,
grande, gigante a trabalhar com ciência
de dados e a ideia é que vocês estejam
capacitados ao final desse curso de
trabalhar em ciência de dados com
qualquer uma delas.
Nós queremos preparar vocês para
aplicações reais de ciências de dados.
Então, nada daqueles exercícios que a
gente vê em faculdade, que são
bonitinhos e que não são nem um pouco
próximos do mundo real. Nós também
queremos abordar aspectos não técnicos.
Que que isso significa? Significa que
ser dados é um trabalho técnico. Você
tem que saber matemática, saber
probabilidade, saber programação, saber
conhecimento de negócios. Mas quando a
gente tá falando de trabalhar no mundo
real, a gente muitas vezes vai trabalhar
em equipe. Às vezes não, mas muitas
vezes, muitas vezes vamos trabalhar em
equipe e com isso precisamos saber lidar
com as outras pessoas, né? Então, vamos
também abordar ao longo desse curso
aspectos não menos técnicos, mas
humanos, que envolvem mais a comunicação
com colegas, a comunicação com clientes.
Além disso, nós vamos apresentar
diferentes tipos de dados e seus
desafios, ensinar tratamentos de dados
na prática e o objetivo no final é
capacitar os alunos para que eles
avaliem criticamente seus modelos.
Então, não só treinar o modelo, tá
feito, vamos em frente. É treinar,
avaliar para saber se ele tá bom,
avaliar para saber se ele atingiu o
problema de negócio, se ele resolveu o
problema de negócio, mostrar como buscar
oportunidade de melhoria desse modelo.
Então, versão um, como é que tá? Versão
dois, quando você mexe um pouquinho aqui
nos parâmetros. versão três, quando você
mexe aqui um pouquinho nas features, eh,
mexer na versão 4, quando você mexe na
qualidade de dados, enfim, você pode não
só avaliar a qualidade de modelo, como
pode avaliar como diferentes alterações
nele, nos dados, na forma de treiná-lo,
que que essas diferentes alterações
trazem de qualidade e como que você pode
comparar ele com outros modelos também,
não só comparar ele com outras versões
dele mesmo.
Além disso, nós vamos querer
contextualizar ciências e dados em
diferentes áreas de aplicação, mostrando
a sua a sua versatilidade.
Porque acontece é ciência de dados é uma
área muito versátil. Você pode trabalhar
com ciência de dados e esportes,
ciências de dados e cinema e direito e
tecnologia e gastronomia. Então, eu
imagino que um dos principais motivos
para vocês estarem interessados em
comprar cursos de sensados como esse é
que vocês já viram que ela pode ajudar
vocês de alguma forma, que ela pode ser
aplicada em algum assunto mais palpável
e que interessa a vocês. E a ideia é que
isso é uma uma das grandes qualidades
positivas, qualidades positivas, uma das
grandes forças da ciência dados e a
ideia é contextualizar a aplicação
dentro dessa força.
me apresentar um pouco agora, né?
Apresentar o professor. Meu nome é
Andrea Visone. Eu sou estatístico pela
FRJ e sou cientista de dados. Trabalho
há 5 anos em empresas de diferentes
portes, mas principalmente empresas de
portes grandes e gigantes. Eh, eu sou
mestre em inteligência computacional.
Esse nome é um nome antigo ali da COP
FRJ, que é o a pós-graduação de
engenharia. Eu me estudei na engenharia
elétrica da FRJ e fiz o mestrado em
inteligência computacional. Esse nome é
antigo e basicamente é machine learning.
Então eu foquei em aprendizado de
máquina durante meus anos do mestrado.
Tenho experiência com diversas áreas e
diversos projetos. Então trabalhei com
os mais diversos assuntos de ciência de
dados, nos mais diferentes clientes, os
mais diferentes projetos.
Eu espero de vocês o quê? Eu não espero
nenhum conhecimento muito fantástico. Eu
espero que conheça um conhecimento
básico de diferentes áreas, Python, R,
SQL e estatística barra sens dados,
porque a ideia é construir com vocês
conhecimento. Então, a ideia é que vocês
saiam de um nível pequeno de
conhecimento para um nível maior ao
final do curso e um nível que permita
com que vocês se insiram no mercado com
facilidade e com alta qualidade de
entregas.
Qual é a questão? A questão é que eu não
presumo conhecimento zero. Eu presumo
que vocês sabem como instalar o Python,
como instalar o R, como rodar um Hello
World. Eu presumo que vocês sabem rodar
uma query básica, presumo que vocês já
ouviram falar de alguns dos conceitos
mais básicos de estatística e ciência de
dados. Então eu não presumo um
conhecimento
grande, eu presumo um conhecimento
pequeno, mas não zero. Preciso que ele
exista.
O curso em si, ele é dividido em oito
módulos e esses módulos estão
organizados em ordem de complexidade.
Vão do mais simples até o mais complexo.
Então v mais simples, que é fundamento,
ciência de dados e organização, até o
mais complexo, que é produção, colocar
modelos em produção e boas práticas. E
dentro de cada um desses módulos, nós
teremos várias várias aulas pequenas, 8
a 15 minutos,
às vezes mais menores ainda, como essa
aqui de hoje, que é de apresentação.
Ela, por sinal, não se encaixa em nenhum
desses módulos, porque ela é uma aula
parte, é uma apresentação do curso,
apresentação do professor, apresentação
dos pré-requisitos
e nós temos os oito módulos em si.
Então, a gente sai de fundamentos e
organização para estrutura de dados e
pré-processamento, para exploração e
análise descritiva, para estatística e
inferência. Depois vamos paraa modelagem
preditiva, em seguida para avaliação e
otimização de modelos. Finalmente vamos
pros casos avançados. Caso avançado são
características especiais dos dados,
como, por exemplo, serem indexados no
tempo ou no espaço. Um exemplo de
indexação no tempo eh, a taxa de
conversão de real para dólar.
Ela é uma taxa que varia longo tempo.
Então, a taxa no dia 1eo de outubro não
vai ser igual a taxa no dia 2 de
outubro.
E mais do que isso, as variáveis que
afetam essa conversão também são
indexadas no tempo. Então vamos pegar
aqui, por exemplo, uma mudança de
tarifas, como foi o caso dos Estados
Unidos desse ano. A mudança de tarifas,
ela altera fortemente a taxa de
conversão. Então você pode entender que
se a taxa de a mudança de tarifa
acontece no dia X, que a
conversão no dia x + 1 vai ser
diferente. Então você leva em conta não
só a taxa do dia X, como as variáveis
que afetaram a taxa do dia X para tentar
estimar o dia X mais 1. Veja coisa com o
local. Com local. Você pode, por
exemplo, tentar estimar roubos de carro
no Rio de Janeiro, tentar estimar quais
são os lugares mais perigosos, entre
aspas, no Rio de Janeiro, com base no
número de roubo de carro. Então você
indexa o teu dado e a tua resposta com
base no espaço. Então saber que um roubo
de carro aconteceu numa rua X ou Y da
Barra da Tijuca ou que aconteceu numa
rua X ou Y do Flamengo, que aconteceu na
comunidade da Rocinha, isso vai fazer
diferença. Então os seus dados podem
também ser indexados por tempo,
desculpa, por espaço. Então por exemplo,
quantos policiais tinham naquela rua uma
hora antes do do assalto? Então tá
indexado por tempo e por espaço, né? Bem
legal. Então, nós temos vários casos
avançados que os métodos tradicionais
não lidam tão bem. E aí o foco desse
módulo Ses finalmente, produção e boas
práticas. é que acontece é muitas vezes,
muitas vezes nesses citados a gente
estuda como fazer modelos, não como
entregar os modelos e o que fazer depois
que eles estão entregues. E a ideia
nesse módulo é focar nisso, o que fazer
para colocar modelo de produção, quais
são boas práticas, enfim, a gente vai
sair de fundamentos até entregar coisa
para cliente. Então é um é um curso bem
completo e que se complementa a vá que
complementa vários outros daqui da CSD.
Bom, gente, por hoje é isso. Aqui tá a
página aqui da da CSD em todos os as
redes sociais.
Até a próxima aula, que a gente vai
começar a colocar a mão na massa em si.
M.