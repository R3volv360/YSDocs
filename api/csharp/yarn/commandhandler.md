# CommandHandler Delegate

Represents the method that is called when the Dialogue delivers a
[`Command`](/api/csharp/yarn/command.md).


```csharp
public delegate void CommandHandler(Command command);
```

## Parameters
|Parameter|Description|
|:---|:---|
|[`Command`](/api/csharp/yarn/command.md) command|The [`Command`](/api/csharp/yarn/command.md) that has been delivered.|


## See Also
* [`LineHandler`](/api/csharp/yarn/linehandler.md): 
Represents the method that is called when the Dialogue delivers a
[`Line`](/api/csharp/yarn/line.md).

* [`OptionsHandler`](/api/csharp/yarn/optionshandler.md): 
Represents the method that is called when the Dialogue delivers an
[`OptionSet`](/api/csharp/yarn/optionset.md).

* [`NodeStartHandler`](/api/csharp/yarn/nodestarthandler.md): 
Represents the method that is called when the Dialogue begins
executing a node.

* [`NodeCompleteHandler`](/api/csharp/yarn/nodecompletehandler.md): 
Represents the method that is called when the Dialogue reaches the
end of a node.

* [`DialogueCompleteHandler`](/api/csharp/yarn/dialoguecompletehandler.md): 
Represents the method that is called when the dialogue has reached
its end, and no more code remains to be run.

## Namespace
[`Yarn`](/api/csharp/yarn/README.md)

## Assembly
YarnSpinner.dll

## Source
Defined in [YarnSpinner/Dialogue.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner/Dialogue.cs#L326), line 326.