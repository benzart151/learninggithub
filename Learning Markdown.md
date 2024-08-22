Learning Markdown
==============================================================

<br>
<br>

Code
-------------------------------------------------------------------------------------------------
Put the tic markes on either side of a word or line to make `code`
```
`code`
```

Or create a code block withe three tic marks before at the beginning and end of all lines.
```
	```
	<!DOCTYPE html>
	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Document</title>
	</head>
	<body>
	
	</body>
	</html>
	```
```

<br>
<br>

Headings
-------------------
# Headline Level 1 
*(One hashtag at the beggining of the line creates Headline Level 1)*
```
# Headline Level 1
```

Also Headline Level 1 
=
*(Headline Level 1 can also be created by putting = signes on the next line)*

```
Also Headline Level 1
=
```

## Headline Level 2 
*(Two hashtags at the geginning of the line creates headline Level 2)*
```
## Headline Level 2
```

Also Headline Level 2
-
*(Putting dashes on the next line also creates a level 2 headline)*
```
Also Headline Level 2
-
```

The rest of the headlines have the corrosponding number of hashmarks at the beginning.
```
### Headline Level 3
#### Headline Level 4
##### Headline Level 5
###### Headline Level 6
```
### Headline Level 3
#### Headline Level 4
##### Headline Level 5
###### Headline Level 6

<br>
<br>

Special Styles
--------------------
Double astrics before and after a word makes it `**bold**` **bold** <br>
Double underscores befrore and after a word makes it `__bold__`  __bold__<br>
Single astrics before and after a word makes it `*italic*` *italic*<br>
Single underscores before and after a word makes it `_italic_`  _italic_<br>
In GitHub Mardown double tilda's before and after words makes them <br>`~~Strike Through~~` ~~Strike Through~~

`> A greater than sign before a paragraph makes it block quotes`
>This is a block quot
dont' forget to vote
or you'll end up in a mote

Horizontal Rules can be created with the followin code each line needs to proceded and followed by a blank line to make it work correctly.*<br>

`--- Three hyphens` 

---

`*** Three Asterisks`

***

`___ Three Underscores`

___

<br>
<br>

Lists
-------------------------
The following characters at the beginning of the lin make unordered lists
```
- Hyphens
* Asterisks
+ Plus Signs
```
- Hyphens
* Asterisks
+ Plus Signs

For ordered lists put a number followed by a period at the beginning of the lin. For unordered sublists tab the next line and put an asterisk at the beginning of the line. *The numbers do not have to be in order and they will still be ordered in the output.*
```
1. First Ordered List Item
	* Unordered sub-list.
1. Numbers don't really matter
```

1. First Ordered List Item
	* Unordered sub-list.
1. Numbers don't really matter

<br>
<br>

Links
--------------------------------
URLs are automatically made clickable
https://www.linkedin.com 

