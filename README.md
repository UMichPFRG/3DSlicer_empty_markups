# Read Me
Example of empty [3D Slicer](https://www.slicer.org/) markup list to simplify project workflow after measurements have been establish and it production phase.
There is an example for each markup type.
This only works in Slicer 5.0.2 or above.

## Creating the empty markups lists 
**Option 1**
- Identify what kind of markups you will be using, i.e. 2 closed curves, 1 ruler and 1 list of points
- Download the files and change the names appropriately as relevant for your project (after files have been downloaded):
    - closed_curve.mrk.json (from example above, if you need 2 closed curves, copy this file after download so you have 2 closed curves type files)
    - ruler.mrk.json 
    - list_of_points.mrk.json


**Option 2**
- Create the empty markups directly in Slicer
![Screenshot of empty markups in 3D Slicer](https://github.com/UMichPFRG/3DSlicer_empty_markups/blob/main/create_empty_markup_lists.PNG)
- Save the .mrk.json files (in the save menu, change from .mrb to .mrml, deselect all, and select only the .mrk.json files)
![Screenshot of saving empty .mrk.json files](https://github.com/UMichPFRG/3DSlicer_empty_markups/blob/main/saving.PNG)

## Loading empty markup lists into 3D Slicer
- Drop files into [3D Slicer](https://www.slicer.org/), do this after you loaded the .mrb into the scene. When you save the .mrb it will now include the markups as well
![Screenshop loading empty files into Slice](https://github.com/UMichPFRG/3DSlicer_empty_markups/blob/main/add_drop_into_scene.PNG)
