# tips

rosrun xacro xacro.py pan_tilt.xacro > pan_tilt_generated.urdf

roslaunch urdf_tutorial display.launch model:='$(find urdf_tutorial)/urdf/01-myfirst.urdf'

rosrun collada_urdf urdf_to_collada "MY_ROBOT".urdf "MY_ROBOT".dae

you can render the kuri model using the guide as above.

