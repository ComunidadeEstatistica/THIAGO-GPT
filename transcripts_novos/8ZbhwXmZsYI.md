# Regressão Logística no Poderoso H20 do R

- **URL:** https://www.youtube.com/watch?v=8ZbhwXmZsYI
- **ID:** 8ZbhwXmZsYI

## Transcrição

olá pessoal não é mais não
esse vídeo para o canal está difícil vou
mostrar a vocês como está mais nessa
logística no r usando o pacote naquela
zona
o pacote é bem interessante que eu tenho
uma série de ferramentas tanto pra tal
dado conta pra construir os modelos
ele trabalha de forma um pouco diferente
ele a lógica a abaixo dados no servidor
que o maior deles
e lá eles têm uma série de mecanismos
que otimizam bastante processamento dos
algoritmos
então quando a gente trabalha com base
na ordem de milhões de linhas
o ganho de produtividade é bem alto
de forma resumida como a gente pode
trabalhar com a gasol de forma normal
wifi com os pacotes com esse comando
aqui é onde eu vou fazer conexão com o
servidor h2oh
esse primeiro parâmetro é a quantidade
de cpus disponíveis
ele tem permissão para usar o caixa dois
é usar do seu uso
você passa menos um ele vai ficar com
seu oponente eu tenho minha máquina que
vai utilizar todas segundo parâmetro é
quantidade de memória ram da marca que
eu deixo eles há um caso aqui na
televisão pelos até dez dias jean e
executar e fazer conexão rock conexão
feita com sucesso esta conectado no
clássico dó de ver com informações aqui
comum que lancetta no brasil onde a
perda de memória aqui e ali para
trabalhar é o de idéias pra ele desliga
depois de trabalhar então ele tem aqui
para mandar os objetos os dados e tem
uns que ele achou que gostaria de ver o
que ele pode usar ok vamos carregar
abaixo dados aqui pra cá só dar um
pouquinho de contexto
o trabalho de dados vamos mostrar que
nós vamos ganhar h
a gente quer usar a mach landim para
identificar a quem deve contratar ou não
contratar baseado no resultado de alguns
trechos
nós agora a resposta é contratar ou não
contratar caiaque forma bem
anália aqui já está trabalhando em ok
os dados já subiram ao servidor a 2 o
comando aqui a variável prova lógica do
tipo eu quem conhece como médio tem um
dado importante tem esse valor mínimo o
valor máximo dela e assim o valor médio
do desvio padrão dizia que tem algumas
variáveis também tem dados faltantes do
tipo num que é o reconhece como factor
então nós temos três várias categorias
de classe que a variável
a resposta pode assumir dois valores não
contratar é contratar aqui a gente vai
separar a base para treino de
finalização e teste então comandando o
primeiro parâmetro que ele pede é o
objeto com os dados segundo a proporção
que eu quero que vai pra treino 10
restantes automaticamente eles já vão
pra à base de teste ao executar
ele vai gerar uma lista com três objetos
ou seja a base de treino validação e
teste seus arquivos saber qualquer coisa
sobre a analista contábil das linhas vai
ver aqui que a primeira
basta tem 508 observações que a baixa do
treino
a segunda base que aborda a relação de
62 ea terceira 69 e processar as bases
a gente acerta novamente quase fase com
uma lista não erre
então quero que o meu objeto da lista
seja armazenado no objeto que não tem
como treinar
o segundo objeto vai ficar na validação
conta de lesão eo terceiro vai pro teste
e quando a gente trabalhando com base
muito grandes
a gente sempre espera liberar morte pela
doença só poder trabalhar
então não precisa mais dessa lista de
morrer aqui então apresentar um modelo
padrão diz que vai impedir como vetor
para variáveis protetoras
eu vou guardar eles aqui na variável é
um objeto no meio campo chegou a dizer
que está aqui pode ver em baixo e agora
a resposta vai ser um retorno por um é
com o nome na verdade a resposta que eu
vou chamar ele de irmão então entrar
aqui no modelo
o amazon.com e lm ele vai pedir alguns
parâmetros muito x onde vou passar a 92
variados protetora para onde eu vou
passar a resposta drone frame é onde vou
passar abaixo das que você parou o
treino e deixou frame é onde trabalha em
relação à família
nesse caso as funções da família
policial trabalhava há nome ao subir na
área de montagem por exemplo modelar com
a atribuição da lapa gama ou usar no
nosso caso o nome ao a função de ligação
de usar aquela gente mesmo
alfa deu certo ele o a1 é equivalente à
regressão laço porque eu quero que além
disso a modelo já que até faz
automaticamente as variáveis são las
através de uma linha amarela constante
lembra ele vai ponderar os coeficientes
vem contribuindo significativamente para
a pensão até eles estão lá em 0
o volante lembra
aqui ele vai identificar para mim
automaticamente o valor desse laban
poder for vai tentar sem valores através
de devastação causada principalmente a
classe c é bem interessante a gente tem
é a mostra diferente para o clássico
por exemplo se eu tivesse muitas
observações para a classe contratar bem
pouquinho para classe não contratar
então se eu voltasse para o iguaçu ele
está nas técnicas de anderson tempo ou
exemplo ele vai equilibrar a qualidade a
morte cada classe
esse parâmetro aqui ele remove colunas
entre as várias editoras linhares
ou seja são aquelas que são fortemente
relacionadas
dependendo do modelo e se podem
influenciar aqueles remove esperando
aqui é como a gente quer que ele traz os
assaltantes
nesse caso eu vou pedir para colocar a
média da variável
esses parâmetros anormais para com o
mtur vai padronizar variáveis numéricas
para todos têm a mesma idade medida
esse parâmetro é interessante
toda vez que a gente trabalhou com base
em risco muito variáveis acontece de
vingar o que ela tem o mesmo valor em
toda a mostra segue na equipe cidade de
defaults da população cruzada que ele
use trabalhar com cinco fogos
então tem uma série de outros parâmetros
que pode usar aqui sempre foi trabalhar
com eles
então eu vou executar aquele mostra o
status 100% ele está treinando e guarda
aqui a gente pedir pra ele mostrar pra
gente
a outra parente querido armazenou no
modelo pode ser que está aqui então que
está falando aqui ele me dá né
aqui vai dar nos dados modelo da família
minha o link o git irrigação laço longe
lembra aquele usou ele começou com 14
protetores e depois continuou com oito
do final seja zerou os coeficientes
aqui a gente tem os betas as variáveis
que eles alguns da oposição têm os betas
padronizados são todos da mesma unidade
de medida da china caac qual trabalhava
o mais importante ea - para pedir são
roque abaixo
nós temos algumas métricas na base de
treino rubinho acertou bem na hora de
treino e é isso aqui particularmente eu
acho mais interessante que ele já dá os
pontos de corte que essa logística ela
não vai falar com tatiana contágio vai
falar verão a probabilidade de
compropriedade eu falo que contrata você
quiser
ele é aquele da américa
o ponto de corte o valor da meta caso
uni
josé é o maior f1 em casar a média
harmônica entre a um recall ea precisão
eu o ponto de corte 6460 ou seja acima
de 64 por cento eu falo de contrato
abaixo não completa a maior graça o
ciclo de corte aqui é uma praxe 96
é bem interessante
aqui nós temos as mesmas métricas toque
na base da ação é que mateus confusão na
baja vedação ficou bom também aqueles
bons de corte religação
e aqui nós temos os resultados na
avaliação cruzada então abrirá a atriz
confusão na validação cruzada
ela é um pouco mais e melhor porque é
uma técnica mais exigente mas continuou
bom modelo que tem um ponto dos pontos
de corte analise e aqui ele dá para a
gente os resultados de cada fonte
então a couraça média das cinco notas 7
teve padrão aqui sendo que não falou de
um apurado foi de seu valor foi de 2 a
próxima desse valor até o fim por 5 a 1
o técnico interessante por essas medidas
e poderem se pode também totar a curva
rock
a taxa de iva de positivo é muito boa
ele pode pilotar as variáveis mais
importantes que o modelo de forma
gráfica que era mais importante pois
caso aqui foi o psicotécnico
eu posso gerar mais uma nova confusão
é uma outra base que ainda não viu então
o preço é bem exigente com um modelo tão
grande que ele vai ter uma boa posição
no mundo real é além da operação cruzada
além da baixa inflação ainda separa uma
base para o teste aqui já é uma confusão
ela e eu posso salvar o modelo aqui
também é para os futuros modelos treinar
aqui e que encerra a conexão com o h2o
ok
já eliminamos objetos pessoais então é
isso
dessa forma o usuário python é é
praticamente iguais de r para quem o x o
python pode absorver o conteúdo desse
vídeo também
é isso obrigado