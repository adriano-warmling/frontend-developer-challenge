/* ==========================================================================
O HTML e o CSS estão ok, mas o desafio está incompleto, ainda estou aprendendo a parte de JavaScript, meu curso começa semana que vem.

Tentei o desafio a fim de testar um pouco minhas habilidades por mais que estas sejam limitadas.
Vou me esforçar e aprender como faz com aquele JSON, e quem sabe um dia faça o Desafio completo.

Basicamente é um simples html e seu css.
Vou colar esse mesmo texto antes do que deveria ser o arquivo o style.css para facilitar a localização do mesmo.

Criticas, sugestões e boas práticas são sempre bem vindas.

Atenciosamente: 
Adriano Warmling.
warmling.adriano@gmail.com

Aqui começa o HTML
   ========================================================================== */

<!DOCTYPE html>
<html lang="pt-br">
	<head>
		<meta charset="utf-8">
        <title>Desafio Links</title>
		<link rel="stylesheet" href="css/style.css">
	</head>
	<body>

		<header class="header">
			<div class="container">

                <div class="header_title1">
                    <p>uma seleção de produtos</p>
                </div>

                <div class="header_title2">
                    <p>especial para você</p>
                </div>

                <div class="header_title3">
                    <p>Todos os produtos dessa lista foram selecionados a partir da sua navegação. Aproveite!</p>
                </div>

				<nav class="header_menu">
                    <div class="container">
                        <div class="menu_button1"><a href="conheca-links.html">Conheça a Links</a></div>
						<div class="menu_button"><a href="ajude-algoritimo.html">Ajude o algorítimo</a></div>
						<div class="menu_button"><a href="seus-produtos.html">Seus produtos</a></div>
                        <div class="menu_button"><a href="compartilhe.html">Compartilhe</a></div>
                    </div>
				</nav>
			</div>
        </header>
        

        <div class="body_title">
            <h2>Sua seleção especial</h2>
        </div>

        <!-- Grid de produtos -->
        <article class="container">

            <!-- Grid 1 -->
            <div class="products_container grid-4">
                <div class="product_img">
                    1
                </div>
                <div class="product_name">
                    <p>Nome do produto</p>
                </div>
                <div class="product_description">
                    <p>Descrição do produto um pouco maior, com duas linhas ou três que explica melhor do que se trata.</p>
                </div>
                <div class="product_price">
                    <p>De: R$23,99</p>
                </div>
                <div class="product_price1">
                    <p>Por: R$19,99</p>
                </div>
                <div class="product_installment">
                    <p>ou 2x de R$9,99</p>
                </div>
                <div class="buy_button">
                    <p>Comprar</p>
                </div>
            </div>

            <!-- Grid 2 -->
            <div class="products_container grid-4">
                <div class="product_img">
                    2
                </div>
                <div class="product_name">
                    <p>Nome do produto</p>
                </div>
                <div class="product_description">
                    <p>Descrição do produto um pouco maior, com duas linhas ou três que explica melhor do que se trata.</p>
                </div>
                <div class="product_price">
                    <p>De: R$23,99</p>
                </div>
                <div class="product_price1">
                    <p>Por: R$19,99</p>
                </div>
                <div class="product_installment">
                    <p>ou 2x de R$9,99</p>
                </div>
                <div class="buy_button">
                    <p>Comprar</p>
                </div>
            </div>

            <!-- Grid 3 -->
            <div class="products_container grid-4">
                <div class="product_img">
                    3
                </div>
                <div class="product_name">
                    <p>Nome do produto</p>
                </div>
                <div class="product_description">
                    <p>Descrição do produto um pouco maior, com duas linhas ou três que explica melhor do que se trata.</p>
                </div>
                <div class="product_price">
                    <p>De: R$23,99</p>
                </div>
                <div class="product_price1">
                    <p>Por: R$19,99</p>
                </div>
                <div class="product_installment">
                    <p>ou 2x de R$9,99</p>
                </div>
                <div class="buy_button">
                    <p>Comprar</p>
                </div>
            </div>

            <!-- Grid 4 -->
            <div class="products_container grid-4">
                <div class="product_img">
                    4
                </div>
                <div class="product_name">
                    <p>Nome do produto</p>
                </div>
                <div class="product_description">
                    <p>Descrição do produto um pouco maior, com duas linhas ou três que explica melhor do que se trata.</p>
                </div>
                <div class="product_price">
                    <p>De: R$23,99</p>
                </div>
                <div class="product_price1">
                    <p>Por: R$19,99</p>
                </div>
                <div class="product_installment">
                    <p>ou 2x de R$9,99</p>
                </div>
                <div class="buy_button">
                    <p>Comprar</p>
                </div>
            </div>

            <!-- Grid 5 -->
            <div class="products_container grid-4">
                <div class="product_img">
                    5
                </div>
                <div class="product_name">
                    <p>Nome do produto</p>
                </div>
                <div class="product_description">
                    <p>Descrição do produto um pouco maior, com duas linhas ou três que explica melhor do que se trata.</p>
                </div>
                <div class="product_price">
                    <p>De: R$23,99</p>
                </div>
                <div class="product_price1">
                    <p>Por: R$19,99</p>
                </div>
                <div class="product_installment">
                    <p>ou 2x de R$9,99</p>
                </div>
                <div class="buy_button">
                    <p>Comprar</p>
                </div>
            </div>

            <!-- Grid 6 -->
            <div class="products_container grid-4">
                <div class="product_img">
                    6
                </div>
                <div class="product_name">
                    <p>Nome do produto</p>
                </div>
                <div class="product_description">
                    <p>Descrição do produto um pouco maior, com duas linhas ou três que explica melhor do que se trata.</p>
                </div>
                <div class="product_price">
                    <p>De: R$23,99</p>
                </div>
                <div class="product_price1">
                    <p>Por: R$19,99</p>
                </div>
                <div class="product_installment">
                    <p>ou 2x de R$9,99</p>
                </div>
                <div class="buy_button">
                    <p>Comprar</p>
                </div>
            </div>

            <!-- Grid 7 -->
            <div class="products_container grid-4">
                <div class="product_img">
                    7
                </div>
                <div class="product_name">
                    <p>Nome do produto</p>
                </div>
                <div class="product_description">
                    <p>Descrição do produto um pouco maior, com duas linhas ou três que explica melhor do que se trata.</p>
                </div>
                <div class="product_price">
                    <p>De: R$23,99</p>
                </div>
                <div class="product_price1">
                    <p>Por: R$19,99</p>
                </div>
                <div class="product_installment">
                    <p>ou 2x de R$9,99</p>
                </div>
                <div class="buy_button">
                    <p>Comprar</p>
                </div>
            </div>

            <!-- Grid 8 -->
            <div class="products_container grid-4">
                <div class="product_img">
                    8
                </div>
                <div class="product_name">
                    <p>Nome do produto</p>
                </div>
                <div class="product_description">
                    <p>Descrição do produto um pouco maior, com duas linhas ou três que explica melhor do que se trata.</p>
                </div>
                <div class="product_price">
                    <p>De: R$23,99</p>
                </div>
                <div class="product_price1">
                    <p>Por: R$19,99</p>
                </div>
                <div class="product_installment">
                    <p>ou 2x de R$9,99</p>
                </div>
                <div class="buy_button">
                    <p>Comprar</p>
                </div>
            </div>            
        </article>
		
		<!-- Botão para mais produtos -->
		
		<div class="container">
			<div>
				<button class="large_button">
					<p>Ainda mais produtos aqui!</p>
				</button>
			</div>
		</div>
		
		<!-- Formulário  -->
		
		<div class="body_title">
            <h3>Compartilhe a novidade</h3>
        </div>
		
		<div class="pre_formulario">
			<p>Quer que seus amigos também ganhem a lista personalizada deles? Preencha agora!</p>
		</div>
			
		<div class="container">
			<div>
				<button class="large_button">
					<p>Enviar agora</p>
				</button>
			</div>
		</div>
		

        <!-- Footer do site -->

        <footer class="footer">
            <div class="container">
                <p class="footer_credits">Testando suas habilidades<br> Links Impulse</p>
            </div>
        </footer>
    </body>
    
    
    /* ==========================================================================
O HTML e o CSS estão ok, mas o desafio está incompleto, ainda estou aprendendo a parte de JavaScript, meu curso começa semana que vem.

Tentei o desafio a fim de testar um pouco minhas habilidades por mais que estas sejam limitadas.
Vou me esforçar e aprender como faz com aquele JSON, e quem sabe um dia faça o Desafio completo.

Basicamente é um simples html e seu css.
Vou colar esse mesmo texto antes do que deveria ser o arquivo o style.css para facilitar a localização do mesmo.

Criticas, sugestões e boas práticas são sempre bem vindas.

Atenciosamente: 
Adriano Warmling.
warmling.adriano@gmail.com

Aqui começa o CSS
   ========================================================================== */
   
   
