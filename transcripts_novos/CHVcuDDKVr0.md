# Part 1 - Linear Regression - It's your chance! Now or never! - Prof. Adriana Silva

- **URL:** https://www.youtube.com/watch?v=CHVcuDDKVr0
- **ID:** CHVcuDDKVr0

## Transcrição

pessoal o thiago me convidou para fazer
uma apresentação a gravar um vídeo no
blog dele
estou devendo isso para ele já faz muito
tempo agora são 11 40 saiu vitoriosa
aqui não adianta me lembro que o lugar é
um dos lugares que o dólar também ea
gente vai fazer então esse vídeo sozinho
para colocar nesse blog abrigado pelo
convite e o que eu quero falar aqui ele
me deixou livre para escolher o que
falar então já começar por uma parte
simples da estatística
mas olhando de uma forma um pouco mais
facilitada para a gente ver que antes
que entre realmente dá pra ficar em
várias situações a quando a gente começa
a pensar em analytics começa a pensar na
estatística como você vê os seus
clientes nem se preocupar entendeu data
do corte já trabalhou
então a gente tem que saber o tipo a
essência daquele da então imaginar
quando eu estou olhando indivíduos
indivíduos que são por exemplo meus
alunos meus alunos eles têm sete cada um
deles então tem homens e mulheres sexo é
uma variável
essa variável é do tipo que no final é
uma característica 1
existe também tem unidades têm de 30
tenho 20 150
a variável idade é um nome eles têm
salários
então cada um vai ter um salário
diferente a outra variável salário
variável contínuo a essência de cada uma
delas tem que ser tratada com que ela
permite que eu faço com aquela variável
então uma variável categoria
a média é uma variável no médico
consegue com normalmente quando eu tenho
duas variáveis numéricas eu começo a
pensar em coisas pra tentar atirar em
saúde
então vou dar um exemplo mais simples do
universo imagina que eu tenho pizzarias
e essas fitas itália
ela tem um lugar onde tenha universidade
e aí eu pedi pro outro a galera que
trabalha comigo coletar a informação do
número de alunos que eu tenho disponível
na minha universidade versus o número de
pixels que eu tô vendendo então eu sei
lá eu tenho 30 alunos e wendy 70 pitas
que estou inventando aqui não quer dizer
que esses números vão bater tá 2550 30 é
77 e assim vá tão cada linha no banco de
dados aqui uma pizzaria e cada linha tem
número de alunos referentes aos aumentos
na região na pizzaria número de fitas
que eu conversando exemplo são duas
variáveis numéricas
são duas áreas numéricas é instinto
humano e até uma necessidade minha
porque eu sou dona das pizzarias o que
querem entender se existe algum tipo de
relacionamento entre essas variáveis
então o que a gente vai fazer posso
começar primeiro fazer uma crítica
individual de cada uma delas
logo na seqüência que queria tentar
juntá las e aí a ideia de fazer um
estágio tecnológico
imagine que eu encontrei algo desse tipo
aqui que a gente percebe o euro esse
grave que na medida que eu vou
aumentando o número de alunos que está
acontecendo com minha filha eu tomo
entanto o número de ferro de peixes
então é claro existe uma certa
a associação entre essas duas variáveis
e aí como é que o mensura sucesso
existe uma métrica que chama e com
relação difícil que é o gol que ele
faria em menos de 1 e 1 que significa
isso
esse é menos um significa que existe uma
forte correlação negativa ou seja quando
uma variável aumenta a outra diminui
quando exerce significativa que não
existe nenhuma correlação ou seja quando
uma variável aumenta a outra se mantém
estável e quando ele é perto de um
existe uma forte correlação positiva com
um momento o outro também ao menos nessa
situação aqui a gente vê nitidamente que
existe uma forte correlação positiva em
número de alunos e fixas vendidas
e aí a gente consegue mensurar isso
calculando com relação de preço no
entanto andando quando comum não querer
saber se grau da associação e sim eu
querer prever
imagine o seguinte cenário eu sou o dono
da pizzaria e eu estou na dúvida de
abrir outra pizzaria e eu tenho dois
lugares estratégicos que eu possa haver
sempre que sair eu preciso priorizar e
eu quero saber qual então vai me dar
mais venda
como eu posso fazer isso criar uma
equação que baseado no número de alunos
que é um fato
a universidade já estão a tentar inferir
o número de pizza que eu vou vender não
conseguir tomar uma decisão de qual
lugar eu voltei à pizzaria 1º e aí a
gente volta pra ficar
é natural que na hora que a gente olha
concessão desse tipo é naturalmente
querer transar uma reta no momento em
que o traz uma reta o meu coração a
minha vontade você aí também
provavelmente fez isso que transformar
então exatamente em cima dos pontos vai
ser agora não poderia ter uma reta aqui
olha estranho é porque há por que se
está longe dos pontos
esse é um instinto é exatamente isso o
está longe dos pontos significa o quê
porque quem está perto dos cocos por que
você quer errar menos que significa
américa
não é que eu traço uma reta que eu estou
assumindo que esse ponto aqui eu estou
chamando de se então o que está
acontecendo aqui eu estou errado esse
pedacinho esse ponto aqui eu estou
chamando fim da época então estou
errando mesmo assim já esse outro número
foi muito pequeno
então eu estou fazendo o que eu estou
buscando algo em que explique esses
pontos mas que vão teremos é fato que
vai ter e então ela supera de sentido
porque o meu objetivo é o que minimizar
esses erros eu quero estar mais perto
dos pontos possíveis para garantir que
eu vou ter um modelo que consiga prever
um número difícil na hora que eu tiver o
número de alunos das duas localizações
estou buscando e aí olha lá a gente
aprendeu isso no colégio é quando eu vou
criar uma reta que a gente aprendeu a +
b x a maio deixe só que a estatística a
gente mudou um pouquinho isso que a
gente fez e me chama de ainda chama de b
a gente resolveu chamar isso de beta 0
mas beta 1 x 1
não tem nada diferente que é o aaa aaa o
que a gente aprendeu no colégio é onde
corta o exijo que eu bs minha inclinação
que agora só mudei o nome sem pânico
e aí isso daqui também mostrou que
enquanto o aluno muda o que limpassem
quem na minha pizza vendida que eu quero
prever porque essa é a dúvida não quer
tomar uma decisão e eu não vou abrir uma
pizzaria
então se eu consigo criar uma equação
que seja o melhor possível minimizando o
eu que minimizou ele é fazer a reta em
cima mais perto possível dos pontos
o então vamos pensar o ponto eu vou
chamar dito
ele é composto pelo que pela reta que eu
tô querendo criar mas quem um errinho
que eu vou sempre amar
então eu chegar a um ritmo verdadeiro
que é esse ponto eu preciso pegar a reta
que essa equação
mas se eu que esse pedacinho que eu tô
muito bem então quer dizer o que eu
preciso fazer o quê minimizar este como
eu vou minimizar isso é bom entender o
que eu ele que eu ele não é o real que é
o ponto - o estimado na reta então é o
quê
- o y chapé que que é isso um chapéu
esse momento é tá velho - beta 1 x 1
isso é terrível e ótimo então eu tenho
uma função na qual quero minimizar o
momento não quero minimizar uma função
eu tenho que ter raiva e vou levar em
função de que poderia estar funcionando
meta é poder levar a função do perdão
que são dois parâmetros do golpe se
encontrar para desenhar sua reta mais
perto do povo
minimizando o meu e então ela ficou mais
o risco de de de fazer uma reta que é
porque eu estou minimizando um erro em
função desses meus pontos e ainda o
momento em que eu deveria ir com essa
função em função de diversas vezes em
função do verdão chegar uma forma