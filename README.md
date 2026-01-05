# Introduction to HTML: Starting on the Netflix Landing Page Clone

Learn HTML5, the language that creates the basic structure of websites. Every site begins with HTML. Nail down these basics ASAP to jump into the exciting world of web development.

## What is this project about
Working towards building the awesome Netflix platform (it will not be complete though). 

### The Building blocks of a web:
1. Welcome: 
- Learn by doing - gain interactive experience.
- Attempt challenges and push them to the repositories - follow Zaio tutor guidance.
- Learn Faster &  experience a deeper level of learning.

- what I did in this course following the guidance of the tutor:
 + I learnt how the Web works,
 + Coded like a real programmer (Using the right tools)
 + Structuring and organizing the files
 + The HTML Document
 + How to code the Netflix landing page with HTML, learning by doing.
 + Layouts elements
 + Important HTML elements like Headings, paragraphs, tables and etc. Many much more!

- I worked off the code pushed by Akhil and gaining a very interactive experience.

- By the end of the series 'Starting on the NetFlix Landing page clone' you should have built Netflix landing page barebones structure using only HTML and CSS.

#### **HTML**
- All content comes from HTML: Hyper Text Markup language. It's a Mark up language that computer can interprets and write on the Website.
- The HTML file, known as Entry point file is basically where each websites starts at.
- HTML is the basics, headings, paragraphs, etc.


1. **HTML vs CSS**

- How important are HTML vs CSS relatively.
- Websites cannot without CSS, it needs the styling functionality to be able to work 100%.
- 

2. How to use the interactive coding environment:

- Ashkil will be coding something in the interactive coding environment, pushing each time. I just have to pull into my VS code environment and make pushes each time.
- Practice n Practice, pull the changes and make your hands dirty everytime.

3. Let's get setup:

- Have google Chrome setup installed [x]
- Have VS Code setup installed [x]
- Have Live Server extension installed in VS Code [x]

4. **HTML Book Analogy**

- Tells the browser exactly what the content we are writing.
- Consists of:
 + Headings, Paragraphs,
 + Bold, italics fonts, using links to allow redirection or open other pages,
 + The NavBar at the top of the page, the footer,
 + The main content.
- We will be creating the netflix landing page: `https://www.netflix.com/za/`
- Basic Syntax:'Tags' - everything is wrapped in "tags" to tell the Browser what is what. Using opening tags & closing tags. All these together becomes an element. e.g.:
 + Heading == `<h1>Some heading text</h1>`, 
 + Paragraph == `<p>Some paragraph text</p>`,
 + Main section == `<main>Some Main section Content text</main>`
 + NavBar section == `<nav>Some navbar context(usual in divided sections)</nav>`
 + Div tags == `<div>Some divided contexts(for better arrangement of context in each sections)</div>`. ETC...
- Within each tags, we can have level of nesting either within other elements or outside elements.
- Tags: `<> </>`
- Opening tags: `<>`
- Closing tags: `</>`
- Everything from opening to closing tags is an element.
- Elements define our content in the Browser - `<p>` this is paragraph, `<h1>` this is heading, etc.

5. **File Naming Conventions & File organizing:** Stick to same consistance of these so that you follow good practices in the Web Development Industries.

- Sstick to lowercase for naming files,
- Make the names shorter,
- Have descriptive naming - `profile.html` not 'page1.html`, etc.
- Use underscores or hyphens instead of 2 words merged. e.g. `about-us.html`. No Capital letters like - `AboutUs.html`, wrong this one. No spaces.
- Main folder is the root folder.
- the `index.html` is normally what is used for the home or root file. Thus it's in the root folder, not sub folders.
- Can put pages into sub folders.
- Assets folders for images

6. File structure:
- We normally have the first thing at top of every HTML file document:

```
<!DOCTYPE html>
```
- Tells the browser we are using the HTML5 file
```
<html>
```
- tells the Browser that only the HTML is written in between these.
- kind of redundant, but it acts as the root of the Doc.

