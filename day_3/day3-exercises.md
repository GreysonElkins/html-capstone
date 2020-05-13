##  If you're using an input element in a form, what attribute controls the behavior of that input?
`<type>` is the attribute that controls the behavior of input elements. `="text"` will display the users input. `="password"` will mask the input. `="radio"` creates options for the user to select. `="checkbox"`is similar to radio, but it allows users to select and deselect one or more options. `="hidden"` creates a form control the page will not display.
##  What element is used to create a dropdown list?
`<select></select>` It contains two or more `<option></option>` elements which determines what the user will see.

##  If you're using an input element to send form data to a server, what should the `type` attribute be set to?
When sending input to a server, the `<form type="post"></form>`

##  What element is used to group similar form items together?

`<fieldset></fieldset>`will create a line around the edge of related information in most browsers. The `<legend></legend>` element can be used to identify the purpose of that group.

##  Describe the differences between border, margin, and padding.

Border margin and padding all are used to delineate between different elements, or boxes. Each element has a border, whether or not it's visible, but we can change it's appearance using CSS. The border is like the frame. Padding determines the distance between elements, while margin sets the distance between an element's border and it's content.

##  For a CSS rule `padding: 1px 2px 5px 10px`, what sides of the content box does each pixel value correspond to?

The top 1px, right 2px, bottom 5px, and left 10 px

##  Describe the difference between block-level and inline elements.

Block level elements display above and below each other. Inline elements sit next to each other like words in a sentence.

##  What is the role of fixed positioning, and why is z-index important in the scenario of using fixed positioning?

When you elements are outside of *normal flow* they can overlap. *z-positioning* allows us to control which element appears on-top. Elements with a *fixed position* are positioned in relation to the browser window instead of their parent element and do not affect the position of other objects (this means they do not move as the user scrolls) so they can disappear or appear behind other objects. The higher the z-indexes value, the closer to the front it will appear. 
