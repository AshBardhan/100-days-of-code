# 100 Days Of Code - Log

### Day 1: June 24, 2017 (Saturday)

**Today's Progress**: Getting started with SVG.

**Thoughts**: I've been thinking about this for a long time. Just learning and pracitising the basics. I'm hoping to make some really awesome art using SVG in future. Perhaps coding CSS images is too mainstream for me now. :P

**Link(s) to work**
1. [SVG Tutorial Reference | Jenkov](http://tutorials.jenkov.com/svg/index.html)
2. [SVG Tutorial Reference | W3C Schools](https://www.w3schools.com/graphics/svg_intro.asp)

### Day 2: June 25, 2017 (Sunday)

**Today's Progress**:
1. Learned SVG elements are their attributes
2. Created an image of "Peacock" in SVG at Codepen

**Thoughts**: Tutorials by Jenkov are more comprehrensive and really helpful for intermediate level coders. I had fun while coding in SVG, though it was challening at the beginning. But coding CSS images really helped me out here as I always have the appraoch of figuring out common patterns before jumping to code. And besides, it took me almost 2 hours to get those curves right. :P

**Link(s) to work**
1. [Peacock SVG | Codepen](https://codepen.io/AshBardhan/details/bRogLR)

### Day 3: June 26, 2017 (Monday)

**Today's Progress**:
1. Learned SVG animation
2. Added animations on the previously made "Peacock" SVG at Codepen

**Thoughts**: I always love to make animations in CSS. So I gave it a shot in SVG as well. It is interesting and bit challenging. But too many elements and attributes have to be put inside the code to make it work, especially on reusable elements with minor tweaks. I feel CSS animation is better and it's great in SCSS. I'll try to do that way tomorrow. Anyways, Eid Mubarak everybody! :)

**Link(s) to work**
1. [Peacock SVG - Animated | Codepen](https://codepen.io/AshBardhan/details/owGVXJ/)

### Day 4: June 27, 2017 (Tuesday)

**Today's Progress**:
1. Separated the animation logic from the previously made "Peacock" SVG and added it in CSS.
2. Applied [BEM appraoch](https://css-tricks.com/bem-101/) while naming CSS classes.

**Thoughts**: The code seems neat now (especially the SVG), but the Line of code (LoC) has increased overall. However, you do have a separate control while animating (especially on common elements like - green feathers of the peacock). Another thing I've noticed that the green feathers get repainted in pure SVG code while toggling tabs, but not in CSS animations. Still gotta make my source code shorter by using SCSS later on.

**Link(s) to work**
1. [Peacock SVG + CSS - Animated | Codepen](https://codepen.io/AshBardhan/details/rwYEPK/)

### Day 5: June 28, 2017 (Wednesday)

**Today's Progress**:
1. Optimized my CSS animations in "Peacock" SVG, using SCSS preprocessor.
2. Discovered the problem behind [repainting of SVG animated peacock feathers](https://twitter.com/CreativeBakchod/status/879911856793567232). Had to [initialize position on every component](https://twitter.com/CreativeBakchod/status/880282925639507968) to avoid repainting. That's a bummer! :P

**Thoughts**: Well coding in SCSS is really fun. You can do a lot programming using SCSS, especially loops, nesting, string concatenation and arithmetic operations. It is helpful when you've some components having common design pattern (sometimes minor tweaks in position or animations though). And for BEM lovers, this is best thing you can ever have. Just check my code mentioned in the links below and you'll know why. ;)

Also, my LoC has been reduced from 81 to 48. That's better, cleaner and prettier.
[Ahh! I love it](http://i1.kym-cdn.com/photos/images/newsfeed/000/591/928/94f.png)

**Link(s) to work**
1. [Peacock SVG + SCSS - Animated | Codepen](https://codepen.io/AshBardhan/details/xrpyor/)
2. [Peacock SVG - Animated (no more repainting) | Codepen](https://codepen.io/AshBardhan/details/owGVXJ/)