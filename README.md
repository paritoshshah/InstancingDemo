InstancingDemo
==============

Efficiently render copies of static meshes using instanced drawing:

* 900+ cubes in a single instanced draw call, 5% CPU usage, 60 FPS
* location offsets done right in the shader using gl_InstanceID
* works on all iOS devices, uses instancing opengl extension