```
<head>
```
- Not visible to the Browser.
- Contains the Meta tags with essential informations.
- If you want to link to the style sheet file, you can add it through the head section using link tag, `<link>`
- Hidden but really important and controlling - like a brain:
 + ``<title>``
 + The title tag is within the head, it is the tab page heading/title.ss

```
<body>
```
- Where all the content goes, like headings, paragraphs, main sections, and etc.

7. **Headings & Paragraphs**

- Headings denote the hierarchy & page structure.
- Only have 6 levels of headings:
 + `<h1>, <h2>, <h3>, <h4>, <h5> & <h6> `

- Paragraphs are really simple opposed to headings.
- They are regular text we use
- use the tag: `<p>`
- Not numbered like headings, only the `<p>` tag.

8. **Strong vs Em**

```
<strong>
```
- Write **bold** text in the browser
- Strong importance - tells the browser that there's a really import text in this element between the tag `<strong></strong>`.
-  It is not advisable to use `<b></b>`, it does tell the Browser you are using a strong text. Good practice use `<strong>`

```
<em>
```
- Write *italic* text in the browser.
- Emphasis on the certain text in between `<em></em>`

9. **The Anchor element**

- `<a>` is short for anchor
- Used to link:
 + To link to a different location on the current page.
 + or to another page.

- E.g.:

```
<a>Sign in</a>
```

- **How will the browser know where to redirect when this element is clicked on?** We need to understand the elements' attributes.

9. Elements can have attributes:

- Are always given within the opening tag.
- Gives extra info:
 + Where link goes...
 + Or location of the image.

- Written as follows:
 + `<a href="https://www.netflix.com/ke-en/login">Sign In</a>`
 + Attributes are always follwed by an equal sign '=' and "" quotes marks containing info for the attribute.

- A link won't work without the **`href`** attribute.
- Also won't without the **`http://`** or **`https://`** if external:
 + This let's the browser know that the link is an external website.
 + This is also known as **Absolute Path**.
 + `<a href="https://www.netflix.com/ke-en/login">Sign In</a>`

- **Relative Path**: Like Absolute Path where we can specify the external website, we can also point to files in our project called Relative path.

10. **Relative Path**:

- Pointing to files in locally - in the project.
- Visit about us page:
 + `<a href="./about-us.html">About Us</a>`
 + `<img src="./assets/bgimage.png" alt="">`
 + Above is how to create an image - pointing to a local file i.e. **Relative Path** 
- Create a CONTACT US page, link it in the Home page pointing to Contact Us page - That's how you use **Relative Path**

11. Opening in a new tab: **Target attribute**:

- Use the `target="_blank"` attribute within the opening tag of the anchor tag <a> to open in a new tab.
 + `<a href="./about-us.html" target="_blank">About Us</a>`
- `https://www.w3schools.com/tags/att_a_target.asp`

12. Redirecting to a different part on the same page: Anchor tag - position on same page.

- Move cursor to a different element on the code editor.

- In the `<a>` href attribute use the `#` to point to an id of different element in order to move to that different element in the same editor.

- e.g.

```
<a href="#redirect_Section">POINT TO A DIFFERENT SECTION</a>
.
.
.
<h1 id="redirect_section">TEST 2 REDIRECTION SECTION</h1>
```

- You can always point to the different part on the same page using this anchor tag with `href="#"` and the added id of that element.


13. Add images to the HTML pages.
- Similar to `<a>` the image element requires an attribute to work, 
- It uses the `src` - short for source
- Image tag is self-closing tag.
 + `<img src="./assets/bgimage.png" alt="">`

- File paths - can be relative or from online similar to `<a>`
 + Relative Path: `<img src="https://www.link.com" alt="">`
 + Absoluete Path: `<img src="./assets/bgimage.png" alt="">`

14. What does the alt attribute do? 
- Images are not valid without the `alt` attribute.
- `Alt` attribute is used to describe the image.
- `Alt` attribute describe the intent of the image:
 + Can be empty string
 + `<img src="./assets/bgimage.jpg" alt="Netflix Cover Image">`

15. Lists:

- What are lists 
 + Regular bulleted or numbered lists.
 + Navigations
 + Organizing other

