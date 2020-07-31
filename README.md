# BlenSor - Blender Sensor Simulation Toolkit 

BlenSor is a modified blender version 2.79 to simulate range scanning devices.

## Build Instruction
This is an instruction to build the BlenSor as a Python module.
1. Refer to this link https://wiki.blender.org/wiki/Building_Blender/Other/BlenderAsPyModule
2. Create conda env -> `conda create -n blender python=3.6` Python version is critical to run blender correctly.
3. Activate conda env -> `conda activate blender`
4. Build as suggested in above link.
5. Install Numpy before running BlenSor in Python -> `conda install numpy`
6. Test the installation -> `python -c "import bpy; bpy.ops.render.render(write_still=True)"`

If successfully rendered, a png image will generated in /tmp/.png

Author: Fanghao Yang

for more information visit: www.blensor.org
