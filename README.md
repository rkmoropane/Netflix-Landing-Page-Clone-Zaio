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

2. Building blocks of Web: HTML, CSS & Javascript.
**HTML**
- All content comes from HTML: Hyper Text Markup language. It's a Mark up language that computer can interprets and write on the Website.
- The HTML file, known as Entry point file is basically where each websites starts at.
- HTML is the basics, headings, paragraphs, etc.

**CSS**
- Cascading Styling Sheets. 
- The look of the website - Human Body Analogy - Intertwined.
- Fonts, Colors, Backgrounds, layouts and many more styles.
- It brings that look and feel to websites, creates that amazing astatic. 

**JavaScript**
- Programming Language
- Used to manipulate the HTML and CSS
- Can build Web Apps - Many Frameworks, like React.JS, Angular.JS built on top of JavaScript. You can build mobile, web, desktop apps and etc.
- Brings live to Website, makes website interactive. Triggers actions, changes the placement of other elements - removes/display the headings, title & etc. Makes developers play around with HTML and CSS using JavaScript to make Websites functional.

3. **HTML vs CSS**

- How important are HTML vs CSS relatively.
- Websites cannot without CSS, it needs the styling functionality to be able to work 100%.
- 

4. How to use the interactive coding environment:

- Ashkil will be coding something in the interactive coding environment, pushing each time. I just have to pull into my VS code environment and make pushes each time.
- Practice n Practice, pull the changes and make your hands dirty everytime.

5. Let's get setup:

- Have google Chrome setup installed [x]
- Have VS Code setup installed [x]
- Have Live Server extension installed in VS Code [x]

6. **HTML Book Analogy**

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

7. **File Naming Conventions & File organizing:** Stick to same consistance of these so that you follow good practices in the Web Development Industries.

- Sstick to lowercase for naming files,
- Make the names shorter,
- Have descriptive naming - `profile.html` not 'page1.html`, etc.
- Use underscores or hyphens instead of 2 words merged. e.g. `about-us.html`. No Capital letters like - `AboutUs.html`, wrong this one. No spaces.
- Main folder is the root folder.
- the `index.html` is normally what is used for the home or root file. Thus it's in the root folder, not sub folders.
- Can put pages into sub folders.
- Assets folders for images

8. File structure:
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

9. **Headings & Paragraphs**

- Headings denote the hierarchy & page structure.
- Only have 6 levels of headings:
 + `<h1>, <h2>, <h3>, <h4>, <h5> & <h6> `

- Paragraphs are really simple opposed to headings.
- They are regular text we use
- use the tag: `<p>`
- Not numbered like headings, only the `<p>` tag.

10. **Strong vs Em**

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

11. **The Anchor element**

- `<a>` is short for anchor
- Used to link:
 + To link to a different location on the current page.
 + or to another page.

- E.g.:

```
<a>Sign in</a>
```

- **How will the browser know where to redirect when this element is clicked on?** We need to understand the elements' attributes.

12. Elements can have attributes:

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

13. **Relative Path**:

- Pointing to files in locally - in the project.
- Visit about us page:
 + `<a href="./about-us.html">About Us</a>`
 + `<img src="./assets/bgimage.png" alt="">`
 + Above is how to create an image - pointing to a local file i.e. **Relative Path** 
- Create a CONTACT US page, link it in the Home page pointing to Contact Us page - That's how you use **Relative Path**

14. Opening in a new tab: **Target attribute**:

- Use the `target="_blank"` attribute within the opening tag of the anchor tag <a> to open in a new tab.
 + `<a href="./about-us.html" target="_blank">About Us</a>`
- `https://www.w3schools.com/tags/att_a_target.asp`

15. Redirecting to a different part on the same page: Anchor tag - position on same page.

- Move cursor to a different element on the code editor.

- In the `<a>` href attribute use the `#` to point to an id of different element in order to move to that different element in the same editor.

- e.g.
`
```
<a href="#redirect_Section">POINT TO A DIFFERENT SECTION</a>
.
.
.
<h1 id="redirect_section">TEST 2 REDIRECTION SECTION</h1>
```

- You can always point to the different part on the same page using this anchor tag with `href="#"` and the added id of that element.


16. 