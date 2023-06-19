# Contributing

Use this template to contribute:

```markdown
<!-- $Q: A, B, C or D -->
<details id="kebab-case-id">
<summary><b>Question</b></summary>

(Leave 1 blank line above the answer if you need to render Markdown syntax)
Answer/explanation.

[Source](some.reliable.source) (no source needed for common sense/obvious stuff)

**Note:** if a resource is used extensively in the same document, you can put it at the bottom of the page.
</details>
```

`$Q` expresses the quality of an answer:
- D = unsatisfying;
- C = satisfying/ok;
- B = good;
- A = "[done and done](https://en.wiktionary.org/wiki/done_and_done)".


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
Answer C
</details>


**For follow-up question(s):** use blockquotes for indentation.

<!-- $Q:X -->
<details id="id">
<summary><b>First question</b></summary>

Answer

<blockquote>
<details><summary id="sub-id-1">Follow-up question</summary>

Answer
</details>

<details><summary id="sub-id-2">Follow-up question</summary>
Answer
</details>
</blockquote>

</details>

**Style, etc:**
- Write simple, clear, concise English.
- Explain new terms. The order of questions matter.
- Leave 4 newlines between each question.

That's all! Thanks for reading!
