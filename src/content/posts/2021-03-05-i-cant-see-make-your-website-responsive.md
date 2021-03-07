---
template: blog-post
title: I Can't See - Make your Website Responsive!
slug: responsive
date: 2021-03-04 20:43
description: "This article covers responsive website layouts. "
featuredImage: /assets/ben-kolde-ajcipx1vdxi-unsplash.jpg
---
One issue I have with websites on mobile devices is that some aren't responsive. For example, I remember back in high school my school's website was a pain to navigate through because the website only targeted visitors who were on a desktop rather than any device smaller than that. I couldn't see the navigation bar clearly and when I tried to search for something, the search bar would be so small it would be difficult to tap. This frustration may be what users on your website may feel if you don't make it responsive!

## What is Responsive Web Design?

Mobile has changed the way everyone interacts with and designs websites. In order to adapt to these smaller screen sizes, the web industry/web designers needed a solution to adjust designs across various devices. This solution is responsive web design, in which the website's design responds to the user's behavior based on screen size, platform, and orientation. 

### Three Defining Features of Responsive Websites

1. Flexible Layouts: In CSS, we can create the layout of a website with a flexible grid. This method consists of columns that automatically adjust themselves to the size of the screen or browser window.
2. Media Queries: Media queries allow web designers to specify different styles for different screen sizes/devices. Sometimes having flexible layouts isn't enough since the columns may be too small to display content effectively.
3. Flexible images and videos: Flexible containers resize themselves as the user changes the browser or devices. By having a max-width property of 100%, the media content is scalable. 

## Responsive Web Design Basics

### Set the viewport and size content to the viewport

The meta viewport value 

```css
width=device-width;
```

instructs the page to match the screen's width in device-independent pixels, which are representations of a single pixel, which may on a high-density screen consist of many physical pixels (Andrew & LePage, 2020). This allows the page to adjust content to different screen sizes. Additionally, you may set the value of 

```css
initial-scale=1;
```

which instructs the browser to establish a 1:1 relationship between CSS pixels and device-independent pixels regardless of device orientation, and also allows the page to take advantage of the full landscape width. In addition to setting an initial-scale, there are also other attributes such as minimum-scale, maximum-scale, and user-scalable. However, when set, they may disable the user's ability to zoom in/out, which can cause accessibility issues, so it is not recommended to use them. 

When it comes to the content of the website, sometimes on a mobile device people are forced to scroll horizontally, which results in a poor user experience. For images, a common way to avoid a horizontal scrollbar is to set the images to a max-width of 100%. By doing this, the image shrinks to fit the space it has when the viewport size is smaller than the image and the image will not stretch larger than its natural size. An example is shown below:

```css
img {
  max-width: 100%;
  display: block;
}
```

### CSS Layout Techniques and Media Queries

As discussed before, in CSS, we can create the layout of a website with a flexible grid. This method consists of columns that automatically adjust themselves to the size of the screen or browser window. We can also use media queries that allow web designers to specify different styles for different screen sizes/devices. 

One layout method we can use is flexbox, which is typically used when you want to fit a set of items of different sizes into a row or rows. For example, the below code will look like this:

```css
.container {
  display: flex;
  flex-wrap: wrap;
  list-style: none;
  margin: 0;
  padding: 0;
}

.container li {
  flex: auto;
  background-color: rgba(0,0,0,.9);
  color: #fff;
  border-radius: .5em;
  padding: .5em;
  text-align: center;
}
```

![A picture of what the code will look like](/assets/blogpic.png "Flexbox Example")

Another layout method we can use is CSS Grid Layout which allows you to have more freedom with how you want to organize your content. Take the following example below:

```css
.container {
  display: grid;
  grid-template-columns: 1fr 3fr;
}
```

![A picture of what the code would look like](/assets/blogpic2.png "CSS Grid Example")

CSS Media queries make it easy to change styles based on the types of device users are on. We can use the following attributes for different screen sizes:

* `width` (`min-width`, `max-width`)
* `height` (`min-height`, `max-height`)
* `orientation`
* `aspect-ratio`

We can also test for other features such as the type of pointer used to interact with the device and whether the user can hover over elements:

* `hover`
* `pointer`
* `any-hover`
* `any-pointer`

### Breakpoints

It's best to design the content to fit on a small screen size (such as mobile devices) first, then expand the screen until a breakpoint becomes necessary. To insert a breakpoint, create two media queries at the end of your CSS for the component, one to use when the browser is a certain amount of pixels and below, and one for when it is wider than that many pixels. For example:

```css
@media (max-width:600px) {

}

@media (min-width:601px) {

}
```

After setting these breakpoints, you can see how your site looks by using Chrome DevTools. In Chrome DevTools, there is a built-in feature that allows you to see what your website looks like on different devices. 



## Responsive Web Design Examples

1. Dropbox

![Dropbox web design](/assets/dropbox-responsive-web-design.png "Dropbox web design")

Dropbox uses a fluid grid and flexible visuals. The images and font color change to accommodate the background color when switching from desktop to mobile devices.

2. Shoplify

![Shoplify web design](/assets/shopify-responsive-web-design.png "Shoplify web design")

The call-to-action button and illustrations are the only aspects of the website that change between desktop and mobile devices. They also make use of a hamburger icon for mobile devices. 

3. GitHub

![GitHub web design](/assets/github-responsive-web-design.png "GitHub web design")



Similar to Shoplify, they also use a hamburger icon for devices smaller than a desktop. When switching from a desktop to a tablet, the dark area changes from a two-column layout to a single-column layout, with the copy above the signup form instead of beside it. 



Now that you know how to make your website responsive, let's see how much you can improve it!



#### Sources

Thumbnail Picture by Ben Kolde:

https://unsplash.com/photos/Ajcipx1VDXI 



Articles:

[](https://xd.adobe.com/ideas/principles/web-design/responsive-web-design-2/)<https://xd.adobe.com/ideas/principles/web-design/responsive-web-design-2/>

[](https://web.dev/responsive-web-design-basics/)<https://web.dev/responsive-web-design-basics/>

[](https://www.invisionapp.com/inside-design/examples-responsive-web-design/)<https://www.invisionapp.com/inside-design/examples-responsive-web-design/>