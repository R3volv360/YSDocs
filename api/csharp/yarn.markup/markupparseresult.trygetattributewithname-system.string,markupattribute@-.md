# MarkupParseResult.TryGetAttributeWithName Method

Gets the first attribute with the specified name, if present.


```csharp
public bool TryGetAttributeWithName(string name, out MarkupAttribute attribute)
```

## Parameters
|Parameter|Description|
|:---|:---|
|[`string`](https://docs.microsoft.com/dotnet/api/System.String) name|The name of the attribute to get.|
|[`MarkupAttribute`](/api/csharp/yarn.markup/markupattribute.md) attribute|When this method returns, contains the attribute with the specified name, if the attribute is found; otherwise, the default [`MarkupAttribute`](/api/csharp/yarn.markup/markupattribute.md). This parameter is passed uninitialized.|
## Return Type
[`bool`](https://docs.microsoft.com/dotnet/api/System.Boolean): `` if the [`MarkupParseResult`](/api/csharp/yarn.markup/markupparseresult.md) contains an attribute with the
    specified name; otherwise, ``.



## Namespace
[`Yarn.Markup`](/api/csharp/yarn.markup/README.md)

## Assembly
YarnSpinner.dll

## Source
Defined in [YarnSpinner/YarnSpinner.Markup/MarkupParseResult.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner/YarnSpinner.Markup/MarkupParseResult.cs#L75), line 75.