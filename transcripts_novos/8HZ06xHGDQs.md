# Aula 1 - Trabalhando com os microdados da PNAD COVID19 no R - Prof. Cleiton Rocha

- **URL:** https://www.youtube.com/watch?v=8HZ06xHGDQs
- **ID:** 8HZ06xHGDQs

## Transcrição

Olá a todos, meu nome é Cleiton.
Rocha, e neste vídeo vou te mostrar
Como trabalhar com microdados
PNAD COVID em R. Vou te mostrar como
Baixe-os, carregue-os no R, faça
mudanças e finalmente gerar o
gráficos. Então vamos lá.
Em primeiro lugar, eles vão acessar o
O site do IBGE está correto? Ele
covid19.gov.br barra, ou melhor
, pnadcovid. bar. Então, neste
página em que você vai clicar aqui
Downloads, certo? E eles serão
redirecionado para esta parte aqui. Ei,
Aqui mesmo, na seção de downloads, ele aparecerá assim.
fechado. Eles vão clicar aqui.
microdados, dados e escolha o mês que
Você quer. Neste vídeo, vou...
trabalhando com os dados de junho, que
Essas são as que eu já tenho aqui no
O computador está funcionando bem? Mas não é só isso.
impede que eles trabalhem com qualquer outra pessoa.
mês. Então, quando você baixar isso
arquivo compactado, certo? Eles vão
Descompacte e estes dois arquivos serão gerados.
arquivos, dados e dicionário de
o PNAD. Hum, eu recomendo que você crie
uma pasta de trabalho específica com
Esses dados e depois disso eles
Copie o caminho para essa pasta, certo?
bom? Então, por exemplo, aqui,
Eles copiam e vêm aqui para R e escrevem
setwd. E eles vão colar o...
rota, entendeu? E onde quer que haja um bar
Eles sempre acrescentam mais um. Então,
Feito isso, basta carregá-lo. Preparar.
Então, esta é a pasta de trabalho.
que usaremos aqui no RStudio.
Ah, os pacotes para trabalhar com o
Os dados PNAD serão dplyr, que é
para manipulação de dados e pesquisa,
que é um pacote focado em pesquisas
como esta. PNAD, readr é um
pacote para carregamento de dados; ggplot2 é
Um pacote para geração de gráficos;
O tidyr, assim como o dplyr, é usado para
Realizar algumas manipulações de dados.
E o Cairo é um pacote complementar de
ggplot2. É usado para extrair dentes.
da imagem e melhorar a aparência de
Gráfico geral. Hum, por precaução
Não tenho esses pacotes instalados.
antes de escrever a função da biblioteca,
Eles devem digitar install.packages.
Então, veja só, e entre aspas
Escreva o nome do pacote que
Eles querem instalar, tudo bem? Como eu
Eu já os tenho instalados, só preciso
chamemos esses pacotes. No vídeo de
Não vamos trabalhar com esses dois hoje.
pacotes abaixo. Então aqui está
Os pacotes já foram carregados. Então
Agora eu tenho os pacotes e o meu
pasta de trabalho definida. Então
O que vou fazer agora é carregar o
dados. Então, vou dar um nome a
O banco de dados que eu quero. O
Vou ligar para penade_line covid. Vou usar
a seta e a função read_csv. CSV.
Aqui vou inserir meu nome.
banco de dados, que é este nome de
Aqui, ok? Basta copiar e
Cole aqui entre aspas junto com o seu
extensão, que é CSV. Hum, em
col_types Estou relatando que o
O padrão para colunas é D, que é
duplo, ou seja, é sempre o formato.
Numere as colunas, ok?
Então vou carregá-lo agora. Ah, por
carregar um fragmento de código no
script, eles podem clicar em qualquer
ponto do mesmo e pressione control
Pressione Enter para executar. Ou eles podem
selecione tudo, venha aqui e
Pressione Executar. Isso depende de você.
Então, o banco de dados foi criado.
Você está assistindo? Agora precisamos
Ative os pesos. Como fazemos isso?
Vou dar um nome a este novo.
variável que estou criando. O que é o
Tabela do tipo pesquisa. Então ele
Vou colocar este nome, punido com pesos,
Muito criativo. Hum, vou ligar para o
banco de dados que carregamos, certo? E eu vou
para usar o operador de tubulação, que é este
pequeno símbolo aqui, porcentagem mais alta
isso, porcentagem. Eles podem escrever ou
Eles podem pressionar a combinação.
controle de mudança m e lá é gerado um
Operador de tubulação. Então, depois do
Vou usar o operador pipe, vou usar a função
svydesign, que faz parte do pacote de pesquisa. E
Vou inserir alguns aqui.
Informações da prisão, certo? Aqui
No IDS, direi qual unidade é.
amostragem primária. Em estratos é o
estrato de amostragem. Pesos é o peso
. E no Nest eu digo que quero
que aninhamento ocorre dentro do
estrato de amostragem. Esta informação,
upa, estrato e o peso da variável
Eles encontram isso no dicionário, tudo bem?
? Então vamos subir aqui. Aqui
estrato, unidade primária, o peso com
Pós-estratificação, certo? E
Estou filtrando meu capital aqui, não é?
Quero trabalhar somente com Salvador. Então
O que direi aqui? Filtrar capital é igual a
29. O número 29 chegou. Salvador. Então
Vou carregá-lo agora. Preparar. Meu gráfico
Foi criado um tipo de pesquisa. Agora com
os pesos das variáveis. Qual
O que vamos fazer agora é criar alguns
colunas. com as informações com o
que queremos trabalhar. Então, eu vou
criar dentro desta mesma tabela, não
Não vou criar nenhuma informação nova.
Sem nova base, então a
Vou ligar para cá e para lá, vou usar o
Vou usar o operador pipe e a função.
mutate, que vem do pacote dplyr para
Criar colunas. Este "um é igual a um"
Eu explico isso mais tarde, ok? Quando
Vá trabalhar com ele. Hum, então
Vou criar a primeira coluna aqui:
sexo. Utilizando a função if_else. Ele
O if_else funciona da seguinte maneira:
Se essa variável for igual a um,
Defina-a como homem, caso contrário,
Mulher, sim? Então, isto
informações, mais uma vez, o
Podem ser encontradas no dicionário. Não sei
Esqueça o dicionário. Então aqui está
, veja, o nome da variável e seu
Informações do rótulo: um homem,
Duas mulheres, sim? Então, eu sou
Usando if_else aqui. Ah, para o
Para a idade, vou usar a função case_when.
É usado para criar intervalos, certo?
nos valores. Então, por exemplo,
Na variável de idade de 15 a 24 anos, sim?
Usando a função %in% aqui em vez de
Comigo também, né? Para intervalos o
Eu uso. Portanto, estou relatando que
De 15 a 24, crie este rótulo; de 25 a
34 crie este rótulo e assim
sucessivamente até atingir um valor maior que
64, que eu defino como 65 ou mais. Preparar.
Agora vamos falar de cores. Estou fazendo uma denúncia aqui.
um branco, dois pretos, quatro
marrom. Para este vídeo, vou usar apenas
as três raças, porque a grande maioria
Ou melhor, da população
metropolitano pertence a um dos
Essas três corridas. Mas, caso
Quem estiver assistindo a este vídeo, seja de
região norte e quero trabalhar
Também com os povos indígenas, é interessante.
. Qualquer pessoa da região sul ou sudeste
Usar "amarelo" também pode ser
Útil, não é? Mas para Salvador, estes
Três raças são mais do que suficientes. Ei,
aqui na escolaridade, antes de usar
case_when, estou usando a função
fator. Porque? Porque ao usar
fator associado à função de níveis,
Consegui organizar meus dados.
Porque eu não quero, por exemplo, que
Ao gerar um gráfico de barras, o
a primeira barra que aparece é
fundamental, seguido pela média e depois
Sem instruções. Não, eu quero preservar.
Esta ordem aqui, começando de fora
Instrução até o nível de pós-graduação.
Então, antes de usar `case_when`, eu usava
fator, eu reporto os parâmetros
normalmente, como fizemos aqui,
E então definirei os níveis.
Então eu coloco na ordem que eu quero.
que aparece, que cada etiqueta
aparecer, ou melhor. Então, feche-o.
Aqui, bem pertinho, tá bom? tipo de
emprego, assim como educação,
níveis de fator. Então, estou usando
Aqui estão as informações do funcionário.
doméstico, militar, policial, setor
privado, público, empregador e
autônomo. Nessa faixa salarial, eu vou...
Para criar as categorias, certo?, de
Salário que eu almejo. Então, menos que
um salário mínimo, entre 1 e 2, e 3,
OK? Coloquei esse valor aqui entre
parênteses, este intervalo, melhor
disse, entre parênteses, apenas para um
É uma questão estética, entendeu? Mas isso
Não interfere com nada. Você pode
Use 100, como temos feito.
aqui. Então aqui está, mais uma vez.
Eu criei, não criei?, uma ordem na qual eu quero
que aparece, começando com menos de um
Salário superior a cinco. Ah, aqui está.
Situação em casa, teletrabalho.
Aqui estou eu usando isso entre os fiéis. Então,
Um deles está trabalhando remotamente.
que não está presente pessoalmente, o que é
dois, e ajuda de emergência, quem
Quem não recebe ajuda, acaba recebendo. Ei,
lembrando que este último parêntese
Você precisa fechar aqui, ok? Mutar.
Pronto, é só carregar e funciona.
Isso mesmo, ok? Eles podem ver que
Não houve erros. VERDADEIRO? Agora vamos
para criar as tabelas com as informações
que queremos gerar os gráficos
. A primeira será o teletrabalho.
Por sexo e cor, ok? Então eu irei.
para criar a tabela chamada home_line
linha_sexo cor. Vou chamar esta tabela de
o servidor com o qual estamos trabalhando,
Operador de tubulação. Vou solicitar o agrupamento por
Sexo e cor, certo?, educação e
Resumindo, ou seja, realiza uma ação.
geralmente baseado no que eu sou
agrupamento. Então vou criar um.
coluna chamada teletrabalho. Vou usar
a função serve_total. E aqui
Informo que o teletrabalho é C03 = 1 e
Solicito a remoção dos valores ausentes. Aqui
Informo que a mão de obra é a variável.
C01. Você pode ver isso aqui no dicionário.
C01. Você fez alguma coisa na semana passada?
trabalho? Então eu defino o que é um e
Solicito também que seja removido. Aqui estou
criando uma nova coluna que será
Esta coluna com a porcentagem, certo?
de pessoas que trabalham remotamente. Então
teletrabalho entre os trabalhadores
multiplicado por 100. E peço para remover
Valores NA, ou seja, valores ausentes.
Mais uma vez. Então, carregando isto
Aqui, pronto. Então, veja só,
os valores de sexo, cor, uh, o
rótulos, ou melhor, valores.
Então, eu tenho 66.000 homens de cor.
brancos no total da força de trabalho. E
Desses 66.000, 13.000 estão em
teletrabalho. Então, aqui está uma mulher morena.
Possui um total de 213.621 mulheres.
mulheres mestiças da população metropolitana
e desses, 44.000 estão em teletrabalho.
E a porcentagem dará isso, ou seja,
isto dividido por isto. Então, no dia 21
% dessas mulheres estão em teletrabalho
. Ah, esta coluna aqui, casa
office_line e mão de obra_line, são os
erro padrão, ok? Neste vídeo
Não trabalharemos com erros padrão.
Estamos interessados ​​apenas na porcentagem de
nós geramos. VERDADEIRO? Para gerar o
gráfico, opa, para gerar o gráfico
Vamos usar a função GGPLOT. Esse
O gráfico já apareceu porque
Eu já enviei antes, tá bom? Mas
Você vai ver agora. Hum, vamos usar o
Função GG Plot e informaremos a base
dos dados que queremos, que são estes
Acabamos de criá-lo. E em estética
Nós definimos os parâmetros, certo?
treinamento. Então o filtro será o
A cor, no eixo Y, representa o trabalho em home office.
que é a porcentagem, e o eixo X é
sexo. É um gráfico de barras. E aqui
Inserimos algumas informações.
Carregando isto. Preparar. Aqui está um texto sobre chiclete
Esta é a informação aqui que
Aparece no topo, ok? Em outras palavras, o
valores, certo? texto. Estou usando um
Tema clássico. Aqui estão alguns
informações, certo?, sobre o assunto, como o
Eixo X, eu quero em preto, certo?
este nome aqui, o eixo Y, o texto
do eixo Y, eu quero em [ __ ]
Tamanho 10, que é este aqui. É, o
linha, este contorno aqui em cores
preto, o título deste tamanho, este
cor e assim por diante. Aqui o
"Legenda, quero que ela permaneça lá embaixo."
Talvez eles não vejam isso muito bem.
vídeo, mas há um esboço ao redor
Segundo a lenda, trata-se de um cinza muito suave.
É por isso que a função de fundo da legenda...
Onde eu informo a cor, sua escala, certo?
? Aqui nos laboratórios, eu reporto o nome que
Quero isso para meu próprio conhecimento, isto é, em
Eixo X: Quero sexo, aqui a porcentagem
e a legenda é o rodapé, onde
Eu escrevo a fonte dos dados, certo?
O título e o menu são as cores, certo?
OK? Então aqui estou eu definindo
As cores que eu quero para cada barra.
Isto aqui é RGB. Existe até um
Há mais cor aqui, mas não há
problema. Escala Y, script Y. Eu sou
informando que eu quero este eixo Y
Vá de 0 a 100, em incrementos de 10, ?
correto? E seu nome é porcentagem. E
Vou fazer o upload disso aqui como uma lista.
É por isso que você vê um nome.
seguido de uma seta. Então, tipo isso
Eu carrego meu gráfico em formato de lista.
Então eu posso guardar, tudo bem?
Então vou usar a função Salvar do GG.
Vou informar o nome dos dados, certo?
?,desta lista. Vou informar o nome.
Com quem eu quero que ele compareça e
Vou salvar com a extensão PNG. Aqui estão
Algumas informações sobre o tamanho,
OK? e tipo igual a Cairo, que
É o tipo de imagem que lembra o Cairo. Como
Você deve se lembrar, nós carregamos o pacote aqui.
Cairo, certo? Assim que estiver carregado, estará pronto.
Já temos uma imagem do gráfico em
nossa pasta de trabalho. Então
Eles percebem que a qualidade da imagem é muito boa.
Bom, né? O Cairo elimina isso.
serrado do mesmo. O tamanho
Também é agradável. Acho que agora
Fica melhor com um contorno cinza.
Por aqui, né? O resto
Agora está muito parecido, tudo bem?
Então, trabalhando em casa devido aos estudos e
cor. Vou agrupar por escolaridade e
cor. Ok, a informação foi criada.
Olhar. Agora carregue isto e salve. Ter
Aqui e agora, home office por sexo e idade.
e trabalho. Aqui estão algumas notícias que eu tenho:
Está ordenando o eixo X, certo? Uh,
O que é isto aqui? Aqui
Basicamente, estou inserindo o eixo X.
manualmente, porque como você pode ver
Este nome aqui, trabalhador
doméstico (entre parênteses) é
bastante longo. Se eu não inserir o eixo X
manualmente, este nome aqui
acabará ocupando o espaço do
outros, ou seja, militares, policiais.
Assim, o gráfico ficará muito
Carregado, né? Ao inserir o eixo X
manualmente, posso incluir alguns
quebras de linha para controlar o
situação. Então, aqui está este N-barra
É para romper a linha. Então,
Entrei aqui manualmente e cheguei aqui.
com a função discreta de escala X e
Eu reporto os valores que desejo.
aparecer no meu eixo X. Então, eu carrego
esse. Preparar. Então, veja, eles podem
Observe que houve uma quebra de linha aqui.
Aqui também. Se isso não acontecesse, se
Eu não teria feito isso, esse nome de
Aqui ocuparia espaço.
É bastante grande aqui, como você pode ver.
Sobrepondo-se aos outros. Economizando
Escritório em casa por faixa salarial e cor.
Ok, salvando. E agora vamos para
Trabalhar com ajuda emergencial. ?
Eles se lembram disso no início do vídeo.
Eu disse que explicaria por que eu estava
Criando aquela primeira coluna, certo? Aqui
aparece pela primeira vez. Hum, eu sou
Agrupando meus dados aqui por intervalo.
remuneração. E aqui na Summarize, o
A primeira coluna que quero criar é
ajuda. É bastante semelhante àquele que
Nós o fizemos para o escritório em casa, certo?
Onde eu defino que a variável é esta
d51 = 1. Mas agora quero ver o total.
deste grupo, ou seja, o total de
pessoas com menos de um salário
mínimo, o total entre um e dois. E
Para fazer isso, vou criar esta coluna.
total. E nela eu relato essa coluna.
uma que nós criamos. que resulta nessa soma
total. Então você pode ver que nós temos
Aqui está o número total de pessoas que receberam
menos que um salário mínimo. Total
Entre 1 e 2 aqui, veja, 197.442
pessoas, menos do que um salário mínimo.
569.520 entre 1 e 2, 153.123 e assim por diante
sucessivamente. E dentre estes, que
Ele recebeu ajuda. Carregando...
isto aqui. Preparar. Eu tenho meu gráfico
preparar. Este é o meu gráfico favorito.
É, você está vendo isso aqui...
Está lá, é como um gráfico de barras.
, VERDADEIRO? Não são colunas, é assim que é.
, Tudo bem? Então. Para isso, eu usei
Essa pequena informação aqui, essa
Função de inversão do cabo, coordenada de inversão. Para o
Utilizando-o, eu crio um gráfico de barras.
Em vez de um gráfico de colunas, que tal um gráfico de colunas?
VERDADEIRO? Adicione à lista agora.
Salvar escritório em casa por tipo
lar. Eu também estou aqui.
Colocando manualmente o mesmo X.
Economizando. E agora, trabalho remoto por gênero.
Se funcionar. E é isso. Então eles verão
Aqui estão todos os nossos gráficos.
Eles estão armazenados em nossa área de trabalho.
E com isso, chego ao fim deste vídeo.
. Ah, agradeço a todos que
Eles enxergaram até aqui, ok? E eu sou grato.
Agradeço também ao Thiago pela oportunidade.
de gravação e disseminação em seu
canal. Espero que tenha gostado, não é?
Sim, pessoal? Um abraço. Bye Bye. Olá
a todos. M.