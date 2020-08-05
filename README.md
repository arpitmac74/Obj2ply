# Object2ply
Complete conversion of object files to ply files with color encdoing as well as uv coordiantes.
## Model Converter OBJ to Ply. a Python extension module for coversion of object to ply with full properties along with texture coordinates, color and alpha coordinates.
Currently there is no python extension to fully converts the data,vertex colors, they lack face conversion, vt coordinates and vn properties as well.
Can be used to any type of object file conversion to ply.
The application is solely used in the field of computer graphics for game engines such as blender and Unity.

## Dependencies
```
import numpy
```
## Notes

- Make sure that the version of NumPy used for compiling the readply
  extension has the same API version as the one that is used by Blender
  (the official binary distributions of Blender include a version of NumPy)
- The `readply` extension module can be compiled for both Python 2.x and 3.x,
  even though Blender uses Python 3.x
- Texture coordinates may be stored in s+t or u+v vertex fields, depending
  on what property names the PLY file being read uses
## Author

Arpit Maclay(arpitmac74@gmail.com), Vidalign Inc.