/* RESET ALL HTML PRESETS */

/* ==========================================================================
   Reset
   ========================================================================== */

/**
 * Remove anchor text-decoration
 */ 

a {
	text-decoration: none;
}

/**
 * Remove list-style
 */ 

ol, ul {
	list-style: none;
}

html, body, div, span, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, a, em, img, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, article, footer, header, nav, section, main {
	margin: 0;
	padding: 0;
	border: 0;
	vertical-align: baseline;
}

h1, h2, h3, h4, h5, h6, p, a, ul {
	font-size: 1em;
	font-weight: normal;
}


/* Normalize */

/*! normalize.css v8.0.1 | MIT License | github.com/necolas/normalize.css */

/* Document
   ========================================================================== */

/**
 * 1. Correct the line height in all browsers.
 * 2. Prevent adjustments of font size after orientation changes in iOS.
 */

html {
  line-height: 1.15; /* 1 */
  -webkit-text-size-adjust: 100%; /* 2 */
}

/* Sections
   ========================================================================== */

/**
 * Remove the margin in all browsers.
 */

body {
  margin: 0;
}

/**
 * Render the `main` element consistently in IE.
 */

main {
  display: block;
}

/**
 * Correct the font size and margin on `h1` elements within `section` and
 * `article` contexts in Chrome, Firefox, and Safari.
 */

