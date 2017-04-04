# OpenCL-path-tracing-tutorial-3-Part-2
OpenGL viewport with interactive camera and depth-of-field (WIP, needs a better random number generator for depth of field)

Compiling instructions (for macOS)

- Install glew via homebrew with: brew install glew
- Fetch cl.hpp with: wget -P CL https://www.khronos.org/registry/OpenCL/api/2.1/cl.hpp
- Compile with: mkdir build ; cd build ; cmake -DCMAKE_CXX_FLAGS="-I .." .. ; make
- Run with: build/clpathtracer

Compiling instructions (for Ubuntu Linux 16.04)

- Install necessary libraries: apt-get install cmake libxmu-dev libxi-dev libglew-dev freeglut3-dev
- Install OpenCL driver for Intel for example: apt-get install ocl-icd-opencl-dev beignet-opencl-icd

- Fetch cl.hpp with: wget -P CL https://www.khronos.org/registry/OpenCL/api/2.1/cl.hpp
- Compile with: mkdir build ; cd build ; cmake -DCMAKE_CXX_FLAGS="-I .." .. ; make
