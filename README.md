##OVERVIEW

**glTF is a work in progress and not an official Khronos-ratified specification**  
As an initiative from the COLLADA Working Group, this project stands in Khronos repository.  
Everyone is welcomed to contribute and provide feedback. 

## Specification  

Can be found [here](https://github.com/KhronosGroup/glTF/blob/master/specification/README.md).  
_This is a work-in-progress from the COLLADA Working Group; it is not an official Khronos-ratified specification yet.  It is incomplete and subject to change.  We've made it available early in the spirit of transparency to receive early community feedback.  Please create [issues](https://github.com/KhronosGroup/glTF/issues) with your feedback._

_In particular, the definition of materials are in flux, and work on animations and texture and geometry compression are still in the early stages.  We are also initially focusing on WebGL, OpenGL and OpenGL ES need additional considerations.  The related open-source tools are also not 100% compatible with this spec yet._

## Converter

A [converter](https://github.com/KhronosGroup/glTF/wiki/converter) can be used to produce glTF assets out of COLLADA.

## Viewer

```
git clone https://github.com/KhronosGroup/glTF.git
cd glTF
git submodule update --init --recursive
```

Start a web server in `glTF/webgl` which contains an `index.html` page linking to the demos.

#### Workflow

this project provides a reliable toolchain based on OpenCOLLADA.
Starting from exporter plugins in major authoring tools to COLLADA parsing when converting to JSON, 
OpenCOLLADA is where all efforts to import/export COLLADA files are centralized.
