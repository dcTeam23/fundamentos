---
marp: true
author: rodolfobertini
theme: default
paginate: true
header: 'Apresentação: O que é DNS?'
footer: 'Exercício Markdown - Rodolfo Bertini - Digital College - Turma FS23-Aldeota'
backgroundImage: "linear-gradient(to bottom, #000000, #0288d1, #0288d1, #000000)"
color: #120783
---
# O que é DNS?

## Introdução ao DNS

![bg fit opacity:10%][DIGITAL]

- O que é DNS?

<!-- 
Quase tudo na Internet começa com uma solicitação DNS. DNS é o diretório da Internet. Clique em um link, abra um aplicativo, envie um e-mail, e a primeira coisa que o dispositivo faz é perguntar ao diretório: Onde encontro isso?

Um servidor DNS é como uma enorme lista telefonica, que guarda o nome dos sites e informa para os computadores os números IP pertecentes aqueles nomes. 
Por exemplo, quando você digita  www.digitalcollege.com.br no seu navegador, o DNS é responsável por encontrar o endereço IP correspondente a esse nome e direcionar a sua conexão para o servidor certo. Assim, você não precisa memorizar números complicados para acessar os sites que deseja.
-->

- Significado: Sistema de Nomes de Domínio (Domain Name System)
- Função principal: Traduzir nomes de domínio em endereços IP

<!-- 
Todos os computadores da internet, de smartphones ou notebooks a servidores que distribuem conteúdo para grandes sites, se encontram e se comunicam entre si usando números. Esses números são conhecidos como endereços IP. Ao abrir um navegador e acessar um site, você não precisará lembrar-se de um longo número nem digitá-lo. Em vez disso, você poderá informar um nome de domínio, como digitalcollege.com.br, e ainda assim encontrar o que deseja. 
-->

---

## Funcionamento do DNS

![bg fit opacity:10% ][digital]

### Exemplo: <www.digitalcollege.com.br.>
- Hierarquia de DNS
- Raiz: "." 
<!-- 
No topo da hierarquia estão os 13 servidores raiz. Um servidor-raiz (root name server) é um servidor de nome para a zona raiz do DNS.  
-->
- Domínios de primeiro nível (TLDs)
<!--
Cada domínio é formado por nomes separados por pontos. O nome mais à direita é chamado de domínio de topo. Exemplos de domínios de topo são .com, .org, .net, .edu, .inf, .gov.
-->
     - ccTLD : .br .ar .pt .tv 
<!--
O domínio de topo de código de país[1] ou domínio nacional de nível superior (country code top-level domain - ccTLD), é o domínio de topo na Internet geralmente usado ou reservado para um país ou um território dependente. Ex.: .br .ar .pt .tv (Tuvalu)
-->
     - gTLD : .com .net .org / .mil .edu .gov
<!-- 
O domínios de topo genéricos. Eles se dividem em duas outras categorias: patrocinadas e não-patrocinadas. 

As não patrocinadas não precisam de qualquer associação ou organização patrocinadora para que seja possível a realização do registro, também não tem muitas restrições. Exemplos: .com, .net, .org, .biz, .info.

Já as gTLDs patrocinadas são aquelas que representam uma comunidade associada à extensão, como por exemplo: .edu, .gov, .mil, .aero, etc.
-->

- Domínios de segundo nível (exemplo.com) <!-- 
São servidores gerenciados por universidades e grandes empresas que por opção pode preferir montar seu próprio servidor DNS para abrigar seus registros e pegar registros de algum servidor de autoridade de algum servidor de serviço. 
-->

---

## Diagrama Funcionamento do DNS

![bg fit opacity:10%][digital]

![Grafico][grafico1]

---

## DNS para segurança de navegação

![bg fit opacity:10% ][digital]

- Filtragem de conteúdo: Bloqueio de sites indesejados
<!--


O DNS 1.1.1.1 precisou de pouco tempo para se tornar popular. A Cloudflare quer mais. Exatamente dois anos depois, a companhia decidiu lançar mais serviços do tipo, só que focados em segurança e no bloqueio de conteúdo adulto: os servidores de DNS 1.1.1.2 e 1.1.1.3, ambos gratuitos. 
-->
- Bloqueio de sites adultos: Restrição de acesso a conteúdo inadequado
- Prevenção contra sites maliciosos: Identificação de domínios perigosos

---

## Conclusão

![bg fit opacity:10% ][digital]

- O DNS é essencial para a navegação na Internet
- Permite tradução de nomes de domínio em endereços IP
- DNS pode ser usado para melhorar a segurança da navegação
- Filtragem de conteúdo, bloqueio de sites adultos e detecção de sites maliciosos são algumas das aplicações do DNS na segurança

[DIGITAL]: https://github.com/rodolfobertini/rodolfobertini/assets/132242813/6e603083-2be7-4ebc-a70a-cdf84e102e71

[GRAFICO1]: https://github.com/rodolfobertini/rodolfobertini/assets/132242813/c9fbe749-59b5-4c4e-8fdb-7e6dcac21609