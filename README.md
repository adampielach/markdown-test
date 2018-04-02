<!-- good GitHub reference -->

The original reference for Markdown: 
[John Gruber's original spec](http://daringfireball.net/projects/markdown/)

<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

<!-- Italics -->

*This text is italic*

_This_ is italic

<!-- Strong -->

**This text** is strong

__This text__ is also strong

<!-- Strikethrough -->

~~This text~~ is strikethrough

<!-- Horizontal rule -->

---
___

<!-- Blockquote -->
>This is a quote

<!-- links -->

[Google](http://www.traversymedia.com)

[Google](http://www.traversymedia.com "Google") with title on hover.

<!-- ul -->

* Item 1
* Item 2
* Item 2
    * Nested Item 1
    * Nested Item 2

<!-- ol -->

1. Item 1
1. Item 2
1. Item 3
    
<!-- Inline code block -->

`<p>This is a paragraph</p>`

<!-- image -->
## IMAGES
-----

You attach an image with: `![alt_text](URL "title")`.

![Markdown logo](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Markdown Logo")

Image can also be referenced with `[reference_name]: URL`.

You just have to specify image like `![alt_text][reference_name]`.

![Markdown logo][markdown_reference]

[markdown_reference]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

<!-- GitHub Markdown -->

<!-- Code blocks -->

```bash
    npm install

    npm start
```

```javascript
    function add(num1, num2) {
        return num1 + num2;
    }
```

```python
    def add(num1, num2):
        return num1 + num2
```

<!-- Tables -->

| Name           | Email                      |
| -------------- | ------------------------- |
| Adam Pielach   | adampielach@gmail.com     |
| Traversy Media | support@traversymedia.com |

<!-- Task Lists -->

* [x] Task 1
* [x] Task 2
* [ ] Task 3