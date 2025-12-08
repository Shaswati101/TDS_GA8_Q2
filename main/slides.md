---
marp: true
title: Custom Marp Presentation
author: 22f2001495@ds.study.iitm.ac.in
paginate: true
theme: mytheme
class: invert

---

# My Marp Presentation  
### by 22f2001495@ds.study.iitm.ac.in

Welcome to a custom-themed Marp slide deck.

---

<!-- Background image -->

![bg](./images/my_img.jpg)

# Starry Starry Nights

This is a famous painting by the **Vincent Van Gough**

---

# Algorithmic Complexity

You can include mathematical expressions:

Inline math:  
`$O(\log n)$` is logarithmic,  
`$O(n^2)$` is quadratic.

Block math:

$$
T(n) = T\left(\frac{n}{2}\right) + O(1)
$$

This solves to:

$$
T(n) = O(\log n)
$$

---

# Custom Theme Definition

Below is the custom theme used in this presentation.

```css
/* mytheme.css */
@charset "UTF-8";

section {
  background-color: #111;
  color: #fff;
}

section.invert {
  background-color: #eee;
  color: #000;
}

h1, h2, h3 {
  letter-spacing: 0.5px;
}

footer {
  color: #bbb;
}
