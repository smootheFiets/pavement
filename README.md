# pavement
Set of JOSM presets designed to quickly adjust highway tags surface, smoothness, and cycleway.  The one-click shortcuts below are for personal use by the author; their names probably don't make much sense to anyone else.  Sorry for that! (but feel free to adapt to your own needs)

This file provides two main presets:
* "state_of_the_road" with drop-down menus for surface and smoothness.
* "Cycle lane" with drop-down menu for presence and type of cycle lanes (https://wiki.openstreetmap.org/wiki/Key:cycleway - not to be confused with https://wiki.openstreetmap.org/wiki/Tag:highway%3Dcycleway): supported values are lane, shared_lane, no. If suffixes forward/backward are necessary to describe the situation on the ground, they need to be added by other means (manually?); they are not supported by this preset.  Note that cycleway=no is not usually a useful addition to the map; see https://www.openstreetmap.org/user/smootheFiets/diary/392144 for an exception.

Some frequently-used combinations of surface and smoothness are provided as separate one-click non-interactive presets for convenience/speed of tagging (pardon their quirky names):
* Jut: surface=asphalt, smoothness=good
* Beton OK: surface=concrete, smoothness=good
* Rumpelsteine: surface=paving_stones, smoothness=intermediate
* Gras: surface=grass, smoothness=bad
* Schelpenpadje OK: surface=fine_gravel, smoothness=intermediate
* Schelpenpadje slecht: surface=fine_gravel, smoothness=bad
* Panzerplatten: concrete_plates intermediate, width=1.5, segregated=no (standard on G13 fietspaden)
* Autobahn: asphalt, good, lanes=2, width=2.5 (standard G12a)

... plus three non-interactive smoothness presets:
* excellent
* good
* intermediate

## Version history
* 0.1_2020-07-10: first version, uploaded on Github on 2020-08-28 (private release)
* 0.2_2020-09-11: add "Panzerplatten" and "Autobahn"

## Author
smootheFiets
* https://www.openstreetmap.org/user/smootheFiets
* https://github.com/smootheFiets