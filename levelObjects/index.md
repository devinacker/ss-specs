## Level Objects

A level object is anything that is not part of the basic level layout (the tile map).

Objects are identified using three values. They are divided by class, subclass and type. In this documentation such an identifier will be written as ```c/s/t```. For example, the cyberjack port is ```9/2/0```.

Information about level objects exists in two places:
* Static properties, describing an object in general
* Instance data, describing the state of a specific object instance in the game

The static properties are stored in a separate file. See [Property Files](../fileFormat/PropertyFiles.md) for basic information.
Instance data is stored as part of an archive. See [Level Objects](../archives/levelObjects.md) for basic information.

The following object classes exist:
* 0 Weapons
* 1 Ammo
* 2 Projectiles
* 3 Grenades and explosives
* 4 Patches
* 5 Hardware
* 6 Software and logs
* 7 Scenery and fixtures
* 8 Gettable and other objects
* 9 Switches and panels
* 10 Doors and gratings
* 11 Animations
* 12 Traps and markers
* 13 Containers
* 14 Critters