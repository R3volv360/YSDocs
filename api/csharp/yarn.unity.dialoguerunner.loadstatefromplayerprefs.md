# DialogueRunner.LoadStateFromPlayerPrefs(string)

Method in [DialogueRunner](/api/csharp/yarn.unity.dialoguerunner.md)

## Summary


Loads all variables from the  <code>PlayerPrefs</code>  object into
the Dialogue Runner's variable storage.


```csharp
public bool LoadStateFromPlayerPrefs(string SaveKey = "YarnBasicSave")
```

## Remarks

<p>
This method loads a string containing JSON from the <code>PlayerPrefs</code> object under the key <code>SaveKey</code>,
deserializes that JSON, and then uses the resulting object to set
all variables in <a href="yarn.unity.dialoguerunner.variablestorage.md">VariableStorage</a>.
</p> <p>
The loaded information can be stored via the <a href="yarn.unity.dialoguerunner.savestatetoplayerprefs.md">SaveStateToPlayerPrefs(string)</a> method.
</p>

## Parameters

|Name|Description|
|:---|:---|
|`string` SaveKey|The key to use when storing the variables.|

## Returns

<code>true</code>  if the variables were successfully
loaded from the player preferences;  <code>false</code> 
otherwise.

## See Also

* VariableStorageBehaviour.SetAllVariables\(Dictionary\<string,     float\>, Dictionary\<string, string\>, Dictionary\<string, bool\>,     bool\)
