## HTML and CSS Assessment

#### Q1. What is the purpose of the `<track>` tag, and when should it be used?

- [ ] The `<track>` tag is used for specifying subtitles. It is typically applied as a child of the `<audio>` and `<video>` tags.
- [ ] The `<track>` tag is used for specifying subtitles. It is typically applied as a child of the `<video>` tag.
- [ ] The `<track>` tag is used for specifying subtitles, captions, and other types of time-based text. It is typically applied as a child of the `<video>` tag.
- [x] The `<track>` tag is used for specifying subtitles, captions, and other types of time-based text. It is typically applied as a child of the `<audio>` and `<video>` tag.

#### Q2. What are the best examples of void elements?

- [ ] `<link><meta><title>`
- [x] `<wbr><base><source>`
- [ ] `<input><br><p>`
- [ ] `<area><embed><strong>`

#### Q3. In HTML5, which tag or tags embed a webpage inside of a webpage?

- [ ] `<iframe>, <frame>, and <frameset>`
- [ ] `<frame>`
- [x] `<iframe>`
- [ ] `<frame> and <frameset>`

#### Q4. Where do `<header>` and `<footer>` tags typically occur?

- [ ] as children of `<body>, <article>, <aside>, and <section>` tags
- [x] as children of `<body>, <article>, and <section>` tags
- [ ] as children of `<body>, <article>, <aside>, <nav>, and <section>` tags
- [ ] as children of `<body>, <article>, <table>, and <section>` tags

#### Q5. What's the best way to apply bold styling to text?

- [x] `<strong>`
- [ ] Use CSS.
- [ ] `<bold>`
- [ ] `<b>`

#### Q6. When is the <link> tag used?

- [ ] when linking style sheets, JavaScript, and icons for mobile apps
- [ ] when linking style sheets, favicons, and preloading assets
- [x] when linking style sheets and favicons
- [ ] when linking style sheets, external URLs, and favicons

#### Q7. The "value" attribute is associated with which set of tags?

- [ ] `<button><input><form>`
- [ ] `<input><label><meter>`
- [ ] `<input><option><textarea>`
- [x] `<li><input><option>`
  
#### Q8. What should fill the two blanks in the HTML code below?

```css
<address ______  _____>
    <span itemprop="streetAddress">
    6410 Via Real
    </span><br>
    <span itemprop="addressLocality">Carpinteria</span>,
    <span itemprop="addressRegion">CA</span>
    <span itemprop="addressCode">93013</span>
</address>
```

- [x]  `itemscope` `itemtype="http://schema.org/PostalAddress"`
  
- [ ]  `itemsref="http://schema.org/PostalAddress"` `itemid="address"`
  
- [ ]  `itemscope` `itemref="http://schema.org/PostalAddress"`
  
- [ ]  `itemid="address"` `itemtype="http://schema.org/PostalAddress"`

#### Q9. When should you use the `<aside>` element?

- [x] when the content can be removed without detracting from the page's message
- [ ] for anything you want to move to the side, like a pull quote box, a sidebar, or an image with text wrapping around it
- [ ] for anything in parentheses
- [ ] for anything in a sidebar

#### Q10. With which tags is the `<source>` element associated?
- [ ] `<svg>, <picture>, <audio>, and <video>`
- [x] `<picture>, <audio>, and <video>`
- [ ] It is iterchangeable with the src attribute, so any element which uses src may use <source..... 
- [ ] `<audio> and <video>`

#### Q11. What is NOT a valid attribute for the `<textarea>` element?

- [ ] readonly
- [x] max
- [ ] form 
- [ ] spellcheck

