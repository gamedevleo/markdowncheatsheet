# This is a markdown file cheat sheet.

<!-- Headings -->

## 1. Headings

```markdown
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6
```

> Best Practices:
>
> Need a blank line on top of the heading.
>
> And a space after the hashtag.

---

<br/>

## 2. Italic, Strong and strike through

### 2.1 Italic

```
  *This text* is italic.
```

_This text_ is italic.

```
  _This text_ is also italic.
```

_This text_ is also italic.

### 2.2 Strong

```
  **This text** is strong.
```

**This text** is strong.

```
  __This text__ is also strong.
```

**This text** is also strong.

### 2.3 Strong and Italic

```
  ***This text*** is strong and italic.
```

**_This text_** is strong and italic.

> Best Practices:
>
> Try to use *, **, *** to italic or strong the word.
>
> Since underscore (_) doesn't work in the middle of a word.

### 2.4 Strike through

```
  ~~This text~~ is strike through.
```

~~This text~~ is strike through.

---

## 3. Horizontal Rule

### 3.1 Three underscores

```
  ___
```

---

### 3.2 Three asterisks

```
  ***
```

---

### 3.3 Three dashes

```
  ---
```

---

<br/>

## 4. Blockquote

### 4.1 Normal blockquote

```
  > This is a blockquote
```

> This is a blockquote

### 4.2 Multiple lines blockquote

```
  > This is the first sentence of a blockquote.
  > This is the second sentence of a blockquote.
  > This is the third sentence of a blockquote.
  > This is the fourth sentence of a blockquote.
  > This is the fifth sentence of a blockquote.
  > This is the sixth sentence of a blockquote.
```

> This is the first sentence of a blockquote.
> This is the second sentence of a blockquote.
> This is the third sentence of a blockquote.
> This is the fourth sentence of a blockquote.
> This is the fifth sentence of a blockquote.
> This is the sixth sentence of a blockquote.

### 4.3 Multiple paragraphs blockquote

```
  > This is the first paragraph of a blockquote.
  >
  > This is the second paragraph of a blockquote.
  >
  > This is the third paragraph of a blockquote.
```

> This is the first paragraph of a blockquote.
>
> This is the second paragraph of a blockquote.
>
> This is the third paragraph of a blockquote.

### 4.4 Nested blockquote

```
  > This is a blockquote.
  >
  >>This is a nested blockquote.
  >>
  >>> This is a nested blockquote in a nested blockquote.
  >
  > To break the nested blockquote, add a space between lines.
```

> This is a blockquote.
>
> > This is a nested blockquote.
> >
> > > This is a nested blockquote in a nested blockquote.
>
> To break the nested blockquote, add a space between lines.

### 4.5 Blockquote with other elements

```
  > ### The result looks great!
  >
  > *Everything* is going to **be** ***great***.
```

> ### The result looks great!
>
> _Everything_ is going to **be** **_great_**.

---

<br/>

## 5. Links

### 5.1 Just a link

```
  <https://www.markdownguide.org>
```

<https://www.markdownguide.org>

### 5.2 Email Link

```
  <fake@example.com>
```

<fake@example.com>

### 5.3 Normal link

```
  [Google](https://google.com)
```

