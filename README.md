## OpenGL setup for vscode

This is a simple setup for vscode to use OpenGL with C++.

## Requirements
Download and install the following:
- [mingw-w64](https://github.com/fatbrother/mingw64)
- [freeglut](https://www.transmissionzero.co.uk/software/freeglut-devel/)
- [glew](https://sourceforge.net/projects/glew/files/glew/2.1.0/glew-2.1.0-win32.zip/download)

## Setup
1. Create a new folder for your project
2. Move the .vscode folder into your project folder
3. Change the include paths in the .vscode/c_cpp_properties.json file to the paths of your mingw-w64
4. Download the freeglut and glew zip files and extract them into your C:\
5. Use #include <GL/glew.h> and #include <GL/glut.h> to use libraries
6. Use #include "glm/glm.hpp" and #include "glm/gtc/type_ptr.hpp" to use glm
7. Use CTRL+SHIFT+B to build your project
8. Use the library happily