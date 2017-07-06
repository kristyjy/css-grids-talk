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
.col-12[
# Let's Compare
]

--

.col-6[

### Grid

- 2 Dimensional
- Children are Grid Items
- Useful for complex grid-based designs
]

.col-6[

### Flexbox

- 1 Dimensional
- Children can "Flex"
- Useful for alignment
]

--

.col-12[
### Both
- Are awesome!
- They can and **should** be used together!
]

---
# Browser Support
<img src="/images/caniuse.jpg" alt="Can I Use Grid" width="800" />

### But oh no IE and Edge!

Though IE and Edge do not support the latest spec they do support the old syntax and can easily use a fallback until Microsoft finishes their implementation.

---
# Let's Get Started

A basic grid can be built with 2 or 3 properties:

```css
.grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 20px;
}
```

Full Example: [Example 1 - Simple Grid](https://codepen.io/kristyjy/pen/d9a4771c5c7170aa3834095898e91e21/)
---
# Supporting All of the Browsers!

This grid example is the save as above but uses @supports for fallback

[Example 2 - Simple Grid with fallback](https://codepen.io/kristyjy/pen/9e2bddb28973e9da1f2c4fd0d9b8444f)

---
# The Real Power of Grid

CSS Grid comes with some fancy new properties and functions! It allows us to make a fully responsive grid with NO breakpoints!

[Example 3 - Multi Size Grid - No Breakpoints!](https://codepen.io/kristyjy/pen/b9dfbfad63f940819a9f308ef6b93872)

---
# My grid is smarter than your honors student!

Using the rule:

```css
.grid {
	grid-auto-flow: dense;
}
```

[Example 4 - Auto Flow!](https://codepen.io/kristyjy/pen/e081e6c0395346b5ed84bb0c60edb384)

---
# References
- [W3C CSS Grid Layout Module Spec](https://www.w3.org/TR/css3-grid-layout/)
- [Grid By Example - Rachael Andrew](https://gridbyexample.com/)
- [Complete Guide to Grid - Chris House](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [An Introduction to the FR CSS Unit - Robin Rendle](https://css-tricks.com/introduction-fr-css-unit/)
- [How the minmax() Function Works - Ire Aderinokun](https://bitsofco.de/how-the-minmax-function-works/)
- [Should I use Grid or Flexbox? - Rachael Andrew](https://rachelandrew.co.uk/archives/2016/03/30/should-i-use-grid-or-flexbox/)
- [Does CSS Grid Replace Flexbox? - Robin Rendle](https://css-tricks.com/css-grid-replace-flexbox/)
- [Solving Problems With CSS Grid and Flexbox: The Card UI - Ian Yates](https://webdesign.tutsplus.com/tutorials/solving-problems-with-css-grid-and-flexbox-the-card-ui--cms-27468)
---
class: impact

# Questions?