[Google](https://google.com)

### 5.4 Normal link with hover description

```
  [Google](https://google.com 'This is Google link')
```

[Google](https://google.com 'This is Google link')

### 5.5 Link with reference style

```
  [Google][1]

  [1]:https://google.com 'This is Google Link'
```

[Google][1]

[1]: https://google.com 'This is Google link'

### 5.6 Image with hover description

```markdown
![Markdown Logo](https://markdown-here.com/img/icon256.png 'This is a markdown logo')
```

![Markdown Logo](https://markdown-here.com/img/icon256.png 'This is a markdown logo')

### 5.7 Image with link

To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

```
  [![Random Picture](https://picsum.photos/300/300) 'random 300x300 pictures from picsum'](https://picsum.photos/300/300)
```

[![Random Picture](https://picsum.photos/300/300 'random 200x300 pictures from picsum')](https://picsum.photos/300/300)

### 5.8 Link to Heading IDs

```markdown
#### My Great Heading {#custom-id}

[Heading ID](#custom-id)
```

#### My great heading {#custom-id}

[Heading ID](#custom-id)

---

<br/>

## 6 Lists

### 6.1 Unordered list

#### 6.1.1 Unordered list using asterisks

```
  * Item 1
  * Item 2
  * Item 3
```

- Item 1
- Item 2
- Item 3

#### 6.1.2 Unordered list using dashes

```
  - Item 4
  - Item 5
  - Item 6
```

- Item 4
- Item 5
- Item 6

#### 6.1.3 Unordered list using plus sign

```
  + Item 7
  + Item 8
  + Item 9
```

- Item 7
- Item 8
- Item 9

> Best Practices:
>
> Markdown applications don’t agree on how to handle different delimiters in the same list. For compatibility, don’t mix and match delimiters in the same list — pick one and stick with it.
>
> Best Practices:
>
> To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.
>
> ```markdown
> - This is the first list item.
>
> - Here's the second list item.
>
>   I need to add another paragraph below the second list item.
>
> - And here's the third list item.
> ```

### 6.2 Ordered List

```
  1. Item 1
  2. Item 2
  3. Item 3
```

1. Item 1
2. Item 2
3. Item 3

### 6.3 Task Lists

```
  - [x] Task List 1
  - [x] Task List 2
  - [ ] Task List 3
```

- [x] Task List 1
- [x] Task List 2
- [ ] Task List 3

---

<br/>

## 7 Code blocks

### 7.1 Inline code block

```
  This is a sentence. `<p>This a p tag</p>` This is another sentence.
```

This is a sentence. `<p>This is a p tag</p>` This is another sentence.

### 7.2 Normal code block

````
  ```
    npm install

    npm start
  ```
````


```
  npm install

  npm start
```

### 7.2 Specific language code block

For specific language code block just add the language name after ` ``` ` sign. There are several examples down below.

javascript code

````
  ```javascript
    function add(num1, num2) {
      return num1 + num2;
    }
  ```
````

result

```javascript
function add(num1, num2) {
  return num1 + num2;
}
```

jsx code

````
  ```jsx
    <h1 className='heading-one'>I am a heading 1</h1>
    <p className='paragraph'>I am a paragraph</p>
  ```
````

```jsx
    <h1 className='heading-one'>I am a heading 1</h1>
    <p className='paragraph'>I am a paragraph</p>
```

---

<br/>

## 8 Tables

### 8.1 Normal table

```
  |  Name  |  Age  |  Gender |
  |  ---   |  ---  |   ---   |
  |  kay   |  23   |   male  |
  |  John  |  30   |   male  |
```

| Name | Age | Gender |
| ---- | --- | ------ |
| kay  | 23  | male   |
| John | 30  | male   |

### 8.2 Table with alignment

```
  | Name | Age | Gender |
  |:---- |:---:| -----: |
  | kay  | 23  | male   |
  | John | 30  | male   |
```

| Name | Age | Gender |
| :--- | :-: | -----: |
| kay  | 23  |   male |
| John | 30  |   male |

---

<br/>

## 9 Emoji

```
  :rocket: :smile: :house: :moneybag:
```

:rocket: :smile: :house: :moneybag:

Complete list of markdown emoji please click link down below:

[Complete list of github markdown emoji markup](https://gist.github.com/rxaviers/7360908 'Complete list of github markdown emoji markup')

---

<br/>

## 10 Footnotes

```
  Here's a simple footnote[^1], and here's a longer one[^bignote].

  [^1]: This is the first footnote.
  [^bignote]:
      Here's one with multiple paragraphs and code.

      Indent paragraphs to include them in the footnote.

      `{ my code }`

Add as many paragraphs as you want.

```

Here's a simple footnote[^1], and here's a longer one[^bignote].

[^1]: This is the first footnote.

[^bignote]:
    Here's one with multiple paragraphs and code.
    Indent paragraphs to include them in the footnote.

    `{ my code }`

Add as many paragraphs as you want.
