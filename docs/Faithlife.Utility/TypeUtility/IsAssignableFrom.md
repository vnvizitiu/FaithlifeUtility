# TypeUtility.IsAssignableFrom method

Determines whether an instance of the specified type can be assigned from an instance of the specified parent type.

```csharp
public static bool IsAssignableFrom(this Type type, Type parentType)
```

| parameter | description |
| --- | --- |
| type | The type. |
| parentType | The parent type. |

## Return Value

true if parentType and type represent the same type, or if type is in the inheritance hierarchy of parent type, or if type is an interface that parentType implements, or if parent type is a generic type parameter and type represents one of the constraints of parent type. false if none of these conditions are true, or if parent type is null.

## See Also

* class [TypeUtility](../TypeUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->
