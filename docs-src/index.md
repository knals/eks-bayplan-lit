---
layout: page.11ty.cjs
title: <eks-bayplan-lit> ⌲ Home
---

# &lt;eks-bayplan-lit>

`<eks-bayplan-lit>` is an awesome element. It's a great introduction to building web components with LitElement, with nice documentation site as well.

## As easy as HTML

<section class="columns">
  <div>

`<eks-bayplan-lit>` is just an HTML element. You can it anywhere you can use HTML!

```html
<eks-bayplan-lit></eks-bayplan-lit>
```

  </div>
  <div>

<eks-bayplan-lit></eks-bayplan-lit>

  </div>
</section>

## Configure with attributes

<section class="columns">
  <div>

`<eks-bayplan-lit>` can be configured with attributed in plain HTML.

```html
<eks-bayplan-lit name="HTML"></eks-bayplan-lit>
```

  </div>
  <div>

<eks-bayplan-lit name="HTML"></eks-bayplan-lit>

  </div>
</section>

## Declarative rendering

<section class="columns">
  <div>

`<eks-bayplan-lit>` can be used with declarative rendering libraries like Angular, React, Vue, and lit-html

```js
import {html, render} from 'lit-html';

const name = 'lit-html';

render(
  html`
    <h2>This is a &lt;eks-bayplan-lit&gt;</h2>
    <eks-bayplan-lit .name=${name}></eks-bayplan-lit>
  `,
  document.body
);
```

  </div>
  <div>

<h2>This is a &lt;eks-bayplan-lit&gt;</h2>
<eks-bayplan-lit name="lit-html"></eks-bayplan-lit>

  </div>
</section>
