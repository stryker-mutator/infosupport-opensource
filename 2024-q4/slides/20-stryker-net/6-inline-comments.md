## Inline comments

Old:
```csharp
// Stryker disable all
var x = 1 + 1;
```
New:
```csharp
if (condition) {/* Stryker comment*/;....}: // this comment will apply to the whole syntax block
if (/* Stryker comment*/ condition) {....}: // this comment will apply to the whole condition expression
```