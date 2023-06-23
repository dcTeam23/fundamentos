---
marp: true
theme: gaia
_class: lead
paginate: true
color: #000
BackgroundColor: #fff
BackgroundImage: url('https://media.licdn.com/dms/image/C4E0DAQEG5kUbG3kzQw/learning-public-crop_288_512/0/1567117705208?e=2147483647&v=beta&t=aj4p8bK0oDlZwEqvaS5Xc2y4mA8vdzJLY95OSCwYzJs')
---

# Modelo Osi

---

# O que é o modelo Osi? 


**OSI é a sigla para Open Systems Interconnection – ou Sistemas Abertos de Interconexão, em português. Basicamente, esse modelo consiste em um padrão para os protocolos de rede. Simplificando ainda mais, ele determina quais regras de comunicação devem ser seguidas para a conexão entre dois ou mais computadores.**

---
# A importancia do Modelo OSI
**Por que o modelo OSI é importante? Embora a internet moderna não siga estritamente o modelo OSI (segue mais de perto um conjunto mais simples de protocolos da internet), o modelo continua sendo muito útil para solucionar problemas de Rede. Seja uma pessoa que não consegue colocar seu notebook na internet ou um site que esteja inativo para milhares de usuários, o modelo OSI pode ajudar a resolver e isolar a fonte do problema. Se o problema puder ser reduzido a uma camada específica do modelo, muito trabalho desnecessário poderá ser evitado.**

---

# As 7 Camadas

![bg right](https://github.com/dcTeam23/fundamentos/assets/608731/9f83db27-16f0-46b1-902c-6ef0e6d4c2ca)


---

# Física


**Essa camada é uma das mais importantes do modelo OSI. Isso porque ela é responsável pela ligação de cabos físicos ou sem fio entre toda a rede. Outra característica é que a transmissão dos dados brutos é feita a partir daqui.**

---

# Enlace

**É nesta parte que ocorre a conexão entre dois nós conectados fisicamente em uma rede. Essa camada do modelo OSI é composta por duas partes: o controle de enlace lógico (LLC), que identifica e checa erros; e o media access control (MAC), que usa endereços MAC para conectar e definir permissões nos dispositivos.**

---

# Redes

**A responsabilidade dessa camada é a de transmitir dados entre um host a outro em diferentes redes. Do mesmo modo, é válido apontar que outra importante função é a de cuidar dos pacotes de roteamento, selecionando o caminho mais curto para isso.**

---

# Transporte

**A camada de transporte pega os dados e os quebra em segmentos. Em seguida, na parte final, junta tudo novamente para que as informações alcancem a camada de sessão. Ela transmite através de protocolos como o TCP e UDP.**

---

# Sessão

**É aqui que o modelo OSI cria os canais de comunicação entre dispositivos. Como o próprio nome diz, essa camada é responsável por abrir sessões e garantir que tudo esteja funcional para que dados possam ser transferidos.**

---

# Apresentação

**Essa camada faz a preparação dos dados para a camada de aplicações. Ou seja, garante que as informações possam ser usadas e faz toda a criptografia.**

---

# Aplicação 

**Oferece protocolos que permitem que um software envie e receba informações significativas para os usuários. Por isso, é altamente usada por itens como navegador de internet e cliente de e-mail. Alguns exemplos: HTTP, FTP, POP e DNS.**