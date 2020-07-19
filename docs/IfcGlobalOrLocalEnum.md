IfcGlobalOrLocalEnum
====================
This enumeration type defines if the local object coordinate system or the
global world coordinate system for the project is used to describe the measure
values of entities which have a reference to this type.  
  
> NOTE  The world coordinate system is given by the
> _IfcGeometricRepresentationContext.WorldCoordinateSystem_ and is unique
> within the project. The local (or object) coordinate system is given
> by_IfcProduct.ObjectPlacement_ and is used by all _IfcRepresentation_''s
> within the _IfcProduct.Representation_.  
  
> HISTORY  New enumeration in IFC2x2.  
[ _bSI
Documentation_](https://standards.buildingsmart.org/IFC/DEV/IFC4_2/FINAL/HTML/schema/ifcrepresentationresource/lexical/ifcglobalorlocalenum.htm)


Attributes
----------
| Attribute     | Definition   |
|---------------|--------------|
| GLOBAL_COORDS |              |
| LOCAL_COORDS  |              |