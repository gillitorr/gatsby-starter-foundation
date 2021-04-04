---
template: blog-post
title: Bored? Try this CSS trick all the cool devs are using!
slug: /cssanimations
date: 2021-04-03 20:14
description: "Learn about CSS animations and how they can liven up your website
  in cool and fun ways. "
featuredImage: /assets/pankaj-patel-sxihya4oejs-unsplash.jpg
---
**CSS Animation? What is that?**

In CSS, there is an animation property that can be used to animate other properties such as color, background-color, height/width, etc., without the use of JavaScript. Each animation is defined by the rule @keyframes, which is then called with the animation property. For example, in this [codepen](https://codepen.io/team/css-tricks/pen/ZGYZBx) found below, written by the website CSS-tricks, the animation "pulse" will change from blue to red in a time span of 5 seconds, infinitely. 

<iframe height="265" style="width: 100%;" scrolling="no" title="A simple animation" src="https://codepen.io/team/css-tricks/embed/ZGYZBx?height=265&theme-id=dark&default-tab=css,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/team/css-tricks/pen/ZGYZBx'>A simple animation</a> by CSS-Tricks
  (<a href='https://codepen.io/css-tricks'>@css-tricks</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

There are also sub-properties:

* animation-name: name of the @keyframes rule
* animation-duration: length of time it takes for the animation to complete one cycle
* animation-timing-function: establish a preset acceleration curve (ex: ease, linear)
* animation-delay: time between the element being loaded and the start of the animation sequence
* animation-direction: set direction of animation after the cycle (default: resets on each cycle)
* animation-iteration-count: number of times the animation will play
* animation-fill-mode: set which values are applied before or after the animation
* animation-play-state: pause/play the animation

So what are some cool CSS animations we can learn and practice from? Let's take a look.

**(Pure) CSS Animation Examples** 

After reading Brenda Stokes Barron's article "17 Cool Pure CSS Animations," I've compiled five animations I thought were the coolest and that could be used for future projects. 

1. [Parallax Star Background](https://codepen.io/saransh/pen/BKJun)

   Written by Saransh Sinha, this CSS animation allows users to experience a starry night while exploring the page.  We can see from the code that there are three types of stars that move at different speeds, really enhancing the starry night/outer space feeling. Personally, I would use this as either a home page or loading page, with additional text and CSS styling to bring it together. For example, on a loading page, maybe another CSS animation that could be added is a shooting star or a flying UFO. 

<iframe height="265" style="width: 100%;" scrolling="no" title="Parallax Star background in CSS" src="https://codepen.io/saransh/embed/BKJun?height=265&theme-id=dark&default-tab=css,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/saransh/pen/BKJun'>Parallax Star background in CSS</a> by Saransh Sinha
  (<a href='https://codepen.io/saransh'>@saransh</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

2. [3D Sphere](https://codepen.io/iamlark/pen/jYzYJg)

   A colorful and fun animation that you cannot take your eyes off of, this 3D sphere written by Sergej Skrjanec would be a great way to captivate user's attention as your web page is loading. 

<iframe height="265" style="width: 100%;" scrolling="no" title="Pure CSS 3D Sphere" src="https://codepen.io/iamlark/embed/jYzYJg?height=265&theme-id=dark&default-tab=css,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/iamlark/pen/jYzYJg'>Pure CSS 3D Sphere</a> by Sergej Skrjanec
  (<a href='https://codepen.io/iamlark'>@iamlark</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

3. [CSS Border Animation](https://codepen.io/Rplus/pen/lEDBj)

   Another creative addition to making your website livelier, this CSS border animation draws users' attention to the content inside of it. It would be good to use as a loading page or maybe even for a hover effect for a button.

<iframe height="265" style="width: 100%;" scrolling="no" title="[PURE CSS] border animation without svg" src="https://codepen.io/Rplus/embed/lEDBj?height=265&theme-id=dark&default-tab=css,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/Rplus/pen/lEDBj'>\\\[PURE CSS] border animation without svg</a> by Rplus
  (<a href='https://codepen.io/Rplus'>@Rplus</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

4. [Animated CSS Mail Button](https://codepen.io/jakegilesphillips/pen/MveNLe)

What better way to open an e-mail than actually opening an envelope on screen! This CSS Mail button written by Jake Giles-Phillips shows a creative hover effect for a button that looks like an envelope. One way I would use this button is for when users have messages they want to read, they can click this button that will reveal all the messages they have. 

<iframe height="265" style="width: 100%;" scrolling="no" title="Animated CSS Mail Button" src="https://codepen.io/jakegilesphillips/embed/MveNLe?height=265&theme-id=dark&default-tab=css,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/jakegilesphillips/pen/MveNLe'>Animated CSS Mail Button</a> by Jake Giles-Phillips
  (<a href='https://codepen.io/jakegilesphillips'>@jakegilesphillips</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>
  
5. [Glowing Loader](https://codepen.io/Maxoor/pen/JZZvXJ) 

In this CSS animation written by Maxime Rossignol, two dots chase each other around while the user is waiting for the website to load. A creative and fun experience for users for all ages!

<iframe height="265" style="width: 100%;" scrolling="no" title="The Glowing Loader - Pure CSS Animation" src="https://codepen.io/Maxoor/embed/JZZvXJ?height=265&theme-id=dark&default-tab=css,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/Maxoor/pen/JZZvXJ'>The Glowing Loader - Pure CSS Animation</a> by Maxime Rossignol
  (<a href='https://codepen.io/Maxoor'>@Maxoor</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>



After seeing these creative works, I decided to try to make a button that had a shine effect:
<iframe height="265" style="width: 100%;" scrolling="no" title="CSS Button with Glowing Background" src="https://codepen.io/gillitorr/embed/BapRMNz?height=265&theme-id=dark&default-tab=css,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/gillitorr/pen/BapRMNz'>CSS Button with Glowing Background</a> by gillitorr
  (<a href='https://codepen.io/gillitorr'>@gillitorr</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>



**Animate.css**

While exploring through the wonders of Google, I stumbled upon Animate.css on [animate.style](animate.style). As the website states, "Animate.css is a library of ready-to-use, cross-browser animations for use in your web projects. Great for emphasis, home pages, sliders, and attention-guiding hints".

Animation.css is installed with npm

`$ npm install animate.css --save`

Once it is installed, you can add the class `animate__animated` to an element, along with any of the animation names with `animate__` as its prefix. If you look on the website, there is a whole list of animations you can do:

* Attention seekers (bounce, flash, pulse, shakeX/Y)
* Back entrances (backInDown/Left/Right/Up)
* Back exits (BackOutDown/Left/Right/Up)
* Bouncing entrances
* Bouncing exists
* Fading entrances
* Fading exists
* Flippers
* Lightspeed
* Rotating entrances
* Rotating exits
* Specials (hinge, jackInTheBox, rollIn/Out)

You can also use the provided animations `keyframes`directly. For example:

```css
.my-element {
  display: inline-block;
  margin: 0 0.5rem;

  animation: bounce; /* referring directly to the animation's @keyframe declaration */
  animation-duration: 2s; /* don't forget to set a duration! */
}
```

Additionally, you can make CSS custom properties. If you need to change an animation duration, you can set a new value to globally or locally. It also makes it easy to change all your animations time-constrained properties. Anime.css also comes with some utility classes, such as delay classes, slow/slower/fast/faster classes, and repeating classes. 

While this can improve an interface's UX, it is important to follow some guidelines in order to prevent worsening user experience. 

1. Meaningful animations: Avoid animating an element just for the sake of it
2. Don't animate large element: It won't bring much value to the user
3. Don't animate root elements: This can trigger some browser bugs, and generally does not bring good value to your UX
4. Avoid infinite animations: It may annoy your users or distract them from the content you are trying to provide
5. Keep in mind the initial and final state of your elements: `animation-fill-mode` controls the state of an element before and after the animation. You can change the default from `both`to what you need.
6. Don't disable the prefers-reduced-motion media query: This is a critical accessibility feature that should never be disabled since it helps users who have vestibular/seizure disorders.

You can also use animate.css with JavaScript or make a custom build. 

CSS animations provide users with fun and engaging experiences, but it is always important to keep in mind what element you are animating and why you are animating it. Which elements do you need to draw attention to? Which animations are not that necessary? Now that you've learned more about CSS animations, join the cool developers featured in this blog and create and innovate some designs!

Sources:

https://css-tricks.com/almanac/properties/a/animation/ 

https://1stwebdesigner.com/17-cool-pure-css-animations/

https://animate.style/ 

Parallax Pixel Stars: https://codepen.io/saransh/pen/BKJun

3D Sphere: https://codepen.io/iamlark/pen/jYzYJg

Border: https://codepen.io/Rplus/pen/lEDBj

Mail Button: https://codepen.io/jakegilesphillips/pen/MveNLe

Glowing Loader: https://codepen.io/Maxoor/pen/JZZvXJ

Thumbnail Picture: https://unsplash.com/photos/SXihyA4oEJs

My Inspiration for my CodePen: 
https://codepen.io/dhanishgajjar/pen/NgQqVj 

My CodePen: https://codepen.io/gillitorr/pen/BapRMNz