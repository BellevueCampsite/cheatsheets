---
title: Portfolio
category: Bootstrap
layout: 2017/sheet
tags: Featured
---

### Position stacked blocks of fixed size in the center
Use __max-width__ to define size of the blocks you're going to put in the stack. Afterwards, style each of your containers using __mx-auto__ class from Bootstrap to proportionally fill the empty space on the left & right of an every container, therefore keeping your fixed-size block always in the center.
```css
/* style.css */
section { max-width: 1024px; } /* size of the block */
```
    ...
    <link href="style.css" rel="stylesheet">
    ...
    <section class="mx-auto">
      #about me
    </section>
    <section class="mx-auto">
      #portfolio
    </section>
    <section class="mx-auto">
      #contact me
    </section>
