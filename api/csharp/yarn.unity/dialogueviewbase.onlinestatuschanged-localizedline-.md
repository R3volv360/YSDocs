# DialogueViewBase.OnLineStatusChanged Method

Called by the DialogueRunner to indicate that the line that
this view is delivering has changed state.


```csharp
public abstract void OnLineStatusChanged(LocalizedLine dialogueLine)
```
## Remarks

Subclasses of [`DialogueViewBase`](/api/csharp/yarn.unity/dialogueviewbase.md) should override
this method to be notified when a line has become interrupted,
and when the line has finished being delivered by all views.

The default implementation does nothing.


## Parameters
|Parameter|Description|
|:---|:---|
|[`LocalizedLine`](/api/csharp/yarn.unity/localizedline.md) dialogueLine|The [`LocalizedLine`](/api/csharp/yarn.unity/localizedline.md) that has changed state.|


## See Also
* [`LineStatus`](/api/csharp/yarn.unity/linestatus.md): 
The presentation status of a [`LocalizedLine`](/api/csharp/yarn.unity/localizedline.md).

## Namespace
[`Yarn.Unity`](/api/csharp/yarn.unity/README.md)

## Assembly
YarnSpinner.dll

## Source
Defined in [../YarnSpinner-Unity-Dev/Packages/YarnSpinner/Runtime/Views/DialogueViewBase.cs](https://github.com/YarnSpinnerTool/YarnSpinner-Unity//blob/develop/Runtime/Views/DialogueViewBase.cs#L84), line 84.