### New features

We've been preparing StrykerJS 6.0

See [blog article](https://github.com/stryker-mutator/stryker-mutator.github.io/pull/400) <!-- .element target="_blank" -->

- 📦 ESM support
- ⏩ Hot reload
- 🗿 `--ignoreStatic`

---

#### Hot reload

<div class="flex">
<div class="col sm">

**Old process**

1. Activate the mutant
2. _load all files_
3. Run the tests with the test runner of choice.
4. _Unload all files_
5. Report the result

</div>
<div class="col sm">

**New Process**

<!-- .element class="fragment" data-fragment-index="0" -->

1. (once) Load the code using `import`
1. Activate the mutant
1. Run the tests with the test runner of choice.
1. Report the result

<!-- .element class="fragment" data-fragment-index="0" start="0" -->

</div>
</div>

Theoretical example:

<!-- .element class="fragment md" data-fragment-index="1" -->

- 1k files
- 10k mutants
- <!-- .element class="fragment" data-fragment-index="2" --> <em>ten million file IO actions</em> 😓
- <!-- .element class="fragment" data-fragment-index="3" --> 30% performance improvement

<!-- .element class="fragment md" data-fragment-index="1" -->
