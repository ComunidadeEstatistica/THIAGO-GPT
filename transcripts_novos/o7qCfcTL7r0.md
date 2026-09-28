# Algoritmos Genéticos - Aplicação no R

- **URL:** https://www.youtube.com/watch?v=o7qCfcTL7r0
- **ID:** o7qCfcTL7r0

## Transcrição

no vídeo anterior feito aqui para o
canal
a gente falou sobre algoritmos genéticos
e eu dei uma explicação uma avaliação
teórica sobre como funciona os
algoritmos genéticos
agora tivemos uma aplicação prática de
algoritmos genéticos utilizando o r
a gente vai pegar um problema bem
simples um problema desse clássico
solucionado por algoritmos genéticos e
ele sendo simples a gente consegue
compreender é entender de forma mais
fácil o seu funcionamento então imagine
a seguinte situação você vai fazer uma
viagem uma aventura por exemplo humano
na selva é você vai pegar um vôo em um
pequeno avião e você tem uma restrição
você pode levar apenas 15 quilos de
bagagem é uma restrição comum que existe
qualquer tipo de vôo nesse caso
aconteceu é 15 quilos só que você tem
vários itens a gente está vendo aqui uma
lista de sete itens de sobrevivência na
selva que você gostaria de levar só que
esses sete itens se você olhar aqui em
baixo o peso deles é 30 quilos ea
restrição é 15 quilos
bom o que acontece esses itens
eles têm duas em dois atributos
eles têm um ponto e peso o ponto a
importância do item o peso é obviamente
quanto que ele pesa então qual é o
problema que nós temos que resolver
nós temos que criar uma combinação que
otimize os pontos mas que não passe da
restrição dos 15 quilos
bom você pode pensar se não eu vou pegar
os itens que valem mais pontos e vôo
solar eles até chegar aos 15 quilos é
uma solução é mas não será a melhor
solução porque porque você pode assim
deixar de incluir algo por exemplo tem
um peso
mas que tenha mais pontos neco ou seja
pode haver sobras que você vai
desperdiçar o que se tem que buscar uma
otimização entre pontos e peso de forma
que por exemplo você pode deixar de
levar o item que vale 10 pontos e pesa
10 quilos mas em compensação você vai
trocar ele por dois itens por exemplo
que pé que pesam oito quilos e valem 12
pontos o que é esse o tipo de problema
que a gente tem que resolver com o
algoritmo genético como é que a gente
resolve isso existe várias formas que o
algoritmo genético funciona a gente vai
usar a forma binário tipo binário como
que o título minerário bom nós vimos ali
que a gente tem uma combinação de sete
itens que podem ser levados certo no
algoritmo genético cada item vai ser um
limite
então o que ele vai fazer ele vai nos
passar uma sugestão de configuração de
bits
quando eu tenho 21 quer dizer que aquele
beach idéia que aquele item deve ser
incluído na minha viagem quando eu tenho
um de 2001 que é de que ele tem não deve
ser incluído que o algoritmo genético
vamos ver se ele vai testar as melhores
combinações usando aquelas técnicas que
nós vimos anteriormente de crossover e
letista mutação ele vai usar essas
técnicas buscando a melhor combinação
agora como que o algoritmo genético ele
vai saber qualquer melhor qual que é a
melhor combinação bom ele não sabe este
papel de testar a melhor combinação cabe
a nós
nós temos que receber a combinação
proposta pelo algoritmo genético testar
se essa combinação atingir ou seja ela
tende as restrições de não passar dos 15
quilos e nós vamos dizer o algoritmo
genético essa combinação é boa ou é ruim
com esse retorno nosso da nossa função
que vai avaliar o quão boa é essa a
solução proposta pelo
genético ele vai ter condições de
através de votação para sobre o elitismo
propor soluções melhores e melhores até
chegar a uma solução que pode ser a
melhor possível porque então a gente
implementa uma função de avaliação e nós
vamos chamar de função de avaliação que
vai dizer para o algoritmo genético o
quão bom o quanto aquela solução é boa
ou não para o problema que a gente está
apresentando então agora a gente vai
desenvolver a gente vai analisar o
script led tem o script pronto de como
resolver esse tipo de problema
bom então estou aqui com o r estúdio
aberto o que você precisa fazer para
executar esse exemplo
primeiro você tem que instalar o pacote
gear dead genético algoritmos é esse é o
melhor pacote no meu entendimento de
implementação de algoritmos genéticos no
r
eu não vou fazer situação que obviamente
já que é instalado você se não tiver
você tem que não só rodar esse comando
aqui está comentado depois de instalado
o pacote obviamente você precisa
carregar ele eu vou fazer a carga que
bom é que a gente começa a solução do
problema
primeiro eu criei um baita frame a frame
do r com os itens que nós queremos levar
na viagem então aqui o nosso da frente
que tem um canivete e feijão batata
lanterna da chave do unicórnio bússola e
ele tem que os pontos que cada item vale
o peso nem tão sedenta frente nada mais
é do que aquela tabela que nós vimos
agora pouco então está vendo aqui o item
pontos e peso
ok nossa tabela e ditta está criada com
os pontos os pesos bom o próximo passo
aqui ó é a função de adaptação esta
função aqui que nós estamos chamando df
o que ela faz ela recebe ela vai receber
do algoritmo genético uma combinação de
bits onde cada bit quer dizer se o item
está incluído ou não e nós vamos ver se
aquela solução atende se é boa ou não
então o que a gente faz um agente
percorre os 7 bits e verificam
se um bilhete é não está igual a zero ou
seja isso se o item é para ser incluído
na mochila o que a gente faz a gente
soma os pontos ea gente soma o peso
certo então ó de novo ele vai passar eu
vou colocar aqui um exemplo vai passar
aqui uma combinação que seria por 0 1 0
0 1 1 0 ele pode fazer passar essa
combinação
nós vamos verificar o primeiro e quem
aqui é zero
se ele é zero ele não entra nesse
difícil a 1 ele entra se ele entrar no
isso que vai fazer ele vai somar os
pontos daquele item por exemplo o item 2
é um em dois temos feijão feijão são 20
pontos um peso dele é 5 ok então ele
percorre todos os sete bits
os beach um ele soma os pontos e o peso
que ele vai fazer bom obviamente que a
solução que interessa é que tem maior
pontos mais pontos
então ele retorna aqui os pontos naquela
solução proposta só que tem um porém
nós sabemos que o peso não pode passar
de 15
então é estes do viterbo aqui ó desde
que ele verifica se o peso maior que 15
pontos igual a zero ou seja essa solução
não interessa então o que vai acontecer
com essa função de avaliação ela vai
pegar diversas propostas do algoritmo
genético ela vai somar os pontos se não
passou do peso ele vai retornar quantos
pontos aquela solução apresenta
igualmente que o marítimo genético vai
trabalhar na busca de uma solução que
tenha mais pontos possíveis
ok é essa é a função de avaliação eu vou
marcar aqui e vou criar ela
bom aqui então começa o algoritmo
genético de fato então lo é executar o
algoritmo genético ou armazenado o
objeto na variável resultado a função
que a gente usa que o algoritmo genético
ela se chama gear reagir a um músico que
vem do pacote gear maiúsculo primeira
que eu tenho tipo esse tipo de problema
é um problema binário eu posso ter o
problema
foi um problema de permutação são os
modelos clássicos de algoritmo genético
este aqui é o binário boate fitness é a
função de avaliação qual função que o
marítimo genético vai utilizar pra
avaliar a adequação da solução a
resolução do problema então vejo que
fitness é ff é a função que nós criamos
agora pouco número de bits é quantos
bits tem então vocês lembram nesta em
sete itens então para cada item beach
então ele tem sete o número de população
popes ice é o tamanho da população é
quanto os cromossomos quanto às soluções
ele vai propor a cada interação nós
estamos botando aqui 10 é número de
internação de interações alterações
máximas são quantas gerações serão
geradas
então ele vai tentar ele vai gerar 15
gerações tentando utilizar o resultado
depois de quinze ele para mim eu posso
também é criar uma condição de parada
que a gente não vai usar aqui que é o
que ela vai ele vai parar quando atingir
um valor máximo um valor x um parâmetro
x no retorno da função de avaliação e
aqui e se essa
esse parâmetro names simplesmente o nome
dos objetos para que num resultado a
gente consiga ver se o objeto foi
incluído ou não na solução proposta
então vou ficar aqui na linha vou dar um
compromisso entre aqui então vejo ele
executou e aqui está dizendo que a
solução melhor
ela retornou 82 né então a gente vai ver
aqui um sumário da solução tão vejo a
solução que ele encontrou hessen
canivete com feijão sem batata com o
lanterna consegue dormir sem cordas sem
pulso não tem essa é a solução essa é a
melhor solução não sei
a gente não sabe o que tem que fazer
você pode fazer aumentar a número de
interações e ver se a solução se uma
nova solução ela consegue atingir o
valor de retorno da função maior
vejam aqui por último o plot de
resultado então
vejo aqui ó a gente tem o valor máximo a
que ele atingiu foi 80 ok 80 pontos foi
o retorno máximo que isso que a função
de retorno deu é extrair o suco
conseguir mais então a gente teria que
testará rodado mais interações certo
lembrando que o objetivo é o maior
número de pontos possíveis
e a gente já sabe que esses que essa
combinação proposta pelo algoritmo
genético não vai ultrapassar a nossa
restrição que são os 15 quilos então
esse foi um exemplo simples bastante
didático mas dá para estender o
funcionamento e o poder do algoritmo
genético obrigado pela audiência e até a
próxima