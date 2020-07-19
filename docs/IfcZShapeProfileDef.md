IfcZShapeProfileDef
===================
_IfcZShapeProfileDef_ defines a section profile that provides the defining
parameters of a Z-shape section to be used by the swept area solid. Its
parameters and orientation relative to the position coordinate system are
according to the following illustration. The centre of the position coordinate
system is in the profile''s centre of the bounding box.  
  
> HISTORY  New entity in IFC2x2.  
  
{ .change-ifc2x4}  
> IFC4 CHANGE  Type of _FilletRadius_ and _EdgeRadius_ relaxed to allow for
> zero radius.  
  
Figure 1 illustrates parameters of the Z-shape profile definition.  
  
  
  
  
  
|  
![Z-shape profile](figures/ifczshapeprofiledef.gif)  
  
  
|  
  

_Position_  
  
The parameterized profile defines its own position coordinate system.  
The underlying coordinate system is defined by the swept area solid  
that uses the profile definition. It is the xy plane of:

  

  

  * IfcSweptAreaSolid.Position
  

  

By using offsets of the position location, the parameterized profile  
can be positioned centric (using x,y offsets = 0.), or at any position  
relative to the profile.

  
  
  
  
---|---  
  
  
  
  
  

Figure 1 -- Z-shape profile  
  
  
  
[ _bSI
Documentation_](https://standards.buildingsmart.org/IFC/DEV/IFC4_2/FINAL/HTML/schema/ifcprofileresource/lexical/ifczshapeprofiledef.htm)

