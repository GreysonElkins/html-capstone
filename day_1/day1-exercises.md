## On a website, what is the purpose of HTML code?

HTML determines the structure of content and pages. Whether font sizes, colors, the placement of text or images, HTML code tells web browsers how to display the information therein.

## What is the difference between an element and a tag?

Elements are specific HTML codes which live within brackets. Elements start and end with tags. If an element is books on a shelf the tags are the bookends on either sides of the book and they look like `<book>The Shining, by Stephen King</book>` The element communicates what is a "book" to the browser.

## Why do we use attributes in HTML elements?

Attributes imbue specific qualities to elements. They are inserted into the opening tag, and look like name="value".

## Describe the purpose of the head, title, and body HTML elements.

The body element contains what is shown in the browser. Above the body, the head contains information about the page - this can include the title. The title element can be used as a visual title within the head or the body, but it also determines the text that will appear in the tab, or at the top of the browser when viewing the page.


## In your browser (Chrome), how do you view the source of a website?

You can either inspect elements, (command + shift + c), or view the source code (command + shift + u). The former is much easier to look at; the source is displayed in a split pane and you can jump through it by hovering over elements of the main page.

## List five different HTML elements and what they are used for. For example, `<p></p>` is a paragraph element, and it is used to represent a paragraph of text.

`<sup></sup>` is a superscript element and it is used to make the text it contains appear as superscript.
`<br />` Is an element used to create line breaks in text. It does not contain text, and only uses one tag.
`<hr />` is used to create a horizontal line between paragraphs. Like `<br />`, it does not contain text and uses one tag.
`<b></b>` is a bold element, and it presents the text it contains as bold text.
`<i></i>` is an italic element, which displays the text it contains as italics.


## What are empty elements?

Empty elements are elements which usually require one tag, and as of yet seem to affect formatting of a page, but not the actual text around it.

## What is semantic markup?

Semantic markup is code that is used to convey specific information about content to the program presenting it. It may affect formatting, but is not used as a visual tool. The extra information it carries can communicate extra information with programs like screen readers and search engines.

## What are three new semantic elements introduced in HTML 5? Use page 431 in the book to find more about these new elements

`<article>,<aside>,<nav>,<footer>,<header>`

Headers and footers can appear at the top and bottom of every page, or individual pages.

A lot of these elements are based on the typical formatting of blog-style websites.

`<nav>` is for containing the primary site navigation. Some developers have been using it for the links at the bottom of the page (privacy policy, copyright, etc.) This is a developing practice which may not catch on.

`<aside>` can be used as part of a page, or an article. In articles, the `<aside>` element is for nonessential, but related information to the article. Outside of an article, it generally acts as a container for related information to the entire page.

https://codepen.io/greysonelkins/pen/gOpzdYg.html
