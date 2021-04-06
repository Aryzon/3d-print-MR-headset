Edit the Base model
-
If you want to edit a model it is easiest to use the base models. These are the models used before they are subdivided to generate a smooth model so they have way less vertices to work with.

Import to Gravity Sketch
-
If you have a VR headset you can use Gravity Sketch to modify the base models:
1) Import the models to your Landingpad.
2) Go into Gravity Sketch and import the models to your sketch. Set dimensions to millimetres and rotate to make it upright.
3) Go into edit mode of the model and select 'Convert to Subdivision Object'.
4) Optional: Delete all vertices on one half of the model and select 'Mirror'. It should automatically connect the center vertices.

Export Gravity Sketch
-
To use the model that was edited in Gravity Sketch you will need specific export settings:

Choose 'Export' and go to 'Advanced Settings' then set Sided Normals to 'Welded'.
Set Subd to 'Base' if you want to further edit this model in another program like Blender.
Set Subd to 'Smooth' if you want to export a printable model. Make sure the front surface is still flat and set the subdivision level on the model to max.

From Base to Printable model
-
1) Import the base model to Blender
2) Add a 'Subdivision Surface' modifier and set the viewport level to 3.
3) (Only for the main body) add a cube to the scene with settings:
	Location:
	x: -70 y: 68, z: -66
	Rotation:
	x: 0 y: 0 z: 45
	Scale
	x: 7.0 y: 1.5 z: 1.4
4) (Only for the main body) add a 'Boolean' modifier on the Main body, set it to Union and choose the cube from step 3 as the object.
5) With another 'Boolean' modifer set to 'Difference' slice a thin piece off the front of the main body and the phone holder to make it flat. Use a large enough cube for example as the object. 
5) Select the model you want to export. Choose File -> Export -> STL. Set it to export only the selected object and choose the up axis of your printer, (often Y-up).
