# Guia de Estudos

Guia sugerido pelo Fiasco através do Youtube.

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

1.2 **Código Binário**

Máquinas identificam dois estados de acordo com os sinais elétricos, que são o desligado e ligado, o nosso 0 e 1, ou simplesmente o sistema binário

Na computação, toda a informação é processada pela máquina através do código binário, que usa como base o sistema binário para converter os valores 0 e 1 dos pulsos elétricos em informações.

O *binary digit* (dígito binário) é o 1 bit. É a menor unidade de informação do computador. Ela pode ser compartilhada ou armazenada em banco de dados com os valores 0 e 1.

Já o byte, consiste no agrupamento (soma) de 8 bits para facilitar o processo das informações que são enviadas ao computador. Além dele, existem ainda: kilobyte (8.192 bits), megabyte (8.388.608 bits), gigabyte (8.589.934.592) e terabyte (8.796.093.022.208).

Ao observar o termo “binário”, podemos ter uma ideia do que ele é. “Bi” é igual a dois e “nário” significa número. O código binário é composto por dois números, o 0 e o 1. Isso significa que somente esses dois números são usados para representar todos os caracteres do computador, incluindo as letras, caracteres especiais e números.

Então o numero 14 será representando pelo conjunto de número binário `1110`.

~~~~
14(base10) = 1110(base2)

14 / 2 = 7 resto **0**  
7 / 2 = 3 resto **1**  
3 / 2 = **1** resto **1**  
~~~~

E o numero 36 será representando pelo conjunto de número binário `100100`.

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

Para acesso a internet precisamos de um modem, ele é responsável pelo conversão dos sinais entre o computado e a internet. Computador gera/aceita ondas quadradas (binários) já a internet reconhecem sinais/ondas senoidais a transformação destes sinais é chamada de `modulação` e `demodulação`.

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
*githug.com* -> domínio  
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

*Infraestrutura de Top-Level Domain*

A primeira e única infraestrutura de Top-Level Domain é a ARPA. Ela significa Address and Routing Paramenter Area (Área de Parâmetro de Endereço e Roteamento, numa tradução livre).

Ela é reservada pela IANA para a Internet Engineering Task Force (IETF, ou Força Tarefa de Engenharia da Internet). Portanto, só é usada para resolver problemas técnicos e de infraestrutura.

2.7 **Hospedagem**

Hospedagem de sites (português brasileiro) ou alojamento de sites (português europeu) é um serviço que possibilita a pessoas ou empresas com sistemas online a guardar páginas, arquivos, informações, imagens, vídeo, ou qualquer conteúdo acessível por Web. Provedores de hospedagem de sites tipicamente são empresas que fornecem um espaço em seus servidores e conexão à internet a estes dados aos seus clientes.

Tipicamente, a hospedagem de sites hospeda arquivos 24 horas por dia, em um endereço IP estático, por sua vez, utilizamos um domínio para encontrar com facilidade este site, é muito comum confundir hospedagem de sites com registro de domínio, entretanto, apesar de ambos trabalharem em conjunto, são serviços diferentes.

2.8 **Navegadores**

Um navegador de rede, navegador web, navegador da internet ou simplesmente navegador (em inglês: Web browser, browser), é um programa que habilita seus usuários a interagirem com documentos HTML hospedados em um servidor da rede.

Tim Berners-Lee, que foi um dos pioneiros no uso do hipertexto como forma de compartilhar informações, criou o primeiro navegador, chamado WorldWideWeb (www), em 1990. Mais tarde, para não confundir-se com a própria rede, trocou de nome para Nexus.

A web, entretanto, só explodiu realmente em popularidade com a introdução do NCSA 'Mosaic, que era um navegador gráfico (em oposição a navegadores de modo texto) rodando originalmente no Unix, mas que foi também portado para o Macintosh e Microsoft Windows logo depois. A versão 1.0 foi liberada em setembro de 1993.

