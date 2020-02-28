# Pop's restaurant menu
![Schermafbeelding 2020-02-28 om 02 33 29](https://user-images.githubusercontent.com/45489420/75502298-c2893e80-59d2-11ea-9cfa-deb1ced0f4f0.png)
[Visit the website here](https://jenniferslagt.github.io/css-to-the-rescue-1920)

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

## What is progressive enhancement?
Progressive Enhancement (PE) is methodology that allows Web developers to concentrate on building the best possible websites for every user! So it has to work on every device, every browser, every internet connection so that everyone can interact with it. It offers a basic user experience and ensures stability. But it can costs more time from developers because they have to plan their project. In short: it emphasizes core web page content first.

### How did I apply PE?
To keep PE in mind, I changed the web fonts of the application.
I used a simple web font. When a user has a slow network it can take some time to load the whole content. So I just kept it on sans-serif. Nobody wants to wait for the content ;)

Because the (main) goal is to experiment with CSS, I don't think my application is the perfect example for PE. But it's always important to keep in mind that PE really matters for a good UX.

## Used data
I didn't know what the menu of Pop's was, so I decided to search it. I only used a part of it. In the source you'll see the link to the website I used. 

## Sources
* The menu I used: https://aminoapps.com/c/riverdale/page/blog/pops-menu/KWjE_PrMIMuBxP642xGzBLMz5RwmNekrb5n<br>
You can go to my wiki to find the sources per topic.
* PE: https://www.freecodecamp.org/news/what-is-progressive-enhancement-and-why-it-matters-e80c7aaf834a/ <br>
https://www.smashingmagazine.com/2009/04/progressive-enhancement-what-it-is-and-how-to-use-it/

## Reflection
I learned a lot about CSS in the past few weeks. I did knew that CSS was not only to apply a visual presentation, but also interaction. But the posibilities are way more than I thought. In the beginning I used the guide of website "CSS Tricks" a lot, because I thought this will contain a lot of the properties. Well, it has a lot of properties, but I found out the scope of CSS is much bigger. For example, you can combinate all this properties which can have an exciting output. CSS can change <u> a lot</u> of details. But I did have some struggles because of all those details (for example my struggles with the SVG's). Every detail can affect another detail. So sometimes the output wasn't what I expected. In short: the scope of CSS is very big, but don't forget to focus on the details. In the Netherlands we say: "Je ziet door de bomen het bos niet meer." 

## Credits
I would like to thank the teachers, the extra "help students", the visitors and my fellow students for helping me to accomplish my learning goals.
