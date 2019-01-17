---
layout: post
title: "The roadmap"
categories: blog
date: 2019-01-15
---

v0.1
----

see [cadracks.org, v0.1]({% post_url blog/2019-01-11-Cadracks_org_v0.1 %})

v0.2
----

- PythonOCC scripts display

  PythonOCC is a great library that wraps OpenCascade with Python. 
  It is therefore possible to write the logic to define geometry in Python. 
  The script and its 3d representation (aka Shape) will be displayed side by side on the web interface.

- CadRacks-Core Part scripts display

  A Part will encapsulate the geometrical shape of the part as well 
  as its extra info: anchors to link to other parts and assemblies, 
  material, ... The resulting geometry and info will be viewable in the web 3d viewer.

- CadRacks-Core partzips display

  A partzip is a zipped file that contains static geometry (STEP, IGES, STL, BREP) and 
  extra info tied to this geometry. It is a means to reuse existing CAD files in new assembly definitions.

- Online CAD viewer improvements

  Add menu items to the viewer to trigger standard views: front, right, top, fit all ...

  Display using original colors, not the default platform color sequence.

- More documentation

  Document the notions of Part, Assembly, Anchor, Partzip ...
  
  More tutorials to create real projects

v0.3
----

- IFC files display

  Display Industry Foundation Classes, probably using IfcOpenShell.
  Make the IFC files wrappable as Part

- FreeCAD assembly3 files display

  Display of assembly3 FreeCAD files (anticipation for FreeCAD 0.19)

- Diff tool

  Create a diff-ing and merging tool for geometry, compatible with git.

- Extra info on stepzips and parts (PDM)

  Display available PDM info when selecting a part in the 3D viewer

- Ipynb, GCode, Dxf, Dwg, Svg files display

  3d or 2d display of these file formats.


v0.4
----

- Cadracks IDE (Integrated Development Environment)

  Equivalent of a software development IDE, but for geometry. Side by side display of 
  geometry definition scripts and 3d view. Side by side display of assembly definition scripts and 3d view. 
  Display of static file formats and partzip formats.

- Cadracks FreeCAD Workbench

  FreeCAD workbench that helps with the definition of Anchors (assembling helper) on existing geometry.

- Cadracks-core assembly display

  3d web display of Assembly definitions (Python script assembly definitions)

- Cadracks-core libraries integration

  3d web display of parts libraries, reusable in projects.

- Open Source Vehicle model as example

  Open Source Vehicle model as a proof-of-concept for CadRacks

- Helper libraries

  Using PythonOCC directly might be hard! Add libraries that make the syntax simpler or that automate common tasks.


v1.0
----

- Private repositories

  On cadracks.org, private repositories cannot display CAD files for technical reasons. 
  Find a solution to this problem.

v1.1
----

- Simulations files display

  3d display of simulation (CFD, FEA) results. Paraview-like.


