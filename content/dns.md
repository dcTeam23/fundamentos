<!-- Conteúdo do PDF da Digital College -->
# **DNS** ***(Domain name system)***

## Diagrama

### Explicação da Hierarquia DNS

```mermaid

---
title: Explicação da Hierarquia DNS
---

stateDiagram-v2
state "Raiz" as ServidorRaiz1
state "br" as Altonivel1
state "com" as DNSConAutoridade1
state "gov" as DNSConAutoridade2
state "digitalcollege" as Site1
state "dados" as Site2
state "aldeota" as ServidorRedeSede1
state "sul" as ServidorRedeSede2
state "10andar" as ServidorRedeAndar1
state "1andar" as ServidorRedeAndar2
state "larrypage" as ServidorSala1
state "recepcao" as ServidorSala2
state "pcdoabraao" as MaquinaDesktop1
state "pcdoaluno01"as MaquinaDesktop2
state "pcdarecpcao" as MaquinaDesktop3

    ServidorRaiz1 --> Altonivel1
    Altonivel1 --> DNSConAutoridade1
    Altonivel1 --> DNSConAutoridade2
    DNSConAutoridade1 --> Site1
    DNSConAutoridade2 --> Site2
    Site1 --> ServidorRedeSede1
    Site1 --> ServidorRedeSede2
    ServidorRedeSede1 --> ServidorRedeAndar1
    ServidorRedeSede1 --> ServidorRedeAndar2
    ServidorRedeAndar1 -->  ServidorSala1
    ServidorRedeAndar2 --> ServidorSala2
    ServidorSala1 --> MaquinaDesktop1
    ServidorSala1 --> MaquinaDesktop2
    ServidorSala2 --> MaquinaDesktop3
    
state "Servidores-Raiz" as ServidorRaiz1
state "Servidores de domínio de topo (TLD)" as Altonivel1
state "Servidores com autoridade" as DNSConAutoridade1
state "Servidores com autoridade" as DNSConAutoridade2
state "Servidor Principal do Site (SLD)" as Site1
state "Servidor Principal do Site(SLD)" as Site2
state "Servidor da Sede Aldeota (Subdomínio)" as ServidorRedeSede1
state "Servidor da Sede Sul(Subdomínio)" as ServidorRedeSede2
state "Router do 10 Andar" as ServidorRedeAndar1
state "Router do 1 Andar" as ServidorRedeAndar2
state "Wifi da Sala Larry Page" as ServidorSala1
state "Wifi da recepcao" as ServidorSala2
state "Nome do PC do Professor" as MaquinaDesktop1
state "Nome do PC de Aluno 01"as MaquinaDesktop2
state "Nome do PC da Recepçao" as MaquinaDesktop3
```

### Site da Internet

Exemplo de endereço completo de uma maquina na rede
pcdoabraao.larrypage.10andar.aldeota.digitalcollege.com.br

```mermaid
stateDiagram-v2
state "Raiz" as ServidorRaiz1
state "br" as Altonivel1
state "com" as DNSConAutoridade1
state "gov" as DNSConAutoridade2
state "digitalcollege" as Site1
state "dados" as Site2
state "aldeota" as ServidorRedeSede1
state "sul" as ServidorRedeSede2
state "10andar" as ServidorRedeAndar1
state "1andar" as ServidorRedeAndar2
state "larrypage" as ServidorSala1
state "recepcao" as ServidorSala2
state "pcdoabraao" as MaquinaDesktop1
state "pcdoaluno01"as MaquinaDesktop2
state "pcdarecpcao" as MaquinaDesktop3

    ServidorRaiz1 --> Altonivel1
    Altonivel1 --> DNSConAutoridade1
    Altonivel1 --> DNSConAutoridade2
    DNSConAutoridade1 --> Site1
    DNSConAutoridade2 --> Site2
    Site1 --> ServidorRedeSede1
    Site1 --> ServidorRedeSede2
    ServidorRedeSede1 --> ServidorRedeAndar1
    ServidorRedeSede1 --> ServidorRedeAndar2
    ServidorRedeAndar1 -->  ServidorSala1
    ServidorRedeAndar2 --> ServidorSala2
    ServidorSala1 --> MaquinaDesktop1
    ServidorSala1 --> MaquinaDesktop2
    ServidorSala2 --> MaquinaDesktop3

```