h1 {
  font-size: 2em;
  margin: 0.67em 0;
}

/* Grouping content
   ========================================================================== */

/**
 * 1. Add the correct box sizing in Firefox.
 * 2. Show the overflow in Edge and IE.
 */

hr {
  box-sizing: content-box; /* 1 */
  height: 0; /* 1 */
  overflow: visible; /* 2 */
}

/**
 * 1. Correct the inheritance and scaling of font size in all browsers.
 * 2. Correct the odd `em` font sizing in all browsers.
 */

pre {
  font-family: monospace, monospace; /* 1 */
  font-size: 1em; /* 2 */
}

/* Text-level semantics
   ========================================================================== */

/**
 * Remove the gray background on active links in IE 10.
 */

a {
  background-color: transparent;
}

/**
 * 1. Remove the bottom border in Chrome 57-
 * 2. Add the correct text decoration in Chrome, Edge, IE, Opera, and Safari.
 */

abbr[title] {
  border-bottom: none; /* 1 */
  text-decoration: underline; /* 2 */
  text-decoration: underline dotted; /* 2 */
}

/**
 * Add the correct font weight in Chrome, Edge, and Safari.
 */

b,
strong {
  font-weight: bolder;
}

/**
 * 1. Correct the inheritance and scaling of font size in all browsers.
 * 2. Correct the odd `em` font sizing in all browsers.
 */

code,
kbd,
samp {
  font-family: monospace, monospace; /* 1 */
  font-size: 1em; /* 2 */
}

/**
 * Add the correct font size in all browsers.
 */

small {
  font-size: 80%;
}

/**
 * Prevent `sub` and `sup` elements from affecting the line height in
 * all browsers.
 */

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sub {
  bottom: -0.25em;
}

sup {
  top: -0.5em;
}

/* Embedded content
   ========================================================================== */

/**
 * Remove the border on images inside links in IE 10.
 */

img {
  border-style: none;
}

/* Forms
   ========================================================================== */

/**
 * 1. Change the font styles in all browsers.
 * 2. Remove the margin in Firefox and Safari.
 */

button,
input,
optgroup,
select,
textarea {
  font-family: inherit; /* 1 */
  font-size: 100%; /* 1 */
  line-height: 1.15; /* 1 */
  margin: 0; /* 2 */
}

/**
 * Show the overflow in IE.
 * 1. Show the overflow in Edge.
 */

button,
input { /* 1 */
  overflow: visible;
}

/**
 * Remove the inheritance of text transform in Edge, Firefox, and IE.
 * 1. Remove the inheritance of text transform in Firefox.
 */