#### Q12. What is the best way to code the sample shown?
![Sample](https://i.ibb.co/HVwStTZ/sample.png)

- 
```
<details>
   <summary>Parmesan Deviled Eggs</summary>
   <p>These delectable little bites are made with organic eggs, fresh Parmesan, and chopped pine nuts. </p>
</details>
```

- 
```
<h4>▸ Parmesan Deviled Eggs</h4>
<p>These delectable little bites are made with organic eggs, fresh Parmesan, and chopped pine nuts. </p>
```

- 
```
<details open>
   <summary>Parmesan Deviled Eggs</summary>
   <p>These delectable little bites are made with organic eggs, fresh Parmesan, and chopped pine nuts. </p>
</details>
```
^^ CORRECT ^^

- 
```
<details>
	<h4>▸ Parmesan Deviled Eggs</h4>
	<p>These delectable little bites are made with organic eggs, fresh Parmesan, and chopped pine nuts. </p>
</details>	
```


#### Q13. What is the purpose of the `<samp>` element?

- [ ] It connects the web browser to a SA-MP server
- [ ] It identifies enclosed text as a sampler or an example.
- [x] It identifies sample output from a computer program.
- [ ] It uses a simple application messaging protocol to connect the browser to a texting device.

#### Q14. When should you use `<ol>` and `<ul>` elements?

- [x] Use `<ul>` when you want a bulleted list and `<ol>` when you want a numbered list.
- [ ] Use `<ul>` when you have a list of items in which the order of the items matters. Use `<ol>` when you have a list of items that
could go in any order.
- [ ] Use `<ol>` when you want a bulleted list and `<ul>` when you want a numbered list.
- [ ] Use `<ol>` when you have a list of items in which the order of the items matters.

#### Q15. What is the difference between the post and get methods in a form?

- [ ] post is used for sending information to the server. get is used for retrieving form information from the server.
- [ ] get is used for sending information to the server. post is used for retrieving form information from the server.
- [ ] With get, data is included in the form body when send to the server. With post, the data goes through the URL
- [x] With post, data is included in the form body when send to the server. With get, the data goes through the URL

#### Q16. What is the difference between the `<div>` and `<span>` tags?

- [x] <div> is used where a generic block-level tag is needed, while <span> is used where a generic inline tag is needed.
- [ ] <div> is used for major divisions on a page, while <span> is used to span across columns.
- [ ] <div> is the industry-standard default tag, but you could use <span> if you prefer.
- [ ] <div> is used where a generic inline tag is needed, , while <span> is usedwhere a generic block-level tag is needed
  
#### Q17. What should fill the blank in the HTML code bellow?

```
<form method="post" action="mailto:info@linkedin.com" ____="text/plain" >
```
- [x] enctype
- [ ] media
- [ ] type
- [ ] rel

#### Q18. What is the correct markup for tha alt attribute of an image?

-  
```
js
  <img src="cubism.jpg"
   alt="Version of ""Whistler's Mother"" in cubist style">
```  
-  
```
js
  <img src="cubism.jpg"
    alt="Version of "Whistler's Mother" in cubist style">
``` 
-  
```
js
   <img src="cubism.jpg"
     alt='Version of "Whistler\'s Mother" in cubist style'> 
``` 
^^ CORRECT (NOT SURE) ^^

- 
```
js
   <img src="cubism.jpg"
     alt="Version of  \"Whistler's Mother\" in cubist style">
```
  
#### Q19. In the code below, what is the purpose of the id attribute?

```js
<p id="warnig" >Be careful when installing this product.</p>
```

- [x] It establishes that id is a unique identifier in the document, used for styling CSS, scripting, and linking within a webpage.
- [ ] It establishes that id is a unique identifier in the document, used for styling CSS and with Javascript code.
- [ ] It establishes that id may be used for styling CSS several times per page.
- [ ] It establishes that id is a unique identifier in the website, used for styling CSS, scripting, and linking within a webpage.

#### Q20. What is the best semantic markup for the sentence shown?

```markdown
On July 21, 1969, Neil Armstrong said, "One small step for man, one giant leap for mankind."
```

- [x] `<p> On <time datetime="1969-07-21">July 21, 1969</time>, Neil Armstrong said, <q cite="https://www.hq.nasa.gov/alsj/a11l/a11.html">One small step for man, one giant leap for mankind.</q>`
- [ ] `<p> On July 21, 1969, Neil Armstrong said, <q cite="https://www.hq.nasa.gov/alsj/a11l/a11.html">One small step for man, one giant leap for mankind.</q>`
- [ ] `<p> On July 21, 1969, Neil Armstrong said, <q>One small step for man, one giant leap for mankind.</q>`
- [ ] `<p> On <time datetime="07-21-1969">July 21, 1969</time>, Neil Armstrong said, <q cite="https://www.hq.nasa.gov/alsj/a11l/a11.html">One small step for man, one giant leap for mankind.</q>`
  
#### Q21. What should fill the blank in the HTML code below?

```
<a href="https://es.yahoo.com/" hreflang="____" target="_blank">Visita Yahoo</a>
```

- [ ] es
- [ ] es-spanish
- [x] es-es
- [ ] spanish

#### Q22. Review the text in the red box in the image shown. What is the best way to code this in HTML
![Image of  footer](https://i.imgur.com/WaKvL9d.png)

- [ ] ordered list
- [x] unordered list inside a nav element
- [ ] ordered list inside a nav eleme
- [ ] unordered list

#### Q23. What is the best way to code three choices within a form so that the user can select only one item?

- [ ]
```
<label for="example">Make a choice:</label>
<datalist id="example">
	<option value="Choice 1">
	<option value="Choice 2">
	<option value="Choice 3">
</datalist>
```

- [ ]
```
<p>Make a choice:</p>
<input id="choices" name="example" />

<datalist value="choices">
	<option value="Choice 1">
	<option value="Choice 2">
	<option value="Choice 3">
</datalist>
```

- [ ]
```
<label for="example">Make a choice:</label>
<input list="example" id="choices" name="choices" />

<datalist id="choices">
	<option value="Choice 1"> Choice 1</option>
	<option value="Choice 2"> Choice 2</option>
	<option value="Choice 3"> Choice 3</option>
</datalist>
```

-  [x]
```
<label for="example">Make a choice:</label>
<input list="choices" id="example" name="example" />

<datalist id="choices">
	<option value="Choice 1">
	<option value="Choice 2">
	<option value="Choice 3">
</datalist>
```


#### Q24. How do you confirm that a document is written in HTML5?

- [ ] The server wraps the webpage in an HTML5 wrapper.
- [x] Use the "<!DOCTYPE html>" declaration that starts the document.
- [ ] The browser receives encoding from the server to display the document with HTML5.
- [ ] It is enclosed in a "<html>" tag.

#### Q25. What does the code shown below accomplish?

```
<picture>
	<source srcset="image1.jpg" media="(min-width: 1000px)">
	<source srcset="image2.jpg" media="(min-width: 750px)">
	<img src="image3.jpg" />
</picture>
```
	
- [ ] It displays image1.jpg at 1000px and higher, image2.jpg at 750-999px, and image3.jpg at 749px and lower.
- [ ] It displays image1.jps at 1000px and higher and image2.jpg at 750-999px, image3.jpg is a default in case `<picture>` is not supported.
- [x] It displays image1.jpg at 1000px and higher and image2.jpg at 750px and higher, image3.jpg is a default in case `<picture>` is not supported.
- [ ] It displays image1.jpg, image2.jpg and image3.jpg at 1000px and higher.
  
#### Q26. What code will produce the table shown below?

- [ ]
```
<table>
	<scope cols="2" style="background-color: yellow">
	<tr>
		<th>Col 1</th>
		<th>Col 2</th>
		<th>Col 3</th>
	</tr>
	<tr>
		<td>first</td>
		<td>second</td>
		<td>third</td>
	</tr>
</table>
```

- [x]
```
<table>
	<colgroup span="2" style="background-color: yellow">
	<tr>
		<th>Col 1</th>
		<th>Col 2</th>
		<th>Col 3</th>
	</tr>
	<tr>
		<td>first</td>
		<td>second</td>
		<td>third</td>
	</tr>
</table>
```


- [ ]
```
<table>
	<group cols="2" style="background-color: yellow">
	<tr scope="row">
		<th>Col 1</th>
		<th>Col 2</th>
		<th>Col 3</th>
	</tr>
	<tr scope="row">
		<td>first</td>
		<td>second</td>
		<td>third</td>
	</tr>
</table>
```

- [ ]
```
<table>
	<columns colspqn="2" style="background-color: yellow">
	<tr>
		<th>Col 1</th>
		<th>Col 2</th>
		<th>Col 3</th>
	</tr>
	<tr>
		<td>first</td>
		<td>second</td>
		<td>third</td>
	</tr>
</table>
```

#### Q27. What is the `<hr>`tag typically used for?

- [ ] This tag is depreciated and should not be used.
- [x] It designates a topic shift within a section at the paragraph level.
- [ ] It draws a horizontal line.
- [ ] It designates a shift of topic at the section level.

#### Q28. What should fill the two blanks in the HTML code below?

```
<section itemscope itemtype="http://schema.org/Restaurant">
	<h1 itemprop="name">Nadia's Garden</h1>
	<p itemscope ______ ______>
		<span itemprop="ratingValue">4.5</span> reviews
	</p>
</section>
```

- [ ] `itemprop="aggregateRating" itemref="http://schema.org/AggregateRating"`
- [x] `itemprop="aggregateRating" itemtype="http://schema.org/AggregateRating`
- [ ] `itemid="aggregateRating" itemtype="http://schema.org/AggregateRating`
- [ ] `itemid="aggregateRating" itemref="http://schema.org/AggregateRating`

#### Q29. Which HTML snippet links back to the very top of a webpage?

- [x]
```
<a id="top"></a> <!-- placed at the top of the page -->  
<a href="#top">back to top</a>
```


- [ ]
```<a name="top"></a> <!-- placed at the top of the page -->  
<a href="#top">back to top</a>
```

- [ ]
```
<a href="#">back to top</a>  
<a href="#top">back to top</a>
```

- [ ]
```
<button href="#">back to top</button>  
<button href="#top">back to top</button>
```

#### Q30. Which three tags where deprecated in HTML4 but returned to HTML5?

- [x] ` <rb> <rp> <rt>`

- [ ] `<acronym> <code> <wbr>`

- [ ] `<hgroup> <q> <wbr>`

- [ ] `<b><i><u>`

#### Q31. The "______"tag is used for marking up a short code snippet, while the ______ tag is used for marking up a longer block of code.

- [ ] `"<kdb>"; <pre>`

- [ ] `"<pre>"; <code>`

- [ ] `"<kdb>";<mark>`

- [x] `"<code>";<pre>`


#### Q32. What does the `<label>` tag do?

- [ ] It labels webpages with important information.
- [ ] It visually associates a text label with an interface element.
- [ ] It visually labels from fields.
- [x] It programmatically associates a text label with an interface element.

#### Q33. To get a link to open in a new window or tab, use the ______ attribute.

- [x] _blank
- [ ] _self
- [ ] _new
- [ ] _parent


CSS Assessment
--------------

#### Q1. In the following example, which selector has the highest specificity ranking for selecting the anchor link element?
```css
ul li a 
a 
.examole a 
div a
```
- [ ] .example a  <<<<---Correct
- [ ] div a 
- [ ] a
- [ ] ul li a

#### Q2. Using an attribute selector, how would you select an `<a>` element with a "title" attribute?
- [ ] a[title]{...}    <<<<---Correct
- [ ] a > title {...}
- [ ] a.title {...}
- [ ] a=title {...}

#### Q3. CSS grid and flexbox are now becoming a more popular way to create page layouts. However, floats are still commonly used, especially when working with an older code base, or it you need to support older browser version. What are two valid techniques used to clear floats?
- [ ] Use the "clearfix hack" on the floated element and add a float to the parent element.
- [ ] Use the overflow property on the floated element or the "clearfix hack" on either the floated or parent element.
- [ ] Use the "clearfix hack" on the floated element or the overflow property on the parent element.
- [ ] Use the "clearfix hack" on the parent element or use the overflow property with a value other than "visible."     <<<<---Correct

#### Q4. What element(s) do the following selectors match to?
`1) .nav {...}`
`2) nav {...}`
`3) #nav {...}`

- 
```
1) An element with an ID of "nav"
2) A nav element
3) An element with a class of "nav"
```
- 
```
They all target the same nav element.
```
- 
```
1) An element with an class of "nav"     <<<<---Correct
2) A nav element
3) An element with a id of "nav"
```
- 
```
1) An element with an class of "nav"
2) A nav element
3) An div with a id of "nav"
```

#### Q5. When adding transparency styles, what is the difference between using the opacity property versus the background property with an `rgba()` value?
-  [ ] Opacity specifies the level of transparency of the child elements. Background with an `rgba()` value applies transparency to the background color only.
-  [ ] Opacity applies transparency to the background color only. Background with an `rgba()` value specifies the level of transparency of an element, as a whole, including its content. 
-  [ ] Opacity specifies the level of transparency of an element, including its content. Background with an `rgba()` value applies transparency to the background color only.  <<<<---Correct
-  [ ] Opacity applies transparency to the parent and child elements. Background with an `rgba()` value specifies the level of transparency of the parent element only.

#### Q6. What is true of block and inline elements?
-  [ ] By default, block elements are the same height and width as the content container between their tags; inline elements span the entire width of its container.
-  [ ] By default, block elements span the entire width of its container; inline elements are the same height and width as the content contained between their tags.
-  [ ] A "<nav>" element is an example of an inline element. "<header>" is an example of a block element.  <<<<---Correct
-  [ ] A "<span>" is an example of a block element. "<div>" is an example of an inline element.

#### Q7. CSS grid introduced a new lenght unit, fr, to create flexible grid tracks. Referring to the code sample below, what will the widths of the three columns be?
```css
.grid {
    display: grid;
    width: 500px;
    grid-template-columns: 50px 1fr 2fr;
}
```
-  [ ] The first column will have a width of 50px. The second column will be 50px wide and the third column will be 100px wide.
-  [ ] The first column will have a width of 50px. The second column will be 150px wide and the third column will be 300px wide.  <<<<---Correct
-  [ ] The first column will have a width of 50px. The second column will be 300px wide and the third column will be 150px wide.
-  [ ] The first column will have a width of 50px. The second column will be 500px wide and the third column will be 1000px wide.

#### Q8. What is the line-height property primarily used for?
-  [ ] to control the height of the space between two lines of content      <<<<---Correct
-  [ ] to control the height of the space between heading elements
-  [ ] to control the height of the character size
-  [ ] to control the width of the space between characters

#### Q9. Three of these choices are true about class selectors. Which is NOT true?
-  [ ] Multiple classes can be used within the same element.
-  [ ] The same class can be used multiple times per page.
-  [ ] Class selectors with a leading period
-  [ ] Classes can be used multiple times per page but not within the same element.  <<<<---Correct


#### Q10. There are many properties that can be used to align elements and create page layouts such as float, position, flexbox and grid. Of these four properties, which one should be used to align a global navigation bar which stays fixed at the top of the page?
-  [ ] position   <<<<---Correct
-  [ ] flexbox
-  [ ] grid
-  [ ] float

#### Q11. In the shorthand example below, which individual background properties are represented?
`background: blue url(image.jpg) no-repeat scroll 0px 0px;`

-
```
background-color: blue;                          <<<<---Correct
background-image: url(image.jpg);
background-repeat: no-repeat;
background-attachment: scroll;
background-position: 0px 0px;
```
-
```
background-color: blue;
background-img: url(image.jpg);
background-position: no-repeat;
background-scroll: scroll;
background-size: 0px 0px;
```
-
```
background-color: blue;
background-src: url(image.jpg);
background-repeat: no-repeat;
background-wrap: scroll;
background-position: 0px 0px;
```
-
```
background-color: blue;
background-src: url(image.jpg);
background-repeat: no-repeat;
background-scroll: scroll;
background-position: 0px 0px;
```

#### Q12. In the following example, according to cascading and specificity rules, what color will the link be?
```
.example {color: yellow;}
ul li a {color:  blue;}
ul a {color: green;}
a {color: red;}
<ul>
    <li><a href="#" class="example">link</a></li>
    <li>list item</li>
    <li>list item</li>
</ul>
```

-  [ ] green
-  [ ] yellow  <<<<---Correct
-  [ ] blue
-  [ ] red

#### Q13. When elements overlap, they are ordered on the z-axis (i.e., which element covers another). The z-index property can be used to specify the z-order of overlapping elements. Which set of statements about the z-index property are ture?
-  [ ] Larger z-index values appear on top of elements with a lower z-index value. Negative and positive numbers can be used. z-index can only be used on positioned elements.     <<<<---Correct
-  [ ] Smaller z-index values appear on top of elements with a larger z-index value. Negative and positive numbers can be used. z-index must also be used with positioned elements.
-  [ ] Larger z-index values appear on top of elements with a lower z-index value. Only positive numbers can be used. z-index must also be used with positioned elements.
-  [ ] Smaller z-index values appear on top of elements with a larger z-index value. Negative and positive numbers can be used. z-index can be used with or without positioned elements.

#### Q14. What is the difference between the following line-height settings?
```css
line-height: 20px
line-height: 2
```
-  [ ] The value of 20px will set the line-height to 20px. The value of 2 will set the line-height to twice the size of the corresponding font-size value.   <<<<---Correct
-  [ ] The value of 20px will set the line-height to 20px. The value of 2 is not valid.
-  [ ] The value of 20px will set the line-height to 20px. The value of 2 will default to a value of 2px.
-  [ ] The value of 20px will set the line-height to 20px. The value of 2 will set the line-height to 20% of the corresponding font-size value.

#### Q15. In the following example, what color will paragraph one and paragraph two be?
```javascript
<section>
    <p>paragraph one</p>
</section>

<p>paragraph two</p>

section p{
    color: red;
}
section + p {
    color: blue;
}
```
-  [ ] Paragraph one will be blue, paragraph two will be red.
-  [ ] Both paragraphs will be blue.
-  [ ] Paragraphs one will be red, paragraph two will be blue.  <<<<---Correct
-  [ ] Both paragraphs will be red.

#### Q16.What are three valid ways of adding CSS to an HTML page?
-
```
1. External; CSS is written in a separate file.
2. Inline; CSS is added to the <head> of the HTML page.
3. Internal; CSS is included within the HTML tags.
```
-
```
1. External; CSS is written in a separate file and is linked within the <header> element of the HTIML  file . 
2. Inline; CSS is added to the HTML tag.
3. Internal; CSS is included within the <header> element of the HTML  file.
```
-
```
1. External; CSS is written in a separate file and is linked within the <head> element of the HTML file . 
2. Internal; CSS is included within the <header> element of the HTML file.
3. Inline; CSS is added to the HTML tag.
```
-
```
1. External; CSS is written in a separate file and is linked within the <head> element of the HTML file .
2. Inline; CSS is added to the HTML tag.
3. Internal; CSS is included within the <head> element of the HTML file.
```
#### Q17. Which of the following is true of the SVG image format?
-  [ ] CSS can be applied to SVGs but JavaScript cannot be.
-  [ ] SVGs work best for creating 3D graphics.
-  [ ] SVGs can be created as a vector graphic or coded using SVG specific elements such as <svg>, <line>, and <ellipse>.  <<<<---Correct
-  [ ] SVGs are a HAML-based markup language for creating vector graphics.


#### Q18.In the example below, when will the color pink be applied to the anchor element?   
    a:active { 
        color: pink;
    }
    
- [ ] The color of the link will display as pink after its been clicked or if the mouse is hovering over the link.
- [ ] The color of the link will display as pink on mouse hover.
- [x] The color of the link will display as pink while the link is being clicked but before the mouse click is released.  
- [ ] The color of the link will display as pink before it has been clicked.

#### Q19. To change the color of an SVG using CSS, which property is used?
- [ ] Use background-fill to set the color inside the object and stroke or border to set the color of the border. 
- [ ] The color cannot be changed with CSS.
- [ ] Use fill or background to set the color inside the object and stroke to set the color of the border.
- [ ] Use fill to se t the color inside the object and stroke to set the color of the border.  <<<<---Correct

#### Q20. When using position: fixed, what will the element always be positioned relative to?
- [ ] the closest element with position: relative
- [ ] the viewport <<<<---Correct
- [ ] the parent element
- [ ] the wrapper element

#### Q21. By default, a background image will repeat ________
- [ ] only if the background-repeat property is set to repeat
- [ ] indefinitely, vertically, and horizontally  <<<<---Correct
- [ ] indefinitely on the horizontal axis only 
- [ ] once, on the x and y axis

#### Q22. When using media queries, media types are used to target a device category. Which choice lists current valid media types?
- [ ] print, screen, aural <<<<---Correct
- [ ] print, screen, television
- [ ] print, screen, speech 
- [ ] print, speech, device 

#### Q23. How would you make the first letter of every paragraph on the page red?
- [x] p::first-letter { color: red; }  
- [ ] p:first-letter { color: red; }
- [ ] first-letter::p { color: red; }
- [ ] first-letter:p { color: red; }

#### Q24.In this example, what is the selector, property, and value?
```css
p {
color: #000000;
}
```
-
``` 
"p" is the selector
"#000000" is the property 
"color" is the value
```
-
```
"p" is the selector      <<<<---Correct
"color" is the property 
"#000000" is the value
```
-
```
"color" is the selector
"#000000" is the property 
"#p" is the value
```
-
```
"color" is the selector
"p" is the property 
"#000000" is the value
```

#### Q25. What is the rem unit based on?
- [ ] The rem unit is relative to the font-size of the p element.
- [ ] You have to set the value for the rem unit by writing a declaration such as rem { font-size: 1 Spx; }
- [ ] The rem unit is relative to the font-size of the containing (parent) element.
- [ ] The rem unit is relative to the font-size of the root element of the page. <<<<---Correct

#### Q26.Which of these would give a block element rounded corners?
- [ ] corner-curve: 10px
- [ ] border-corner: 10px
- [ ] border-radius: 10px  <<<<---Correct
- [ ] corner-radius: 10px
 
#### Q27. In the following media query example, what conditions are being targeted?

`@media (min-width: 1024px), screen and (orientation: landscape) { … }`

- [ ] The rule will apply to a device that has either a width of 1024px or wider, or is a screen device in landscape mode.
- [ ] The rule will apply to a device that has a width of 1024px or narrower and is a screen device in landscape mode.
- [ ] The rule will apply to a device that has a width of 1024px or wider and is a screen device in landscape mode. <<<<---Correct
- [ ] The rule will apply to a device that has a width of 1024px or narrower, or is a screen device in landscape mode.
 
#### Q28. CSS transform properties are used to change the shape and position of the selected objects. The transform-origin property specifies the location of the element's transformation origin. By default, what is the location of the origin?
 
- [ ] the top left corner of the element
- [ ] the center of the element  <<<<---Correct
- [ ] the top right corner of the element
- [ ] the bottom left of the element

#### Q29. Which of the following is not a valid color value?
- [ ] color: #000
- [ ] color: rgb(0,0,0)
- [ ] color: #000000
- [ ] color: 000000 <<<<---Correct

#### Q30. What is the vertical gap between the two elements below?
```css
<div style="margin-bottom: 2rem;">Div 1</div>
<div style="margin-top: 2rem;">Div 2</div>
```
- [ ] 2rem
- [ ] 32px
- [ ] 64px
- [ ] 4rem <<<<---Correct

#### Q31. When using the Flexbox method, what property and value is used to display flex items in a column?
- [ ] flex-flow: column; or flex-direction: column <<<<---Correct
- [ ] flex-flow: column;
- [ ] flex-column: auto;
- [ ] flex-direction: column;

#### Q32. Which type of declaration will take precedence?
- [ ] any declarations in user-agent stylesheets <<<<---Correct
- [ ] important declarations in user stylesheets
- [ ] normal declarations in author stylesheets
- [ ] important declarations in author stylesheets

#### Q33. The flex-direction property is used to specify the direction that flex items are displayed. What are the values used to specify the direction of the items in the folowing examples?
- [x] Example 1: flex-direction: row;
Example 2; flex-direction: row-reverse;
Example 3: flex-direction: column;
Example 4: flex-direction: column-reverse;   
- [ ] Example 1: flex-direction: row-reverse;
Example 2; flex-direction: row;
Example 3: flex-direction: column-reverse;
Example 4: flex-direction: column;
- [ ] Example 1: flex-direction: row;
Example 2; flex-direction: row-reverse;
Example 3: flex-direction: column;
Example 4: flex-direction: reverse-column;
- [ ] Example 1: flex-direction: column;
Example 2; flex-direction: column-reverse;
Example 3: flex-direction: row;
Example 4: flex-direction: row-reverse;

#### Q34. There are two sibling combinators that can be used to select elements contained within the same parent element; the general sibling combinator (~) and the adjacent sibling combinator (+). Referring to esample below, which elements will the styles be applied to?
```css
h2 ~ p {
    color: blue;
}
h2 + p {
    background: beige;
}
```
```html
<section>
    <p>paragraph 1</p>
    <h2>Heading</h2>
    <p>paragraph 2</p>
    <p>paragraph 3</p>
</section>
```
- [ ] Paragraphs 2 and 3 will be blue. The h2 and paragraph 2 will have a beige background.
- [x] Paragraphs 1, 2, and 3 will be blue, and paragraph 2 will have a beige background.   <<<<---Correct
- [ ] Paragraphs 2 and 3 will be blue. Paragraph 2 will have a beige background.
- [ ] Paragraph 2 will be blue. Paragraphs 2 and 3 will have a beige background.

#### Q35. When using flexbox, the "justify-content" property can be used to distribute the space between the flex items along the main axis. Which value should be used to evenly distribute the flex items within the container shown below?
- [ ] justify-content: space-around;
- [ ] justify-content: center;
- [ ] justify-content: auto;
- [x] justify-content: space-between;   <<<<---Correct

#### Q36. There are many advantages to using icon fonts. What is one of those advantages?
- [ ] Icon fonts increase accessibility.
- [ ] Icon fonts can be used to replace custom fonts.
- [x] Icon fonts can be styled with typography related properties such as font-size and color. 
- [ ] Icon fonts are also web safe fonts.
 