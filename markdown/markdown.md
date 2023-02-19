# **The Markdown Guide - Matt Cone**

## **Headings**

*You should also put blank lines before and after a heading for compatibility.*

# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6

## **Paragraphs**

*To create paragraphs, use a blank line to separate one or more lines of text.  
Don't put tabs or spaces in front of your paragraphs.*

I really like using Markdown

I think I'll use it from now.

## **Line Breaks**

*To create a line break, end a line with two or more spaces, and then type.*

This is the first line.  
And this is the second line.

## **Emphasis**

### **Bold**

*To bold text, add two asterisks or underscores before and after a word or phrase.
To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.*

I love **bold text**.  
I love **bold text**.  
Love**is**bold

### **Italic**

*To italicize text, add one asterisk or underscore before and after a word or phrase.  
To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.*

The *cat's meow*  
The *cat's meow.*

A*cat*meow.

### **Bold and Italic**

*To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase.  
To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.*

***Important*** text.  
_**Important**_ text.

Really***very***important text.

## **Blockquotes**

*To create a blockquote, add a > in front of a paragraph.  
For compatibility, put blank lines before and after blockquotes.*

> Dorothy followed her through many rooms.

### **Blockquotes with Multiple Paragraphs**

*Blockquotes can contain multiple paragraphs. Add a > on the blank lines between the paragraphs.*

> This is the first paragraph.
>
> This is the second paragraph.

### **Nested Blockquotes**

*Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.*

> This is the first paragraph.
>
> > And this is the nested paragraph.

### **Blockquotes with Other Elements**

*Blockquotes can contain other Markdown formatted elements. Not all elements can be used — you’ll need to experiment to see which ones work.*

>##### The quarterly results look great
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> *Everything* is going **well**.

## **Lists**

*You can organize items into ordered and unordered lists.*

### **Ordered Lists**

*To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.*

1. First item
2. Second item
3. Third item
4. Fourth item

### **Unordered Lists**

*To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items.*

- First item
- Second item
- Third item
- Fourth item
  
- First item
- Second item
- Third item
- Fourth item

- First item
- Second item
- Third item
- Fourth item

### **Starting Unordered List Items With Numbers**

*If you need to start an unordered list item with a number followed by a period, you can use a backslash (\) to escape the period.*

- 1968\. A great year!
- I think 1969 was second best.
  
### **Nesting List items**

*To nest line items in an ordered list, indent the items four spaces or one tab.*

1. First item
2. Second item
3. Third item
   1. Indented item
   2. Indented item
4. Fourth item

*To nest line items in an unordered list, indent the items four spaces or one tab.*

- First item
- Second item
- Third item
  - Indented item
  - Indented item
- Fourth item

### **Adding Elements in Lists**

*To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.*

#### **Paragraphs**

- This is the first list item.
- Here's is the second list item.

    I need to add another paragraph below the second list item.
- And here's the third list item

#### **Blockquotes**

- This is the first list item.
- Here's is the second list item.
    > A blockquote would look great here.
- And here's the third list item

#### **Code Blocks**

*Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.*

1. Open the file.
2. Find the following code block on line 21:

        <html>
            <head>
                <title>Test</title>
            </head>

3. Update the title to match the name of your website.

#### **Lists**

*You can nest an unordered list in an ordered list, or vice versa.*

1. First item
2. Second item
3. Thied item
    - Indented item
    - Indented item
4. Fourth item

## **Code**