## Lógica de Programação

Lógica de programação (ou, por extensão, lógica computacional) é uma forma de organizar pensamentos que permite a tradução do raciocínio lógico humano para a linguagem das máquinas, permitindo que elas realizem alguma determinada tarefa.

Lógica de Programação é uma técnica que permite você desenvolver uma sequência de instruções que visam atingir um determinado objetivo.

Isso quer dizer que, dentro da lógica de programação, você possui diversos conceitos que te permitirão escrever instruções, em forma de algoritmos, que irão guiar a máquina a fazer o que você desejar.

1. **Algorítimo**

 algoritmo é a própria sequência de instruções que irão permitir você atingir seu objetivo. Ela basicamente é o mapa, roteiro, guia que vai permitir a máquina compreender o que deve ser feito.

É possível pegar qualquer coisa que a gente faz cotidianamente e transformar em um algoritmo. Basta entender os processos realizados e conseguimos criá-lo. Vamos tomar como exemplo fazer um pão com manteiga para seu café da manhã.

~~~~
Fazer um pão com manteiga*  
Início  
 1. Pegue 1 pão  
 2. Pegue uma faca  
 3. Abra o pão ao meio utilizando a faca  
 4. Pegue o pote de manteiga  
 5. Abra o pote de manteiga  
 6. Use a faca para passar a manteiga na parte interna do pão  
 7. Feche o pote de manteiga  
 8. Feche o pão  
 9. Sirva o pão  
Fim
~~~~

2. **Tipo de Dados**

Um tipo de dado nada mais que é algo do mundo real que pode ser representado computacionalmente. Por exemplo, os números que pertencem ao conjunto dos números inteiros, os números que pertencem ao conjunto dos números reais, letras, caracteres especiais, acentuação, pontuação, palavras, etc.

As linguagens de programação implementam formas de representar e manipular esses dados, que podem ser classificados em dois grandes grupos: os tipos de dados primitivos e os tipos de dados não primitivos.

2.2 **Tipo de Dados Primitivos**

Os tipos de dados primitivos são os tipos básicos que devem ser implementados por todas as linguagens de programação, como os números reais, inteiros, booleanos, caracteres e strings.

*Inteiros*

int - para números inteiros

*Float*

float - para números fracionado

*Booleanos*

bool - armazena True ou False

*Strings*

str - para conjunto de caracteres

2.3 **Tipo de Dados Não Primitivos**

Os tipos de dados não primitivos, normalmente são os vetores, matrizes, classes, enumerações, etc., que costumam ser estruturas de dados mais complexas do que os tipos de dados primitivos.

*Vetor*

Um vetor é uma variável composta unidimensional formada por uma sequência de variáveis, todas do mesmo tipo, com o mesmo nome e alocadas sequencialmente na memória. Uma vez que as variáveis têm o mesmo nome, o que as distingue é um índice, que referencia sua localização dentro da estrutura.

Em python é chamado de `lista`.

~~~~python
lista_python = ['banana','laranja','maçã']
~~~~

Uma matriz é uma coleção de variáveis de mesmo tipo, com mesmo nome e alocadas sequencialmente na memória. Uma vez tendo o mesmo nome, o que as distingue são índices que referenciam sua localização dentro da estrutura.

As matrizes podem ser tanto unidimensionais (vetores) como multidimensionais.

Em python as matrizes são demonstradas com `listas` dentro de `listas`

~~~~python
linhas = [0]*5
print(linhas)
colunas= [linhas] * 5
print(colunas)
~~~~

3. **Variáveis e Constantes**

Programas de computador utilizam os recursos de hardware mais básicos para executar algoritmos. Enquanto o processador executa os cálculos, a memória é responsável por armazenar dados e servi-los ao processador.