### Analogia com Localização no Mundo Real

```mermaid
stateDiagram-v2
state "Mundo" as ServidorRaiz1
state "Brasil" as Altonivel1
state "Ceará" as DNSConAutoridade1
state "Pernambuco" as DNSConAutoridade2
state "Fortaleza" as Site1
state "Recife" as Site2
state "Digital College - Sede Aldeota" as ServidorRedeSede1
state "Digital College - Sede Sul" as ServidorRedeSede2
state "10 Andar" as ServidorRedeAndar1
state "1 Andar" as ServidorRedeAndar2
state "Sala Larry Page" as ServidorSala1
state "Recepção Digital College" as ServidorSala2
state "Mesa do Professor" as MaquinaDesktop1
state "Bancada dos Alunos" as MaquinaDesktop2
state "Bancada da Recepção" as MaquinaDesktop3

    ServidorRaiz1 --> Altonivel1
    Altonivel1 --> DNSConAutoridade1
    Altonivel1 --> DNSConAutoridade2
    DNSConAutoridade1 --> Site1
    DNSConAutoridade2 --> Site2
    Site1 --> ServidorRedeSede1
    Site1 --> ServidorRedeSede2
    ServidorRedeSede1 --> ServidorRedeAndar1
    ServidorRedeSede1 --> ServidorRedeAndar2
    ServidorRedeAndar1 -->  ServidorSala1
    ServidorRedeAndar2 --> ServidorSala2
    ServidorSala1 --> MaquinaDesktop1
    ServidorSala1 --> MaquinaDesktop2
    ServidorSala2 --> MaquinaDesktop3
```

### Mesclado

```mermaid
stateDiagram-v2
state "Mundo" as ServidorRaiz1
state "Brasil" as Altonivel1
state "Ceará" as DNSConAutoridade1
state "Pernambuco" as DNSConAutoridade2
state "Fortaleza" as Site1
state "Recife" as Site2
state "Digital College - Sede Aldeota" as ServidorRedeSede1
state "Digital College - Sede Sul" as ServidorRedeSede2
state "10 Andar" as ServidorRedeAndar1
state "1 Andar" as ServidorRedeAndar2
state "Sala Larry Page" as ServidorSala1
state "Recepção Digital College" as ServidorSala2
state "Mesa do Professor" as MaquinaDesktop1
state "Bancada dos Alunos" as MaquinaDesktop2
state "Bancada da Recepção" as MaquinaDesktop3

    ServidorRaiz1 --> Altonivel1
    Altonivel1 --> DNSConAutoridade1
    Altonivel1 --> DNSConAutoridade2
    DNSConAutoridade1 --> Site1
    DNSConAutoridade2 --> Site2
    Site1 --> ServidorRedeSede1
    Site1 --> ServidorRedeSede2
    ServidorRedeSede1 --> ServidorRedeAndar1
    ServidorRedeSede1 --> ServidorRedeAndar2
    ServidorRedeAndar1 -->  ServidorSala1
    ServidorRedeAndar2 --> ServidorSala2
    ServidorSala1 --> MaquinaDesktop1
    ServidorSala1 --> MaquinaDesktop2
    ServidorSala2 --> MaquinaDesktop3
    
state "Raiz" as ServidorRaiz1
state "br" as Altonivel1
state "com" as DNSConAutoridade1
state "gov" as DNSConAutoridade2
state "digitalcollege" as Site1
state "dados" as Site2
state "aldeota" as ServidorRedeSede1
state "sul" as ServidorRedeSede2
state "10andar" as ServidorRedeAndar1
state "1andar" as ServidorRedeAndar2
state "larrypage" as ServidorSala1
state "recepcao" as ServidorSala2
state "pcdoabraao" as MaquinaDesktop1
state "pcdoaluno01"as MaquinaDesktop2
state "pcdarecpcao" as MaquinaDesktop3
```
