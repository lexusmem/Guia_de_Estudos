# Guia de Estudos

Guia sugerido pelo Fiasco através do Yutube.

> [YouTube Fiasco - Guia de Estudos](https://www.youtube.com/watch?v=A1BaZr82XJI)

## Como Funciona o Computador e a Internet

Devemos entender como a internet está estruturada Protocolos de Rede HTTP/HTTPS/DNS e mais assuntos relacionados ao www e como funciona o computador.

> [Protocolos de Rede](https://medium.com/@christiancost47/protocolos-de-rede-quem-s%C3%A3o-o-que-fazem-onde-vivem-5f7ef43aa526)

> [Pdf - Historia da Internet](https://github.com/lexusmem/Guia_de_Estudos/blob/778b97bbc8172e1b18eba6ec756d4558f597347f/01%20-%20Hist%C3%B3ria%20da%20Internet.pdf)

> [Pdf - Como Funciona a Internet](https://github.com/lexusmem/Guia_de_Estudos/blob/778b97bbc8172e1b18eba6ec756d4558f597347f/02%20-%20Como%20funciona%20a%20Internet.pdf)

Os topico abordados nos itens 1 (Computador) e 2 (Internet) foram com base nos videos do canal do YouTube Curso em Video do apresentador Guanabara.

> [YouTube Guanabara - Internet I](https://youtu.be/F74GKCLXUWM)

> [YouTube Guanabara - Internet II](https://youtu.be/nlO5hySqJFA)

> [YouTube Guanabara - Internet III](https://youtu.be/RFHSt1PCy0k)


**1. Computador**

1.1 **Linguagem da Máquina**

Os computadores são equipamentos eletrônicos, ou seja, significa que funcionam através da eletricidade. Nesse sentido, todos os dados do computador são transportados em minúsculos fluxos de eletricidade, chamados corrente elétrica. Esse processo acontece pelo barramento de dados, nele acontece a troca de dados, sejam eles de entrada ou saída.

E, os microprocessadores possuem milhares ou milhões de pequenos dispositivos eletrônicos, chamados transistores e esses componentes agem como interruptores, controlando o fluxo das correntes elétricas durante o uso do computador. Além disso, os computadores usam essas correntes elétricas para representar os números 0 e 1 (código binário).

Somente esses dois números são utilizados, porque os transistores, assim como os interruptores de luz, possuem apenas duas posições: ligado ou desligado. Dessa forma, o transistor ligado (1) representa um dos números; o desligado (0) representa o outro.

Nossos equipamentos, os computadores, usam séries de 0 e 1 para compor letras, sons e quaisquer outros dados, sendo essa a linguagem pela qual o hardware e software se comunicam. Por exemplo, o computador armazena (Linguagem de Máquina) a palavra dog (“cachorro”, em inglês) desta forma: 01100100 (d), 01101111 (o) e 01100111 (g).

Em outras palavras, os computadores somente leem os números 0 e 1. Portanto, todas as instruções que um computador segue são formadas por séries de combinações desses dois números.

Como não há como padronizar o nível do conhecimento dos usuários, sabe-se que para as pessoas é difícil trabalhar com séries extensas de números. Então, os técnicos que escrevem programas de computador, chamados programadores, criaram suas próprias linguagens que visam converter as linhas de códigos em binários.

1.2 **Codigo Binário**

Máquinas identificam dois estados de acordo com os sinais elétricos, que são o desligado e ligado, o nosso 0 e 1, ou simplesmente o sistema binário

Na computação, toda a informação é processada pela máquina através do código binário, que usa como base o sistema binário para converter os valores 0 e 1 dos pulsos elétricos em informações.

O *binary digit* (dígito binário) é o 1 bit. É a menor unidade de informação do computador. Ela pode ser compartilhada ou armazenada em banco de dados com os valores 0 e 1.

Já o byte, consiste no agrupamento (soma) de 8 bits para facilitar o processo das informações que são enviadas ao computador. Além dele, existem ainda: kilobyte (8.192 bits), megabyte (8.388.608 bits), gigabyte (8.589.934.592) e terabyte (8.796.093.022.208).

Ao observar o termo “binário”, podemos ter uma ideia do que ele é. “Bi” é igual a dois e “nário” significa número. O código binário é composto por dois números, o 0 e o 1. Isso significa que somente esses dois números são usados para representar todos os caracteres do computador, incluindo as letras, caracteres especiais e números.

Então o numero 14 será representando pelo conjunto de número binario `1110`.

~~~~
14(base10) = 1110(base2)

14 / 2 = 7 resto **0**  
7 / 2 = 3 resto **1**  
3 / 2 = **1** resto **1**  
~~~~

E o numero 36 será representando pelo conjunto de número binario `100100`.

~~~~
36(base10) = 100100(base2)

36 / 2 = 18 resto **0**  
18 / 2 = 9 resto **0**  
9 / 2 = 4 resto **1**  
4 / 2 = 2 resto **0**  
2 / 2 = **1** resto **0**  
~~~~

Quando falamos em textos, também podemos criá-los por meio do código binário. Ao usá-lo, podemos formar uma palavra, um livro e até uma mensagem criptografada. Para isso, existe a tabela ASCII — American Standard Code for Information Interchange — criada por Robert W. Bemer. 

Ela tem uma escala que vai de 0 a 127 e cada elemento corresponde a um caractere. Com isso, conseguimos atribuir um valor numérico para as letras, além dos acentos, símbolos e teclas de funções. Porém, ainda é necessário converter os valores da tabela ASCII para o código binário das letras.

> [Tabela ASCII](https://web.fe.up.pt/~ee96100/projecto/Tabela%20ascii.htm)

Para isso, basta utilizar o código da ASCII que corresponde ao caractere em questão. Por exemplo: o **“T”** maiúsculo corresponde ao decimal 84. Então, para convertê-lo para números binários, basta realizar o processo anteriormente, dividindo por 2. Neste caso, o resultado será 1010100.   

**2. Internet**

A internet foi criada em 1969 devido a guerra fria entre EUA e União Soviética. Nos EUA nasceu a ARPANET criada pela DARPA, pequena rede com apenas 4 pontos.  

Internet é a rede mundial é a rede das redes.

Dentro da internet temos servidores especializados em determinados tipos de serviços ou protocolos (FTP, GOPHER, SMTP, POP3, IMAP, HTTP). O WWW - Word Wide Web criada em 1993/1994 é uma sub-rede da internet é a parte da internet especializada em HTTP.

Para acesso a internet precisamos de um modem, ele é responsavel pelo conversão dos sinais entre o computado e a internet. Computador gera/aceita ondas quadradas (binarios) já a internet reconhecem sinais/ondas senoidais a transformação destes sinais é chamada de `modulação` e `demodulação`.

2.1 **IP - Internet Protocol**

O endereço IP é o identificador que permite que as informações sejam enviadas entre dispositivos em uma rede. A Internet precisa de um meio de distinguir diferentes computadores, roteadores e sites. O endereço IP providencia isso, além de ser uma parte essencial do funcionamento da Internet.

Um endereço IP é uma sequência de números separados por pontos. O endereço IP é representado por um conjunto de quatro números: por exemplo, 192.158.1.38. Cada número do conjunto pode variar entre 0 e 255. Ou seja, o intervalo de endereçamento IP vai de 0.0.0.0 a 255.255.255.255.

Os números do endereço IP não são aleatórios. Eles são matematicamente gerados e atribuídos pela IANA (Internet Assigned Numbers Authority, autoridade de números atribuídos à Internet), um departamento da ICANN (Internet Corporation for Assigned Names and Numbers, corporação da Internet para atribuição de nomes e números). A ICANN é uma organização sem fins lucrativos que foi fundada nos Estados Unidos em 1998 para ajudar a manter a segurança da Internet e possibilitar seu uso por todos.

O protocolo de Internet funciona da mesma forma como qualquer outra linguagem, comunicando-se com base em diretrizes definidas para encaminhar informações. Todos os dispositivos encontram, enviam e trocam informações com outros dispositivos conectados usando esse protocolo. Ao falar a mesma linguagem, qualquer computador em qualquer local pode conversar com outro.

Ao acessar um site no navegador através uma URL como por exemplo *github.com* é realizado a busca do endereço do IP registrado nesta URL no servidor DNS para realizar acesso através do IP ao endereço desejado

2.2 **TCP - Transmission Control Protocol**

Protocolo de Controle de Transmissão (do inglês: Transmission Control Protocol, abreviado TCP) é um dos protocolos de comunicação, da camada de transporte da rede de computadores do Modelo OSI, que dão suporte a rede global Internet, verificando se os dados são enviados na sequência correta e sem erros via rede. É complementado pelo protocolo da Internet, normalmente chamado de, TCP/IP.

Neste protocolo da camada de transporte (camada 4 OSI) se assentam a maioria das aplicações cibernéticas, como o SSH, FTP, HTTP — portanto, a World Wide Web, devido sua versatilidade e robustez. O Protocolo de controle de transmissão provê confiabilidade, entrega na sequência correta e verificação de erros dos pacotes de dados, entre os diferentes nós da rede, para a camada de aplicação.

Aplicações que não requerem um serviço de confiabilidade de entrega de pacotes podem se utilizar de protocolos mais simples como o User Datagram Protocol (UDP), que provê um serviço que enfatiza a redução de latência da conexão.

2.3 **Protocolo - TCP/IP**

TCP/IP é um conjunto de protocolos que possibilita a comunicação entre computadores e servidores, formando a Internet. Ele combina o Protocolo de Controle de Transmissão (TCP), responsável pela transmissão de dados, com o Protocolo de Internet (IP), que identificar os computadores e servidores.

Embora apenas dois protocolos estejam evidenciados no nome do TCP/IP, a tecnologia funciona por meio de camadas, que trabalham em conjunto para garantir a transmissão, integridade e segurança dos dados conforme eles viajam pela web.

A divisão do TCP/IP em camadas existe porque, desta forma, a transmissão de dados pode ser padronizada e realizada de modo independente dos dispositivos envolvidos no processo. Isto é, não importa o sistema operacional, a arquitetura do seu processador ou a linguagem de programação envolvida: por ser um modelo padronizado e processado de maneira uniforme, o TCP/IP garante que os dados serão transmitidos da forma correta.

Abaixo, vamos dar uma olhada em cada uma dessas camadas separadamente e vamos falar sobre as suas funções. Em seguida, explicaremos como elas funcionam em conjunto para formar o TCP/IP.

A camada de transporte refere-se ao Protocolo de Controle de Transmissão (TCP) da sigla TCP/IP. Ela é que define como os dados serão transmitidos entre as duas partes do processo (como o seu computador e o servidor no qual um site está hospedado, por exemplo).

Seguindo com o paralelo do serviço postal, a camada de transporte seria a preparação do seu pacote para envio: o serviço define qual meio de transporte será utilizado e como o pacote será embalado para que chegue no seu destino intacto, entre outras medidas.

Para isso, a camada de transporte estabelece os canais de comunicação de transferência de dados, todos eles independentes dos hosts e responsáveis por garantir que cada byte que compõe os dados em questão serão transmitidos de forma íntegra.

É nesta camada que os dados são divididos em pacotes e numerados, criando uma sequência lógica que será verificada nas camadas seguintes para garantir que o processo seja concluído com processo. Além disso, é a camada de transporte que define para onde os dados devem ser enviados e a que taxa essa transferência deve ser realizada.

Para realizar esse processo, o TCP usa as chamadas portas, elementos numéricos que identificam os pontos de uma transferência de dados. As portas são sempre utilizadas em conjunto com um endereço de rede (como o endereço IP, sobre o qual falaremos mais abaixo).

Por serem identificadas numericamente num padrão de 16 bits, as portas vão do 0 até o 65535. Alguns números de portas são universalmente utilizados para determinados processos. Por exemplo:

Porta 20: transferência de dados via FTP  
Porta 21: controle de comando FTP  
Porta 22: login SSH (Secure Shell)  
Porta 25: recebimento de emails via SMTP  
Porta 53: serviço de DNS (Sistema de Nomes de Domínio)  
Porta 80: transferências HTTP  
Porta 443: transferências HTTPS (via TLS/SSL)  

No paralelo com o serviço postal, a camada de rede (IP) — também conhecida como camada de Internet — é responsável por dar o sinal verde final para o envio do seu pacote. 

Em linguagem mais técnica, essa camada lida com as interfaces dos hosts e transforma os pacotes de dados em datagramas. Cada datagrama possui dois componentes principais: um cabeçalho (header), contendo o endereço IP da origem e do destino e outros dados relevantes, e a carga útil (payload), que contém os dados em si que estão sendo enviados.

Aqui, vale fazer a distinção entre IP e endereço IP. IP, ou Protocolo de Internet, é o conjunto de regras e definições que permite que os dados sejam enviados entre computadores e servidores conectados ao redor do mundo. 

O endereço IP, por outro lado, é um elemento específico, utilizado para identificar numericamente cada host envolvido no processo de transferência — garantindo, desta forma, que os dados saiam do lugar certo e cheguem ao lugar certo, da mesma forma que um endereço doméstico para uma transportadora.

Além do protocolo IP, a camada de rede também utiliza o protocolo ICMP (Protocolo de Mensagens de Controle da Internet), responsável por fornecer relatórios de erros às fontes de envio de dados. Desta forma, caso haja algum problema na comunicação entre os hosts, a mensagem definirá qual foi o erro ocorrido e ajustes poderão ser realizados para completar o processo de maneira bem-sucedida.

Como foi possível notar nos tópicos acima, o modelo TCP/IP trabalha com uma pilha de protocolos e processos que ocorrem continuamente, e que podem variar de forma significativa de acordo com o tipo de dado que você está transferindo (um site ou um email, por exemplo), o dispositivo, a arquitetura do sistema, a configuração do servidor, sua conexão com a rede e diversos outros aspectos.

Usemos como exemplo, para ilustrar o trabalho em conjunto das camadas, o envio de um email:

1. Ao clicar no botão “enviar”, a camada de aplicação entende que se trata do envio de um email e aciona o protocolo SMTP, responsável por esse tipo de comunicação.  
2. A camada de transporte divide o conteúdo em pacotes numerados, para garantir a integridade dos dados, e direciona os pacotes para a porta apropriada — no caso de um email, geralmente é a porta 25, mais utilizada para o protocolo SMTP.  
3. A camada de rede transforma os pacotes em datagramas, contendo os endereços IP da origem e destino dos dados, e direciona os datagramas aos servidores de destino.  
4. A camada de interface cuida da transferência dos dados em si, definindo como eles serão enviados — por exemplo, via Wi-Fi, caso seu dispositivo esteja conectado a uma rede sem fio.
5. Ao chegar no servidor de destino, os pacotes são enviados novamente à camada de transporte para serem reorganizados de volta em seu formato original.  
6. Uma vez realizado este processo de remontagem, o email finalmente chega à caixa de entrada do destinatário.  

2.4 **DNS - Domain Name System**

Um serviço DNS é um serviço globalmente distribuído que converte nomes legíveis por humanos, como *www.exemplo.com*, em endereços IP numéricos, como 192.0.2.1, usados pelos computadores para se conectarem entre si.  

O sistema DNS da internet funciona praticamente como uma agenda de telefone ao gerenciar o mapeamento entre nomes e números. Os servidores DNS convertem solicitações de nomes em endereços IP, controlando qual servidor um usuário final alcançará quando digitar um nome de domínio no navegador da web. Essas solicitações são chamadas consultas.

2.5 **HTTP - Hypertext Transfer Protocol**

HTTP é a sigla para Hypertext Transfer Protocol, ou Protocolo de Transferência de Hipertexto. Esse é o principal protocolo responsável pela transferência de dados na Internet, criando as bases necessárias para a conexão entre um cliente e um servidor.

Por isso, o HTTP é um protocolo que funciona no modelo computacional cliente-servidor.

HTTP, cuja primeira versão foi desenvolvida por Tim Berners-Lee — considerado o “pai da Internet” — e sua equipe no CERN (Organização Europeia para a Pesquisa Nuclear) entre 1989 e 1991. O protocolo foi desenvolvido para ser uma camada de aplicação leve e fácil de operar, capaz de ser processado por qualquer máquina ou servidor.

A primeira versão do HTTP, publicada em 1991, não tinha código de versão: posteriormente, ela passou a ser chamada de HTTP/0.9 para diferenciá-la das versões seguintes. Ela continha apenas o básico do protocolo, sem cabeçalhos ou códigos de status.

O HTTP funciona por meio de um modelo de requisição e resposta — ou, em inglês, request and response. 

Em outras palavras, toda a comunicação entre cliente e servidor é realizada através da troca de requisições e respostas: o cliente solicita algum elemento e o servidor responde com aquele elemento (ou algum código de erro, caso ele não seja encontrado).

Cada requisição HTTP contém alguns elementos básicos, tais como:

* A versão HTTP utilizada.
* O URL referente à solicitação HTTP.
* O chamado método (ou verbo) HTTP, que indica a ação principal que será realizada por aquela requisição — dois dos principais métodos HTTP são o GET, que solicita um determinado dado, e o POST, que indica ao servidor o envio de dados do cliente. Esses dados incluem nome de usuário e senha numa tela de login, por exemplo.
* O cabeçalho (header) HTTP, com dados sobre o navegador, cookies e o tipo de dado solicitado
* O corpo (body) HTTP, que é opcional e incorpora informações porventura necessárias para o cumprimento da solicitação.

Já a resposta HTTP é composta basicamente por três elementos:

* O código de status, que indica o status da solicitação HTTP. Ele pode ser um código indicando que a requisição foi bem-sucedida, um código de erro, um código de redirecionamento ou muito mais — falaremos mais sobre isso abaixo.
* O cabeçalho de resposta HTTP, que transmite ao cliente dados sobre o servidor.
* O corpo HTTP, que traz de fato os dados solicitados pela requisição — como, por exemplo, o código HTML que será convertido pelo navegador nas páginas web que você deseja acessar.

2.5.1 *HTTPS - Hypertext Transfer Protocol Secure*

HTTPS significa Hypertext Transfer Protocol Secure, ou Protocolo de Transferência de Hipertexto Seguro. Trata-se do mesmo protocolo HTTP acima explicado, mas com uma camada de criptografia que protege as transferências de dados entre cliente e servidor.

Esse tipo de proteção é importante porque, sem ela, o protocolo HTTP transmite informações em formato de texto simples. Isso significa que um potencial invasor instalado em algum ponto da comunicação (como um malware ou um usuário mal-intencionado conectado à sua rede Wi-Fi) poderá capturar facilmente as informações trocadas — inclusive dados sensíveis, como senhas ou números de cartão de crédito.

Com o HTTPS, a comunicação entre cliente e servidor é criptografada. Ou seja, os dados são codificados na saída e decodificados ao chegar ao seu destino final, por meio de uma chave de criptografia presente apenas nos dois pontos da transferência. Desta forma, mesmo que possíveis invasores consigam capturar os dados trocados, eles não poderão ser decodificados e permanecerão seguros.

Para que o seu site funcione com HTTPS, é necessário obter um certificado SSL (Camada de Soquetes Segura) ou TLS (Segurança na Camada de Transporte). Tecnicamente, o TLS é sucessor do já descontinuado SSL, mas, por costume, a indústria continua utilizando a sigla SSL. Mesmo que, na prática, você esteja obtendo um certificado TLS, mais moderno e seguro.

2.6 **URL**

A URL é o endereço eletrônico que permite que o seu site ou blog seja encontrado na rede. A sigla URL significa: Uniform Resource Locator, e pode ser traduzida para o português como: Localizador Uniforme de Recursos.

A URL como por exemplo *https://www.github.com/lexusmes* são dividas em partes e que cada uma tem o seu significado.

*https://* -> scheme  
*www* -> sub-domínio  
*githug.com* -> domíno  
*.com* -> TLD  
*/lexusmem* -> caminho  

2.6.1 *Scheme*

Chamamos de scheme o protocolo que o servidor web deve usará para acessar a página.

O mais comum para sites e blogs é “https://” e “https://”. O primeiro significa “Hypertest Transfer Protocol”, e o segundo tem a adição da letra S, que representa “Secure” no final.

Basicamente, é a forma de dizer ao servidor “essa é uma página de site, é assim que você deve encará-la”.

O “https” costumava ser usado só em sites que usavam dados confidenciais, mas já é regra até em blogs e páginas que não contém dados tão importantes.

Outros protocolos são “mailto://”, que diz ao servidor para enviar um e-mail para o link em questão e “ftp://”, muito usado para transferir arquivos de um computador para o servidor.

2.6.2 *TLD - Top-level domain*

Um top-level domain é o último segmento do seu nome de domínio, aquele elemento localizado após o último ponto. Como ele fica no final do endereço, ele também é conhecido como sufixo de domínio.

Para esclarecer, vamos analisar por partes o seguinte exemplo de domínio *https://www.github.com/lexusmes*.

Como você pode ver, o top-level domain é *.com* isso mostra que trata-se de um site comercial. Mas como sabemos disso?

Aspectos de domínio, especialmente TLDs, são coordenados pela Corporação da Internet para Atribuição de Nomes e Números (ICANN). A organização supervisiona todos os tipos de top-level domains e com quais sites eles são associados. Como o top-level domain de um website precisa aderir a isso, podemos ver sobre o que é uma página através de seu TLD.

O ICANN classifica os TLDs em quatro categorias principais, com base em fatores do site como propósito, dono e localização geográfica:

*gTLD - Top-level Domain Genérico*

O TLD Genérico é o tipo mais comum que permite que todos os tipos de usuários façam seus registros. Os exemplos mais familiares desse tipo de TLD são:

.com – para sites comerciais.  
.org – para organizações.  
.net – para redes.  
.xyz – para uso geral.  
.name –  para indivíduos.  
.biz – para negócios e empreendimentos em geral.  
.space – para ter seu próprio espaço na web.  
.site – para fazer seu espaço próprio na internet.  
.info – para plataformas de informação.  
.club – para clubes online.  
.tech – para portais de tecnologia.  
.online – para firmar uma presença na internet.  
.co – para corporações e marcas de grande porte.  
.pro – para profissionais de qualquer nicho de mercado.  
.app – para criadores de aplicativos.  
.dev – para desenvolvedores.  
.studio – para artistas, músicos e profissionais da cultura.  
.agency – para agências de qualquer tipo.  
.life – para mostrar seu estilo de vida.  
.blog – para reforçar que você é um blogueiro.  
.cloud – para empresas e negócios na nuvem.  
.link – para o mundo dos negócios conectados.  
.io – para empresas de tecnologia.  
.tv – para entretenimento em geral.  

*sTLD - Top-level Domain Patrocinado*

O sTLD é um tipo genérico de extensão que é operado por organizações privadas. Usuários que querem registrar o seu site sob esse tipo de domínio devem cumprir certas regras. Alguns dos exemplos de Top-level Domain são:

.gov – para sites governamentais.  
.edu – para instituições educacionais.  
.int – para organizações internacionais baseadas em tratados.  
.mil – para o exército dos EUA.  
.mobi – para sites de produtos e serviços mobile.  
.jobs – para companhias e organizações legais.  
.tel – para sites de serviços de comunicação na internet.  
.post – para sites de serviço postal.  
.asia – para sites baseados na região da Ásia-Pacífico.  

*ccTLD - Top-level Domain de Código de País*

O TLD de código de país traz a localização ou o código ISO do território. O código ISO é uma abreviação de duas letras que representa o nome de certas áreas. Exemplos comuns desse tipo de TLD são:

.br – Brasil.  
.es –  Espanha.  
.cc – Ilhas Cocos.  
.ru –  Rússia.  
.us – Estados Unidos.  
.eu – União Europeia.  
.ca –  Canadá.  
.nl – Holanda.  
.de –  Alemanha.  
.fr – França.  
.vc – São Vicente e Granadinas.  
.in – Índia.  
.ch – Suíça.  
.jp – Japão.  
.ai – Anguila.  
.se – Suécia.  
.cn – China.  
.pl – Polônia.  
.id – Indonésia.  
.me – Montenegro.  

*Infrastrutura de Top-Level Domain*

A primeira e única infraestrutura de Top-Level Domain é a ARPA. Ela significa Address and Routing Paramenter Area (Área de Parâmetro de Endereço e Roteamento, numa tradução livre).

Ela é reservada pela IANA para a Internet Engineering Task Force (IETF, ou Força Tarefa de Engenharia da Internet). Portanto, só é usada para resolver problemas técnicos e de infraestrutura.

2.7 **Hospedagem**

Hospedagem de sites (português brasileiro) ou alojamento de sites (português europeu) é um serviço que possibilita a pessoas ou empresas com sistemas online a guardar páginas, arquivos, informações, imagens, vídeo, ou qualquer conteúdo acessível por Web. Provedores de hospedagem de sites tipicamente são empresas que fornecem um espaço em seus servidores e conexão à internet a estes dados aos seus clientes.

Tipicamente, a hospedagem de sites hospeda arquivos 24 horas por dia, em um endereço IP estático, por sua vez, utilizamos um domínio para encontrar com facilidade este site, é muito comum confundir hospedagem de sites com registro de domínio, entretanto, apesar de ambos trabalharem em conjunto, são serviços diferentes.

2.8 **Navegadores**

Um navegador de rede, navegador web, navegador da internet ou simplesmente navegador (em inglês: Web browser, browser), é um programa que habilita seus usuários a interagirem com documentos HTML hospedados em um servidor da rede.

Tim Berners-Lee, que foi um dos pioneiros no uso do hipertexto como forma de compartilhar informações, criou o primeiro navegador, chamado WorldWideWeb (www), em 1990. Mais tarde, para não confundir-se com a própria rede, trocou de nome para Nexus.

A web, entretanto, só explodiu realmente em popularidade com a introdução do NCSA 'Mosaic, que era um navegador gráfico (em oposição a navegadores de modo texto) rodando originalmente no Unix, mas que foi também portado para o Macintosh e Microsoft Windows logo depois. A versão 1.0 foi liberada em setembro de 1993.

## Git e GitHub

Aprender como funciona o Git e Github.

> [Youtube Ignôrancia Zero - Git e Github - Setup](https://youtu.be/alxRKszfTck)

> [Youtube Ignôrancia Zero - Curso Git e Github](https://youtube.com/playlist?list=PLfCKf0-awunORbTiGbKnp7MlkXbT5lk1y)

> [Alex - Comandos básicos para Git Bash](https://github.com/lexusmem/Comandos_Git_Cmd.git)

> [Curso Git e GitHub Guanabara - Curso em Video](https://www.cursoemvideo.com/curso/curso-de-git-e-github/)

## HTML e CSS

Aprender sobre HTML e CSS que são linguagens de marcação.  
Aprender através do curso do Gustavo Guanabara no Youtube.

> [YouTube Guanabara - Curso Html e Css3](https://youtube.com/playlist?list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n)

> [Curso Html e Css3 Guanabara - Curso em Video](https://www.cursoemvideo.com/curso/html5-css3-modulo1/)

Para aprender conceitos basicos de flexbox e grid layout utilizar o site para aprender.

> [Dica - Site desafios Grid e Flexbox](https://codingfantasy.com/games/flexboxadventure)


## Aprender um Framework - Bootstrap

Aprenda sobre uma coleção de estilos pré-definidos ecomponente reutilizaveis através do Bootstrap.

## Cria e Copiar

Nesta fase deve ser criado sites deve tentar copiar sites para treinar tudo que está aprendendo.

> [Dica - Site desafios FrontEnd por nível.](https://www.frontendmentor.io/challenges)

## Lógica de Progamação

Aprender lógica através do Portugol ou junto da linguagem de programação que definir aprender.

> [Curso Guanabara Lógica de Programação - Curso em Video](https://www.cursoemvideo.com/curso/curso-de-algoritmo/)

> [YouTube Guanabara - Curso Lógica Programação](https://youtube.com/playlist?list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n)

> [Curso Lógica de Programação - Alura](https://www.alura.com.br/planos-cursos-online)

## Lingagem de programação

Foi indicado JS (JavaScript) porém não abro mão do Python.

* ## JavaScript  

> [Dica - Site desafios JavaScript.](https://www.jschallenger.com/)

* ## Python

Lista de aprendizado para Python

### **Nível Iniciante:**

**1. Sintaxe básica de Python**

Aprenda a estrutura básica de um programa Python, incluindo variáveis, tipos de dados, operadores e estruturas de controle de fluxo (como condicionais e loops).

> [Python - O Básico da Sintaxe](http://devfuria.com.br/python/sintaxe-basica/)

1.1 ***Declaração de variavéis***

Exemplo:
~~~~Python
    idade = 25  
    nome = "João"
~~~~

Uma variável não pode ser utilizada em uma expressão sem ter sido inicializada.  

Não existe “criação automática” de variáveis.  

Exemplo de atribuição:  

~~~~Python
	reais = euros * taxa
~~~~

As variáveis `euros` e `taxa` devem ser inicializadas, se não o erro `name 'euros' is not defined` será exibido.

Também podemos inicializar mais de uma variável dessa forma:  

~~~~Python
	a, b = 10, 20
~~~~

1.2 ***Valor nulo (null)***

Em Python, "None" equivale ao valor nulo (null).

Podemos iniciar as variáveis com o valor "None".
~~~~Python
reais  =  None
~~~~

**2. Funções em Python**

Entenda como definir e chamar funções em Python.

**3. Listas, tuplas e dicionários em Python**

Familiarize-se com listas, tuplas e dicionários, e aprenda a manipulá-los.

**4. Manipulação de arquivos em Python**

Arquivos e exceções: Aprenda a ler e escrever arquivos, bem como a lidar com exceções em Python.

**5. Importação de módulos em Python**

Módulos e pacotes: Explore a importação de módulos e a organização de código em pacotes.  

### **Nível Intermediário:**

**1. Programação orientada a objetos em Python**  

Aprenda sobre classes, objetos, herança, polimorfismo e encapsulamento.

**2. Explorar módulos padrão do Python**

Explore a biblioteca padrão do Python, que inclui módulos para tarefas como manipulação de strings, operações matemáticas, datas e horas, entre outros.

**3. Manipulação avançada de strings em Python**

Aprofunde-se nas operações de manipulação de strings, formatação e expressões regulares.

**4. Lidar com erros e exceções em Python**

Aprenda a lidar com erros e exceções de forma mais avançada, personalizando as mensagens de erro e utilizando blocos de exceção específicos.

**5. Gerenciamento de arquivos e diretórios em Python**

Aprenda a interagir com arquivos e diretórios usando a biblioteca os e a biblioteca shutil.

### **Nível Avançado:**

**1. Programação funcional em Python**

Explore conceitos como funções lambda, map, filter e reduce para escrever código Python mais conciso e elegante.

**2. Trabalhando com threads e processos em Python**

Aprenda a trabalhar com threads e processos simultâneos em Python para lidar com programação concorrente.

**3. Programação orientada a eventos em Python**

Programação orientada a eventos: Explore bibliotecas como asyncio e Twisted para escrever código assíncrono e lidar com E/S de forma eficiente.

**4. Interagindo com bancos de dados em Python**

Aprenda a interagir com bancos de dados utilizando bibliotecas como SQLite, MySQL ou PostgreSQL.

**5. Frameworks web em Python**

Familiarize-se com frameworks web populares como Flask ou Django para construir aplicativos e APIs da web.  