# leon-Template1
### pure HTML and CSS 
![2022-09-26](https://user-images.githubusercontent.com/107018939/192271829-d9125f7a-ccd8-4f2a-a277-cc2b8b24c817.png)
![2022-09-26 (3)](https://user-images.githubusercontent.com/107018939/192271840-e09b1377-e2ab-4959-9963-c5d2920f6d52.png)

<br>
-check my website page: https://ahmedsalamaabuzaid.github.io/kasper-template2/

## inspiration

I have used the PSD file from graphberry website 
<br>
[leon template](https://www.graphberry.com/item/leon-psd-agency-template)
</br>

### Who

I'm ahmed salama. I'm a front-end developer and I've been teaching myself HTML, CSS, and other web development and scripting for long time.
And I want to teach you now some things i have learned.
Because you're good looking.
And because it's useful.

 ##tips and advices...
**  here is what i used and i will give you some tips to follow **
 
### IN HTML

1. Use proper document structure
HTML documents will still work without elements such as <html>, <head>, and <body>. However, the pages will not render correctly in every browser so it's       important to be consistent using the proper document structure.

2. Declare the correct doctype
When creating an HTML document, the first thing to declare is the doctype. This will tell the browser the standards you are using to render your markup         correctly. The doctype goes before the <html> tag at the top of the page. If you are unsure about what declaration to use, W3.org provides information on       choosing the right doctype.

3. Always close tags
To avoid encountering validation errors always remember to have a closing tag for every tag you create.

4. Don't use inline styles
It may seem like an easy route to place styling in line with the code instead of creating an external style sheet. However, inline styles are not a good       coding practice because it makes it harder to update and maintain a website. Instead, keep your styles separate from your HTML mark-up.

5. Use alt attribute with images
It is not required to have an alt attribute with images, which makes it easy to ignore. However, it is important to have a meaningful alt attribute for         validation and accessibility reasons. The alt attribute provides context to screen readers so it should be descriptive as to what the image contains.

6. Validate frequently
Instead of waiting until you are finished with your HTML document, validate your code multiple times as you work. This will help save some time in the end     by identifying errors early on, especially if your document is lengthy. One popular HTML validator to use is W3C's markup validation service.

7. Place external style sheets within the <head> tag
Although external style sheets can be placed anywhere in the HTML document, it is best practice to place them within the <head> tag. This will allow your       page to load faster.

8. Use meaningful tags
Each section of your web page should be built using the most appropriate HTML5 tag for the content. It's best to avoid excessive use of generic tags, such     as <div>, when there could be a more descriptive tag for the job such as <section>, <article>, and so on

9. Use lowercase markup
Your HTML markup can be written in lowercase or uppercase and the web page will render correctly. However, it is best practice to keep tag names in             lowercase because it is easier to read and maintain.

10. Reduce the number of elements on a page
HTML documents can become complicated, especially for webpages with a lot of content. To reduce the size of your pages, check for opportunities to further     optimize your code once you are finished with your markup.

### in CSS
    
1. Create it Readable

The readability of your CSS is necessary, although the general public overlooks its importance. Nice readability of your CSS makes it a lot easier to keep up with the future, as you will be able to notice components faster.

Note: Usually while writing CSS, most developers adopt one of the following approaches.

Approach 1: All on one line as below:

```CSS
.example{background:red;padding:2em;border:1px solid black;}
```
Approach 2: Each style gets its own line as below:

```CSS
.example {
background: red;
padding: 2em;
border: 1px solid black;
}
```

Both practices square measure is acceptable, although you may usually notice that way two despises way one! Simply keep in mind – opt for the tactic that appears best TO YOU. This is all that matters.

2. Use Reset and Normalize CSS

Most CSS frameworks have an option to reset them. If you are not aiming to use the existing framework reset CSS  one, then a better option will be to set them to reset or normalize. Resets or Normalize CSS eliminate browser inconsistencies like heights, font sizes, margins, headings, etc. The reset permits your layout to look consistent all told browsers.

Find different type of Reset CSS from here: http://cssreset.com/

3. Organize the Stylesheet

It is smart to put your stylesheet come in the simplest way that permits you to realize elements of your code quickly. I like to recommend a top-down format that tackles designs as they seem within the ASCII text file. So, an associate degree example stylesheet could be ordered like this:

i) Generic Element (body, a, p, h1, etc.)
ii) .header
iii) .nav
iv) .wrapper
Also, use commented CSS like below:

