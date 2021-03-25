# Cheat Sheet

## Notes
Hello and welcome this is a cheat sheet on how to make .mk (Mark Down) files. Before we get started I highly recommend opening this file via "**VS Code**" and installing the extansion "**Auto-Open Markdown Preview**". The extension allows you to have the original text of the .mk-file on the left and see what the file looks like after it has been compiled on the right.

I hope this cheat sheet helps you and I wish you the best of luck with your project.

kind regards, pbofataf7

---

## Introduction

What is a .mk File? It is a text file which allows you to modify how the text looks without being as much as html. In this cheat sheet all the explaination to the code will be written like this. If you would like to know what the code syntax looks like you should look at the comments.

<!-- This is how you can make comments. Just put them with in brakets like these and your good to go. The comments can go over multiple lines and in the final output not a letter will be able to see. -->

---

<!-- Headings -->
## Headings

How do we make headings in .mk? Here are a few examples. Notice how the get smaller the more `#` we use. Just don't forget the space after them.

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5

---

## Formating Test

There are different ways on how you would like your text to be displayed. You might want it to be *italic* or perhabs you need it to be **bold** and sometimes you need to make an emphasise on how ~~not~~ to do things. Here are a few examples.

### Italic

<!-- Italics -->
*This text* is italic

_This text_ is also italic

### Strong

<!-- Strong -->
**This text** is bold

__This text__ is also bold

### Strikethrough

<!-- Strikethrough -->
~~This text~~ is strikethrough

---

## Lines

By now I belief you've noticed the horizontal lines that go threw the page and particion the sections nicely. Here is how you can do that.

<!-- Horicontal Rule -->

---
---

## Quotation

If you would like to add some additional information to the text a quote might be what you need.

<!-- Blockquote -->
> This is a quote

---

## Links

If people should be able to check your sources you might want to include links in your file this is how you can do that.

<!-- Links -->

<!-- [ ] = the part between these brackets is what the link will look like.
( ) = the part between thes brackets is URL and defines where the link takes you and the part in quotation marks is what will be displayed while you hover over the link.-->
[My Source](https://www.youtube.com/watch?v=HUBNt18RFbo&ab_channel=TraversyMedia)

[Everlasting Wealth](https://www.youtube.com/watch?v=dQw4w9WgXcQ&ab_channel=RickAstleyVEVO "Not really :P")

---

## Lists

Here is everthing you need to now on how to make lists and a few examples.

### Unordered Lists

<!-- Unordered List -->

<!-- Any symbol would work for an unordered list. Not just * but also - or + and many more. -->
* Item 1
* Item 2
* Item 3
    * nested Item 1
    * nested Item 2
        * even more nested Item 1

### Ordered Lists

<!-- Ordered List -->
1. Item 1
1. Item 2
1. Item 3
    1. nested Item 1
    1. nested Item 2
        1. even more nested Item 1

---

## Code

Sometimes you would like to show an idea of yours on a concrete example. In such cases it might come in handy that you can display code within a markdown file. You can have simple one liners of code, have entire coding blocks or explain the code with some `text` and have code within that `text`.

### Inline Code Block

<!-- Inline Code Block -->
<!-- just but whatever you'd like to have as code between these  ` ` -->

`<p>This is a paragraph</p>`

`int x = 6;` => `x` is an `int` variable with the value `6`

`float x = (float) y;` => `y` is an `float` variable but tepends on `x` for its value. 

In Detail: It gets **casted** from an `int` to a `float`. In this case its value would be `6.0`.

### Code Blocks

<!-- Code Blocks -->
<!-- Use a triple ` at the start and the end of your code. You can also add the name of the computational laguage after the first ` to get the proper highlighting. -->

Git Bash
```bash
    npm install

    npm start
```

Javascript
```javascript
    function add(num1, num2) {
        return num1 + num2;
    }
```

HTML
```html
    <p> A paragraph example</p>
```

Java
```Java
    public void Greeting(){
        System.out.println("Hello World");
    }
```

---

## Images

Maybe you would like to spice up your file by adding a few pictures. Here is how you can do it.

<!-- Images -->
<!-- start the code with ![ ... ] add a title between thes brackets. Add ( ... )
containing the URL to the picture to it. In addition if you would like to get a certain message displayed when you hover over it, add " ... " at the end inside the bracket containing the message-->

Like this

![Markdown Logo](https://markdown-here.com/img/icon256.png "The Markdown Logo")

---

## Tables

Last but not least tables can also be included in your markdown file.

<!-- Tables -->
<!-- Just follow the example underneath and do not forget to make spaces after the | or it wont display the table correctly.  -->

| Name      | Email             |
|-----------|-------------------|
| John Doe  | john@gmail.com    |
| Jane Doe  | jane@gmail.com    |

---

## GitHub exclusives

There are a few features that markdown files only display if you upload them to a GitHub.

### ReadMe Naming

If the file is saved as README.md and then uploaded to
GitHub it gets displayed automatically in the dashboard underneath the list of all files within the repository.

### Task lists

In GitHub this list will be displayed with clickable blocks.

<!-- Task Lists -->
<!-- Same syntax as the other lists. -->

* [x] Task 1 read this file to the end
* [ ] Task 2 rename it to README.md and upload it to a GitHub
* [ ] Task 3 check the remaining boxes

Thanks for reading.

---
