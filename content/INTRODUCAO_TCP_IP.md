---
marp: true
author: JanainaTeixeira
header: 'Apresentação: Introdução ao TCP/IP'
footer: 'Exercício Markdown - Janaina Tannus - Digital College - Turma FS23 Aldeota'
_class: invert
paginate: true
size: 16:9
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
---
<!-- -------------- Slide 1: Minha apresentação -------------- -->
<!-- _paginate: false -->

# <!--fit--> Intro sobre TCP/IP :rocket:

# <center><span style="color: grey"> By: </span> Jana Tannus </center>
<center><span style="color:#1d2c3d"> https://github.com/jmtannus </span> </center>

---
<!-- -------------- Slide 2: Introdução ao TCP/IP - comunicando-se em redes -------------- -->
<!-- _paginate: false
backgroundImage: Url(https://ip-check.info/wp-content/uploads/2022/04/tcpip-696x453.jpg.webp) -->

![bg conversa w:1000](https://github.com/dcTeam23/fundamentos/assets/61756665/fc7caafc-118a-4f2a-91fb-6ac06ab46503)

<!--Olá pessoal, pra quem não me conhece,eu me chamo Janaína e vou apresentar uma introdução aos famosos Protocolo de Controle de Transmissão e Protocolo de Internet: TCP e IP.

Imagine uma sala cheia de pessoas conversando, cada uma com sua própria linguagem e forma de se comunicar. Agora, pense em como seria difícil para elas se entenderem e trocarem informações de maneira eficiente. É nesse momento que entra em cena o protocolo de comunicação.-->

---

<!-- --------------------------------- Slide 3: protocolo de comunicação -------------------------------- -->
<!-- _class: invert
_color: #c5cdd9  -->
<!-- backgroundImage: black -->

<!--O que é protocolo de comunicação?

É como se fosse uma linguagem comum que todas as pessoas dessa sala deveriam falar para garantir que a informação seja transmitida corretamente.-->
# <!--fit--> Protocolo de Comunicação

</br>

# Conjunto de **regras** e **convenções**

# estabelecidas para permitir a **troca de dados entre:**

# *sistemas, dispositivos ou componentes de uma rede.*

---

<!-- ----------------------------------- Slide 4: aspectos do protocolo ----------------------------------- -->
<!-- backgroundImage: "linear-gradient(to bottom, #c5cdd9, #35495e)" 
_color: black -->

<!--Ele garante que a informação seja transmitida de maneira confiável, segura e padronizada.-->

## <!--fit--> Esse protocolo define aspectos como:

<span style="color: white">

* ## A estrutura dos dados

* ##  Os formatos de mensagem

* ##  Os procedimentos de envio e recebimento

* ##  Os mecanismos de detecção e correção de erros. 

</span>

---
<!-- --------------------------------- Slide 5: aspectos do protocolo --------------------------------- -->
<!-- _color: dark -->

<!--Ele é como um mediador que facilita a troca de informações, tornando possível a interconexão de computadores, servidores, dispositivos móveis e muito mais.Com ele podemos enviar e receber e-mails, acessar sites, fazer chamadas de vídeo, compartilhar arquivos e desfrutar de uma infinidade de serviços online. -->
<!--Sem protocolos de comunicação padronizados, seria difícil, por exemplo, existir uma rede global como a Internet.-->

<center>

# Porque o protocolo de comunicação é essencial para a transmissão de dados em redes?

</br>

Porque permite que dispositivos e sistemas **diferentes** se comuniquem
de forma **harmoniosa**. Eles são fundamentais para a **conectividade** e
 para o **funcionamento da internet** e de muitas outras redes.

</center>

---

<!-- --------------- Slide 6: Base Invisível --------------- -->
<!-- backgroundImage: "linear-gradient(to bottom,#c5cdd9, #FFF )"-->

 ![bg left:33% h:330 rededados](https://github.com/dcTeam23/fundamentos/assets/61756665/511ca44a-1d18-4dc2-982a-22a0288c91de)

#  Podemos dizer que o protocolo de comunicação

## <!--fit-->  é a base invisível

### que permite a comunicação entre sistemas, tornando possível a interconexão do mundo moderno.

---
<!-- ------------------------ Slide 7: como padronizaram o protocolo ------------------------ -->
<!-- 
backgroundImage: #101010
_color: dark
_class: invert -->

<!--Para padronizar a criação de protocolos, o modelo OSI (Open Systems Interconnection) foi criado em 1971 e formalizado em 1983. Esse modelo define uma arquitetura de protocolo para redes. Com ele, diferentes fabricantes podem fabricar seus equipamentos para se comunicar, interpretar as informações contidas na comunicação e realizar a tarefa solicitada.O modelo OSI prevê que uma rede deve ter 7 camadas -->

# <!-- fit--> Mas... como? :roll_eyes:

---
<!-- ------------------------ Slide 8: Camadas do modelo OSI ------------------------ -->
<!-- backgroundImage: "linear-gradient(to bottom,#c5cdd9, #35495e )" 
_color: black
_class: lead -->

# <!--fit--> Camadas do modelo OSI:

<div class="columns">
<div>

* **Aplicativo** – funções especializadas no nível do aplicativo

* **Apresentação** – formatação de dados e conversão de caracteres e códigos

* **Sessão** – Negociação e estabelecimento de conexão com outro nó

* **Transporte** – Meios e métodos de entrega de dados de ponta a ponta

</div>

<div>

* **Rede** – Roteamento de pacotes através de uma ou mais redes.

* **Link**  – Detecção e correção de erros introduzidos pelo meio de transmissão

* **Físico** – Transmissão de bits através do meio de transmissão.

</div>
</div>

---

<!-- --------------- Slide 9: PROTOCOLOS competindo pelo domínio --------------- -->
<!-- _class: lead -->

# <!--fit--> PROTOCOLOS
## <!--fit--> competindo pelo domínio

<!--surgimento dos protocolos de comunicação-->

<!--Como surgiu os protocolos de comunicação? Antes da era da Internet, quando as redes de computadores estavam iniciando, diferentes protocolos competiam pelo domínio, cada um com sua própria forma de estabelecer comunicação. Era como se diferentes línguas estivessem sendo faladas em cada rede, dificultando a interoperabilidade e a troca de informações.

Um dos protagonistas dessa história é o TCP/IP, o protocolo que acabou se tornando o padrão mundial para a comunicação em redes. Mas antes de alcançar esse status, outros protocolos também desempenharam papéis importantes. Por exemplo:  NETBEUI, o IPX/SPX e o Apple Talk.
Esses protocolos eram utilizados nas redes das empresas e, em seu auge, cada um deles tinha sua própria capacidade de estabelecer comunicação.-->

---
<!-- ------- Slide 10: imagem uso de protocolo diferente (NETBEUI, o IPX/SPX e o AppleTalk) ------- -->

<!-- backgroundImage: "linear-gradient(to bottom, #c5cdd9, #FFF)"-->

<!-- No entanto, à medida que a necessidade de interconexão e compartilhamento de recursos crescia, tornou-se evidente a necessidade de um protocolo comum que unificasse as redes. E assim, o TCP/IP emergiu como um vencedor claro-->

![w:100% protocolos](https://user-images.githubusercontent.com/61756665/248303222-ad546c70-4f69-4e4f-bbd0-46f8b9ae0ae6.png)

---
<!-- ---------------------------- Slide 11 - Tópico: Criadores ---------------------------- -->
![bg h:900 w:1280 image-3](https://github.com/dcTeam23/fundamentos/assets/61756665/9428ca3b-7600-4c70-99b8-a9937a1fa050)

<!-- à direita, Vinton Cerf . Matemático e Mestre em Tecnologia americano. Foi em 2005 vice-presidente da Google. Na época de sua contratação, o executivo-chefe da empresa, Eric Schmidt, chegou a dizer que Vinton Cerf era uma das pessoas mais importantes da história ainda vivas. Junto a Robert Kahn, é um dos criadores da Internet, tendo participado da criação dos protocolos TCP/IP, que são os alicerces da conexão à rede. Foi esse de óculos, Robert, quem desenvolveu o TCP e Vinton, o barbudo, que iniciou o desenvolvimento do IP para transmissão de informações pela Internet, que foi reconhecido com a publicação do artigo A Protocol for Packet Network Intercommunication.-->

---
<!-- -------------------------- Slide 12 - Tópico: Curiosidade -------------------------- -->
<!-- _class: invert
_color: gray  -->
<!-- backgroundImage:  black -->

<!-- Hoje, quando pensamos no pai da internet, a maioria das pessoas pensa em Tim Berners Lee, o homem que criou a World Wide Web. ele é realmente o pai da internet moderna. 

MAS Vint Cerf criou a MANEIRA pela qual Tim Lee poderia mais tarde criar O 'W W W' como a conhecemos hoje. 

<!--Os protocolos TCP/IP foram importante para o funcionamento da Internet devido à sua capacidade de conectar redes heterogêneas, permitindo a comunicação entre diferentes sistemas operacionais e dispositivos, compartilhando dados entre eles de forma eficiente em todo o mundo. Ele foi desenvolvido ao longo de décadas, como resultado de pesquisas e colaborações entre cientistas, engenheiros e acadêmicos.-->

<div>
<center>

# Tim Berners Lee x Vint Cerf

# <!--fit --> ![w:800 tim vint](https://github.com/dcTeam23/fundamentos/assets/61756665/d2dba3bb-68f0-4ddc-aff7-4dcf972fa15d)

# <!--fit--> pai da internet moderna  |  pai da internet

## <!--fit--> criou a World Wide Web  |  co-projetou protocolos TCP/IP

</center>
</div>

---
<!-- ---------------------------- Slide 13 - Tópico: O que é o TCP/IP? ---------------------------- -->
<!-- backgroundImage: "linear-gradient(to bottom, #1a2938, #35495e ,#c5cdd9 )" 
<!-- _class: leader -->
<!-- _color: #c5cdd9 -->

<!-- Com sua abordagem robusta, o TCP/IP assegura que a informação seja transmitida de maneira confiável, segura e padronizada, garantindo uma comunicação eficiente entre dispositivos e redes.-->

![bg right:45% w:400 internet1](https://github.com/dcTeam23/fundamentos/assets/61756665/c702733c-9648-4596-96bd-a808513551fa)

<center><span style="color: #011121">

# TCP:: Transmission Control Protocol

</span> 

</center>

<!--Garante a Transmissão Confiável e Padronizada dos Dados: Ele é responsável por estabelecer uma conexão virtual entre remetentes e destinatários, dividir os dados em pacotes e controlar o fluxo de transmissão, sem que os dados sejam corrompidos ou alterados.-->

* ### Conjunto de protocolos para a **comunicação em redes**

* ### **Segurança** na transmissão da informação

* ### **Comunicação eficiente** entre dispositivos e redes

---
<!-- ---------------------------- Slide 14 - Tópico: O que é o IP? ---------------------------- -->
<!-- backgroundImage: "linear-gradient(to bottom,#c5cdd9, #35495e, #1a2938  )" 
_class: invert-->
<!-- _color: #FFF -->

![bg left:50% h:600 network_cabling1](https://github.com/dcTeam23/fundamentos/assets/61756665/57016b83-be0f-4da5-86f9-22a1898746cc)

<center>
<span style="color: #011121">

# IP :: Internet Protocol

</span> 

</center>

Fornece **endereçamento e identificação** para cada dispositivo conectado à rede, permitindo que os pacotes de dados sejam corretamente encaminhados entre remetentes e destinatários garantindo a comunicação eficiente entre eles.

<!--O IP é responsável por atribuir um endereço IP único a cada dispositivo na rede, seja ele um computador, smartphone, servidor ou qualquer outro dispositivo conectado à internet. Esse endereço IP funciona como uma identificação exclusiva do dispositivo, permitindo que os pacotes de dados sejam roteados corretamente através da rede.

Além disso, o IP define como os pacotes de dados devem ser fragmentados, encapsulados e transmitidos entre os dispositivos. Ele estabelece regras para o envio, roteamento e recebimento dos pacotes, garantindo a integridade e a confiabilidade da comunicação.

Sem o IP, não seria possível estabelecer a conectividade e a troca de informações que caracterizam a internet e as redes de computadores.-->

---
<!-- ---------------------------- Slide 15 - Tópico: Finalidades do TCP ---------------------------- -->
<!-- _class: invert -->
#### O TCP oferece várias funcionalidades essenciais para a comunicação eficiente e confiável na internet e em outras redes. Algumas das principais finalidades do TCP são:
</br>

* Confiabilidade
<!-- Garante a entrega confiável dos dados, verificando se os pacotes são recebidos corretamente e retransmitindo-os, se necessário. Ele também controla a detecção e a recuperação de erros durante a transmissão.-->
* Ordenação
<!-- Mantém a ordem correta dos pacotes de dados durante a transmissão, reorganizando-os, se necessário. Isso garante que os dados sejam recebidos na mesma sequência em que foram enviados.-->
* Controle de Fluxo
<!-- Controla o fluxo de transmissão, ajustando a taxa de envio dos pacotes de acordo com a capacidade da rede e a capacidade de processamento do destinatário. Isso evita a sobrecarga da rede e a perda de pacotes devido a congestionamento.-->
* Segmentação
<!-- Divide os dados em segmentos de tamanho apropriado para a transmissão pela rede. Isso permite que grandes quantidades de dados sejam transmitidas de forma eficiente e evita problemas de congestionamento.-->
* Estabelecimento e encerramento de conexão
<!-- Estabelece uma conexão virtual entre remetentes e destinatários, permitindo a troca de dados. Ele também gerencia o encerramento dessa conexão de forma adequada e segura.-->

---
<!-- -------------------------- Slide 16 - Tópico: Frase de Vint Cerf -------------------------- -->
<!-- _class: invert
_color: gray  -->
<!-- backgroundImage:  black -->

![bg 80% image-5](https://github.com/dcTeam23/fundamentos/assets/61756665/75515c71-819f-4f0c-94b7-467d2d2ac5b2)

<!-- "The internet we experience today has exceeded all my initial estimations." : "A internet que experimentamos hoje superou todas as minhas estimativas iniciais"
À medida que a popularização da Internet crescia, o TCP/IP se consolidou como o protocolo padrão, impulsionando a expansão da rede mundial de computadores. Ele foi adotado por organizações, empresas e governos ao redor do mundo, criando um ambiente de conectividade sem precedentes. -->

---

<!-- -------------------- Slide 17: Sistemas operacionais que utilizam o TCP/IP -------------------- -->
<!--_color: #c5cdd9-->
backgroundImage: ![bg space](https://github.com/dcTeam23/fundamentos/assets/61756665/ac6b2249-3264-4291-a258-9c6cb8a4a74e) -->
</br></br></br>

## <!--fit---> *Conectividade de Rede*
# <!--fit--->  nos Principais Sistemas Operacionais
<div class="columns">
<div>

* ## Windows **(Microsoft)**
* # MacOS **(Apple)**
</div>
<div>

* ## Linux **(sistema operacional de código aberto)**
<!-- Linux, utilizado em servidores, dispositivos embarcados e muitos outros dispositivos-->

* # Outros Sistemas **(Unix, Android e iOS)**
<!--A maioria dos sistemas operacionais modernos, como Windows, macOS, Linux e Unix, suporta nativamente o protocolo TCP/IP. Além disso, outros sistemas como iOS, Android e várias distribuições de Unix-like também o suportam. O TCP/IP é amplamente utilizado como o principal protocolo de rede, permitindo a comunicação eficiente entre diferentes dispositivos e sistemas operacionais.-->
</br></br></br></br></br>
</div>
</div>

---
<!-- -------------------------- Slide 18 - Tópico: Arquitetura do TCP/IP -------------------------- -->
<!-- _class: +invert -->
<!-- backgroundImage: #c5cdd9 -->
<!-- _color: #35495e -->

<!--Comparado com o modelo OSI já sitado anteriormente, você pode ver como as 4 camadas TCP/IP e suas funções estão relacionadas:-->

![bg left:35% w:450](https://www.datarain.com.br/wp-content/uploads/2020/08/modelo-TCP-IP.png)

### <!--fit--> Arquitetura do TCP/IP

# <!--fit--> Camadas do TCP/IP e suas funções

<div class="columns">

<div>

* ### Aplicação **(Camada 4)**

* ### Transporte **(Camada 3)**

</div>
<div>

* ### Internet ou Rede **(Camada 2)**

* ### Link ou Físico **(Camada 1)**

</div>
</div>

---
<!------------------------------- Slide 19 - Mas como? (Pergunta com Emoji Pensativo)------------------------------->

<!-- backgroundImage: #101010
_color: dark
_class: invert -->
</br>

# <!-- fit-->Mas... Como são utilizados para 
# <!-- fit-->*identificar* e *localizar*
# <!-- fit--> dispositivos na rede? :thinking:

</br>

---
<!-- ----------------------------- Slide 20 - Tópico: Endereçamento IP ----------------------------- -->
<!-- _class: +invert -->
<!-- backgroundImage: #c5cdd9 -->
<!-- _color: #35495e -->

![bg right:40% w:480 enderecoIP](https://github.com/dcTeam23/fundamentos/assets/61756665/795a83fb-6de7-43af-bfb3-a129883b8b8d)

# Endereçamento IP

## Conceitos:

* Endereço IP: Representados no formato decimal, ex: 192.168.1.0. O endereço IP **identifica uma conexão à Internet** e não a máquina em si.
<!--O endereço IP versão 4, é uma sequência de números com 32 bits de tamanho, escrito com quatro octetos, quatro sequências de 8 bits, a cada sequência dá-se o nome de byte. Os endereços IP são representados no formato decimal, ex 192.168.1.0. O endereço IP identifica uma conexão à Internet e não a máquina em si.-->
* Máscara de sub-rede: Número de 32-bit que mascara um endereço IP e divide o endereço IP em: **endereço de rede** e **endereço de host**.
<!--Um endereço IP tem dois componentes, o endereço de rede e o endereço do host. Uma máscara de sub-rede separa o endereço IP nos endereços de rede e de host (<network><host>).-->

* Gateway (portal): Estabelece a comunicação entre múltiplos ambientes.
<!--Gateway é um termo em inglês que significa portão ou portal, um sistema ou equipamento cuja função básica é estabelecer a comunicação entre múltiplos ambientes. Com ele, é possível fazer a conexão entre equipamentos localizados em redes diferentes e que comuniquem através de padrões distintos.-->

---
<!-- --------------------------------- Slide 21 - Tópico: Conclusão --------------------------------- -->
<!-- backgroundImage: #c5cdd9 -->
<!-- _color: #35495e -->

![bg left:38% w:850 78029121434_crop](https://github.com/dcTeam23/fundamentos/assets/61756665/b0c19f6a-9859-41af-a1cd-9ddf4b052fba)

# Hoje, o TCP/IP é o alicerce da comunicação na Internet e em muitas outras redes. 
## É ele que permite que nossos dispositivos se conectem, troquem mensagens, acessem informações, realizem transações e nos ajudem a explorar o vasto mundo online.

<!-- A história dos protocolos de comunicação é uma prova do poder da inovação e da busca por uma linguagem comum que transcende fronteiras e diferenças. A evolução desses protocolos nos conduziu a um futuro interconectado, onde a comunicação é instantânea e o compartilhamento de conhecimento é ilimitado.

Nesta jornada pelo passado, podemos apreciar o impacto transformador dos protocolos de comunicação e a maneira como eles moldaram o mundo em que vivemos hoje. E enquanto continuamos avançando em direção ao desconhecido, podemos olhar para trás e agradecer aos pioneiros que nos trouxeram até aqui, conectando pessoas, ideias e possibilidades.-->

---

<!-- -------------------------- Slide 22- Tópico: Perguntas e discussões ------------------------- -->
<!-- _class: invert -->
<center>

## <!--fit--> :woman_shrugging: <span style="color: #FFF">  Perguntas?  </span> :man_shrugging:

# Obrigada pela atenção!

## Um ótimo dia pra todos!

# 🌻

</center>