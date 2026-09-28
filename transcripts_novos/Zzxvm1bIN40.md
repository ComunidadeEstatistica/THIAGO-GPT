# Alteryx - Unique - Aula 4

- **URL:** https://www.youtube.com/watch?v=Zzxvm1bIN40
- **ID:** Zzxvm1bIN40

## Transcrição

a ferramenta que a gente vai ver agora é
a ferramenta Unic essa ferramenta serve
para que a gente consiga
eh excluir duplicadas dos nossos dados
ou seja linhas que estejam lá duplicadas
que ten os mesmos dados a gente consiga
ficar apenas com uma dessas linhas e
todas as outras que forem iguais a gente
remove dos nossos dados nos nossos dados
aqui a gente tem eh uma primeira coluna
que seria uma numeração do Pokémon em
que a gente consegue ver que tem números
duplicados o restante é diferente mas a
gente tem essa numeração duplicada que
seria para falar de variações de um
Pokémon nesse caso que está fazendo as
variações não interessam a gente quer
saber só dos Pokémons originais Então a
gente vai retirar essas variações
através da eliminação desses números
aqui duplicados eu vou fazer com que
toda vez que ele encontre que o ALX
encontre é um valor duplicado desta
coluna aqui de
hashtag ele vai remover o que for
duplicado como é que a gente vai fazer
isso aqui na aba de preparação se você
não estiver vendo já aqui nessa primeira
nessa primeira parte dela você vai ver
que tem uma setinha aqui na direita em
que você clica e vai aparecer de
ferramentas que tem pro lado então Então
vai aparecer essa aqui que é Unique que
é a ferramenta que a gente vai usar pega
ela arrasta para cá faz a conexão dela
com o data cleansing que é a ferramenta
anterior e você vai ver que por ela
estar selecionada vai aparecer a
configuração da ferramenta nessa
configuração de ferramenta você consegue
selecionar Quais são os campos que ele
vai que o altrex vai utilizar de
referência para saber se uma linha é
duplicada ou não então então você pode
por exemplo clicar aqui em tudo para ele
olhar a linha inteira e comparar com o
todo registo da base se tem outra linha
que tenha todos os valores
iguais ou você pode fazer com apenas um
ou dois ou três ou quantos Campos Você
Quiser ao mesmo tempo no caso eu vou
selecionar só a hashtag que é onde eu
quero mas eu poderia colocar # name e
type One por exemplo para ser a
referência dele se algo é duplicado ou
não vou deixar apenas a
hashtag vou dar um
Run E aí nós vamos perceber que aqui
antes da ferramenta
é de unique clicando nessa seta que
entra nela a gente vê os dados que
entraram nela a gente consegue ver que
entraram 800 dados nela 800 linhas nela
e quando a gente clica nessa saída aqui
nessa tinha u a gente vai estar vendo só
as linhas únicas que saíram Então a
gente vai est vendo que não foram 8
linas que saíram entraram 800 mas saíram
721 por a gente tinha aí 79 linhas que
eram
duplicadas mas o interessante do ALX É
que ele não remove simplesmente essas
linhas Na verdade ele apenas as separa
então quando a gente olha aqui nessa
saída na série de duplicates A a gente
vê todas essas 79 linhas que foram
retiradas da nossa base principal e
assim você consegue se precisar por
algum motivo trabalhar também com essas
linhas que foram duplicadas além das
Linhas únicas o que acontece com as
linhas duplicadas
é é o seguinte quando você tem uma linha
duplicada aqui por exemplo a um dessa
aqui que é o bubassauro quando você
encontra outra linha duplicada aqui
então você tem por exemplo um bubassauro
e um bubassauro
mega você consegue e com o alrex fazer
com que um bubassauro fique aqui que é a
primeira linha que ele encontrou e todas
as outras linhas que ele encontra depois
como por exemplo um buaro mega todas
asas que ele encontra depois da primeira
ele vai jogar pro duplicates então no
único você tem todas as linhas que são
de fato só elas não tem nenhum valor
duplicado E tem também uma amostra de
cada uma das linhas duplicadas que
existem então ele vai sempre ver eh se
existem 5 10 20 de uma mesma linha ele
vai pegar a primeira colocar nessa saída
u e todo o restante ele vai jogar na
saída
D l