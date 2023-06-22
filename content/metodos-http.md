# Métodos de requisição HTTP

## O que é HTTP?

O HTTP é um protocolo de comunicação, ou seja, uma convenção de regras e padrões que controla e possibilita uma conexão e troca de dados entre dois sistemas computacionais.

É baseado no modelo de cliente-servidor, ou seja, de um lado, um navegador requisita um determinado dado, e do outro, um computador (ou servidor) retorna a informação desejada (ou não, caso não ela seja encontrada, ocorra um erro ou não exista).

Criado na década de 1990, o HTTP surgiu da necessidade de se padronizar a troca de informações pela internet, de uma maneira que fosse leve, rápida e compreendida por todos os computadores conectados à rede.

## Como funciona?

Clientes e servidores se comunicam pela internet trocando mensagens individuais. As mensagens enviadas pelo cliente, geralmente navegadores web, são chamadas de requisições (requests). As réplicas dos servidores são chamadas de respostas (responses), podendo conter algum conteúdo (como arquivos HTML) além de informações sobre o status da requisição.

Usuários comuns não lidam diretamente com essas mensagens. Elas são executadas e tratadas por navegadores, programas ou servidores proxy e web. Estes serviços proveem mensagens HTTP por meio de arquivos de configuração (no caso de servidores), APIs (para navegadores) e outras interfaces.

Requisições e respostas HTTP são estruturadas da seguinte forma:
- Uma linha única inicial (start-line) que descreve as requisições a serem implementadas ou seu status de sucesso (ou falha);
- Um conjunto opcional de cabeçalhos HTTP especificando a requisição ou descrevendo o conteúdo da mensagem;
- Uma linha em branco apenas para indicar que toda a meta-informação da requisição já foi enviada;
- O conteúdo da mensagem, chamado de corpo (body), conforme solicitado pela requisição. A presença ou não do corpo e seu tamanho são especificados pelos cabeçalhos HTTP (head).

A versão atual do protocolo HTTP é chamada de HTTP/2, divulgada em 2014 e tendo sido sua primeira revisão desde o protocolo HTTP/1.1, padronizado em 1997. Essa versão trouxe várias melhorias de segurança e desempenho, visando também a crescente utilização de smartphones na navegação pela internet.

## Métodos HTTP e segurança
O protocolo HTTP define oito métodos de requisição (GET, POST, PUT, DELETE, HEAD, TRACE, OPTIONS e CONNECT) para indicar qual ação deve ser realizada no recurso especificado.

Os métodos GET e POST, PUT e DELETE são os mais utilizados em aplicações web. Um servidor HTTP deve implementar, pelo menos, os métodos GET e HEAD para ser funcional.

O HTTP funciona em conjunto com algum outro protocolo de transferência, sendo o TCP/IP (Transmission Control Protocol) o mais comum. Os recursos enviados por HTTP são identificados e localizados na rede por URLs (Uniforme Resource Locators), o tipo mais comum de identificador de recursos uniforme (URI, da sigla em inglês) para a web.

Uma característica importante do protocolo HTTP que todo usuário deve se atentar é quanto as conexões seguras. Na web, ela normalmente é feita pelo HTTPS (Hyper Text Transfer Protocol Secure), uma implementação do protocolo HTTP sobre uma camada adicional de encriptação.

Essa camada transmite os dados de forma criptografada, além de permitir a verificação de autenticidade do servidor e do cliente por meio de certificados digitais. No entanto, isso nem sempre significa que o site em si é seguro, mas apenas que a conexão está protegida do acesso de terceiros.

## Definição:
<dl>
<dt id="get">
<code>Get</code>
</dt>
<dd>
    O método <code>GET</code> solicita a representação de um recurso específico. Requisições utilizando o método <code>GET</code> devem retornar apenas dados.
  </dd>
  <dt id="head">
<code>HEAD</code></dt>
<dd>
    O método <code>HEAD</code> solicita uma resposta de forma idêntica ao método <code>GET</code>, porém sem conter o corpo da resposta.
  </dd>
  <dt id="post">
<code>POST</code>
</dt>
<dd>
    O método <code>POST</code> é utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.
  </dd>
  <dt id="put">
<code>PUT</code>
</dt>
<dd>
    O método <code>PUT</code> substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.
  </dd>
  <dt id="delete">
<code>DELETE</code>
</dt>
<dd>
    O método <code>DELETE</code> remove um recurso específico.
  </dd>
  <dt id="connect">
<code>CONNECT</code>
</dt>
<dd>
    O método <code>CONNECT</code> estabelece um túnel para o servidor identificado pelo recurso de destino.
  </dd>
  <dt id="options">
<code>OPTIONS</code>
</dt>
<dd>
    O método <code>OPTIONS</code> é usado para descrever as opções de comunicação com o recurso de destino.
  </dd>
<dt id="trace">
<code>TRACE</code>
</dt>
<dd>
    O método <code>TRACE</code> executa um teste de chamada <em>loop-back</em> junto com o caminho para o recurso de destino.
  </dd>
  <dt id="patch">
<code>PATCH</code>
 </dt>
<dd>
    O método <code>PATCH</code> é utilizado para aplicar modificações parciais em um recurso.
  </dd>
</dl>