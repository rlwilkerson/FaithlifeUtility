# TypeUtility.IsSubclassOf method

Determines whether an instance of the specified type is a subclass of the current type.

```csharp
public static bool IsSubclassOf(this Type type, Type c)
```

| parameter | description |
| --- | --- |
| type | The type. |
| c | The type to compare. |

## Return Value

true if the Type represented by the c parameter and the current Type represent classes, and the class represented by the current Type derives from the class represented by c; otherwise, false. This method also returns false if c and the current Type represent the same class.

## See Also

* class [TypeUtility](../TypeUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->