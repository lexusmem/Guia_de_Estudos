# Guia de Estudos

Guia sugerido pelo Fiasco através do Yutube.

> [YouTube Fiasco - Guia de Estudos](https://www.youtube.com/watch?v=A1BaZr82XJI)

## Como Funciona o Computador e a Internet

Devemos entender como a internet está estruturada Protocolos de Rede HTTP/HTTPS/DNS e mais assuntos relacionados ao www e como funciona o computador.

> [Protocolos de Rede](https://medium.com/@christiancost47/protocolos-de-rede-quem-s%C3%A3o-o-que-fazem-onde-vivem-5f7ef43aa526)

> [Pdf - Historia da Internet](https://github.com/lexusmem/Guia_de_Estudos/blob/778b97bbc8172e1b18eba6ec756d4558f597347f/01%20-%20Hist%C3%B3ria%20da%20Internet.pdf)

> [Pdf - Como Funciona a Internet](https://github.com/lexusmem/Guia_de_Estudos/blob/778b97bbc8172e1b18eba6ec756d4558f597347f/02%20-%20Como%20funciona%20a%20Internet.pdf)

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

2.2 **DNS - Domain Name System**

Um serviço DNS é um serviço globalmente distribuído que converte nomes legíveis por humanos, como *www.exemplo.com*, em endereços IP numéricos, como 192.0.2.1, usados pelos computadores para se conectarem entre si.  
O sistema DNS da internet funciona praticamente como uma agenda de telefone ao gerenciar o mapeamento entre nomes e números. Os servidores DNS convertem solicitações de nomes em endereços IP, controlando qual servidor um usuário final alcançará quando digitar um nome de domínio no navegador da web. Essas solicitações são chamadas consultas.




Ciração destes protocolos para controlar a rede.

TCP

HTTP

Nova tecnologia os protocolos HTTP e HTPPS integradas ao TCP/IP.

Linguagem de marcação Html

WWW - Word Wide Web

Navegadores - primeiro navegar mosaik

> [YouTube Guanabara - Internet I](https://youtu.be/F74GKCLXUWM)

> [YouTube Guanabara - Internet II](https://youtu.be/nlO5hySqJFA)

> [YouTube Guanabara - Internet III](https://youtu.be/RFHSt1PCy0k)

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