# DisposableUtility.DisposeAfter&lt;T&gt; method (1 of 4)

Disposes the specified object after executing the specified delegate.

```csharp
public static void DisposeAfter<T>(this T disposable, Action action)
    where T : IDisposable
```

| parameter | description |
| --- | --- |
| T | The type of the input |
| disposable | The object to dispose. |
| action | The delegate to execute before disposing the object. |

## See Also

* class [DisposableUtility](../DisposableUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

---

# DisposableUtility.DisposeAfter&lt;T&gt; method (2 of 4)

Disposes the specified object after executing the specified delegate.

```csharp
public static void DisposeAfter<T>(this T disposable, Action<T> action)
    where T : IDisposable
```

| parameter | description |
| --- | --- |
| T | The type of the input |
| disposable | The object to dispose. |
| action | The delegate to execute before disposing the object. |

## See Also

* class [DisposableUtility](../DisposableUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

---

# DisposableUtility.DisposeAfter&lt;TInput,TOutput&gt; method (3 of 4)

Disposes the specified object after executing the specified delegate.

```csharp
public static TOutput DisposeAfter<TInput, TOutput>(this TInput disposable, 
    Func<TInput, TOutput> action)
    where TInput : IDisposable
```

| parameter | description |
| --- | --- |
| TInput | The type of the input. |
| TOutput | The type of the output. |
| disposable | The object to dispose. |
| action | The delegate to execute before disposing the object. |

## Return Value

The value returned by the delegate.

## See Also

* class [DisposableUtility](../DisposableUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

---

# DisposableUtility.DisposeAfter&lt;TInput,TOutput&gt; method (4 of 4)

Disposes the specified object after executing the specified delegate.

```csharp
public static TOutput DisposeAfter<TInput, TOutput>(this TInput disposable, Func<TOutput> action)
    where TInput : IDisposable
```

| parameter | description |
| --- | --- |
| TInput | The type of the input. |
| TOutput | The type of the output. |
| disposable | The object to dispose. |
| action | The delegate to execute before disposing the object. |

## Return Value

The value returned by the delegate.

## See Also

* class [DisposableUtility](../DisposableUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->