- Types of lists:
+ Ordered lists `<ol>`
+ Unordered lists `<ul>`
- Each list has a list item:

```
<ol>
    <li></li>
    <li></li>
    <li></li>
</ol>
```

16. Div tags:
- Div stands for division.
- Used to Divide content into sections
-  The reason we might divide the content into section is so that we can style these divided content into different styling.

17. The Layout Elements:

- Header
- Nav
- Section:
 + Main: Article
 + Aside
- Footer
- We can actually give the direct meaning to our sections e.g. `<footer></footer>` to make the Browser understand that the page has footer element.
- 

18. HTML Form Element: Taking user data using input tags.
- Is used collect the user input.
- User input is most often sent to the server for a processing.
- `<form>` is used to create an HTML form for the user:
 + input
```
<form>
.
form elements
.
<form>
```

19. Form elements - A real world example: Login Form.
```
- <label>
- <select>
- <textarea>
```

- `<button type="button">Click Me!</button>`
- To create input for user, use the input tag: `<input type="text" id="username" name="username">`, there are many types you can give to your input tag, text, or passsword and etc. It depends what you wanna give it.
- We can always give our input a label, `<label for="username">Username</label>` this is just used for labelling your user input.
- E.g.: Real world example - Login Form.
```
    <form action="">
        <h1>LOGIN FORM</h1>
        <label for="username">Username</label>
        <input type="text" id="username" name="username"><br>
        <label for="password">Password</label>
        <input type="password" id="password" name="password"><br>
        <label for="gender">Female</label>
        <input type="radio" id="female" name="female" value="Female">
        <label for="gender">Male</label>
        <input type="radio" id="male" name="male" value="Male">
    <button>LOGIN</button>
    </form>
```
- You can add a newline(next line) using the following tag: `<br>`

20. Labels & Textarea:
**Label**
- For an input, you have to add the attribute name in case of radio type, so that they refer to the radio input, if one is selected the other is unselected.
e.g.:

```
    <form action="">
        <h1>LOGIN FORM</h1>
        <label for="username">Username</label>
        <input type="text" id="username" name="username"><br><br>
        <label for="password">Password</label>
        <input type="password" id="password" name="password"><br>
        <br>
        <input type="radio" id="Female" name="gender" value="female">
        <label for="female">Female</label><br>
        <input type="radio" id="Male" name="gender" value="male">
        <label for="female">Male</label><br>
        <input type="radio" id="Other" name="gender" value="other">
        <label for="other">other</label><br>
        <button>LOGIN</button>
    </form>
```
- For an input, you can add the different atttribute name in case of checkbox type, you can selected more than one different value of this input type - You can different options that is how checkbox are used.

```
    <form action="">
        <h1>LOGIN FORM</h1>
        <label for="username">Username</label>
        <input type="text" id="username" name="username"><br><br>
        <label for="password">Password</label>
        <input type="password" id="password" name="password"><br>
        <br>
        <input type="checkbox" id="Female" name="gender" value="female">
        <label for="female">Female</label><br>
        <input type="checkbox" id="Male" name="gender" value="male">
        <label for="female">Male</label><br>
        <input type="checkbox" id="Other" name="gender" value="other">
        <label for="other">other</label><br>
        <button>LOGIN</button>
    </form>
```
**Textarea**
- For description open text, you cannot use input tag, use the textarea tag - this you can add more text for description input that user needs to submit.

e.g:
```
    <form>
        <h1>LOGON FORM</h1>
        <label for="username">Username</label>
        <input type="text" id="username" name="username">
        <br>
        <label for="password">Password</label>
        <input type="password" id="password" name="password">
        <br>
        <label for="description">Description</label>
        <textarea name="description" id="description" cols="30" rows="10"></textarea>
        <button>LOGIN</button>
    </form>
```
**Select**
- For available values of inputs that user might want to select in the select area of the forms, you can use the `<select>` tag. Using this you can give the values to which the user can select.
- Inside the `<select>` you can give options as values that user can choose from. Use the option inside the `<select>`.
e.g.:
```
<form>
    <label for="Profile">Select Profile<label>
    <select name="profile" id="profile>
        <option value="Akhil">Akhil</option>
        <option value="Jane">Jane</option>
        <option value="Sam">Sam</option>
        <option value="Historia">Historia</option>
    </select>
</form>
```

