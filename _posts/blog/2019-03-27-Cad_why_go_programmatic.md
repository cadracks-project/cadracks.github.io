---
layout: post
title: "CAD : why go programmatic?"
categories: blog
date: 2019-03-27
---

If you have to design a door block for your home, programming is no the first 
thing that comes to mind. Creating geometry with programs is less intuitive 
and has a steeper learning curve than designing in a CAD soft with a nice UI. 
When the project becomes more complex, the steeper learning curve is worth 
taking up. You will be fighting an uncommon way to design stuff, sometimes 
unfriendly and cumbersome APIs but there are many rewards along the way.

When one thinks of CAD, clicking menus and dragging the mouse to create shapes 
usually comes to mind. Yet, this is not the only way to do it: you can 
actually write a program that creates shapes and geometry. 
This is called programmatic CAD and it has many advantages.

Since programmatic CAD is normally done using a CAD Kernel Library that keeps 
backwards compatibility, you are no longer dependent on vendor software 
versions. Even free CAD 'click factories' programs suffer from this: try to 
open a 5 year old model in the latest version .... 
And with programmatic CAD, anything you design is parametric. Change that 
radius, no problem, everything adapts.

The possibilities are not restrained by what the software vendor has in mind. 
You can connect to a server, retrieve some data that you use as input for 
your design. You can combine logic and data, or separate it (better). 
The choice is yours.

But the best is yet to come: you can version your CAD geometry generating 
programs like any other program. Your CAD project is versionable with git or 
any other version management tool. An this opens the door to asynchronous and 
heterogeneous collaboration. That's better suited to open hardware projects; 
when any contributor might be working on improvements anywhere, at any time 
and with a different set of tools.

Programmatic CAD is also great to learn programming: the feedback is visual, 
3d shapes, arrays of cubes ... make the learning more fun than console outputs. And thanks to the great OpenCascade and its PythonOCC bindings, it is free !

Up to date and outside of proprietary CAD scripting, the most famous programmatic CAD initiative is OpenSCAD. And it is 
great and used. CadRacks goes by the same philosophy as OpenSCAD, trying to 
add an industrial-grade CAD kernel and ways to assemble parts as intuitively 
as possible.


Pros
----

- Get out of the click factory
- Software version independence. Only depend on kernel that normally keeps backwards compatibility.
- Parametric by design
- Higher abstraction and possibilities
- Versionable like software projects
- Easier asynchronous and heterogeneous collaboration
- Good to learn programming
- Free


Cons
----

- Less intuitive / Steep learning curve
- Uncommon approach
- Sometimes unfriendly APIs