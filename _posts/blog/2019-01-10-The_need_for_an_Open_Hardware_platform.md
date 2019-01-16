---
layout: post
title: "The need for an Open Hardware platform"
categories: blog
date: 2019-01-10
---

The context
-----------

Thanks to worldwide internet access and collaborative development hubs, Open Source 
software has become ubiquitous. Many commercial softwares now have an Open Source 
counterpart that is as good and sometimes better. Think of LibreOffice, Apache and Nginx for web servers, 
OpenFoam for CFD, Code Aster for Finite Element Analysis ... and the list may go on and on.

Yet, Computer Aided Design is trailing a bit. Some initiatives are incredibly good (FreeCAD, Open Cascade ...) 
but there is no complete solution that would compete with high end, tens of thousands dollars a seat, solutions. 
So, if you are working on a hobby project, a project that serves a niche, or on a more ambitious design on your spare time, 
it is very unlikely that you have access to these costly solutions. Let's not even mention the case where twenty people work 
on the same project: how likely is it that they even all use the same software?

CAD, CAM, CAE has historically been dominated by big commercial players. Yet, some Open Source 
initiatives are becoming more and more credible and their capabilities and start to 
compete with the big players in some areas. Some Open Source initiatives are even 
on par with the commercial solutions in specific areas:
- FreeCAD for parametric geometry;
- Open Cascade as a CAD kernel;
- solvespace as a constraints solver

Yet, big players also offer the possibility to work as a team on projects more complex 
than hobby level; something that is seldom, if ever, found in Open Source CAD or in reasonably priced CAD softs.


CadRacks
--------

The goal of the CadRacks project is to build on what is already there and working well. 
One of the goals is to bring the team working functionalities to Open Hardware projects that are present in high 
end solutions without having to sign a several tens of thousands dollars check.

By assembling the best bits from the Open Source world, and innovating a bit, we believe we can offer a great tool at zero cost!

Our vision is to create an Open Hardware projects hub where engineers/innovators/enthusiasts can contribute 
from anywhere in the world, at any time, with any CAD software.

To reach that goal, we feel the following needs must be addressed:

- a way to work together on Open Hardware projects, a Github for CAD if you like

  [cadracks.org](http://cadracks.org) serves this purpose.

- a way to assemble heterogeneous files (different formats) into sub-assemblies and assemblies

  A very innovative way is to add vectors to specific locations on parts. These vectors can be used to define 
  how parts are assembled and constrained relative to each other. This is extremely flexible and allow 
  to mate a STEP defined part with an STL defined one, completely independent from proprietary formats.

- the possibility to define a part or an assembly via scripting, and to have these script defined parts ready to be 
  assembled with statically defined parts or assemblies.
- a way to add data (material, price, suppliers ...) to the parts and assemblies that define a project;
- a standardized way to communicate building instructions;
- a way to provide users with parts libraries, so that they can concentrate on their projects without reinventing the wheel ... or a normalized bolt.