* Putting a word in brackets tells the previewer that this is link i.e. [Wetsite]
* Then putting the URL in parenthesis tells the previewer where the link goes
* Putting the title in quotes after the URL in quotes causes the shows the title when you hover over the text in brackets
```
[Website](https://www.linkedin.com "LinkedIn") 
```
[Website](https://www.linkedin.com "LinkedIn")

<br>

* A link can also be specified later by putting the word to be linked in brackets
* Then specifying where the link goes later in the document
```
[LinkedIn]
[linkedin]: https://www.linkedin.com
```
[LinkedIn]

* Another Way to do specify a link later is to put the word to be linked in brackets
* The put a number in brackets after the word
* And use the number in brackets and a : later in the doucment to specify where the link points.
```
[Learning][1]
[1]: https://www.linkedin.com/learning
```
[Learning][1] This is another method of specifying the link below see line 51

[linkedin]: https://www.linkedin.com
[1]: https://www.linkedin.com/learning

<br>
<br>

Images
---------------------------------------------------
The 1st way to link an image is to put the reference in brackets with an exclamation point at the beginning. The put the URL to the image in parenthasis.
```
![Tomolor](https://pixelprowess.com/i/stargazers/tomolor.png) 
```

![Tomolor](https://pixelprowess.com/i/stargazers/tomolor.png) 

The 2nd way to link an image is to put the reference in brackets with an exclamation point at the beginning<br>
`![Tomolor]` Reference<br>
<br>
Then put the reference in brackets followed by a colon and then the URL somewhere else in the document<br>
`[Tomolor]: https://pixelprowess.com/i/stargazers/tomolor.png` Image URL

![Tomolor]
	
	
[Tomolor]: https://pixelprowess.com/i/stargazers/tomolor.png

	

To create an image that is also a link, the image reference and image address are surrounded by brackets followed by the link address which makes and image link.<br>	
`[![Tomolor](https://pixelprowess.com/i/stargazers/tomolor.png)](https://raybo.org)`<br>
* The 1st set of brackets contains an exclamation mark forllowed, by the bracketed image reference followed by the image URL in parentheses
* The closing bracket for the image and image URL is followed by the link URL in parentheses

[![Tomolor](https://pixelprowess.com/i/stargazers/tomolor.png)](https://raybo.org)
   
<br>
<br>


Markdown Additions (GFM) GitHub Flavored Markdown
-----------------------------------------------------------------------------------------------------
This is a footnote [^1] *Denoted by the code* `[^1]`<br>
This is another footnote [^2] *Denoted by the code* `[^2]`

The footnotes point to references as below. The footnotes always appear at the bottom, no matter where you put the references.
```
[^1]: My reference
[^2]: Another footnote
```

[^1]: My reference - clicking on footnote 1 points here
[^2]: Another footnote - clicking on footnote 2 points here

<br>
<br>

Tables
-------------------------------------------------------------------------------------------------------
* Tables are defined by the pipe symble  `| some text `<br>
* The top row are the headings.
* The second row defines the alignment.
	* Dashes on the second line defines a left aligned column `| ---- `<br>
	* Dashes with colons on both sides defines a ctner aligned column `| :----:`<br>
	* Dashes with a colon on the right side defines a right aligned column `| ----: `<br>
* Pipe symbols aren't necessary on the right and they do not need to be aligned, however it looks nicer and is standard practice to align everything and put a pipe symbol on both sides.
```
| Left  | Center | Right   |
| ----  | :----: | ------: |
| One   | Two    | $1.00   |
| Three | Four   | $120.00 |
| Five  | Six    | $.99    |
```
<br>

| Left  | Center | Right   |
| ----  | :----: | ------: |
| One   | Two    | $1.00   |
| Three | Four   | $120.00 |
| Five  | Six    | $.99    |

<br>
<br>

Task List
------------------

Your create task lists by starting wiht a dash ` - [ ]` and putting opening and closing brackets with a space between them. If you put an x between the brackets the task will be checked off, if there is no x the task will be blank. You creating sub tasks by tabbing the line of tasks after the main line. In some previewers the tasks will be checkable and moveable.

```
- [x] Task 1
	- [ ] Task 1 - Subtask 1
	- [ ] Task 1 - Subtask 2
- [ ] Task 2
```

- [x] Task 1
	- [ ] Task 1 - Subtask 1
	- [ ] Task 1 - Subtask 2
- [ ] Task 2

<br>
<br>

HTML
---------------

HTML Can be added with the `<details>` tag, and just about any kind of html inside of that tag.

```html
	<details>
	<summary>collapsed</summary>
	<h2>Header</h2>
	<p>This is the copy for the collapsed text.</p>
	</details>
```

The text is colapsed in teh example of the above code below.

<details>
<summary>collapsed</summary>
<h2>Header</h2>
<p>This is the copy for the collapsed text.</p>
</details>

<br>
<br>

Drag/Drop/Paste
---------------

The following file types can be dragg and dropped or pasted.<br>
`.png` `.gif` `.jpg` `.jpeg` `.svg` `.log` `.docx` `.pptx` `.xlsx` `.txt` `.pdf` `.zip` `.gz` `.tgz` `.mp4` `.webm`

#and @mentions
-------------
In a pull request @ lists the people on the project # lists all the issues or open pull requests.<br>
The `:` sign will list emojis available for that editor.<br>
Putting a hexadecimal number inside of tic marks will give a preview of the color in a pull request. <br>
There are some other features of Markdown that work on pull requests but not in the markdown file.

Disallowed Raw HTML
-------------------
`<title>` `<textarea>` `<style>` `<xmp>` `<iframe>` `<noembed>` `<noframes>` `<script>` `<plaintext>`

	
	
