# Flexdashboard - Learn how to build dashboards in R - Caio Moreira

- **URL:** https://www.youtube.com/watch?v=mdsx8WNEOgc
- **ID:** mdsx8WNEOgc

## Transcrição

Olá a todos, é um prazer. Meu nome é Caio
Moreira, eu sou estatístico e fui
A convite do Professor Thiago Marques
Para apresentar a você o pacote Flex.
Painel. Com o Flex Dashboard será
É possível criar um tabuleiro como este que
veja na tela, onde neste exemplo
Temos dados de vários países. Isto
que é selecionado aqui, neste
Nesse caso, é o Brasil. E podemos visualizar
expectativa de vida, PIB por
per capita e população em milhões
população. Nesta aba temos
os dados apresentados no
gráfico e podemos filtrar o período.
Por exemplo, está aqui desde 1952.
até 2007. Vou escolher uma aqui.
período mais curto até 1982 e o
Os dados serão atualizados. Também
Podemos selecionar o país que nós
Interessante de observar. Por exemplo, eu vou
mudança aqui do Brasil para a China e o
Os dados são atualizados automaticamente.
Esta aba é dinâmica, ela é feita
usando o painel Flex e alguns
Funções brilhantes. Em contraste, isto
Outra aba é estática; Não importa
Qualquer escolha que você fizer aqui será definitiva.
igual. E nele temos os dados por
continente, certo? População total
dos continentes ao longo do
Ao longo do tempo, o PIB médio dos países
que compõem o continente e o
expectativa média de vida de
países do continente. Os gráficos
O que estamos vendo aqui foi feito
usando GG Plot, que não é o foco.
do vídeo agora, mas apenas presente
Como construir o projeto. E usando
Os gráficos do GG Plot com um
Função Plotly, chamada função GG
Tramicamente. Vou te mostrar isso, quando
posicionamos o cursor do mouse sobre o
O gráfico mostra os dados que são
Eles estão apresentando. Muito legal, né?
VERDADEIRO? Então vamos lá, eu vou para
mostrar como se faz e no final de
Este vídeo vai te ensinar como construir uma prancha.
tão bom quanto este. Ok, estou aqui.
Aqui em R, certo? E o primeiro passo
é instalar o pacote. Primeiro fazemos
Clique em pacotes e depois clique em
Na instalação, escrevemos o nome do
Pacote, flexível, nós selecionamos e fabricamos
Clique em instalar. Não vou instalar.
Eu já tenho o meu, mas só
É necessário instalá-lo e não há nenhum erro.
Após a instalação, para iniciar um
arquive e crie um quadro, nós viemos
Aqui, para um novo arquivo, e selecionamos
a opção R Markdown. Nós clicamos em
modelo, já que flex é um modelo
Do R Markdown. E se eles o instalassem
Agora deve aparecer corretamente.
aqui nesta opção. Eles o selecionam e
Eles clicam em OK. Isso abrirá um arquivo.
básico, que já serve como um design
Passos iniciais para construir seu tabuleiro.
Aqui está o título. Vou mudar o
Título aqui. Vou dar um toque de classe. E
Aqui está a orientação. Dele
A orientação é por colunas. E
Além disso, outra coisa que já faz é
Carregue o pacote flexível para nós.
painel. O design que nos entrega
Começa aqui com uma coluna. Aqui
É usado para definir o tamanho.
Tamanho, essa unidade que eu acho que está em
pixels. Uma coluna aparecerá com o
gráfico A e outra coluna com o
Os gráficos B e C, um sobre o outro.
Se você alterar a orientação aqui
colunas para linhas, quando você cria aqui
Seria uma fileira e outra fileira, a
Os gráficos B e C apareceriam lado a lado.
do outro. Então eu vou te mostrar como
A orientação por linha permanece a mesma. Vamos
Veja como fica esse gráfico aqui.
Este quadro pede que o salvemos.
Salve com o título da turma. E lá
Sim, o nome já mudou para o quê?
tinham colocado, turma, gráfico A, B e
C. Como criamos um novo?
página? Para criar uma nova página,
Chegamos e definimos o nome. O
Vou chamá-la de página um e usar o
sinal de igual, pelo menos três vezes.
1 2 3. Usando o símbolo três vezes
Da mesma forma, você entenderá que é um
página. Eu criei a página um. Eu vou para
Crie também a página abaixo.
dois. Vou deixar a primeira página com o quê?
que eu já tinha. E na página dois eles
Vou mostrar como criar as colunas.
Página dois. As colunas. Já volto.
Aqui, eu simplesmente escrevo coluna. Sim
Quero definir o tamanho, então copio isto.
Insira aqui o tamanho
É isso que você quer, certo? Vou copiar. Ir
para colocar em uma coluna muito menor
, VERDADEIRO? Coloque a primeira coluna.
Primeira coluna muito pequena. Eu vou para
colocar. Para indicar que se trata de uma coluna,
Eu uso hífens embaixo da palavra
coluna. Eu escrevo 1, 2, três traços e
Ok, você identificou que é um(a)
coluna. Para identificar o título de
onde este gráfico aparecerá, isto
mesa, qualquer que seja a minha escolha, eu uso a
hashtag. Vou chamá-lo de gráfico um. E
Vou inserir o código onde vou colocar isso.
gráfico. VERDADEIRO? Possui uma coluna,
Apenas um gráfico muito pequeno aparecerá.
xixi. Agora, digamos que eu queira
outra coluna. Vou excluir o tamanho.
porque irá ocupar automaticamente o
espaço restante. E nesta coluna
Quero uma pequena aba onde eu possa
para alternar entre um gráfico e outro, de um para outro
mesa para outra, tanto faz. Então
Eu pressiono tabulação 7, e o programa identifica as tabulações.
para que possamos clicar. E aqui vou eu.
É possível alterar o título do gráfico.
Vou inserir os dados como se fosse para
Alterar, inserir os dados um e dois,
como se eu fosse mudar de uma mesa para outra
dados para outro. Então, para construir
Seu painel de controle. Também vou aproveitar essa oportunidade.
Aqui estou eu, e vou mudar de assunto. Eu vou para
Escolha um tema que você queira, deixe mais
bonito. Viemos até aqui e
Alteramos a opção de tema e escolhemos
alguns. Pesquise na internet, você encontrará algo lá.
centenas. Vou escolher este time do United.
. É aquele do exemplo que eu mostrei.
Então voltamos a falar com ele. Vou levar
este arquivo que eu separei para
mostre-lhes. Vamos. O resultado
É este aqui. A primeira página é assim
como já era. É o gráfico A aqui,
B e C empilhados. E página dois
que acabamos de criar, a primeira
coluna muito pequena, que eu escolhi
tamanho. E aqui com abas, dados
um e dois dados. Se eu quisesse colocar um
pequena tabela para apresentar aqui, poderia
Mude um pouco as coisas, entendeu? Muito simples
Criar um projeto. Agora vamos para
exemplo que eu te mostrei e nós vamos
Entender o que ele contém e como instalá-los.
coisas dinamicamente. Certo, o quê?
Temos aqui? Primeiro, o título que
Eu escolhi a orientação, eu mudei de
colunas para linhas. Eu vou mudar, eu vou
Mostre a eles como adicionamos linhas agora.
E eu coloquei essa opção aqui, veja, quarto
igual a brilhar. Porque? Porque nós vamos
Utilize agora os recursos do Shiny.
começando com esta barra de seleção
que podemos ver aqui, veja, como
Fazemos isso para criar uma lista como esta.
e um desses bares onde filtramos o
período. Certo, vamos criar a lista.
Usamos o comando de entrada select. Aqui
Damos-lhe um nome que evoca o país.
selecionado. Digitei o código do país.
Este jogo de escolhas me dá a lista de
opções e o país que já está chegando
selecionado. Essa entrada cria uma lista
. O controle deslizante criará a barra que
É aqui que selecionaremos o período.
Isso está vazando para o gráfico, certo?
Para criar todo esse espaço, nós usamos
entradas, abrimos as chaves, pontos na barra lateral
, colocamos pelo menos três hífenes e
Indicamos o tipo de entrada que vamos usar.
ter. Dei dois exemplos aqui, mas
Podemos procurar outros, já que existem muitos.
avançar. Por exemplo, talvez você queira
Adicionar um botão. Esta parte do código
que é reativo, você precisará informá-lo
R é reativo. E é para isso que eles servem.
diversas funções, dependendo do tipo
da produção que você vai obter. Por
Por exemplo, nossa saída é um gráfico.
do Plotly, então eu uso a função
renderPlotly. Aqui eu criei uma linha,
VERDADEIRO? O título é esperado de
vida. Eu especifiquei a função renderPlotly.
Criei um gráfico com ggplot e usei o
Função ggplotly para transformar um
gráfico ggplot em um objeto do tipo
Plotly para que eu possa mover o cursor e isso
Exibir os dados apresentados no
gráfico. Então, o que é isso?
O que você está fazendo aqui? Aceite a entrada
do país, que é este aqui,
Referindo-se a: país. Refere-se a isto
lista de opções que eu criei usando o
Função selectInput. Pegue e filtre o
anos até o período que está aqui
na contribuição do ano. Usamos a entrada $
país para obter o país
selecionado da lista e insira o valor em dólares por ano.
para obter o ano selecionado aqui
. Então você executa esse código, certo?
VERDADEIRO? O código de pesquisa,
Digamos, e usando a função de entrada
com o símbolo de dólar, identificará
Qual opção está selecionada?
tanto na lista quanto na barra.
O RenderPlotly, como eu disse, renderiza
Um objeto Plotly. E nós também temos
a opção renderTable, que
irá renderizar uma tabela quando usarmos
Os objetos dinâmicos do Shiny, que são
Basicamente, é isso que tem aqui.
aba, o que muda. No outro
guia, análise por continente,
Como tudo é estático, é muito mais
simples. Só precisamos programar, em
o espaço de código reservado,
Aquilo que desejamos que apareça. Por
Por exemplo, aqui estou eu simplesmente
criando os gráficos com ggplot e
usando a função ggplotly. Não
Preciso mostrar ou indicar ao R o tipo
saída, como fiz no outro
guia usando renderTable para um
tabela ou renderPlotly para um gráfico,
nem utilize funções reativas. Apenas
Usamos isso quando usamos isso
Funcionalidade brilhante. Recordando
Insira esta opção aqui. Tempo de execução
igual a Brilhante. É isso aí, pessoal!
Espero que tenha gostado. Eles
Recomendo que você pratique, faça uma pausa
vídeo e tentem fazer vocês mesmos
O que eu apresentei aqui. E se eles forem
Se tiver interesse em entrar em contato comigo para qualquer assunto,
Para receber este código, você precisará usar esta classe ou código.
Vou pedir ao Professor Thago que se retire do meu quarto.
LinkedIn aqui na descrição.
Você pode entrar em contato comigo e me enviar uma mensagem.
mensagem para enviar o código a eles;
tanto a que criamos agora quanto a
Código de exemplo para eles testarem.
Modifique-o você mesmo e crie o seu próprio.
painel próprio. Agradeço ao professor.
Thago pela oportunidade de participar
aqui no canal e eu agradeço.
Obrigado por ficar comigo.
assistindo a este vídeo. Muito obrigado e
vejo você em breve.