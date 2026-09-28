# Do you know what OVERFITTING is? Ways to react and try to fix it?

- **URL:** https://www.youtube.com/watch?v=5Sa51nO-1PQ
- **ID:** 5Sa51nO-1PQ

## Transcrição

Olá pessoal. Aqui estou eu novamente. Já
Eu falei sobre regressão linear,
regressão logística, árvores de
decisão e, quase no final da parte
quatro do vídeo sobre árvores
decisão, mencionei o tópico de
sobreajuste e vários outros surgiram
questões. Então, fiz um acordo com Thiago.
Grave outro vídeo para fazer um resumo e
Explique um pouco o que isso significa.
Certo, então o que significa sobreajuste? Ele
O sobreajuste ocorre quando você cria um
um modelo tão específico, mas tão
específico para esse conjunto de dados,
que perde a capacidade de generalizar
para um momento posterior, para um
uma situação ligeiramente diferente daquela
Você analisou. E isso não é nada atraente.
quando estou interessado em criar um
modelo preditivo. Só se torna
atraente quando quero entender um
evento e não pretendo prever o quê
acontecerá no futuro. Eu sempre digo
Isso aconteceu em sala de aula. Um bom exemplo para
Procurar por peças com sobreajuste é como o Titanic.
. Porque? Todos os sites
Eles apresentam o Titanic como se fosse para
Faça uma previsão. Para mim, não é isso.
Não faz sentido nenhum. Diga-me, em
Quando teremos um navio com o
a mesma tecnologia do Titanic que
Eu bati em um iceberg, então eu
Aplique um modelo preditivo e veja
Quem morrerá e quem sobreviverá?
Isso não vai acontecer. E daí
O que eu quero fazer com os dados do Titanic?
Quero realizar um sobreajuste, ou
sobreajuste, para entender o quê
Isso aconteceu nesse contexto. Eu posso usar
regressão logística e interpretar o
"razões de chances", como mencionei
anteriormente, e eu posso fazer uma árvore
decisão de compreender as razões
e o que levou à morte do
Pessoas, quais eram os
características de indivíduos que
Eles morreram. Muito bom. Mas não é só isso.
O que normalmente procuro no meu dia a dia
dia, no meu ambiente de trabalho;
Normalmente tento prever algo, tento
criar e aprender com uma população que
já vivenciei o evento que me
Tenho interesse, mas quero aplicar isso a
uma população diferente. Então não
Tenho interesse em realizar um sobreajuste. ?
Porque? Porque quero generalizar e
Quero ter uma precisão que seja
satisfatório nessa nova base de
dados. É por isso que eu deveria me preocupar com
esse. No momento estou preocupado
não causar sobreajuste, isto é, não
Para criar um algoritmo sobreajustado,
Então, o que eu faço? É aí que isso entra em jogo.
conceito de treinamento, validação
e teste. Esses são termos muito comuns em
o mercado, mas eu sempre gosto disso
perguntar com quem estou falando para
Para entender o que significa treinamento,
validação e testes para essa pessoa,
porque existem pessoas que mudam a forma como elas
Diga isso e não haverá problema algum. Então
Então vou explicar como
Eu entendo como isso funciona e
Qual é a sua aplicação? Olhando para o
termo de árvore de decisão, se
Lembra do vídeo anterior? E aqui
Temos a árvore, e acontece o seguinte:
Falamos de fraude e de coisas que não são fraude. E nós vimos
como construir esta árvore
decisão, como eu trabalho com ele para
que é generalizável e não
sobreajuste. Então, o que é o
ideia? Eu tenho esse banco de dados.
Eles relembram no vídeo anterior que
Vamos desenhar no quadro? Esta base de
Vamos dividir os dados em três partes.
Treinamento, validação e testes.
O que significa treinamento?
É no treinamento que vou criar o
árvore de decisão de acordo com meu
critérios de interrupção. Bem, aí está.
que fazer um curso para entender um
Um pouco mais sobre a árvore de decisão,
Mas seria isto aqui. Vou criar
Esta árvore de decisão, que é o quê
Eu a chamo de árvore máxima. Então, eu sou
criando minha maior árvore possível, de acordo com
as regras que estabeleci, que são as
parâmetros da árvore de decisão. E
Então, o que vou fazer com o
validação? Ok, vou pegar a base.
Para validação, você concorda?
comigo, pois possui a variável
resposta porque veio da base
original que eu dividi em três partes?
Então eu vou pegar esta base, a
Aplicarei as regras que criei aqui.
na sala de treinamento e eu verificarei
Qual é o ajuste, ou seja, o que é
a qualidade dessa apresentação. E
Então, o que vou fazer? Você vê
Aqui nesta árvore temos 1, 2,
3, 4, 5 folhas? Este aqui é um
árvore, mas se olharmos atentamente, veremos que
Muito criativo, é aí que eu digo isso.
Precisamos pensar fora da caixa;
Isto é uma árvore, mas não é apenas uma árvore.
árvore. Podem ser várias árvores.
Então imagine que eu remova isso aqui.
última divisão de renda. Que
ocorrido? Uma árvore permaneceu com quatro
folhas. No momento em que eu removi aquilo
divisão de renda, de onde você é?
Concordo que se trata de uma subárvore.
da árvore original? Então, qual deles?
É essa a ideia? Eu criei a árvore máxima em
a parte do treinamento e eu estou
pegando todas as subárvores e
testando seu desempenho na base de
validação. E então verei quem o tinha.
o melhor desempenho na base de
validação para escolhê-lo como meu
modelo final. Então eu posso construir
Esta árvore é máxima em uma base, mas
Esta não é necessariamente a que vai acabar indo
produção, isto é, aquela que medirá
o futuro. Porque? Porque pode ser
Muito específico para isso.
conjunto de dados. E é aí que o
validação para fazer o que chamamos de
poda. Se, ao analisá-lo na base de
Validação: Verifico que os quatro
folhas funcionam melhor do que cinco,
Então eu podo, eu removo esta última parte.
de uma renda e deixe a outra como está.
Possui quatro folhas. E daí
Aconteceu aqui? Eu criei a árvore de
decisão, a árvore máxima na base
treinamento. Eu a podei na base.
validação. E qual é o propósito do
Outra base? Como costumo brincar com meus alunos,
É inútil, só serve para...
Se o seu chefe lhe perguntar qual é o
erro, aplique o modelo escolhido no
Valide o teste e meça sua eficácia.
precisão. Ah, Adriana, mas
Então, como escolho o melhor modelo em
Validação? Pronto, aí está.
Para entender o negócio e saber para quê.
Você vai usar esse modelo, que é o
O próximo vídeo curto que vou gravar. Então
Aguarde um pouco, nós vamos
Discutir isso. Mas neste
Neste momento preciso de uma medição que
Diga-me qual é o meu melhor modelo. E assim
Depende do motivo e da razão pela qual você está lá.
fazendo esse modelo. Então a ideia
de treinamento, validação e testes
O problema é que não cria supermodelos.
específicos, mas modelos que são
generalizável. Essa é uma maneira de
trabalhar. A ferramenta SAS, por
Por exemplo, funciona dessa maneira. Mas
Existem outras formas, quais são elas? Há
Muitas pessoas que usam baixa validação
esse mesmo conceito e continua testando
parâmetros diferentes, mudanças nas coisas
lá para ver o que poderia acontecer, para
Vamos ver se a qualidade dessa árvore melhora.
É o mesmo conceito que acabei de dizer.
dizer. Portanto, tudo é muito semelhante.
Apenas algumas nuances mudam. Agora, é
O que é muito importante é o teste.
Pode fazer parte dessa base.
original que foi dividido em três, ou
Pode ser de uma forma que chamamos de "
"fora de tempo", que está fora do tempo
estudar. Por que isso é interessante?
Usar esse conceito de "fora do tempo"? Ei
É como se eu estivesse aplicando isso em
vida real. Então, se, por exemplo
Estou observando um evento no qual
Meu passado remonta a dezembro,
Deixe novembro e dezembro de fora da lista.
base e, a partir daí, retrocedendo,
Você cria o treinamento e o
Na validação, você decide qual é o melhor modelo e
Então você considera novembro e dezembro como
teste para verificar o erro real que
o que aconteceria se você tivesse colocado isso
modelo na prática. Então, a ideia
O problema com o sobreajuste é que
Fui tão específico que acabei
dando errado. Portanto, é
É interessante que seja generalista e, em
No momento em que eu me tornar generalista,
Preciso de outra base para conseguir isso.
pesagem. É por isso que eles existem.
treinamento, validação e
prova. Espero que tenha gostado.
que foi útil e que ajudou
Mais um pouco. E é isso aí, pessoal.
Haverá também outro vídeo curto.
falando sobre para que servem.
modelos. Muito obrigado.