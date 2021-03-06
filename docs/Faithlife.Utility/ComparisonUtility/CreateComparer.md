# ComparisonUtility.CreateComparer&lt;T&gt; method (1 of 2)

Creates a comparer from a delegate.

```csharp
public static Comparer<T> CreateComparer<T>(Func<T, T, int> comparer)
```

| parameter | description |
| --- | --- |
| T | The type to compare. |
| comparer | The compare delegate. |

## Return Value

The comparer.

## See Also

* class [ComparisonUtility](../ComparisonUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

---

# ComparisonUtility.CreateComparer&lt;T&gt; method (2 of 2)

Creates a comparer from a delegate.

```csharp
public static Comparer<T> CreateComparer<T>(params Func<T, T, int>[] comparers)
```

| parameter | description |
| --- | --- |
| T | The type to compare. |
| comparers | The compare delegates. |

## Return Value

The comparer.

## See Also

* class [ComparisonUtility](../ComparisonUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->
