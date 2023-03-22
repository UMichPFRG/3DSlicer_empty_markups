# Read Me
Example of empty [3D Slicer](https://www.slicer.org/) markup list to simplify project workflow after measurements have been establish and it production phase.
There is an example for each markup type.
This only works in Slicer 5.0.2 or above.

## How to use?
** Starting production phase of a new subject **
## Creating the empty markups lists 
** Option 1 **
- Identify what kind of markups you will be using, i.e. 2 closed curves, 1 ruler and 1 list of points
- Download the files and change the names appropriately as relevant for your project (after files have been downloaded):
    - closed_curve.mrk.json (from example above, if you need 2 closed curves, copy this file after download so you have 2 closed curves type files)
    - ruler.mrk.json 
    - list_of_points.mrk.json


** Option 2 **
- Create the empty markups directly in Slicer
- Save the .mrk.json files (in the save menu, change from .mrb to .mrml, deselect all, and select only the .mrk.json files)


## Loading empty markup lists into 3D Slicer
- Open .mrb file in [3D Slicer](https://www.slicer.org/) and drop the files into the Slicer Scene:
