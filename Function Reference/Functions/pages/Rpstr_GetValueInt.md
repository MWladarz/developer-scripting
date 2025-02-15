# Rpstr_GetValueInt

## Description
Get an integer value from the VectorScript value repository.

```pascal
FUNCTION Rpstr_GetValueInt(
				name         : STRING;
				defaultValue : INTEGER) : INTEGER;
```

```python

def vs.Rpstr_GetValueInt(name, defaultValue):
    return INTEGER
```

## Parameters
|Name|Type|Description|
|---|---|---|
|name|STRING|The name of the value.|
|defaultValue|INTEGER|Default value if the name does not exist in the VectorScript value repository.|

## See Also
VS Functions:
[Rpstr_RemoveValues](Rpstr_RemoveValues.md)| [Rpstr_RemoveValue](Rpstr_RemoveValue.md)| [Rpstr_GetValueBool](Rpstr_GetValueBool.md)| [Rpstr_SetValueBool](Rpstr_SetValueBool.md)| [Rpstr_GetValueInt](Rpstr_GetValueInt.md)| [Rpstr_SetValueInt](Rpstr_SetValueInt.md)| [Rpstr_GetValueReal](Rpstr_GetValueReal.md)| [Rpstr_SetValueReal](Rpstr_SetValueReal.md)| [Rpstr_GetValueStr](Rpstr_GetValueStr.md)| [Rpstr_SetValueStr](Rpstr_SetValueStr.md)

## Version
Availability: from Vectorworks 2012
## Category
* Utility

