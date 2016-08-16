# PyCSpace
### A python module that generates C-space visualizations with dynamic user interaction.

" _In classical mechanics, the parameters that define the configuration of a system are called generalized coordinates, and the vector space defined by these coordinates is called the configuration space of the physical system._ " (from [Wikipedia](https://en.wikipedia.org/wiki/Configuration_space)).

In determining the optimal or possible paths for an object in space, one must understand the limitations introduced by the relevant geometries, topology, and movement freedoms in a defined scope. Configuration space (or "C-space") is a means of understanding possible positioning of an object (or objects) as it (or they) relate to the space with respect to DOFs and obstacles. While C-space is an optional transform for any N-dimensional space, this Python module works exclusively with 2-dimensional visualizations that may serve as top-view C-space for planar restricted 3D objects/obstacles.

The features included in this Python module include:
+ __C-SPACE VISUALIZATION__ : A graphical generation of c-space for any positioning of an object and obstacles
+ __ACTIVE MANIPULATION__ : Click-and-adjust interaction style for rapid regeneration of C-space (translational and rotational controls)
+ __OBJECT PROPERTY DEFINITION__ : Input options for DOFs and special properties (e.g. Is the system in question holonomic or nonholonomic?)
