# Contributing

Use this template to contribute:

```markdown
<!-- $Q: A, B, C or D -->
<details id="kebab-case-id">
<summary><b>Question</b></summary>
<blockquote>

(Leave 1 blank line above the answer if you need to render Markdown syntax)
Answer/explanation.

[Source](some.reliable.source) (no source needed for common sense/obvious stuff)

Note: if a resource is used extensively in the same document, you can put it at the bottom of the page.
</blockquote></details>
```

> $Q expresses the quality of an answer, it's used for prioritizing work.
> D = unsatisfying;
> C = satisfying/ok;
> B = good;
> A = "[done and done](https://en.wiktionary.org/wiki/done_and_done)".


---

**Multiple choice question:**

<!-- $Q:X -->
<details id="id">
<summary><b>Question:</b>
  <ul>
    <li>Answer A</li>
    <li>Answer B</li>
    <li>Answer C</li>
  </ul>
</summary>
<blockquote>
Answer C
</blockquote></details>


---

**For follow-up question(s):**

<!-- $Q:X -->
<details id="id">
<summary><b>First question</b></summary>
<blockquote>

Answer

<details><summary id="sub-id-1">Follow-up question</summary>
  <blockquote>Answer</blockquote>
</details>

<details><summary id="sub-id-2">Follow-up question</summary>
  <blockquote>Answer</blockquote>
</details>
</blockquote></details>
