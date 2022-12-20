---
layout: page
lang: en
ref: styleguide
title: Styleguide
description: This is a style guide for the jekyll theme
---

This is a paragraph. You don't need to read the rest of it, it is not very informative and reading will be a waste of time. It is here as filler text, text that fills out the page and makes this look like a realistic paragraph. That is it. Nothing more. Sorry if you did end this far, we did warn you.

# Heading 1

**This is a paragraph.** You don't need to read the rest of it, it is not very informative and reading will be a waste of time. It is here as filler text, text that fills out the page and makes this look like a realistic paragraph. That is it. Nothing more. Sorry if you did end this far, we did warn you.

## Heading 2

This is a paragraph. You don't need to read the rest of it, it is not very informative and reading will be a waste of time. It is here as filler text, text that fills out the page and makes this look like a realistic paragraph. That is it. Nothing more. Sorry if you did end this far, we did warn you.

### Heading 3

This is a paragraph. You don't need to read the rest of it, it is not very informative and reading will be a waste of time. It is here as filler text, text that fills out the page and makes this look like a realistic paragraph. That is it. Nothing more. Sorry if you did end this far, we did warn you.

#### Heading 4

This is a paragraph. You don't need to read the rest of it, it is not very informative and reading will be a waste of time. It is here as filler text, text that fills out the page and makes this look like a realistic paragraph. That is it. Nothing more. Sorry if you did end this far, we did warn you.

##### Heading 5

This is a paragraph. You don't need to read the rest of it, it is not very informative and reading will be a waste of time.

###### Heading 6

This is a paragraph. You don't need to read the rest of it, it is not very informative and reading will be a waste of time. It is here as filler text, text that fills out the page and makes this look like a realistic paragraph. That is it. Nothing more. Sorry if you did end this far, we did warn you.

## Emphasis

**This is bold text**

*This is italic text*

~~Strikethrough~~

## Links

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

## Quoting

>“Creativity is allowing yourself to make mistakes. Design is knowing which ones to keep.”

This is a `paragraph`. You don't need to read the rest of it, it is not very informative and reading will be a waste of time. It is here as filler text, text that fills out the page and makes this look like a realistic paragraph. That is it. Nothing more. Sorry if you did end this far, we did warn you.

***

## Code Blocks

```css
#header h1 { 
  color: #fff;
  margin-bottom: 1.5em; 
}

.author-avatar {
  border-radius: 5px;
  display: block;
  height: 60px;   
  margin-right: 30px;
  width: 60px;
}
```

```javascript
// Simple map
var map;
function initMap() {
  map = new google.maps.Map(document.getElementById('map'), {
    center: {lat: -34.397, lng: 150.644},
    zoom: 8
  });
}
```

```json
{"menu": {
  "id": "file",
  "value": "File",
  "popup": {
    "menuitem": [
      {"value": "New", "onclick": "CreateNewDoc()"},
      {"value": "Open", "onclick": "OpenDoc()"},
      {"value": "Close", "onclick": "CloseDoc()"}
    ]
  }
}}
```

```yml
sass:
  input_file: sass/main.scss.njk
  output_file: assets/css/main.css
  indentWidth: 4
  outputStyle: nested
  precision: 10
```

```
No language indicated, so no syntax highlighting. 
```

Inline `code` has `back-ticks around` it.

## Videos

<iframe src="https://player.vimeo.com/video/153339497?byline=0" width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

[Terraforming](https://vimeo.com/153339497) from [Studio Swine](https://vimeo.com/studioswine) on [Vimeo](https://vimeo.com)

## Full Width Image

Images work too! Already know the URL of the image you want to include in your article? Simply paste it in like this to make it show up:

{% include image_full.html imageurl="/images/wales-flag.jpg" alt="Wales flag" caption="This is the caption" %}

This is a `paragraph`. You don't need to read the rest of it, it is not very informative and reading will be a waste of time. It is here as filler text, text that fills out the page and makes this look like a realistic paragraph. That is it. Nothing more. Sorry if you did end this far, we did warn you.

## Regular Image

{% include image_caption.html imageurl="/images/wales-flag.jpg" alt="Wales flag Super" caption="This is the caption" %}

This is a `paragraph`. You don't need to read the rest of it, it is not very informative and reading will be a waste of time. It is here as filler text, text that fills out the page and makes this look like a realistic paragraph. That is it. Nothing more. Sorry if you did end this far, we did warn you.

## Lists

Here is an unordered list of items, typically rendered as a bulleted list:

+ an item on the list
+ and another
+ and another
+ it doesn't matter what order the items go in

Here is an ordered list of items, typically rendered as a numbered list:

1. the first item in the list
2. the second
3. the third
4. and the fourth

### Tables

| Title | Title |
| ------| ----- |
| Text  | Text  |
| Text  | Text  |
| Text  | Text  |