```css 
/****** header ******/
styles goes here…
/****** navigation ******/
styles goes here…
/****** main content ******/
styles goes here…
/****** footer ******/
styles go here…
```
4. Combine CSS Elements

Elements during a stylesheet typically share properties. Rather than re-writing previous code, why not simply mix them? As an example, your h1, h2, and h3 components would possibly share identical font and color. Hence you can combine the same:

```css 
h1, h2, h3 {
font-family: verdana;
color: #e1e1e1;
}
```
5. Use Appropriate Naming Convention

One of the main advantages of CSS is the ability to separate designs from content. You’ll be able to change the entire design of your website by simply modifying the CSS without ever touching the markup language. Therefore don’t create your CSS by using limiting names. Use additional versatile naming conventions and keep consistent.

The naming of your CSS elements is based on what they’re, not what they give the impression of being like. For instance, “.comment-blue” is not appropriate than “.comment-beta” (because if you need to change the color of this class, then you only need to change in CSS, not in HTML), and “.post-large-font” is additional limiting than “.post-title”.

6. Always avoid inline styling

Using inline styling show the HTML code messy. Updating each HTML events style through global CSS is hard. So you always need to avoid inline style. Below is the example related to this style:

Bad Code:

```css 
<div style="float:left">
<img src="images/logo.gif" alt="" />
</div>
```
Good Code:

```css 
<div class="left">
<img src="images/logo.gif" alt="" />
</div>
```

7. Always use External CSS

The use of external CSS is beneficial. You can pull all the CSS in an external file and include this files in your HTML.

Benefits of External CSS:

All the CSS are stored within single Stylesheet.
All the style changes are done in a single CSS for each page (Easier to maintain the website).
Single CSS will be cached and page load faster.
Due to the use of external CSS, we can differentiate the CSS like web page layout CSS and Print-friendly CSS.
Use different version external stylesheet in your HTML as follows:

```css 
<link rel="stylesheet" href="style.css" type="text/css" media="screen" />
<link rel="stylesheet" href="style.css" type="text/css" media="print" />
```
8. Shorthand CSS

One feature of CSS is the ability to use shorthand properties and values. Most properties and values have acceptable shorthand alternatives.

Example:

```css 
img {
margin-top: 5px;
margin-right: 10px;
margin-bottom: 5px;
margin-left: 10px;
}

button {
padding: 0 0 0 20px;
}
```

Instead of above we can use shorthand CSS as follows:

```css 
img {
margin: 5px 10px;
}

button {
padding-left: 20px;
}
```
Also:

```css 
.module {
background: #DDDDDD;
color: #FF6600;
}
```
Instead of above we can use shorthand CSS as follows:

```css
.module {
background:#ddd;
color:#f60;
}
```
9. Minify CSS file size with CSS Compressors

It’s an excellent thought to minify the CSS file to reduce the file size. Through this, you can help browsers to accelerate the stacking of your CSS codes. So you can use a tool like CSS Compressor and Minifier to get this going.

You can minify your CSS here: https://csscompressor.net/

10. Cross-browser compatibility:

When you use an external stylesheet (where we can use browser engine prefix like -moz-, -webkit-, -o- and -ms-) for layout and valid markup (XHTML, HTML5), then your web pages work well on all browsers such as IE, Opera, Chrome, Mozilla, and Safari, etc..

Also following are the prefix description:

```css 
-moz- /* this is use for Firefox browser*/
-webkit- /*this is use for chrome and safari browsers*/
-o- /*this is use for opera browser*/
-ms- /*this is use for Internet Explorer (but not always it’s depends on CSS3 browser support)*/
```
