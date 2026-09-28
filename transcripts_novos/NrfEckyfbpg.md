# Genetic Algorithms - Discover the origin

- **URL:** https://www.youtube.com/watch?v=NrfEckyfbpg
- **ID:** NrfEckyfbpg

## Transcrição

Olá pessoal. Quem fala é Fernando Amaral.
. Sou professor e escritor na área de
inteligência artificial e trabalho no
mercado em projetos de inteligência
artificial por quase 10 anos.
Hoje vamos falar rapidinho, bem,
Teremos uma introdução sobre
algoritmos genéticos, que eu considero
Pessoalmente, um dos mais
fascinante na área de
ciência de dados. Então, ciência
Os dados, especificamente, sempre parecem
imitar o mundo natural. E as áreas
onde a ciência de dados tem mais
Os sucessos são exatamente esses
aspectos, aqueles pontos em que parece
Inspiração do mundo natural.
Então, temos alguns aqui.
exemplos. Você provavelmente já ouviu falar
falando sobre redes neurais
artificiais, que buscam simular o
função cerebral dos seres
vivo. Redes neurais
convolucional, que é uma área que tem
têm tido mais sucesso recentemente do que
Também está relacionado com o
redes neurais. Nessas redes
redes neurais convolucionais, o padrão
conectividade entre neurônios
É inspirado na organização de
o córtex visual dos seres vivos.
Portanto, essas técnicas têm grande
sucesso no reconhecimento de padrões
e imagens. Aqui temos o*
recozimento simulado*, outro exemplo que
É um algoritmo de busca e
otimização para resolução de problemas
complexo e é baseado no
Princípios da termodinâmica. Aqui
Temos a *Otimização por Colônia de Formigas*,
que também é um processo de busca
de caminhos através de grafos que
É inspirado no comportamento de
as formigas. Então, eles olharam
inspiração no comportamento de
as formigas. E, por fim, aqui está mais uma.
técnica que é o tema do vídeo
Hoje, o que são algoritmos genéticos?
Então, o que são algoritmos?
genético? Eles são inspirados por
teoria da evolução natural.
Você provavelmente já ouviu falar disso.
boa parte da teoria da evolução
natural. Foi proposto por Charles
Darwin no livro A Origem das Espécies
espécies, que hoje são consideradas a
o livro científico mais importante do
história. Um breve aparte aqui, quando
Falamos de teoria na ciência, uma
teoria tem um significado muito importante
diferente daquela que usamos na linguagem
popular. Em linguagem popular,
Uma teoria é uma hipótese. Na ciência
É algo composto por vários elementos.
mas entre eles um grande número de
Evidências analisadas. Essa evidência
são analisados ​​e aceitos por
cientistas que são qualificados em
aquela área, naquele ramo. Então, é isso.
Chamamos isso de teoria. Assim como a teoria
da gravidade. e outras teorias
científico, mas é algo altamente
Comprovado por evidências, certo?
Aceito pela comunidade científica.
O princípio básico da evolução
É natural que os indivíduos sejam melhores
Aqueles que estão adaptados têm maior probabilidade de
sobreviver e, consequentemente, para
transmitir seu material genético para seus
descendentes. Então, pense nisso.
Algo assim: quanto mais tempo demorar
Quanto mais vidas o indivíduo tiver, mais oportunidades surgirão.
Possui a capacidade de se reproduzir. E ter mais
oportunidades de reprodução, mais
Ele transmite seu material genético. E
aqueles indivíduos que se reproduzem
Além disso, eles transmitem mais da sua carga.
genética, eles são mais propensos
tornar-se a espécie dominante
e para sobreviver em um ambiente. Eu tenho um
Aqui está um exemplo que costumo usar em
classe e é um exemplo, obviamente apenas
para fins educacionais, de modo que
Entender como funciona. Então,
Imagine um tipo de borboleta. Ah, e
Esta espécie de borboleta tem
Hábitos noturnos, né? Então,
Estamos vendo alguns desses por aqui.
espécie, certo? São borboletas com
hábitos noturnos. Eles dormem durante o
dia, certo?, e eles saem para se alimentar,
Bem, para reproduzir, durante o
noite. O que está acontecendo? Durante
O processo de reprodução ocorre
mutação nos genes de um destes
borboletas. É uma mutação, é uma
processo aleatório, o que acontece com
Essa mutação? um descendente de
cruzamento dessas duas borboletas. Olhar,
É aqui que ocorre a mutação. Coloquei o dado.
aqui para representar que é um
processo aleatório. Um descendente de
Esse processo passa por essa mutação e
Acaba ficando preto. E o que é?
O que está acontecendo? Já que são borboletas de
hábitos noturnos, para predadores
Eles têm mais dificuldade para enxergar à noite.
Assim, dessa forma, essa borboleta
Preto, não é? continua a viver mais tempo e
Ele transmite mais genes, não é? Esse
gera um tipo de reação em
corrente. Seus filhos, netos, bisnetos,
bisnetos e todos os seus descendentes
Eles vivem mais tempo e a população aumenta.
exponencialmente. Predadores, portanto
Por outro lado, eles continuam procurando pelo
Borboletas brancas, certo? as borboletas
que eles veem durante a noite, isso ou
acabam se extinguindo ou até mesmo
Eles se tornam minoria, vivendo apenas em
uma região específica, enquanto
Os pretos estão espalhados por toda parte.
território. Portanto, é importante
Note que a evolução é altamente
relacionado ao meio ambiente, certo?
A capacidade de um ser vivo de
adaptar-se ao ambiente em que
encontra. A evolução natural tem
Três elementos principais, certo? Tem
três processos principais dos quais
Vamos conversar aqui, veja. A encruzilhada,
elitismo e mutação. Ele
Crossover: o que é e como funciona?
Então, quando dois indivíduos
Eles se cruzam, o cruzamento mistura a carga
A genética desses indivíduos, certo?
? Realizar uma travessia de carga
genética desses indivíduos no
processo de algoritmos genéticos.
O que faz um algoritmo?
genético? Essas soluções para um
problema específico que são melhores
adaptado, isto é, que são mais
Eles estão perto de resolver o problema.
mais propensos a transmitir seus
carga genética para o próximo
geração. Não é que aqueles
soluções propostas com baixo
A adaptação não pode ser transmitida.
Mas a probabilidade é menor, certo?
? Então, o ponto de convergência é, eu diria,
a técnica mais importante na
processo evolutivo. Então temos
elitismo. É assim que o elitismo funciona:
Aceito as soluções, as propostas.
melhor adaptado e eu não os misturo; o
Eu passo isso para a próxima geração.
sem cruzar, sem fazer a travessia. E
a mutação aqui, um processo também
O que é importante? Vou levar
alguns genes na solução proposta
E, aleatoriamente, vou alterar,
Vou alterar esses genes. Então,
Como isso funcionaria? Vamos lá!
Vamos falar sobre um exemplo muito simples, que é
um exemplo clássico usado quando
Estamos ensinando, quando estamos
Praticando algoritmos genéticos.
Então, imagine que você tem que fazer
uma viagem em um pequeno avião e tem um
Restrição: você só pode carregar 15 kg.
Mas é como uma jornada por uma floresta,
quer transportar o maior número de
possíveis artigos Então, o quê?
Isso acontece? Ele quer priorizar os itens.
o mais importante. Então, tem um
Lista de itens aqui. Existem sete
itens que pesam no total. 30 kg,
Mas só pode transportar 15. O que é isso?
O que você quer fazer? Ele quer levar o
o mais importante. Os mais importantes
Eles são classificados aqui por
pontos, certo? Então, por exemplo
O saco de dormir é, juntamente com o
bússola, a coisa mais importante. Mas o
O saco de dormir pesa sete. A bússola
Tem um peso de um. Como
Um algoritmo genético funcionaria.
para nos dar a melhor solução para isso
problema? Certo, então o que acontece quando
princípio? O algoritmo genético
proporá algumas soluções
Aleatório, né? Então,
proporá algumas soluções que
será criado aleatoriamente. Por exemplo
Aqui está uma solução. Para o
Chamamos a solução de cromossomo, certo?
VERDADEIRO? Vou colocar o C aqui.
Veja, cada elemento aqui é um gene.
VERDADEIRO? Vou colocar o G aqui.
Então, o que o G está me dizendo?
aqui? Se for, se for um, é...
dizendo para trazer a faca aqui. Meu
Ele está dizendo para não usá-los.
feijões aqui, deixe a batata levar, deixe
De qualquer forma, não leve a lanterna, certo?
Aqui é intermitente.
dizendo o que tenho que dizer
Usar ou não usar. Esta primeira solução
Terá vários cromossomos, certo? Não
Terá apenas um cromossomo. Ou seja,
Cada cromossomo é uma proposta.
Então, por exemplo, suponhamos que
Apresente-nos um, dois, três, quatro
propostas. Cada proposta será uma
diferentes combinações de elementos. ?
O que vou fazer? Eu vou para
Aplique esta proposta a uma função
adaptação. Qual é essa função?
adaptação? Ele vai medir, ele vai dizer
Quantos pontos tem a solução?
Ele propôs o algoritmo genético. Quantos
Mais pontos, melhor, certo? Então,
Quanto mais, melhor. Exceto, é claro, se
Aqui, ultrapassei o limite de peso permitido.
15 kg, a solução não é adequada. Então,
Minha função de adaptação precisa
Encontre a proposta que otimize a
pontos e não exceder 15 kg. Então,
Eu pego a solução um e olho lá, olho
. Este aqui recebeu 45 pontos e
Não ultrapassou 15 kg. Este outro dos
Ele marcou 42 pontos aqui. Este outro
A partir daqui, ele ganhou mais de 15 kg, então
Dou zero. E este outro aqui, porque
Por exemplo, ele marcou 65 pontos. OK?
Essa foi a primeira geração.
proposto por algoritmos genéticos
. O que o algoritmo fará agora?
Certo, ele vai fazer a travessia, ele vai atravessar
Estas propostas onde as propostas
aqueles que se adaptaram melhor, é
Em outras palavras, quanto mais pontos, mais eles têm.
oportunidade de perpetuar seu fardo
Genética, certo? Então, nós somos
Olhando aqui, este é o de número 45 e este outro...
com 65. Propostas dois e três que
Eles tinham menos pontos, eles também têm
oportunidade de transmitir seus genes para o
próxima geração, mas a
A oportunidade é menor. E também pode
Aplicar o elitismo pode levar a
solução número quatro e passe-a para o
próxima geração sem misturar, sem
Não faça nenhuma adaptação. E também
pode aplicar o processo de mutação.
Pode retirar alguns cromossomos do
próxima geração e alter, certo?
algum gene aleatoriamente. Com isso
O que está acontecendo? Crie, você
propõe uma nova geração, uma
nova geração com uma nova
solução para este problema. E existe.
uma alta probabilidade de que este novo
Esta geração tem uma melhor capacidade de adaptação.
Ou seja, meu número aumentará.
pontos e assim o processo continua
Até que duas coisas aconteçam. Que o
O tempo acaba ou você atinge o valor.
ótimo, ao valor máximo possível
ser. Existem problemas que você conhece, que
Você sabe qual seria o valor ideal?
Existem outros que não, certo? Nesta
Neste caso, não sabemos qual deles.
Qual seria o valor máximo em pontos?
VERDADEIRO? Então podemos restringir o
execução do algoritmo genético por
gerações, certo? Podemos dizer
Quantas gerações serão produzidas?
ou por tempo. Se eu souber o valor máximo ou
o valor mínimo que eu quero que ele atinja
Em termos de otimização, posso te perguntar
e também que ele pare quando atingir
esse valor mínimo. Então é isso?
VERDADEIRO? Conseguimos ter uma ideia sobre o
Como funcionam os algoritmos
genética. Espero que tenha gostado.
. Até a próxima. Muito obrigado por
seu público. M.