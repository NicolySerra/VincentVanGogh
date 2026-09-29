# 🎨 Vincent Van Gogh — Creative Profile Card

Um pequeno projeto desenvolvido como exercício de **HTML e CSS**, criado para experimentar composição visual, posicionamento de elementos, imagens, tipografia e estilização de uma página de perfil.

> 🎨 Projeto criado para praticar e brincar com possibilidades visuais utilizando apenas HTML e CSS.

 ## 📌 Sobre o projeto

A proposta deste projeto foi criar uma espécie de **cartão de perfil artístico**, inspirado em páginas de perfil e interfaces de redes sociais.

Durante o desenvolvimento, foram explorados:

* Estruturação de páginas com HTML5
* Estilização utilizando CSS3
* Posicionamento de elementos
* Uso de imagens e recursos externos
* Tipografia personalizada
* Variáveis CSS
* Formas geométricas utilizando `clip-path`
* Organização visual e composição de uma interface

O projeto não possui backend ou funcionalidades complexas. Seu objetivo principal foi **experimentar e aprender através da prática**.

---

## 🛠️ Tecnologias utilizadas

* HTML5
* CSS3
* Google Fonts
* Imagens externas
* CSS `clip-path`

---

## ✨ Elementos interessantes

### 🔷 Avatar personalizado

A imagem principal utiliza `clip-path` para criar um formato geométrico:

```css
clip-path: polygon(
    50% 0,
    100% 25%,
    100% 75%,
    50% 100%,
    0 75%,
    0 25%
);
```

Isso permite transformar a imagem retangular em uma forma semelhante a um **hexágono** sem precisar editar a imagem originalmente.

### 🎨 Variáveis CSS

Foram utilizadas variáveis para facilitar o controle das cores:

```css
html,
body {
    --black: hsl(240, 6%, 13%);
    --gray: hsl(240, 9%, 89%);
}
```

Assim, as cores podem ser reutilizadas em diferentes elementos sem precisar repetir seus valores.

### 📐 Layout

O projeto utiliza:

```css
display: grid;
place-items: center;
```

para centralizar o conteúdo na página, enquanto o container interno controla a largura e o alinhamento das informações.

---

## 📂 Estrutura

```text
VincentVanGogh/
│
├── index.html
├── style.css
│
└── img/
    ├── build.png
    ├── mask.png
    └── redes.png
```

---

## 🧠 O que pratiquei

Este projeto foi uma oportunidade para praticar conceitos fundamentais de desenvolvimento web:

**HTML**

* Estrutura semântica básica
* Imagens
* Links
* Listas
* Organização de conteúdo

**CSS**

* Flexbox
* CSS Grid
* Variáveis
* Margens e espaçamentos
* Posicionamento absoluto
* Pseudo-estrutura de elementos
* `clip-path`
* Backgrounds
* Tipografia

---

## 🚧 Possíveis melhorias

Como este foi um projeto experimental, existem várias possibilidades de evolução:

* [ ] Tornar o layout responsivo
* [ ] Corrigir e melhorar a utilização do Google Fonts
* [ ] Substituir imagens externas por assets próprios
* [ ] Adicionar links reais para redes sociais
* [ ] Criar animações e efeitos de hover
* [ ] Melhorar a acessibilidade
* [ ] Separar melhor os componentes visuais
* [ ] Adicionar uma versão para desktop

---

## 💡 Observação

Este projeto faz parte da minha coleção de **projetos experimentais**, desenvolvidos para praticar programação, testar ideias visuais e acompanhar minha evolução no desenvolvimento web.

Nem todo projeto precisa nascer com uma finalidade profissional. Alguns servem simplesmente para **aprender, experimentar e descobrir novas possibilidades**. 🎨

---

### 🚀 Desenvolvido por Nicoly Serra

[GitHub](https://github.com/NicolySerra)
