# Engineering Sketch Pad (ESP)
User Manual:  
https://flexcompute.github.io/EngineeringSketchPad/EngSketchPad/ESP/ESP-help.html  
Valid CSM statements:  
https://flexcompute.github.io/EngineeringSketchPad/EngSketchPad/ESP/ESP-help.html#sec5.4

# Staging prebuild artifacts for commit

The artifacts should be build on a machine with an old enough version of glibc to cover expected deployments.

```
[edit download.sh and stage.sh to confirm versions]
./download.sh
./stage.sh
```
which rebuids libegads.so to resolve indirect OpenCASCADE libraries.
Commit new, removed, and modfied files.
