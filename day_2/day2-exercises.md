##  There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?

* **Ordered lists** uses numbers to list items in order. These are created using the tags `<ol></ol>` and it contains elements with listed items between the tags `<li></li>`. It's possible to change the way an `<ol>` list orders items through an attribute (whether you want roman numerals, numbers, or letters) but it is recommended to use CSS for this instead.
* **Unordered** lists use bullet points and do not communicate order. They are created using the tags `<ul></ul>`, and similarly they utilize `<li></li>` and their appearance are also modifiable by attributes or CSS.
* **Definition lists** contain sets of terms and their definitions. The list here  might be considered an Unordered definition list, but I didn't write it with HTML. *Definition Lists* are created using the tags `<dl></dl>` and utilize two elements to separate the term to be defined (`<dt></dt>`) and the definition itself. (`<dd></dd>`)

All of these lists are indented by the browser, and multiple lists can be nested into one another.

##  What is the basic structure of an element used to link to another website?

Useres can click anything between the `<a></a>` tags, and you specify that you're traveling to another page by using the href attribute. So: `<a href="http://www.yourmom.com">You can title the link here</a>`. In other words, your opening tag contains the clickable element `<a>` with the href attribute, and before the closing tag you have your link text. When leaving the site you should include the **absolute url** (http://www.) in the href attribute.

##  What attribute should you include in a link to open a new tab when the link is clicked?

The **target** attribute will open links in a new window, and I believe the user sets their browser to use tabs or windows for this sort of link by default. the target's value will open a new tab when it `=_blank`

##  How do you link to a specific part of the same page?

First you have to create points in the page where you will jump to. To do this, you apply an **id attribute** (to any HTML element). For example, you may create a header that looks like `<h4 id="skip the introduction">The Meat of the Story</h4>`
Using the `<a>` element with a href attribute, you can link to that point in the document with the id's value following a `#`. So our example might be linked to with `<a href="#skip the introduction">Spoilers ahead</a>`.

##  What is the purpose of CSS?
CSS determines the aesthetic of a webpage. It controls things like font, color, size, etc.

##  What does CSS stand for? What does cascading mean in this case?

Cascading Style Sheets. Cascading means that there is an order of importance when different rules deal with the same **elements**. The last rule will be used before the preceding rules should they conflict, for instance. Or if *selectors* are more specific they will take precedence. We are able to choose which rules should be expressed out of order by adding `!important` after the *value*

Furthermore, properties applied to one element will generally apply to their "child" elements as well. For instance, any headings or paragraphs within a body will inherit the styling of the body, unless signaled specifically to do otherwise.

##  What is the basic structure of a CSS rule?

They contain two parts, a **selector** and a **declaration**. The *selector* calls out all *elements* that should be affected by the *declaration*. So if you want to change paragraph elements, you use p. The declaration lives inside of curly brackets. They have a **properties** and **values** which are separated by colons. *Selectors* are case sensitive. You can specify several selectors at once, and several properties at once. CSS looks like this:

`p, h1{
    font-size: 24px;
    font-color: blue;}`
or

`selector{
  property: value;
  }`

##  How do you link a CSS stylesheet to your HTML document?

CSS files can be linked to within the HTML files, or placed inside of HTML pages.
To link them you use the following **syntax**
`<link href="css/example.css" type="text/css" rel="stylesheet" />`

(internal to an HTML file, you call on CSS using a `<style>` element with a *type* attribute whose value is "text/css")

##  When is it useful to use external stylesheets as opposed to using internal CSS?

External stylesheets can be used to modify more than one page at a time. HTML pages can also use more than one style sheet.
Each stylesheet can serve specific purposes, where one might determine layout while another handles color.

##  Describe what a color hex code is.

Hex codes are 6 digit codes preceded by a # which specify the amount of red, green, and blue in a color.

##  What are the three parts of an HSL color property?

Hue is what we generally think of as color, and can be displayed in a color wheel. Saturation is the amount of color in a color. As you decrease saturation, the object's color fades into black & white. Lightness is the amount of white or black in a color, and can make colors lighter or darker.

##  In the world of typeface, what are the three main categories of fonts? What are the differences between them?

* **serif** has flair at the end of it's lines.
* **sans-serif** the letters have straight ends, and no flair.
* **monospace** every letter has the same width.

##  When specifiying font-size, what are the main three units used?

Pixels, percentages (of the default text sixe, 16px), and ems (ems are equivalent to the width of a letter m.)
