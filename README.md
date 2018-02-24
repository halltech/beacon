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

Part | Quantity | Info | Reccomended Source
---- | -------- | ---- | ------------------
Nema17 Steppers	| 4 | 0.59 Nm torque reccomended
E3D V6 Hotend | 1 |
MGN12 Linear Rails | 4 |


































## Credits
Developed and Designed by:
- Matthew Hall [[@MH15](https://github.com/MH15)]
- Peter Hall [[@peterhall16](https://github.com/peterhall16)]

Many thanks to:
- The folks over at the [[Reprap Forum](http://forums.reprap.org)] for provided such a condensed pool of knowledge.
- My high school shop teacher for letting me print part after part on the first two versions of this machine.
