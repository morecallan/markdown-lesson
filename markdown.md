# What is Markdown?

> Markdown is a lightweight markup language with plain text formatting syntax designed so that it can be converted to HTML and many other formats using a tool by the same name. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

> Note: GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

<hr>

# Markdown Basics

### Headers
<!-- ###### h6
##### h5
#### h4
### h3
## h2
# h1 -->



### Lists
  - ###### Ordered List

1. Dogs
1. Cats
1. Frogs


  - ###### Unordered List

- Banana
- Apple
- Celery

  - ###### List with sublists

1. Dog
  - Dog food
  - Toys
  - Friends
1. Cat
  - No friends
    - Maybe one friend

### Links
[This is how you link.](https://www.google.com/webhp?sourceid=chrome-instant&rlz=1C5CHFA_enUS729US730&ion=1&espv=2&ie=UTF-8#q=linking+in+markdown)

[SpaceJam](https://www.google.com)

### Images
<!-- ![Zoe Image](./lolzoe.jpg) -->
![Zoe Thinks She's Cool](./lolzoe.jpg)

### Code
`var friend = "x";`

```
var friend = "x";
var friend = "x";
var friend = "x";

for (var i = 0; i < zoe.cool; i++) {
  //something
}
```

### Comments
<!-- this is a comment -->

### Bold and Italics
*this is italics*

**this is bold**

_this is underscore_

### More Advanced Topics
[Task lists, Syntax Highlighting,  Tables, Username Mentions, Emojis(:metal:)](https://guides.github.com/features/mastering-markdown/#)

<hr>

# Viewing Your Markdown
### Sublime
1. Use <kbd>cmd</kbd>+<kbd>shift</kbd>+<kbd>P</kbd> then Package Control: Install Package
1. Look for `Markdown Preview` and install it.
1. Run with command
  - Run <kbd>cmd</kbd>+<kbd>shift</kbd>+<kbd>P</kbd> then `Markdown Preview` to show the follow commands (you will be prompted to select which parser you prefer)
	- Markdown Preview: Preview in Browser

### Atom
1. Run with command
  - <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>m</kbd>


<hr>


# Adding an image source via Github
1. New branch
1. Add image to project
1. Merge to master
1. Navigate to image on github
1. Click the "raw" icon in top right. ![Raw Icon]()
1. Use the URL at the top of the page to reference the image. **Make sure it has the words "raw" & "master" in the link.**

<hr>

# Resources
- [Mastering Markdown - Github](https://guides.github.com/features/mastering-markdown/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Why Markdown](http://brettterpstra.com/2011/08/31/why-markdown-a-two-minute-explanation/)
