[Home](../README.md) • [CSS Snippets](./css.snippets.md)

# CSS Questions

**Content:**
- [Fundamentals](#fundamentals)
- [Selectors](#selectors)
- [Layout](#layout)
<!-- - [](#) -->



## Fundamentals

<!-- $Q:D -->
<details id="">
<summary>What are the main parts of CSS syntax?</summary>

- Selectors
- Body (or block)
- Rules
- Properties
- Values
</details>



<!-- $Q:D -->
<details>
<summary>How to center elements?</summary>

Several ways.

Simple one:
```css
selector {
  margin: 0 auto;
  text-align: center;
}
```
</details>



## Selectors

<!-- $Q:D -->
<details>
<summary>How to combine CSS pseudo-classes?</summary>

Just append them:
```css
.myclass:hover::first-letter {}
```
</details>



<!-- $Q:D -->
<details>
<summary>Should I use `:after` or `::after`</summary>

Use `::after` to establish a discrimination between pseudo-classes and pseudo-elements. Browsers still accept the notation `:after` introduced in CSS 2 though.

Note: Microsoft Internet Explorer 8 supports `:after` only.
</details>



<!-- $Q:D -->
<details>
<summary>Why and how do you use `justify-content`?</summary>

**Flex display:** `justify-content` determines how the items inside a flex container are positioned along the main axis, affecting their position and the space around them.
</details>



## Layout

<!-- $Q:D -->
<details>
<summary>How to use flexbox?</summary>

Change the display then mind:
- `flex-direction`: axis: horizontal/vertical and LTR/RTL

```css
selector {
  display: flex;
  flex-direction: row | row-reverse | column | column-reverse;
  flex-wrap: wrap | nowrap;

  /* always useful */
  justify-content: start | center | space-between | space-around | space-evenly;
}
```

<blockquote>
  <!-- $Q:C -->
  <details>
  <summary>Why and how do you use `flex-direction`?</summary>

  `flex-direction` has 4 possible values:
  - `row` (default): horizontal axis, items left to right (LTR)
  - `row-reverse`: horizontal axis, RTL
  - `column`: vertical axis, top to bottom
  - `column-reverse`: vertical axis, bottom to top
  </details>

  <!-- $Q:C -->
  <details>
  <summary>Why and how do you use `flex-wrap`?</summary>

  To determine how flex items behave when the flex container is too small:
  - `wrap` the items to wrap to the next row or column.
  - `nowrap` prevents items from wrapping and shrink them if needed.
  </details>
</blockquote>
</details>
