# 🔍 Seletores de CSS

<p align="left">
    <img src="./Arquivos/Seletores-logo.png" alt="Logo" width="45%">
</p>

**Autor:**  *João Victor Moura*

**Curso:**  *ADS*

> Guia prático de consulta rápida para iniciantes em CSS, com foco nos seletores importantes do CSS3, útil para quem precisa revisar algo rápido.

---

## 🎯 Seletores

- ### **Ponto (.)**
```
Seleciona uma classe. É o mais comum para aplicar estilos a vários elementos que compartilham o mesmo nome de classe.

Exemplo: .minha-classe { color: blue; }
```
- ### **Sustenido/Hash (#):**
```
Seleciona um ID. IDs são únicos em uma página e são usados para estilizar um único elemento específico.

Exemplo: #meu-id { font-size: 20px; }
```
- ### **Nenhum Símbolo**
```
Seleciona uma tag HTML. Você pode estilizar todos os elementos de um tipo específico, como p, div ou h1.

Exemplo: p { margin-bottom: 10px; }
```
- ### **Dois Pontos (:)**
``` 
Usado para pseudo-classes, que selecionam elementos em um estado específico, como hover (quando o mouse está sobre o elemento) ou visited (quando um link já foi visitado).

Exemplo: a:hover { color: orange; }
```
- ### **Dois Pontos Duplos (::)**
```
Usado para pseudo-elementos, que selecionam uma parte de um elemento. Por exemplo, ::before para adicionar conteúdo antes de um elemento ou ::after para adicionar depois.

Exemplo: p::before { content: "Olá!"; }
```

## ✅ Exemplo Completo

#### HTML
```bash
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Exemplo de Seletores CSS</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>

    <h1>Título Principal</h1>

    <div id="container-principal">
        <p class="paragrafo-destaque">Este é o primeiro parágrafo dentro do container.</p>
        <p>Este é o segundo parágrafo normal.</p>
        <p>Este é o terceiro parágrafo, que será estilizado quando passarmos o mouse por cima.</p>
    </div>

    <a href="https://www.google.com" class="link-externo">Ir para o Google</a>
    <br>
    <a href="https://www.google.com/search?q=exemplo" class="link-externo">Pesquisar por Exemplo</a>
    
    <button class="botao-principal">Clique aqui</button>
    
</body>
</html>
```

#### CSS
```bash
/* Seletor de Tag: aplica a todos os elementos h1 */

h1 {
    color: darkred;
    text-align: center;
}

/* Seletor de ID: aplica APENAS ao elemento com o id "container-principal" */

#container-principal {
    background-color: #f0f0f0;
    padding: 20px;
    border: 1px solid #ccc;
    margin: 20px;
}

/* Seletor de Classe: aplica a qualquer elemento com a classe "paragrafo-destaque" */

.paragrafo-destaque {
    font-weight: bold;
    font-size: 1.1em;
}

/* Pseudo-classe: muda a cor do link quando o mouse está sobre ele */

.link-externo:hover {
    color: orange;
    text-decoration: none;
}

/* Pseudo-elemento: adiciona o texto "(link externo)" após o link */

.link-externo::after {
    content: " (link externo)";
    font-size: 0.8em;
    color: gray;
}
```