O recurso que nós utilizamos em nossos programas para escrever e ler dados da memória do computador é conhecido como variável, que é simplesmente ***um espaço na memória o qual reservamos e damos um nome***. Por exemplo, podemos criar uma variável chamada “idade” para armazenar a idade de uma pessoa.

Você pode imaginar uma variável como uma gaveta “etiquetada” em um armário.

Chamamos este espaço alocado na memória de variável, porque o valor armazenado neste espaço de memória pode ser alterado ao longo do tempo, ou seja, o valor ali alocado é “variável” ao longo do tempo. Diferente das ***constantes***, que é um espaço reservado na memória para armazenar um valor que não muda com o tempo. Por exemplo, o valor PI (3.14159265359…) que nunca vai mudar.

4. **Declaração de Variáveis**

Declarar uma variável significa informar ao computador que reserve um espaço na memória para armazenar um determinado tipo de dado e que este espaço será identificado por um nome. Exemplo em pseudocódigo:

~~~~
x: inteiro
x = 10
~~~~
Em Python, você não precisa declarar explicitamente o tipo de uma variável. Basta atribuir um valor a ela para criar uma variável. O tipo é inferido automaticamente.

5. **Estruturas de Controle**

São mecanismos utilizados para controlar o fluxo de execução do programa.

As principais estruturas são:

5.1 **Estruturas condicionais**

Permitem tomar decisões com base em condições.

Exemplos de estruturas condicionais são o "if", "else" e "switch case".

5.2 **Estruturas de repetição**

Permitem repetir um conjunto de instruções várias vezes.

Exemplos de estruturas de repetição são o "for", "while" e "do-while".

6. **Funções**

Uma função é um bloco de código que executa alguma operação. Opcionalmente, uma função pode definir parâmetros de entrada que permitem que os chamadores passem argumentos para a função. Uma função também pode retornar um valor como saída. As funções são úteis para encapsular operações comuns em um só bloco reutilizável, idealmente com um nome que descreve de modo claro o que a função faz.

Funções em Python são definidas por meio da seguinte sintaxe:

~~~~python
def nomedafuncao(parametro1, parametro2, ...):
    corpodafuncao
~~~~

