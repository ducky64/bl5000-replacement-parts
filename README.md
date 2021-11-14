# bl5000-replacement-parts
Custom replacement mechanical parts designs for the Hios BL-5000 electric screwdriver.

Designed in FreeCAD. Works on 3d-printing processes.

License: [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

## Measurements
### Metal Connector
- Overall height: 19.55 mm
- Threaded diameter: 17.78 mm
- Threaded section height: ~7.5 mm
  - ~4mm sticks out past the plastic housing
- Flange diameter: 22.95 mm
- Flange height: 6.00 mm
- Inner diameter: 16.00 mm
- Inner height: ~6 mm
- Notch distance between points: ~7.72 (on plastic side), ~7.80mm (on metal side)
- Notch inner is approximately flush with threaded section on plastic side
- Width between 'flats' of notch: 21.45 mm


## Lever
![Image](../master/docs/lever1.png?raw=true)
![Image](../master/docs/lever2.png?raw=true) 
 
Replacement lever (trigger) part. Has a cutout over the switch to allow operating mode to be switched without uninstalling the lever.

External components required:

- A 3mm (diameter) x 2mm (length) cylidrical magnet, to be press-fitted into the slot near the end of the lever. This is the "actuator", the screwdriver has a magnetic field sensor as the trigger.
- A spring, between 4mm and 6mm in diameter, inserted near the pivot point. This provides return force. If you already have a lever, you can take the spring from that.
- A ~20mm M3 screw, used for the pivot. If you already have a lever, you can take the screw from that.

## TypeCTriggerPlate
Replacement rear connector "plate" designed to take a USB Type-C PD Trigger module. Will need internal rewiring and soldering.

This has two pieces, as two boolean operations in the FreeCAD file. The intersection piece is the outer plate, while the subtraction piece provides a backing to prevent the Type-C connector from sliding inside.

## AndersonConnectorPlateHalf
![Image](../master/docs/anderson-half-plate.png?raw=true)

Replacement rear connector "plate" designed to accept an Anderson Powerpole 15/30/45A housings. Will need internal rewiring and soldering, but these screwdrivers will work off 12V. Print two of these, sandwich a Powerpole connector between them, and insert them where the metal circular connector used to be. May require a bit of trial-and-error to properly tolerance the part so that it is neither too loose or too large.
