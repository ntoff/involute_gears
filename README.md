parametric involute gears + gear fitting script 

storing here for safe keeping

parametric involute gears modified to:
* remove depreciated openscad code
* fix incorrect polyhedron faces (bevel gears now render correctly on F5)

spur fitter script modified to:
* add variables for some of the stuff inside the gear generator script so you don't have to edit 2 scripts to make a set of gears

Original greg frost gear script: https://www.thingiverse.com/thing:3575

Original spur  gear fitter script: https://www.thingiverse.com/thing:6894

To make it work, change line 75 in spur_generator.scad from `//example_gears();` to `example_gears();` (just remove the //'s)