*To denote a word or phrase as code, enclose it in backticks (`).*

At the command prompt, type `nano`.

### **Escaping Backticks**

*If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks.*

``Use `code` in your Markdown file.``

### **Code Blocks**

*To create code blocks, indent every line of the block by at least four spaces or one
tab.*

 <html>
     <head>
    </head>
</html>

## **Horizontal Rules**

*To create a horizontal rule, use three or more asterisks (***), dashes (---), or
underscores (___) on a line by hemselves.*

***

---

___

## **Links**

*To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (<https://duckduckgo.com>)).*

Use [Duck Duck Go](https://duckduckgo.com).  
Use [ProgramozásKarrier.hu](https://programozaskarrier.hu).

*Markdown applications don’t agree on how to handle spaces in the middle of a URL.
For compatibility, try to URL encode any spaces with %20.*

[Link](https://www.I%20am%20tired.com "I am tired!")

### **Adding Titles**

*You can optionally add a title for a link. This will appear as a tooltip when the user
hovers over the link. To add a title, enclose it in parentheses after the URL.*

Use [Duck Duck Go](https://duckduckgo.com "My search engine!").  
Use [ProgramozásKarrier.hu](https://programozaskarrier.hu "I study here").

### **URLs and Email Addresses**

*To quickly turn a URL or email address into a link, enclose it in angle brackets.*

<https://eff.org>  
<fake@example.com>

### **Formatting Links**

*To emphasize links, add asterisks before and after the brackets and parentheses. To
denote links as code, add backticks in the brackets.*

I am a big **[Queen](https://www.queenonline.com "The best band ever!!!")** fan.  
*[Rush](https://www.rush.com "2112") is also very good.*  
It's an important [`code`](#code)

### **Reference-style Links**

*Reference-style links are a special kind of link that make URLs easier to display and
read in Markdown. Reference-style links are constructed in two parts: the part you
keep inline with your text and the part you store somewhere else in the file to keep
the text easy to read.*

#### **Formatting the First Part of the Link**

*The first part of a reference-style link is formatted with two sets of brackets. The
first set of brackets surrounds the text that should appear linked. The second set of
brackets displays a label used to point to the link you’re storing elsewhere in your
document.  
Although not required, you can include a space between the first and second set of
brackets. Also, the label in the second set of brackets is not case sensitive and can
include letters, numbers, spaces, or punctuation.*

- [Roger Taylor] [1]

#### **Formatting the Second Part of the Link**

1. The label, in brackets, followed immediately by a colon and at least one space
(e.g., [label]: ).
2. The URL for the link, which you can optionally enclose in angle brackets.
3. The optional title for the link, which you can enclose in double quotes, single
quotes, or parentheses.

My favorite drummer is [Roger Taylor].

## **Images**

*To add an image, add an exclamation mark (!), followed by alt text in brackets, and
the path or URL to the image asset in parentheses. You can optionally add a title after the URL in the parentheses.*

![Muse is great!](https://starity.hu/images/articles/800x600/dalpremier-muse-mercy-05190839.jpg "MUSE")

### **Linking Images**

*To add a link to an image, enclose the Markdown for the image in brackets, and then
add the link in parentheses.*

[![Muse is great!](https://starity.hu/images/articles/800x600/dalpremier-muse-mercy-05190839.jpg)

## **Escaping Characters**

*To display a literal character that would otherwise be used to format text in a
Markdown document, add a backslash (\) in front of the character.*

- List  
/*

### **Characters You Can Escape**

*You can use a backslash to escape the following characters.*

## **HTML**

*Many Markdown applications allow you to use HTML tags in Markdown-formatted
text. This is helpful if you prefer certain HTML tags to Markdown syntax. For
example, some people find it easier to use HTML tags for images. Using HTML is
also helpful when you need to change the attributes of an element, like specifying
the color of text or changing the width of an image.  
To use HTML, place the tags in the text of your Markdown-formatted file.*

This **word** is bold. This <em>word</em> is italic.

## **Tables**

*To add a table, use three or more hyphens (---) to create each column’s header, and
use pipes (|) to separate each column. For compatibility, you should also add a pipe
on either end of the row.*

| Name              | Band          |  
| ---               | ---           |
| Roger Taylor      | Queen         |
| Neil Peart        | Rush          |

### **Alignment**

*You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.*

| Name              | Band          |  
| :---:             | ---:          |
| Roger Taylor      | Queen         |
| Neil Peart        | Rush          |

### **Formatting Text in Tables**

*You can format the text within tables. For example, you can add links, code (words
or phrases in backticks (`) only, not code blocks), and emphasis.
You can’t add headings, blockquotes, lists, horizontal rules, images, or HTML tags.*

