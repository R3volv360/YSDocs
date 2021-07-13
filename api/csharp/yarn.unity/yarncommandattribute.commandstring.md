# YarnCommandAttribute.CommandString Property

The name of the command, as it exists in Yarn.


```csharp
public string CommandString { get; set; }
```
## Remarks

This value does not have to be the same as the name of the
method. For example, you could have a method named
"`WalkToPoint`", and expose it to Yarn as a command named
"`walk_to_point`".




## Namespace
[`Yarn.Unity`](/api/csharp/yarn.unity/README.md)

## Assembly
YarnSpinner.dll

## Source
Defined in [../YarnSpinner-Unity-Dev/Packages/YarnSpinner/Runtime/DialogueRunner.cs](https://github.com/YarnSpinnerTool/YarnSpinner-Unity//blob/develop/Runtime/DialogueRunner.cs#L1417), line 1417.