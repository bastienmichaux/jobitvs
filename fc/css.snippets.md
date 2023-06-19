[Home](../README.md) • [CSS Questions](./css.md)

# CSS Snippets

## Text effects

<!-- $Q:D -->
<details>
<summary>Initial letter / drop cap</summary>

Using vanilla CSS:
```css
.drop-cap::first-letter {
  font-size: 2rem;
  font-weight: 600;
  float: left;
  line-height: 2rem;
  margin-right: 0.5rem;
}
```

Using `initial-letter` (experimental; not supported by Firefox as of 2023):
```css
selector {
  initial-letter: normal; /* default  */
  initial-letter: 1.5; /* occupies 1.5 lines */
}
```

Sources:
- [reddit](https://www.reddit.com/r/web_design/comments/13s0flv/css_drop_cap/)
- [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/initial-letter)
</details>