21. Buttons element:
- the `<button>` defines a clickable button.
- Inside a `<button>` element you can put the text (And Tags like, `<i>`, `<strong>`, `<img>`, `<br>`, `<em>`). This is not possible with the button created with the `<input>` element.
+ `<button type="button">Click Me!</button>`
- The type=button, is there so that you can create an action, send data to the back end or perfom some sort of user interface change in order words it allows to create some sort of an event that can get triggered by some sort of an action

22. The Video Element:
- The `<video>` element is used to show the video on a web page.
e.g.:

```
    <video controls autoplay playsinline muted loop preload width="600" height="500">
        <source src="https://assets.nflxext.com/ffe/siteui/acquisition/ourStory/fuji/desktop/video-tv-in-0819.m4v"
                    type="video/mp4">
        <source src="https://www.w3schools.com/html/mov_bbb"
                    type="video/mp4">
    </video>
```

- The video tag comes with attributes:
+ `autoplay=`: when the page loads the video starts playing automatically.
+ `playsinline=`: It plaays inline with whatever element is there around it.
+ `muted=`: Video is going to be muted, no sounds is there
+ `loop=`: The video is going to play in a loop.

- You can give the source inside the `<source>` tag, where you will specify the source in it using the `src` attribute, where you can use either Relative Path or Absolute path. And the `type` attribute you can specify in it the type of the element, e.g. mp4 video like `type="video/mp4"`.
**Other video tag attributes**:
- autoplay:	Specifies that the video will start playing as soon as it is ready
- controls:	Specifies that video controls should be displayed (such as a play/pause button etc).
- height(in pixels):	Sets the height of the video player
- loop:	Specifies that the video will start over again, every time it is finished
- muted:	Specifies that the audio output of the video should be muted
- poster(URL):	Specifies an image to be shown while the video is downloading, or until the user hits the play button
- preload(auto, metadata, none):	Specifies if and how the author thinks the video should be loaded when the page loads.
- src(URL):	Specifies the URL of the video file
- width(In pixels):	Sets the width of the video player

23. Span tag:

- Is used a lot quite often on the logos, where more styling needs to be applied on. E.g.:
`<span style="color: red;">Start</span>`
- Its quite an interesting element in HTML. 
- It's used for a very specific kind of styling on a specific html element, you can use span tag on these unique element, e.g. Logo.

24. Tables:
- `<table class="styled">`
- `<thead>`
 + `<tr>`
 + `<th>First Name</th>`

- `<tbody>`
 + `<tr>`
 + `<td>John</td>`
- Table Styling: Normally for table you'd use the bootstrap to style the table.
- 

25. Commenting code: 
- It is very good practice. Helps with code handovers & debugging
- Code is commented as follows: ``<! -- <h2>Enjoy on your TV.</h2> -->``
- 

26. The Favicon. Whats that?
- Icon
- Used inside the head tag:

```
<head>
    <link rel="icon" href="assets/favicon.png">
</head>
```

27. Embedding Scripts in HTML:

- You can use link tag to add the font-family from `fonts.google.com`, this way you will need to specify the CSS rule in the head tag, and skip creating a styling file.
- Another you can use scripts tag - `<scripts>`, at the very end of our body. Right before the closing body tag.
e.g.
```
    <script>
        alert("HELLO WORLD")
    </script>
```




#### **CSS**
- Cascading Styling Sheets. 
- The look of the website - Human Body Analogy - Intertwined.
- Fonts, Colors, Backgrounds, layouts and many more styles.
- It brings that look and feel to websites, creates that amazing astatic. 

**JavaScript**
- Programming Language
- Used to manipulate the HTML and CSS
- Can build Web Apps - Many Frameworks, like React.JS, Angular.JS built on top of JavaScript. You can build mobile, web, desktop apps and etc.
- Brings live to Website, makes website interactive. Triggers actions, changes the placement of other elements - removes/display the headings, title & etc. Makes developers play around with HTML and CSS using JavaScript to make Websites functional.

