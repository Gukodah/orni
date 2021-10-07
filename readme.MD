# Dicionário Técnico e informações

##Tipos de Projetos

###Aplicativo Nativo
>Um aplicativo nativo é um aplicativo construido especificamente para uma determinada plataforma, IOS ou Android.
Esse tipo de aplicativo costuma ser mais performático, porem o seu tempo de desenvolvimento é maior, aliado a um consideravel aumento de custos.

>Linguagens e modelos para aplicativos nativos:
>>Java / Kotlin - Utilizadas para desenvolvimento Android.
>>Swift / Objective-C: Utilizadas para desenvolvimento IOS.

###Aplicativo Híbrido
>Um aplicativo híbrido é um aplicativo construido com foco nas duas plataformas, normalmente o processo de desenvolvimento é mais rápido, e os custos são consideravelmente mais baixos. Os pontos negativos desse tipo de aplicativo é que ele costuma ser mais lento que o nativo,  então o foco do cliente que escolhe esse tipo de projeto não deve ser performance, mas sim interoperabilidade e velocidade de desenvolvimento.
No entanto, diferentemente dos aplicativos ENCAPSULADOS, os aplicativos híbridos possibilitam o acesso a resucursos do sistema do dispotivo movel, como por exemplo a camera ou agenda de contatos.

>####Linguagens e modelos para aplicativos HÍBRIDOS:
>>#####React Native com Expo
>>>Typescript: O typescript é uma linguagem baseada em javascript, de preferencia ela deve ser utilizada em projetos de grande escala, pois dispõe de recursos modernos para organização de estrutura do projeto que o javascript ainda não contempla.

>>>Javascript: O javascript é uma linguagem interpretada, sem tipos fixos, e sem muitos recursos para organização da estrutura do projeto. Ele pode ser utilizado para projetos pequenos, mas não é recomendado para projetos grandes.
Um fator interessante é o tempo de desenvolvimento, e nivel de experiecia que o desenvolvedor responsavel precisara apresentar, ambos os fatores são reduzidos devido ao menor nivel de complexidade dessa linguagem quando compadara com o typescript, por exemplo.

>>>Expo: O expo nada mais é que uma ferramenta para auxiliar no fluxo de trabalho quando se utiliza o framework react native. 
Ele disponibiliza uma serie de recursos, como acesso a interfaces nativas do sistema, e integrações facilitadas com serviços serverless.
Ele tambem possui uma ferramenta prorpria para realizar os testes dos aplicativos desenvolvidos com base nele, o Expo Go.

>>#####Flutter 
>>>O flutter é uma tecnologia disponibilizada pela google, ela segue a mesma linha do react native, porem conta com menos bibliotecas com recursos já desenvolvidos, o que pode acarretar em um acressimo do tempo de desenvolvimento.
>>>Dart: Essa é a linguagem utilizada pelo framework flutter, ela apresenta muita semelhança ao Java.

###Aplicativo Encapsulado
> Um aplicativo encapsulado funcionam como uma especie de navegador WEB, como um container personalizado que carrega um determinado conteudo via HTTP.
Em outras palavras, ele é como um site que pode ser publicado em lojas para aplicativos, e pode possuir um icone personalizado.
>>#####O "Encapsulamento" e as línguagens utilizadas
>>O encapsulamento não é nada alem de uma WebView que vai carregar um WebSite Responsivo, portanto, as línguagem que podem ser utilizadas, são as mais diversas. existem muitas maneiras de se encapsular uma app.
Mas é importante que seja utilizada a palavra chave: ENCAPSULADO.


##O é linguagem e o que não é ?
>> Nem todos os termos que utilizamos para referimo-nos a recursos que vão ser utilizados durante o desenvolvimento de um projeto podem ser considerados linguagens de programação.

>>#####Tabela de Lingaugens(Incluindo linguagens de marcação) e seus respectivos frameworks, fluxos de trabalho e ferramentas e OBJETIVOS.

>>| Javascript/Typescript |      HTML / CSS / JavaScript      |    Java / Kotlin   | Swift / Objective-C |    PHP    |     SQL    |
|:---------------------:|:---------------------------------:|:------------------:|:-------------------:|:---------:|:----------:|
|   Firebase Firestore  |         WebSites diversos         | APP nativo Android |    APP nativo IOS   | WordPress | PostgreSQL |
|   Firebase Functions  |           Encapsulamento          |                    |                     |    API    |    MySQL   |
|     Firebase Auth     | PWA(Progressive Web Application ) |                    |                     |           |            |
|      React Native     |             WordPress             |                    |                     |           |            |
|        React JS       |                                   |                    |                     |           |            |
|         Ionic         |                                   |                    |                     |           |            |
|          API          |                                   |                    |                     |           |            |
|        MongoDB        |                                   |                    |                     |           |            |



##WHM
>O WHM (Web Host Mananger) é uma ferramenta que ultilizamos para gerenciar as os projetos dos clientes, tambem é possivel operar os recursos mais gerais do servidor, como o acesso ao terminal shell, e filas do serviço de email.

>Instruçoes para acessar o WHM: 

>Instruções para acessar o terminal:

>Instruções para acessar terminal remotamente:

>Instruções para gerenciar portas no terminal:

##HLG2
>Servidor de homologação, utilizado para testar os projetos antes de encaminha-los para os clientes.

>instruções para acessar o HLG2:

##CPanel
>O Cpanel é uma ferramenta que utilizamos para gerencias um projeto em especifico, ou seja, ele se apresenta um nivel a baixo do WHM, através dele é possivel gerenciar recursos especificos de cada cliente, por exemplo: contas de email, bancos de dados, acesso FTP, acesso SSH, entre outros. 

>Instruções para criar um conta de email: 

>Instruçoes para acessar o FTP: 

>Instruções para acessar o gerenciador de arquivos da conta:

>Instruções para criar um banco de dados:

##WordPress
>O WordPress é um sistema de gerenciamento de conteúdos, utilizamos ele para gerenciar tanto a estrutura HTML, scripts JS e estilos CSS, quanto os conteúdos pertencentes aos projetos dos clientes.

>Instruções para criar um novo projeto WordPress: 

>Instruções para alterar gerenciar menus no WordPress:

>Instruçoes para gerenciar estilos no WordPress:

>Instruções para conectar o alterar o banco de dados conectado ao WordPress:

##React Native
> O React é um framework de front end, que disponibiliza uma serie de resursos para que sejam desenvolvidas aplicações HÍBRIDAS, existem algumas alterações minimas que precisarão ser realizadas para que uma aplicação desenvolvida neste framework opere 100% em todas as plataformas mobile.

