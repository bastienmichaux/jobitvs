[Home](../README.md) • [HTML Questions](./html.md)

# HTML Snippets

<!-- $Q:D -->
<details>
<summary>Minimal HTML5 document</summary>

- The 2 meta tags must come first to ensure proper document rendering
- Any other head element should come after these tags
- Always include the document's language
```html
<!DOCTYPE html>
<html lang="xx">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>
</body>
</html>
```
</details>



<!-- $Q:C -->
<details id="table">
<summary>How to make a table</summary>

```html
<table>
  <tr>
    <th>Number</th>
    <th>Letter</th>
  </tr>
  <tr>
    <td>1</td>
    <td>A</td>
  </tr>
  <tr>
    <td>2</td>
    <td>B</td>
  </tr>
</table>
```
</details>
