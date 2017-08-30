# EnumerableUtility.CrossProduct&lt;T&gt; method (1 of 2)

Returns the Cartesian cross-product of a sequence of sequences.

```csharp
public static IEnumerable<IEnumerable<T>> CrossProduct<T>(this IEnumerable<IEnumerable<T>> sequences)
```

| parameter | description |
| --- | --- |
| sequences | The sequences. |

## Return Value

A new sequence of sequences, where the first item in each sequence is from the first input sequence, the second item is from the second input sequence, and so on.

## See Also

* class [EnumerableUtility](../EnumerableUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

---

# EnumerableUtility.CrossProduct&lt;TSequence,TItem&gt; method (2 of 2)

Returns the Cartesian cross-product of a sequence of sequences.

```csharp
public static IEnumerable<IEnumerable<TItem>> CrossProduct<TSequence, TItem>(this IEnumerable<TSequence> sequences)
    where TSequence : IEnumerable<TItem>
```

| parameter | description |
| --- | --- |
| sequences | The sequences. |

## Return Value

The cross product.

## See Also

* class [EnumerableUtility](../EnumerableUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->