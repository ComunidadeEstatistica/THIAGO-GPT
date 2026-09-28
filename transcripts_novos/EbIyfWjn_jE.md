# Baixar Dados da B3 de forma fácil com R e pacote GetDFPData2 - Leonardo Chalhoub (Mestre ADM UFPGS)

- **URL:** https://www.youtube.com/watch?v=EbIyfWjn_jE
- **ID:** EbIyfWjn_jE

## Transcrição

Olá amigos boa tarde eu sou Leonardo
chalhoub tenho mestrado em Finanças e
vim aqui para dar uma força para quem
gosta de mexer com dados
eh um ex-professor meu e outros colegas
criar uma ferramenta no R chamado pacote
getd FP
data que é excelente e você tem como
pegar tudo da bolsa rapidamente tudo
tudo tudo tudo eh
Já tem alguns vídeos mostrando aí o get
dfp data 1 só que esse primeiro ele era
mais lento e tinha algumas limitações
como por exemplo somente ter a
possibilidade de frequência
anual o pessoal que fez o pacote né o
professor Marcelo perlin o Daniel vancin
Doutor fizeram agora uma segunda versão
o get dfp Data 2 aonde você consegue os
dados de uma forma bem mais rápida
e você consegue escolher entre a
frequência anual ou
trimestral então eu vou mostrar para
vocês
aqui que se você colocar get dfp Data 2
no Google já aparece ali ó o repositório
do professor perlin no
github na primeira opção tá aqui toda a
documentação do getdp datata 2
para você usar
ele você precisa
e
instalar o Dev Tools completo certo e
depois passar esse comando aqui porque
ele ainda não tá no cran então ele vai
pegar direto aqui do
github e aqui tá o código é muito
tranquilo você vai precisar não só
instalar ele né como também instalar o
Tide
verse e eu vou mostrar para vocês como
isso fica aqui no R primeiro eu vou
mostrar o resultado final e depois eu
vou mostrar como se faz vai ser um vídeo
curto Olha só eu rodei aqui paraas para
informações trimestrais tá então me
gerou aqui um
dataframe aqui que eu tenho o ativo
passivo o DRE consolidado de todas as
empresas da B3 de 2018 a 2020 período
que eu escolhi aleatoriamente para ser
curto
mesmo se você clicar aqui por exemplo no
ativo você tem acesso a tudo olha que
maravilha ó conta um ativo Total ativo
circulante caixa equivalente de caixa
isso para cada trimestre para cada
empresa ou seja você com isso aqui na
mão é só exportar para para Excel
dependendo do uso que você for ter Ou
você já manipula aqui dentro do R mesmo
é muito muito interessante e agora eu
vou mostrar para vocês como se faz ó eu
vou aqui na
vassourinha jogar tudo fora você
carrega você carrega aqui os
pacotes você com esse comando Aqui DF
info
compies você já vai pegar um Data Frame
eu vou mostrar PR vocês com as
informações das empresas olha só que
legal mas não as informações
contábeis ó todas as empresas o
setor ó o CNPJ do auditor o
endereço telefone o e-mail lá do do
responsável
Tem tudo aqui ó a o e-mail do diretor de
relações né Ó tem tudo é coisa querida
mesmo ó o telefone ó quer procurar
emprego começa a ligar aí
irmão depois
disso a gente pode usar o DF search
Company se a gente quiser só uma empresa
em específico ou um conjunto pequeno de
empresas mas isso normalmente Não serve
né a gente quer tudo então para colocar
tudo é só vir aqui nesse próximo comando
que é o id cvm e colocar
nul aqui se você colocar o DF search ele
vai pegar os
dados só da daquelas empresas se você
colocar nul ele vai pegar todas E aí
embaixo vem o comando aqui para gerar o
dataframe l ITR aqui tá na frequência
trimestral que esse comando aqui o get
ITR data ele é muito simples na
documentação aqui
do do pacote é muito fácil você entender
tá como ele funciona eu deixo pros
interessados aí que Visit o
site e ó ao rodar isso aqui eu já vou
ter tudo vamos
testar ele vai demorar uns minutinhos
mas esse pacote o get dfp Data 2 é muito
mais rápido que o get D FP data
1
e a gente já tá quase concluindo aqui
embaixo ó é a mesma coisa só que isso
aqui é para frequência anual né Às vezes
a pessoa não quer trimestre quer o anual
então é a mesma coisa só que em vez de
ser o get TR data vai ser o get dfp
data Então eu só vou esperar terminar de
baixar tudo
e vou mostrar para vocês o dataframe e
acabou o vídeo e eu desejo pros
pesquisadores que sejam ajudados por
esse humilde vídeo que a sua
produtividade aumente muito antigamente
há poucos anos atrás a coleta de dados
era um
problema aparentemente Isso
acabou vamos esperar um pouco
botar um reg né PR gente esperar com
calma
[Música]
aí OK depois de alguns minutos chegou
tudo e agora eu tenho aqui ó o Data
Frame L que foi o que eu pedi quando eu
clico nele o que que aparece o que vocês
viram no início do vídeo ó o ativo
passivo dre
é coisa linda ó clicando aqui você tem
acesso a tudo aqui tá o
dre das empresas ó item por item
trimestre a trimestre começando aí com a
Eletrobras
ó certinho na ordem Ó
receita custo resultado bruto tá aqui os
números ó ó cada coluna tem
tudo então meus
amigos eu espero que esse vídeo tenha
ajudado eu espero que isso seja útil
para quem gosta de mexer com dados é
muito prático é muito fácil
é coisa top e
grátis obrigado um grande abraço e até a
próxima