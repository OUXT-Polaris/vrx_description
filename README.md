# vrx_description

This package contains

- VRX machine's configure files
- The xacro and urdf files that automatically generatetd


## Xacro & URDF file generation
See following for more details.
https://bitbucket.org/osrf/vrx/wiki/tutorials/Creating%20a%20custom%20WAM-V%20Thruster%20and%20Sensor%20Configuration%20For%20Competition

## Launch with VRX environment
You need to set parameter `urdf` to the generated urdf file.  

```bash
$ roslaunch vrx_gaxebo sandisland.launch urdf:=<path to the urdf file>
```

For more details, see following.
https://bitbucket.org/osrf/vrx/wiki/tutorials/Creating%20a%20custom%20WAM-V%20Thruster%20and%20Sensor%20Configuration%20For%20Competition
