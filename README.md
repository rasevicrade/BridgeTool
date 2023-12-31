# Demo
[Setup Example](https://drive.google.com/file/d/1vaHqmtV_9ZWy77LKMxUikcPWRw3ANaEh/view?usp=drive_link)

[Demo](https://drive.google.com/file/d/1jnPlGSLwNGs0uSs_zeI3mOjMNT4I_frW/view?usp=drive_link)

# What is it
A Houdini project allowing user to generate a bridge based on spline setup. Also contains HDA which can be dragged into Unreal Engine 5 for a simple setup.

# Available customizations
![image](https://github.com/rasevicrade/BridgeTool/assets/20711087/0fab1fb8-95cd-4cea-880d-bfb23328f1fd)
- User can set the length of the bridge, height of railings and distance between vertical ropes. 
- Simulation frame uses Houdini''s simulation to calculate position of ropes, user can select different frame to get different value of simulation in time (between start and hanging). Be careful with setting this value, as any frame requires all frames before it to be calculated, hence simulation becomes slower the bigger this value is.
- Once you are satisfied with positioning and sizes, press **Reset Simulation** button to calculate the position of ropes and planks!

