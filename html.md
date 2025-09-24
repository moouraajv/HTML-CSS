# 💻 Tags de HTML

<p align="left">
    <img src="./Arquivos/logo-html.jpg" alt="Logo" width="70%">
</p>

**Autor:**  *João Victor Moura*

**Curso:**  *ADS*

> Guia prático de consulta rápida para iniciantes em HTML, com foco nas tags mais comuns e importantes do HTML5, útil para quem precisa revisar algo rápido.

---

## 🏷️ As Tags

- ### ```<a>```
```
Exemplo: <a href="https://www.google.com">Ir para o Google</a>

Exibição: Aparece como o texto "Ir para o Google", geralmente azul e sublinhado. Ao clicar, o navegador navega para a página do Google.
```
- ### ```<abbr>```
```
Exemplo: <abbr title="World Wide Web">WWW</abbr>

Exibição: O texto "WWW" aparece. Quando você passa o mouse sobre ele, uma pequena caixa de texto (tooltip) exibe a frase "World Wide Web".
```
- ### ```<address>```
```
Exemplo: <address>João da Silva</address>

Exibição: O nome "João da Silva" é exibido, geralmente em itálico.
```
- ### ```<area>```
```
Exemplo: <area shape="circle" coords="100,100,50" href="sun.htm" alt="Sol">

Exibição: Não aparece visivelmente na tela. Ela cria uma área invisível e clicável dentro de uma imagem maior, definida por um <map>.
```
- ### ```<article>```
```
Exemplo: <article><h2>Título do Artigo</h2><p>Conteúdo aqui...</p></article>

Exibição: Os conteúdos internos (título e parágrafo) são exibidos normalmente na página, mas o navegador entende que eles formam um conteúdo independente.
```
- ### ```<aside>```
```
Exemplo: <aside>Esta é uma barra lateral.</aside>

Exibição: O texto "Esta é uma barra lateral." é exibido, muitas vezes posicionado à esquerda ou direita do conteúdo principal.
```
- ### ```<audio>```
```
Exemplo: <audio controls><source src="som.mp3" type="audio/mpeg"></audio>

Exibição: É exibido um reprodutor de áudio padrão do navegador, com botões para "Play", "Pause" e uma barra de progresso.
```
- ### ```<b>```
```
Exemplo: <b>Texto em negrito.</b>

Exibição: O texto "Texto em negrito." aparece com as letras mais escuras e espessas.
```
- ### ```<base>```
```
Exemplo: <base href="https://www.exemplo.com/imagens/">

Exibição: Nada é exibido. Essa tag afeta como links e arquivos são carregados em segundo plano.
```
- ### ```<bdi>```
```
Exemplo: <bdi>مرحبا</bdi>

Exibição: O texto árabe "مرحبا" (que é escrito da direita para a esquerda) é exibido corretamente, sem interferir com a direção de outros textos ao redor.
```
- ### ```<bdo>```
```
Exemplo: <bdo dir="rtl">Este texto está ao contrário.</bdo>

Exibição: O texto "Este texto está ao contrário." é exibido de trás para a frente, da direita para a esquerda.
```
- ### ```<blockquote>```
```
Exemplo: <blockquote><p>Citação longa.</p></blockquote>

Exibição: O parágrafo da citação é exibido, geralmente com um recuo (margem) à esquerda e à direita.
```
- ### ```<body>```
```
Exemplo: <body><h1>Olá</h1></body>

Exibição: Tudo o que está dentro dessa tag, como o título "Olá", é o que você vê na janela do navegador.
```
- ### ```<br>```
```
Exemplo: Primeira linha.<br>Segunda linha.

Exibição: O texto "Primeira linha." aparece em uma linha, e o texto "Segunda linha." é forçado para a linha de baixo.
```
- ### ```<button>```
```
Exemplo: <button type="button">Clique aqui</button>

Exibição: Um botão clicável é exibido na tela, com o texto "Clique aqui" no centro.
```
- ### ```<canvas>```
```
Exemplo: <canvas id="meuCanvas"></canvas>

Exibição: Nada é exibido a princípio. Ele cria uma área retangular em branco onde scripts podem desenhar gráficos.
```
- ### ```<caption>```
```
Exemplo: <table><caption>Vendas</caption>...</table>

Exibição: O texto "Vendas" aparece como um título centralizado acima da tabela.
```
- ### ```<cite>```
```
Exemplo: <cite>A Grande Aventura</cite>

Exibição: O texto "A Grande Aventura" é exibido, geralmente em itálico.
```
- ### ```<code>```
```
Exemplo: <code>var x = 10;</code>

Exibição: O texto "var x = 10;" é exibido usando uma fonte monoespaçada, como Courier, para se parecer com código de programação.
```
- ### ```<col> e <colgroup>```
```
Exemplo: <table><colgroup><col span="2" style="background-color:red"></colgroup>...</table>

Exibição: A cor de fundo das duas primeiras colunas da tabela se torna vermelha.
```
- ### ```<data>```
```
Exemplo: <data value="2000-01-01">Primeiro dia</data>

Exibição: O texto "Primeiro dia" aparece na tela. O valor da data (2000-01-01) fica "escondido" para ser usado por scripts ou outras ferramentas.
```
- ### ```<datalist>```
```
Exemplo: <input list="browsers"><datalist id="browsers">...</datalist>

Exibição: Ao digitar no campo de texto, uma lista suspensa de sugestões pré-definidas aparece abaixo.
```
- ### ```<dd>```
```
Exemplo: <dd>Definição do termo.</dd>

Exibição: O texto "Definição do termo." é exibido com um pequeno recuo, geralmente abaixo do termo correspondente em uma lista de definições.
```
- ### ```<del>```
```
Exemplo: <del>Texto excluído</del>

Exibição: O texto "Texto excluído" é exibido com uma linha horizontal passando por ele, como se estivesse riscado.
```
- ### ```<details>```
```
Exemplo: <details><summary>Detalhes</summary>...</details>

Exibição: O texto "Detalhes" aparece como um link com uma pequena seta ou triângulo ao lado. Ao clicar, o conteúdo "escondido" se expande e fica visível.
```
- ### ```<dfn>```
```
Exemplo: <dfn>HTML</dfn> é uma linguagem de marcação.

Exibição: A palavra "HTML" aparece, geralmente em itálico, indicando que é a primeira vez que esse termo é definido no documento.
```
- ### ```<dialog>```
```
Exemplo: <dialog open>Olá, mundo!</dialog>

Exibição: Uma caixa de diálogo flutuante aparece no centro da tela com o texto "Olá, mundo!".
```
- ### ```<div>```
```
Exemplo: <div><p>Conteúdo</p></div>

Exibição: Não tem efeito visual por padrão. Ele funciona como um contêiner invisível que agrupa elementos e pode ser estilizado com CSS.
```
- ### ```<dl>, <dt>, <dd>```
```
Exemplo: <dl><dt>Termo</dt><dd>Definição</dd></dl>

Exibição: O termo "Termo" é exibido em uma linha, e a definição "Definição" aparece logo abaixo e recuada.
```
- ### ```<em>```
```
Exemplo: <em>Texto enfatizado.</em>

Exibição: O texto "Texto enfatizado." é exibido em itálico.
```
- ### ```<embed>```
```
Exemplo: <embed src="swf/game.swf" type="application/x-shockwave-flash">

Exibição: Um espaço é reservado na página para exibir um jogo ou aplicativo. Se o navegador não tiver o plugin necessário, uma mensagem de erro pode aparecer.
```
- ### ```<fieldset>```
```
Exemplo: <fieldset><legend>Dados Pessoais</legend>...</fieldset>

Exibição: Uma borda é desenhada ao redor dos elementos do formulário, com o texto "Dados Pessoais" no canto superior esquerdo da borda.
```
- ### ```<figcaption>```
```
Exemplo: <figure><img src="foto.jpg" alt="Foto"><figcaption>Legenda</figcaption></figure>

Exibição: O texto "Legenda" aparece centralizado abaixo da imagem, funcionando como a descrição dela.
```
- ### ```<figure>```
```
Exemplo: <figure><img src="foto.jpg" alt="Foto"></figure>

Exibição: A imagem foto.jpg é exibida. O navegador entende que essa imagem é um conteúdo independente do resto do texto.
```
- ### ```<footer>```
```
Exemplo: <footer><p>Direitos autorais 2023</p></footer>

Exibição: O texto "Direitos autorais 2023" é exibido, geralmente no final da página ou seção, muitas vezes com um fundo diferente.
```
- ### ```<form>```
```
Exemplo: <form action="/submit-form.php" method="post">...</form>

Exibição: Não tem efeito visual. É um contêiner invisível que define onde os dados do formulário serão enviados.
```
- ### ```<h1> a <h6>```
```
Exemplo: <h1>Título principal</h1>

Exibição: O texto "Título principal" é exibido com uma fonte muito grande e em negrito. A fonte diminui progressivamente de h1 para h6.
```
- ### ```<head>```
```
Exemplo: <head><title>Minha Página</title></head>

Exibição: Nada do conteúdo dessa tag é exibido na página. O texto "Minha Página" aparece na aba ou título da janela do navegador.
```
- ### ```<header>```
```
Exemplo: <header><h1>Meu Site</h1></header>

Exibição: O texto "Meu Site" aparece no topo da página. O navegador entende que isso faz parte do cabeçalho da página.
```
- ### ```<hr>```
```
Exemplo: <p>Primeiro parágrafo.</p><hr><p>Segundo parágrafo.</p>

Exibição: Uma linha horizontal aparece na página, separando os dois parágrafos.
```
- ### ```<html>```
```
Exemplo: <html><head>...</head><body>...</body></html>

Exibição: Nada é exibido. É a tag raiz que define que o documento é HTML.
```
- ### ```<i>```
```
Exemplo: <i>Texto em itálico.</i>

Exibição: O texto "Texto em itálico." é exibido em itálico.
```
- ### ```<iframe>```
```
Exemplo: <iframe src="pagina.html"></iframe>

Exibição: Um "buraco" na página é criado, e a página pagina.html é exibida dentro dele.
```
- ### ```<img>```
```
Exemplo: <img src="imagem.jpg" alt="Descrição da imagem">

Exibição: A imagem imagem.jpg é exibida no local da tag. Se a imagem não for encontrada, o texto "Descrição da imagem" é exibido.
```
- ### ```<input>```
```
Exemplo: <input type="text">

Exibição: Uma caixa de texto simples é exibida, onde o usuário pode digitar.
```
- ### ```<ins>```
```
Exemplo: Este texto foi <ins>inserido</ins>.

Exibição: O texto "inserido" é exibido com um sublinhado.
```
- ### ```<kbd>```
```
Exemplo: Pressione <kbd>Ctrl</kbd> + <kbd>C</kbd>.

Exibição: O texto "Ctrl" e "C" é exibido em uma fonte monoespaçada, para se parecer com o texto em uma tecla de teclado.
```
- ### ```<label>```
```
Exemplo: <label for="nome">Nome:</label><input type="text" id="nome">

Exibição: O texto "Nome:" aparece. Ao clicar nele, o cursor se move automaticamente para a caixa de texto correspondente.
```
- ### ```<legend>```
```
Exemplo: <legend>Dados Pessoais</legend>

Exibição: O texto "Dados Pessoais" aparece como um título na borda superior do <fieldset>.
```
- ### ```<li>```
```
Exemplo: <li>Item 1</li>

Exibição: O texto "Item 1" é exibido como um item de lista, com um marcador (ponto ou número) à esquerda.
```
- ### ```<link>```
```
Exemplo: <link rel="stylesheet" href="estilo.css">

Exibição: Nada é exibido, mas o navegador usa o arquivo estilo.css para estilizar a página.
```
- ### ```<main>```
```
Exemplo: <main>Conteúdo principal da página.</main>

Exibição: O conteúdo interno é exibido, e o navegador o reconhece como o conteúdo principal.
```
- ### ```<map>```
```
Exibição: Nada é exibido. É uma tag que define as áreas clicáveis de uma imagem, que só são visíveis quando você passa o mouse sobre elas.
```
- ### ```<mark>```
```
Exemplo: Este é um texto <mark>marcado</mark>.

Exibição: O texto "marcado" aparece com um fundo amarelo, como se estivesse destacado com um marca-texto.
```
- ### ```<menu>```
```
Exibição: Aparece como uma lista comum, com cada item em uma nova linha.
```
- ### ```<meta>```
```
Exibição: Nada é exibido. São dados invisíveis que o navegador usa para exibir a página corretamente.
```
- ### ```<meter>```
```
Exemplo: <meter value="2" min="0" max="10">2 de 10</meter>

Exibição: É exibida uma barra de progresso com o valor 2, de um máximo de 10. O texto "2 de 10" também é exibido.
```
- ### ```<nav>```
```
Exemplo: <nav><ul><li><a href="#">Início</a></li></ul></nav>

Exibição: O link "Início" é exibido. O navegador entende que ele faz parte da navegação principal.
```
- ### ```<noscript>```
```
Exemplo: <noscript>Seu navegador não suporta JavaScript.</noscript>

Exibição: Se o JavaScript estiver ativado, nada é exibido. Se estiver desativado, o texto "Seu navegador não suporta JavaScript." aparece.
```
- ### ```<object>```
```
Exibição: Similar ao <embed>, exibe um objeto como um arquivo Flash ou um applet Java.
```
- ### ```<ol>```
```
Exemplo: <ol><li>Item 1</li><li>Item 2</li></ol>

Exibição: A lista é exibida com números, como "1. Item 1" e "2. Item 2".
```
- ### ```<optgroup>```
```
Exemplo: <select><optgroup label="Carros">...</optgroup></select>

Exibição: No menu suspenso, a palavra "Carros" aparece como um título de grupo, mas não pode ser selecionada.
```
- ### ```<option>```
```
Exemplo: <option value="volvo">Volvo</option>

Exibição: O texto "Volvo" aparece como uma opção selecionável em um menu suspenso.
```
- ### ```<output>```
```
Exemplo: <output name="resultado">0</output>

Exibição: O número "0" é exibido. Esse número pode ser atualizado por um script com o resultado de um cálculo.
```
- ### ```<p>```
```
Exemplo: <p>Este é um parágrafo.</p>

Exibição: O texto "Este é um parágrafo." é exibido em uma linha separada, com um espaçamento acima e abaixo.
```
- ### ```<param>```
```
Exibição: Nada é exibido. É uma tag que passa informações para um objeto incorporado.
```
- ### ```<pre>```
```
Exemplo: <pre>Este texto   mantém o espaçamento.</pre>

Exibição: O texto é exibido em uma fonte monoespaçada, e todos os espaços extras e quebras de linha são mantidos exatamente como foram escritos no código.
```
- ### ```<progress>```
```
Exemplo: <progress value="50" max="100">50%</progress>

Exibição: Uma barra de progresso é exibida, preenchida até a metade. O texto "50%" pode ser exibido ao lado.
```
- ### ```<q>```
```
Exemplo: <q>Esta é uma citação curta.</q>

Exibição: As aspas são adicionadas automaticamente ao redor do texto: "Esta é uma citação curta.".
```
- ### ```<rb>, <rp>, <rt>, <rtc>, <ruby>```
```
Exemplo: <ruby>漢字<rt>kanji</rt></ruby>

Exibição: O texto "kanji" aparece em uma fonte menor, logo acima do texto principal "漢字".
```
- ### ```<s>```
```
Exemplo: <s>R$ 100,00</s> R$ 50,00

Exibição: O texto "R$ 100,00" é exibido com uma linha horizontal passando por ele, indicando que é um preço antigo.
```
- ### ```<samp>```
```
Exemplo: <samp>Arquivo não encontrado.</samp>

Exibição: O texto "Arquivo não encontrado." é exibido em uma fonte monoespaçada.
```
- ### ```<script>```
```
Exibição: Nada é exibido, mas o código JavaScript dentro da tag é executado, podendo mudar o conteúdo da página, mostrar pop-ups, etc.
```
- ### ```<section>```
```
Exibição: Não tem efeito visual, mas o navegador entende que o conteúdo é uma seção de um documento.
```
- ### ```<select>```
```
Exemplo: <select><option>...</option></select>

Exibição: Uma caixa de seleção suspensa é exibida.
```
- ### ```<small>```
```
Exemplo: <small>Direitos autorais 2023</small>

Exibição: O texto "Direitos autorais 2023" é exibido em um tamanho de fonte menor que o texto padrão.
```
- ### ```<source>```
```
Exibição: Nada é exibido. É uma tag que informa ao <video> ou <audio> onde encontrar os arquivos de mídia.
```
- ### ```<span>```
```
Exemplo: <span>texto colorido</span>

Exibição: Não tem efeito visual por padrão. Ele funciona como um contêiner invisível para uma parte do texto que pode ser estilizada com CSS, como mudar a cor.
```
- ### ```<strong>```
```
Exemplo: <strong>Texto importante.</strong>

Exibição: O texto "Texto importante." é exibido em negrito, com uma forte ênfase.
```
- ### ```<style>```
```
Exibição: Nada é exibido, mas as regras de estilo dentro da tag são aplicadas ao documento.
```
- ### ```<sub>```
```
Exemplo: H<sub>2</sub>O

Exibição: O "2" é exibido em um tamanho menor e ligeiramente abaixo do "H".
```
- ### ```<summary>```
```
Exibição: O texto é exibido com um ícone de seta. Ao clicar, o conteúdo do <details> se expande ou retrai.
```
- ### ```<sup>```
```
Exemplo: E = mc<sup>2</sup>

Exibição: O "2" é exibido em um tamanho menor e ligeiramente acima do "c".
```
- ### ```<svg>```
```
Exemplo: <svg width="100" height="100"><circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" /></svg>

Exibição: Um círculo vermelho com uma borda preta é desenhado na página.
```
- ### ```<table>```
```
Exibição: Exibe os dados em um formato de grade.
```
- ### ```<tbody>```
```
Exibição: Não tem efeito visual, mas define o corpo principal da tabela.
```
- ### ```<td>```
```
Exemplo: <td>Célula de dados</td>

Exibição: O texto "Célula de dados" é exibido em uma célula da tabela.
```
- ### ```<textarea>```
```
Exemplo: <textarea rows="4" cols="50">Insira seu texto aqui</textarea>

Exibição: Uma caixa de texto maior e redimensionável é exibida.
```
- ### ```<tfoot>```
```
Exibição: Não tem efeito visual, mas define o rodapé da tabela.
```
- ### ```<th>```
```
Exemplo: <th>Cabeçalho</th>

Exibição: O texto "Cabeçalho" é exibido em negrito e centralizado em uma célula, no topo de uma coluna.
```
- ### ```<thead>```
```
Exibição: Não tem efeito visual, mas define o cabeçalho da tabela.
```
- ### ```<time>```
```
Exemplo: <time datetime="2023-09-23">23 de setembro de 2023</time>

Exibição: O texto "23 de setembro de 2023" é exibido. A data formatada internamente pode ser usada por ferramentas de busca.
```
- ### ```<title>```
```
Exemplo: <title>Minha Página</title>

Exibição: Nada é exibido na página, mas o texto "Minha Página" aparece na aba do navegador.
```
- ### ```<tr>```
```
Exibição: Não tem efeito visual, mas define uma linha na tabela.
```
- ### ```<track>```
```
Exibição: Nada é exibido. É uma tag que informa ao navegador onde encontrar legendas ou descrições para um vídeo.
```
- ### ```<u>```
```
Exemplo: <u>Texto sublinhado.</u>

Exibição: O texto "Texto sublinhado." é exibido com um sublinhado.
```
- ### ```<ul>```
```
Exemplo: <ul><li>Item</li></ul>

Exibição: O texto "Item" é exibido em uma lista com marcadores (geralmente pontos).
```
- ### ```<var>```
```
Exemplo: ...onde <var>r</var> é o raio.

Exibição: O "r" é exibido em itálico, indicando que é uma variável.
```
- ### ```<video>```
```
Exemplo: <video controls><source src="video.mp4" type="video/mp4"></video>

Exibição: Um reprodutor de vídeo é exibido na página com os botões de controle para "Play", "Pause", barra de progresso, etc.
```
- ### ```<wbr>```
```
Exemplo: ...pode ser<wbr>quebrado aqui.

Exibição: Não tem efeito visual. Se a palavra for muito longa e não couber na linha, ela será quebrada na posição do <wbr>.
```