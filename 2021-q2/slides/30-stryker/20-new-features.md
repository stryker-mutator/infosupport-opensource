### New in StrykerJS 5

* ✨ New dimension
* <!-- .element class="fragment" --> 🤷‍♂️ Discovering files
* <!-- .element class="fragment" --> 👽 Nullish coalescing mutation
  ```diff
  -foo ?? bar
  +foo && bar
  ```
* <!-- .element class="fragment" --> ⚔ Weapon regeX mutation
  ```diff
  - /\d{4}\s?[a-Z]{2}/
  + /\d\s?[a-Z]{2}/
  + /\D{4}\s?[a-Z]{2}/
  ```
* <!-- .element class="fragment" --> 🕵️‍♂️ Default coverage analysis
* <!-- .element class="fragment" --> 🃏 Fixed <a href="https://github.com/facebook/jest/pulls?q=is%3Apr+author%3Anicojs+is%3Aclosed" target="_blank">issues in Jest</a>

<!-- .element class="no-list"  -->