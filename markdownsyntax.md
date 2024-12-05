# Basic Markdown Syntax

> You will need either a GitHub repository or some other service to host your Markdown pages

[Return to Homepage](README.md)

---

# Headers

For headers, you put a '#' for the number header you want and a space before the text you want to be a header.

Header 1 | # *Text you want*
# Header 1

Header 2 | ## *Text you want*
## Header 2

Header 3 | ### *Text you want*
### Header 3

Header 4 | #### *Text you want*
#### Header 4

Header 5 | ##### *Text you want*
##### Header 5

Header 6 | ###### *Text you want*
###### Header 6

# Paragraphs

Paragraphs are quite simple in Markdown, you just type it out! 

Here are some neat features you can use with paragraphs:

#### Line Breaks

You can start a new line by either:  
Ending a line with two spaces

Or leaving an empty line between your text.

#### Bold and Italics

You can make text *bold* by surrounding it with asterisks (\*)  
And you can make text _italiccized_ by surrounding it with underscores (\_)  
And you can do ***both*** by surrounding it with three asterisks (\***)  

#### Lists

There are two kinds of lists, ordered and unordered.

##### Ordered

For ordered lists, you just need to start the entries with a 1., 2., and so on. If you need a subitem, you add an indent (or four spaces) and start back at 1.
1. First item
2. Second item
3. Third item
    1. Indented item
5. Fourth item

You start every item with a dash (\-) for unordered lists. Same rule for indents.
- First item
- Second item
    - Indented item
- Third item

#### Links

You can create links to another page by putting the text you want the link to show up as in brackets [], and the link itself next to it in parentheses.  
\[Linked text](link)

For example, if you want an easy access Markdown cheat sheet, you can go to [the following link](https://www.markdownguide.org/cheat-sheet/)

#### Images

Images are very similar to links, except you need to have an excalmation point (!) at the beginning.  
\!\[Alt text incase the image doesn't load](link to image)

You can either link to an image already hosted on the web, or if you have images hosted in your repository you can put the file path.  
For example, I have a folder where I have stored the pictures for this tutorial, so if I put mdghTutorialPictures/_picturename_ in parentheses I can link to any image in there.  
You can also use this method to link to other Markdown pages on your repository.
