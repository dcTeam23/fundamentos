---
marp:  true
---
<!--
theme: default
paginate: true
-->

<!-- _backgroundColor: orange -->
<!-- _color: black -->
# Fundamentos CSS
![bg left](css.jpg)

---

### O que é o CSS e como ele funciona.

###### O CSS "Cascading Style Sheets" (Folhas de Estilo em Cascata) é uma linguagem de estilo ou uma linguagem de marcação utilizada para definir a aparência e o layout de documentos HTML (ou outros tipos de documentos XML). Ele separa a apresentação visual do conteúdo estrutural de um documento, permitindo que você controle a forma como os elementos HTML são exibidos em um navegador.
###### O CSS permite separar o conteúdo de um documento HTML de sua apresentação visual. Em vez de incluir diretamente estilos no código HTML, você pode usar o CSS para especificar como os elementos HTML devem ser exibidos em um navegador. Isso proporciona uma maior flexibilidade e facilidade na criação de designs consistentes em várias páginas e sites.


---

# Existem três maneiras principais de aplicar CSS a uma página HTML:

* Estilos embutidos: Você pode definir estilos diretamente no código HTML usando a tag `<style>`. Os estilos são especificados dentro dessa tag, geralmente na seção `<head>` do documento HTML. Isso permite que você defina estilos específicos para um documento individual.
* Estilos internos: Você também pode incluir um arquivo CSS separado usando a tag `<link>`. Essa tag é colocada na seção `<head>` do documento HTML e faz referência ao arquivo CSS externo, permitindo que você defina estilos que se aplicam a várias páginas.
* Estilos externos: É possível escrever todo o código CSS em um arquivo separado com extensão `.css` e referenciá-lo usando a tag `<link>`. Essa abordagem é útil para manter o código CSS organizado e reutilizável em diferentes páginas.


---

O CSS permite que você defina estilos para diferentes elementos HTML, como texto, imagens, caixas, links e outros. Você pode especificar cores, fontes, tamanhos, espaçamentos, posicionamento e muito mais. O CSS também suporta o uso de seletores para aplicar estilos a elementos específicos com base em sua classe, ID ou hierarquia no documento HTML.
Através da combinação do HTML para estrutura e conteúdo e do CSS para a apresentação visual, é possível criar páginas da web esteticamente agradáveis, responsivas e consistentes. O CSS desempenha um papel fundamental no design web moderno, permitindo uma personalização completa da aparência dos elementos de uma página...


---

# Os fundamentos do CSS:

---
### O CSS é baseado em um conceito chamado "Seletores".

1. Seletores: Os seletores são utilizados para identificar os elementos HTML aos quais você deseja aplicar estilos. Existem diferentes tipos de seletores, como seletores de tag, seletores de classe, seletores de ID e seletores de atributo.
2. Propriedades: As propriedades são os atributos que você define para os elementos selecionados. Elas especificam como um elemento deve ser apresentado, como cor, tamanho, margens, bordas, etc.
3. Valores: Cada propriedade do CSS tem um valor correspondente. Os valores podem ser palavras-chave, como "bold" (negrito) ou "center" (centralizado), ou podem ser valores numéricos, como "10px" ou "2em", para especificar tamanho e dimensões.

---
4. Declarações: Uma declaração CSS é composta por uma propriedade e um valor, separados por dois pontos (:), e finalizados por um ponto e vírgula (;). Por exemplo, `color: blue;`.
5. Regras: Uma regra CSS é formada por um seletor, seguido por um bloco de declarações envolvidas por chaves {}. Por exemplo:

---

css
seletor {
  propriedade: valor;
  propriedade: valor;
}


---

6. Cascata: O termo "Cascading" (em cascata) no nome do CSS refere-se ao mecanismo de prioridade e herança de estilos. Quando vários estilos conflitam, o CSS segue uma ordem de prioridade para determinar qual estilo será aplicado. Além disso, os estilos definidos para elementos pais podem ser herdados pelos elementos filhos.
7. Especificidade: A especificidade refere-se à regra que determina qual estilo será aplicado quando múltiplas regras conflitam para o mesmo elemento. Cada seletor possui um valor de especificidade, e o CSS utiliza esses valores para resolver os conflitos e aplicar o estilo correto.
8. Box Model: O Box Model é um conceito fundamental do CSS que define como os elementos HTML são renderizados em caixas retangulares. Cada elemento é composto por margem, borda, preenchimento (padding) e conteúdo, e você pode controlar o tamanho e o espaçamento dessas partes usando propriedades CSS.
Esses são os principais fundamentos do CSS. Compreendendo esses conceitos, você estará pronto para começar a criar estilos personalizados para suas páginas da web.
Vou fornecer um exemplo básico de um trabalho utilizando CSS. Neste exemplo, vamos criar uma página com um título, um parágrafo e um botão estilizados.
---
### Primeiro, vamos criar um arquivo HTML chamado "trabalho.html" e adicionar o seguinte código:

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="trabalho.css">
</head>
<body>
  <h1>Título do Trabalho</h1>
  <p>Este é um parágrafo de exemplo.</p>
  <button>Meu Botão</button>
</body>
</html>
```
---
### Agora, vamos criar um arquivo CSS chamado "trabalho.css" e adicionar o seguinte código:

```css
/* Estilizando o título */
h1 {
  color: blue;
  font-size: 24px;
  text-align: center;
}

/* Estilizando o parágrafo */
p {
  color: gray;
  font-size: 16px;
}

/* Estilizando o botão */
button {
  background-color: green;
  color: white;
  font-size: 18px;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
}
```
---

Agora, abra o arquivo "trabalho.html" em um navegador e você verá o título, o parágrafo e o botão estilizados de acordo com as regras CSS definidas.
Neste exemplo, definimos as seguintes propriedades CSS:
- Para o título (`<h1>`), definimos a cor do texto como azul, o tamanho da fonte como 24 pixels e o alinhamento centralizado.
- Para o parágrafo (`<p>`), definimos a cor do texto como cinza e o tamanho da fonte como 16 pixels.
- Para o botão (`<button>`), definimos a cor de fundo como verde, a cor do texto como branco, o tamanho da fonte como 18 pixels, o preenchimento interno de 10 pixels no topo e na base e 20 pixels nas laterais, removemos a borda padrão e definimos o cursor do mouse como ponteiro ao passar sobre o botão.
---


