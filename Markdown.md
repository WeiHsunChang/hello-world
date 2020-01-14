# How-To-Markdown


# Headings
```
# h1
## h2
### h3
#### h4
##### h5
###### h6

使用下劃線來表示H1和H2
Alt-h1
===
Alt-h2
---
```
# h1
## h2
### h3
#### h4
##### h5
###### h6

Alt-h1
===
Alt-h2
---

# Emphasis
```
*italic*
**bold**
_**combined**_
```
*italic*
**bold**
_**combined**_

### draw line through the text
`~~this line~~`
~~this line~~


# lists

### unordered list
```
- item1
- item2
- item3
```
- item1
- item2
- item3

### nested list
```
add tab or full-space
- One
    - 1.1
    - 1.2
- Two
- Three
```
- One
    - 1.1
    - 1.2
- Two
- Three


# links

### the easiest way
`http://google.com`
http://google.com

### Inline-style
`[Google Homepage](http://google.com "Here is alt")`
[Google Homepage](http://google.com "Here is alt")

### Reference-style
```
[NodeSchool Site][ref]
[GitHub][1]
[W3Schools]
[how-to-markdown] is a workshopper that teaches you how to write Markdown.

[ref]: http://nodeschool.io
[1]: http://github.com/
[W3Schools]: https://www.w3schools.com
[how-to-markdown]: //git.io/how-to-markdown
```
[NodeSchool Site][ref]
[GitHub][1]
[W3Schools]
[how-to-markdown] is a workshopper that teaches you how to write Markdown.

[ref]: http://nodeschool.io
[1]: http://github.com/
[W3Schools]: https://www.w3schools.com
[how-to-markdown]: //git.io/how-to-markdown


# images
` ![Markdown logo](http://bit.do/how-to-markdown)`
 ![Markdown logo](http://bit.do/how-to-markdown)
 
# Blockquotes
```
> To be, or not to be, that is the question.
> William Shakespeare
```
> To be, or not to be, that is the question.
> William Shakespeare 

# Code

### Inline code
type back-ticks
```
`<code>`
```

`<code>`

### Blocks of code
type three back-ticks
```
    ```
    console.log(1)
    ```
```


```
console.log(1)
```
#### Syntax highlighting
need to indicate what language do you use

```
    ```javascript
    console.log(1)
    ```
```

```javascript
console.log(1)
```


# Tables
```
| left-align | centered | right-align |
| :--------- | :-------:| ----------: |
| line 1     | line 1   | line 1      |
| line 2     | line 2   | line 2      |
| line 3     | line 3   | line 3      |
```
| left-align | centered | right-align |
| :--------- | :-------:| ----------: |
| line 1     | line 1   | line 1      |
| line 2     | line 2   | line 2      |
| line 3     | line 3   | line 3      |


* There must be at least 3 dashes separating each header cell. Colons to align columns count as dashes.
* The outer pipes (|) are optional.
* You can use inline Markdown in cells.
    ```
    | Markdown | `renders` | blank   |
    | -------- | --------- | ------- |
    | *italic* | **bold** | _**combined**_ |
    ```
    | Markdown | `renders` | blank   |
    | -------- | --------- | ------- |
    | *italic* | **bold** | _**combined**_ |


# Horizontal rules
type three or more dashes (-), asterisks (*) or underscores (_)

---
***
___


# GFM(GitHub Flavored Markdown)
> GitHub uses its own version of the Markdown syntax that provides an additional set of useful features.
### Task lists
- [ ]  Checkbox
- [x]  An x between them makes the item marked as completed.