1. CSS inline, Internal And External CSS.
- Apply the DRY principle. Use external CSS
- 

2. Selectors:
- Simple selectors
- Combinator selectors
- Pseudo-class Selectors
- Pseudo-elements Selectors
- Attribute Selectors

3. Id Selector:
- No two or more items can have the same value of the id.

4. Class Selectors:
- Most used in your CSS. Use `.`

5. Simple Selectors: Multiple classes:

- `<p class="lg-font red"></p>`

6. Universal selector `*`:

Use `*` for Universal Selector.

7. CSS Fonts:

- Access all the fonts from `fonts.google.com`, select your favorite and add it through import in CSS. E.g.:
``
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,400;0,500;0,600;0,700;1,300&display=swap');

``

8. CSS properties:
- Lot of properties in CSS we can use to style our elements.

- **Layout and Positioning**
These properties control the placement, size, and arrangement of elements on a page. 
 + display: Defines how an element is shown (e.g., block, inline, flex, grid, none).
 + position: Specifies the element's positioning method (e.g., static, relative, absolute, fixed, sticky).
 + top, bottom, left, right: Used with positioned elements to specify location.
 + float: Specifies whether an element should float to the left or right.
 + width, height: Sets the dimensions of an element.
 + margin, padding: Control the space outside and inside an element's border, respectively.
 + overflow: Controls what happens to content that is too big to fit into an area. 

- **Text and Fonts**
These properties control the typography and appearance of text. 
 + color: Sets the color of the text.
 + font-family: Specifies the typeface.
 + font-size: Sets the size of the text.
 + font-weight: Sets the thickness of the characters (e.g., bold, normal, 400, 700).
 + text-align: Aligns the text within its element (e.g., left, center, right, justify).
 + text-decoration: Adds decorations to text (e.g., underline, overline, line-through, none).
 + line-height: Sets the height of a line box. 

- **Visual Effects and Appearance**
These properties manage visual styling, backgrounds, and interactivity. 
 + background-color: Sets the background color of an element.
 + background-image: Specifies a background image.
 + border: A shorthand property for setting the width, style, and color of an element's border.
 + border-radius: Adds rounded corners to elements.
 + box-shadow: Attaches one or more shadows to an element.
 + opacity: Sets the transparency level of an element.
 + cursor: Specifies the mouse cursor to be displayed when pointing over an element. 

`` https://www.w3schools.com/CSSref/index.php``

9. CSS: Box Models
- Consists of Margins, padding & content
e.g.
```
.my-box {
    height: 100px;
    width: 100px;
    background: rebeccapurple;
    border: 10px solid black;
    margin: 20px 25px 30px 25px;
    padding: 50px 15px 10px 20px;
}
```

10. CSS: Box sizing
-  `{ box-sizing: border-box;}` is used to include the padding and border of the element within the specified height and width of the element.
- How to resolve the problem with the Width and Height on above example of Box Model.
- Use Box Sizing, height is actual equal ( 2 x  Padding + 2 x  Border), the one given in the above example is not the actual height of the element.
- Use Box Sizing, width is actual equal (2 x  Padding + 2 x  Border), the one given in the above example is not the actual width of the element.
- Padding and Border are added the actual size of these two. 
- We can use **Box Sizing** which allows to include the padding and border in an element's total width and height. 
- NB: **Rearrange the actual values of Width and Height, so the height and width of the element will be exactly equal to value specified in the Box Model example.**
e.g.:
```
* {
    box-sizing: border-box;
    margin: 0px;
}
```
11. CSS: Backgrounds

- Used to define the background effects for an element.
+ background-color: color of the image
+ opacity: set the transparency of the image.
+ background-image: URL(link)
+ background-size: e.g. 'auto' default, 'cover' good practice, 'contain'==auto, 
+ background-repeat: specify the repeat of the image, e.g.: 'no-repeat' default, '2 5'=='2 in x-axis and 5 in y-axis' and ect.
+ background-position: the positioning of the image, e.g. 'top', 'center' default, etc


