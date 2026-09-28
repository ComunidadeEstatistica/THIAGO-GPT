# Data Lake - Prof  David Braga - Parte 1

- **URL:** https://www.youtube.com/watch?v=shnrcCakV7M
- **ID:** shnrcCakV7M

## Transcrição

olá pessoal tudo bem meu nome é david
braga
é com grande prazer que eu apresento a
vocês tá é eu tenho uma parceria com
tiago pra trazer para o canal está
difícil a conteúdos relativos à big data
a integração de ambientes a adul pe
coisas desse universo está a minha meta
com vocês também vai ser é tentar
renovar o máximo com essas atualizações
com esses avanços tecnológicos tenha
ocorrido no mercado
vamos ver se conseguimos com gerar
conteúdos integrando é assuntos como
datas assuntos como a china ou em
assuntos como o tiro coisas desse tipo
que eu acho também levante bem bacana
também disse compartilhar eu sou um
grande crente que nossa maior chave hoje
de mudança de melhoria na nossa vida é o
compartilhamento e as parcerias por
conta disso agradeço muito o feedback de
vocês todos todas as ajudas e os apoios
que vocês derem vou ficar muito feliz
está o que eu mais vou buscar aqui
trazem conteúdos relevantes e de formas
objetivas que eu não traga nada muito
extenso e que seja realmente é que
realmente agregue a vocês muito obrigado
fico muito feliz de participar desse
canal que tem a certeza que ajuda muitas
pessoas podem contar comigo muito
obrigado
olá pessoal é então conforme eu combinei
com algumas pessoas é muito obrigado
primeiramente pelo feedback tá é que foi
dado o passado pelo canal 7 físico é
agradeço realmente ranking tentou
assistir os primeiros vídeos pois o
áudio estava muito ruim estava na época
sem microfone e peça desculpas pela
qualidade porque a minha meta foi levar
um conteúdo que agregasse ao máximo mas
sem o áudio nítido fica difícil mesmo eu
também sou um uma pessoa que gosta de de
entender o que estou indo da melhor
maneira possível e influencia bastante é
nos próximos conteúdos vôo
sempre para buscar uma qualidade técnica
energia de de de som e imagem pra
fortalecer todos aí
muito obrigado a ver o pessoal
primeiramente é isso que eu gostaria
então vamos refazer essa essa essa aula
tá ou até mesmo tentar ser mais
pragmático então vamos começar que seria
o data lei que tá pessoal data lei que
ele é conhecido no mercado
pô por assim por ser umas teoricamente o
da telecheque
muitos confundem com um conceito mas ele
não é um conceito o data lei que é uma
estratégia para abordagem de dados então
o data lake ele ele contempla todo todo
o universo de de armazenamento que você
define na sua arquitetura como é é como
aderente à navegação de seus dados
então por exemplo é ele pode ser
abrangente a a mais de uma tecnologia a
diversos ambientes integrados então eu
posso sim ter 11 tem uma base oracle
integrada com histórias de cloud dentro
de uma google de uma amazon e isso
também integrado com alguma outra
ferramenta como um bico ir e como alguma
outra ferramenta de consumo
então eu posso fazer é um desenho de
arquitetura demonstrando uma solução que
é que permeia por entre esses ambientes
definindo como meu data lake o que quais
são as características normalmente
utilizadas para padronização e para a
aplicação de governança c e e
metodologias é é muito utilizado o
segregações lógicas que são segregações
lógica são definições de camadas e d e e
organização da de diretórios e
organização de dados está então o que o
quanto eu quero dizer um
agregação lógica eu o normalmente eu
detalhe camadas onde se nada é onde
esses dados vão navegar e vão é é ser
transformados nossa evoluídos né então
contudo com todo esse contexto é eu vou
detalhar para vocês aqui uma forma
didática o fluxo de de uma de uma
aplicação de uma implementação de data
letta
então digamos que o nosso cliente é
queira adicionar uma estratégia em todos
nessa organização
pra começar a utilizar é é é melhores
práticas e conceitos de metodologia de
governança pra aplicar sobre seu
ambiente atual então ele inicialmente
faz uma definir quais são as suas fontes
do nosso lado esquerdo vamos ter um
quadradinho com as fontes de dados
detalhando algumas algumas redes sociais
como facebook twitter
iremos também embarca nessa gestões
arquivos manuais e arquivos gerados por
humanos e bases relacionais e ii na
nuvem né então teremos aqui as contas
por foram é é definidas
o segundo passo é definirmos a
tecnologia de armazenamento como
contextualiza inicialmente é possível
que essa essa abrangência ocorra para
mais de um ambiente ou para mais de uma
tecnologia no nosso caso vamos é é
utilizar uma estratégia que está sendo
bem difundida que é eleger uma uma
tecnologia de suporte e que tem um
custo-benefício é bem relevante e aí
iremos aplicar a nossa a nossa a etapa
de camadas da nossa ligação lógica então
elegemos a tecnologia de armazenamento é
e aí a primeira a primeira fase é
definir a camada de esteja camada de
esteja é podem se dar vários nomes
normalmente no mercado é conhecido como
raul deita é então temos diversas é
homem de cultura está aqui no meu caso
eu vou definir como esteje que vai ser a
camada de repouso
então eu vou aplicar scripts ou utilizar
tecnologias que vão fazer a ingestão
desses dados
dentro dessa minha dessa minha estrutura
de armazenamento então a minha primeira
camada de utilização vai ser a câmara
esteja camada de pouso dos meus dados
depois disso é a gente navega estrutura
esses dados que antes chegaram de forma
bruta eles chegaram com diversos tipos
diversos formatos não foram tratados não
foram feito nenhum tipo de transformação
eles apenas são gravados dentro dessa
dessa estrutura é e depois a gente vai
precisar estruturar esses dados então
por exemplo se entra assim um arquivo
xml estruturado é necessário fazer uma
adequação e uma estruturação desse cara
em formato tabular para aquele permeie e
pra que ele evolua dentro da nossa da
nossa estratégia de dados
então pra isso a gente aplique aplicaria
algum tipo de script algum tipo de
mecanismo é utilizado em alguma
tecnologia que possibilitasse essa
transformação essa estruturação
então a gente vai ter a a as tecnologias
são ingeridas na esteje pousando dentro
dentro da já nossa estrutura de
armazenamento e sendo transformados
agora para uma camada que a gente não
melhorar aqui nomeou aqui como dados
brutos
depois é dentro dessa navegação é vimos
o cliente solicitou que a gente
refinasse um pouco esses dados então
quando a gente fala de consolidados são
dados refinados dados que já foram
aplicadas algumas regras de negócio a
área de negócio já solicitou que
adaptassem que criasse alguns campos
enriquecidos que fossem consolidado
algumas informações que antes estavam
duplicadas
a gente já é mineiro e já e já refinou
essa informação
então dentro dessa camada de dados
consolidados já temos é os dados mas vê
mais considerados verdade que é que a
organização poderia ter
tanto pra pra uso pra consumos de
dashboards para consumos de de da tensai
está então é bem é bem abrangente essa
essa camada nossa quarta camada dentro
da nossa arquitetura esperada
que fofo que inicialmente planejarmos
seriam dados prontos
meu nome é esse eu desci as
nomenclaturas bem sugestivas está a fim
mesmo de de facilitar o entendimento
dessa navegação
normalmente o pessoal utiliza target
works é nomes mais mais voltado às boas
práticas e até mesmo indicações de de
metodologias de processamento de de
governança tá é o que seria nossa camada
de dados brutos a camada de dados brutos
são a camada que já se aplicam
agregações sumariza ações já são
aplicadas dimensionamentos então é nesta
camada que executamos é é toda essa essa
essa definição do dado é aqui
normalmente onde a gente já consegue
definir todas as dimensões e
visualizações de um de uma informação e
pode prover e e alimentar dashboards é é
áreas usuárias e diretorias coisas desse
tipo
é nesse primeiro vídeo eu vou parar
nessa nessa primeira pasta então a gente
já entendeu é as fontes a uma ingestão
em lote está a gente está falando aqui
de um piper laine em lote que seria é de
forma periódica essas execuções seriam
esquerdo lados agendadas em determinei
para cada para cada tipo de arquivo
superou-se sua periodicidade é distinta
mas ela não executa em tempo real não
extreme então está faltando de um lote e
essa navegação pelos da pelas camadas já
estão ocorrendo transformações
enriquecimento consolidações e
refinamento tá então vamos depois para a
parte 2 muito obrigado pessoal