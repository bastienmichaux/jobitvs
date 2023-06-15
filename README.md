# jobitvs

Collapsible section template

## JS

<details>
<summary><b>1: How to log something in JS?</b></summary><br>

Use the built-in function `console.log`
```js
console.log('Something', something);
```

</details>


<details><summary><b>2: How to declare a constant in JS?</b></summary><br>


Use the `const` keyword instead of `var` or `let`
```js
const foo = "foo";
```
</details>

## HTTP

<details>
  <summary><b>Signification of HTTP response code 503?</b></summary>
  Error: the server is not ready to handle the request.

  <details><summary>Common causes for error 503?</summary>
  The server is down for maintenance or is overloaded.
  </details>

  <details><summary>How and when devs should return a 503 error?</summary>
  It should be used for temporary conditions and the Retry-After HTTP header should, if possible, contain the estimated time for the recovery of the service. 
  </details>

  [Source: MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/503)
</details>
