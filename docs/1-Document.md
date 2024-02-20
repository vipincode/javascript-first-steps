# Introduction

The Document interface represents any web page loaded in the browser and serves as an entry point into the web page's content, which is the DOM tree.

- `document` The entire HTML document

```js
document.title;
```

- This is show the page of title

```js
document.body.children;
```

- This return the body children like, `header`, `div#id`
- it show element with class name or id.
- all the elements within the body

## the (first) element with id="board"

```js
document.getElementById("board");
document.querySelector("#board");
```

- the (first) element with id="board" ex.
- `<div id="board">...</div>`

## all the `h1` elements

```js
document.getElementsByTagName("h1");
document.querySelectorAll("h1");
```

## all the elements with class="player"

```js
document.getElementsByClassName("player");
document.querySelectorAll(".player");
```

## Length Property

- Bcs we learn these property return as array of elements, and `length` is an array property so its show actual length of array
- meaning, how many data document have.
- the number of elements with class="player"

```js
document.getElementsByClassName("player").length``; // return 2, 3 or many depend
```

```js
document.querySelectorAll(".player").length; // return 2, 3 or many depend
```

## Get textContent

- the text inside the element with id="p1-name"

```js
document.getElementById("p1-name").textContent;
```

```js
document.getElementById("p1-name").textContent = "Sofia";
```

- replace the text of the #p1-name element

```js
document.getElementById("p1-name").append(" & friends");
```

- add to the end of the element's current text
