# 🌐 Exercícios de HTML

Repositório criado para prática de **HTML básico**, com exemplos de estrutura de páginas, listas, links e formatações de texto.

---

## 🌸Conteúdo

✔️ Estrutura básica de um documento HTML  
✔️ Títulos `<h1>` até `<h6>`  
✔️ Parágrafos e quebra de linha `<p>` `<br>`  
✔️ Uso de meta tags (`description`, `keywords`)  
✔️ Listas ordenadas `<ol>` e não ordenadas `<ul>`  
✔️ Links `<a>`  
✔️ Formatações de texto: **negrito**, *itálico*, <u>sublinhado</u>, sobrescrito e subscrito  
---

## 🎀Exemplos

### Estrutura de documento 1
```html
<!DOCTYPE html>
<html>
<head>
  <title>Jornal</title>
  <meta name="description" content="Página destinada as novidades e inovações">
  <meta name="keywords" content="inovação, escola, novidades, tecnologia, estudo">
</head>
<body>
  <h1>Título</h1>
</body>
</html>
Lista não ordenada
html

<ul>
  <li>Grande Sertão: Veredas</li>
  <li>Capitães de Areia</li>
  <li>Memórias Póstumas de Brás Cubas</li>
</ul>

---
```
# 🌐 Exercício de HTML - 2

Repositório com exercício prático de **HTML5**, explorando a construção de uma página completa com cabeçalho, navegação, formulários, conteúdo principal, lateral e rodapé.

---

## 🚀 Estruturas utilizadas

✔️ **Header** com barra de navegação (`<header>`, `<nav>`)  
✔️ **Links**  (incluindo acesso ao site)                                                                                                                                                                                                             
✔️ **Formulário** com campos de Login/Senha ou Cadastro (`<form>`, `<label>`, `<input>`, `<button>`)  
✔️ **Main** com parágrafos e divisões de conteúdo (`<main>`, `<p>`, `<div>`)  
✔️ **Aside** com tabela ou imagens (`<aside>`, `<table>`)  
✔️ **Imagens** (logo da página e notícia ilustrativa)  
✔️ **Footer** com lista de contatos (`<footer>`, `<ul>`, `<ol>`, `<li>`)  

## Estrutura básica do exercício 2

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Exercício HTML - 2</title>
</head>
<body>
  <!-- Cabeçalho e Navegação -->
  <header>
    <nav>
      <ul>
        <li><a href="https" target="_blank">Site</a></li>
      </ul>
    </nav>
  </header>

  <!-- Formulário -->
  <form>
    <label>Nome:</label>
    <input type="text" required>
    <label>E-mail:</label>
    <input type="email">
    <label>Telefone:</label>
    <input type="tel">
    <button>Enviar</button>
  </form>

  <!-- Conteúdo Principal -->
  <main>
    <div>
      <p>Primeiro parágrafo do conteúdo principal.</p>
      <p>Segundo parágrafo do conteúdo principal.</p>
      <img src="noticia.jpg" alt="Imagem de notícia">
    </div>
  </main>

  <!-- Conteúdo Lateral -->
  <aside>
    <table border="1">
      <tr><th>Dia</th><th>Evento</th></tr>
      <tr><td>Segunda</td><td>Reunião</td></tr>
      <tr><td>Terça</td><td>Palestra</td></tr>
    </table>
  </aside>

  <!-- Rodapé -->
  <footer>
    <ul>
      <li>Email: contato@empresa.com</li>
      <li>Telefone: (00) 0000-0000</li>
      <li>Endereço: Rua Exemplo, 123</li>
    </ul>
  </footer>
</body>
</html>


````
-----------------------------

=======> Como aplicar CSS✨✨✨

* Inline → dentro da própria tag HTML
<p style="color: red;">Texto em vermelho</p>


* Interno → dentro da tag <style> no HTML
<style>
  p { color: blue; }
</style>


* Externo → em um arquivo .css separado
<link rel="stylesheet" href="style.css">

 🎆Seletores básicos
 
/* Por elemento */
p { color: green; }

/* Por id */
#titulo { font-size: 24px; }

/* Por classe */
.destaque { background: yellow; }

🎨 Propriedades comuns

Cores e texto

color: red;
background-color: lightgray;
font-size: 18px;
font-family: Arial, sans-serif;
text-align: center;


Caixas e espaçamento

margin: 10px;   /* espaçamento externo */
padding: 15px;  /* espaçamento interno */
border: 1px solid black;


Tamanho

width: 200px;
height: 100px;

🖼️ Layout

Display

display: block;
display: inline;
display: flex;
display: grid;


Flexbox exemplo

.container {
  display: flex;
  justify-content: center;
  align-items: center;
}


Grid exemplo

.grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 10px;
}




