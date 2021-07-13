# StringTableEntry Struct


```csharp
public struct StringTableEntry
```



## Constructors
|Name|Description|
|:---|:---|
|[`StringTableEntry(StringTableEntry)`](/api/csharp/yarn.unity/stringtableentry._ctor-stringtableentry-.md)||
## Fields
|Name|Description|
|:---|:---|
|[`Comment`](/api/csharp/yarn.unity/stringtableentry.comment.md)| A comment used to describe this line to translators. |
|[`File`](/api/csharp/yarn.unity/stringtableentry.file.md)| The name of the Yarn script in which this line was originally found. |
|[`ID`](/api/csharp/yarn.unity/stringtableentry.id.md)| The line ID for this line. This value will be the same across all localizations. |
|[`Language`](/api/csharp/yarn.unity/stringtableentry.language.md)| The language that the line is written in. |
|[`LineNumber`](/api/csharp/yarn.unity/stringtableentry.linenumber.md)| The line number in the file indicated by [`File`](/api/csharp/yarn.unity/stringtableentry.file.md) at which the original version of this line can be found. |
|[`Lock`](/api/csharp/yarn.unity/stringtableentry.lock.md)| A string used as part of a mechanism for checking if translated versions of this string are out of date. |
|[`Node`](/api/csharp/yarn.unity/stringtableentry.node.md)| The name of the node in which this line was originally found. |
|[`Text`](/api/csharp/yarn.unity/stringtableentry.text.md)| The text of this line, in the language specified by [`Language`](/api/csharp/yarn.unity/stringtableentry.language.md). |
## Methods
|Name|Description|
|:---|:---|
|[`CreateCSV(IEnumerable<StringTableEntry>)`](/api/csharp/yarn.unity/stringtableentry.createcsv-ienumerable-stringtableentry--.md)||
|[`Equals(Object)`](/api/csharp/yarn.unity/stringtableentry.equals-system.object-.md)||
|[`GetHashCode()`](/api/csharp/yarn.unity/stringtableentry.gethashcode.md)||
|[`ParseFromCSV(String)`](/api/csharp/yarn.unity/stringtableentry.parsefromcsv-system.string-.md)| Reads comma-separated value ata from <code data-dev-comment-type="paramref" class="paramref">sourceText</code>, and produces a collection of [`StringTableEntry`](/api/csharp/yarn.unity/stringtableentry.md) structs. |
|[`ToString()`](/api/csharp/yarn.unity/stringtableentry.tostring.md)||
## Namespace
[`Yarn.Unity`](/api/csharp/yarn.unity/README.md)

## Assembly
YarnSpinner.dll

## Source
Defined in [../YarnSpinner-Unity-Dev/Packages/YarnSpinner/Runtime/StringTableEntry.cs](https://github.com/YarnSpinnerTool/YarnSpinner-Unity//blob/develop/Runtime/StringTableEntry.cs#L7), line 7.