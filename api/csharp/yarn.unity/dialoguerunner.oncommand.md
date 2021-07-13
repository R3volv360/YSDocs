# DialogueRunner.onCommand Field

A [`DialogueRunner.StringUnityEvent`](/api/csharp/yarn.unity/dialoguerunner.stringunityevent.md) that is called when a <see cref="!:Command"></see> 
is received.


```csharp
public DialogueRunner.StringUnityEvent onCommand
```
## Remarks

Use this method to dispatch a command to other parts of your
game. This method is only called if the <see cref="!:Command"></see>
has not been handled by a command handler that has been added
to the
[`DialogueRunner`](/api/csharp/yarn.unity/dialoguerunner.md), or by a method on a <see cref="!:MonoBehaviour"></see> in the scene with the attribute [`YarnCommandAttribute`](/api/csharp/yarn.unity/yarncommandattribute.md). {{<note>}} When a command is
delivered in this way, the [`DialogueRunner`](/api/csharp/yarn.unity/dialoguerunner.md) 
will not pause execution. If you want a command to make the
DialogueRunner pause execution, see <see cref="!:AddCommandHandler(string, CommandHandler)"></see>.
{{</note>}}

This method receives the full text of the command, as it
appears between the `<<` and `>>`
markers.




## See Also
* [`YarnCommandAttribute`](/api/csharp/yarn.unity/yarncommandattribute.md): 
An attribute that marks a method on a <see cref="!:MonoBehaviour"></see>
as a [command]( {{<ref
"/docs/unity/working-with-commands">}}).

* [`DialogueRunner.StringUnityEvent`](/api/csharp/yarn.unity/dialoguerunner.stringunityevent.md): 
A type of <see cref="!:UnityEvent"></see> that takes a single string
parameter. 

## Namespace
[`Yarn.Unity`](/api/csharp/yarn.unity/README.md)

## Assembly
YarnSpinner.dll

## Source
Defined in [../YarnSpinner-Unity-Dev/Packages/YarnSpinner/Runtime/DialogueRunner.cs](https://github.com/YarnSpinnerTool/YarnSpinner-Unity//blob/develop/Runtime/DialogueRunner.cs#L172), line 172.