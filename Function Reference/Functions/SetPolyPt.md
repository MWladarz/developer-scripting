# SetPolyPt

## Description
Procedure SetPolyPt sets the location a specified vertex in the referenced polygon.

```pascal
PROCEDURE SetPolyPt(
				objectHd : HANDLE;
				index    : INTEGER;
				xR       : REAL;
				yR       : REAL);
```

```python
def vs.SetPolyPt(objectHd, index, xR, yR):
    return None
```

## Parameters
|Name|Type|Description|
|---|---|---|
|objectHd|HANDLE|Handle to polygon.|
|index|INTEGER|Index of vertex.|
|xR|REAL|New X coordinate of vertex.|
|yR|REAL|New Y coordinate of vertex.|

## Remarks
(Gerard Jonker, 2007 Jan. 8) Please have a look at my [http://www.vectorlab.info/index.php?title=Absolute_Origin comments on the VectorLab] regarding this function, concerning index and origin.

([[User:CBM-c-|_c_]], 2010 Dec. 25) From Raymond Mullin: ''It only works for Polygons, and not for Polylines.''. Using this function on polylines will rise an invalid handle warning. Please be careful on conversions from polygon to polyline through [[VS:InsertVertex| InsertVertex]] or other routines. See [[VS:SetPolylineVertex| SetPolylineVertex]]. I thus remove the word ''polylines'' from the description above.

## See Also
For polygons:
* [GetPolyPt| GetPolyPt](GetPolyPt|%20GetPolyPt.md)

For polylines:
* [GetPolylineVertex| GetPolylineVertex](GetPolylineVertex|%20GetPolylineVertex.md)
* [SetPolylineVertex| SetPolylineVertex](SetPolylineVertex|%20SetPolylineVertex.md)

## Version
Availability: from All Versions

## Category
* Objects - Polys

