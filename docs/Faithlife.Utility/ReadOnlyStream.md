# ReadOnlyStream class

A read-only stream wrapper.

```csharp
public sealed class ReadOnlyStream : WrappingStreamBase
```

## Public Members

| name | description |
| --- | --- |
| [ReadOnlyStream](ReadOnlyStream/ReadOnlyStream.md)(…) | Initializes a new instance of the [`ReadOnlyStream`](ReadOnlyStream.md) class. |
| override [CanWrite](ReadOnlyStream/CanWrite.md) { get; } | Gets a value indicating whether the current stream supports writing. |
| override [Read](ReadOnlyStream/Read.md)(…) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| override [ReadAsync](ReadOnlyStream/ReadAsync.md)(…) | Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests. |
| override [SetLength](ReadOnlyStream/SetLength.md)(…) | Sets the length of the current stream. |
| override [Write](ReadOnlyStream/Write.md)(…) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| override [WriteAsync](ReadOnlyStream/WriteAsync.md)(…) | Asynchronously writes a sequence of bytes to the current stream, advances the current position within this stream by the number of bytes written, and monitors cancellation requests. |

## See Also

* class [WrappingStreamBase](WrappingStreamBase.md)
* namespace [Faithlife.Utility](../Faithlife.Utility.md)
* [ReadOnlyStream.cs](https://github.com/Faithlife/FaithlifeUtility/tree/master/src/Faithlife.Utility/ReadOnlyStream.cs)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->