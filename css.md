# 💻 Tags de CSS

<p align="left">
    <img src="./Arquivos/css3-logo.jpeg" alt="Logo" width="65%">
</p>

**Autor:**  *João Victor Moura*

**Curso:**  *ADS*

> Guia prático de consulta rápida para iniciantes em CSS, com foco nas tags mais comuns e importantes do CSS3, útil para quem precisa revisar algo rápido.

---

## 🏷️ As Tags

## 📖 Sumário
- [Seletores](#-seletores)
- [Pseudo-Seletores e Classes](#-pseudo-seletores-e-classes)
- [Box Model e Posicionamento](#-box-model-e-posicionamento)
- [Cores](#-cores)
- [Texto](#️-texto)
- [Fontes](#🅰️-fontes)
- [Paging](#-paging)
- [Tabela](#-tabela)
- [Interface](#️-interface)
- [Miscelânea](#-miscelânea)

## 🔍 Seletores

- ### ```div```
```
Exemplo: div { color: blue; }

Exibição: Aplica a cor azul a todos os elementos <div> da página.
```
- ### ```div#id```
```
Exemplo: div#header { background-color: #f0f0f0; }

Exibição: Aplica uma cor de fundo cinza clara somente ao elemento <div> que tem o id "header".
```
- ### ```div span```
```
Exemplo: div span { font-style: italic; }

Exibição: Aplica o estilo itálico a todos os elementos <span> que estão dentro de um <div>.
```
- ### ```div>span```
```
Exemplo: div>span { border: 1px solid black; }

Exibição: Aplica uma borda a todos os elementos <span> que são filhos diretos de um <div>.
```
- ### ```div+span```
```
Exemplo: div+span { margin-top: 10px; }

Exibição: Adiciona uma margem superior de 10 pixels a um <span> que vem imediatamente após um <div>.
```
- ### ```div~span```
```
Exemplo: div~span { opacity: 0.5; }

Exibição: Diminui a opacidade de todos os elementos <span> que vêm depois de um <div> no mesmo nível hierárquico.
```
- ### ```.class```
```
Exemplo: .destaque { font-weight: bold; }

Exibição: Deixa em negrito qualquer elemento que tenha a classe "destaque".
```
- ### ```#id```
```
Exemplo: #logo { width: 150px; }

Exibição: Define a largura do elemento com o id "logo" para 150 pixels.
```
- ### ```[attributo]:```
```
Exemplo: [type] { color: red; }

Exibição: Aplica a cor vermelha a todos os elementos que possuem o atributo type.
```
- ### ```a[href="attr"]```
```
Exemplo: a[href="https://www.google.com"] { text-decoration: none; }

Exibição: Remove o sublinhado de todos os links que apontam para o Google.
```
- ### ```a[href~="attr"]```
```
Exemplo: a[href~="termos"] { font-size: 1.2em; }

Exibição: Aumenta a fonte de links cujo atributo href contém a palavra "termos" (separada por espaços).
```
- ### ```a[href|="attr"]```
```
Exemplo: a[href|="pt-BR"] { color: green; }

Exibição: Colore de verde links cujo href começa com "pt-BR" seguido de hífen.
```
- ### ```a[lang^="en"]```
```
Exemplo: a[lang^="en"] { color: red; }

Exibição: Colore de vermelho links cujo atributo lang começa com "en".
```
- ### ```a[lang$="fr"]```
```
Exemplo: a[lang$="fr"] { color: green; }

Exibição: Colore de verde links cujo atributo lang termina com "fr".
```
- ### ```a[lang*="de"]```
```
Exemplo: a[lang*="de"] { font-weight: bold; }

Exibição: Deixa em negrito links cujo atributo lang contém a subcadeia "de".
```
## ✨ Pseudo-Seletores e Classes 

- ### ```:first-child```
```
Exemplo: p:first-child { font-size: 2em; }

Exibição: Aumenta o tamanho da fonte do primeiro parágrafo de cada contêiner.
```
- ### ```:last-child```
```
Exemplo: li:last-child { color: purple; }

Exibição: Muda a cor do último item de uma lista para roxo.
```
- ### ```:hover```
```
Exemplo: a:hover { color: orange; }

Exibição: Altera a cor do texto de um link para laranja quando o cursor do mouse passa sobre ele.
```
- ### ```:focus```
```
Exemplo: input:focus { border: 2px solid blue; }

Exibição: Aumenta a espessura e muda a cor da borda de um campo de input quando ele está selecionado.
```
- ### ```:link```
```
Exemplo: a:link { color: blue; }

Exibição: Define a cor azul para links que ainda não foram visitados.
```
- ### ```:visited```
```
Exemplo: a:visited { color: #800080; }

Exibição: Muda a cor de links que já foram visitados para roxo.
```
- ### ```:active```
```
Exemplo: button:active { background-color: darkgray; }

Exibição: Muda a cor de fundo de um botão para cinza escuro no momento em que ele é clicado.
```
- ### ```::before```
```
Exemplo: li::before { content: "» "; }

Exibição: Adiciona o caractere "»" antes de cada item de uma lista.
```
- ### ```::after```
```
Exemplo: a::after { content: " (link)"; }

Exibição: Adiciona o texto "(link)" depois de cada link na página.
```
## 📦 Box Model e Posicionamento 

- ### ```margin```
```
Exemplo: div { margin: 20px; }

Exibição: Adiciona 20 pixels de espaço externo ao redor de um elemento div.
```
- ### ```padding```
```
Exemplo: div { padding: 10px; }

Exibição: Adiciona 10 pixels de espaço interno ao redor do conteúdo de um elemento div.
```
- ### ```border```
```
Exemplo: div { border: 1px solid black; }

Exibição: Cria uma borda sólida de 1 pixel e cor preta ao redor de um elemento.
```
- ### ```width e height```
```
Exemplo: img { width: 100px; height: 100px; }

Exibição: Redimensiona uma imagem para 100 pixels de largura por 100 pixels de altura.
```
- ### ```display```
```
Exemplo: li { display: inline; }

Exibição: Faz com que os itens de uma lista fiquem lado a lado, em vez de um abaixo do outro.
```
- ### ```position```
```
Exemplo: div { position: relative; top: 10px; }

Exibição: Move um elemento 10 pixels para baixo de sua posição original.
```
- ### ```float```
```
Exemplo: img { float: right; }

Exibição: Alinha a imagem para a direita, permitindo que o texto flua ao redor dela.
```
- ### ```z-index```
```
Exemplo: div.caixa { position: absolute; z-index: 10; }

Exibição: Garante que a caixa com a classe "caixa" apareça na frente de outros elementos que se sobreponham a ela.
```
- ### ```overflow```
```
Exemplo: div { overflow: scroll; }

Exibição: Adiciona barras de rolagem a uma <div> se o conteúdo for maior que a área visível.
```
- ### ```visibility```
```
Exemplo: p { visibility: hidden; }

Exibição: O parágrafo fica invisível, mas ainda ocupa seu espaço na página.
```
- ### ```cursor```
```
Exemplo: div { cursor: pointer; }

Exibição: Quando o cursor do mouse passa sobre a div, ele muda para o ícone de uma mão.
```
## 🎨 Cores 

- ### ```color```
```
Exemplo: p { color: #FF5733; }

Exibição: Muda a cor do texto de todos os parágrafos para um tom de laranja.
```
- ### ```background```
```
Exemplo: body { background: #f0f0f0; }

Exibição: Altera a cor de fundo de toda a página para um cinza claro.
```
- ### ```background-image```
```
Exemplo: body { background-image: url("background.jpg"); }

Exibição: Define uma imagem chamada "background.jpg" como plano de fundo da página.
```
- ### ```background-repeat```
```
Exemplo: body { background-repeat: no-repeat; }

Exibição: Garante que a imagem de fundo não se repita e apareça apenas uma vez.
```
- ### ```background-position```
```
Exemplo: body { background-position: center; }

Exibição: Centraliza a imagem de fundo no meio da página.
```
- ### ```background-attachment```
```
Exemplo: body { background-attachment: fixed; }

Exibição: Faz com que a imagem de fundo permaneça no mesmo lugar enquanto o usuário rola a página.
```
## ✍️ Texto 

- ### ```text-align```
```
Exemplo: h1 { text-align: center; }

Exibição: Centraliza o texto de todos os títulos <h1>.
```
- ### ```text-indent```
```
Exemplo: p { text-indent: 50px; }

Exibição: Adiciona um recuo de 50 pixels na primeira linha de cada parágrafo.
```
- ### ```text-decoration```
```
Exemplo: a { text-decoration: none; }

Exibição: Remove o sublinhado dos links.
```
- ### ```text-shadow```
```
Exemplo: h1 { text-shadow: 2px 2px 4px #000000; }

Exibição: Adiciona uma sombra preta ao texto do título <h1>.
```
- ### ```text-transform```
```
Exemplo: h2 { text-transform: uppercase; }

Exibição: Converte todo o texto do título <h2> para letras maiúsculas.
```
- ### ```white-space```
```
Exemplo: p { white-space: nowrap; }

Exibição: Impede que o texto de um parágrafo quebre a linha, fazendo com que ele continue na mesma linha.
```
- ### ```word-spacing```
```
Exemplo: p { word-spacing: 5px; }

Exibição: Aumenta o espaço entre as palavras de um parágrafo para 5 pixels.
```
- ### ```line-height```
```
Exemplo: p { line-height: 1.5; }

Exibição: Aumenta a altura das linhas de um parágrafo, adicionando mais espaço entre elas.
```
- ### ```letter-spacing```
```
Exemplo: h1 { letter-spacing: 3px; }

Exibição: Aumenta o espaço entre cada letra de um título <h1> para 3 pixels.
```
## 🅰️ Fontes 

- ### ```font```
```
Exemplo: p { font: italic bold 12px Arial, sans-serif; }

Exibição: Define o estilo, peso, tamanho e família de fonte para um parágrafo em uma única linha.
```
- ### ```font-family```
```
Exemplo: body { font-family: "Times New Roman", Times, serif; }

Exibição: Altera a fonte de todo o texto do corpo da página.
```
- ### ```font-size```
```
Exemplo: h3 { font-size: 1.5em; }

Exibição: Aumenta o tamanho da fonte de todos os títulos <h3>.
```
- ### ```font-weight```
```
Exemplo: p { font-weight: bold; }

Exibição: Torna o texto de um parágrafo mais grosso (negrito).
```
- ### ```font-style```
```
Exemplo: em { font-style: normal; }

Exibição: Remove o estilo itálico padrão do elemento <em>.
```
- ### ```font-variant```
```
Exemplo: p { font-variant: small-caps; }

Exibição: Converte o texto para letras maiúsculas, mas mantém o tamanho das letras minúsculas.
```
## 🔢 Paging

- ### ```size```
```
Exemplo: @page { size: A4; }

Exibição: Define o tamanho da página para impressão como A4.
```
- ### ```page-break-before```
```
Exemplo: h1 { page-break-before: always; }

Exibição: Força um título <h1> a sempre começar em uma nova página impressa.
```
- ### ```page-break-after```
```
Exemplo: div { page-break-after: always; }

Exibição: Força um elemento <div> a ser seguido por uma quebra de página.
```
- ### ```page-break-inside```
```
Exemplo: p { page-break-inside: avoid; }

Exibição: Impede que um parágrafo seja quebrado entre duas páginas na impressão.
```
- ### ```orphans```
```
Exemplo: p { orphans: 2; }

Exibição: Garante que pelo menos duas linhas de um parágrafo fiquem na próxima página, em vez de uma única linha.
```
- ### ```widows```
```
Exemplo: p { widows: 2; }

Exibição: Garante que pelo menos duas linhas de um parágrafo fiquem na página anterior, em vez de uma única linha.
```
## 📊 Tabela 

- ### ```caption-side```
```
Exemplo: caption { caption-side: bottom; }

Exibição: Coloca a legenda da tabela na parte inferior, em vez da parte superior.
```
- ### ```table-layout```
```
Exemplo: table { table-layout: fixed; }

Exibição: Define que a largura das colunas da tabela é determinada pelas larguras das células da primeira linha.
```
- ### ```empty-cells```
```
Exemplo: table { empty-cells: hide; }

Exibição: Oculta as células vazias da tabela.
```
- ### ```border-collapse```
```
Exemplo: table { border-collapse: collapse; }

Exibição: Faz com que as bordas das células da tabela se unam em uma única linha.
```
## 🖥️ Interface

- ### ```cursor```
```
Exemplo: a { cursor: pointer; }

Exibição: Altera o ícone do mouse para uma mão (ponteiro) quando passa sobre um link.
```
- ### ```outline```
```
Exemplo: input:focus { outline: 2px solid blue; }

Exibição: Adiciona uma borda azul ao redor de um campo de input quando ele está selecionado, que não ocupa espaço.
```
## 🧩 Miscelânea 

- ### ```content```
```
Exemplo: a::after { content: " (Link)"; }

Exibição: Adiciona o texto "(Link)" após um link, como um conteúdo gerado.
```
- ### ```quotes```
```
Exemplo: q { quotes: "«" "»"; }

Exibição: Define que a tag <q> usará os caracteres « e » como aspas.
```
- ### ```list-style```
```
Exemplo: ul { list-style: square; }

Exibição: Muda os marcadores de uma lista não ordenada de pontos para quadrados.
```
- ### ```list-style-type```
```
Exemplo: ul { list-style-type: circle; }

Exibição: Muda o tipo de marcador para círculos vazios.
```
- ### ```list-style-image```
```
Exemplo: ul { list-style-image: url("marker.png"); }

Exibição: Usa uma imagem personalizada como marcador da lista.
```
- ### ```list-style-position```
```
Exemplo: ul { list-style-position: inside; }

Exibição: Posiciona o marcador da lista dentro do conteúdo.
```