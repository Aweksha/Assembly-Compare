# Assembly-Compare
A simple C++ "Hello, World!" app set up with CMake. The main.cpp prints "Hello, World!" to the console, while CMakeLists.txt configures the project for C++17, creating the assembly_compare executable.



# Assembly Compare

This project is a simple "Hello, World!" C++ application, built using CMake.

## Files
- **main.cpp**: Contains the source code for the program, which outputs "Hello, World!" to the console.
- **CMakeLists.txt**: Defines the CMake configuration for building the project.

## Requirements
- **CMake**: Version 3.24 or higher
- **C++ Compiler**: Supports C++17

## Building the Project

1. **Navigate to the project directory:**
   ```bash
   cd assembly_compare
   ```

2. **Create a build directory:**
   ```bash
   mkdir build
   cd build
   ```

3. **Generate build files using CMake:**
   ```bash
   cmake ..
   ```

4. **Build the project:**
   ```bash
   cmake --build .
   ```

## Running the Program
After building, you can run the program with:
```bash
./assembly_compare
```

This should display:
```
Hello, World!
```
