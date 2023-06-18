[Home](../README.md)

# HTTP Questions

Questions:
- [Explain response code 503](#503)

<details id="503">
<summary>Explain response code 503</summary>

Error: the server is not ready to handle the request.

<details><summary>Common causes for error 503?</summary>
The server is down for maintenance or is overloaded.
</details>

<details>
<summary>How and when devs should return a 503 error?</summary>
It should be used for temporary conditions.

The `Retry-After` HTTP header should, if possible, contain the estimated time for the recovery of the service.
</details>

[Source: MDN](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/503)
</details>
