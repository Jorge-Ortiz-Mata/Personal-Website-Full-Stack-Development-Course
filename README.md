
# Full-Stack Development Course.

The full-stack development course consists in how to learn several web technologies using different programming languages.
You will learn HTML, CSS, Javascript, NodeJS, React, Databases and so much more. This is a complete course that I recommend
in order to improve your programming skills.

## HTML.

### Elements

* h1 => Heading of HTML
* center => Center the content.
* div => Section a content.
* p => Paraph.

* ul => Create an unordered list.
* ol => Create an ordered list.
* li => List's item.
* br => Make a break line.
* hr => Show a line.

* img => Implement an image.

* a => Linking to other pages.

* table => Create a table.
* thead => Header's table.
* tbody => Header's body.
* tr => Row's table.
* td => Cells.

* form => Create a form.
* label => Field's description.
* input => Form's input (text, password, color, checkbox, submit, file, date, radio, range, email).
* textarea => Big input field.

* span => It's used in order to set an specific style in a parraph. 

## CSS.

### Rules. 

Note: If you try to set CSS attributes, CSS inline is take it as priority, after the internal CSS and last, external CSS

### Attributes.

* background-color => Change the background color.
* color => Change the font color.
* border => Draw a border of an item.
* border-radius => It sets the element's radius.
* border-style => Change the border type.
* width => Change the width of an element.
* height => Change the height of an element.

### Classes.

Classes are used to identify elements from a HTML file. Using classes, you can set the same class for many other elements.

* They are declared: `class="name-class"`.
* Inside stylesheet file: `.name-class{ attribute }`

### ID's.

An ID is very similar to classes. You can use ID's in order to identify elements but, insetead of classes, you can use them one for each element.

* They are declared: `id="name-id"`.
* Inside stylesheet file: `#name-id{ attribute }`.

### Positions and Coordinates.

You can use positions and coordinates in order to place objects in the HTML file.

#### Positions

* Static: It's the default position of an element.
* Relative: Where the element takes place, that is its origin.
* Absolute: The origin of an element is set at the beginning of the parent element.
* Fixed: It fixes an element in the webpage.

#### Coordinates.

* top.
* left.
* right.
* bottom.

### Display.

There are many options using display. They're used  in order to place the items better. 
If you want to use it, see this example:

* index.html

```
<div class="father-box">
    <span class="box">Ruby on Rails.</span>
    <span class="box">Ruby.</span>
    <span class="box">PostgreSQL.</span>
    <span class="box">MySQL.</span>
    <span class="box">Javascript</span>
    <span class="box">HTML.</span>
    <span class="box">React.</span>
</div>
```

* style.css

```
.box{
    display: inline-block;
    border: 2px solid #ff0000;
}
```

* Inline: It places the elements inline.
* Block: It places the elements line by line.
* Inline-block: It's a comnbination between inline and block.

## More information.

In the sections below, you'll find more information used in this project.

### Emojipedia.

Visit to emojipedia in order to get emojis from different kind of styles. Yo can visit: https://emojipedia.org/

### Favicon.

In order to create a pixel icon, you can visit https://favicon.cc 
Once you create your own icon, you have to download and save it into the project. For example:

* `<link rel="icon" href="../assets/media/favicon.ico">`.

### Colorhunt.

Colorhunt provides Hex-Colors for your webiste. It gives you some examples of which color you can use. You can visit: https://colorhunt.co/
