# 🌐 Projeto HTML Básico – Trilha HTML DIO

Este projeto foi desenvolvido como parte da **Trilha de HTML** da DIO. O objetivo foi praticar os conceitos fundamentais de HTML, construindo um website simples com diversas tags aprendidas durante as aulas.

A ideia foi criar uma **estrutura básica de site**, aplicando todas as tags vistas na prática, além de pesquisar e usar algumas novas para expandir o conhecimento.

---

## 🧠 Objetivo

O desafio consistiu em:

✅ Criar um website simples e bem estruturado  
✅ Utilizar todas as principais tags aprendidas no curso  
✅ Pesquisar e aplicar novas tags sugeridas  
✅ Publicar o projeto em um repositório no GitHub

---

## 🛠️ Tecnologias e Ferramentas

- HTML5
- Editor de código (VS Code recomendado)
- Navegador web
- Git e GitHub

---

## 🏗️ Estrutura do Projeto

O projeto utiliza uma série de **tags HTML** para estruturar e organizar o conteúdo da página. Veja abaixo as principais utilizadas:

### ✍️ Tags de texto e formatação:

- `<h1>` até `<h6>`: títulos de diferentes níveis
- `<p>`: parágrafos
- `<mark>`: destaca uma palavra
- `<small>`: texto com tamanho reduzido
- `<i>`: texto em itálico
- `<u>`: sublinhado
- `<strong>`: negrito
- `<del>`: texto riscado
- `<font>`: muda a cor do texto (tag obsoleta, usada aqui para aprendizado)

### 🧾 Listas:

- `<ol>`: lista ordenada
- `<ul>`: lista não ordenada
- `<li>`: itens de lista

### 🌐 Links e navegação:

- `<a>`: âncoras e hyperlinks

### 🧪 Outros elementos:

- `<hr>`: linha horizontal
- `<sub>`: subscrito (ex: fórmulas químicas como H₂O)
- `<sup>`: sobrescrito (ex: potências como 2¹⁰)
- `<blockquote>`: citações em bloco
- `<abbr>`: abreviações com significado visível ao passar o mouse

---

## 💡 Exemplo de Código

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Projeto HTML Básico</title>
</head>
<body>

  <h1>Bem-vindo ao Meu Website</h1>
  <h2>Este é um subtítulo nível 2</h2>
  <h3>Subtítulo nível 3</h3>
  <h4>Subtítulo nível 4</h4>
  <h5>Subtítulo nível 5</h5>
  <h6>Subtítulo nível 6</h6>

  <p>Este é um parágrafo com uma palavra <mark>destacada</mark>.</p>
  <p>Texto com <i>itálico</i>, <u>sublinhado</u>, <strong>negrito</strong> e <small>pequeno</small>.</p>

  <hr>

  <p>Lista ordenada:</p>
  <ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
  </ol>

  <p>Lista não ordenada:</p>
  <ul>
    <li>Ler</li>
    <li>Jogar</li>
    <li>Estudar</li>
  </ul>

  <p>Visite a <a href="https://dio.me" target="_blank">DIO</a></p>

  <p>Fórmula da água: H<sub>2</sub>O</p>
  <p>2<sup>10</sup> = 1024</p>

  <blockquote>
    "A simplicidade é o último grau de sofisticação." – Leonardo da Vinci
  </blockquote>

  <p><font color="blue">Texto com a tag font (obsoleta, usada para fins didáticos).</font></p>
  <p>Este texto foi <del>riscado</del> com a tag del.</p>
  <p>Exemplo de abreviação: <abbr title="HyperText Markup Language">HTML</abbr></p>

</body>
</html>
