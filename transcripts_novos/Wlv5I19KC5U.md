# Aula 09 – Dados fundamentalistas com a GetDFPData - Trading com Dados

- **URL:** https://www.youtube.com/watch?v=Wlv5I19KC5U
- **ID:** Wlv5I19KC5U

## Transcrição

e nessa seção o pessoal queria
apresentar para vocês a mais uma
biblioteca na verdade a última
biblioteca do nosso tutorial que vai nos
ajudar seção 6
tô trabalhando com dados
fundamentalistas Então se vocês não
tiverem aberto essa biblioteca ainda
podem pegar que tá
E aí
e vai trabalhar com essa biblioteca a
gente precisa Na verdade é um pouquinho
de paciência porque normalmente quando a
gente traz dados de balanço de empresas
né os trimestrais a mente vem muita
informação a gente sabe que os balanços
trimestrais das empresas de Capital
aberto divulgam são arquivos gigantescos
vem muita coisa então provavelmente aqui
quando vocês forem trabalhar com a sua
biblioteca é bom ser trabalharem com a
volume reduzidos né períodos reduzidos
para facilitar a extração uma função
bacana dessa biblioteca essa daqui
pessoal a g de fpd
o ponto g' a ponto info campeões Por que
que a gente executa esse daqui quando
ele terminar de executar Esse comando e
a gente obter aqui o nosso objeto a
gente vai ver que a gente precisa da
descrição das empresas na hora de fazer
as consultas Por que vão abrir aqui os
dados quando a gente faz as consultas
com essa biblioteca a gente usa aqui o
nome da empresa né O que tá na descrição
ali do contrato social da empresa não é
nome social da empresa então por exemplo
se vocês quiserem pegar esse daqui eu
acho que é Sabesp Observe que esse aqui
Qual é o nome o nome social né vamos
continuar olhando aqui eu tenho alupar
tentar ordenar esses daqui
é por ordem alfabética
E aí fica até mais fácil talvez não é
pelo fato do deitar frame ser um pouco
extenso isso demora um pouco tá pessoal
é mas vamos dar uma olhada Tem empresas
aqui na verdade que eu nunca ouvi falar
né gente só tem muita empresa aí de
Capital aberto na verdade não tanto
quanto deveria ter né no Brasil tem
cerca aí vamos ver aqui 525 empresas nos
Estados Unidos é mais de 10 vezes isso
mas enfim tem bastante descrição aqui
nós temos movida MRS tem uma empresa
específica que eu queria aqui trabalhar
com vocês vamos ver se eu acho
e pronto olha essa empresa aqui que eu
queria mostrar para vocês na bolsa a
gente tem a real três tem esse código
que a referente arrumo empresa né de de
ferrovia saúde tem se vocês passaram
aqui para baixo vocês vão ver aqui para
mesma empresa
e vocês vão ter vários CNPJ da empresa
lá
e muda aqui o nome social e tal mas
essencialmente a mesma empresa Então o
que é que a gente precisa fazer vou
pegar o nome dessa empresa aqui
e vai ser o meu nome de referência eu
vou chamar essa daqui de Campo aí tá
bom então uma vez que a gente encontrou
o nome social da empresa que a gente vai
usar de referência para fazer nossa
consulta a gente pode passar os outros
parâmetros que vão como argumento na
função então data inicial a gente pode
colocar
O Primeiro de Janeiro 2019 por exemplo é
bom colocar um período pequeno tá
pessoal porque você consulta ficar muito
grande demora muito e possivelmente a
gente não vai conseguir vai ficar muito
dado né muita informação e possivelmente
a gente não vai conseguir ver tudo Vou
colocar até 1º de Janeiro 2020
Oi e o tipo de exportação pai
de esportes eu vou dizer que é xlsx para
que ele faça o download e internamente
um arquivo em Excel
o executar isso daqui a função que vai
fazer a consulta é essa daqui ó g de
fpd. Get The app deita e aqui gente vai
passar os parâmetros então nome das
empresas vai ser aqui
o Campione
a first date vai ser o bem que a gente
definiu lá em cima Leste deixe vai ser
aqui a nota final e por enquanto é isso
vocês tiverem dúvida a gente pode
consultar também aqui
e o manual da função
é aparentemente é isso que a gente
precisa deixa eu ver se Faltou algo
e vamos é que está isso aqui então
pessoal avô assinar lá isso Algum objeto
eu vou falar que são Dados fundo the
Hill 3 dados fundamentalistas de rumo a
aparentemente ele conseguiu então
encontrar os dados fundamentalistas ele
tá fazendo download como dados de
balanços como eu falei né são Dados
extenso tem bastante coisa Possivelmente
ele leve alguns minutos para fazer todo
download só dá uma olhada aqui
vou ver se ele vai dar uma ideia do
tamanho do arquivo
a e agora então a gente espera então ele
terminou o download aqui vamos ver o que
ele falou né
o processo em até assim download
é bem aparentemente deu certo então
vamos abrir aqui ver o que é que eles
não nos trouxe vai PSOL então
aparentemente não deita frame vão abrir
se deitar frame para ver o que ele tem
dentro Olha que interessante pessoal é
um deita frame que dentro de se deitar
frame ele tem vários outros deitar frame
Então vamos ver aqui algo interessante
para a gente analisar a cor toque
holders bacana isso né quem são os Os
acionistas Atuais Como que é o capital
social desta empresa vão abrir Street
afreim
é bem aparentemente é só ó o América
América Latina logística ela tem 100
porcento do Capital em não entendo
Exatamente porque isso né já tirei o
trem deveria ter um uma parte na na
bolsa também
é mas deve ter alguma explicação para
isso que outros indicadores a gente pode
ver aqui então vamos dar uma explorada
a composição atual da ação Vamos ver
isso aqui
e Olha que bacana a gente consegue ver
quantas ações estão negociadas das ações
ordinárias e das ações preferenciais né
do capital social da empresa não
consegue ver os ativos dessa empresa
Então vamos lá
Olá a todos os ativos ativo circulante
caixa equivalente de caixa aplicações
financeiras contas a receber bastante
coisa fluxo de caixa como são importante
né pessoal para qualquer análise
fundamentalista
E então percebo que tá bem bem completo
isso aqui também diz que caixa líquido
atividades operacionais caixa gerado nas
operações variações nos ativos e
passivos
e obviamente não vou entrar em detalhe
aqui que eu acho que nem é a minha
intenção aqui nesse tutorial a da gente
entender todas as variáveis todo
indicadores fundamentalistas eu acho que
aqui o que vale a gente ressaltar né
mostrar que esse dados eles estão aqui
disponíveis uma forma estruturada a
gente consegue usar nas nossas análises
então coisa bacana que eu tinha visto o
que são dividendos os dividendos pagos
percebam que a empresa não pagou um
dividendo interessantes bem a gente viu
que são vários deitar freios dentro de
um deitar frame a gente quiser um desses
desses daí para fins específicos não é o
que a gente faz então a gente precisaria
vir aqui
como ver o número da coluna né então é
e vamos supor aquela stockholders 0 a 11
não se eu quisesse ou deitar firme tá
dentro dessa coluna 11 como que eu
poderia fazer
eu gostaria eu pegar a isso daqui eu
ainda que só isso daqui para trazer
apenas esse elemento 11 eu chamaria isso
de alguma coisa com quadro social por
exemplo isso a gente executasse daqui
tem que eu teria eu teria uma lista
dentro dessa lista obviamente eu quero
apenas o primeiro elemento E aí eu
Poderia gerar um deita frame disso daqui
bom então a gente teria o quadro social
aqui de uma forma bem mais organizada tá
pessoal da mesma forma Vocês poderiam
fazer isso para outra coisa vamos ver se
tem mais coisas interessantes aqui para
gente trazer esse aqui é bacana o
histórico de dividendos vamos ver se tem
alguma coisa
eu estou demorando para carregar Imagino
que esteja vazia tá
e vamos ver aqui o fluxo de caixa é de 7
a 17 eu vou chamar essa pedir
o fluxo de caixa
bom então a gente tem um deita frame aí
com informações do fluxo de carro
bom então de uma forma relativamente
tranquilo a gente conseguiu trazer dados
fundamentalistas para auxiliar nas
nossas análises E aí para terminar a
pessoal só voltando um pouco eu queria
mostrar para vocês algumas ferramentas
né a gente falou há pouco tempo da
biblioteca quanto molde se vocês tiverem
curiosidade eu acho que vale a pena
entrar aqui no site da própria
biblioteca né que o autor da biblioteca
e frio escrevendo um pouco se o
funcionamento se vocês entrarem aqui por
exemplo na galeria
e vocês vão ver que ele dá alguns
exemplos de indicadores de análise
técnica que se podem obter então por
exemplo aqui vocês têm ao volume e tem
coisas como a Ingrid força relativa a
índice de momento estocástico dentre
outros tá bem bacana dá uma olhada para
que você tem que quem quiser né quem
tiver mais curiosidade de olhar tem
também o próprio manual aqui da
continuou dica aí tem várias ferramentas
de análise técnica disponíveis para
vocês usarem no próprio aqui beleza
pessoal esse era o conteúdo do tutorial
que eu tinha para apresentar para vocês
né onde Vocês conseguem usar a linguagem
é para obter e analisar dados de ações
espero que vocês tenham gostado e se
vocês quiserem conhecer mais sobre o
nosso projeto da trade em Condados
convido todos vocês a entrarem no nosso
site vou mostrar o nosso site aqui para
vocês
eu creio em com dados.com nosso site
vocês podem conhecer um pouco mais sobre
a gente conhecer um pouco mais aí sobre
a nossa história no nosso site também
vocês têm acesso
e ao nosso então convido vocês a darem
uma olhada nos cursos que a gente tem
não deixe também de conferir o nosso
canal no YouTube e as nossas redes
sociais porque a gente tá sempre
postando conteúdo de Inteligência
Artificial programação estatística
ciência de dados voltados ao mercado
financeiro espero que vocês tenham
gostado aí do nosso tutorial foi um
prazer ter feito esse material esse esse
curso neste minicurso para vocês Quero
Agradecer mais uma vez ao Tiago pelo
convite né a todo mundo aí da
estatidados e que gera conteúdo não é
uma referência gigantesca para deitar
ações no Brasil e foi uma honra
gigantesca receber um convite dele e tô
aqui gerando o material para o canal
dele então Thiago mais uma vez muito
obrigado pelo seu convite Espero que
todos vocês aí tenham gostado do
tutorial áudio do minicurso que a gente
gerou e conto com a participação de
vocês aí quero ver vocês também
e nos nossos workshops nas nossas lives
nossos cursos beleza pessoal grande
abraço e a gente se vê em breve 1