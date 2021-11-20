# This is a markdown file cheat sheet.

<!-- Headings -->
## 1. Headings
```
  # Heading 1

  ## Heading 2

  ### Heading 3

  #### Heading 4

  ##### Heading 5

  ###### Heading 6
```
>Best Practices: 
>
>Need a blank line on top of the heading.
>
>And a space after the hashtag.

---

## 2. Italic, Strong and strike through

### 2.1 Italic

```
  *This text* is italic.
```
 *This text* is italic.  

```
  _This text_ is also italic.
```
_This text_ is also italic

### 2.2 Strong 

```
  **This text** is strong
```
**This text** is strong.

```
  __This text__ is also strong.
```
__This text__ is also strong.

### 2.3 Strong and Italic

```
  ***This text*** is strong and italic.
```
***This text*** is strong and italic.

>Best Practices:
>
>Try to use *, **, *** to italic or strong the word. 
>
>Since underscore (_) doesn't work in the middle of a word.

### 2.4 Strike through
```
  ~~This text~~ is strike through.
```
~~This word~~ is strike through.

---

## 3. Horizontal Rule

### 3.1 Three underscores
```
  ___ 
```
```markdown
  ___
```
### 3.2 Three stars
```
  ***
```
***

### 3.3 Three dashes
```
  ---
```
---

## Blockquote
<!-- Blockquote -->
> This is a quote.
>
>>This is a nested quote.
>>
>>>This is a nested quote in a nested quote.

<!-- Blockquotes with Other Elements  -->
> ### The result looks great!
>
> - Item 1
> - Item 2
> - Item 3
>
> *Everything* is going to **be** ***great***.

>Best Practices:
>
>Separate different phases by adding one more > sign.
>
>Example:
>
>\>Best Practices:
>\
>\>
>\
>\>This is another paragraph.

## Links
<!-- Links -->
### Normal Link
[My Website](https://devkaiyang.com 'Kaiyang Li\'s website')

### Email Link
<fake@example.com>

<https://www.markdownguide.org>

### Link with reference style
<!-- Links with reference style -->
[My website][1]

[1]:https://devkaiyang.com "My website"

### Image
<!-- Images -->
![Markdown Logo](https://markdown-here.com/img/icon256.png 'This is a markdown logo') 


### Image with link
To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

[![An old rock in the desert](https://picsum.photos/200/300 "random 200x300 pictures from picsum")](https://picsum.photos/200/300)

### Link to Heading IDs
```markdown
  ### My Great Heading {#custom-id}

  [Heading ID](#heading-id)
```
## Lists

### Unordered List
<!-- UL -->
* Item 1
* Item 2
* Item 3
  + Nested Item 3.1
  + Nested Item 3.2
  + Nested Item 3.3
- Item 4
- Item 5
- Item 6  

### Ordered List
<!-- OL -->
1. Item 1
2. Item 2
3. Item 3

>Best Practices:
>
>To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.
>
>```markdown
>  * This is the first list item.
>  * Here's the second list item.
>
>    I need to add another paragraph below the second list item.
>
>  * And here's the third list item.
>```

## Code blocks

### Inline code blocks
<!-- Inline Code Block -->
This is a sentence. `<p>This is a p tag</p>` This is another sentence.

normal code
<!-- Code Blocks -->
```
  npm install

  npm start
```

javascript code
```javascript
  function add(num1, num2){
    return num1 + num2;
  }
```

python code
```python
  def add(num1,num2):
    return num1 + num2
```

## Tables 
<!-- Tables -->
|  Name   | Age   | Gender  |
| :---    | :---: |    ---: | 
| Smith   |  23   | Male    |
| John    | 34    | Male    |

## Task Lists 
<!-- Task Lists -->
* [X] Task List 1
* [x] Task List 2
* []  Task List 3

## Footnotes
<!-- Footnotes -->
Here's a simple footnote[^1], and here's a longer one[^bignote].

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code .

  Indent paragraphs to include them in the footnote.

    `{ my code }`
  
  Add as many paragraphs as you want.
