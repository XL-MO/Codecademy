
HTML (HyperText Markup Language) é usado para fornecer conteúdo a uma página da web e instruir os navegadores sobre como estruturar
esse conteúdo.
O conteúdo de um elemento HTML são as informações entre as tags
de abertura e fechamento de um elemento.
<h1> Codecademy é incrível! 🙂 </h1> _ _
O <li> elemento de item de lista cria itens de lista dentro:
Listas ordenadas <ol>
Listas não ordenadas <ul>
<ol> _ _
 < li > Siga para leste na Prince St </ li >
 < li > Vire à esquerda na Elizabeth </ li >
</ ol >
<ul> _ _
 < li > Biscoitos </ li >
 < li > Leite </ li >
</ul> _ _
O <video> elemento incorpora um reprodutor de mídia para
reprodução de vídeo. O src atributo conterá o URL do vídeo.
Adicionar o controls atributo exibirá os controles de vídeo no media
player.
Nota: O conteúdo dentro da tag de abertura e fechamento é
mostrado como substituto em navegadores que não suportam o
elemento.
< video src = " test-video.mp4 " controles >
 Vídeo não suportado
</ vídeo >
The <em> element emphasizes text and browsers will usually
italicize the emphasized text by default.
<p>This <em>word</em> will be emphasized in
italics.</p>
/ Fundamentos de HTML
Aprenda HTML: Elementos
HTML
Conteúdo do Elemento
<li> Elemento de item de lista
<video> Elemento de vídeo
<em> Elemento de ênfase
Folhas de dicas
The <ol> ordered list element creates a list of items in sequential
order. Each list item appears numbered by default.
<ol>
 <li>Preheat oven to 325 F </li>
 <li>Drop cookie dough 🍪</li>
 <li>Bake for 15 min ⏰</li>
</ol>
The <div> element is used as a container that divides an HTML
document into sections and is short for “division”. <div> elements
can contain flow content such as headings, paragraphs, links, images,
etc.
<div>
 <h1>A section of grouped elements</h1>
 <p>Here’s some text for the section</p>
</div>
<div>
 <h1>Second section of grouped elements</h1>
 <p>Here’s some text</p>
</div>
HTML is organized into a family tree structure. HTML elements can
have parents, grandparents, siblings, children, grandchildren, etc.
<body>
 <div>
 <h1>It's div's child and body's
grandchild</h1>
 <h2>It's h1's sibling</h2>
 </div>
</body>
An HTML closing tag is used to denote the end of an HTML element.
The syntax for a closing tag is a left angle bracket < followed by a
forward slash / then the element name and a right angle bracket to
close > .
<body>
 ...
</body>
HTML attributes consist of a name and a value using the following
syntax: name="value" and can be added to the opening tag of an
HTML element to configure or change the behavior of the element.
<elementName name="value"></elementName>
<ol> Ordered List Element
<div> Div Element
HTML Structure
Closing Tag
Attribute Name and Values
The <br> line break element will create a line break in text and is
especially useful where a division of text is required, like in a postal
address. The line break element requires only an opening tag and
must not have a closing tag.
A line break haiku.<br>
Poems are a great use case.<br>
Oh joy! A line break.
HTML image <img> elements embed images in documents. The
src attribute contains the image URL and is mandatory. <img> is
an empty element meaning it should not have a closing tag.
<img src="image.png">
HTML can use six different levels of heading elements. The heading
elements are ordered from the highest level <h1> to the lowest
level <h6> .
<h1>Breaking News</h1>
<h2>This is the 1st subheading</h2>
<h3>This is the 2nd subheading</h3>
...
<h6>This is the 5th subheading</h6>
The <p> paragraph element contains and displays a block of text. <p>This is a block of text! Lorem ipsum dolor sit
amet, consectetur adipisicing elit.</p>
In HTML, specific and unique id attributes can be assigned to
different elements in order to differentiate between them.
When needed, the id value can be called upon by CSS and
JavaScript to manipulate, format, and perform specific instructions on
that element and that element only. Valid id attributes should begin
with a letter and should only contain letters ( a-Z ), digits ( 0-9 ),
hyphens ( - ), underscores ( _ ), and periods ( . ).
<h1 id="A1">Hello World</h1>
HTML attributes are values added to the opening tag of an element to
configure the element or change the element’s default behavior. In
the provided example, we are giving the <p> (paragraph) element a
unique identifier using the id attribute and changing the color of the
default text using the style attribute.
<p id="my-paragraph" style="color: green;">Here’s
some text for a paragraph that is being altered by
HTML attributes</p>
<br> Line Break Element
<img> Image Element
<h1> - <h6> Heading Elements
<p> Paragraph Element
Unique ID Attributes
HTML Attributes
The <ul> unordered list element is used to create a list of items in
no particular order. Each individual list item will have a bullet point by
default.
<ul>
 <li>Play more music 🎸</li>
 <li>Read more books 📚</li>
</ul>
An <img> element can have alternative text via the alt attribute.
The alternative text will be displayed if an image fails to render due to
an incorrect URL, if the image format is not supported by the browser,
if the image is blocked from being displayed, or if the image has not
been received from the URL.
The text will be read aloud if screen reading software is used and
helps support visually impaired users by providing a text descriptor for
the image content on a webpage.
<img src="path/to/image" alt="text describing
image" />
The <body> element represents the content of an HTML document.
Content inside <body> tags are rendered on the web browsers.
Note: There can be only one <body> element in a document.
<body>
 <h1>Learn to code with Codecademy :)</h1>
</body>
The <span> element is an inline container for text and can be used
to group text for styling purposes. However, as <span> is a generic
container to separate pieces of text from a larger body of text, its use
should be avoided if a more semantic element is available.
<p><span>This text</span> may be styled
differently than the surrounding text.</p>
O <strong> elemento destaca texto importante, sério ou urgente e
os navegadores normalmente renderizarão esse texto destacado em
negrito por padrão.
< p > Este é um texto < forte > importante </
forte > ! </ p >
Um elemento HTML é uma parte do conteúdo de um documento
HTML e usa a seguinte sintaxe: tag de abertura + conteúdo + tag de
fechamento. No código fornecido:
<p> é a tag de abertura.
Hello World! é o conteúdo.
</p> é a tag de fechamento.
< p > Olá, mundo! </ p >
<ul> Unordered List Element
alt Attribute
<body> Body Element
<span> Span Element
<strong> Strong Element
Elemento HTML
A sintaxe para uma única tag HTML é um colchete angular de abertura
< seguido pelo nome do elemento e um colchete angular de
fechamento > . Aqui está um exemplo de <div> tag de abertura.
<div> _ _
Etiqueta HTML
0
Imprimir Compartilhar




HTML SEMÂNTICO

* O HTML semântico introduz significado a uma página por meio de elementos específicos que fornecem contexto sobre o que está entre as tags.

*HTML semântico é um padrão moderno e torna um site acessível para pessoas que usam leitores de tela para traduzir a página e melhora o SEO do seu site.

<header>, <nav>e <main>crie <footer>a estrutura básica da página da web.

<section>define elementos de um documento, como capítulos, títulos ou qualquer outra área do documento com o mesmo tema.

<article>contém conteúdo que faz sentido por si só, como artigos, blogs, comentários, etc.

<aside>contém informações relacionadas ao conteúdo principal, mas não necessárias para a compreensão das informações dominantes.

<figure>encapsula todos os tipos de mídia.

<figcaption>é usado para descrever a mídia em <figure>.

<video>Os elementos <embed>, e <audio>são usados ​​para arquivos de mídia.