Online: e.g.
```
* {
    background: bg-color bg-image bg-repeat bg-position;
}
```
Example set for the project:
e.g.
```
.banner-wrap {
    background-image: url("https://assets.nflxext.com/ffe/siteui/vlv3/73334647-ad51-42a9-b07b-93298cc2a8e1/2b0fca4f-c15c-4622-9efc-572c4a408c30/IN-en-20230605-popsignuptwoweeks-perspective_alpha_website_large.jpg");
    opacity: 50%;
    background-size: cover;
    background-repeat: no-repeat;
}
```
12. CSS Selectors: Comninator Selectors:
**Four types**
- Descendent selector> matches all the elements that are descendents of a specific element.
e.g.
```
.combined p {
    background: yellow;
}
```
- Child Selector `>`: Selects all elements that are the children of the specified element
e.g.
```
.combined > p {
    background: yellow;
}
```

- Adjacent Sibling selector: is used to select the element that is directly after another specified element: meaning right next only
e.g.
```
.combined + p {
    background: yellow;
}
```

- General Sibling Selectors: Selects all the elements that are sibling of the specified element.
 e.g.
```
.combined ~ p {
    background: yellow;
}
```

13. CSS units:
- Px value == absolute value
- % relative to the parent
e.g. box2 inside box1, box2 takes percentage towards box1.
HTML:
```
    <div class="box1">
        <div class="box2"></div>
    </div>
```
CSS:
```
.box1 {
    height: 200px;
    width: 200px;
    background: blue;
}
.box2 {
    height: 50%;
    width: 50%;
    background: red;
}
```

or Make box2 take only 50% of height:
```
.box1 {
    height: 200px;
    width: 200px;
    background: blue;
}
.box2 {
    height: 50%;
    width: 100%;
    background: red;
}
```
- Vw == based on the screen size
- Vh == based on the screen size
e.g.: 
```
.banner-wrap {
    background-image: url("https://assets.nflxext.com/ffe/siteui/vlv3/73334647-ad51-42a9-b07b-93298cc2a8e1/2b0fca4f-c15c-4622-9efc-572c4a408c30/IN-en-20230605-popsignuptwoweeks-perspective_alpha_website_large.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    height: 100vh;
    width: 50vw;
}
```

apply to the project:
```
.banner-wrap {
    background-image: url("https://assets.nflxext.com/ffe/siteui/vlv3/73334647-ad51-42a9-b07b-93298cc2a8e1/2b0fca4f-c15c-4622-9efc-572c4a408c30/IN-en-20230605-popsignuptwoweeks-perspective_alpha_website_large.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    height: 90vh;
}
```

**CSS: FONTS**: The following are used specifically for fonts.
- Rem == relative to the root
e.g.
```
h1 {
    font-size: 5rem; /* relative to the default value times 3*/
    color: white;
}
```
- em == relative to the parent element's fonts - Bad user design-principle, prefer to use `rem` as it is good principles.
```
.banner-container {
    font-size: 20px;
}

.get-started-form h3{
    font-size: 2em;
}

```
- % works the same as em for fonts


14. CSS: Flex and Flow.
- A layout module. For flexible responsive layout structures
- Use flexbox to organize your elements better.
e.g. 
```
.menu-area {
    display: flex;
}
```
- By default if appears in row, which is horizontal.
- Properties:
 + **Flex-direction**: define a direction in which a container wants to stack the flex items = 'row' default, column', 'row-reverse', 'column-reverse'
 + **justify-content**: align flex items. 'flex-start', 'flex-end', 'center', 'space-around' and 'space-between'
 + **align-items**: align flex items in **opposite direction** (vertically): 'flex-start', 'flex-end', 'center', 'stretch' default and 'baseline':
 e.g.:
 ```
 .banner-container {
    display: flex;
    color: white;
    flex-direction: column; /* if flex-direction equals this, The 'justify-content' switch with 'align-items', thus we align flex items using 'align-items' property.*/
}
```
correct way:
```
.banner-container {
    display: flex;
    color: white;
    flex-direction: column; /* The 'justify-content' switch with 'align-items', thus we align flex items using 'align-items' property.*/
    align-items: center;
}
```
 + Flex-wrap
 + Flex-flow
 + align-content


