# As 3 Etapas Para um Bi Perfeito - Parte 2 - Prof. Grimaldo

- **URL:** https://www.youtube.com/watch?v=Ehx_xSUhuNk
- **ID:** Ehx_xSUhuNk

## Transcrição

parecida com a área operacional e copia
seus dados para essa área em chamas
esteja toda vez que você vai carregar
esses dados às cidades são limpos ou
seja toda a manhã
eu faço a transferência do meu
operacional para astrid área então se
dar somente porque são dados que vão
sendo modificadas
se não guarda pessoal da meninada está
servindo só de apoio e depois esse
processo caso venha a cancelar durante
seu processo de carga dormia tele você
pode resultar não se fosse diretamente
no operacional da empresa e isso não
seria possível de assuntos gasto muito
grande bem após ter feito a estrutura de
estagiário você começa a montar o ataque
house e se a data errada dividida em
dois tipos de tabela que você vai ver
daqui a pouco que tem a ver com a
modelagem multidimensional que você vai
construir esses dois tipos de tabela é o
que ele chama de dimensão e fatos
note bem tudo o que você constrói um
projeto de bi área ou seja no processo
de concurso no piauí e na posição do
banco de dados que a nota de rosa vai
necessariamente caindo que a dimensão
até fato tudo que é textual que você vai
utilizar para as suas pesquisas
você quer que eu vou que é necessário
pesquisar então tudo que é textual a
gente constrói em tabelas de banco de
dados uma dimensão por exemplo o cliente
informações de produto tipo de embalagem
e um dado bem específico importante que
você não pode esquecer jamais que a
informação de tempo ou seja eu vou
formular uma pergunta aqui pra que você
perceba o quanto é importante dos
clientes compraram tipo de embalagem
plástica e plástica do produto
pipoca vamos dizer assim no ano de 2015
note que você sempre determina uma
estrutura de tempo para relatar isso se
não tivesse o tempo você dizer quais são
os clientes que compram tipo de
embalagem plástica do produto pipoca
não faz muito sentido mas qual ano no
qual semestre e com o mês porque a
relação é sempre analisada por um
período você tem que analisar essas
anormalidades então a tempo
é uma estrutura de dados
lá onde você guarda informações que
realmente identificam quando foi
utilizado
aquele dado então toda dimensão guarda
das prisões textuais já fato não há
falta utilizada para medição seu negócio
a produção informa soldados onde você
vai guardar métricas valores por exemplo
a quantidade de produtos vendidos
o iphone os valores de compra for
efetuada os valores de venda dos lucros
que foram votar ou seja os dados
quantitativos e eu posso fazer uma
pergunta que cruzando dimensão em faro
quantas vendas foram efetuadas e 15 da
linha de produto é branca na região de
salvador
note o a ferramenta que é a construção
do house vai permitir com que você chega
essa informação de forma rápida como
através da modelagem específicas está
vendo esse formato de cuba que é a
construção do modelo multidimensional
que acelera a pesquisa em bancos de
dados tradicionais você tem a leitura de
tabelas através de junções de
relacionamentos aqui dentro da estrutura
muito nacional através da estrutura de
células então na verdade as informações
e região linha de produtos tempo ea
venda que foi apurada daquele período
estão guardadas em um único lugar
ou seja quadra a quadra com a cada
quadradinho de se apresentam às quatro
informações juntas se aceleram seus
dados
e aí a informação chega mais rápido ao
gestor
então pra isso fui construindo o projeto
e da tele house para que desse
aceleração na pesquisa dos dados bem pra
que você faça a construção das dimensões
da faca você tem que fazer um modelo
eficiente que fica aquele modelo que vai
gerenciar aquele cuba aquele cubo que
acelera a pesquisa tem dois tipos de
modelo quando você trabalha com projetos
e b ae
e na condição de tratar e aos que são os
modelos está esquema snow flake a que
seus quadris menores são as dimensões e
esse quadril sim
ao maior é quem chama da fapa seja as
métricas ligada aos de escritores no
modelo flec
você tem a mesma informação só que
tabelas dimensões ligadas a outras
tabelas de dimensões o que acontece
quando você se aproxima do modelo de
relacionamento entre as tabelas você
volta para um paradigma operacional e no
paradigma operação novas empresas a
leitura e tabelas fazendo junções o
chamado de joyce é muito lento não se
aquilo fosse rápido não se precisava
construir projetos de data warehouse
então você deve evitar a concessão de
snow flakes que a ligação entre
dimensões e sempre dá prioridade para
moderar os modelos está esquema bem aqui
é um exemplo você pode construir as
dimensões estão aqui na periferia ea
parte central é a parte das metas é a
falta tão dimensões ea fap há tempos
sempre presente
note aqui um exemplo bem tranqüilo de
uma estrutura de carga e um modelo multi
dimensional temos arquivos operacionais
que vão para a estagiária leitura da
estréia de vinheta ela grava no modelo
multi dimensional como é que
operacionalizar isso bem aqui um exemplo
do modelo operacional que a gente está
destacando que o modelo de vendas onde
eu tenho várias tabelas operacionais
periféricas como é que o transforma esse
modelo operacional para que seja
eficiente na coxa são de natalie house
simplesmente vou aplicar uma modelagem
está esquema ou modelagens no fly e se
for está esquema ela será da seguinte
forma eu tenho as métricas aqui no caso
de vendas quantidade e valor do item
eu tenho as ligações com as dimensões
norte e eu tenho essas funções pelo que
chama de chávez a fisciais ufrgs quis
porque porque no processo de construção
de um data e house
você tem uma estrutura de tempo que
guarda o histórico dos dados
então para guardar o histórico dos dados
você vai usar chaves artificiais para
evitar duplicação dos dados
então aqui no caso
tabela de cliente onde você tem
operacional dividida em 5 você vai fazer
a junção e guardar uma chave artificial
para que seja ligado à tabela fato
então este é o processo de construção eo
modelo de universo multidimensional de
uma tabela fato central e as dimensões
de formas periféricas
já no modelo snow flake você tem a mesma
coisa na tabela central e os fatos
já as favelas dimensões se ligam a
outras abrange dimensões no caso
anterior a gente tinha tipo de cliente
inserido dentro da tabela cliente agora
separar em duas tabelas
esse modelo é extremamente mais lento do
que o modelo está esquema então é vítima
essas funções porque isso deixa a
estrutura dos dados não é carregada e
você não consegue dar eficiência seu
modelo nem da velocidade para que os
gestores possam consultar os dados bem
no processo de construção você deve
seguir algumas etapas
é importante que você siga essas etapas
e essa etapa não é uma forma aleatória
uma forma seqüencial que você tem que
seguir a primeira coisa que você tem que
fazer é trazer os dados esses dados são
importados através da ferramenta é ele
pode ser em qualquer