# Beacon 3D Printer

## About
The third iteration in our quest to build a custom 3D printer has finally succeeded to a point where we can release our work to the public. We hope this model will provide a price-efficient route for those making their own 3D printers as well as a high quality machine for experimentation and design.

### Design Goals
While the goals of this project evolved over time, we feel these ideas impacted Beacon the most:
- Keep the cost low enough for students such as ourselves to construct and experiment with. You should be able to build one for around $350.
- Use high quality components such as linear rails instead of smooth rods, etc.
- Maintain the "reprap"-esque nature of the machine by encouraging customization. 

### Project Story
TODO

## Guide
All of the STL files needed are located under the `stl` directory. Source files in Autodesk Inventor format are found under `source`.

### Printing Parts
We designed the parts with ease of printing in mind. None of them require high resolution, so printing shouldn't take too long. Reccomended settings include:
- 0.25mm layer height
- 20% triangular infill
- 3 perimeters/shells (this is important for strength)
- whatever else suites your workflow
Some parts require support, some don't. Once you've printed the parts you can proceed to drill out an holes where screws won't fit and remove the supports/rafts.

### Sourcing
Many of the components can be found anywhere. Take these links with a grain of salt, most of them will probably not be the cheapest source.

Part | Quantity | Info | Recomended Source
---- | -------- | ---- | ------------------
Nema17 Steppers	| 4 | 0.59 Nm torque reccomended
E3D V6 Hotend | 1 |
MGN12 Linear Rails | 4 |
Smoothieboard 4x | 1 | any controller should work
6mm GT2 Belt | | about 2 meters
Aluminum Extrusions | | SEE BELOW


You can either cut your extrusions to length yourself or have them cut to ship by a service such as [Misumi](https://us.misumi-ec.com/) like we did. It is almost equivalent in price and shipping is much less because the pieces are shorter.

Extrusion Name | Type | Length | Quantity
-------------- | ---- | ------ | --------
X Axis | 2020 | | 1
Y Axis | 2040 | | 2
Z Axis | 2040 | | 1
Center Brace | 2040 | | 1
Front/Back | 2040 | | 2

TODO

### Assembly
TODO: make google slides assembly instructions and link
Based on the [assembly instructions](https://slides.google.com) assembly is rather straightforward. Some tips, however, are listed below:
1. Do not tighten the t-nuts to tight, you will break the plastic.
2. You cannot let the blocks slide off the linear rails. The bearings might fall out. I may or may not have done this.
3. Read the [Smoothieboard documentation](http://smoothieware.org/3d-printer-guide) THOURGHLY before plugging anything in. If you opt to use a different board (Ramps, Duet, etc.) read their respective docs. I have fried two Ramps boards in the past for the silliest of reasons.
Google Slides presentation also available [here](documentation/assembly.pdf) in PDF format

## Credits
Developed and Designed by:
- Matthew Hall [[@MH15](https://github.com/MH15)]
- Peter Hall [[@peterhall16](https://github.com/peterhall16)]
Contact me (text preferred) at +19378464465 if you have any questions or need assistance in clarifying these shoddy instructions.

Many thanks to:
- The folks over at the [Reprap Forum](http://forums.reprap.org) for provided such a condensed pool of knowledge.
- My high school shop teacher for letting me print part after part on the first two versions of this machine.

