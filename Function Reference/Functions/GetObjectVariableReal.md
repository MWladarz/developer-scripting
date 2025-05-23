# GetObjectVariableReal

## Description
Returns the value of a VectorWorks object property. Used with properties returning a REAL value. Always returns values in mm, regardless of document units.

For specific object selector index values, see the [[VS:Function Reference Appendix#Appendix G - Object Selectors|Appendix]].

```pascal
FUNCTION GetObjectVariableReal(
				h     : HANDLE;
				index : INTEGER): REAL;
```

```python
def vs.GetObjectVariableReal(h, index):
    return REAL
```

## Parameters
|Name|Type|Description|
|---|---|---|
|h|HANDLE|Handle to object.|
|index|INTEGER|Object property index.|

## Examples
==== VectorScript ====
```pascal
dim_offset:= GetObjectVariableReal(h,4);
```
==== Python ====
```python
dim_offset = vs.GetObjectVariableReal(h,4)
```

## Version
Availability: from VectorWorks9.0

## Category
* Object Info

