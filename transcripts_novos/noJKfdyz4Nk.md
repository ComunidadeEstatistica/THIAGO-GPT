# R Avançado 02  - Regras de Associação - Apriori - Prof. Rodrigo Rosa

- **URL:** https://www.youtube.com/watch?v=noJKfdyz4Nk
- **ID:** noJKfdyz4Nk

## Transcrição

olá pessoal rodrigo novamente com você
dando prosseguimento à nossa série de
vídeos agora com os algoritmos de data
mãe no r
vamos começar aqui pelos de regras da
associação tá então primeiro algoritmo
que a gente vai ver vai ser o a priori
então vou pedir para vocês fazerem
instalação desse pacote aqui ó
o arroz está depois que você se instalar
em malta comentado por quem já tem esse
pacote instalado você está ali e depois
vocês carreguem ele através da libreta
não carrega o pacote carregou sem erro
nenhum e eu vou carregar um conjunto de
dados que eu tenho aqui tá eu vou
mostrar pra vocês primeiramente a gente
vai trabalhar com esse conjunto aqui ó a
os dois conjuntos
esse aqui é mais para um exemplo mais
simples né
aqui seria a gente vai buscar a relação
entre esses produtos onde a linha onde
está em branco quer dizer que os outros
não foram comprados né
esse primeiro aqui a gente única coisa
que foi comprado foi o upgrade o
biscoito foram comprados por exemplo a
gente tem essa última linha aqui foi o
koff o tinha o alex eo milk brad hughes
cut mag cook a esse aqui é uma base de
dados bem bem resumida é mais para vocês
entenderem como ele funciona
seriam as vendas de um supermercado
simulando às vezes você pega um
supermercado então a gente teria que 20
vendas está o número de linhas está se
vocês olharem vocês vão ver que não tem
um cabeçalho tá então é direto só o nome
dos produtos está a utilizar
primeiramente esse daqui e depois a
gente vai utilizar esse outro que o
supermarket está
este aqui sim simulam a simula não não é
esse aqui sim é uma venda real thaw de
um supermercado
tá então tem vários produtos aqui ó tá e
tem bastante instâncias aqui os
existentes seriam as vendas né
o número de vendas está então se podem
ver que esse arquivo aqui é bem grande
ta ai está tudo lá no um derrame e
também pessoal acaba de atualizar lá
coloquei esses dois arquivos lá para
vocês quem quiser pegar tá
ah ah ah ah sim eu vou mostrar pra vocês
onde vocês podem pegar arquivos também
está tão primeiros mais conhecidos que
eu vou falar tá é o o occ e tá é um
repositório de contém vários data 7 está
aqui a gente pode ver os mais baixados
willy sakineh qualidade do vinho
então a gente tem vários conjuntos aqui
tá se vocês virem aqui envio em data que
tem outros conseguem fazer um filtro
aqui né pelo tipo tipo de tributo data
área é também uma olhada com calma que
outro eu quero botar o carro também é um
site bem interessante que eu recomendo
que vocês deem uma olhada com bastante
calma e evitar esses conjuntos desses
dois eu peguei que nunca está a outro
aviso prévio para vocês é que assim o
conjunto às vezes não vêem um formato
padrão né então você vai ter que fazer
um pré processamento desses dados para
processamento é um das etapas da
descoberta de conhecimento então quem é
quem desconhece a surgir dá uma olhada
nisso aí primeiro e geralmente é uma das
partes mais trabalhadas que tem fazer o
tratamento destes conjuntos de dados
está bom mas chega de conversa vamos ao
que interessa então tá então estou
criando um novo objeto chamado baby é
base aqui tá que ele vai fazer a leitura
de um
arquivo que eu vou chamar pelo fale to
está só que diferentemente dos outros
está a eu vou fazer amor como foi
chamado para mim pegar esse arquivo
chamado switch ponto transitions é essa
[Música]
aqui é uma função dessa dúvida até carro
está pra gente fazer o tratamento de
nosso conjunto como que ele está
estruturado lá tá então vou a falha
chuvoso para abrir o sábado e selecionar
o arquivo como vocês viram não tenho
cabeçalho tenho você tem o reader para
fauci separador a vírgula e tem outro
parâmetro aqui que é interessante a
gente começar a usar que é o rm
duplicate tá então digamos uma linha tem
um produto que se repete por exemplo tem
mil que milk duas vezes a ele vai
eliminar essa duplicação tá então ele
vai ver vai deixar na linha apenas um
produto vai eliminar o que se repete
está o nosso conjunto muito pequeno não
vai fazer diferença mas para conjuntos
muito grandes podem fazer grande
diferença deixou carregar o nosso
primeiro arquivo aqui só pra gente fazer
uns testes mais básico está do
mercadinho simulador né
a primeira coisa que eu vou fazer que é
dar um sangue na base está também na
base eu consigo ter algumas informações
a eu consigo ver que são 20 linhas e 11
colunas tá uma densidade aqui de 0.3 que
já me leva até uma leve redução aqui
sobre o que eu posso utilizar o meu
suporte está aqui eu tenho 11 itens mais
freqüentes então tem o prédio koff o
escute o team com flex e outros somou um
total de 25
não consigo ver algumas informações
mas aqui também depois vocês olhem com
calma essa é isso daqui
a outra função que eu tenho aqui na
biblioteca olho está é esse item frango
esse plot está tão 8 em franco sempre
plot o próton e se os objetos que
aparecem mais vezes por exemplo um
grande cofre está então vou dar um
control em ter aqui tá então ele pilota
aqui pra mim forma de gráfico né
os itens que aparecem com mais
freqüência que é a freqüência relativa
tá que koff mil que o tia isso aqui pra
nossa base pequena da ficou bem legal da
gente vê né a escola base muito grande
depois a gente vai ver
às vezes pode ficar complicado de se
observar
então ainda dentro desse porte aqui
vocês podem passar top-5 tá ou qualquer
outro valor que ele vai selecionar
apenas o 15 mais vendidos neste caso que
nos colocar um top 10 vai selecionar os
dez mais vendidos está não encontrou em
ter aqui ele busca só os cinco mais
vendidos da os cinco que aparece em
nenhuma com maiores transações também
pessoal é bem interessante está bom mas
vamos ao que interessa como criar regras
tá então vou criar um objeto que chamado
regras está a ele vai receber a função a
priori tac é do pacote arroz está então
o a priori e o que eu vou passar como
parâmetro não a priori eu vou passar
primeiramente a minha base de dados é
que a base que eu criei tá e vou passar
um parâmetro tá esse parâmetro qual o
que vai ser
ele vai ser uma lista tá então parâmetro
igual parâmetro é igual a list tá e o
que vai dentro dessa lista está o
suporte tá que vocês podem se inscrever
extenso mas eu preferi resumir suporte
vírgula ea confiança tá eu não vou
entrar em detalhes do suporte explicar
bem detalhadamente que a suporte que a
confiança está quem quiser saber um
pouquinho a mais dá uma olhadinha no
playlist do eca procure lá ô ô ô a
priori e acho que eu explico um
pouquinho mais aprofundado a o suporte
ea confiança tá mas isso aqui é
indispensável que vocês busquem na
literatura para saber o que significa a
importância deles dentro do dos
classificadores classificadores não né
das regras da associação tá aqui é muito
importante também pessoal
então vou dar um control entre aqui para
gerar nossas regras pontos e olhar que a
saída ontem várias informações aqui mais
uma que me interessa aqui ó 0 regra está
provavelmente um desses suportes aqui é
o suporte está muito alto a confiança
está muito alto está não vou baixar um
pouco o suporte o bota 40 baixar também
um pouco a confiança e colocar 70 anos e
que gera não gerou nada ainda então
tenho 10 regras está a baixar bem
suporte então já começou pode estar
ficando lá em cima e colocar o suporte
de 0.1 a confiança vou deixar em 40 a 50
encontrou entre rock e agora eu tenho 55
regras aqui foram criadas como eu faço
para visualizar essas regras
eu chamo espectro e passa o regras está
a fazer uma inspeção nessas regras tão
bom contra o inter
aqui as minhas regras geradas tá então
tenho 55 regras aqui ea partir disso eu
posso fazer uma associação entre elas
então quem compra o dim compra médio com
suporte de 10% ea confiança de 100%
é isso aqui é 100% que quem comprou ou
vai comprar o médio está
o suporte é desta quem comprou james
comprá-la a all black com o suporte de
délcio a confiança de um tá é
excessivamente tá é assim que vocês vão
fazendo a associação do das regras de
você está a isso aqui é um pouco
diferente dos classificadores né as
regras porque as regras vocês vão ter
que levar para um especialista para
dizer se a regra faz sentido não faz
sentido ter regras podem ser óbvias
por exemplo há uma coisa que pode sempre
acontecer a quem comprou margarina
compra pão às vezes pode ser uma regra
relevante o cara já sabe disso o
especialista o negócio do mercado já
sabe
então você tem que procurar em regras
que são que não são muito óbvias
a outra coisa será notar aqui é por
exemplo aqui essa regra 26 o quem compra
biscuit compra cook compra a que nós lei
está com a confiança de 100% também deu
suporte dessas está então aqui você tá
podem vir vários elementos está no r
como a priori o então tá ele não traz
esse não faz isso tá ele traz apenas um
elemento se não me engano o eca lhe
fazem isso ele pode trazer mais
elementos aquino então a quem compra
biscuit e kuki compra com flex então né
então copa com o flex e comprar milk
shake no a priori noé e não acontece
apenas um elemento aqui sim aqui pode
aparecer mais tá e aí vocês vão
procurando você inclusive pode mudar
esses parâmetros aqui há a confiança
está a montar uma confiança de 80 aqui
pra ver tão bom aí já com o homem tem a
confiança de menino me regras
vinte e uma regra está em um espectro de
novo aqui eu consigo ver essas regras
aqui e aí eu faço uma seleção das regras
que achou relevante no e levo para o
especialista do negócio tá ele vai olhar
e vai dizer ah isso aqui e talvez seja
relevante talvez não seja a e como é que
vocês vão testar isso aqui essas regras
na prática a a aí é só fazendo o
algoritmo não vai dar pra vocês não vai
dar um resultado pra vocês vão ter que
pegar essas regras aqui e aplicar na no
mercado lá por exemplo quem compra
biscuit discutir e milk como papão tá é
uma regra que né a gente vê que não tem
muita relevância assim mas digamos que
tivesse relevância que a pessoa não
soubesse
então ela poderia colocar a nossa regra
que eu não sabia isso aqui eu não sabia
que quem votava biscoito comprava leite
comprava pão o que eu vou fazer eu vou
pegar vou colocar o pão próximo dos
biscoitos e do leite
e aí eu vou testar se isso se as vendas
realmente aumenta ou não tá mais ou
menos assim que vocês vão ter que fazer
a aplicação dessas regras das regras são
aplicadas na prática
então aqui vocês podem fazer um combo
também o quem comprar a discutir o que
corre flex compra café tá você pode
fazer um combo desses produtos aqui
colocar o próximo do café também tá e
assim vocês vão fazendo estudando as
regras de vocês
tranquilo o pessoal aqui de um pouco
porque nosso conjunto é porque né agora
vamos fazer a mesma coisa que a gente
fez carregar um arquivo saque base dois
agora a gente vai pegar aquele real
daquele mercado que tinha deixou abrir
aqui
o supermarket aqui carregou sem
problemas tá bom somar com ele aqui a
gente vê tá é um um arquivo bem maior né
então tem 7501 linhas
tá por 119 colômbia está o produto que
mais saiu foi água mineral depois ovos
paquete chocolate os outros aqui eu
posso fazer um lote na freqüência que
ficou bem ruim é porque são muitos
produtos né
não dá nem pra ver os nomes aqui ó
então vou dar um plot que de novo só que
com um top 5 está como a gente tinha
feito então a gente busca aqui os
produtos aqui com maior freqüência a
gente pode ver que a água mineral ovos
de chocolate como já tinha aqui em cima
dessas informações para nós está pode
aumentar isso aqui a gente pode botar
por exemplo 10 apareceu mais o assim
vocês podem trabalhando também em um
suporte de 0.5 0.5 vamos rodar aqui
acontece 10 regras um pouquinho esse
suporte a 0
o que acontece quando o conjunto de
vocês é muito grande
tá então sou muitas vendas que acontece
tá e os produtos eles tenham menor
freqüência de saída
então o que vocês podem fazer vocês
podem fazer um
hum como calcular o suporte né podem
usar uma estratégia está por exemplo
está o que eu estou fazendo aqui tá eu
vou fazer o seguinte ó eu quero um
produto que sai a quatro vezes
tá quatro vezes digamos que esse que
esse conjunto de dados que se referem a
três dias de venda tá então quero um
produto que saiu quatro vezes em três
dias a que essa amostra que tem poderia
ser uma semana e seria 7 duas semanas 14
eu vou multiplicar esses dois valores
está multiplicar isso aqui vai dar 12 né
12 tac o que eu vou pegar fazer vou
pegar o 12 e vou dividir pelo número de
linhas que eu tenho já então eu tenho lá
7500 em uma linha está então vou dar um
contra o inter de novo agora eu tenho
aqui um valor que é 0.001 colocar usar
esse valor aqui como suporte
tá então vou dar um control em ter aqui
é legal a 74 regras é eu posso
visualizar essas regras
tá tem várias regras aqui ó
por exemplo quem comprá leite frente
fria e esse nome é que eu não sei como
está mas parece uns schiff não seja
pronunciado deixar para vocês aqui dá
também comprar chocolate está com o
suporte de 0.01 e uma confiança de 88%
então assim como mal quando a base de
dados de vocês é muito grande está e
vocês querem saber como elas podem
começar a calcular você pode usar essa
estratégia está a freqüência que o
produto saiu o tempo
é a ou seja o intervalo de tempo de
duração do que foi feita essa essa
análise de de vendas é por exemplo a
esse conjunto que se refere às vendas
realizadas em uma semana
são 17 aqui tá pega o valor e dividir
pelo número de de linha está bem
tranquilo eu dividir aqui deixou
diminuir um pouco a confiança e colocar
5
nossa olha só 1377 regras está
inspecionando as regras aqui olha só
carregando carregando carregando
carregou a última regra pessoal é muita
regra pra vocês olharem está há uma
coisa que a gente nota aqui por exemplo
água mineral sempre aparece
tá e às vezes pode ser meio óbvio a aaa
produtos açaí por exemplo quem comprar
um salgadinho comprar a água então às
vezes água pode ser um água ou qualquer
outro produto pode ser um um produto que
se repete muito na nossa base de dados
então de repente vocês podem como vocês
podem fazer o tratamento disso vocês
podem eliminar esses produtos que que
aparece com maior frequência podem
eliminar a água pode eliminar os ovos e
assim em testar o a priori de novo só
com os outros produtos tá eu vou dar um
exemplo pra vocês por exemplo a uma loja
já a que vende e água
a loja vende gás e vende água por
exemplo digamos uma que vem da água
já a loja vende água mas ela pode vender
outras coisa pode vender bala pode ver e
cigarro
pode vender produtos alimentícios em
geral nep mas pequenas coisas erva mate
esse tipo de coisa tá mas o foco da
empresa é a água
então se você for fazer 11 regras da
sucessão em cima dessa empresa água
sempre vai aparecer
tá mas de repente não é interessante
porque o foco da empresa é a água tá
então é interessante seria eliminar a
água e ver o que a empresa vende é qual
a relação dos outros produtos vendidos
fora a água tá então estratégia você
pode utilizar bom
outra coisa que a gente pode fazer aqui
também tá na hora da fazer a inspeção é
utilizar o software está com sorte ele
vai dar um ordenado nesse nesse nosso
conjunto aqui e como coordenar então
chama um espectro
vou passar o sorte o software receber
mais dois parâmetros está num vai ser às
regras regra um que foi que eu criei
agora eu vou mandar ele ordenar pelo que
possa ordenar ele tanto pelo suporte
pela confiança como pelo lift tá eu vou
mandar ordenada pela confiança e eu
quero que mostre apenas os elementos
regras do de uma 30
vou dar um control inter aqui ele pode
ver aqui a 30
ele ordenou pela confiança
o vento aqui em cima até passei é todo
no outro jogo
só sei se para baixo aqui olha só
olha só
então tenho a confiança aqui ó
a confiança 111 e já cai ano a 5 959 13
em torno de novo pela confiança tá
poderia ordenar pelo valor do suporte
pelo lift está também não teria problema
nenhum
tá eu tô aqui esse outro parâmetro que
tá indo junto aqui tá com uma confiança
é o número que eu quero que mostra então
quero o doou 30 por exemplo depois que
eu faço análise
eu posso o selecionado 30 aos 60 por
exemplo 60 contra o inter
e aí eu busco sem as regras também
tranquilo o pessoal tá aqui as as minhas
outras regras o bom era assim isso que a
gente tinha pra ver que sobre o a priori
tá
sugiro que vocês deem uma olhada
nesses parâmetros aqui o suporte
confiança lift está como eu disse eu
tenho uma playlist do eca já tinha feito
esse momento mais sobre parâmetros lá da
importância deles eles são extremamente
importante você tem que conhecer esse
parâmetro está a idéia dessa playlist
aqui não entra muito no detalhe e
mostrar como utiliza mesmo as
bibliotecas e os algoritmos está a
[Música]
parece simples mas para fazer uma
análise e fazer um emprego não é tão
simples assim tá então sugiro que vocês
deem uma olhada também no material
estude um pouco mais sobre regras da
associação tá algoritmo mais comum que a
gente viu sendo utilizado eu a priori tá
mas a gente vai estudar outro também nos
próximos vídeos também pessoal
bom vou ficando por lá por aqui
qualquer comentário que vocês tiverem
dúvidas podem ser os comentários aí a
quem gostou da light escrevo no canal
compartilhem ativo notificações e nos
vemos no próximo vídeo valeu