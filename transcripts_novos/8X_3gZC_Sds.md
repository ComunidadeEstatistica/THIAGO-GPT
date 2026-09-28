# Exploratory Analysis and Cluster Analysis - Prof. Luiz Paulo Fávero

- **URL:** https://www.youtube.com/watch?v=8X_3gZC_Sds
- **ID:** 8X_3gZC_Sds

## Transcrição

Olá a todos, vocês devem estar percebendo que
mesmo fora do trabalho, mesmo
longe do escritório, neste lugar
paraíso, estamos aqui
Compartilhando conteúdo com vocês. O
técnicas curatoriais, também
conhecidas como técnicas agnósticas ou
de interdependência, são orientados
ao tomador de decisões e ao
pesquisador que não pretende
Criar um modelo preditivo. para
outras observações não presentes no
amostra. Em outras palavras, o objetivo
A principal dessas técnicas é
realizar um diagnóstico sobre o
observações que já estão presentes
na amostra e eles não têm a capacidade
preditivo ou inferencial.
Independentemente disso, eles são
técnicas muito úteis para tirar
decisões, porque apresentam capacidade
interpretativo de dados e, mais do que isso
, capacidade de produção de
gráficos e capacidade
interpretação visual. Os resultados
Essas técnicas podem, às vezes, funcionar.
servir como insumos para outros
técnicas confirmatórias ou
inferencial, como, por exemplo,
modelos de regressão, modelos de
regressão logística ou modelos de
Regressão para dados de contagem. O
técnicas exploratórias podem
basicamente divididas em técnicas de
análise de cluster, também
conhecida como análise de
aglomerados ou agrupamentos,
análise fatorial de componentes
pontos principais e análise de
Correspondência simples e múltipla. Ele
A análise de cluster tem como
objetivo principal do grupo
observações que, por algum motivo,
ser semelhantes em relação a certos
critérios e considerações
única e exclusivamente o uso de
variáveis ​​quantitativas para o
classificação das referidas observações.
Imagine então, por exemplo, um
situação em que tenho o objetivo
classificar ou agrupar indivíduos
indivíduos semelhantes que, por exemplo,
Podem ser clientes ou pessoas físicas.
de um banco específico. Imagine isso
Tenho várias variações destas.
clientes, como, por exemplo, idade,
renda familiar média, anos de
escolaridade e, obviamente, variáveis
relacionado ao próprio investimento
dessas pessoas, como o volume
financeiro aplicado em um fundo e o
atividade mensal da conta
atual. todas as variáveis
quantitativo. Porque? Porque eles são
todas as variáveis ​​que eu tenho
condição de extração. Uma medida de
posição, como a média
e uma medida de dispersão, como por exemplo
Por exemplo, o desvio padrão. Pessoas
A primeira coisa a fazer é
precisamente a padronização destes
variáveis, porque elas apresentam unidades
diferente. A idade da pessoa é informada.
em anos e o volume financeiro mudou
O valor mensal é dado em unidades.
monetário, por exemplo, em reais.
Então, nesse sentido, existe um
técnica de padronização bastante
comumente chamados de escores Z,
onde todas as novas variáveis
apresentará uma média de zero e um
desvio padrão de um. Já
A partir desse momento, eu posso então
criar distâncias entre estes
observações baseadas em
critérios utilizados. Lembrando que
Todas essas variáveis ​​são quantitativas.
e a partir deste momento eu posso
Comparar coisas semelhantes é
Em outras palavras, posso inserir todas as variáveis.
Com base no mesmo princípio, média zero,
desvio padrão um, para poder
formar meu grupo de
observações. Lembrando então que
uma vez que a padronização de
As variáveis, o pesquisador tem
condições eficazes para começar
o procedimento de análise de
clusters através da criação de
distâncias entre observações.
Existem muitas distâncias para
variáveis ​​quantitativas, como, por exemplo
Por exemplo, a distância de Mahalanobis,
a distância euclidiana ou a própria distância
Distância quadrática euclidiana. Ele
O pesquisador terá que decidir o quê
distância a utilizar dependendo do
critérios de pesquisa para
efeitos da tomada de decisão. Além do mais
a partir da determinação da distância até
uso em análise de agrupamentos,
o pesquisador também precisa
definir o método de aglomeração
a partir do qual, através de um esquema de
Com a aglomeração, grupos se formarão.
ou agrupamentos, em que cada grupo
conterá certas observações ou
indivíduos, clientes do meu banco
. Feito isso, o pesquisador poderá
avaliar visualmente também o
classificação dessas observações
em grupos, por exemplo, através de um
gráfico chamado dendrograma e também
por meio de mapas perceptuais onde
As observações são colocadas em cada uma.
dos grupos formados. Esses grupos
são resultados da técnica e
representar uma determinada variável
qualitativo, ou seja, não pode
Calcule a média dos grupos.
Essas observações foram registradas em
grupo um ou estaria melhor localizado em
grupo um baseado no
variáveis ​​utilizadas pela similaridade.
Essas outras observações no grupo
dois e assim por diante. Em outras palavras, o
análise de cluster que tem
entrada de variáveis ​​quantitativas, tem
por meio de clusters de saída que representam
variáveis ​​qualitativas e que podem ser
usada em outras técnicas do
que abordaremos em outros vídeos.
levar em consideração exclusivamente e
exclusivamente variáveis ​​qualitativas.
As pessoas são essenciais. Então, o
A análise de agrupamentos possui as seguintes características:
Entrada de variável quantitativa. Bastante
Tenha cuidado com isso. Quais variáveis
quantitativo? Porque deles
Eu calculo as distâncias entre observações.
Distâncias. Qual é a distância?
entre uma pessoa que tem três filhos
E quanto a uma pessoa que tem apenas um filho?
Distância dois. Qual é a distância?
Euclidiano? Por exemplo, entre um
pessoa que tem renda familiar
uma média de 5.000 reais e outra que
tem uma renda familiar média de
3.000, a distância é de 2.000 reais.
Agora, isso não faz absolutamente nenhum sentido.
Ao falar sobre a distância entre variáveis
qualitativo, a menos que um seja feito
ponderação arbitrária, como já vimos.
no primeiro vídeo da série. Aquilo é
Completamente absurdo. O que é o
distância, por exemplo, entre um
uma pessoa que torce para o Flamengo e um
pessoa que vai para São Paulo? Não
Existe distância. Você pode fazer piadas
Nesse aspecto, mas a distância efetiva
entre essas duas categorias disso
variável, neste caso equipe de
O futebol não faz sentido.
Pessoal, eu já vi muita gente fazer isso.
análise de agrupamento para variáveis
qualitativo, atribuindo uma ponderação
arbitrário, tanto na academia quanto
no ambiente empresarial, tanto no
tanto na universidade quanto em empresas. Pessoas
, cuidadoso. Não faça esse tipo de coisa.
ponderação arbitrária. Isto é um
Um erro muito comum na análise de
dados e é um erro muito comum no
Técnica de análise de agrupamentos.
É isso aí, pessoal. Gostei e
Compartilhe este e outros vídeos de
nosso canal. Espero que você esteja bem
Estou gostando bastante e fiquem ligados para as novidades!
publicações. Muito obrigado. Ei