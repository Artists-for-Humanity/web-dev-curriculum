

# 🏆  **Goals:** 
- ⭐️ learn basic HTML tags (H1, H2, H3, p, li, ul, img, src, href)
- ⭐️ connect css files and manipulate styling (classes/ names)

**These 3 languages are key for Web Developers:**

- <span style = "color:#FFC857"> **HTML** </span> to define the content of web pages
- <span style = "color:lightblue">**CSS** </span>to specify the layout of web pages
- <span style = "color:#B23A48">**JavaScript** </span>to program the behavior of web pages

<br/>

# **Focusing on <span style = "color:#FFC857"> HTML</span>  :**

> HTML stands for Hyper Text Markup Language, and is the standard markup language used to crete website
 We use **Tags** to describe the elements of the page

#### Some of the most common tags include:

- The <span style="color:white; background-color:gray;padding:3px; border-radius:4px; "> body</span> tag is used to encompass most content in the HTML file 

- The  <span style="color:white; background-color:gray;padding:3px; border-radius:4px; "> title</span> tag refrs to a title 

- The <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">p</span> tag refers to "paragraph" and is used to hold any long piece of text 

- The <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">H1</span> tag refers to Header 1, the <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">H2</span> tag refers to Header 2, and finally <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">H3</span> tag refers to Header 3. These are often used to style your text into various headers and subheaders depending on the developers needs

-  The <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">link</span> tag refers to a external site

- The <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">image</span> tag allows you to add images to your site, it's often used with the <span style="color:black; background-color:lightblue ;padding:2px; border-radius:4px; "> src=""</span> attribute to find the image in your project 

- The <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">image</span> li </span> and  <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">ul </span> tags allow you to make list an dunordered list. This is good to ctreat bullets within your site listing out information

- lasty we have the <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">image</span> often used with the <span style="color:black; background-color:lightblue ;padding:2px; border-radius:4px; ">href=""</span> attribute that allows you to link elements of your site to other pages on your own site as well as other websites on the internet



#### Every one of these must be used with an **"opening"** and **"closing"** tag. These are made with the `<` (greater than) and `>` (less than symbols). The "closing" tag uses a `/` (slash) character as well.

####  ➡️ **Open up <span style= "color:#FFC857"> **lesson2pt1.html** </span> and click the "Go Live" button on the bottom right of your VS code**


<br/>

# **Focusing on <span style = "color:lightblue"> CSS </span> :**

> CSS stands for Cascading Style Sheets, and describes how HTML elements are to be displayed on screen, paper, or in other media

To use CSS you need a **selector** and **declaration**, a declaration is usally made up of **property** and a **value**. Say you want to edit your H1 tag and make it big and red. Your selector would be `h1` and the declaration would be "making it red". This can be done using the property of `color` and giving it the value of `red`

The syntax would look something like this...
~~~ html

<H1> This is my H1 </H1>

<style>

h1 {
    color:red
}

</style>

~~~

You can add <span style = "text-decoration: underline; color:white; padding:2px; border-radius:6px; margin-left:5px; margin-right:5px"> inline styles </span> like we see above. This is where we house all our styles in between two style tags. This works but it can make a file very long and hard to read.
It's best practice to separate your styling into a separate file usally called something like <span style="color:lightblue">**styles.css**</span>

These two files need to be able to communicate so we use link them using the <span style="color:white; background-color:gray;padding:3px; border-radius:4px; ">link</span> tag 
``` html
 <link rel="stylesheet" href="lesson2.css" type="text/css" />
```
In the **Lesson 2** folder open up <span style="color:#FFC857"> **lesson2pt2** </span> and <span style="color:lightblue"> **lesson2.css** </span>  side by side, see if you can tell what each element might look like based on the styles

####   ➡️   **Open up <span style= "color:#FFC857"> **lesson2pt2.html** </span> and click the "Go Live" button on the bottom right of your VS code, see how <span style= "color:lightblue"> **lesson2.css** </span> effects the page**













