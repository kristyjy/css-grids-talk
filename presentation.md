title: CSS Grids
class: animation-fade
layout: true

.bottom-bar[
  **{{title}}** - By Kristy Yeaton
]

---

class: impact

# {{title}}
## How to start using them TODAY!
### By: Kristy Yeaton

---
# What is CSS Grid?
--

### Grid as defined by W3C
> This CSS module defines a two-dimensional grid-based layout system, optimized for user interface design. In the grid layout model, the children of a grid container can be positioned into arbitrary slots in a predefined flexible or fixed-size layout grid.

--

### TLDR; (What I think of CSS Grids)
> CSS Grids are native solution for complex and simple grid layouts alike and gives us the power to build things that were previously impossible with CSS alone.

---
# But what about Flexbox?
--

### Flexbox as defined by W3C
> The specification describes a CSS box model optimized for user interface design. In the flex layout model, the children of a flex container can be laid out in any direction, and can “flex” their sizes, either growing to fill unused space or shrinking to avoid overflowing the parent. Both horizontal and vertical alignment of the children can be easily manipulated. Nesting of these boxes (horizontal inside vertical, or vertical inside horizontal) can be used to build layouts in two dimensions.

---
# Grid vs Flexbox

### Key Differences
--

- 1 Dimensional vs 2 Dimensional
--

- Flexible Size vs Grid
--

- Use for alignment

---
# Browser Support

---
# Let's Jump In!
a simple use of grid

---
# Our New Friends the FR Unit + the minmax Function
explain how grids use FR w/ examples

---
# The Real Power of Grid
show some complex grid examples

---
# Supporting All of the Browsers!
show complex grid example using @supports for fallback

---
# References
- [W3C CSS Grid Layout Module Spec](https://www.w3.org/TR/css3-grid-layout/)
- [Grid By Example - Rachael Andrew](https://gridbyexample.com/)
- [Complete Guide to Grid - Chris House](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [An Introduction to the FR CSS Unit - Robin Rendle](https://css-tricks.com/introduction-fr-css-unit/)
- [How the minmax() Function Works - Ire Aderinokun](https://bitsofco.de/how-the-minmax-function-works/)
- [Should I use Grid or Flexbox? - Rachael Andrew](https://rachelandrew.co.uk/archives/2016/03/30/should-i-use-grid-or-flexbox/)
- [Does CSS Grid Replace Flexbox? - Robin Rendle](https://css-tricks.com/css-grid-replace-flexbox/)
---
class: impact

# Questions?

---
# The basics

## Getting started

Use [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to write your slides. Don't be afraid, it's really easy!

--

## Making points

Look how you can make *some* points:
--

- Create slides with your **favorite text editor**
--

- Focus on your **content**, not the tool
--

- You can finally be **productive**!

---

# There's more

## Syntax highlighting

You can also add `code` to your slides:
```html
<div class="impact">Some HTML code</div>
```

## CSS classes

You can use .alt[shortcut] syntax to apply .big[some style!]

...or just <span class="alt">HTML</span> if you prefer.

---

# And more...

## 12-column grid layout

Use to the included **grid layout** classes to split content easily:
.col-6[
  ### Left column

  - I'm on the left
  - It's neat!
]
.col-6[
  ### Right column

  - I'm on the right
  - I love it!
]
