# Reading Material HTML/CSS/GIT Week 1

## Agenda

These are the topics for week 1:

1. What is the command line interface (CLI)?
2. Introduction to HTML:
   - Crash course
   - The most commonly used tags
   - Semantic HTML
3. Introduction to CSS:
   - Crash course
   - Where to write it?
   - The box model
   - The cascading effect

## 0. Video Lectures

Watch this video: [Videos 1 - 6](https://www.youtube.com/playlist?list=PLVYDhqbgYpYXbAL_Hps1Y--THRmaTFipj)

<a href="https://www.youtube.com/playlist?list=PLVYDhqbgYpYXbAL_Hps1Y--THRmaTFipj" target="_blank"><img src="../assets/week1-arco.png" width="600" height="400" alt="HYF Video" /></a>

## 1. What is the command line interface (CLI)?

The `Command Line interface` (also known as CLI or shell) is a way to navigate through your computer's content (media, folders, applications, etc.) without a visual user interface. It allows you to type text commands to perform specific tasks. Since you can directly control the computer by typing, many tasks can be performed more quickly, and some tasks can be automated with special commands that loop through and perform the same action on many files.

As a beginning developer it's important to get familiar with it, as it will teach you how computers work: as tools that you give instructions to. This is not any different from programming for web development; but instead of writing instructions to the computer directly, you write instructions for browsers to execute!

The first thing you'll notice is that once you type in a command, the computer doesn't always give back feedback. This is completely normal. Most of application development goes like that, and it's good to get used to it.

**Note for Windows users**: Please install [Git for Windows](https://gitforwindows.org). It comes with an application called *Git BASH* which simulates frequently used CLI commands in Unix fashion. This aligns our work here in this course, as we can all use the same commands. But there is an even bigger reason: Being comfortable in the Unix Bash shell is very important for a web developer, as web servers usually run Linux.

For more information, check the following resources and code along:

- [Understanding the Command Line for Beginners](https://learntocodewith.me/getting-started/topics/command-line/)
- [A Command Line Primer for Beginners](https://lifehacker.com/a-command-line-primer-for-beginners-5633909)
- [Command Line Crash Course](https://www.youtube.com/watch?v=yz7nYlnXLfE)

## 2. Introduction to HTML

### Crash course

HTML is the foundation of web development. It is an acronym for **HyperText Markup Language**. It is used to structure content on a webpage. What do we mean by content? Plain text, images, videos, links to other websites, etc. The structure gives content meaning by defining that content as, for example, headings, paragraphs, or images.

In order to learn HTML properly it's important to know what is is. Go through the following resources to learn more about it:

- [HTML5 Basics - History of HTML](https://www.youtube.com/watch?v=NzzGt7EmXVw)
- [HTML Crash Course](https://www.youtube.com/watch?v=UB1O30fR-EE)

### The most commonly used tags

If at any point you came to believe you would have to learn a whole list of tags by heart in order to write great HTML, you are in luck: that's not needed.

The most important thing to know is that the tags are used to **structure content**, or in other words: to decide how each part is organized in order to more easily understand what the page is trying to communicate.

It's useful to memorize this list, but don't feel like you have to learn and memorize _every_ HTML tag. Once you understand the basics, you can easily look up which tag you need.

Check out the following article to find a list of the most commonly used tags: [The Most Commonly Used Tags](https://www.geeksforgeeks.org/most-commonly-used-tags-in-html/)

## Semantic HTML

Semantic HTML are HTML tags that introduce meaning to the web page rather than just presentation. For example, a `<p>` tag indicates that the enclosed text is a paragraph. A `<nav>` tag indicates a navigation menu of some kind. Both examples show meaning and structure, in this way it's easier to understand for both the browser and the developer.

This leads to the following insight about writing code: while code is written to produce working software, it should also be written so **other developers can easily read and understand it**. That's why it's so important to write meaningful code: if somebody else can read it and understand what you meant you did a great job!

Take a look at the following resources to learn more about semantic HTML:

- [Semantic HTML](https://www.internetingishard.com/html-and-css/semantic-html/)
- [HTML5 as Fast as Possible](https://www.youtube.com/watch?v=IsXEVQRaTX8)

## 3. Introduction to CSS

### Crash course

CSS is just as important as HTML. It is an acronym for **Cascading Style Sheets**. It is a language created to change the appearance of content. By referring to the HTML tags you can `style` it in various ways: change the `font-size`, increase the `height` or attach a `background-image` to it.

Go through the following video to get a firmer grasp of the fundamentals of CSS:

- [CSS Crash Course](https://www.youtube.com/watch?v=yfoY53QXEnI)

### Where to write it?

There are 3 basic ways to write CSS:

- In an external stylesheet: a `.css` file, that is linked to a `.html` file using the following tag:

```html
<link href="/path/to/style.css" rel="stylesheet" />
```

- In the `<head>` of a `.html` file. This is done using the `<style>` tag. This is called an `internal stylesheet`:

```html
<head>
  <style>
    body {
      background-color: blue;
    }
  </style>
</head>
```

- As part of the attribute `style` inside any HTML tag. This is called `inline styling`:

```html
<div style="background-color: blue;">Techrity is cool!</div>
```

In practice, you'll always write your CSS in separate `.css` files. This is because you want to make sure **every file has a single purpose**: an HTML file should only contain the content and structure of a page, while a stylesheet should only contain styling rules that apply to a page.

This is a software design principle called [`separation of concerns`](https://softwareengineering.stackexchange.com/questions/32581/how-do-you-explain-separation-of-concerns-to-others).

### The box model

"In CSS, everything is a box". This phrase summarizes a central concept in HTML/CSS: the box model. When building a web page each element can be considered a box that has the following properties: `margin`, `border`, `padding` and `content`. Starting from the first element within the `<body>`, everything that comes after will be pushed down (thanks to these 4 properties).

To learn more about the box model, go through the following:

- [Learn CSS Box Model In 8 Minutes](https://www.youtube.com/watch?v=rIO5326FgPE)
- [Opening the Box Model](https://learn.shayhowe.com/html-css/opening-the-box-model/)

### The cascading effect

The first C in CSS stands for Cascading and it's crucial to learning how to use CSS correctly. Essentially, it means that it matters
(1) **in which order** and
(2) **how specific**
you write CSS rules.

Read the following articles to learn about it:

- [The "C" in CSS](https://css-tricks.com/the-c-in-css-the-cascade/).
- [How CSS works: understanding the cascade](https://blog.logrocket.com/how-css-works-understanding-the-cascade-d181cd89a4d8)

## Finished?

Are you finished with going through the materials? Nice job!!! If you feel ready to get practical, click [here](./MAKEME.md).
