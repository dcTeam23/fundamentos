# Métodos de requisição HTTP

<p>O protocolo HTTP define um conjunto de métodos de requisição responsáveis por indicar a ação a ser executada para um dado recurso. Embora esses métodos possam ser descritos como substantivos, eles também são comumente referenciados como HTTP Verbs (Verbos HTTP). Cada um deles implementa uma semântica diferente, mas alguns recursos são compartilhados por um grupo deles, como por exemplo, qualquer método de requisição pode ser do tipo <a href="safepag.md" rel="next">safe</a>, idempotent ou cacheable (en-US).</p>
<dl>
<dt id="get">
<code>Get</code>
</dt>
<dd>
    <p>O método <code>GET</code> solicita a representação de um recurso específico. Requisições utilizando o método <code>GET</code> devem retornar apenas dados.</p>
  </dd>
  <dt id="head">
<code>HEAD</code></dt>
<dd>
    <p>O método <code>HEAD</code> solicita uma resposta de forma idêntica ao método <code>GET</code>, porém sem conter o corpo da resposta.</p>
  </dd>
  <dt id="post">
<code>POST</code>
</dt>
<dd>
    <p>O método <code>POST</code> é utilizado para submeter uma entidade a um recurso específico, frequentemente causando uma mudança no estado do recurso ou efeitos colaterais no servidor.</p>
  </dd>
  <dt id="put">
<code>PUT</code>
</dt>
<dd>
    <p>O método <code>PUT</code> substitui todas as atuais representações do recurso de destino pela carga de dados da requisição.</p>
  </dd>
  <dt id="delete">
<code>DELETE</code>
</dt>
<dd>
    <p>O método <code>DELETE</code> remove um recurso específico.</p>
  </dd>
  <dt id="connect">
<code>CONNECT</code>
</dt>
<dd>
    <p>O método <code>CONNECT</code> estabelece um túnel para o servidor identificado pelo recurso de destino.</p>
  </dd>
  <dt id="options">
<code>OPTIONS</code>
</dt>
<dd>
    <p>O método <code>OPTIONS</code> é usado para descrever as opções de comunicação com o recurso de destino.</p>
  </dd>
<dt id="trace">
<code>TRACE</code>
</dt>
<dd>
    <p>O método <code>TRACE</code> executa um teste de chamada <em>loop-back</em> junto com o caminho para o recurso de destino.</p>
  </dd>
  <dt id="patch">
<code>PATCH</code>
 </dt>
<dd>
    <p>O método <code>PATCH</code> é utilizado para aplicar modificações parciais em um recurso.</p>
  </dd>
</dl>