# How to install prettier

By now, you should already have Visual Studio Code installed on your computer.
The next step is to go to the extensions tab on your workspace, as shown in the first image:

https://github.com/JonathanGrossmanITC/frontend_tips/blob/main/prettier/Capture1.PNG


## [HTML and CSS Refresher](#html-and-css-refresher)

HTML and CSS are languages that instruct the browser how to display the contents on the page. HTML defines the **elements** of the page. The elements of the page consist of text, images, videos, content blocks, and more. HTML and CSS together define the **layout** and **style** of the elements. The layout is how the elements are organized on the page. The element styles include the size, spacing, color, font, and more.  

### A web page is a document




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
