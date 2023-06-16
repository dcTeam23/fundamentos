---
marp: true
author: JanainaTeixeira
theme: gaia
_class: lead
paginate: true
backgroundColor: #101010
---
<!-- 1º slide -->
<!-- _paginate: false -->
<!--  
Fala: 
Imagine uma sala cheia de pessoas conversando, cada uma com sua própria linguagem e forma de se comunicar. Agora, pense em como seria difícil para elas se entenderem e trocarem informações de maneira eficiente. É nesse momento que entra em cena o protocolo de comunicação.-->

# Introdução ao TCP/IP 

![w:400](https://www.dltec.com.br/blog/wp-content/uploads/2023/02/TCP-IP.png)<!--fit-->

---
<!-- 2º slide -->
<!-- backgroundImage: "linear-gradient(to bottom, #67b8e3, #0288d1)" 
_color: white-->

<!-- _class: lead -->

## Protocolo de comunicação <!--fit -->
<!--_color: black -->
<!-- _bold: #044569 -->

### Um protocolo de comunicação é um conjunto de **regras** e **convenções** estabelecidas para permitir a **troca de dados entre:**
# sistemas, dispositivos ou componentes de uma rede.  

<!--É como se fosse uma linguagem comum que todos os participantes da comunicação devem seguir para garantir que a informação seja transmitida corretamente. -->

---
<!-- _color: black 
_class: lead -->
## Esse protocolo define aspectos como a estrutura dos dados, os formatos de mensagem, os procedimentos de envio e recebimento, além dos mecanismos de detecção e correção de erros. 

Ele garante que a informação seja transmitida de maneira confiável, segura e padronizada. 

---
<!-- _color: dark
_class: lead -->
## O protocolo de comunicação é essencial para a transmissão de dados em redes, pois permite que dispositivos e sistemas diferentes se comuniquem de forma harmoniosa. 

<!--Ele é como um mediador que facilita a troca de informações, tornando possível a interconexão de computadores, servidores, dispositivos móveis e muito mais.-->

---
<!-- _color: dark
_class: lead -->
### Graças aos protocolos de comunicação, podemos enviar e receber e-mails, acessar sites, fazer chamadas de vídeo, compartilhar arquivos e desfrutar de uma infinidade de serviços online. 

&nbsp;
Eles são fundamentais para a conectividade e para o funcionamento da internet e de muitas outras redes.

---
<!-- _color: dark
_class: lead -->
### Portanto, podemos dizer que o protocolo de comunicação é a base invisível que permite a comunicação entre sistemas, tornando possível a interconexão do mundo moderno.

&nbsp;
É graças a ele que podemos nos conectar, trocar informações e aproveitar todas as maravilhas da era digital.

---
<!-- _class: lead -->
# **Surgimento** 
# **dos protocolos de comunicação**

---
<!--Agora vamos explorar a história do surgimento dos protocolos de comunicação.-->
<!-- _class: lead -->
### Antes da era da Internet, quando as redes de computadores estavam iniciando, diferentes protocolos competiam pelo domínio, cada um com sua própria forma de estabelecer comunicação.

<!-- Um dos protagonistas dessa história é o TCP/IP, o protocolo que acabou se tornando o padrão mundial para a comunicação em redes. Mas antes de alcançar esse status, outros protocolos também desempenharam papéis importantes. Vamos mencionar alguns deles, como o NETBEUI, o IPX/SPX e o Apple Talk.
Esses protocolos eram utilizados nas redes das empresas e, em seu auge, cada um deles tinha sua própria capacidade de estabelecer comunicação. Era como se diferentes línguas estivessem sendo faladas em cada rede, dificultando a interoperabilidade e a troca de informações.-->

---
<!-- imagem -->
<!-- No entanto, à medida que a necessidade de interconexão e compartilhamento de recursos crescia, tornou-se evidente a necessidade de um protocolo comum que unificasse as redes. E assim, o TCP/IP emergiu como um vencedor claro-->

---
<!-- _class: lead -->
# **TCP/IP:**
### (Transmission Control Protocol/Internet Protocol)

### O TCP é um protocolo de comunicação utilizado em redes de computadores para garantir a entrega confiável e ordenada de dados entre dispositivos. 

---
<!-- imagem -->
<!-- _class: lead -->
#### Ele é responsável por estabelecer uma conexão virtual entre remetentes e destinatários, dividir os dados em pacotes e controlar o fluxo de transmissão, sem que os dados sejam corrompidos ou alterados.

<!-- O TCP/IP ganhou destaque devido à sua capacidade de conectar redes heterogêneas, permitindo a comunicação entre diferentes sistemas operacionais e dispositivos. Ele foi desenvolvido ao longo de décadas, como resultado de pesquisas e colaborações entre cientistas, engenheiros e acadêmicos.-->

---
<!-- imagem -->
<!-- _class: lead -->
#### O TCP oferece várias funcionalidades essenciais para a comunicação eficiente e confiável na internet e em outras redes. Algumas das principais finalidades do TCP são:

Confiabilidade
<!-- O TCP garante a entrega confiável dos dados, verificando se os pacotes são recebidos corretamente e retransmitindo-os, se necessário. Ele também controla a detecção e a recuperação de erros durante a transmissão.-->
Ordenação
<!-- O TCP mantém a ordem correta dos pacotes de dados durante a transmissão, reorganizando-os, se necessário. Isso garante que os dados sejam recebidos na mesma sequência em que foram enviados.-->
Controle de Fluxo
<!-- O TCP controla o fluxo de transmissão, ajustando a taxa de envio dos pacotes de acordo com a capacidade da rede e a capacidade de processamento do destinatário. Isso evita a sobrecarga da rede e a perda de pacotes devido a congestionamento.-->
Segmentação
<!-- O TCP divide os dados em segmentos de tamanho apropriado para a transmissão pela rede. Isso permite que grandes quantidades de dados sejam transmitidas de forma eficiente e evita problemas de congestionamento.-->
Estabelecimento e encerramento de conexão
<!-- O TCP estabelece uma conexão virtual entre remetentes e destinatários, permitindo a troca de dados. Ele também gerencia o encerramento dessa conexão de forma adequada e segura.-->

---

### O IP tem a função de fornecer endereçamento e identificação para cada dispositivo conectado à rede, permitindo que os pacotes de dados sejam corretamente encaminhados entre remetentes e destinatários.
<!--O IP é responsável por atribuir um endereço IP único a cada dispositivo na rede, seja ele um computador, smartphone, servidor ou qualquer outro dispositivo conectado à internet. Esse endereço IP funciona como uma identificação exclusiva do dispositivo, permitindo que os pacotes de dados sejam roteados corretamente através da rede.

Além disso, o IP define como os pacotes de dados devem ser fragmentados, encapsulados e transmitidos entre os dispositivos. Ele estabelece regras para o envio, roteamento e recebimento dos pacotes, garantindo a integridade e a confiabilidade da comunicação.

Em resumo, o Internet Protocol (IP) serve para fornecer identificação e endereçamento único aos dispositivos na rede, permitindo a transmissão correta dos pacotes de dados e garantindo a comunicação eficiente entre eles. Sem o IP, não seria possível estabelecer a conectividade e a troca de informações que caracterizam a internet e as redes de computadores.-->

---
<!-- imagem -->
<!-- À medida que a popularização da Internet crescia, o TCP/IP se consolidou como o protocolo padrão, impulsionando a expansão da rede mundial de computadores. Ele foi adotado por organizações, empresas e governos ao redor do mundo, criando um ambiente de conectividade sem precedentes. -->

---
<!-- _class: lead -->
![w:700](https://www.datarain.com.br/wp-content/uploads/2020/08/modelo-TCP-IP.png)

<!-- Hoje, o TCP/IP é o alicerce da comunicação na Internet e em muitas outras redes. É ele que permite que nossos dispositivos se conectem, troquem mensagens, acessem informações, realizem transações e nos ajudem a explorar o vasto mundo online.

A história dos protocolos de comunicação é uma prova do poder da inovação e da busca por uma linguagem comum que transcende fronteiras e diferenças. A evolução desses protocolos nos conduziu a um futuro interconectado, onde a comunicação é instantânea e o compartilhamento de conhecimento é ilimitado.

Nesta jornada pelo passado, podemos apreciar o impacto transformador dos protocolos de comunicação e a maneira como eles moldaram o mundo em que vivemos hoje. E enquanto continuamos avançando em direção ao desconhecido, podemos olhar para trás e agradecer aos pioneiros que nos trouxeram até aqui, conectando pessoas, ideias e possibilidades.-->

---
<!-- _class: lead -->
# **Conectividade de Rede** 

# **nos Principais Sistemas Operacionais**

<!-- Os principais sistemas operacionais do mercado que utilizam o TCP/IP como base para a conectividade de rede são: -->

---
<!-- imagem -->
<!-- Windows: O sistema operacional Windows, desenvolvido pela Microsoft, suporta nativamente o protocolo TCP/IP. Ele é amplamente utilizado em computadores pessoais e em muitos ambientes corporativos.-->

<!-- imagem -->
<!--macOS: O sistema operacional macOS, da Apple, também é compatível com o TCP/IP. Ele é utilizado em computadores Mac e oferece suporte completo às funcionalidades de rede baseadas nesse protocolo.-->

<!-- imagem -->
<!-- Linux: O Linux é um sistema operacional de código aberto amplamente utilizado em servidores, dispositivos embarcados e muitos outros dispositivos. Ele possui suporte nativo ao TCP/IP e oferece uma ampla gama de ferramentas e recursos para configuração e gerenciamento de redes.-->

<!-- imagem -->
<!--Além desses três principais sistemas operacionais, muitos outros sistemas, como Unix, Android e iOS, também utilizam o TCP/IP como base para a conectividade de rede. Isso demonstra a importância e a onipresença desse protocolo no mundo da tecnologia, permitindo a comunicação eficiente entre diferentes dispositivos e sistemas operacionais. -->

---
# Conclusão:

<!-- _class: lead -->
### O TCP/IP é um protocolo essencial para a conectividade de rede nos principais sistemas operacionais do mercado. 

**Sua integração nativa em sistemas como Windows, macOS e Linux possibilita uma comunicação eficiente, segura e confiável entre dispositivos, viabilizando o acesso à internet, o compartilhamento de recursos e o funcionamento harmonioso das redes.**

<!--Essa onipresença do TCP/IP no mundo da tecnologia destaca seu papel fundamental na interconectividade dos dispositivos e na capacidade de troca de informações em escala global.-->

---
<!-- _class: lead -->
# Obrigada pela atenção
tenham um ótimo dia!
🌻