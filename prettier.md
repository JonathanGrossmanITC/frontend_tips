# Day 1: HTML and CSS Basics

HTML, CSS, and JavaScript are the three main languages required for building the frontend of a web application. HTML and CSS are used primarily to organize and style the contents of a web page. In contrast, JavaScript is used to provide functionality to your page. For instance, using JavaScript, you can send the values entered into a form to a server or change the information shown on the page based on what the user clicks.  

Read this lesson and look at the links before the first class. In class, you will be expected to be familiar with the topics in this document. You will watch a live coding session that uses the concepts discussed in here. In that live coding session, we will set up our frontend web application and begin building our mobile-first design.  

We will start the class by building the folders and files the browser needs to load our web application. In doing this, we will do a quick refresher on what HTML and CSS are. We will talk about how when a user opens a browser on their computer, the browser requests the HTML, CSS, JavaScript, and media files the browser needs to build the web page (i.e., the source code). The browser uses the source code and other files to assemble the web page for the user to see and interact with.

Here in this lesson, you start by studying the very basics of HTML and CSS. This will help you build your project folder and connect your HTML, CSS, and JavaScript files. Next, you'll learn about using external stylesheets and CSS selectors. Then, you'll learn about a mobile-first approach to web development using media queries. Media queries are a very useful tool in responsive web design. They let you change an element's style based on the screen size. This mobile-first approach will help you think about how to approach structuring your code as your start your project.  

Although this lesson assumes you already have some HTML, CSS, and JavaScript skills, it is not required that you do.

By the end of this lesson, you will have:

- A refresher on [HTML and CSS basics](#html-and-css-refresher) and a good idea of how to structure your project folder    
- An intro to [CSS Selectors](#css-selectors) and the ability to work with an external stylesheet    
- Mobile-first design using [media queries](#media-queries) to help you think about structuring your project from the start    
- Self-study resources for learning about pseudo elements  

## [HTML and CSS Refresher](#html-and-css-refresher)

HTML and CSS are languages that instruct the browser how to display the contents on the page. HTML defines the **elements** of the page. The elements of the page consist of text, images, videos, content blocks, and more. HTML and CSS together define the **layout** and **style** of the elements. The layout is how the elements are organized on the page. The element styles include the size, spacing, color, font, and more.  

### A web page is a document
You're probably familiar with working in a Word Doc, Google Doc, Notepad, and .txt files. Similar to those, an HTML file is just a document for storing information. Try this. Make a file on your desktop called `document.html`. Open it and write the sentence "This is just a document". Save the file. Open a browser and drag your `document.html` file to the browser. What do you see in the browser?  

Pretty cool, but wouldn't it be better if you could add some style to the text? You could change its color, position, size, and more. Using HTML and CSS syntax, you can tell the browser how to do those things. One of the things that makes HTML and CSS so special is that browsers know how to interpret those kinds of files and display them to the user.  

In this section, you'll learn about HTML tag syntax. This is a special syntax you need to use so that the browser knows what to do. Before studying the tag syntax, first, you'll see an example of how to structure an HTML page. In order to maximize the use of an HTML file, you need to know how to structure one. Then, you'll study some different tag types and how they work.   

Before going further, here is an example of a basic HTML document structure, which the browser reads from top to bottom:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Hello</title>
  </head>
  <body>
    <h1>Hello ITC!</h1>
    <h2>Welcome.</h2>
    <p>This is text inside a paragraph tag.</p>
    <div>This is text inside a div.</div>
    <h4>
      <span>This half is in a span, </span>
      <span>and this half is in a different span.</span>
    </h4>
  </body>
</html>
```

The example above uses multiple HTML tags. At the top, the `<!DOCTYPE html>` tells the browser that this file is an HTML file. Next, the `html` tag is the main element that wraps all the other HTML tags. The `head` tag holds metadata about the page. Here, the metadata in the `head` tags sets the title that you see in the browser's tab at the top. Look for it in the image of the example below. Other metadata, however, is usually just for the browser to read, not for the user to see. An example is a link to a stylesheet, which you'll see below in the CSS section.  

The `body` tag holds all the content for the page. It wraps all the page's content-holding elements and indicates to the browser that this is where the content is located.  

Inside the body are the content-holding tags. In this example, the content is text. You see `h1`, `h2`, and `h4` tags, each of which come with different default font styling. You also see `p`, `div`, and `span` tags, each of which comes with its own default styling. More on this later. The bottom line is that inside the `body` element is where you'll put the content that the user sees in the browser.  

To see this HTML in your own browser, download this repository and drag to the browser the [hello html file](html/hello.html). It should look like this:

![](images/hello_html_photo.png). 

Finding [HTML examples](https://www.w3schools.com/html/html_examples.asp) online is a great way to help you write your own code.  

As the example demonstrates, a website is really just a document. You can display the document either in the browser window or as the HTML source. When viewed in the browser, you see the page content organized and styled for the end user. When viewed as source code, you see all the HTML code. Regardless, it is the same document.  

The web page document relies upon other documents for content, style, and functionality. The HTML document relies upon CSS documents, images, and other files for content and style. It relies upon JavaScript files for functionality.  

In your project folder, organize your files similar to the structure here in this repository.

```html
-root
  --css
    ---styles.css
  --js
    ---index.js
  --html
    ---about.html
  --images
    ---image.png
  index.html
```

The root folder contains subfolders for `css`, `js`,`html`, and `images`. Usually, you put the `index.html` in the root folder. You can name the root folder whatever you want, like `portfolio_project` or whatever.


### Developer Tools


![](images/inspector.png)