### **Escaping Pipe Characters in Tables**

*You can display a pipe (|) character in a table by using its HTML character code
(\&#124;).*

## **Fenced Code Blocks**

*Depending on your Markdown processor or editor, you’ll use three backticks (```)
or three tildes (∼∼∼) on the lines before and after the code block.*

~~~
{
    "firstName": "John",
    "lastName": "Deacon",
    "age": 25
}
~~~

### **Syntax Highlighting**

*Many Markdown processors support syntax highlighting for fenced code blocks. This
feature allows you to add color highlighting for whatever language your code was
written in. To add syntax highlighting, specify a language next to the backticks before the fenced code block.*

~~~json
{
    "firstName": "John",
    "lastName": "Deacon",
    "age": 25
}
~~~

## **Footnotes**

*Footnotes allow you to add notes and references without cluttering the body of the
document. When you create a footnote, a superscript number with a link appears
where you added the footnote reference. Readers can click the link to jump to the
content of the footnote at the bottom of the page.*  

*To create a footnote reference, add a caret and an identifier inside brackets ([^1]).
Identifiers can be numbers or words, but they can’t contain spaces or tabs. Identifiers
only correlate the footnote reference with the footnote itself — in the output,
footnotes are numbered sequentially.*

*Add the footnote using another caret and number inside brackets with a colon
and text ([^1]: My footnote.). You don’t have to put footnotes at the end of the
document. You can put them anywhere except inside other elements like lists, block
quotes, and tables.*

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.  

[^bignote]: Here's one with multiple paragraphs and code.

## **Heading IDs**

*Many Markdown processors support custom IDs for headings — some Markdown
processors automatically add them. Adding custom IDs allows you to link directly
to headings and modify them with CSS. To add a custom heading ID, enclose the
custom ID in curly braces on the same line as the heading.*

### My Great Heading {#custom-id}

### **Linking to Heading IDs**

*You can link to headings with custom IDs in the file by creating a standard link with
a number sign (#) followed by the custom heading ID.*

[Heading Ids](#heading-ids)

## **Definition Lists**

*Some Markdown processors allow you to create definition lists of terms and their
corresponding definitions. To create a definition list, type the term on the first line. On the next line, type a colon followed by a space and the definition.*

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

## **Strikethrough**

*You can “strikethrough” words by putting a horizontal line through the center of
them. This feature allows you to indicate that certain words are a mistake not meant
for inclusion in the document. To strikethrough words, use two tilde symbols (∼∼) before and after the words.*

The world is ~~flat~~ round.

## **Task Lists**

*Task lists allow you to create a list of items with checkboxes. In Markdown
applications that support task lists, checkboxes will be displayed next to the content.
To create a task list, add dashes (-) and brackets with a space ([ ]) in front of task
list items. To select a checkbox, add an x in between the brackets ([x]).*

- [x] Markdown
- [ ] GitHub Video
- [ ] HTML

## **Emoji**

*There are two ways to add emoji to Markdown files: copy and paste the emoji into
your Markdown-formatted text, or type emoji shortcodes.*

### **Copying and Pasting Emoji**

*In most cases, you can simply copy an emoji from a source like Emojipedia and paste
it into your document. Many Markdown applications will automatically display the
emoji in the Markdown-formatted text. The HTML and PDF files you export from
your Markdown application should display the emoji.*

## **Using Emoji Shortcodes**

*Some Markdown applications allow you to insert emoji by typing emoji shortcodes.
These begin and end with a colon and include the name of an emoji.*

Gone camping! :tent: Be back soon.

That is so funny! :joy:

## **Automatic URL Linking**

*Many Markdown processors automatically turn URLs into links. That means if you
type <http://www.example.com>, your Markdown processor will automatically turn it
into a link even though you haven’t used brackets.*

<https://www.queenonline.com>

### **Disabling Automatic URL Linking**

*If you don’t want a URL to be automatically linked, you can remove the link by
denoting the URL as code with backticks.*

`https://www.queenonline.com`
