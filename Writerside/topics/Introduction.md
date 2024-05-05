# Introduction

**Documentation for systems analysis workflow tools.**

Analysis takes place with Wolfram Language and System Modeler, a Modelica tool, using OpenIPSL. Numbers of parameters, interconnections, and parameter complexity make analysis prone to errors. The intention of this document is to introduce methods to simplify gathering, validation, and configuration of systems by rapid generation of parameters and presenting them as a Modelica document.

This document will focus on power system with expectations of incorporating mechanical and gas systems as necessary. There are already tools for analyzing power transmission systems including Siemens PSS®E and distribution systems including DNV's Synergi Electric. Mathematica's and System Modeler's real advantage is the flexibility of analysis. The problem to overcome is the workflow. The idea of drag and drop can not be achieved without a vast database of information.
# Power
Power systems can be broken into two: transmission and distribution. A distribution system is typically radial, a directed acyclic graph (DAG), while a transmission system is not. Both have non-linear components.

In typical systems, component parameters are created from the vast testing documentation for power system components. They don't change unless new construction takes place. Therefore, parameters remain in the system, and testing documentation is eliminated. This eliminates the possibility of reusing the documentation and learning for the tests.

Component validation is almost impossible without the test data. Therefore, a method to store and configure the data for analysis is necessary. This requires a system database more extensive than anything presently available. Presently, I understand implementing a .NET interface with a Microsoft SQL data repository. This is in "the works" and constantly changing.

The component analysis will take place with Wolfram Language and the system analysis will take place with System Modeler. Time series analysis of load data is presently a Microsoft Access front end into SQL back end. I would like to move this to a Wolfram Language tool.
# References
_Engineering System Dynamics: A Unified Graph-Centered Approach, Second Edition_ by Forbes T. Brown

_Modelica by Example_ by Michael M. Tiller

_Query: Getting Information from Data with the Wolfram Language_ by Seth J. Chandler

ContosoUniversity on ASP.NET Core 6.0 on .NET 6 and Razor Pages
https://github.com/jbogard/ContosoUniversityDotNetCore-Pages
(Integration testing is not implemented even though it is a good idea to do so. Entity Frame is used instead of grate.)

OpenIPSL: Open-Instance Power System Library for dynamic analysis
https://github.com/OpenIPSL/OpenIPSL