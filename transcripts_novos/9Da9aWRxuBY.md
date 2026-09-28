# Lesson 1 - What are LLMS and what are they called (Part 1)

- **URL:** https://www.youtube.com/watch?v=9Da9aWRxuBY
- **ID:** 9Da9aWRxuBY

## Transcrição

Bom, pessoal, voltamos aqui. Vamos agora
de fato dar início ao nosso treinamento.
Vamos iniciar o nosso módulo um.
Bom, o módulo um, ele tem por objetivo
introduzir conceitos fundamentais sobre
o uso de LLMs, tá? Nosso módulo um, ele
tá organizado em duas lições e um
projeto. A primeira lição é relacionada
à chamada de LLMs, tá? Em seguida, nós
vamos verificar LCH Chain, mas qual que
é a conexão lógica entre esses dois
tópicos, tá? Nós vamos fazer chamadas de
LLMs, vamos eh verificar algumas
dificuldades ou algumas ah alguns
padrões que não são seguidos a depender
do LLM que você vai utilizar.
E vamos utilizar LC Chain como uma forma
de abstrair todas essas complexidades e
facilitar a nossa vida com respeito ao
consumo de LLMs.
Ah, e por fim, o nosso projeto que é
basicamente um chatbot com base em
contexto de documento, nós vamos fazer
uma prévia do que é regia, tá?
E então, basicamente essa proposta do
projeto. Nós vamos ter aqui documentos,
vamos extrair os textos dos documentos e
adicionar este texto extraído a um
prompt junto da pergunta do usuário e
vamos responder a pergunta do usuário
com base no contexto que foi obtido
documento.
Agora, pessoal, sobre a estrutura, sobre
como o como esse material tá organizado,
tá? vocês vão ter acesso a aos ao ao
material que eu apresento aqui, aos
Júpiter Notebooks, as apresentações.
E os materiais executáveis, eles vão
estar organizados em pastas nesse
formato, tá? Então, por exemplo, aqui o
nosso módulo um, nós temos o os Júpiter
Notebooks, temos também documento, que é
o que nós vamos utilizar como exemplo
projeto, e temos um markdown de
apresentação. Todos os módulos desse
curso seguir este padrão. Tudo bem?
No meu caso, pessoal, eu vou utilizar o
o VS Code, tá? Você pode ficar à vontade
para utilizar Jupiter Notebook ou
qualquer outra forma de você julgar
conveniente. Nesse caso, eu vou precisar
abrir a pasta específica, né? Tá aqui no
meu desktop, agent courses módulo 1.
Então, pessoal, aqui já temos já temos
acesso ao material correspondente ao
módulo um. dei uma otimizada no tamanho
da tela e acho que é suficiente para que
vocês possam ver. Ah, todo módulo tem o
material de apresentação. Então, bora
dar uma olhada no material de
apresentação do módulo um. Para
facilitar a leitura do Markdown,
aconselho vocês a utilizarem aqui o
preview.
Perfeito. Então, esse é o nosso módulo
inicial, conceito sobre é conceitos
gerais sobre uso de LLMs, chamada de de
LLMS, tá? Então, o objetivo é introduzir
os conceitos fundamentais relacionados
aos LLMs e você vai aprender diferentes
formas de construir ah os modelos de
linguagem e conhecerá algumas dos das
principais tipos e aplicações. E nós
vamos dar ênfase ao LC Chain, que é um
framework que é amplamente utilizado
para desenvolver aplicações hoje no
mercado. é um framework que tem boa
aceitação e o projeto é o
desenvolvimento de um chatbot capaz de
responder a perguntas a partir de
informações extraídas de documentos.
Perfeito. Então essa é a nossa breve
introdução sobre o módulo um. Um tópico,
uma informação relevante, pessoal, é que
nos slides eu não tô trazendo conteúdo
teórico. Então vamos iniciar aqui o
nosso primeiro Júpiter Notebook. Aqui
você vai perceber perceber que dentro
dos notebooks desses módulos aqui eu tô
trazendo várias vários textos
descritivos e comentários que eu peço
que vocês leiam com atenção, como por
exemplo aqui do da nossa primeira lição
sobre chamadas de LLMs. Aqui eu tenho
uma descrição sobre KLM. Aqui eu tenho
eh comentários, né, sobre as bibliotecas
que vocês vão precisar utilizar, onde
que vocês podem ter acesso a as API keys
que eu tô apresentando aqui, tá? Eu tô
trazendo aqui algumas alguns valores de
variáveis de API aqui, mas assim,
problema que todas as fontes que eu tô
consumindo gratuitas e que na verdade eu
sempre tô deletando essas API kes.
Então, eh, eu o que o que eu peço para
vocês é que vocês acompanhem o Júpiter
Notebook, que eu vou estar desenvolvendo
ao longo da aula. Eh, e que vocês façam
a leitura dos comentários e do que tá
escrito aqui nos Marks, tá, pessoal?
Perfeito. Bora lá. Módulo um, aula um,
chamada de LLMs. Mas antes de tudo, o
que que é um LLM? Basicamente, pessoal,
hoje quando se fala de AI, se fala de
LLM de forma não explícita, tá? Ah,
então o que é que é um LLM? LLM é a
sigla para large language model e é um
tipo de inteligência artificial treinado
para compreender e gerar linguagem
natural. Ele aprende a partir de grandes
volumes de textos e consegue responder
perguntas, resumir informações,
traduzir, criar textos e até resolver
problemas complexos. Então, os LLM são
modelos que são treinados com uma
quantidade extensiva de informações e
que tem tem a capacidade de compreender
e gerar respostas no formato de
linguagem natural. Eh, hoje em dia a
gente já tem alguns modelos multimodais,
né, que conseguem eh gerar eh respostas
em diversos outros formatos, tá? Então,
pessoal, como primeiro exemplo, nós
vamos fazer uma primeira chamada de LLM,
né? Eh, para esse primeiro exemplo, nós
vamos utilizar o Grock. E o que que é o
Grock? Aqui tem o o link, tá, para vocês
acessarem.
Eh,
eu vou acompanhar com vocês todas as
etapas como se eu não tivesse executado
nada, tá pessoal? Então, vamos aqui ir
no Grock. O Grock, basicamente, nós
vamos utilizar o Grock para consumir
Lls, tá? Ah, então você vem aqui em
developers, free API key, você vai
precisar criar uma conta, tá? Você não
vai ter acesso a essa tela. Eu já tô
logado, você vai precisar logar, mas eu
vou deslogar para mostrar para vocês
como é o processo do zero, tá? Então
aqui você vai continuar com Hub ou
Google. Vou continuar com Google. Conta
aqui já tá conectada.
Show de bola. Eh, podemos vir aqui até o
playground e aqui ele mostra pra gente
como que a gente pode consumir esses
esses modelos, né? Aqui a gente tá
utilizando, tá vendo em Python, poderia
utilizar JavaScript
ou fazer uma chamada do tipo CUR, mas
aqui a gente vai utilizar Python. Ah, é
sempre bom dar uma olhada na
documentação, nos modelos que estão
disponíveis paraa chamada via Grock.
Fato interessante, pessoal, é que você
tem um limite para chamadas gratuitas,
tá? Então, verifiquem qual é esse
limite, mas eu acho que para efeito de
estudo, o que eles permitem que a gente
use é mais do que suficiente, tá,
pessoal? Bora lá. Eh, vamos criar uma
IPI key, uma IPI key para que nós
possamos fazer ah chamadas aos LLMs
utilizando o serviço da Grock, tá? Vou
criar aqui uma uma API aqui. AP aqui,
aula 01.
tá criando.
Perfeito. Vou copiar esse valor. Vamos
voltar pro nosso Júpiter Notebook.
E aqui eu vou copiar o valor da
variável, tá, pessoal? Que é aquela AP
aqui que a gente acabou de criar.
Perfeito. Aqui no playground ele mostra
para você como que você poderia fazer o
cono desse desses modelos utilizando
o a utilizando o Grock, tá? Então aqui
tá muito bem exemplificado. É
basicamente isso que a gente tem aqui
nesse nosso primeiro exemplo, tá
pessoal? Então aqui apresentei a P ke e
aqui pessoal vou criar uma variável de
ambiente chamada Grock Kpi key. Então
beleza. Pô professor de onde que você
tirou a a de onde que você como que você
sabe que a gente precisa criar a
variável com esse nome para poder
utilizar os LLMs via Grock? Isso aqui tá
na documentação, tá pessoal? Ponto muito
importante, leiam as documentações, tá
pessoal? Isso aqui é muito relevante,
mas por tentativa e erro vocês também
conseguiriam, porque a os logs aqui da
chamada iria indicar para vocês precisam
criar essa variável, tá bom? Show de
bola, pessoal. Ah, bora, bora tentar
executar aqui. Já eu já criei aqui a
minha P aqui. Primeiro eu vou tentar
executar e depois a gente vê quais são
os problemas que a gente vai encontrar.
Antes de tudo, eu preciso instalar o
Jupiter Notebook Kernel. Aqui é a
primeira vez que eu executo o
Júpiterente.
Tive um erro. Por quê? Porque eu não
instalei o Grock e eu fiz isso de
propósito. Então bora lá, pessoal. Vou
fazer aqui o ping pistal menos que o
Grock. Então bora executar.
Maravilha. instalado. Eu vou fechar isso
aqui, vou deletar e vou tentar executar
novamente, tá, pessoal?
Olha só, a minha pergunta, a a o meu
prompt foi: "Olá, tudo bem? Me fale uma
curiosidade sobre a linguagem
portuguesa." Ele me retornou. Uma
curiosidade bem legal sobre o português
é que ele possui, na verdade, a palavra
mais longa que seria
anticonstitucionalissimamente.
Difícil uma palavra difícil. Enfim,
pessoal, nós conseguimos fazer aqui a
nossa primeira chamada de Lilm para
almas pra gente. Então, foi
relativamente fácil, foi relativamente
simples e foi gratuito. Olha que legal.
Então, você não precisa desembolsar ou
gastar dinheiro e para fazer o consumo
de LLMs. E aqui nós temos o suficiente
para desenvolver todo o nosso curso, tá?
Vamos apresentar outras possibilidades
para que você não fique preso somente ao
Grock, mas aqui você já conseguiu fazer
a sua primeira chamada de LLM. Então,
tudo bem, pessoal? Essa esse esse código
que tá sendo apresentado aqui é aquilo
que tá apresentado aqui na documentação
do do do portal do Grock, tá? Então tudo
isso que eu tô utilizando, eu eu
simplesmente copiei e colei daqui, tá?
Perfeito. Aqui, pessoal, tem algumas
coisas que são importantes de
verificarmos.
Foi necessário especificar um modelo que
é basicamente o nosso LLM. Assim, a
documentação e como essas essas
bibliotecas são organizadas é uma
maravilha. Se você deixar o seu mouse
aqui, aqui dentro do VS Code, né, você
vai ter acesso à lista de modelos que
você pode utilizar. E o modelo é
basicamente o LLM. Aqui no caso é o GPT
OS, que é um modelo eh de pesos abertos
que foi disponibilizado pela Openi
recente, tá? a mensagem, né, ela
normalmente segue esse padrão. Eh, no
caso aqui, como somos nós que estamos
enviando uma mensagem, né, o usuário,
então a a RLE é user e você precisa
especificar o content. É basicamente o
seu prompt, é o que você tá enviando ao
LLM como requisição. Temperatura, eu vou
explicar isso um pouco mais à frente. E
o max completions tokens também vou
explicar um pouco mais à frente. Enfim,
pessoal, no geral fizemos aqui a nossa
primeira chamada de LLM e já podemos
partir pra nossa próxima etapa, tá bom?
M.