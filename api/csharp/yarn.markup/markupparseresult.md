# MarkupParseResult Struct

The result of parsing a line of marked-up text.


```csharp
public struct MarkupParseResult
```
## Remarks

You do not create instances of this struct yourself. It is created
by objects that can parse markup, such as [`Dialogue`](/api/csharp/yarn/dialogue.md).




## Fields
|Name|Description|
|:---|:---|
|[`Attributes`](/api/csharp/yarn.markup/markupparseresult.attributes.md)| The list of [`MarkupAttribute`](/api/csharp/yarn.markup/markupattribute.md)s in this parse result. |
|[`Text`](/api/csharp/yarn.markup/markupparseresult.text.md)| The original text, with all parsed markers removed. |
## Methods
|Name|Description|
|:---|:---|
|[`DeleteRange(MarkupAttribute)`](/api/csharp/yarn.markup/markupparseresult.deleterange-markupattribute-.md)| Deletes an attribute from this markup. |
|[`TextForAttribute(MarkupAttribute)`](/api/csharp/yarn.markup/markupparseresult.textforattribute-markupattribute-.md)| Returns the substring of [`Text`](/api/csharp/yarn.markup/markupparseresult.text.md) covered by <code data-dev-comment-type="paramref" class="paramref">attribute</code> Position and Length properties. |
|[`TryGetAttributeWithName(String, out MarkupAttribute)`](/api/csharp/yarn.markup/markupparseresult.trygetattributewithname-system.string,markupattribute@-.md)| Gets the first attribute with the specified name, if present. |
## See Also
* [`ParseMarkup(String)`](/api/csharp/yarn/dialogue.parsemarkup-system.string-.md): 
Parses a line of text, and produces a [`MarkupParseResult`](/api/csharp/yarn.markup/markupparseresult.md) containing the results.

## Namespace
[`Yarn.Markup`](/api/csharp/yarn.markup/README.md)

## Assembly
YarnSpinner.dll

## Source
Defined in [YarnSpinner/YarnSpinner.Markup/MarkupParseResult.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner/YarnSpinner.Markup/MarkupParseResult.cs#L40), line 40.