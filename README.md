# pavement
Set of JOSM presets designed to quickly adjust highway tags surface, smoothness, and cycleway.

This file provides two main presets:
* state_of_the_road with drop-down menus for surface and smoothness
* lane with drop-down menu for presence and type of cycle lanes (https://wiki.openstreetmap.org/wiki/Key:cycleway - not to be confused with highway=cycleway): supported values are lane, shared_lane, no. If suffixes forward/backward are necessary to describe the situation on the ground, they need to be added by other means (manually?); they are not supported by this preset.

Some frequently-used combinations of surface and smoothness are provided as separate one-click non-interactive presets for convenience/speed of tagging:
* Jut: surface=asphalt, smoothness=good
* Beton OK: surface=concrete, smoothness=good
* Rumpelsteine: surface=paving_stones, smoothness=intermediate
* Gras: surface=grass, smoothness=bad
* Schelpenpadje OK: surface=fine_gravel, smoothness=intermediate
* Schelpenpadje slecht: surface=fine_gravel, smoothness=bad

... plus three non-interactive smoothness presets:
* excellent
* good
* intermediate

## Author
smootheFiets
* https://www.openstreetmap.org/user/smootheFiets
* https://github.com/smootheFiets

## Version history
* 0.1_2020-07-10: first version, uploaded on Github on 2020-08-28

