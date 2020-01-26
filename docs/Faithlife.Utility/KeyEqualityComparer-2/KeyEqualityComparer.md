# KeyEqualityComparer&lt;TSource,TKey&gt; constructor

Initializes a new instance of the KeyEqualityComparer class.

```csharp
public KeyEqualityComparer(Func<TSource, TKey> keySelector, 
    IEqualityComparer<TKey> keyComparer = null)
```

| parameter | description |
| --- | --- |
| keySelector | The key selector delegate |
| keyComparer | The IEqualityComparer used for comparison of keys |

## See Also

* class [KeyEqualityComparer&lt;TSource,TKey&gt;](../KeyEqualityComparer-2.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->