15. CSS: Elements flow

- Div, span, images: 
 + Divs are display: block; by default. Fill the parent container; and get stack on top of one another
 + Spans are display: inline; by default. Will take minimal space in Divs, they can't have the width and height
e.g.
HTML:
```
    <span class="test">
        TEST
    </span>
```
CSS:
```
.test {
    background: blue;
    height: 50px;
    width: 200px; /* heights and width do not apply to element of span*/
}
```

```
.test {
    background: blue;
    height: 50px;
    width: 200px; /* heights and width do not apply to element of span*/
    display: inline-block; /* Now the height and width will apply, display changed */
}
```

HTML:
```
    <span class="test">
        TEST
    </span>
    <span class="test">
        TEST
    </span>
```
```
.test {
    background: blue;
    height: 50px;
    width: 200px; /* heights and width do not apply to element of span*/
    display: inline-block; /* Now the height and width will apply, display changed they will one next to each other*/
}
```
```
.test {
    background: blue;
    height: 50px;
    width: 200px; /* heights and width do not apply to element of span*/
    display: block; /* Now the height and width will apply, display changed they will one below to each other*/
}
```

 + Images are disply: inline-block; by default. Can set height and width.
- NB: with display: none; element will simply disappear

 -= If the height or width of the element does not work in CSS, just change to the diplay: 'inline-block'; or 'block'

16. CSS Position property: 
- All elements have default position: static i.e. - appear in order specified in element flow
- We can control flow using other properties
- `position: relative`
 + The position element relative to its original  position in the element flow
 + This does not affect the other elements in the flow

e.g.:
```
    <div class="info-container">
        <div class="box relative"></div>
```
```
.box {
    height: 150px;
    width: 150px;
    background: green;
    position: relative; /* Allows you to place an element relative to its original position*/
    top: 0;
    left: 50%;
}

```

- Position: absolute removes an element from the normal flow
 + The element will be positioned in relation to the first ancestor that is not static or that is not in the natural flow
 + can change the positioning of parent to relative - it does not alter the position of elements. e.g.

```
    <div class="box absolute">Absolute</div>

    <div class="info-container">
        <div class="box relative">Relative</div>
```


```
.box {
    height: 150px;
    width: 150px;
    background: green;

}
.relative {
    position: relative; /* Allows you place an element relative to its original position*/
    bottom: 50%;
    left: 50%;
}
.absolute {
    position: absolute;
    right: 0;
}
```

example to apply on 'info-container':
```
    <div class="info-container">
        <div class="box absolute">Absolute</div>
        <h1>Enjoy your TV.</h1>
```

```
.info-container {
    background: black;
    color: white;
    position: relative;
}
.box {
    height: 150px;
    width: 150px;
    background: green;

}
.absolute {
    position: absolute;
    top: 0;
    right: 0;
}
```
- `Position: fixed` - it actually disrupt the element from the normal flow, its used for **navbar**, to place the element fixed to the position relative to the normal flow
```
    <div class="info-container">
        <div class="box fixed">Fixed</div> <!-- it is actually used for navbar, to place the element fixed to the position relative to the normal flow -->
        <!-- <div class="box absolute">Absolute</div> -->
        <!-- <div class="box relative">Relative</div> -->
```

```
.box {
    height: 150px;
    width: 150px;
    background: green;

}
.fixed {
    position: fixed;
    top: 0%;
    left: 0;
    height: 50px;
    width: 100%;
}
```

- `position: sticky;` 
e.g.
```
    <div class="info-container">
        <div class="box sticky">Sticky</div> 
        <!-- <div class="box fixed">Fixed</div>  -->
        <!-- <div class="box Relative">Relative</div>
        <div class="box absolute">Absolute</div> -->
```

```
.box {
    height: 150px;
    width: 150px;
    background: green;
}
.sticky {
    position: sticky;
    top: 0;
    height: 50px;
    width: 100%;
}
```

17. CSS: Flexbox - Fix `info-container` container.
