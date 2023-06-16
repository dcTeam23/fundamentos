# Safe (Seguro)
Um método HTTP é seguro se ele não altera o estado do servidor. Em outras palavras, um método é seguro se ele leva a uma operação de somente leitura. Diversos métodos de HTTP são seguros: <u>GET</u>, HEAD, ou OPTIONS. Todos os métodos seguros também são idempotentes, mas nem todos os métodos idempotentes são seguros. Por exemplo, <u>PUT</u> e <u>DELETE</u> são ambos idempotentes, entretanto são inseguros.

Mesmo se métodos seguros possuem a semântica de somente leitura, servidores podem alterar o seu estado (e.g., eles podem manter log ou estatísticas). O que é importante aqui, é de que chamando um método seguro, o cliente não requer que o servidor mude seu estado, e portanto não gerará carga desnecessária ao servidor. Navegadores podem chamar métodos seguros sem medo de causarem nenhum dano ao servidor: isso permite a eles a possibilidade de fazer atividades como pré-carregamento sem nenhum risco. Web crawlers também usam métodos seguros.

Métodos seguros não servem somente para buscar arquivos estáticos, o servidor pode gerar uma resposta para um método seguro no voô, enquanto o script gerador garantir segurança: ele não deve ativar gatilhos externos, como ativar um pedido de compras em um site.

É responsabilidade da aplicação no servidor implementar a semântica segura corretamente, o servidor web em si, sendo Apache, nginx ou IIS, não pode forçar ela por si só. Em particular, a aplicação não deve permitir que requisições GET alterem seu estado.

Uma chamada a um método seguro, não alterando o estado do servidor: