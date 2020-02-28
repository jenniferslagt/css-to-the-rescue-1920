# Pop's restaurant menu
![Schermafbeelding 2020-02-26 om 14 39 59](https://user-images.githubusercontent.com/45489420/75350207-66290080-58a6-11ea-8bb9-8904f73ad50a.png)


## Description
Do you know Riverdale? It's one of my favourite series on Netflix. In Riverdale, there's a restaurant called Pop's Chock' Lit Shoppe. Pop's has its own style: it's very retro and it gots some nice neon lights. I make a interactive menu for Pop's by using pure CSS and HTML.


## What is CSS?
CSS (Cascading Style Sheet) is used for the seperation and presentation of of a html page. For example, the layout, the fonts and the styling of a page. But it is more than styling. It can also add interaction, like animation, transitions or a hover. 

## Learning Goals / Features
This are the main things I've applied (and learned!) in the past few weeks:
* I made some pure animations which are only styled and animationed with CSS. See wiki > page: "A pure CSS animation".
* I've made a cool hover animation: the logo of Pop's falls down when a user hovers over it. I made this with `@keyframes` where I transform the logo on a specific moment of the animation. 
* I used CSS enitities for fun. These are CSS codes which convert numbers, letters or even some white space (and who knows maybe more :)).
* I used z-index to play with the layers of elements. If the index of a element is higher, than it becomes on the foreground.
* I didn't use any classes. Instead, I used child & sibling selectors, `:nth-child` (which selects the child of his parent) and  a simple CSS selector where you just use `[select-this]` in css and `<div select-this></div>` in HTML.
* I changed the cursor of the user. I made an kind of neon cursor (which becomes green at a hover). This must be a PNG file.
* I changed the scrollbar and made it red by using `::-webkit-scrollbar`.
* I made soms SVG's in illustrator and found out that you can export this as a code. This can be a extremely long code. If you change the vector (for example by making less paths or circles) the code can be shorter.
* All the SVG's haven't unique ID's or classes. The consequence about this is that styles are completely ruined :(. Solution: delete the `<style>` elements and apply CSS for the style. See my wiki > page: "Using CSS on a SVG" to read more about this.
* I made my application responsive without any media queries. I used flexbox (`display:flex`) to fix this.
* I learned what progressive enhancement is (see the next paragraph :))
* I've made a crazy animation with smoke! When the page loads, a video (the smoke) is played and the word "MENU" appears. I didn't know that it's possible to make a cool animation with a video. I used `object-fit: cover;` to make the optimal size of the video.
* I applied a filter with `backdrop-filter` on a image. I guess Photoshop is not longer neccessary!
* I found out that you can use GIF's as a background:). The disadvantage is that you can't apply `backdrop-filter`.
* I also found out that you can even add attributes with CSS! I used this: `content: attr(data-hover);`. (But actually I also didn't know what data-hover means).
* I worked with pseudo-elements (a keyword that lets me style a specific part of the selected element). For example, I used this `h4::first-line`.
* I changed the background of a text by using `-webkit-background-clip: text;`. 
* I found out that there's a special CSS property which <u>only</u> works on a `q` element. This property is called `quotes`. The funny thing is that the value is a quotation mark between a quotation mark.


## Used data
I didn't know what the menu of Pop's was, so I decided to search it. I only used a part of it. In the source you'll see the link to the website I used.

## Sources
* The menu I used: https://aminoapps.com/c/riverdale/page/blog/pops-menu/KWjE_PrMIMuBxP642xGzBLMz5RwmNekrb5n<br>
You can go to my wiki to find the sources per topic.

## Reflection

## Credits
I would like to thank the teachers, the extra "help students", the visitors and my fellow students for helping me to accomplish my learning goals.


<!-- Add a link to your live demo in Github Pages 🌐-->

<!-- ☝️ replace this description with a description of your own work -->

<!-- Add a nice image here at the end of the week, showing off your shiny frontend 📸 -->

<!-- Maybe a table of contents here? 📚 -->

<!-- How about a section that describes how to install this project? 🤓 -->

<!-- ...but how does one use this project? What are its features 🤔 -->

<!-- What external data source is featured in your project and what are its properties 🌠 -->

<!-- Maybe a checklist of done stuff and stuff still on your wishlist? ✅ -->

<!-- How about a license here? 📜 (or is it a licence?) 🤷 -->