button,
select { /* 1 */
  text-transform: none;
}

/**
 * Correct the inability to style clickable types in iOS and Safari.
 */

button,
[type="button"],
[type="reset"],
[type="submit"] {
  -webkit-appearance: button;
}

/**
 * Remove the inner border and padding in Firefox.
 */

button::-moz-focus-inner,
[type="button"]::-moz-focus-inner,
[type="reset"]::-moz-focus-inner,
[type="submit"]::-moz-focus-inner {
  border-style: none;
  padding: 0;
}

/**
 * Restore the focus styles unset by the previous rule.
 */

button:-moz-focusring,
[type="button"]:-moz-focusring,
[type="reset"]:-moz-focusring,
[type="submit"]:-moz-focusring {
  outline: 1px dotted ButtonText;
}

/**
 * Correct the padding in Firefox.
 */

fieldset {
  padding: 0.35em 0.75em 0.625em;
}

/**
 * 1. Correct the text wrapping in Edge and IE.
 * 2. Correct the color inheritance from `fieldset` elements in IE.
 * 3. Remove the padding so developers are not caught out when they zero out
 *    `fieldset` elements in all browsers.
 */

legend {
  box-sizing: border-box; /* 1 */
  color: inherit; /* 2 */
  display: table; /* 1 */
  max-width: 100%; /* 1 */
  padding: 0; /* 3 */
  white-space: normal; /* 1 */
}

/**
 * Add the correct vertical alignment in Chrome, Firefox, and Opera.
 */

progress {
  vertical-align: baseline;
}

/**
 * Remove the default vertical scrollbar in IE 10+.
 */

textarea {
  overflow: auto;
}

/**
 * 1. Add the correct box sizing in IE 10.
 * 2. Remove the padding in IE 10.
 */

[type="checkbox"],
[type="radio"] {
  box-sizing: border-box; /* 1 */
  padding: 0; /* 2 */
}

/**
 * Correct the cursor style of increment and decrement buttons in Chrome.
 */

[type="number"]::-webkit-inner-spin-button,
[type="number"]::-webkit-outer-spin-button {
  height: auto;
}

/**
 * 1. Correct the odd appearance in Chrome and Safari.
 * 2. Correct the outline style in Safari.
 */

[type="search"] {
  -webkit-appearance: textfield; /* 1 */
  outline-offset: -2px; /* 2 */
}

/**
 * Remove the inner padding in Chrome and Safari on macOS.
 */

[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}

/**
 * 1. Correct the inability to style clickable types in iOS and Safari.
 * 2. Change font properties to `inherit` in Safari.
 */

::-webkit-file-upload-button {
  -webkit-appearance: button; /* 1 */
  font: inherit; /* 2 */
}

/* Interactive
   ========================================================================== */

/*
 * Add the correct display in Edge, IE 10+, and Firefox.
 */

details {
  display: block;
}

/*
 * Add the correct display in all browsers.
 */

summary {
  display: list-item;
}

/* Misc
   ========================================================================== */

/**
 * Add the correct display in IE 10+.
 */

template {
  display: none;
}

/**
 * Add the correct display in IE 10.
 */

[hidden] {
  display: none;
}



/* GRID TO BETTER ORGANIZE LAYOUT */

*, *:before, *:after {
  -webkit-box-sizing: border-box; 
  -moz-box-sizing: border-box; 
  box-sizing: border-box;
}

.container {
	width: 960px;
	margin: 0 auto;
	padding: 0px;
	position: relative;
}

.container:after, .container:before {
	content: " ";
	display: table;
}

.container:after {
	clear: both;
}

.grid-1, .grid-2, .grid-3, .grid-4, .grid-5, .grid-6, .grid-7, .grid-8, .grid-9, .grid-10, .grid-11, .grid-12, .grid-13, .grid-14, .grid-15, .grid-16, .grid-1-3 {
	float: left;
	margin-left: 10px;
	margin-right: 10px;
}

.grid-1 	{width: 40px;}
.grid-2 	{width: 100px;}
.grid-3 	{width: 160px;}
.grid-4 	{width: 220px;}
.grid-5 	{width: 280px;}
.grid-6 	{width: 340px;}
.grid-7 	{width: 400px;}
.grid-8 	{width: 460px;}
.grid-9 	{width: 520px;}
.grid-10 	{width: 580px;}
.grid-11 	{width: 640px;}
.grid-12 	{width: 700px;}
.grid-13 	{width: 760px;}
.grid-14 	{width: 820px;}
.grid-15 	{width: 880px;}
.grid-16 	{width: 940px;}
.grid-1-3	{width: 300px;}



