# Intro to MarkDown

Markdown is a plain text formatting syntax aimed at making writing for the internet easier. The philosophy behind Markdown is that plain text documents should be readable without tags mussing everything up, but there should still be ways to add text modifiers like lists, bold, italics, etc. It is an alternative to WYSIWYG (what you see is what you get) editors, which use rich text that later gets converted to proper HTML.
***

## Why and where we can use MarkDown 

Markdown can be used for everything. People use it to CREATE:

- Websites
- Notes
- Books
- Presentations
- Technical documentation

Markdown is portable. Files containing Markdown-formatted text can be opened using virtually any application
***
***
### In this Chapter we willg create a simple website using markdown syntax

**1. Open your visual studio and create a file index.md Inside your file create a Heading tag with text  hello world. The code to create a heading tag is below.**

`#Hello world, my name is Tanya`

**Output**
## Hello world, my name is Tanya. 

***
**2. Below the heading tag, create a paragragh with text descibing yourself. Find the syntax below to insert a paragragh.**

`Here more about me, subscribe and like on my social media platforms. Your support means a lot to me`

**Output**

Hear more about me, subscribe and like on my social media platforms. Your support means a lot to mE
***
 **3. Now insert an image of yourself with caption of your choice. Code to insert an image is below.**

`![Alt Myself](/Antonios.jpg)`

**Output**
### Meet Tanya

![Alt text](/Antonios.jpg)

***
**4. Create an ordered list of chores you do like or don't like doing at home,for chores you don't like strikethrough. Your list should be indented properly.**


`>>1. Chore1`

`>>2. Chore2`

`>>3. ~~Chore3~~`

**Output**

>>1. Cooking
>>2. Washing dishes
>>3. ~~Laundry~~
>>4. ~~Mopping floor~~
>>5. Ioning

***

**5. Create an unorder list of things you mostly do during hours, insert a heading tag with text "my daily task". An example of how you create list tags is below**

`- Task1`

`- Task2`

`- Task3`

**Output**
### My Daily Tasks
- Read email
- Read article online relating to tech
- Collaborate on creating the uncommon curriculum for the upcoming bootcamp
- Work on any ROI assignments


***

**6. Create an achor tag with italicized title of your social media platforms. The text should be  The code to insert links is below.**

`*<a href="https://tanyaradzwa20.github.io/MarkDown2/#myself" title="Facebook">*
an example</a>`

**Output**

*<a href="https://tanyaradzwa20.github.io/MarkDown2/#myself" title="Title">Facebook</a>*
*<a href="https://tanyaradzwa20.github.io/MarkDown2/#myself" title="Title">Instagram</a>*
*<a href="https://tanyaradzwa20.github.io/MarkDown2/#myself" title="Title">Tiktok</a>*

**7. Lastly insert copyright text wrapped in a `<p></p>` tag. To insert actual code in your markdown use the following code without the brackets.**

``(`<p>Copyright. all rights reserved</p>`)``

**Output**

`<p>Copyright. all rights reserved</p>`