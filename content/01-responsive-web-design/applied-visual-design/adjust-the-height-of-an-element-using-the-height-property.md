---
id: 587d7791367417b2b2512ab5
title: Adjust the Height of an Element Using the height Property
challengeType: 0
videoUrl: 'https://scrimba.com/c/cEDaDTN'
forumTopicId: 301034
dashedName: adjust-the-height-of-an-element-using-the-height-property
---

# --description--

<<<<<<< HEAD
Você pode especificar a altura de um elemento usando a propriedade `height` em CSS, semelhante à propriedade `width`. Aqui está um exemplo que altera a altura de uma imagem para 20 px:
=======
Você pode especificar a altura de um elemento usando a propriedade `height` no CSS, igual a propriedade `width`. Aqui está um exemplo que muda a altura de uma imagem para 20px:
>>>>>>> 57207be849f6b6fc94c5c0194845410afa5dbdbe

```css
img {
  height: 20px;
}
```

# --instructions--

<<<<<<< HEAD
Adicione uma propriedade `height` à tag `h4` e defina-a como 25px.

**Nota:** Você pode precisar estar com 100% de zoom para passar no teste do desafio.

# --hints--

Seu código deve alterar a propriedade `h4` `height` para um valor de 25 pixels.
=======
Adicione uma propriedade `height` à tag `h4` e defina o valor para 25px.

**Note:** Você talvez precise estar com o zoom em 100% para passar no teste desse desafio

# --hints--

Seu código deverá mudar a propriedade `height` da tag `h4` para o valor 25 pixels.
>>>>>>> 57207be849f6b6fc94c5c0194845410afa5dbdbe

```js
assert(
  Math.round(document.querySelector('h4').getBoundingClientRect().height) ===
    25 &&
    /h4{\S*height:25px(;\S*}|})/.test($('style').text().replace(/\s/g, ''))
);
```

# --seed--

## --seed-contents--

```html
<style>
  h4 {
    text-align: center;

  }
  p {
    text-align: justify;
  }
  .links {
    margin-right: 20px;
    text-align: left;
  }
  .fullCard {
    width: 245px;
    border: 1px solid #ccc;
    border-radius: 5px;
    margin: 10px 5px;
    padding: 4px;
  }
  .cardContent {
    padding: 10px;
  }
</style>
<div class="fullCard">
  <div class="cardContent">
    <div class="cardText">
      <h4>Google</h4>
      <p>Google was founded by Larry Page and Sergey Brin while they were Ph.D. students at Stanford University.</p>
    </div>
    <div class="cardLinks">
      <a href="https://en.wikipedia.org/wiki/Larry_Page" target="_blank" class="links">Larry Page</a>
      <a href="https://en.wikipedia.org/wiki/Sergey_Brin" target="_blank" class="links">Sergey Brin</a>
    </div>
  </div>
</div>
```

# --solutions--

```html
<style>
  h4 {
    text-align: center;
    height: 25px;
  }
  p {
    text-align: justify;
  }
  .links {
    margin-right: 20px;
    text-align: left;
  }
  .fullCard {
    width: 245px;
    border: 1px solid #ccc;
    border-radius: 5px;
    margin: 10px 5px;
    padding: 4px;
  }
  .cardContent {
    padding: 10px;
  }
</style>
<div class="fullCard">
  <div class="cardContent">
    <div class="cardText">
      <h4>Google</h4>
      <p>Google was founded by Larry Page and Sergey Brin while they were Ph.D. students at Stanford University.</p>
    </div>
    <div class="cardLinks">
      <a href="https://en.wikipedia.org/wiki/Larry_Page" target="_blank" class="links">Larry Page</a>
      <a href="https://en.wikipedia.org/wiki/Sergey_Brin" target="_blank" class="links">Sergey Brin</a>
    </div>
  </div>
</div>
```