/* GENERAL STYLES */

html {
	font-family: "Helvetica Neue", Arial, sans-serif;
}

.menu_button, .menu_button1 {
	width: 160px; 
	height: 40px; 
	margin-left: 40px; 
	margin-top: 50px;
	padding:12px;
	float: left;
	background-color: #FFF; 
	border: 1px solid #707070;
	color: #888888;
	text-align: center;
	text-decoration: none;
	display: block;
	font-size: 14px;
	line-height: 16px;
	cursor: pointer;
	border-radius: 4px;
}

.menu_button1 {
	margin-left: 100px; 
}

.buy_button {
	width: 200px; 
	height: 30px;
	margin-top: 10px;
	padding-top: 6px;
	background-color: #FFF; 
	border: 1px solid #707070;
	color: #888888;
	text-align: center;
	text-decoration: none;
	display: inline-block;
	font-size: 16px;
	line-height: 16px;
	cursor: pointer;
	border-radius: 4px;
  }
  
.large_button {
	width: 260px; 
	height: 39px;
	margin-top: 42px;
	margin-left: 360px;
	padding: 11px 36px 10px 37px;
	background-color: #FFF; 
	border: 1px solid #707070;
	color: #888888;
	text-align: center;
	text-decoration: none;
	font-size: 16px;
	line-height: 16px;
	cursor: pointer;
	border-radius: 4px;
  }


/* Header */

.header {
	top: 0;
	width: 100%;
	height: 320px;
	background: #707070;
	text-align: center;
	color: #FFF;
}

.header_title1 {
	font-size: 20px;
	line-height: 24px;
	margin-top: 69px;
}

.header_title2 {
	font-size: 40px;
	line-height: 49px;
}

.header_title2 p {
	font-weight: bold;
}

.header_title3 {
	font-size: 14px;
	line-height: 16px;
	margin-top: 24px;
}

.menu_button1 :hover, .menu_button :hover {
	color: #000000;
}

.menu_button1 a, .menu_button a {
	color: #888;
	font-size: 14px;
	line-height: 16px;
	display: block; 
}



/* Introduction */

.body_title h2, h3 {
	font-size: 18px;
	line-height: 16px;
	font-weight: bold;
	text-align: center;
	color: #888;
	margin-top: 48px;
}

.body_title h3 {
	margin-top: 164px
}

.products_container {
	background: #FFF;
	width: 200px;
	height: 350px;
	margin-top: 50px;
	margin-left: 30px;
}

.more_products_container {
	background: #FFF;
	width: 200px;
	height: 350px;
}

.product_img {
	width: 200px;
	height: 150px;
	border: 1px solid #707070;
}

.product_name {
	font-size: 14px;
	line-height: 16px;
	margin-top: 14px;
	color: #888888;
}

.product_description {
	height: 60px;
	font-size: 12px;
	line-height: 16px;
	margin-top: 10px;
	color: #888888;
}

.product_price {
	font-size: 14px;
	line-height: 16px;
	color: #888888;
}

.product_price1 {
	font-size: 16px;
	line-height: 16px;
	margin-top: 6px;
	color: #888888;
}

.product_price1 p {
	font-weight: bold;
}

.product_installment {
	font-size: 12px;
	line-height: 16px;
	margin-top: 7px;
	color: #888888;
}

.buy_button article {
	display: block;
	margin-top: 10px;
	text-align: center;
}

.buy_button:hover {
	color: #FFF;
	background-color: #707070;
}

.large_button button {
	margin-top: 43px;
	text-align: center;
}

.large_button:hover {
	color: #FFF;
	background-color: #707070;
}

/* FORM */

.pre_formulario p {
	font-size: 14px;
	line-height: 16px;
	text-align: center;
	color: #888;
	margin-top: 44px;
}


/* Footer */

.footer {
	width: 100%;
	height: 186px;
	margin-top: 50px;
	background: #707070;
	text-align: center;
	color: #FFF;
}

.footer p {
	margin-top: 64px;
	font-size: 14px;
	line-height: 18px;
}

