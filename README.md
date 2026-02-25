# rg-quotations
Quotations in computing based on a file by [Ria Galanos](https://github.com/riagalanos). Each quotation is designed to be printed as a classroom poster. These quotations have been augmented by ones from [HackerSays](http://hackersays.com/), [AZQuotes](https://azquotes.com/quotes/topics/computer-science.html), [adafruit quotations](https://adafruit.com/quotes) (one of which is shipped in every box!), other [Googleable](https://lmgtfy.app/?q=computer+science+quotations) quotation sites, and my [teaching](http://j.mp/psb_david_petty).

## `font-size` property

In addition, this was a chance to use [JavaScript](https://www.ecma-international.org/publications/standards/Ecma-262.htm) to adjust the `font-size` property of each quotation to fill a rectangle of a fixed size. This is accomplished by the [`get_text_size`](https://stackoverflow.com/questions/31305071/measuring-text-width-height-without-rendering) function using an HTML [`canvas`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/getContext) element to calcuate the areas of each line of text of each section in a certain font at a certain size and then scaling the `font-size` property to fill the area of the section. For example:

![RG quotations font-size](./rgq-layout.png)

<hr>

<div style="display: flex; flex-direction: row; justify-content: space-around; margin: 0 10%;">
<a href="https://dcpetty.github.io/rgq/">&#128279; permalink</a> 
<a href="https://github.com/dcpetty/rgq">&#128230; repository</a>
<!-- 
PERMALINK: https://dcpetty.github.io/mit-app-inventor/REPO/
REPOSITORY: https://github.com/dcpetty/mit-app-inventor/tree/main/REPO
MIT APP INVENTOR: https://code.appinventor.mit.edu/?repo=https://raw.githubusercontent.com/dcpetty/mit-app-inventor/refs/heads/main/REPO/REPO.aia
-->
</div>
