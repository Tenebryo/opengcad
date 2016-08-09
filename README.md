# opengcad

OpenGCAD is a psuedo-CAD program inspired by the [Antimony CAD program](http://www.mattkeeter.com/projects/antimony/3/) 
that acts as an external editor for OpenSCAD. A 2D or 3D object is designed by creating a graph of nodes that represent
either geometric primitives or CSG (Constructive Solid Generation). Each node has inputs that can be constants or linked
to the outputs of other nodes. OpenGCAD generates an OpenSCAD program from this graph, which alows a 2D or 3D object file
be created. This program may or may not be useful or helpful to everyone, but is intended to make OpenSCAD more
intuitively accesible to non-programmers.
