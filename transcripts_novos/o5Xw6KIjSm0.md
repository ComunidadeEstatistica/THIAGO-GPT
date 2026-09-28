# Part 1 - Image Classification of Airplanes in Tensorflow using R

- **URL:** https://www.youtube.com/watch?v=o5Xw6KIjSm0
- **ID:** o5Xw6KIjSm0

## Transcrição

Olá pessoal. Bem-vindo(a) de volta ao
Meu canal de MMO. Eu sou Pedro Lealdino e hoje
Vamos criar uma rede neural rápida.
para classificar se uma imagem é uma
carro ou avião. Então vamos lá
. A primeira livraria que
O que precisaremos é do EBImage. Eu não sei como
É pronunciado, mas servirá para...
Podemos trabalhar com as imagens. ?
OK? Muito bom. Eu também precisarei do
Keras, que é a interface que torna o
Conexão entre R e TensorFlow.
Também vou precisar do Caret, não sei.
seja lá como você pronuncie. Nós apenas
ajudará a separar os dados para o
validação de treinamento e
Experimente, está bem? E também PBapply.
Esta biblioteca nos permite fazer o
mesmos loops, digamos, como Lapply e
Aplicar, mas demonstra progresso, um
barra de progresso ao aplicar o
funções. Então, muito bom, muito
bom. Vamos então.
continuando. A primeira coisa que eu preciso
Fazer isso é saber onde meu
Arquivos, ok? Eu já tenho meus arquivos.
aqui e criei uma pasta com aviões e
Mais uma com carros. Vou te mostrar como
são. Então, carros por aqui. Me deixe em paz
Expanda isso para facilitar.
Acho que tenho 40 arquivos aqui de
carros e você verá fotos, ok? Muito
bom. E eu também tenho de avião.
Vejamos aqui. Eu só quero voltar
aqui em cima. Aviões. Abriu
Aqui, mas tudo bem, não tem problema.
. Então, estes são os meus arquivos de
aviões, ok? Então, estes
São meus aviões, ok? Então, é isso.
O que precisamos fazer primeiro é
Estabelecer este espaço como meu ambiente.
trabalhar. Tudo certo? Então,
Vamos. Vamos criar o nosso próprio
primeiro caminho para as imagens do
carros. Então, carros. OK. Muito
bom. Agora, a rota dos aviões.
Aviões. Aviões. Bar. É muito bom.
. Quero te mostrar uma coisa. O que acontece
Quando eu tiro uma foto, eles
Vou mostrar rapidamente aqui, por exemplo,
aviões, ok? Então vou colocar um
Imagem de exemplo. E eu vou ler isto.
Imagem de, opa, uh, do meu desde
meus arredores aqui. OK. Então, vamos lá.
lá. Aqui, agora vou colocar aqui
aviões e eu também colocarei, por exemplo
, avião JPG.jpg. Ah, algo importante.
O que você precisa saber é que isto
A biblioteca normalmente trabalha com
Arquivos JPG. Às vezes eu uso PNGs
Além disso, deve funcionar com PNG.
Mas ele não consegue fazer isso. Então é
Vou converter para JPG de qualquer forma, tudo bem?
? Então, vamos lá. Bem, eu não tenho
Esta imagem de exemplo. Vamos ver
Que imagem de exemplo é essa?
Então, esta imagem de exemplo tem
isto aqui. Veja que já está em
Formato quadrado, tudo bem? Eu vou para
Tente encontrar outra imagem. Vamos
Tire outra foto aqui. Quero usar,
Por exemplo, a vista frontal do 350,
Por exemplo. Muito bom. Veja que isto
A imagem já não é quadrada, não é?
VERDADEIRO? Porque eu tenho as dimensões
Aqui era 1265 por 550. Aqui era 591.
por 591. E três é o número de
Eu tenho canais de cor, certo?, que
É vermelho, azul e verde. Muito
bom. O que mais eu sei sobre essa imagem?
Por exemplo, consigo ver a estrutura,
Isso pode nos dar dois tipos de, uh,
matrizes aqui, neste caso, que são
os dados, certo?, dessa matriz. Qual
O que vamos fazer é criar uma função que
Pegue este vetor exato daqui.
Em outras palavras, vou transformar um array.
Está neste formato aqui, certo?
OK? Está nesse formato, é uma matriz.
multi bidimensional, multidimensional.
Mas eu quero transformá-la em uma matriz.
Unidimensional, ok? Que seria
Pegue esses dados ardata daqui. Então
Vamos criar uma função para isso.
Mas primeiro teremos que transformar
todas as imagens em imagens
quadrado, ok? Porque para poder
Trabalhando com eles dentro do mesmo contexto, né?
, dentro do mesmo parâmetro de
Entrada da minha função no meu modelo. Sim
Não, eu teria, por exemplo, se eu trabalhasse.
com uma imagem que tem um tamanho
diferente, ao passar pelo mesmo padrão de
imagem, provavelmente criará dados
sumiu, ok? Então eu preciso
transformá-las em imagens quadradas e
Vou deixá-los todos quites com o
mesma dimensão, ambas para a largura.
Quanto à altura. Muito bom. Então
Vamos criar uma função chamada
extrair características. E isto
A função receberá como parâmetro, ela irá
Para seguir esse caminho, ele vai seguir o caminho de
A imagem, neste caso, certo? Ah,
Na verdade, deixe-me mostrar-lhe aqui,
Posso até mostrar a imagem, se quiser.
OK? Se, por exemplo, a imagem de
Por exemplo, aqui, vou mostrá-los para você.
Este é o avião, ok? que eu escolhi
Aqui está um exemplo. Então, é isso.
O pacote é muito bom para você.
usar. Não vou mais usar isso.
aqui, então vou apagá-lo. OK.
H. Ok. Muito bom. Então, isto
A função terá esses três parâmetros.
. Vou começar atribuindo a imagem ao
tamanho da imagem, que é a largura
através do alto. Nós nos lembramos disso na escola.
que a área de um retângulo é a
altura por largura. E isso me dá o
tamanho total, ou seja, a área de
A imagem, ok? Então, esse sou eu.
Isso lhe dirá quantos pixels a imagem possui.
. Muito bom. Nome da imagem. Eu vou para
Então, vou percorrer uma lista.
dos arquivos que estão no diretório
que eu passei como parâmetro para a função
. Em seguida, vou imprimir o processo.
processo de conversão destes
imagens. E vou combinar comprimento, sempre.
Estou confuso. E vou tirar isso de
aqui. Imagens. Preparar. Muito bom.
Então eu vou querer uma lista de
parâmetros. parâmetros, que também
acontecerá para cada um dos elementos.
da nossa lista aqui com o nome do
imagem. Vou dar uma passadinha, né?, para cada um deles.
um dos itens desta lista
imagem, uma função chamada imag,
OK? Então, vou criá-lo aqui.
dentro e fará o seguinte: pegar o
imagem. Então vou ler imagine o
O arquivo p é então igual a
diretório que eu já consultei e este aqui
e imagem redimensionada. Então agora
Vamos redimensionar a imagem, opa.
Para obter um valor de 30x30, o quê?
Tudo bem? Bem, a. OK. Muito bom.
Então, quero transformar essa imagem em
matriz com os valores. Você se lembra disso?
Será que vimos isso? Portanto, a matriz de imagem é
equivalente a isso como uma matriz. Esta imagem
Ponto de dados redimensionado, ok?
Nós nos lembramos do que fizemos, nós levamos isso conosco.
dados daqui, ou seja, vamos pegar o
valores de todos os pixels e
transformá-los em uma matriz e
Vamos transpor esta matriz porque ela é uma
vetor coluna. Quero transformá-lo em
Um vetor linha, ok? Então,
retornar. A imagem, o vetor é o mesmo
um vetor s, a transposta da matriz
de imagens. Muito bom. Vetor de retorno
da imagem. Muito bom. Então temos
Agora, aqui, digamos, a parte central.
da nossa função. E aqui vamos nós
retornar. Precisamos de uma matriz que
Pegue todos os dados de todos os
Aviões ou todos os carros, ok?
E volte para nós, digamos, o dataframe.
completo. Então, toda vez que eu pego e
Transformo uma imagem em uma linha,
Digamos que eu vou, hum, adicionar isso.
concatenar isso, digamos, com a linha
antigo. Então isso vai acontecer
transformar um quadro de dados para cada
Para cada imagem, está tudo bem? Esse
Aqui está uma lista de
parâmetros. Muito bom. Este fi, este
A matriz é como uma matriz de dataframe.
Muito bom. E os nomes, então, são
ou seja, os nomes das variáveis ​​de
Essa matriz serão os pixels, certo?
Tudo bem? Então, cada pixel, por
Por exemplo, pixel 1, pixel 2, pixel 3,
será o nome das variáveis ​​de pixel
Aqui, ok? Pixel. E então continua
de um até o tamanho da imagem
. Muito bom. E isso vai nos devolver o que tínhamos.
então a matriz completa. Muito bom.
Vamos ver. Espero que não seja nada.
mal. Vamos verificar se o nosso
A função está funcionando. E daí
Isso acontece? Quero os dados do carro
aqui. Em seguida, dados do carro. Ops. Não é
É isso que eu quero. Os dados do carro serão
Em seguida, extraia as características. Ir
para então passar o diretório do
carros. Caminho do diretório. O que é o
lista telefônica? Carro, se não for eu
enganado. Que. E a altura e a largura,
Neste caso, a largura é igual à largura.
avaliar corretamente. OK. Vamos ver se funciona.
. Veja aqui o processo do nosso
imagens. Tenho 40 imagens. Espere
Isso funciona. Vamos. Eu não me comprometi
erros. Muito bom. Vejo aqui em cima
Então temos, hum, 40. Eu não vou
Venha nos visitar, pois temos muitos
pixels. Hum, então temos 40 aqui.
observações, ou seja, 40 carros e
2700 variáveis, está bom assim? Então
Vamos fazer o mesmo com os aviões.
. Então os planos de dados serão os mesmos.
Extrair características. O caminho será
Então, planos, direção, largura será
também com a mesma largura que a anterior.
igual à altura. Muito bom, muito bom.
Ele está realizando o processo rapidamente.
OK. Agora temos os dados. O quê não
Temos, portanto temos o valor,
Digamos. Vamos fazer isso aqui mesmo.
só para ver o que é
Nós temos aqui. Resumo. Ah, não, eu não sei.
Vamos. Certo, então vamos agora para
Adicionar as tags está correto?
Por que isso está acontecendo? Eu não tenho o
rótulos para cada valor, ou seja,
o carro e o avião. Então, eu vou
coloque-os. Então, quanto aos carros que eu vou usar...
para dar o valor de zero e para o plano
Vou atribuir o valor de um. OK? Muito
bom. Então, agora temos um
variável. Ei, olha só como nós temos
mais uma variável no final do nosso
quadro de dados, que é, digamos, o valor,
Digamos que queremos saber se é um carro.
Ou é um avião. E nós já sabemos disso. OK?
Muito bom.