# Video 1 - Machine Learning Tips Series - Image-Based Team Classification

- **URL:** https://www.youtube.com/watch?v=okWcPDvYRmg
- **ID:** okWcPDvYRmg

## Transcrição

fala galera aqui é saulo catarino
falando no canal estatística lado do
professor tiago max trazendo dicas de
python
hoje eu vou trazer pra vocês uma dica
super legal que vai desmistificar um
assunto que estão querendo transformar
em um bicho de sete cabeças e que não é
que a classificação de imagens
hoje nós faremos dois tipos de
classificação de imagem classificação de
imagem pô é ver o vetorial de suporte
linear classificação vetorial de suporte
linear e também classificação por
regressão vetorial e suporte importando
o pv ea biblioteca
antes de mais nada a gente precisa
estabelecer o conceito de que a imagem
o arquivo de imagem quando ele é lido pé
pelo ou perceber ele é convertido em uma
matriz
como assim a matriz cada pixel como a
gente fala que uma imagem tem resolução
de 200 duzentos a gente está dizendo que
ela tem 200 pizza na horizontal 200
pixels na vertical
então quando a gente abre a imagem que
mantenho com o pv
ele converte essas informações esses é
essa imagem informações de maneira que
cada pixel fica assim zero é apagado 255
a máxima intensidade então como rgb fica
255 255 255 255 255 255 aqui é só isso
aqui é um pixel isso aqui é outro pixel
e assim sucessivamente fazendo 200
desses e 200 para baixo assim das 200 ac
na lateral e 200 assim na vertical
ok vamos abrir uma imagem pra gente ver
isso na prática atlético ge porque é
grande a gente tinha que ela vai ser
reduzida é igual a cb2
o atlético enquanto jpg
vamos ver essa matriz ela como eu falei
tá vendo cada valor desse é relativo a
um pixel da imagem
então dessa forma o shape da matriz se a
imagem de 200 por 200 e é lá é tem que
ser 200 203 porque rgb head grilo netão
três cores para formar cada cada ponto
vamos ver aqui o shape e atlético ponto
sei lá 200 203 porque é uma imagem de
200 pixels 1.200 com três cores rgb
ok então vamos abrir todas as quatro
imagens pra nós o nosso exemplo de
classificação o corinthians
é certo que o flamengo
e aqui é palmeiras
como exibir essas imagens e v2 em show
atlético 2 água que aguardar até antes
de fechar a janela não vê lá tá vendo
200 por 200 a imagem
todas elas de igual forma são 200 por
200
então agora como é comum é é trecho é
redimensionar a imagem porque a gente
está tratando só com quatro imagens
então o banco de dados está
relativamente pequenos mas é pequeno mas
é muito comum a gente reduzir o tamanho
da imagem para treinar modelo porque
porque senão fica muito pesado quando a
gente trabalha com muitas imagens também
é é agilizar o processo de
reconhecimento
agora a gente vai reduzir o tamanho
dessas imagens que história de 200
duzentos das cores para 10,10 negou a 3
pra gente usar a biblioteca o que se vê
também então se o atlético é igual
até é servir dois me saio do atlético já
que é grande e água 10.010 contava que a
gente quer acompanhar o colégio 4
corinthians dia corinthians cingir vai
ficar pequena flamengo g tamengos em
mogi mirim agir
talvez seja vamos ver aqui o shape the
skies print atlético ficou em 10,3 talal
de 200 203 passou para 10 3 ou seja ao
invés de ter 200 k
assim um do lado do outro vai passar
pessoa 10 10
tá com um vamos lá agora a gente vai
concatenar todas essas quatro imagens em
uma única matriz que fica é x é igual ao
mp
nele o atlético corinthians está lá 40
ou seja unificamos as quatro imagens com
10 10 3 para uma única matriz com o
shape 40 10 10
então a gente precisa agora criar o eixo
de índices para cada imagem a gente vai
dar um valor ou seja o atlético é essa
em um
o corinthians vai ser 2 o flamengo e se
três e o palmeiras terá quatro
dessa forma a gente vai relacionar cada
parte de 10,10 pra cada índice
vamos converter isso pra uma matriz de
shape nela
enchi silva vamos dar um recheio
peluches desigual
se cheguei o tamanho do elenco é o
número de índios que a gente tem menos
um que é totalitário da imagem a dívida
do haiti vai dividir a a matriz em
quatro partes iguais ou seja porque o
ibson tem quatro índices houve frente
china está perfeito perfeito 4
agora nós vamos importar as bibliotecas
para criar a nossa classificação na
nossa regressão from importe é que é o
sr
a gente vai fazer todas elas com um
formato linear regressão linear e e
classificação vitória sport nenê
vamos ver aqui agora vai criar objetos e
lf é igual a essa linha vamos criar o sr
obs 1 e agora nosso negócio que começa
propriamente dita a gente vai fazer o
treinamento cnf x y ou seja entramos
aqui com os as imagens aqui com os
índices da imagem
para relacionar cada imagem ao seu
índice nikkei
o dele é se calar treinamos agora a
gente vai fazer uma pressão está nos ver
nós treinamos a máquina para reconhecer
essas imagens
ok agora a gente vai verificar se a
imagem realmente é reconhecida na edição
é igual
lf atlético que a gente vai usar essa
imagem aqui
o atlético tem que botar no chip é
apropriado ea gente também vai calcular
o score dessa escola é igual a gente vai
ter resultado em si foi o atlético tem
que vim com um porque atlético é
relativo ao invés de um a única que sim
então vem aqui print instalar um
vamos colocar também escola que é a
precisão do modelo 100%
vamos fazer uma uma série de hips
condições pra igual
ou seja se a proibição for um aparecerá
a bandeiras por dois apareceram outros
fortaleza parecia outro dos 34
ou seja se o resultado da apreensão foi
um ele vai abrir a imagem
grande resultado
vamos lutar resultado é igual ao
atlético de 2
corin de 3
lamento o g14 palmeiras de agora a gente
vai exibir é mais um show
resultado o resultado de 2 a 0
estava realmente ele abriu a imagem do
atlético mineiro com 100% de precisão
como testavam botar que flamengo tá
vendo que nós fizemos aqui nós treinamos
um modelo e aqui nós botamos uma imagem
para perguntar o computador
acredite me diga que imagem é essa eu
vou baixar aqui uma imagem do escudo 200
por 200
escuto o flamengo e vou botar 200 com
200 tamanho 1 exatamente nos andes
presente de pegar esse escudo daqui
daqui vou salvar a gift você já tá peixe
sob ataque de ontem 11 11 que pareça não
pareça muito expectante trabalhar lá
esse teste teste bng
vamos lá agora a gente vai abrir aqui a
imagem teste é igual e vamos testar essa
imagem em baixo flamengo teste ver como
ele vai classificar não tem 10 56
até porque jpg png venda pública
até que redimensionar teste é igual ao
cv 2 e size teste 10o 10 pronto não vê
agora ela é e ela classificou como o
flamengo voltar pra imagem de teste de
2010
isso já que a imagem de teste
está aqui o resultado precisam dizer por
cento