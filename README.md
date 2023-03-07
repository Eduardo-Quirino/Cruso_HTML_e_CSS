# **HTML5 /CSS3**





# HTML

# categorias:

🔗https://developer.mozilla.org/en-US/docs/Web/HTML/Content_categories#flow_content

> O conteúdo de fluxo é uma categoria ampla que abrange a maioria dos elementos que podem estar dentro do
>
> ```html
>  <body>
> ```
>
> 
>
> **Os elementos de fluxo são:**
>
> ```html
> Os elementos de fluxo são:
> 
> <a>
> <abbr>
> <address>
> <article>
> <aside>
> <audio>
> <b>
> <bdo>
> <bdi>
> <blockquote>
> <br>
> <button>
> <canvas>
> <cite>
> <code>
> <command> Descontinuada
> <data>
> <datalist>
> <del>
> <details>
> <dfn>
> <div>
> <dl>
> <em>
> <embed>
> <fieldset>
> <figure>
> <footer>
> <form>
> <h1>
> <h2>
> <h3>
> <h4>
> <h5>
> <h6>
> <header>
> <hgroup>
> <hr>
> <i>
> <iframe>
> <img>
> <input>
> <ins>
> <kbd>
> <keygen> Descontinuada
> <label>
> <main>
> <map>
> <mark>
> <math>
> <menu>
> <meter>
> <nav>
> <noscript>
> <object>
> <ol>
> <output>
> <p>
> <picture>
> <pre>
> <progress>
> <q>
> <ruby>
> <s>
> <samp>
> <script>
> <section>
> <select>
> <small>
> <span>
> <strong>
> <sub>
> <sup>
> <svg>
> <table>
> <template>
> <textarea>
> <time>
> <u>
> <ul>
> <var>
> <video>
> <wbr>
> ```
>
> 
>
> **Alguns outros elementos pertencem a esta categoria, mas apenas se uma condição específica for cumprida:**
>
> ```html
> <area>, se for descendente de um <map>elemento
> <link>, se o atributo itemprop estiver presente
> <meta>, se o atributo itemprop estiver presente
> <style>, se oscoped Descontinuadaatributo está presente
> ```
>
> 
>
> **conteúdo de seccionamento**
>
> é um subconjunto do conteúdo do fluxo e pode ser usado em qualquer lugar onde o conteúdo do fluxo seja esperado. Os elementos pertencentes ao modelo de conteúdo de seção criam uma [seção na estrutura de tópicos atual](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements) que define o escopo dos [``](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header)elementos, [``](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer)elementos e [conteúdo do título](https://developer.mozilla.org/en-US/docs/Web/HTML/Content_categories#heading_content) .
>
> ```html
> Os elementos pertencentes a esta categoria são <article>, <aside>, <nav>e <section>.
> ```
>
> **Conteúdo do título**
>
> O conteúdo do título é um subconjunto do conteúdo do fluxo, que define o título de uma seção
>
> ```html
> Os elementos pertencentes a esta categoria são <h1>, <h2>, <h3>, <h4>, <h5>e <h6>.<hgroup>
> ```
>
> 
>
> **Frase de conteúdo**
>
> Conteúdo de frase é um subconjunto de conteúdo de fluxo que define o texto e a marcação que ele contém e pode ser usado em qualquer lugar em que o conteúdo de fluxo seja esperado.
>
> ```html
> Os elementos que pertencem a esta categoria são:
> 
> <abbr>
> <audio>
> <b>
> <bdo>
> <br>
> <button>
> <canvas>
> <cite>
> <code>
> <command> Descontinuada
> <data>
> <datalist>
> <dfn>
> <em>
> <embed>
> <i>
> <iframe>
> <img>
> <input>
> <kbd>
> <keygen> Descontinuada
> <label>
> <mark>
> <math>
> <meter>
> <noscript>
> <object>
> <output>
> <picture>
> <progress>
> <q>
> <ruby>
> <s>
> <samp>
> <script>
> <select>
> <small>
> <span>
> <strong>
> <sub>
> <sup>
> <svg>
> <textarea>
> <time>
> <u>
> <var>
> <video>
> <wbr>e texto simples (não consistindo apenas em caracteres de espaços em branco).
> Alguns outros elementos pertencem a esta categoria, mas apenas se uma condição específica for cumprida:
> 
> <a>, se contiver apenas conteúdo de frase
> <area>, se for descendente de um <map>elemento
> <del>, se contiver apenas conteúdo de frase
> <ins>, se contiver apenas conteúdo de frase
> <link>, se o atributo itemprop estiver presente
> <map>, se contiver apenas conteúdo de frase
> <meta>, se o atributo itemprop estiver presente
> ```
>
> 
>
> **conteúdo incorporado**
>
> Conteúdo incorporado é um subconjunto de conteúdo de fluxo que importa outro recurso ou insere conteúdo de outra linguagem de marcação ou namespace no documento e pode ser usado em qualquer lugar em que o conteúdo de fluxo seja esperado. 
>
> ```html
> pertencem a esta categoria incluem:
> 
> <audio>
> <canvas>
> <embed>
> <iframe>
> <img>
> <math>
> <object>
> <picture>
> <svg>
> <video>.
> ```
>
> **conteúdo interativo**
>
> ```html
> Os elementos que pertencem a esta categoria incluem:
> 
> <a>
> <button>
> <details>
> <embed>
> <iframe>
> <keygen> Descontinuada
> <label>
> <select>, e <textarea>.
> Alguns elementos pertencem a esta categoria apenas em condições específicas:
> 
> <audio>, se o controlsatributo estiver presente
> <img>, se o usemapatributo estiver presente
> <input>, se o atributo type não estiver no estado oculto
> <object>, se o usemapatributo estiver presente
> <video>, se o controlsatributo estiver presente
> ```
>
> **Conteúdo associado ao formulário**
>
> O conteúdo associado ao formulário é um subconjunto de conteúdo de fluxo que compreende elementos que possuem um proprietário de formulário, exposto por um atributo de **formulário e pode ser usado em qualquer lugar em que o conteúdo de fluxo seja esperado.** Um proprietário de formulário é o elemento que o contém [``](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)ou o elemento cujo id é especificado no atributo de **formulário .**
>
> ```html
> 	<button>
> <fieldset>
> <input>
> <keygen> Descontinuada
> <label>
> <meter>
> <object>
> <output>
> <progress>
> <select>
> <textarea>
> Esta categoria contém várias subcategorias:
> 
> listado
> Elementos listados nas coleções form.elementse fieldset.elements. Contém <button>, <fieldset>, <input>,<keygen> Descontinuada, <object>, <output>, <select>e <textarea>.
> 
> rotulável
> Elementos que podem ser associados a <label>elementos. Contém <button>, <input>,<keygen> Descontinuada, <meter>,<output> , <progress>, <select>e <textarea>.
> 
> submissível
> Elementos que podem ser usados ​​para construir o conjunto de dados do formulário quando o formulário é enviado. Contém <button>, <input>,<keygen> Descontinuada,<object> , <select>e <textarea>.
> 
> reiniciável
> Elementos que podem ser afetados quando um formulário é redefinido. contém<input> ,<keygen> Descontinuada, <output>, <select>e<textarea>.
> ```
>
> **Elementos de suporte de script**
>
> **Elementos de suporte de script** são elementos que não contribuem diretamente para a saída renderizada de um documento. Em vez disso, eles servem para dar suporte a scripts, seja contendo ou especificando o código do script diretamente ou especificando os dados que serão usados pelos scripts.
>
> ```html
> Os elementos de suporte do script são:
> 
> <script>
> <template>
> ```
>
> ```html
> elementos
> A seguir está uma lista completa de todos os elementos HTML "nível de bloco" (embora "nível de bloco" não seja tecnicamente definido para elementos que são novos em HTML5).
> 
> <address>
> Informações de Contato.
> 
> <article>
> Conteúdo do artigo.
> 
> <aside>
> Conteúdo à parte.
> 
> <blockquote>
> Citação longa ("bloco").
> 
> <details>
> Widget de divulgação.
> 
> <dialog>
> Caixa de diálogo.
> 
> <dd>
> Descreve um termo em uma lista de descrição.
> 
> <div>
> Divisão de documentos.
> 
> <dl>
> Lista de descrição.
> 
> <dt>
> Termo da lista de descrição.
> 
> <fieldset>
> Rótulo de conjunto de campos.
> 
> <figcaption>
> Legenda da figura.
> 
> <figure>
> Agrupa o conteúdo de mídia com uma legenda (consulte Recursos <figcaption>).
> 
> <footer>
> Seção ou rodapé da página.
> 
> <form>
> Formulário de entrada.
> 
> <h1>, <h2>, <h3>, <h4>, <h5>,<h6>
> Níveis de título 1-6.
> 
> <header>
> Cabeçalho de seção ou página.
> 
> <hgroup>
> Informações de cabeçalho de grupos.
> 
> <hr>
> Régua horizontal (linha divisória).
> 
> <li>
> Item de lista.
> 
> <main>
> Contém o conteúdo central exclusivo deste documento.
> 
> <nav>
> Contém links de navegação.
> 
> <ol>
> Lista ordenada.
> 
> <p>
> Parágrafo.
> 
> <pre>
> Texto pré-formatado.
> 
> <section>
> Seção de uma página da web.
> 
> <table>
> Mesa.
> 
> <ul>
> Lista não ordenada.
> ```

>## Atributos Globais
>
>A `<meta>`tag também suporta os [Atributos Globais em HTML](https://www.w3schools.com/tags/ref_standardattributes.asp) .
>
>```html
>Mais exemplos:
>
>Definir palavras-chave para motores de busca:
><meta name="keywords" content="HTML, CSS, JavaScript">
>
>Defina uma descrição da sua página da web:
><meta name="description" content="Free Web tutorials for HTML and CSS">
>
>Defina o autor de uma página:
><meta name="author" content="John Doe">
>
>Atualize o documento a cada 30 segundos:
><meta http-equiv="refresh" content="30">
>
>Configurando a janela de visualização para que seu site tenha uma boa aparência em todos os dispositivos:
><meta name="viewport" content="width=device-width, initial-scale=1.0">
>
>```
>
>
>
># Configurando a Janela de Visualização
>
>```html
>Você deve incluir o seguinte <meta>elemento em todas as suas páginas da web:
>
><meta name="viewport" content="width=device-width, initial-scale=1.0">
>Isso fornece ao navegador instruções sobre como controlar as dimensões e o dimensionamento da página.
>
>A width=device-width parte define a largura da página para seguir a largura da tela do dispositivo (que varia dependendo do dispositivo).
>
>A initial-scale=1.0 parte define o nível de zoom inicial quando a página é carregada pela primeira vez pelo navegador.
>
>Aqui está um exemplo de uma página web sem a meta tag viewport e a mesma página web com a meta tag viewport:
>```
>
>

[^Referência de elementos HTML]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element



# **CSS**  

[^Referencia CSS]: https://developer.mozilla.org/en-US/docs/Web/CSS



> Pode ser usado para retornar um novo [`CSSUnitValue`](https://developer.mozilla.org/en-US/docs/Web/API/CSSUnitValue)com um valor do número do parâmetro das unidades do nome do método de função de fábrica usado.
>
> ```css
> CSS.em(3); // CSSUnitValue {value: 3, unit: "em"}
> 
> ```
>
> ### [Anatomia de um conjunto de regras CSS](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics#anatomy_of_a_css_ruleset)
>
> Vamos dissecar o código CSS para texto de parágrafo vermelho para entender como ele funciona:
>
> <img src="https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/css-declaration-small.png" alt="CSS p declaração cor vermelha" style="zoom:50%;" />
>

Jogos para exercitar Frex Box e Grid 

[^Flexbox Froggy]: https://flexboxfroggy.com/
[^Grid Garden]: https://cssgridgarden.com/

