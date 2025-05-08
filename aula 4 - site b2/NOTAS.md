# O QUE É HTML?

HTML é uma linguagem de diagramação, não confundir com linguagem de programação. Sua função é separar e categorizar cada elemento de um site de modo documenta-los e permitir o uso de SEO (Search Engine Optimization)

No HTML temos as tags, que correspondem a cada elementos de um site, seja um cabeçalho, um botão...
Todo elemento possui uma serie de propriedades as quais podem ser alteradas pelo CSS

# O que o CSS?

O CSS é uma linguagem de estilização cujo propósito é alterar os aspectos visuais dos elementos de um site.

Através do uso de seletores, e propriedades, o desenvolvedor pode modificar os atributos de uma tag ou de um grupo de tags, sendo este atravé dos id's e aquele através dos seletores específicos.

# O QUE SÃO TAGS?

As tags são modos de separar e classificar, ou até mesmo nomear, cada elemento do HTML.

Essencialmente, um HTML é como um documento de texto padrão, porém, sua formatação é completamente manipulável e programável. Para isso usam outras linguagem como CSS (Estilização) e JavaScript (Programação).

Em resumo, as tags separam elementos como cabeçalho, texto, título, imagens, tabelas. Assim cada uma delas possui atributos como tamanho, cor de fundo, bordas e etc.

# TAGS NOVAS:



### SECTION

Pode ser encaixado entre o FOOTER e o HEADER, nela é delimitada uma seção, onde se pode colocar título, parágrafos, outras divs e mais. A tag SECTION pode ser interpretada no lível bastante literal, pois ela simplesmente delimita uma seção em torno de outros elementos. Como se trata de um subdivisão, também pode ser um Componente, o qual se submete a contenção de um Container

### DIV

A div é um container que suporta textos, títulos, parágrafos além de compreender formatação e etc.

### MAIN 

uma alternativa para o section, é o corpo do site onde o conteúdo principal resido. Elementos como parágrafos, informações extensas, botõtes, imagens e paineis, todos estes são característicos do corpo de um site, que é delimitado pelo MAIN. Dentro do MAIN, também pode haver subdivisões delimitadas pelas SECTION.


# SELETORES EM CSS

Os seletores são blocos de código do CSS que editam atributos específicos das tags do HTML.

O Desenvolvedor pode usar dos seletores para fazer uma estilização generalizada dos elementos do HTML.

Quando for necessário fazer uma edição Especial

```css

	/*SELETOR que altera o HEADER*/

		header{
		/*muda a cor de fundo*/
		background-color: #87CEEB;
		color: #4169E1;
		padding: 5px;

	}

````

# CLASSES EM CSS - AGRUPANDO TAGS

As classes são uma maneira de agrupar diferentes tags e alterar seus atributos conjuntamente.

````html

	<p class:"txt1">um texto qualquer<p>

	<h1 class:"txt1"> Um título h1 modificado<h1>

````


````css

	.txt1{
		
	}

````

# ID's - EDITAR TAGS SEM GENERALIZAR