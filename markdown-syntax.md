# Markdown syntax

## Headings


```

# H1
## H2
### H3
#### H4
##### H5
###### H6

```

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Styling

```

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

~~this text is strikethrough~~


```


*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

~~this text is strikethrough~~


## Lists

### Unordered lists

```

* Item 1
* Item 2
  * Item 2a
  * Item 2b

```

* Item 1
* Item 2
  * Item 2a
  * Item 2b

### Ordered lists

```

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

```

1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b

### Nested lists

```

1. First list item
   - First nested list item
     - Second nested list item

```

1. First list item
   - First nested list item
     - Second nested list item

## Images

```

![Markdown Logo](Markdown-mark.svg)
Format: ![Alt Text](url)

```

![Markdown Logo](Markdown-mark.svg)

## Links

```

http://github.com
[GitHub](http://github.com)

```

http://github.com

[GitHub](http://github.com)

## Blockquotes

Antoine de Saint-Exupéry:

> “Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away.”

### Inline code


```

Displaying an inline code use backtick - like that `code example` here.

```

Displaying an inline code use backtick - like that `code example` here.

## GitHub Flavored Markdown

### Code block

Displaying code block use triple backtick:

```

Displaying code block use triple backtick

``` javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
} ```
 ``` 


or just indent the code block

    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }


### Syntax highlighting

For language based syntax highlight use triple backtick and language code. 
For example: ` ```js `

```js

function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}

```

## Task lists

```

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request

```

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request

## Mentioning people and teams
```

@HelsinkiBusinessCollege What do you think about this template?

```

@HelsinkiBusinessCollege What do you think about this template?

## Using emojis

For a full list of available emoji and codes, check out the [Emoji-Cheat-Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).


```

Be yourself. Unless you can be a :unicorn:, In that case, you should always be a :unicorn:.

```

Be yourself. Unless you can be a :unicorn:, In that case, you should always be a :unicorn:.



## Used sources

- [GitHub Docs](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
- [GitHub Guides](https://guides.github.com/features/mastering-markdown/)
- [Advanced formatting](https://docs.github.com/en/github/writing-on-github/working-with-advanced-formatting)