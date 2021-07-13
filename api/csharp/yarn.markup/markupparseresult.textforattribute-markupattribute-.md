# MarkupParseResult.TextForAttribute Method

Returns the substring of [`Text`](/api/csharp/yarn.markup/markupparseresult.text.md) covered by
<code data-dev-comment-type="paramref" class="paramref">attribute</code> Position and Length properties.


```csharp
public string TextForAttribute(MarkupAttribute attribute)
```
## Remarks

If the attribute's [`Length`](/api/csharp/yarn.markup/markupattribute.length.md)
property is zero, this method returns the empty string.

This method does not check to see if <code data-dev-comment-type="paramref" class="paramref">attribute</code> is an attribute belonging to this
MarkupParseResult. As a result, if you pass an attribute that
doesn't belong, it may describe a range of text that does not
appear in [`Text`](/api/csharp/yarn.markup/markupparseresult.text.md). If this occurs, an [`IndexOutOfRangeException`](https://docs.microsoft.com/dotnet/api/System.IndexOutOfRangeException) will be thrown.


## Parameters
|Parameter|Description|
|:---|:---|
|[`MarkupAttribute`](/api/csharp/yarn.markup/markupattribute.md) attribute|The attribute to get the text for.|
## Return Type
[`string`](https://docs.microsoft.com/dotnet/api/System.String): The text contained within the attribute.



## Namespace
[`Yarn.Markup`](/api/csharp/yarn.markup/README.md)

## Assembly
YarnSpinner.dll

## Source
Defined in [YarnSpinner/YarnSpinner.Markup/MarkupParseResult.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner/YarnSpinner.Markup/MarkupParseResult.cs#L112), line 112.