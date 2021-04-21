# What is Prettier

Prettier is a code formatter. What that means is that Prettier adds tabs and line breaks to your code in ways that makes it easier for you and other people to understand. Without proper formatting, your code will be much more difficult to read and maintain.  

# Why and how should you use Prettier?

You should use Prettier to make it easier for developers to read your code. Software, such as a browser, is perfectly capable of reading and executing your code even if the formatting is bad so long as the syntax is correct. That's because the browser doesn’t care if the code looks pretty. Instead, the browser cares whether the is correct and doesn’t produce errors.

You know who does care about code formatting and comments? Humans. People like you and me who need to read, understand, and modify code from time to time. It’s much easier if you have proper formatting. Proper formatting makes the code easier to understand. For instance, a blank line helps you quickly distinguish between different blocks of code and a tab at the beggining of a new line instantly tells you that you're looking at a nested item.  

Even if you're new to programmning, you hopefully can already appreciate the importance of proper formatting because not using formatting in code is equivalent to not using formatting in writing. You wouldn’t read this post if it did away with all the paragraphs and headings, no matter how good the content is!

This code, for example, will work because the synax is correct. But it's ugly, and quite hard for you and me to understand.

![extensions tab](/prettier/Capture3.PNG)

To fix it, just use Prettier! Prettier is one of many code-formatting extensions that with one simple command, will make your code look much better.

On Windows: Alt + Shift + F.  
On Mac Shift + Option + F.  
On Linux Ctrl + Shift + I.  

This is the outcome:

![extensions tab](/prettier/Capture4.PNG)  

# How to install Prettier

By now, you should already have Visual Studio Code installed on your computer. The next step is to go to the extensions tab on your workspace, as shown in the image below:

![extensions tab](/prettier/Capture1.PNG)

Once there, you will be able to find many extensions to make your programming life easier and faster. Search for the Prettier extension, select it, and press install.  

![extensions tab](/prettier/Capture2.PNG)  

After a few seconds, you should have Prettier installed. Now, you can make your code, well, prettier!

You also can set-up Pretter so that it auto-formats each time you save the file. To complete that setup, open your settings by pressing Ctrl + or by clicking the `⚙` at the bottom left of VS Code. In your VS Code settings, search for "format" and choose "format on save".  

![extensions tab](/prettier/Capture5.png)

Next, in the VS Code settings, serach for "default formatter" and make sure to choose Prettier as your default formatter.

![extensions tab](/prettier/Capture6.PNG)

There you go! Now you have a solution that allows you to focus on building instead of formatting!


