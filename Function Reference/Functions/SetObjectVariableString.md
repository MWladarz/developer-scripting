# SetObjectVariableString

## Description
Sets the value of a VectorWorks object property. Used with properties requiring a STRING value.

For specific object selector index values, see the [[VS:Function Reference Appendix#Appendix G - Object Selectors|Appendix]].

```pascal
PROCEDURE SetObjectVariableString(
				h     : HANDLE;
				index : INTEGER;
				value : STRING);
```

```python
def vs.SetObjectVariableString(h, index, value):
    return None
```

## Parameters
|Name|Type|Description|
|---|---|---|
|h|HANDLE|Handle to object.|
|index|INTEGER|Object property index.|
|value|STRING|New value for property.|

## Examples
==== VectorScript ====
```pascal
SetPref(17,FALSE);
```
==== Python ====
```python

```

## Version
Availability: from VectorWorks9.0

## Category
* Object Info