> [Curso Guanabara Lógica de Programação - Curso em Video](https://www.cursoemvideo.com/curso/curso-de-algoritmo/)

> [YouTube Guanabara - Curso Lógica Programação](https://youtube.com/playlist?list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n)

> [Curso Lógica de Programação - Alura](https://www.alura.com.br/planos-cursos-online)

> [O que é lógica de Programação](https://medium.com/interage/logica-de-programacao-o-basico-para-voce-comecar-a-programar-1dd50d981698)

## Git e GitHub

1. **Git**

É um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo (Exemplo: alguns livros digitais são disponibilizados no GitHub e escrito aos poucos publicamente). O Git foi inicialmente projetado e desenvolvido por Linus Torvalds para o desenvolvimento do kernel Linux, mas foi adotado por muitos outros projetos.

Cada diretório de trabalho do Git é um repositório com um histórico completo e habilidade total de acompanhamento das revisões, não dependente de acesso a uma rede ou a um servidor central. O Git também facilita a reprodutibilidade científica em uma ampla gama de disciplinas, da ecologia à bioinformática, arqueologia à zoologia.

O Git é um software livre, distribuído sob os termos da versão 2 da GNU General Public License. Sua manutenção é atualmente supervisionada por Junio Hamano.

2. **GitHub**

É uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. GitHub é amplamente utilizado por programadores para divulgação de seus trabalhos ou para que outros programadores contribuam com o projeto, além de promover fácil comunicação através de recursos que relatam problemas ou misturam repositórios remotos (issues, pull request).

> [Youtube Ignorância Zero - Git e Github - Setup](https://youtu.be/alxRKszfTck)

> [Youtube Ignorância Zero - Curso Git e Github](https://youtube.com/playlist?list=PLfCKf0-awunORbTiGbKnp7MlkXbT5lk1y)

> [Curso Git e GitHub Guanabara - Curso em Video](https://www.cursoemvideo.com/curso/curso-de-git-e-github/)

> [Alex - Comandos básicos para Git Bash](https://github.com/lexusmem/Comandos_Git_Cmd.git)

## HTML e CSS

Aprender sobre HTML e CSS que são linguagens de marcação.  
Aprender através do curso do Gustavo Guanabara no Youtube.

> [YouTube Guanabara - Curso Html e Css3](https://youtube.com/playlist?list=PLHz_AreHm4dkZ9-atkcmcBaMZdmLHft8n)

> [Curso Html e Css3 Guanabara - Curso em Video](https://www.cursoemvideo.com/curso/html5-css3-modulo1/)

Para aprender conceitos básicos de flexbox e grid layout utilizar o site para aprender.

> [Dica - Site desafios Grid e Flexbox](https://codingfantasy.com/games/flexboxadventure)


## Aprender um Framework - Bootstrap

Aprenda sobre uma coleção de estilos pré-definidos ecomponente reutilizaveis através do Bootstrap.

## Criar e Copiar

Nesta fase deve ser criado sites deve tentar copiar sites para treinar tudo que está aprendendo.

> [Dica - Site desafios FrontEnd por nível.](https://www.frontendmentor.io/challenges)

## Linguagem de programação

Foi indicado JS (JavaScript) porém não abro mão do Python.

## JavaScript  

> [Dica - Site desafios JavaScript.](https://www.jschallenger.com/)

## Python

Lista de aprendizado para Python

### **Nível Iniciante:**

**1. Sintaxe básica de Python**

Aprenda a estrutura básica de um programa Python, incluindo variáveis, tipos de dados, operadores e estruturas de controle de fluxo (como condicionais e loops).

> [Python - O Básico da Sintaxe](http://devfuria.com.br/python/sintaxe-basica/)

1.1 ***Declaração de variáveis***

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

1.3 ***Comentários em Python***

 Comentários em Python começam com o caractere cerquilha `#` e estende até o final da linha. Um comentário pode aparecer no inicio da linha ou após espaço em branco ou código, mas não dentro de uma string literal. 

1.4 ***Tipos de Dados Básicos***

Python possui diversos tipos de dados básicos. 

Abaixo lista completa.

*Números inteiros*

`int`- representam números inteiros, como 1, 10, -5.

*Números de ponto flutuante*

`float` - Representam números decimais, como 3.14, 2.5.

*Números complexos*

`complex` - representam números complexos na forma a + bj, onde a e b são números reais e j é a unidade imaginária (√-1). Exemplos: 1+2j, -3+4j.

*Booleanos*

`bool` - representam valores verdadeiro (True) ou falso (False). São usados para expressar condições lógicas.

*Strings*

`str` - representam sequências de caracteres. Podem ser delimitados por aspas simples ('') ou aspas duplas ("").

*Listas*

`list` - representam coleções ordenadas e mutáveis de elementos.

*Tuplas*

`tuple` - são semelhantes a listas, mas são imutáveis.

*Conjuntos*

`set` - representam coleções não ordenadas de elementos únicos.

*Dicionários*

`dict` - representam coleções de pares chave-valor.

*Bytes*

`bytes` - representam sequências de bytes, são tipo de dados imutáveis.

~~~~python
# Uma sequência de bytes representando a palavra 'Hello'
dados_1 = b'\x48\x65\x6c\x6c\x6f'
print(dados_1)  # Saída: b'Hello'
print(type(dados_1))  # Saída: <class 'bytes'>
~~~~

*Bytearrays*

`bytearray` - são semelhantes aos bytes, mas são mutáveis.

~~~~python
# Um bytearray com a sequência de bytes 'Hello'
dados_2 = bytearray(b'\x48\x65\x6c\x6c\x6f')
print(dados_2)  # Saída: bytearray(b'Hello')

# Alterando o primeiro byte para o valor
# hexadecimal 0x41 (representa o caractere 'A')
dados_2[0] = 0x41
print(dados_2)  # Saída: bytearray(b'Aello')
print(type(dados_2))  # Saída: <class 'bytearray'>
~~~~

Esses são os tipos de dados básicos em Python. Cada tipo de dado tem suas características e métodos específicos. É importante entender esses tipos para poder trabalhar com eficiência no desenvolvimento de programas Python.

1.5 **Operadores**

Em Lógica de Programação e Algoritmos, Operadores são símbolos que dizem ao compilador para realizar manipulações (operações) matemáticas, lógicas e de comparação específicas.

Aqui está uma lista completa dos operadores disponíveis em Python, divididos em categorias:

1.5.1 ***Operadores Aritméticos***

São usados na realização de cálculos aritméticos simples, usando as quatro operações básicas da matemática mais operações como o módulo.

   - `+` (adição)
   - `-` (subtração)
   - `*` (multiplicação)
   - `/` (divisão)
   - `%` (resto da divisão)
   - `**` (exponenciação)
   - `//` (divisão inteira)

1.5.2 ***Operadores de Atribuição***

São operadores empregados para realizar a atribuição de valores entre os operandos, como por exemplo a atribuição de um valor a uma variável.

   - `=` (atribuição simples)
   - `+=` (atribuição com adição)
   - `-=` (atribuição com subtração)
   - `*=` (atribuição com multiplicação)
   - `/=` (atribuição com divisão)
   - `%=` (atribuição com resto da divisão)
   - `**=` (atribuição com exponenciação)
   - `//=` (atribuição com divisão inteira)

1.5.3 ***Operadores de Comparação***

Permitem estabelecer uma relação entre dois valores (operandos). Funcionam com quaisquer tipos de dados – desde que os operandos sejam do mesmo tipo.
Comparam o valor à esquerda com o valor à direita do operador, retornando um valor lógico (verdadeiro ou falso) de acordo com o resultado da comparação.

São também conhecidos como Operadores Relacionais.

   - `==` (igual a)
   - `!=` (diferente de)
   - `>` (maior que)
   - `<` (menor que)
   - `>=` (maior ou igual a)
   - `<=` (menor ou igual a)

1.5.4 ***Operadores Lógicos***

Os operadores lógicos recebem valores booleanos (verdadeiro ou falso) como entrada e retornam valores também booleanos como saída. São úteis para trabalhar com múltiplas condições relacionais na mesma expressão

   - `and` (e lógico)
   - `or` (ou lógico)
   - `not` (negação lógica)

1.5.5 ***Operadores de Identidade***

Os Operadores de Identidade são usados para comparar a identidade de dois objetos, ou seja, se eles se referem ao mesmo objeto na memória.

Esses operadores de identidade são usados para comparar a identidade de objetos, ou seja, se eles estão armazenados na mesma posição de memória. Eles retornam um valor booleano `True` se a condição for satisfeita e `False` caso contrário. Esses operadores são úteis para verificar se duas variáveis se referem ao mesmo objeto, em vez de comparar seus valores.

   - `is` (verifica se dois objetos são o mesmo objeto)
   - `is not` (verifica se dois objetos não são o mesmo objeto)

1.5.6 ***Operadores de Associação em Membro***

Os Operadores de Associação em Membro são usados para verificar se um valor está presente em uma sequência (como uma lista, tupla ou string) ou não.

Esses operadores são usados para realizar verificações de pertencimento em sequências. Eles retornam um valor booleano `True` se a condição for satisfeita e `False` caso contrário. Esses operadores podem ser úteis para realizar ações condicionais com base na presença ou ausência de um valor específico em uma sequência.

   - `in` (verifica se um valor está presente em uma sequência)
   - `not in` (verifica se um valor não está presente em uma sequência)

1.5.7 ***Operadores de Bit a Bit***

Os operadores bit-a-bit convertem valores numéricos inteiros fornecidos dados em binário e, em seguida, executam a operação requisitada, retornando o resultado em representação decimal.

   - `&` (AND bit a bit)
   - `|` (OR bit a bit)
   - `^` (XOR bit a bit)
   - `~` (complemento de um bit)
   - `<<` (deslocamento de bits para a esquerda)
   - `>>` (deslocamento de bits para a direita)

Esses são os operadores disponíveis em Python. Eles são usados para realizar diferentes operações em variáveis e valores, dependendo do contexto em que são utilizados. Lembre-se de que a ordem de precedência dos operadores pode afetar o resultado das expressões, e você também pode usar parênteses para controlar a ordem de avaliação.

Abaixo ordem de precedência dos operadores em Python, do mais alto para o mais baixo:

Parênteses: ()
Os parênteses podem ser usados para controlar a ordem de avaliação e definir grupos de operações.

Exponenciação: **
O operador de exponenciação calcula a potência de um número.

Multiplicação, Divisão, Divisão Inteira, Resto da Divisão: *, /, //, %
Esses operadores realizam as operações matemáticas usuais de multiplicação, divisão, divisão inteira (quociente da divisão sem a parte fracionária) e resto da divisão.

Adição e Subtração: +, -
Esses operadores realizam as operações matemáticas usuais de adição e subtração.

Comparação: ==, !=, >, <, >=, <=, is, is not, in, not in
Esses operadores são usados para realizar comparações entre valores e verificar igualdade, diferença, maior que, menor que, maior ou igual, menor ou igual, identidade de objeto e associação em membro.

Operadores de Bit a Bit: &, |, ^, ~, <<, >>
Esses operadores realizam operações de bit a bit em valores numéricos.

Operadores Lógicos: not, and, or
Esses operadores são usados para realizar operações lógicas em valores booleanos.

Lembre-se de que é possível alterar a ordem de avaliação utilizando parênteses para garantir que as operações sejam executadas na ordem desejada. Além disso, é sempre uma boa prática utilizar parênteses para tornar o código mais legível e evitar ambiguidades.

2 **Conceitos Importantes para Python**

Abaixo alguns conceitos importantes d linguagem de programação python.

2.1 ***Variáveis Mutáveis e Imutáveis***

Em python as variáveis dos tipos `int`, `float`, `tuple` e `str` são imutáveis.

No exemplo abaixo a variável criada `faturamento` não sofre alteração e sim ela é recriada com um novo valor.

~~~~python
# Variável do tipo int
faturamento = 1500
print(faturamento)
faturamento = faturamento * 2
~~~~

Para exemplificar melhor no exemplo abaixo ao tentar alterar o primeiro item da tupla `tvendas` gera erro `TypeError: 'tuple' object does not support item assignment` devido a tupla ser imutável.

~~~~python
# Variável do tipo tuple
tvendas = (250, 320, 410)
tvendas[0] = 367
tvendas.append (1000)
print(tvendas)
print(type(tvendas))
~~~~

Já as variáveis do tipo listas `list` e dicionários `dir` são mutáveis podendo os dados das variáveis serem editadas.

~~~~python
# Variável do tipo list
lvendas = [250, 320, 410]
lvendas[0] = 367
lvendas.append (1000)
print(lvendas)
print(type(lvendas))
~~~~

2.2 ***Parâmetros e Argumentos de Funções***

As funções podem ser criadas possuindo ou não parâmetros/argumentos.

Exemplo de função sem parâmetros:

~~~~python
def calcular_imposto()
    print ("Imposto calculado")
~~~~

Exemplo de função com parâmetros:

~~~~python
def calcular_imposto(preco, taxa):
    imposto = preco * taxa
    print(f"Preço: {preco} e Taxa {taxa}.")
    return imposto
~~~~

Existem 3 tipos de argumentos *posicional*, *keyword* e *opcional*.

No exemplo com parâmetros é obrigatório ser informado os dados de `preco` e `taxa` para que a função funcione para que funcione deve ser informado de forma posiciona em que os valores devem seguir a ordem dos argumentos `preco` e `taxa`:

~~~~python
# Argumentos informados de forma posicional
imposto = calcular_imposto(1500, 0.2)
print(imposto)
~~~~

Ou podendo os argumentos ser setados com os nomes das palavras chaves dos argumentos das funções, utilizando o keyword. Neste caso não precisa seguir a ordem dos argumentos das funções:

~~~~python
# Argumentos informados com as palavras chaves das funções com as Keywords
imposto = calcular_imposto(taxa = 0.2, preco = 1500)
print(imposto)
~~~~

E por ultimo o argumento pode ser opcional devendo ele ser atribuído com valor null `None`.

~~~~python
def calcular_imposto_n(preco, taxa, outro_valor = None):
    imposto = preco * taxa
    print(f"Preço: {preco}, Taxa {taxa} e Outro Valor: {outro_valor}.")
    return imposto

# Argumentos opcional None
imposto = calcular_imposto(1500, taxa = 0.2)
print(imposto)
~~~~

2.3 ***if __name__ == "__main__":***

Ao construir uma função que será utilizadas em outro códigos devemos criar o teste no arquivo da função após um estrutura condicional que identifica se o arquivo que esta executando a função é o `main` (principal) para que o teste somente seja executado no arquivo da função.

Exemplo:

~~~~python
def calcular_imposto_n(preco, taxa):
    imposto = preco * taxa
    return imposto

if __name__ == "__main__":
    print(calcular_imposto_n(1500, 0.2))
~~~~

**2. Estruturas de controle de Fluxo**

2.1 **Estruturas Condicionais**

If, Elif, Else

Além das estruturas condicionais básicas, Python também oferece recursos adicionais para manipular condições mais complexas.

Operador Ternário:

O operador ternário é uma forma concisa de expressar uma estrutura condicional em uma única linha. Ele é útil quando você precisa tomar uma decisão simples com base em uma condição. 

Operador "in":

O operador "in" é usado para verificar se um elemento está presente em uma sequência, como uma lista, uma string ou uma tupla.

Encadeamento de Condições:

Você pode encadear múltiplas condições usando os operadores "and" e "or" para criar expressões mais complexas. 

2.2 **Estruturas de Repetição**

While

A estrutura "while" é usada para repetir um bloco de código enquanto uma condição específica for verdadeira

É importante ter cuidado ao usar um "while" para evitar criar um loop infinito. Certifique-se de que a condição será eventualmente falsa para que o loop seja interrompido.

For

A estrutura "for" é usada para percorrer elementos de uma sequência, como uma lista, uma string, uma tupla, entre outros.

Além disso, você também pode usar a função "range()" em conjunto com o "for" para gerar uma sequência numérica.

Python oferece recursos adicionais para manipular loops e controlar o fluxo de execução.

Controle do Loop com "break" e "continue":

Dentro de um loop, você pode usar a instrução "break" para interromper o loop prematuramente, mesmo se a condição ainda for verdadeira.

Já a instrução "continue" permite pular a iteração atual e continuar para a próxima.

Uso do "else" no Loop:

Em Python, você pode usar a cláusula "else" em um loop para especificar um bloco de código a ser executado quando o loop for concluído sem ser interrompido por uma instrução "break".

Iteração com "enumerate":

A função "enumerate" permite iterar sobre uma sequência ao mesmo tempo em que acompanha o índice de cada elemento.

frutas = ["maçã", "banana", "laranja"]
for indice, fruta in enumerate(frutas):
    print(indice, fruta)



2.3 **Estruturas de Controle de Exceções**

try, except, finally

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