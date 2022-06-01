### 🔮 What's next?

- [Method expression mutator](https://github.com/stryker-mutator/stryker-js/pull/3508) <!-- .element target="_blank" -->
- Implement grouping in TypeScript checker 
- [new ESLint checker](https://github.com/stryker-mutator/stryker-js/pull/3474) <!-- .element target="_blank" -->
- Longer term: [`--incremental`](https://github.com/stryker-mutator/stryker-js/issues/2753) <!-- .element target="_blank" -->

---

#### Method expression mutator

| Original             | Mutated               |
| -------------------- | --------------------- |
| `endsWith()`         | `startsWith()`        |
| `startsWith()`       | `endsWith()`          |
| `trim()`             | _none_                |
| `trimEnd()`          | `trimStart()`         |
| `trimStart()`        | `trimEnd()`           |
| `substr()`           | _none_                |
| `substring()`        | _none_                |
| `toUpperCase()`      | ` toLowerCase()`      |
| `toLowerCase()`      | ` toUpperCase()`      |
| `toLocalLowerCase()` | `toLocalUpperCase()`  |
| `toLocalUpperCase()` | ` toLocalLowerCase()` |
| `sort()`             | _none_                |
| `some()`             | `every()`             |
| `every()`            | `some()`              |
| `reverse()`          | _none_                |
| `filter()`           | _none_                |
| `slice()`            | _none_                |
| `charAt()`           | _none_                |
