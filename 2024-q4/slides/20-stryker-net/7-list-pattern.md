## List patterns

``` cs
string[][] transactions = new[]
{
    new[] { "1", "DEPOSIT", "100.00" },
};
foreach (string[] transaction in transactions)
{
    balance += transaction switch
    {
    // "DEPOSIT" should be mutated here
    [_, "DEPOSIT", _, var amount] => decimal.Parse(amount),
    [_, "WITHDRAWAL", .., var amount] => -decimal.Parse(amount),
    };
}
```