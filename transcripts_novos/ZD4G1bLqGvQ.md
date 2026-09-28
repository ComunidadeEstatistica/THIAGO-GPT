# Live Prof. Dr. Marcos Santos (IME/ITA) - AHP-TOPSIS-2N Method - Multicriteria Decision Support

- **URL:** https://www.youtube.com/watch?v=ZD4G1bLqGvQ
- **ID:** ZD4G1bLqGvQ

## Transcrição

Bem, já são quase 11h20.
Então vamos começar por aqui. É um
grande prazer
para te dar as boas-vindas de volta aqui no
Comunidade de estatística, certo?
Estamos aqui com esta linda
palco de volta, no IM, que é
ali em Urca. Para quem não sabe
Ou não é do Rio de Janeiro, tem um
Uma ótima motivação para estudar lá!
Não apenas por causa da instituição, que é
Excelente, uma instituição de
excelência, e tem essa visão
A praia da Urca é maravilhosa, não é?
É incrível. E esse método era
desenvolvido em parceria com o IM e
UFF, não é mesmo, professora?
Foi assim mesmo. Sim. Ótimo. Então,
Fique à vontade e prossiga. Obrigado.
Ok, bom dia a todos, certo?
Para quem ainda não me conhece, eu sou o
Professor Marcos Santos e, a pedido
Com o Professor Thiago, agendamos um
Série de cinco transmissões ao vivo. O primeiro
Eu consegui. Eu falei sobre a teoria.
sistemas gerais e o processo de
tomada de decisões, de uma forma mais
conceptual. A transmissão ao vivo já está no ar.
Disponível, certo? Esse
Tudo está lá no Stat Dados, aberto para
que todos possam ver.
Está lá no Stat Dados. E em um
Em segundo lugar, falei sobre o
pressupostos teóricos da decisão
multicritério, a dificuldade de modelagem
e estruturar um problema,
especialmente aqueles que têm
critérios conflitantes. Em outras palavras, um
problema em que tenho que escolher um
alternativa entre várias, e existem muitas.
critérios que devem ser observados, tais como
custo, tempo e qualidade. Então,
Naturalmente, se eu precisar que algo seja
Faça com alta qualidade e rapidez,
Provavelmente terei que assumir um
alto custo. A questão é a estruturação.
essa decisão. Até onde?
Aceito pagar mais para ser
atendido no tempo que preciso e
com a qualidade que o problema exige.
? Portanto, esses métodos de suporte para
As decisões multicritério são aquelas que
Eles nos ajudam a estruturar esse tipo de
problemas. E retomando nossa terceira
Professor Luiz Frederico fez uma transmissão ao vivo.
. que falou um pouco sobre o método
Sapevo M, certo?, que era um método, né?
que desenvolvemos juntos
no IM e lá na UF e no
CASNVE, certo?, no Centro de Análise
de Sistemas Navais. Uma modelagem
matemática que desenvolvemos juntos.
Ah, para facilitar o uso do
método, criamos uma plataforma chamada
Sapevo Web, certo? Você só precisa fazer login.
para www.s.com e ela operacionaliza o
Cálculos do método Sapevo M, certo? E
Então, hoje estamos no nosso quarto.
transmissão ao vivo onde falaremos sobre o
O método AHP-TOPSIS 2N, que também foi
desenvolvido em parceria, uh em
A associação da IM com a UF, certo?
Brilhante. Finalmente, nosso quinto
A sessão ao vivo será sobre o método THOR.
que foi proposto há 20 anos pelo
Professor Carlos Francisco Simões Gomes
que é professor lá no
Universidade Federal Fluminense. E agora
Estamos trabalhando em uma reforma.
do mesmo, fazendo a parte
Axiomático, certo?, a parte matemática.
mais robusto e também criando um
ferramenta, certo?, um algoritmo em
Python para facilitar seus cálculos, certo?
Não? Estou orientando um aluno de
Mestre, Professor Fabrício Maoni
Tenório, que é professor lá na
CEFET, ele é meu aluno de tese lá no
IM, que está trabalhando nisso
versão mais robusta do método
matemático e também está trabalhando
neste algoritmo em Python, e ele
Esta será a nossa quinta transmissão ao vivo, certo? E
E assim encerramos este ciclo.
Ele até ministrou o minicurso no
O evento do Thor, não foi?
Sim, sim. Eu vou, uh, no final
Também mencionarei no CIMAP que
Vamos fazer um minicurso sobre Sapevo e
um dos THOR.
Ah, isso é ótimo, não é? Ah, e eu estava
Falando com o Thiago, né? Ter
Outras duas, nas quais estamos envolvidos.
outros dois empregos, que é Miguel
Além disso, ele é meu aluno lá na
EU SOU. que ele também desenvolveu um
Código Python para usar o
Métodos PROMETHEE 1, 2 e 3. Thiago,
Acho que ele até frequentou as aulas.
lá.
Sim, sim. Ele fez um ótimo trabalho. Esse
incrível.
PROMETEU.
Ele já chegou, já entrou, e pronto.
Foi inovador, não foi?
Sim, é assim mesmo.
Brilhante. Método PROMETHEE 1, 2 e 3. E
Ele também está propondo um novo
método matemático, do qual já
Nós até já publicamos artigos,
que é o método PROMETHEE-Sapevo M1.
Então, se esse fosse o caso, se houvesse
demanda da comunidade e Thiago quer
, para esses cinco que já fizemos, eles
Adicionamos mais estes dois. Bem?
Claro, claro. Brilhante. O, as pessoas
Você definitivamente vai querer. Vai ser, vai ser
Ser bom demais.
E é aí que permanece.
A resposta tem sido muito boa, não é?
Certo, pessoal?
Certo, então hoje vamos conversar um pouco sobre isso.
do método, deixe-me ver aqui,
Deixe-me colocar aqui o "vamos conversar".
Um pouco do método AHP TOPS2N.
Deixe-me projetar aqui. Onde
É possível compartilhar algo? Aqui.
Lá embaixo é verde. Aqui o
compartilhar. Aqui. Você consegue ver ali?
Sim, é visível.
Sim.
Sim, é visível.
Vamos falar um pouco sobre o método AHP.
TOPS2N. Hum, vou dividir em duas partes.
momentos, sim? Vou falar sobre um
pouco da parte teórica e da parte
matemática do método e então eu irei
Vamos executar um exemplo para que você possa ver em
como é isso?
O resultado foi processado.
Brilhante.
Não sei se vai funcionar bem, como vai ser.
Pode ser isso mesmo, mas vamos ver. Vamos
avançar. Ok, vamos ver o que acontece.
Hum, o método AHP, ambos os métodos
O AHP, assim como o método TOPSIS, não são
Novos métodos já são métodos
consagrada há muitos anos em
Literatura, certo? O método AHP,
Eles são praticamente ambos da mesma região.
Os anos 80, né? O AHP tem
um artigo de 1980 de Thomas Saaty e
TOPSIS, se não me engano, é de
1981 ou 1982, algo assim. A grande jogada é
diga: "Ah, professor, mas então
O que há de novo nisso? Método AHP
TOPS2N. O que há de novo nisso é
Essa fusão, certo?
uma mistura desses dois métodos. Porque
o método TOPSIS para fazê-lo funcionar,
Preciso dizer quais são os pesos de
Os critérios para ele, certo? Sim, eu tenho.
Por exemplo, três, eu vou dizer: "Ah,
O custo representa 50%, a qualidade 30% e o prazo de entrega é
20%. Preciso fornecer essas informações agora.
pesos para os critérios quando eu executar
o método TOPSIS. O problema é que
Quem toma a decisão nem sempre tem certeza de
Esses pesos, né? Nem sempre tem
segurança total para obter estes
pesos, para introduzi-los no método
TOPSIS, de modo que o método TOPSIS
pode gerar o resultado. Então,
Utilizo o método AHP para gerar o
pesos por meio da balança
fundamental para Saaty. O método AHP
Gere os pesos e insira esses pesos.
dos critérios no TOPSIS e lá o
O TOPSIS gera a ordenação, certo?
E o que é esse 2N? Este 2N
Isso decorre do fato de usarmos dois.
diferentes padronizações para gerar
a ordem, em vez de apenas uma,
o TOPSIS normal. É um jeito
até mesmo para avaliar o quão robusto ele é.
nosso pedido, se é que realmente é
coerente ou não.
Quatro padrões diferentes.
E dentre quatro tipos, selecionamos dois,
uma que já é natural ao método
Topsis e outro. E então comparamos o
ordenando para ver se os resultados
Eles concordam. Então é de mão única.
até mesmo para validar se sua classificação
É realmente coerente ou não, porque se
a classificação não corresponde então
Precisamos analisar melhor o problema.
Brilhante. Então, a ideia é muito simples.
Utilize o método AHP para gerar os pesos.
Pegue esse peso e insira-o no Topsis e
calcular os resultados do Topsis com
duas normalizações.
Brilhante. Deve haver novidades em breve.
O Sapevo-Topsis 2N também, né?
Então, essa é a ideia. A ideia não é
Nada complicado. Parece difícil, não é?
É um caça-palavras e tudo mais, mas não é...
Nada complicado. Então vamos lá.
Vou dar apenas uma visão geral rápida aqui.
para que tenhamos uma ideia da parte
conceitual da questão. OK?
Bem, essa história começou com
Este artigo, como eu mencionei, certo?
Professor Carlos Francisco Simões
Gomes foi meu orientador de doutorado, meu
supervisor de pós-doutorado e continuamos
investigando em conjunto, a equipe do
UFF com a equipe do Instituto
Engenharia Militar. Então, ele
Ele trabalhou nisso com seus alunos.
artigo, não me lembro agora se é de
88 ou de 2018, aí está. Ele propôs
Este modelo com seu aluno de doutorado,
Alexandre Pinheiro, em 2018. E saiu.
Este artigo, certo? Isto é um
Revista, é uma revista de peso, não é?
Uma revista bastante interessante. E
Então foi isso, a implementação de
Um novo método híbrido, não é?
AHP-Topsis 2N. E ele aplicou isso ali em um
problema do tempo,
Foi em 2018, bem recentemente,
2018. Portanto, é um método recente.
Não? Estamos falando sobre o que está em
o estado da arte em termos de
Modelagem multicritério.
Brilhante.
E essa foi a proposta quando começamos.
Este curso, certo? Foi realmente
Trazer novos métodos, certo? Novo e
Fácil de usar. Ah, porque os outros
métodos, AHP, Electre, Promethee, o
O próprio Topsis não utiliza métodos novos.
Esses são métodos já estabelecidos; já existem
Existe muita literatura sobre o assunto; há
Tem muitos vídeos no YouTube, então
Isso seria trazer de volta mais do mesmo, não é?
? Então, a proposta, quando eu falei...
Com Thiago, o objetivo era trazer a comunidade
algo realmente novo, algo que é
realmente na fronteira de
conhecimento sobre isso
Modelagem, certo?
Exclusivo aqui. Brilhante.
Portanto, esse método é muito recente.
Ele tem 2 anos de idade. Bem, e é aí que eu digo,
Não? Porque sua parte matemática não é
Então, não é que seja difícil, mas não
Todos estão familiarizados com
Esta parte da álgebra linear, espaços
vetores, etc. Então, eu tenho um
aluno da IM que é Olas, que é
Engenheiro de produção. Ele pegou
Este AHP-TOPSIS-2N assumiu a parte
axiomático e modelei tudo em Python
, Não? Ele criou um executável que eu vou usar.
mostrar, para que possamos executar o
método sem ter que fazê-lo
manualmente ou frequentemente no Excel e
Utilize o método. Então,
então isso tornou as coisas muito mais fáceis para quem
Quero usá-lo e posso colocá-lo
A ferramenta está disponível, certo? Em
fim. Tudo bem.
Brilhante.
Então,
Ele está no laboratório, certo? Olá.
OK,
Ele está no laboratório. Depois
Enviamos o link.
Brilhante.
OK. Vou falar. Então, tipo
Eu estava dizendo que a primeira etapa do método é
utilize o método AHP para gerar
os pesos dos critérios de forma que
então esses pesos são incorporados em
O método TOPSIS, certo? Então, o
O método AHP foi criado por Thomas Saaty.
Quem é esse professor que está aqui?
que infelizmente nos deixou recentemente
. Ele ia dar uma palestra no
Encontro Nacional de Engenharia
A produção, se não me engano, ocorreu em 2017.
.
Hum.
Ou 2018, já não me lembro. Eu ia dar
um bate-papo, mas no ano em que eu ia para
Ao chegar, ele morreu.
Oh.
Sim. Mas ele nos deixou há um ou dois anos.
anos. Então, o professor Saaty era
quem criou o método AHP, que sem
Sem dúvida, é o método mais eficaz.
usado pelo mundo. Digo isso sem
Medo de cometer um erro, certo? Sem dúvida, o
O Processo de Hierarquia Analítica é o
método mais amplamente utilizado no mundo,
tanto no meio acadêmico quanto no mundo
corporativo. Se houver demanda posteriormente,
Se as pessoas quiserem mais tarde, eu posso dar.
um curso ou aula apenas sobre o
Método AHP, certo?
Maravilhoso.
E como é o método mais utilizado,
naturalmente as pessoas acabam
Você está se aprofundando nisso, não é? Sendo o
O mais usado, naturalmente, é
É também a mais criticada, não é?
Exatamente o que as pessoas mais usam e
Então elas terminam, certo? Ah, esse método
Isso não resolve meu problema, resolve?
Ah, esse método está incompleto. Aquilo é
Uma discussão sem fim, não é? Porque
Nenhum método resolve isso, certo?
Nenhum método é completamente perfeito.
Nós dissemos isso, não dissemos? um modelo. Em
Na nossa primeira aula, falamos sobre isso.
O modelo é uma simplificação do
A realidade, não é?
Exatamente.
Portanto, por melhor que seja o modelo
Em matemática, sempre haverá uma lacuna.
Não? Sempre haverá uma resposta que
não poderei dar, principalmente
Ao lidar com sistemas complexos,
VERDADEIRO? É evidente que se eu tomar um
Há um pequeno problema aí, simples assim.
Eu calculo uma média aritmética, é
resolvido. Agora, vou tentar.
estruturando a complexidade, o
subjetividade do pensamento humano,
É claro que é uma tarefa muito maior, né?
Abstrato, não é? Muito mais complexo.
Então, esse era o Professor Saaty.
que em 1970 criou o método AHP e o
O método ganhou força a partir do
Os anos 80, né?
Brilhante.
Estas são as equações. Esta pequena tábua
Inclui um resumo do método AHP, certo?
Podemos ver que não é um método, né?
complicado. Na verdade, dos métodos
Dentre as existentes, talvez a AHP seja a mais
Fácil, né? Não, talvez o
Os números ordinais são os mais fáceis, certo?
Os métodos de Borda, Condorcet e
Os Copeland são os mais simples, não são?
Mas eles também são do século XVII.
Portanto, estão fora da nossa jurisdição.
Chegue aqui. Mas quanto aos métodos?
talvez consagrado na literatura
O método AHP é o mais simples dos
eles, certo? E olhando aqui o
Na modelagem matemática, vemos que
Na verdade, não tem nada.
Algo fora do comum, não é? Ah, a primeira.
Passo a passo, aqui está um guia passo a passo.
Essa prancheta, né? Então, primeiro
formular a matriz de decisão do
que mencionei em nossa segunda
transmissão, certo?
Exato.
Eu expliquei como criamos a matriz de
decisão, certo? Então, aqui está.
a formação das matrizes de
decisão. Hum, eu calculo isso mais tarde.
autovetor, certo? consiste em
ordenar as prioridades ou hierarquia de
as características estudadas.
Portanto, podemos ver aqui que é um
média geométrica, certo? É o
produtor de w i j aumentou para 1 sobre n.
Então, você quer dizer,
É a enésima raiz do produto, não é?
? Hum, vou normalizá-los mais tarde.
autovetores. Aqui W1 dividido por
soma de W1, certo? Então, pegue um
elemento, se não me engano, eu acho
Nós também falamos sobre normalização, certo?
Não fizemos isso? Acho que já mencionamos isso.
na transmissão ao vivo.
Sim, estamos falando de normalização.
Preciso normalizar para poder comparar.
entre critérios.
Conversamos, sim, conversamos, sim, conversamos.
Então, é por isso que eu preciso
normalizar.
Claro. Claro que sim.
Então, calculo o lambda máximo.
é isso aí
Foi Frederico quem fez isso.
Ele mencionou isso, não mencionou? na Sab
aquilo é. E então este índice de
A consistência mede se a opinião de que o
A decisão tomada é consistente, se for o caso.
consistente. Então, se eu disser que A
é melhor que B e B é melhor que C.
então tem que haver um
transitividade aí, certo? Se A for melhor
Se B for melhor que C, então A é
Melhor que C, né? Acontece que
visto que você tem muitas alternativas e
Com muitos critérios, quem toma a decisão fica perdido.
Ele diz que A é melhor que B, B é
melhor que C, C é melhor que K, K é
melhor que P, P é melhor que Z. Portanto,
Em certo momento, ele diz que P é melhor.
A. Então alguém diz: "Opa, espera aí."
Espere um minuto, tem algo que está
Ruim, porque A era melhor que B, e B era melhor.
Esse C, C melhor... como é que agora
"Você está dizendo que P é melhor que A?" Então,
Esse índice de consistência, certo?
E qual é o motivo da consistência, hein?
São utilizadas para avaliar se a opinião de
tomador de decisões, se essa comparação for
consistente ou não. Então, o método
O AHP pode ser resumido de forma muito simples.
Simples, muito educativo, neste
Prancha pequena, não é?
Brilhante. Certo, então, esta é a escala.
A grande sacada de Saaty foi criar aquilo,
VERDADEIRO? Esta é a escala que ele
acreditar. Ele criou uma escala de 1 a eh
Para comparar, hum, esta escala.
Usamos ambos para comparar o
critérios para comparar os
alternativas dentro de cada critério,
Semelhante ao que fizemos em Sapevo, certo?
Não?
Sim. Na Sapevo, estabelecemos um
comparação pareada entre os
critérios para obtenção do peso do
critérios.
Aquilo é.
Criamos um para cada critério.
comparação das alternativas.
Aquilo é.
O método AHP funciona exatamente assim:
Da mesma forma, certo? Exceto que
Para usar este método, que é o
Só vou usar AHP-TOPSIS-2N.
Digamos que estamos na metade do caminho.
O método AHP serve apenas para gerar
o peso dos critérios. Para avaliar
Depois das alternativas, nós...
Digite Topsis. Bom,
então esta escala fundamental de
Saaty, eu tenho de um para... vou comparar
dois critérios. Se for um, significa
que os critérios sejam igualmente
importante. Se alguém em relação a
Outro atribuiu-lhe três, no caso de
tomador de decisões, certo?, o grupo de tomadores de decisões.
Se forem três, significa que um é um
pouco mais importante que o outro. Se for
Cinco significa que é muito mais
importante. Sete, bem mais
importante e nove extremamente mais
importante. Claro, antes disso
Alguém disse, né? Duvido disso.
Isso gera uma discussão interminável, não é?
Ah, qual é a diferença entre
muito mais importante e consideravelmente mais
Importante, não é? Como podemos quantificar isso?
que? No fim. Existem inúmeras
artigos internacionais que levantam
Essa questão, mas não é nossa, não.
Nosso objetivo agora é fazer isso.
discussão especificamente sobre o
Escala fundamental de Saaty. A ideia é
De forma bem simples, trata-se de atribuir importância.
Relativo de um a nove. É isso, não é?
Então eu vou chegar com a pessoa.
quem decide lá na empresa de consultoria e
Vou dizer a ele: "Olha, nós temos custos aqui e
Qualidade, qual é o custo mais
"É importante que a qualidade seja importante para você." Ele
Ele vai atribuir uma nota e vai dizer: "O
O custo para mim é sete, o mais
importante", ele tem um alcance de 1 a
9 para me dizer. Essa é a ideia, certo?
Tudo bem? Se estiver escrito três, significa
que o custo é apenas um pouco maior
mais importante que a qualidade. Se alguém disser,
Isso significa que o custo é muito
tão importante quanto a qualidade. É só isso?
Não? Hum, muito, muito objetivo.
Certo, então, uh, vamos mostrar isso.
em nossa segunda transmissão ao vivo
, Não? A matriz de decisão, eu tenho
Lá, tenho alternativas com
nos critérios e depois preencha aqui com
Esses são os valores que eu tenho, certo?
Obtenho nossa matriz de decisão.
Ah, o Júnior está perguntando aqui, né?
No AHP, as opiniões são consideradas.
testes individuais, como no Sapevo-M,
Opiniões dos responsáveis ​​pela tomada de decisão. Oh,
Cara, é isso aí, é isso aí, é isso aí
Essa pergunta causou muita polêmica.
Porque observe atentamente, hein, para usar o
AHP, ao usar a escala aqui
fundamental para Saaty, ou eu vou ter
Apenas um responsável pela tomada de decisão alocará esses recursos.
valores, ou se eu tiver um grupo de
Os tomadores de decisão precisam ter
Chegaram a um consenso.
E eles vão acabar brigando. É verdade,
Eles precisam discutir as coisas entre si, não é?
eles. Ah, sim, eu tenho uma reunião.
diretiva composta por cinco
diretores. Eles precisam chegar a
um acordo sobre, oh, quanto o
O custo é mais importante que a qualidade.
. Eles precisam chegar a um consenso entre
Eles finalmente disseram, bem,
Chegamos a um consenso e acreditamos que seja isso.
três. É um pouco mais importante.
custo em relação à qualidade.
Então, para você usar o AHP
Assim, certo? Com a escala
O princípio fundamental de Saaty, hein, nós devemos
presumir que era apenas uma pessoa ou
Se houvesse várias pessoas,
que já havia um consenso entre eles.
Brilhante.
Sapevo M. Ese,
A Sapevo já está inovando nessa área, certo?
Ele já está inovando nessa área, por exemplo.
Já considera todas as possibilidades de
decisão dos responsáveis ​​pela tomada de decisão.
O Sapevo não pressupõe que
Houve, necessariamente, um consenso.
Todos têm o direito de manter sua opinião, se
Ele quer, no final, compilar o
É a opinião de cada um, certo? O Sapevo
O original de 1997 era como o método.
AHP, certo?
Sim. Ao atribuir lá
importância relativa, né? Eu já
pressupõe-se que já se tenha chegado a um consenso.
Aconteceu, não aconteceu? Mas o Sapevo M, que
É aquele sobre "Tomadores de Decisão Múltiplos", certo?
Sapevo M resolveu o problema, não é? Que o
As pessoas não precisam brigar umas com as outras.
para poder
Incrível, não é? Hum, então não.
Não sei se respondi à sua pergunta. Ele
Ele disse: "Ótimo, obrigado pelo
"Explicação." Entendido. Entendido.
Certo, então temos aqui o
matriz de decisão e veremos aqui
Um exemplo, um exemplo simples,
Não? Muito educativo. Então eu coloquei o
do celular para evitar o exemplo de
carro, certo? Que sempre damos o
Exemplo de carro. Então, para não...
para não ficarmos sobrecarregados com a questão do carro,
Vou dar um exemplo agora do
Escolher um celular para comprar.
Então, vamos supor que eu queira escolher
um smartphone para comprar,
Não?
Hum.
Certo, e vou listar os critérios ali.
Mais uma vez, certo? Para aqueles que não
Eles viram as primeiras transmissões em
vivo,
Apenas um minuto. Mas há um pequeno
Interferência, não sei de onde vem.
Deixe-me ver aqui. Qual é a questão? Um ruído,
um som.
Sim, há um pouco de ruído. Não sei, não sei sobre
De onde vem isso?
Deixe-me ver aqui. Aguarde um pouco,
Aguarde um pouco.
Ah, deve ser alguma coisa. Ah,
Agora está melhor. Brilhante.
Melhorou.
Brilhante. Brilhante. Ok, obrigado.
Certo, então, vamos supor, vamos supor
Quero comprar um telefone
inteligente.
Então, mais uma vez, eu já expliquei.
Isso acontecerá na segunda transmissão ao vivo.
Mas vou fazer apenas um breve resumo.
Aqui, está tudo bem?
Claro, já que sou eu quem vai...
Para decidir, as alternativas e o
Os critérios dependem de mim, certo? Isto
O que é importante para mim pode não ser
importante para Thiago. O que é
importante para uma empresa pode não ser
Ser importante para alguém. E é mesmo.
É exatamente daí que vem.
A riqueza desses métodos, não é mesmo?
Por exemplo, pode ser que...
Para a minha empresa, o que importa é o
custo, projeto e velocidade. Esse
para as operações da minha empresa.
Pode ser que para o funcionamento de
Outra empresa não faz o projeto.
Se a diferença for menor, então terá...
Outros critérios, certo?
Sim. Ok, então, isso já é...
uma captura de tela do algoritmo
O que fizemos em Python, está correto?
Certo, então deixe-me explicar.
rapidamente. Então, estruturando
O problema, suponhamos, é escolher o
smartphone, eu disse isso para
O custo é importante para mim, certo?
Aqui está a qualidade da câmera,
a capacidade de armazenamento de
Telefone e design, certo? Ah, e
então forme uma matriz aqui
quadrado, veja, 4x4. Espada
O que você está vendo é a escala.
fundamental para Saaty, certo? Esse
A partir daqui, ele está dando estes...
Anotações sobre essa escala aqui, veja.
Eu formo uma matriz quadrada n por n, ?
VERDADEIRO? E então observei o seguinte:
: que na diagonal principal do
Na matriz só existe o número um. Por
que? Porque estou comparando um
critérios consigo mesmo.
Sim,
Ele é obviamente tão importante quanto parece.
mesmo.
Pergunto ao tomador de decisões ou ao grupo de
tomadores de decisão: quão mais importante é
Qual o preço da câmera? Ele diz
quatro. De acordo com a escala
fundamental para Saaty. Tudo certo?
Quão mais importante é o custo que
armazenar? Cinco. E quanto?
Mais importante é o custo do que o
projeto? Sete. OK?
Bom.
Em seguida, observe se o custo com
A relação com a câmera é quatro, a
câmera em relação ao custo
Isso é 1/4, certo?
Ah, ele faz o contrário, não é?
Tem que ser o contrário.
A Sapevo faz coisas simétricas, certo?
É, o Sapevo faz o simétrico.
Exatamente. A Sapevo trabalha com
simétrico. Aqui ele
Ah, tudo bem, né?
Bom.
Hum, se o custo, se o custo tiver um
importância do cinco em relação a
o armazenamento, então o
O armazenamento em relação ao custo é de 1/5.
. E se o custo em relação ao projeto for
sete, então o projeto em relação ao
O custo é um sétimo, não é?
Entendido. Isso faz parte do
desenvolvimento axiomático, como
Você mencionou isso, não é? Na SABO, né?
Trabalhamos com modelos simétricos. Se um for 4
O outro é -4, certo? Se um for dois,
O outro é menos 2. Aqui trabalhamos
com o inverso em vez de trabalhar com
a simétrica, mas a ideia é mais ou menos a simétrica.
Exceto que é a mesma coisa, certo? Exato.
Então aqui, a câmera em relação ao
O espaço de armazenamento é três. Se a câmera
Em relação ao armazenamento, são três.
então o armazenamento em relação a
A câmera tem zoom de 1/3, certo? Então
Preenchemos esta matriz. Isto faz parte de
A primeira etapa do método AHP, certo?
Então, o que significa o
Método AHP? Aqui, pegue isto, vamos voltar.
Olhe aqui. Candidate-se aqui, veja, este W
que é essa média geométrica. Este W
Vem de "weight", ou seja, peso em inglês.
Não? Aplique esta média geométrica.
Aqui estão os pesos e o que ele gera.
Resultados, veja. Os pesos são: custo
0,59, câmera 0,23, armazenamento 0,11
, design 0,05, certo? Então, é isso.
O que a AHP fez foi primeiro aplicar
Esta escala em uma matriz quadrada n
por n, comparando os critérios por
pares e então aplicou esta fórmula
da média geométrica para gerar
esses pesos. Por que? Por que isso?
? Porque ao usar o TOPSIS, que veremos a seguir, veremos
Mais tarde, o responsável pela decisão não estava presente.
É seguro atribuir esses pesos. Então
Veja, isso é uma grande ajuda, não é?
para a pessoa. Isso apenas me diz o que é.
O mais importante para ele: custo.
câmera, design, etc. E o mesmo
O método calcula os pesos. Ele não tem
o que, hum, não precisa, digamos,
Adivinhe esses pesos. Sim.
Além disso, o método AHP me fornece
lambda máximo, o índice de
consistência e a razão para
consistência.
Hum. Brilhante. E também podemos ver que
Em termos de pesos, o custo foi na verdade o
que receberam as pontuações mais altas
Eles são altos, não são? Mesmo depois disso
Cálculos malucos, não é? Ele continuou
reproduzir o quê
ex-
Era o que parecia, não é? Vamos colocar desta forma. E
Bem, essa é a razão para a consistência, que
Na verdade, é esta fórmula aqui.
É uma sequência, não é? Primeiro eu calculo
Esta equação 4, que é lambda
máximo. Então eu tenho que calcular o
índice de consistência para posterior
Calcule o índice de consistência.
Mas o que me interessa no final das contas
Cape é a razão da consistência, que
Tem que ser menos de 10%, certo?
Então, ele calcula tudo aqui e em mim.
indicou que a razão para a consistência
São 7%. Isso significa que isto
A opinião aqui, uh, é OK, é
consistente, é coerente.
Brilhante.
Ele já calculou isso.
Se eu não tivesse feito isso, teria sido feito.
novo. Como funciona?
Se não estiver, precisa ser preenchido.
Força novamente.
Exatamente. O...
matriz de concordância. Ah, nós a chamamos de...
Matriz de ponderação, certo? Ter
o que fazer do zero a matriz de
ponderações, usando a escala
fundamental para Saaty e para alcançar o
cálculo de uma nova proporção de
consistência até que dê menos de 10%
.
Brilhante.
Então, você vê que o método AHP é um
Um método de que gosto muito, embora
Algumas pessoas falam mal do método AHP, um
Eu gosto, sabe?
Brilhante.
Pense nisso.
É interessante também. Isso é
Isso também é novidade para mim. Aquela, aquela não
Você mencionou isso em
Não. Sim, estou ciente de que o
O método AHP tem suas limitações.
Mas todo método tem suas desvantagens.
limitações, certo? Se você for usar
estatísticas, lá rboot, bootstrap,
Não? Verossimilhança, sei lá, blá blá blá
blá blá blá, tudo tem limitações, né?
Central, né?
A média, bem, nem sempre podemos usá-la.
A média, a média, certo? Super útil,
Mas tem problemas, não é? Sim claro.
Atravesse a rua. Em média, ele está vivo
Mas na realidade, ele é,
Ele vai atravessar a rua, certo? Em
A média está viva, passou direto pelo
metade, mas ele acabou morrendo.
Portanto, tudo tem suas limitações.
A questão é que você sabe o
métodos e em que circunstâncias
Você pode usar um método ou outro, certo?
Portanto, parece-me que o método AHP
É um ótimo método. Há muitos anos
Eu o utilizo.
brilhante.
Só que, como sempre digo,
Eu não me apego a métodos. Saber
Pessoas que utilizam exclusivamente o método AHP.
Eles dizem: "Não, eu não uso outro." Eu não, eu não
Eu faço isso. Eu uso esse método que
Acredito que seja o mais adequado para
Esse tipo de problema, né? Não, eu não.
Eu me apaixonei por um método.
Professor, como devo interpretar isso?
índice de consistência? E o motivo é
Entendi, né? Tem que ser menor
Com 10%, não está certo? O índice de
Interpreto consistência como significado. Como
Então?
O índice de consistência aqui,
Vamos voltar aqui e ver. O índice de
consistência vai acontecer, é assim que se chama.
O método, denominado grau de n-1 de
Liberdade, certo? Ele vai calcular
o lambda máximo. Ou seja, como você
Devo explicar? Eu teria que dar um
método, uma classe apenas sobre o
Método AHP.
Ah, ok, entendi. Não, está tudo bem.
São espaços vetoriais, certo?
Podemos agendar uma transmissão ao vivo.
E lá eu mostro passo a passo como é.
Calcule o lambda máximo. Ter
também um algoritmo em Python.
Zumbir.
Calcule passo a passo o lambda, o IC,
VERDADEIRO? Então,
Tudo bem. Caso contrário, eu teria que
Vou explicar para você começando pela equação quatro e
No fim, fomos nós, não é? Se não for eu
Eu me enganei, acho que foi o professor, que
Professor da UF que é responsável
do congresso internacional, como é?
Ela está ligando? Quem é Luciana? É
Forjado.
É Luciana Conforado. Acho que é isso.
Ela criou uma biblioteca em R para
Faça o AHP.
Ele fez isso em R. Ele fez isso em R. Sim, ele fez.
AHP em R.
Tudo bem. Então vou procurar...
Vamos ver se consigo encontrar.
Dê uma olhada, mas depois podemos
agendar uma transmissão ao vivo especificamente e
Lá eu explico
esse lambda máximo e não é difícil,
Só precisa de tempo, não é?
Brilhante.
Certo, e o motivo da consistência é...
que deve ser inferior a 10%. OK. É aqui que o
5%, isso significa essas opiniões
Eles são consistentes, certo? Está correto?
Certo, então eu preciso decidir.
E eu tenho esses dados, certo? São
Dados quantitativos, certo? Então
Vou colocar o iPhone ali; Custa 3000 reais.
. A câmera, digamos, eu configurei para 12.
megapixels, 64 GB de armazenamento.
E depois tem a questão do design, não tem jeito, né?
Certo? Como vou atribuir um valor?
quantitativo para design? E então
Utilizei uma escala Likert de cinco pontos.
pontos.
Então
Na sua opinião, numa escala de um a cinco, como
Este é o design do iPhone? Ah, cinco.
Ah, ok, agora entendi.
Objetivo, a opinião de uma pessoa.
Outra pessoa pode, duas. Eu entendo.
Hum, mas, então, tipo, você pode?
Trabalhar tanto com dados, né?
quantitativo, certo? Se você tiver aqui
o custo, a câmera, que são detalhes que
Temos dados quantitativos, certo?
QUALQUER
Que ótimo, você consegue trabalhar com os dois?
Não?
Você pode, você pode trabalhar com os dois, certo?
Não?
Brilhante. Aqui está um exemplo:
Samsung, câmera de 8 polegadas, US$ 800
megapixels, 32 GB de armazenamento,
O design do Note 4 e o preço de US$ 1500 da LG, certo? Ei,
Então você percebe que há uma troca.
Aqui, claro, não é?
O iPhone tem um bom design, não é?
Não?
Sim. Um espaço de armazenamento, mais ou menos.
Uma câmera, mais ou menos, e é muito cara.
Sim,
Ele provavelmente vai perder, né? Mas
O que eu disse, muita gente diz.
"Ah, mas professor, é óbvio que ele vai..."
perder. Não preciso usar nenhum.
método para chegar a essa conclusão."
Sim, mas este é um exemplo didático.
, Não?
Sim. Se você tivesse 30 alternativas e
critérios,
Como você vai se lembrar disso?
Este é apenas um exemplo, certo?
para que possamos praticar.
E abordando ambos os aspectos qualitativos.
Quanto ao aspecto quantitativo, você precisa
A padronização também deve ser feita, certo?
?, pendência
Você precisa fazer a normalização.
Maçãs com bananas, certo? Exatamente
.
OK.
Certo, então vamos lá.
lá. Então, o seguinte foi concluído aqui.
matriz de decisão. Nós concluímos aqui
a matriz de decisão com os dados de
As que você tem disponíveis, certo? E eis que surge o
normalização, o que você acabou de dizer,
Não? Por que? Porque, como
Eu comparo? Você viu o seguinte, que por dentro
Com base no critério de custo, posso saber que o
O iPhone é o pior porque é o mais
caro e o LG é o melhor porque é o
mais barato. Dentro dos critérios
câmera, posso ver que a LG é a
Qual é melhor, qual é o mais barato e qual é o melhor?
A Samsung é a pior. Dentro do
armazenamento, posso ver que o
A Samsung é a pior, e a LG é a...
melhorar. Dentro do design, consigo ver
que o iPhone é o melhor e o LG é o
pior. Em outras palavras, eu posso fazer um.
comparação intracriterial. Dentro de
Posso comparar as coisas de acordo com cada critério.
mas não consigo comparar critérios
Diferentes, não são? Não sei dizer onde
A Samsung é melhor em termos de custo ou...?
armazenar? Onde você tem um
Melhor desempenho por US$ 800 ou 32 GB?
Não posso saber porque são critérios.
VERDADEIRO? Hum, as unidades são
diferente. Então, é por isso que eu tenho que
normalizar a matriz para fazer
uma comparação, para estabelecer uma
Comparação entre critérios. E também
Para poder estabelecer uma comparação,
Consegui criar uma função de agregação.
de todos eles. No final, eu tenho que
encontrar uma maneira de adicionar o
Desempenho do iPhone em cada critério
. Como vou fazer essa soma? Custo: 3.000
Câmera real de 12 megapixels,
Armazenamento de 64 GB, design 5.
Como é que eu vou somar isso, né? Ei,
não necessariamente acrescentando ao que eu
Quer dizer, mas uma função de
Agregação, certo? uma função de
aditividade.
Sim,
compile isto. Então, para poder
Para compilar, preciso normalizar tudo, certo?
Não? Sim. E
Uma questão é que na literatura
Esses são os quatro procedimentos de
Padronização, certo? Isso está lá também.
no livro do Professor Simões que
Eu mencionei que ele trabalha conosco, ele é
professor lá na UF, ele era meu
orientador de tese de doutorado. Ei,
Então, esses são os quatro.
padronizações que aparecem com mais frequência em
Literatura, certo?
Brilhante.
A padronização do método. Então
Vai voltar, né? A questão é
Quero aplicar o método TOPSIS e
O responsável pela decisão não tem certeza sobre o
obtendo os pesos, então
Ele utiliza o método AHP para gerar o
O peso serve para entrar no TOPSIS, certo? Bom
? No método TOPSIS, se você
Eles analisam o documento que ele divulgou.
O método TOPSIS, se não me engano, é
A partir de 1981, a padronização que utiliza
No método TOPSIS, é este aqui, o número 4, certo? Esse
padronização a partir daqui, A4, que é o
PARA
dividido pela soma de A vezes o
raiz, certo? é elevado à metade
Aqui, sim
É quadrado, não é? A raiz quadrada
da soma dos quadrados, certo?
Sim.
Então, o que fizemos?
Temos outra normalização, esta segunda.
Portanto, essa normalização já é a
Orgânico, já é o natural da TOPSIS.
que seu criador usou. VERDADEIRO? Nós pegamos
outra normalização que é igual a
da SAPEVO,
Ei
que é Aij menos o mínimo dividido
para o máximo,
máximo menos
a fim de gerar valores diferentes
de ordenação, não, valores diferentes
para cada alternativa, mas para ver se
A classificação permaneceu a mesma. Isso é o
questão, porque valores diferentes
Para cada alternativa, é claro que eles darão
porque usei uma normalização
diferentes, os valores de cada um
A alternativa vai mudar. A pergunta
É que a posição no ranking não é
Pode mudar.
Entendido. Se a classificação mudar
Em relação ao outro ponto, é porque algo não está certo.
Ok, preciso estruturar isso melhor.
O problema, entende? Entendido.
É o que chamamos de parte 2N do
método. É a utilização destes
duas normalizações para poder comparar
A ordem, comparando a classificação, certo?
Brilhante.
Essa era também a novidade.
do método. As duas novas funcionalidades são as
Método AHP para geração dos pesos.
Então, o resultado já vem incluído?
A comparação, certo?
Está chegando. Ah,
Então, a grande questão é esta:
O método AHP TOPSIS 2N é o método AHP.
usado para obter pesos e
as duas normalizações para ver se a
O resultado está de acordo com a classificação.
Não? Certo, então aqui vem o
Primeiro a padronização, certo? O
Essa é a primeira normalização.
normalização orgânica que mencionei
do método TOPSIS, que é este de
aqui. É um elemento A e J dividido
pela raiz quadrada da soma dos
quadrados. Então irá gerar isto
normalização aqui. E daí
Você vai beber? Se voltarmos atrás, levará...
os 3000, divididos pela raiz
quadrado de 3000² + 1800² + 1500²,
VERDADEIRO? E aqui está.
Normalização, veja.
O de baixo é
dividido pela raiz quadrada de
3000² + 1800² + 1500². Tudo certo?
Como resultado, este 0,78.
Excelente.
A mesma coisa acontece aqui. Aqui é 0,47,
0,47 será 1800 dividido por
raiz quadrada
de 3000² + 1800² + 1500². Todos
OK? Sim? E isso dará 0,47. E assim
sucessivamente. É assim que todo mundo é por aqui. Agora
Posso comparar as alternativas dentro
de cada critério, certo? Mas também
Posso comparar entre critérios, certo?
Sim.
Posso ver que o Samsung aqui custa
É melhor do que guardar em um depósito, não é?
Sim.
Seu armazenamento tem um bom desempenho,
Tem um desempenho pior. Espere, eu acho
Isso mudou aqui.
Brilhante. Pior espaço de armazenamento, não é?
Sim.
OK. Certo, então eu irei lá. Então,
O que ele vai fazer agora? Agora vem o
truque principal. Ele vai aceitar, olha, ele vai
Aceite esses pesos. Esta matriz irá levar
normalizado e multiplicado por aqueles
pesos que vieram do método AHP, fizeram
Não? Entendido.
Então aqui estão 3000 e coisas do tipo. Normalizou.
Normalizou. Então cheguei a isto
Resultado, né? Hum, agora ele vai pegar e
multiplicará por esses pesos de
AHP. Isso vai gerar esta outra matriz, veja.
Então aqui está a matriz normalizada.
ponderado. Vou ficar com ele.
Então, essa é a primeira.
padronização, que é a
padronização orgânica do método
Topsis multiplicado pelo peso que
Vinho da AHP. Deixe essa matriz salva
Ali, não é? Em seguida, passa para o segundo.
padronização. O segundo
a normalização é igual à de
Método Sapevo, veja. Então permaneceu
Primeiro, observe. 1, 0,2 e 0,7, 0 e 1
, VERDADEIRO? Sim. O que ele faz?
aqui? Veja, no iPhone, no custo,
Estamos realizando essa normalização.
Agora, veja. Aij menos o mínimo
dividido pelo máximo menos o
mínimo, certo?
Sim.
Então ele vai levar os 3000, certo?
VERDADEIRO? Veja, 3000, que é o Aij,
menos 1500,
menos o valor mínimo, que é 1500,
dividido por 3000 menos 1500, certo?
Foi por isso que ele deu um, certo?
Sim.
Aqui, neste tipo de padronização,
Os números um e zero sempre aparecerão.
Então essa é a matriz com o
segunda normalização, que é uma
segunda maneira de normalizar esses
quatro. Bem, então, será preciso isso.
matriz e também a multiplicará por
Os pesos do método AHP. Então
Este resultado permanecerá aqui.
Observe o seguinte.
Só um momento, professora, rápido. Tem
aquela coisa de fazer, hum, 10%, ou melhor
, 1% dos mais jovens, dos segundos mais jovens ou não?
Não possui nenhum. Neste caso de peso,
Não, aquela jogada, aquela jogada
É para evitar peso negativo e
Sim, mas se você olhar para o AHP, não.
Não havia nenhum peso negativo ou zero aqui, veja bem.
Ah,
o problema do peso zero ou do peso
negativo.
Ah, entendi.
Problema. Sim, não tem nenhum aqui, né?
VERDADEIRO? Esse peso é pequeno, mas
Não. Se você tiver um critério com peso zero.
Você pode remover esse critério.
Eu entendo.
Sim.
Ou se você tem uma opinião importante.
negativo, também não tem o mínimo
sentido, porque
Sim,
Isso significa que está atrapalhando, certo?
Sim.
Então não preciso me preocupar com
Isso se deve aos pesos gerados aqui.
Usando o método AHP, veja, você percebe que ele não é mais...
Eles não são nulos nem negativos.
Ah, excelente. Ok, ótimo. ?
Tudo bem?
Então, voltando ao assunto, eu tinha
Esta matriz aqui, basta seguir o
raciocínio. Eu tenho esta matriz de
decisão. Eu fiz duas normalizações.
diferente. Então, esta matriz
Isso gerou outras duas matrizes, certo?
Sim. Eu realizei essas duas normalizações.
Então, a partir de uma matriz, criei outras duas.
matrizes. Então peguei aqueles dois.
matrizes, cada uma delas, e a
Multipliquei pelo peso
pelos pesos AHP.
Sim. Então, fiquei com dois.
matrizes de ponderação normalizadas,
uma com padronização e outra com uma
A partir de agora, vou começar
Execute o método TOPSIS, entendeu?
? Agora
Sim,
matrizes normalizadas e ponderadas, ?
VERDADEIRO? Em seguida, ponderado de acordo com o
normalização e, em seguida, ponderação,
Multipliquei pelo peso do AHP. OK?
Ok, agora vamos abordar o método TOPSIS.
. Então, ainda não o usei.
Eu só havia utilizado o método AHP.
Tudo bem? Pesos e coisas do gênero,
Normalizei a matriz e removi os pesos maiores.
E eu multipliquei esses valores pelos pesos. Preparar
.
Agora vou apresentar o método TOPSIS.
O método TOPSIS, vou explicá-lo aqui.
Igualzinho, sabe? Se necessário, eu darei
Uma aula dedicada exclusivamente ao método TOPSIS.
Caso contrário, também não faz muito sentido.
, Tudo bem?
A ideia por trás do método TOPSIS é muito...
Simples e diferente dos demais. Ei,
Você tem n alternativas, uma é melhor em
Uma coisa é melhor em outra, e outra coisa é melhor em outra coisa.
etc. E o que o método faz?
TOPSIS? Qual é a lógica deles? Faz o
A seguir: Crie uma alternativa que
A chamada alternativa ideal seria
aquela alternativa que tem a melhor
desempenho em todos os critérios,
Ela seria a melhor em tudo. Então, porque
Por exemplo, deixe-me voltar aqui, veja,
Vamos voltar aqui e ver.
Então, crie um telefone aqui.
imaginário que seria mais barato,
Custaria 500 reais. Eu teria o melhor
A câmera teria 15 megapixels.
Terá 128 GB de armazenamento e
teria o melhor design, que seria
C.
Entendido. Aproveite o melhor de tudo.
O melhor em todos os critérios.
Então, obviamente, isso
O telefone não existe.
principalmente porque, se existisse, isso
Essa é a que eu compraria, né? Dado que
É melhor em tudo; Seria irracional.
Não compre.
Sim. Crie um telefone imaginário, ok?
uma alternativa imaginária que vence em
todos.
Sim.
E também cria uma alternativa que
chame-lhe a alternativa ideal e crie uma
uma alternativa que perde em todos os sentidos, que
Seria o pior em tudo.
Sim. Seria o telefone mais caro.
3000 reais, com a pior câmera, 8,
com o pior armazenamento, 32, e com
O pior design, três. E depois
normalizar cria uma distância
Euclidiano entre as alternativas
anti-ideal e ideal, ou seja, cria um
faixa.
Nossa, que ótimo! Ele diz: "Olha
Se o pior smartphone existisse...
mundo, o nível mais baixo da escala é este, e
"Este é o melhor smartphone do mundo."
Sim,
Ele calcula uma distância euclidiana.
entre a alternativa anti-ideal e a
Ideal, não é?
Então, leve esse cara para cá. Ah,
Agora vamos calcular, vamos criar
Um vetor para este Smart 3000, certo?
Câmera de 12 MP, 64 GB de armazenamento
projeto de cinco pontos. Em seguida, crie um
vetor. O vetor o compara com aquilo.
faixa. Quanto mais próximo disso
Um smartphone imaginário, entende?
A alternativa é melhor.
Melhorar. Sim. Excelente.
Brilhante. Sim. Você
Você percebe que, nossa, o cara tinha
Uma ideia brilhante, não é, meu amigo?
Sim. Muito legal. Então ele criará
três vetores. Isso criará um vetor.
para o iPhone, um vetor para o
Samsung e um vetor para LG,
compondo esses valores aqui. Quanto
mais perto da alternativa
ideal e bem diferente da alternativa
Anti-ideal, a alternativa será melhor.
Não? Então vamos voltar. Então o
O algoritmo TOPSIS foi desenvolvido lá.
em 1981 e é uma técnica de
avaliação de desempenho de
alternativas por similaridade
do mesmo com uma solução ideal.
Em seguida, ele calculará um vetor para
cada um e veja quão distantes
Existe esse vetor da alternativa
Ideal, não é?
Entendido. Sim. Estas são as equações.
do método TOPSIS. Não é difícil.
Nenhuma das duas, certo? Mas eu não vou entrar.
aqui estão os detalhes de cada um.
porque eles
Conversar é muito mais fácil, não é?
Conversar sobre o assunto é muito mais fácil.
Aquilo é. Tudo o que eu disse pode ser resumido em
essas equações.
Mas se ela os tivesse mostrado antes, o
As pessoas já teriam criado um bloqueio, não é?
Mas é exatamente isso que o TOPSIS faz, observar
. Então aqui está, vejam, a matriz
decisão. E aqui, veja, observe
Olha só que interessante. No
Na segunda etapa do método TOPSIS, eu tenho
Olha, você tem que pagar o dinheiro adiantado. W1,
W2, WN.
Sim,
com uma soma de 1.
É para que você possa multiplicar. De onde?
Será que eu vou sacar esses pesos, cara? Será que eu vou...
Inventá-las da minha cabeça?
Sim,
É aí que entra o AHP. Insira como
Veja só essa entrada aqui.
Desses modelos W que eu não tinha. Sim. E
Isso também poderia ser SAPEVO, certo?
? Como Junior está dizendo aqui
Olhe para baixo. Use SAPEVO-M mais TOPSIS
para contratar pessoas pode
Seja um bom, hein?
Pode ser o SAPEVO.
Pode.
Então, veja só, eu normalizei. Olhar,
A normalização do TOPSIS é aquela que
Eu mencionei isso, veja. X e J divididos pelo
raiz da soma de X e J². Então
Eu multiplico, sabe, a matriz
normalizado por peso. E eis o que
Eu te falei sobre a alternativa ideal, e
da alternativa anti-ideal.
Brilhante.
Alternativa A+.
Escolha a alternativa A, que é a
Ele ganha em tudo, veja só. P1 +, P2 +,
até PN+. E escolha a alternativa A.
pelo menos, que é o pior em tudo. E
É aí que você calcula esse D extra, entende?
Distância euclidiana? Exatamente.
Então ele vai, pega isso, olha, o pijama.
+ é a distância entre o máximo e o
mínimo para gerar esse intervalo que
Eu mencionei.
Sim. E será preciso tempo para cada um.
Alternativamente, criará a distância de
essa alternativa à alternativa ideal,
que é D, e a distância disso
alternativa à alternativa anti-ideal,
que é D-.
É uma distância euclidiana, essa aí.
uma fórmula que aprendemos na escola,
VERDADEIRO? Hum, quando você estiver em R2,
a distância é a raiz quadrada de X² +
δ y², certo? Aqui você pode ter n
Haverá, sabe, quantas alternativas?
Digamos quatro, cinco, certo? Então
Essas são as fórmulas do método.
TOPSIS. Então, vamos lá. Então
, retornando, sabe, ao nosso
Muito bom, muito legal
Problema com o smartphone. Então,
Primeiro preciso criar a matriz de
Decisão, ok? Eu criei a matriz ali.
Com os preços, sabe, o design,
tal. Então eu tenho que normalizar o
matriz para poder estabelecer uma
comparação entre critérios e para
então formam uma função aditiva
entre eles. Então, ok, eu normalizei.
Na verdade, fizemos dois.
Padronização, certo? Depois,
construção da matriz normalizada
ponderado. Então, eu peguei os dois.
matrizes normalizadas e as
Multipliquei pelos pesos, pelo
pesos
estabelecido além do método AHP.
Sim.
Agora preciso decidir. Então,
Paramos aqui. Isso é o
O próximo passo que precisamos é...
Participe agora, alternativa ideal.
positivo e o
Hum, alternativa ideal negativa, certo?
?
O ideal e o anti-ideal. Que.
Então vamos lá. E daí
O que vou fazer aqui? Existe a matriz de
decisão. Normalização TOPSIS.
OK. Já está feito, certo? Pelo
Isso já foi feito, certo? Hum, ali
explica que, em geral, os critérios
Eles são classificados em dois tipos. Hum, tem um.
que, hum, eu já mencionei em
A segunda aula, certo? Ter
critério monotônico de benefício ou
lucro e eu tenho o critério monótono
custo. O critério monotônico de
lucro ou ganho, quanto maior,
melhorar. E o critério monótono de
Perda ou custo; quanto maior a perda, pior.
, VERDADEIRO? Então, neste momento,
Preciso informar meu algoritmo.
Porque, caso contrário, ele irá interpretar mal. Olhar,
aqui,
Embora seja uma comparação inadequada, eles são
aquelas flechinhas que a gente costumava colocar quando
Utilizamos regras proporcionais de três.
,
Nós incluímos as dimensões, certo? Se for
inversamente proporcional ou
diretamente proporcional.
Sim, vou criar uma função aditiva.
Avaliar as alternativas. Ele
Um iPhone custa 3000 reais. Em outras palavras, é
O pior é o mais caro. Quando
Eu normalizo, veja, está em 0,78.
Após multiplicar pelo custo,
que tem o maior peso, permaneceu em 0,46.
. Se eu não disser nada ao algoritmo, terei que...
tenho um jeito de lhe dizer isso aqui,
Como ele é alto, isso é ruim, entende? O
Câmera aqui?
Sim. Quanto maior, melhor. Então, o melhor
É o de 0,17. Armazenar
Além disso, quanto maior, melhor. Então
O melhor valor é 0,10. Este também,
Quanto maior, melhor. Então, o melhor
É 0,038. Mas não o custo, o custo
Quanto mais velho, pior.
Pior, sim.
Então, se eu deixar como está, o
O algoritmo apresentará mau funcionamento.
Isso interpretará que o iPhone é o melhor.
Porque é o mais caro. E não é. Então
que deve haver um jeito de lhe dizer isso
Isto, para reverter essa mudança.
Então vamos lá. Então, eu vou
Quer dizer, veja bem. Precisamos identificar o
solução positiva ideal para o
critério de benefício e a solução
negativo ideal para o critério de
O custo, não é? No software que vou usar
Para mostrar, aparece ali, diz: o
A solução positiva ideal corresponde à
valor máximo ou mínimo do critério de
custo. Então eu digo a ele: entre
mínimo para o mínimo e máximo para
o máximo. Então eu escrevo o mínimo.
Então, o que estou dizendo para...
algoritmo? Estou dizendo a ele que
É melhor quando custa menos. O melhor
É o preço mais baixo. Então ele me pergunta
o mesmo.
Ah, entendi. Você disse? Entendido.
Tudo bem.
Então ele me pergunta sobre a câmera, e
Eu lhe digo: "Não, eu quero a câmera."
"máximo." É assim que ele entende o valor de
O que importa é a câmera.
Entendido. Ótimo, não é?
Sim.
E então, depois de ter feito isso,
O que ele vai dizer? Então ele diz
Aqui, certo? Em outras palavras, o
As equações anteriores escolhem o
melhores desempenhos em cada critério,
Seja custo ou benefício, eles criam
os vetores positivo e negativo. Que eles não são
mais do que o desempenho de um
alternativa perfeita, ou seja, alta
para os critérios de benefício e baixo
Considerando os critérios de custo, certo?
Tenho que ajudá-lo a subir nesse ranking.
que mencionei da alternativa
Do anti-ideal ao ideal, certo? Eu tenho que
ensinar o algoritmo a entender o quê
O que é bom e o que é ruim, se é barato ou
Caro, né?
Exato.
Bem, tem um truque nisso, veja bem. Sim,
Existe um truque para esse método TOPSIS.
Porque você diz: "Espere, professor,
Algo não está certo. Para quê?
Tenho que calcular A+ e A- e depois D.
+ e D-? Olha só. Veja, aqui, para
O que eu tenho que... ok, entendi.
Vou calcular A- e A+. Vou calcular
esse alcance, essa distância euclidiana.
Sim. Por que preciso calcular o
distância de cada alternativa até
alternativa ideal e de cada alternativa
para o anti-ideal? Por que eu tenho que
Faça esses dois cálculos? Sim. Me siga.
raciocínio. Se houver uma alternativa
o mais próximo possível da alternativa
Nota A+ ideal,
Sim,
Ficará automaticamente muito longe de
alternativa ideal negativa. Eu vou para
repita.
Sim. Se a alternativa for a mais
o mais próximo possível da alternativa ideal
positivo de A+, automaticamente
Ficará mais distante da alternativa.
negativo ideal. Em outras palavras, tenho uma variedade.
Aqui, certo? Quanto mais perto estiver
uma alternativa a partir deste ponto aqui
Sim, para cima.
Fica automaticamente mais longe do
Aponte para baixo aqui.
Sim. Teoricamente, eu não precisaria disso.
Calcule D+ e D-. Isso seria suficiente.
Calcule D+ e aquele com o maior D.
+ vitórias. Mas esse não é o truque. Que
Isso só é verdade em R2.
Somente em R2. Em R2. É verdade. Quem
Está mais próximo disso, é mais
bem diferente daquele outro. Se eu estivesse em R3,
em R4... na verdade, nem mesmo em R2 é.
Uma verdade absoluta. Isso só é verdade em
R1. Isso só é verdade em uma frase.
Sim, não, estamos comparando com um
Reto, certo? Não estamos comparando
com mais de uma dimensão.
Em linha reta. É verdade. Em R1.
Isso é verdade na R1.
VERDADEIRO. É verdade. Mas como estamos?
Introduzindo mais dimensões,
VERDADEIRO? Nós não somos
é
Não estamos preocupados apenas com um
Reto, certo? Nossa, que interessante.
É isso aí. Brilhante.
Sim, se estiver em R1, é verdade. Quanto
Mais próximo de A+, mais distante de A-.
Mas em R2 e além, R3, R4 e N, o que acontece?
Não? Não está presente em um espaço N-dimensional.
É verdade. Veja só aqui
por conta própria. Sergio Malandro, observe o quê
Em seguida, a alternativa Espere,
Espere um momento, eles estão aqui em
funciona. Deixe-me ver aqui, deixe-me
Fale com o cara aqui. Espere um
pedaço. Eu disse ao menino para parar.
Só um instante, já voltamos. Vá em frente,
continue.
Muito bem, então, veja a armadilha aqui.
Observe que a alternativa mais próxima
para o ideal
É a opção C, não é?
Sim. Isso mesmo.
Aqui estão todos os pontos sobre isso.
os círculos são os mais próximos do
alternativa ideal. Mas este C não é o
o que está ainda mais longe do anti-ideal.
Quem está mais distante do anti-ideal?
É a letra D.
Hum. Muito interessante.
Em outras palavras, o que é melhor, é?
É melhor estar perto do ideal ou é...
É melhor estar mais longe do anti-ideal?
Loucura, não é?
Então eu preciso criar uma medida.
relativo. Então é lá que ele dá aulas, certo?
Vou criar D, vou calcular D.
Além disso, serve para calcular a distância.
de cada alternativa para a alternativa
Ideal, não é?
Vou calcular o D para calcular o
distância de cada alternativa até
Alternativa anti-ideal, ok? Onde
Diz que D + é P + menos P, certo?
Não? Dessa alternativa, e D é a
P menos o P dessa alternativa, ?
Não? E lá vou criar, calculando o
distâncias da etapa anterior, o
O próximo passo é determinar o
proximidade relativa. Então a ideia
escolher como a melhor alternativa
aquela que mais se aproxima da
solução positiva ideal e ao mesmo tempo
Quanto mais o tempo passa, mais distante a solução fica.
ideal negativo, porque eles não são
Sinônimos, certo? Vimos que eles não são
sinônimos. Estar perto da solução
O ideal positivo não é sinônimo de ser
mais distante da solução ideal
negativo.
Isso é uma loucura, não é? Que
Estamos acostumados a sempre pensar
Em linha reta, certo? Em linha reta, certo?
Por isso, preciso calcular.
Isto, que é D dividido por D + + D-
.
Sensacional.
E é isso que o ranking vai me proporcionar.
Não? Certo, então voltando ao assunto...
Nosso problema, então, é o que temos lá.
a classificação da primeira normalização
. Tenho o LG, o Samsung e o iPhone lá.
Olha só, o LG com a pontuação. Isso é
padronização tradicional, vindo
da padronização tradicional de
topsis, certo? Então aconteceu ali
0,94, 0,1. E a segunda normalização,
Veja, é claro que os valores têm
que dão resultados diferentes, porque eu usei dois
diferentes padrões, então é
É natural que os resultados sejam
diferente,
Mas o ranking, idealmente, deveria ser
Continue assim, certo?
Exatamente. Não é natural que o
alteração de classificação; a classificação permaneceu
só para ver se as minhas opiniões eram
consistente e realmente chegar a um
apoio para a decisão adequada. Então
Essa é a primeira normalização. Que
Ali, por exemplo, digamos que aconteceu
, Não? Se isso acontecer, terei que ir ao
A origem da Matrix de novo, né?
Preciso repensar todo o problema.
Preciso reformular todo o problema, certo?
Tudo bem?
Isso resolveria todo o problema. Se o
A ordem muda, eu tenho que, eu tenho que
Será que isso resolve o problema por completo?
bom?
Nossa, que trabalho enorme!
Mas é assim que as coisas são, não é? É um
mecanismo de controle para ver se meu
As opiniões são imparciais, se forem
consistente.
Definitivamente.
A função do método é precisamente
É isso aí, é agarrar seus pés e dizer:
"Ei, você entende? Essa modelagem que..."
O que você fez não está certo, você tem que
Analise, entendeu? Porque não funciona
Não há dificuldade em criar um modelo tendencioso e
utilize esse resultado; naturalmente,
Esse resultado não lhe dará o melhor.
Eu apoio a decisão, certo? Bem,
e as possibilidades de aplicação são
Infinito, assim como o Sapevo, certo?
VERDADEIRO?
Sim. Hum, posso aplicar isso em ambos os níveis.
Operacional, tático e estratégico.
Então, eu já orientei um aluno que
Ele aplicou este método HPOPS 2N a
Selecione uma máquina extrusora. É
Em outras palavras, um problema relativamente simples.
Igualzinho a esse de smartphone, né?
Foi um projeto final de curso. E
Máquina de quê? Desculpe. Extrusora.
É uma máquina de extrusão. É um
Máquina para a indústria de plásticos.
Ah, entendi. Tudo bem.
Hum, mas também posso usá-lo para
Escolha um navio de guerra, certo?
A Marinha usou recentemente o
método multicritério para fechar isso
negócio avaliado em 9,1 bilhões de reais.
É Tamandaré, não é?, o que você disse,
É o projeto Corvette ou Fragata
Tamandaré, certo? Hum, com 215
critérios.
Oh. Então eu posso usar isso
ferramenta na maioria dos problemas
Vários, não é? Olha, isto é um
Artigo escrito por um estudante, por um autor de tese.
que é do exército. Ele colocou isso lá
aquisição de um veículo blindado
Veículo multifuncional leve sobre rodas para o
exército brasileiro através do
Método híbrido AHP-TOPSIS-2N, ?
VERDADEIRO? Hum, o exército estava em dúvida.
entre o veículo Iveco ou o
Veículo AVIBRAS. E é aí que usamos
o método AHP-TOPSIS-2N para ver qual
Dos dois, é o veículo que melhor se adapta às necessidades.
Ele serve no exército, certo?
Brilhante. Então, nós escrevemos esse artigo.
e já foi aprovado, será apresentado em
o simpósio de engenharia de
produção que ocorrerá lá em
Pernambuco, Caruaru, certo?
Muito bom.
Hum, outro artigo foi apresentado no
SPM em novembro do ano passado,
VERDADEIRO? Veja, aplicação do método
Híbrido AHP-TOPSIS-2N para o
disposição de orifícios de alívio em
Revestimento de poço de petróleo.
Nossa. Excelente. Veja, você pode
Aplique-o na maioria das situações.
Diversos, não é? Ah, e aqui estou eu.
Você faz perguntas assim: "Nossa, professor, mas
Estou começando a ficar confuso(a) com o
Cabeça, certo? Porque SAPEVO, né?
AHP-TOPSIS-2N, veja, confira, com o
Com o tempo, você gradualmente vai compreendendo essas coisas.
nuances, certo? Quando você tiver o
Método SAPEVO,
É mais qualitativo, não é?
Exatamente. Pode ser usado em
qualquer situação, mesmo quando
Você possui os dados quantitativos. Mas é
Mais interessante ainda, seu poder reside em
ser um tomador de múltiplas decisões e capturar um
opinião que está na cabeça de
alguém. Opinião subjetiva. Ah, isto
Esta xícara é muito melhor do que a outra.
Eu simplesmente sei que é melhor. Não sei quanto
É melhor. Eu sei que é melhor. Então,
SAPEVO é mais interessante quando
Você tem essas variáveis ​​qualitativas que são
Na mente de um especialista, o quê?
VERDADEIRO?
Sim. Agora, se você tiver os dados
valores numéricos das alternativas e do
critérios, você estará subutilizando o
SAPEVO. Você tem métodos mais adequados
Para processar esses dados, certo?
Então, neste caso, neste
Nosso exemplo, certo? Você tem aí,
Você tem uma matriz ali com os dados.
do problema, certo? Eu não preciso do
Ninguém tem opinião para saber que o
O iPhone é mais caro que o Samsung. Que
Não está na cabeça de ninguém. Eu sei
O iPhone é pior, não é?
Sim.
Analiso o custo aqui e vejo que de todos
A melhor delas é a LG. Porque é o mais
barato, vejo que a melhor câmera é a
Da LG, porque tem, né?, aquela da
maior número de megapixels. Então eu não dependo de
Opinião de ninguém. VERDADEIRO? Ele
128 de armazenamento é o ideal.
Portanto, não dependo de opiniões.
Portanto, o Sapevo depende disso.
encontrar uma maneira de extrair do
a cabeça da pessoa, sua opinião e
gerar uma medida quantitativa.
Sim,
Não, não essa. Essa é mais interessante.
quando eu já tenho esses dados, porque
Eu consigo processar esses dados, certo?
Sim. E será que dá para misturá-los?
também, né? Porque existe um design.
ali, por exemplo, que você coloca como
qualitativo.
Ah, você pode misturá-los.
Brilhante.
Então,
E o que eu também acho ótimo é
que o Prometeu de Michael também
Ele trabalha com estatística, certo?
Calcule o desvio padrão, certo?
Calcule o intervalo de confiança. Muito
Bem.
Exatamente. É
Muito legal.
Muito legal. Sim, então ele vai
apresentar aqui no
grupo também.
Aqui estão algumas referências.
Posso enviar esta apresentação para você.
disponibilidade em nosso site
laboratório, do qual o professor
Isso também faz parte disso. Temos vários
publicações sobre o método
AHP-TOPSIS-2N. E além disso
publicações, temos o software para
Baixe o executável do Python ali.
Para poder fazer isso, coloquei o link lá.
isso está ok?
Brilhante. Ah, e eu queria aproveitar esta oportunidade.
a oportunidade,
Ah, fique à vontade.
O oitavo simpósio de engenharia de
A produção ocorrerá lá em Caruaru.
Pernambuco. Hum, será do dia 20 ao dia 22 de
Maio de 2020. Este é o segundo
congresso de engenharia de produção
A maior do Brasil, né? O mais
Engep é ótimo, não é? E isso
Está entre os melhores, não é?
O segundo maior. E quanto ao tópico
Será pesquisa operacional, a
pesquisa operacional como
ferramenta de inovação, eu vou
para utilizar essas ferramentas que temos.
Usado no IM para o público, certo?
Você será o palestrante principal lá.
do
Muito bom.
Ele será o palestrante principal.
além do evento. Então, quem puder
Você está convidado(a) a participar.
Excelente. Parabéns. E muito bom.
Dois alunos enviaram seus
artigos e foram escolhidos, eu acho
Eram sete itens, se não me engano.
Erro no total, sete ou cinco. E de
esses artigos, dois dos meus alunos
foram os dois melhores artigos que
Eles ganharam o prêmio CEP, não ganharam? Do
Os melhores artigos do Brasil.
Excelente. Maravilha. Excelente. Bom,
Então vamos começar a trabalhar.
Vamos começar a trabalhar.
Muito bom.
Vamos começar a trabalhar, certo?
?
Muito bom.
Vou administrar o
algoritmo para que, se alguém quiser
Use o método, saiba mais ou menos
tudo certo?
Como fazer passo a passo.
Então vamos lá, vamos ver se
Corra para lá. Não sei, né? Vamos
Vamos ver o que acontece, ok?
Alguém ficou com alguma dúvida.
Pessoal, e quanto à parte teórica? Qualquer um?
Você tem alguma pergunta?
Fique à vontade para fazê-lo.
Espere, deixe-me ver se consigo compartilhar.
aqui.
Tudo bem. É o primeiro. O primeiro
Compartilhe todo o seu computador.
Espere, quero abrir o Let Me See.
aqui. Ah, pare de compartilhar. Não é
Eu coloquei aqui. Vejamos aqui. Olhar
Se você estiver olhando para a tela ali
Estamos aqui, estamos aqui. Você está assistindo?
Sim?
Então, é isso. Então, eu vou
Apresenta exatamente o mesmo problema.
Deixe-me analisar os dados aqui. Espere.
Vou executar exatamente o mesmo
O problema que estamos discutindo em aula é...
VERDADEIRO? Então, está escrito ali, digite o
número de critérios que você deseja
analisar. Então, neste caso, eles eram
Quatro critérios, certo? Então eu vou
Coloque quatro ali, veja. Quatro,
Certo? Tudo bem?
Ali, pede-se que você insira os critérios desejados.
analisar. Então, vou definir um preço.
Custo. Outro critério: a câmera. Outro
critérios, armazenamento.
E design, certo?
E design. OK. Ele anda por aí fazendo perguntas.
Quando você faz essa pergunta, na verdade
Já está utilizando a escala.
A escala fundamental de Saaty, a de 1
para a etapa 9 do método AHP, certo? Que
O critério de custo é preferível.
em relação à câmera. Eu vou para lá.
Coloque quatro. Ali pergunta quanto
O critério de custo é preferível em
em relação ao armazenamento. Eu vou para
Coloque cinco. Qual é o critério?
O custo é preferível em relação a
projeto. Sete. Qual é o critério?
A câmera é preferível em relação à
critérios de armazenamento. Está lá
três. E qual a importância dos critérios da câmera?
É preferível em relação ao design.
Cinco. Então, qual é o peso do critério?
O armazenamento é preferível em
em relação aos critérios de projeto. Vamos ver,
Design de armazenamento, 3. Veja, já
Ele fez os cálculos.
Hum, ótimo. Ele já enviou.
Então, veja, aqui já me deu o
matriz de ponderação.
Sim,
da AHP. Note que, quando eu disse isso
O custo por câmera é de quatro, no
O algoritmo associou isso automaticamente.
O custo da câmera é 1/4. Eu já fiz isso.
Sim, ótimo, não é? Eu sempre
Eu digo isso aos meus alunos, certo? Nem sequer dê a opinião do
possibilidade de que a pessoa preencha
câmera/custo com 1/4, porque senão,
Ele dirá que aqui é um quinto e que
Aqui é a sexta. Coloque-o em
investir automaticamente e não ter
essa possibilidade de erro. Então, agora
A matriz de ponderação foi formada aqui.
E já apareceu aqui com os pesos. e
Eu já descobri o motivo da consistência.
foi inferior a 10%. OK? Se o motivo para
A consistência é superior a 10%, se
Se for maior que 0,1, o programa para.
E ele diz: "Olha, é inconsistente, é cheio"
"De novo." Você precisa concluir isso.
Você precisa responder a todas essas perguntas.
Faça as perguntas novamente até que sua solicitação seja aprovada.
Em termos de consistência,
Entendeu? Se funcionar, se esse valor estiver aqui,
Se esse valor estiver aqui, o motivo para
consistência, se esse valor for maior que
0,1, o algoritmo não continua.
Entendido.
Não, não vai continuar, não vai pedir o valor.
de alternativas. Ele vai te mandar para
Reavaliar os critérios.
Hum, ótimo.
A razão para a consistência deve ser
menos de 10%.
Esse
bom. Então ele vai lá, digita o
número de alternativas. Então eles são
Três alternativas, certo? Lá vai ele
enviar, deixe-me organizar aqui para
Não confunda. Vou colocá-los lá.
alternativas, certo? Então eu vou
Coloque um ali, depois o outro.
Alternativa da Samsung, e depois a outra.
Alternativa à LG. Está escrito ali: "Entre no
valor da alternativa ao iPhone com
em relação ao critério de custo." Então
O iPhone custa 3.000 reais. Aquilo é. Agora
Estou concluindo o
matriz de avaliação, certo? QUALQUER
matriz de avaliação, é uma matriz de
Decisão, ok? Certo? Então
Que nós não temos em Sapevo, certo? Em
Sapevo depende da opinião de
Alguém, algum especialista. Não, dados,
Se eu tiver os dados, vou usá-los.
VERDADEIRO?
Então, 3.000 iPhones em relação a
Câmera 12. iPhone em relação a
64 GB de armazenamento. Design para iPhone.
Agora ele vai encomendar o Samsung. Custo de
Samsung 1800. Câmera oito,
Armazenamento de 32 GB, design de 4 GB. Lá, LG,
Câmera LG 1500, 15 polegadas, armazenamento de 128.
3. Oh,
brilhante.
Ali, tudo o que eu estava mostrando...
Ele calculou, veja. Então, veja o que
fez. Então eu tenho aqui, veja, o
matriz de decisão, ou matriz de decisão
avaliação, olhar.
Certo? Foi lá que ele fez o primeiro.
padronização,
essa normalização orgânica de
Topsis.
Sim.
Aij dividido pela raiz quadrada de
soma de Aij. Soma de Aj², ¿
VERDADEIRO?
Sim. Ele fez a normalização e aqui está
normalização ponderada, que é a
normalização do Topsis multiplicado
por causa dos pesos, esses pesos aqui de
AHP, certo? Certo? OK. E aqui está o
segundo
Será realizada a segunda normalização.
Segunda normalização, veja.
Ele normalizou a normalização igual a
De Sapevo. Multiplicar
normalização por pesos AHP
. E agora vai começar a executar o
O método TOPSIS, entende?, calcula esses
Distâncias euclidianas e tudo mais, certo?
Está escrito isso, veja. A solução ideal
positivo corresponde ao valor máximo ou
custo mínimo. O que é isso?
Você quer pagar muito ou quer pagar pouco?
Pagar pouco? Ah, eu quero pagar pouco, certo?
VERDADEIRO? Custo, o custo é mínimo, certo?
Não? Então você está dizendo que ele vence.
o celular mais barato.
Então ele entendeu.
Então ele pergunta: "A solução ideal
positivo corresponde ao valor máximo ou
"Requisitos mínimos da câmera?" E você, opa,
Quero a melhor câmera. Máximo. E
do armazenamento: "Opa,
Eu também preciso de espaço para guardar coisas.
"máximo." Em outras palavras, você está dizendo a ele
Essa é a alternativa ideal, não é? Que o
A solução positiva ideal é aquela que
É o celular mais barato, com o melhor
câmera, com o maior armazenamento e
Com um design melhor. Está criando o
celular, aquele smartphone imaginário que
Ele é bom em tudo.
Mas?
E então o projeto. Ah, o design
É também o máximo. Preparar. E lá
O método terminou, certo? Então
Veja, aqui está o ranking do primeiro.
padronização. A LG ficou em primeiro lugar.
A Samsung em segundo lugar e aqui
Esses são os valores, veja. E aqui está o
segunda normalização.
Excelente.
É claro que os valores serão diferentes.
Porque é outra normalização, mas
O que importa para mim é que o ranking seja o
mesmo. LG, Samsung, iPhone. LG, Samsung
iPhone. Isso significa que meu
O problema está bem estruturado, que
Encontrei um resultado coerente e isso
Provavelmente irei refletir sobre o
Pensando nos tomadores de decisão
Decisões, eu apoiarei adequadamente.
para
Muito bom.
os tomadores de decisão.
Sensacional. Excelente.
Junior disse aqui
Nada, o Junior acabou de dizer isso aqui.
Em seguida, ele vai revisar a aula, para
Estude um pouco mais. Por agora, tudo
bom. O problema é quando fazemos isso,
É aí que surgem as dúvidas. Sim.
Ah, sim. Claro. É verdade. Quando
Você coloca, como eu disse, é colocando as mãos em
o trabalho. Que
Sim,
Vamos começar a trabalhar.
É.
Ah, Junior, Junior disse aqui que ele é
incrível. Ela gostou muito, não é?
VERDADEIRO? Incrível. Ana disse muito
Interessante e, acima de tudo, útil.
Parabéns.
Brilhante. Excelente.
Muito útil. Você pode aplicá-lo à maioria
Situações diversas, não é? Deixe-me ver
Se houver algo mais a dizer. Não há nada.
avançar. Então, era isso que eu tinha.
Para mostrar, certo?
Fechado. Maravilha. Gostei muito.
Obrigado, Igor. É,
É útil.
Até eu aprendi alguma coisa hoje, não é? Porque eu
Eu já tinha feito o curso lá,
Mas eu ainda não tinha visto.
Muito bom. Gostei.
Você pode aplicá-lo a problemas muito complexos.
coisas simples, como comprar um celular
1000 ou 2000 reais, ou em um
negociação envolvendo 9.000
Milhões de reais, né? Sim, com
segurança. Problemas complexos, não são?
Até mesmo assistir Netflix com a namorada, né?
Não?
Exatamente. A partir de problemas simples.
É assim mesmo.
E então, para facilitar, criamos isso.
ferramenta ali, certo? Eu, Alace, que
Sim, você pode encontrá-la, Ana.
Você pode encontrar o programa lá no
Laboratório. Você e Alace, mas quem mais?
Era? Eu e Alace.
Ou você e Alace. Brilhante. Nós desenvolvemos em
Python, esse código, certo?
Ela perguntou se o código-fonte de
Os cálculos são públicos.
Não, não o código-fonte, apenas o executável.
Sem código-fonte, apenas o executável. Equipamento,
entendido.
Você pode usá-lo e gerar o
Aquilo é.
Tudo bem. Ei,
É ótimo. Então, pessoal, obrigado.
professor.
Então, é isso.
Bom demais.
Agradeço novamente o convite.
Sensacional. Muito bom. O próximo
A transmissão será feita pelo professor.
Fabrício Maion,
Vai ser sobre o método Thor, certo?
Ele também.
E depois
Nossa, será que ele vai trazer o martelo e tudo mais?
, Não?
O martelo e tudo mais. É
Bem. Então,
É isso aí.
Tania também falou aqui. Muito bom,
Ei. É ótimo. Todos gostaram.
muito. Então, muito obrigado.
Obrigado a todos por estarem aqui. ELE
aquela manhã de sábado não é a
Seria melhor para todos, mas fazer o quê.
Foi isso que conseguimos remarcar aqui.
Devido ao imprevisto, mas foi ótimo.
excelente. Obrigado, professor. Obrigado
também por causa do tempo, por estar disponível
um sábado.
Para qualquer coisa, estou disponível.
Maravilha. Muito obrigado. Um forte
abraço. Bye Bye.