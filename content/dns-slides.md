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

<!-- 
Um servidor DNS é como uma enorme lista telefonica, que guarda o nome dos sites e informa para os computadores os números IP pertecentes aqueles nomes. 
Por exemplo, quando você digita  www.digitalcollege.com.br no seu navegador, o DNS é responsável por encontrar o endereço IP correspondente a esse nome e direcionar a sua conexão para o servidor certo. Assim, você não precisa memorizar números complicados para acessar os sites que deseja.
-->
- O que é DNS?
- Significado: Sistema de Nomes de Domínio (Domain Name System)
- Função principal: Traduzir nomes de domínio em endereços IP

<!-- Todos os computadores da internet, abrangendo de smartphones ou laptops a servidores que distribuem conteúdo para grandes websites do comércio, se encontram e se comunicam entre si usando números. Esses números são conhecidos como endereços IP. Ao abrir um navegador e acessar um site, você não precisará lembrar-se de um longo número nem digitá-lo. Em vez disso, você poderá informar um nome de domínio, como exemplo.com, e ainda assim encontrar o que deseja. -->

---

## Funcionamento do DNS

![bg fit opacity:10% ][DIGITAL]

- Hierarquia de DNS
- Raiz: "." <!-- No topo da hierarquia estão os 13 servidores raiz. Um servidor-raiz (root name server) é um servidor de nome para a zona raiz do DNS (Domain Name System).  -->
- Domínios de primeiro nível (TLDs) <!-- Cada domínio é formado por nomes separados por pontos. O nome mais à direita é chamado de domínio de topo. Exemplos de domínios de topo são .com, .org, .net, .edu, .inf, .gov. -->
- Domínios de segundo nível (exemplo.com) <!-- São servidores gerenciados por universidades e grandes empresas que por opção pode preferir montar seu próprio servidor DNS para abrigar seus registros e pegar registros de algum servidor de autoridade de algum servidor de serviço. -->

---

## Diagrama Funcionamento do DNS

![bg fit opacity:10% ][DIGITAL]

![bg w:580](https://github.com/dcTeam23/fundamentos/assets/132242813/f84fef8a-dcf3-4aaf-9de4-7ee56b4957b0)

---

## DNS para segurança de navegação

![bg fit opacity:10% ][DIGITAL]

- Filtragem de conteúdo: Bloqueio de sites indesejados <!--  DNS 1.1.1.1 precisou de pouco tempo para se tornar popular. Mas a Cloudflare quer mais. Exatamente dois anos depois, a companhia decidiu lançar mais serviços do tipo, só que focados em segurança e no bloqueio de conteúdo adulto: os servidores de DNS 1.1.1.2 e 1.1.1.3, ambos gratuitos. -->
- Bloqueio de sites adultos: Restrição de acesso a conteúdo inadequado
- Prevenção contra sites maliciosos: Identificação de domínios perigosos

---

## Conclusão

![bg fit opacity:10% ][DIGITAL]

- O DNS é essencial para a navegação na Internet
- Permite tradução de nomes de domínio em endereços IP
- DNS pode ser usado para melhorar a segurança da navegação
- Filtragem de conteúdo, bloqueio de sites adultos e detecção de sites maliciosos são algumas das aplicações do DNS na segurança

[DIGITAL]: https://digitalcollege.com.br/wp-content/webp-express/webp-images/uploads/2022/05/logo-digital.png.webp
