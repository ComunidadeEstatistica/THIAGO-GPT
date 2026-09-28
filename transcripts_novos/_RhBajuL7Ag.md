# Seleção de requisitos de um projeto, usando solver do Excel - Prof. Felipe Moreira

- **URL:** https://www.youtube.com/watch?v=_RhBajuL7Ag
- **ID:** _RhBajuL7Ag

## Transcrição

g1
a porta só trazendo para vocês um
problema de seleção de 15 tá
eu tirei esse problema esse artigo vou
colocar esse link para vocês baixarem e
vou colocar um link também para vocês
e quem ainda não tem atualização quem
não tem ainda a liberação na verdade o
sogro do colocar mente também no chão tô
na ativa
ó e aqui pessoal a gente tem 20
requisitos
os classificados por cinco stakeholders
aqui avaliação do primeiro até o quinto
stakeholders com a avaliação que se
simples teclados fizeram do primeiro
requisito e assim por diante e aqui
alguns pesos que a equipe deu para cada
um desses feitores de acordo com a
avaliação que eles fazem da influência
do poder desse jeito poder da relevância
que existem clube tem medo da história
inicialmente a gente faz uma
normalização aqui para que informar
todos esses pesos o que seja um então eu
faço aqui basicamente pegar esse valor
divide com a soma
o que é justamente a forma até aqui
bom e com isso eu ponderando avaliação
de cada um desses tempos que é
basicamente multiplicando esses pesos
a orar pelas avaliações eu consigo uma
métrica
é de métrica de importância digamos
assim dá satisfação que cada um desses
requisitos era no projeto
bom então com isso aqui especificamente
eu já poderia
a criar uma prioridade é preciso dizer
que é uma métrica a partir dessas
médicos eu acordo bem mais de forma
decrescente eu tenho o requisito mais
prioritário digamos assim até que geram
menor que geram a menor satisfação porém
eu tenho também mas que motiva como a
gente viu que para implementar o
requisito
a gente precisa trabalhar nele
e a gente tem uma métrica de 10 mostrar
avaliar o custo de cada um desses
requisitos então se implementasse todos
esses requisitos geraria de acordo com
essa métrica 63.880 desfaçam e geraria
aqui um custo de 85 a
ó e aqui o que que acontece eu tenho
aqui prender de satisfação e
o que elas são de natureza antagônica a
o que no melhor dos mundos eu teria o
máximo de satisfação possível com o
mínimo de custo possível
o que caracteriza aqui um problema de um
problema de otimização de multi objetivo
eu tenho aqui um objetivo de maximizar
a satisfação
o e de mini saco tão esse tipo de
problema ou sou ver especificamente não
resolve não resolve
é mas a gente consegue colocar uma
equação zinho aqui meio que
que simulam a equação de custo-benefício
o benefício seria a satisfação gerada
pela escolha desses requisitos e o custo
nada mais é do que o custo da escolha
desses requisitos né e a minha
utilização a minha equação que o meu
alvo digamos assim esse objetivo
especificamente seria o benefício menos
o custo e aqui eu tem alguns pesos no
caso dos pesos se eu quiser por exemplo
que
e dá o maior ênfase em um benefício
poderia colocar aqui 0.8 eu quiser
conferir dois e apertei aqui os
benefícios à maximização dos benefícios
teria maior importância do que a
minimização dos custos e eu vou deixar
desse jeito eu gostava antes das 50 50
vou colocar o 0800 tá e aqui o objetivo
ele tem essa equação tem o peso
multiplicado pelo benefício menos o peso
multiplicado pelo custo certo
tô entrando aqui o seguinte
e os ouve ele precisa tem alguns graus
de liberdade para trabalhar no casa
e tem esse trecho aqui na planilha que
vai dizer o seguinte olha so
e varia
e essas combinações
e para encontrar qual é a melhor
combinação possível
e maximiza essa relação de
custo-benefício
e já tá então por exemplo o sol ele vai
gerar vários cenários
ó e aqui nesse cenário gerado por
exemplo
e ele viu que a seleção desses
requisitos aqui gerou uma satisfação
quase vinte e um custo de 32 e aí depois
disso ele vai a partir desses resultados
tenta procurar algum seja melhor do que
esse ato basicamente isso acontecer eu
vou deixar se quiser a para não dar
problema não no ponto de início o
é mas aí o artigo também traz um
relacionamento entre os requisitos ele
disse que não existe aqui liberdade
total para escolher esses requisitos
certo
oi e ele fala o seguinte eu usei essa
nomenclatura essa nomenclatura parece
aqui um sinalzinho de +
ó quem fala o seguinte
é que nessa condição no caso r3r 12 quer
dizer que sim ou r3 foi escolhido
e o r12 também se você escolhido e
vice-versa
eu quero ver se eu sou ver escolher o r3
or12 precisa tá escolhido 16 cores né e
sim ur-12 foi escolhido ur3
e também precisa ser escolhi nessa
condição aparecido mas não idêntico
com quem
e ele diz o seguinte ele disse que sim
e o r4 foi escolhido
e o r8 também precisa ser escolhido
o porém o r8
e se ele foi escolhido o r4 não
necessariamente precisa ser escolhido só
e aqui eu fiz umas formas tentando oh
a imitar isso só
bom e quando essas fórmulas elas recebem
um o valor um significa que a restrição
ela foi atendida tá eu vou falar um
pouco mais como é que é essa forma tá
mas por enquanto é importante a gente
saber o seguinte se isso aqui é igual a
um significa que essa restrição no caso
essa aqui
e está sendo atendida e uma outra
restrição que é o percentual de
orçamento liberado dizer o seguinte pode
ser que um acredite que eu vou ter com
orçamento disponível de 85
eu acredito que eu vou ter um orçamento
de oitenta por cento disso e é que eu
tenho que oitenta por cento meses e se
machucar e aí eu vou dizer que o sol e
procure combinações cujo o custo total
não seja superior a 68 tá
bom então vamos montar
e o modelo então vamos usar o solver
eu vou apagar
olá tudo para inicializar
já arrumou a primeira a gente definir o
objetivo
oi vó
o programa de tipo de maximização eu
quero max maximizar esse objetivo
e aqui são as células que o sol ver tem
liberdade
a trabalhar
o e as restrições vai funcionar todas as
restrições
é de uma vez
o que precisa ser igual a 1
e aí
eu vou colocar aqui
e o custo dessa seleção
e tem que ser menor ou igual ao custo
márcio
e aí
g1
e aí
é tão
a qualquer custo e coloquei restrições e
agora vou colocar
o que essas células aqui ela só pode ser
01 elas têm que ser vinagres
com quem
bom então hoje disso e células podem ser
variadas restrições resolvi
olá eu sou ver encontrou uma solução
encontrou uma solução
é é
a escolhida 14 requisitos
o gerando cerca de 74 por cento
e do total de satisfação 74 por cento de
benefícios totais e 67 por cento do
custo total abaixo e oitenta por cento
do orçamento né e aí você pode fazer
variações variações aqui do a quantidade
de de orçamento por mim e vou tentar
variar que os pesos do benefício peso no
custo e ver qual a influência disso na
seleção no resultado tá agora vamos nas
restrições
e essa restrição como lembrado significa
que se r3 foi escolhido r2 16 escolhido
mas se o r2 foi escolhido r3 também
precisa ser escolhido
e aqui nós temos o seguinte
e o que satisfaz essa restrição é
a linfa escolhido
um ou os dois sempre triste
com quem
é isso aqui eu represento por essa forma
se a célula que tem a escolha do r3 foi
igual a célula da célula escolha do r12
você não sei guarde se elas forem iguais
às contrários é
ó e aqui a única condição que não atende
é o caso deve escolher o r4 e eu r8 não
sei escolhido
a foto
em todas as outras elas são aceitáveis e
aqui eu consigo
o cabelo esse essa restrição dizer o
seguinte olha o único caso em que
é isso aqui
o que acontece é quando o r8
e ele é menor
e eu quero é quatro eu coloquei esse ur8
for maior ou igual a série 1001
bom então espero que faz o contrário por
favor não deixe de entrar em contato
tirar suas dúvidas da garota escola e
até a próxima a