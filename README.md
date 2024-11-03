# Basic OpenGL


## How to install "make" command and C/C++ compilers:


### For Windows:

1. Install `Chocolatey` from: \
   https://chocolatey.org/install

2. After finishing the installation run the following command:
   ```
   choco install make
   ```

3. To install the C/C++ compilers go to the website: \
   https://code.visualstudio.com/docs/cpp/config-mingw

4. Follow the guide on to install the C/C++ Compiler and validate that they are installed by running the commands:
   ```
   gcc --version
   g++ --version
   ```


### For MacOS:

1. Install `Xcode tools` using the command:
   ```
   xcode-select --install
   ```

2. (Optional) Install `brew` from: \
   https://brew.sh/

3. (Optional) Install with `brew` the `GLFW` library using the command:
   ```
   brew install glfw
   ```


## How to compile and run the OpenGL engine using the Makefile:


### Using the CMD/Terminal:

1. Open the CMD/Terminal

2. Navigate to the project folder using "cd" commands

3. Run the command:
   ```
   make
   ```

4. Run the commands:
   ```
   cd bin
   ./main
   ```


### Using Visual Studio Code:

1. Download Visual Studio Code from: \
   https://code.visualstudio.com/download

2. Download the `Makefile Tools Extension` from the Visual Studio Code Extensions or from: \
   https://marketplace.visualstudio.com/items?itemName=ms-vscode.makefile-tools

3. Configure the `Makefile Tools Extension` to compile the engine using the available [Makefile](Makefile).

`Notice:` With this tool you can run the OpenGL in Debugging mode as well.


## MacOS known issue with "libglfw.3.dylib" file

The MacOS tends to block the file: "libglfw.3.dylib" which is crucial for running the OpenGL engine. 
To remove the block, open the MacOS "Settings", go to "Privacy & Security", scroll down until you find the "libglfw.3.dylib" and chose enable permission to it.


## Useful guides for building the OpenGL engin:

- For Windows: \
  https://www.youtube.com/watch?v=hRInLNR9iRg

- For MacOS: \
  https://www.youtube.com/watch?v=7-dL6a5_B3I


## Useful Youtube guides:

- The Cherno: https://www.youtube.com/watch?v=W3gAzLwfIP0&list=PLlrATfBNZ98foTJPJ_Ev03o2oq3-GGOS2

- Victor Gordan: https://www.youtube.com/watch?v=XpBGwZNyUh0&list=PLPaoO-vpZnumdcb4tZc4x5Q-v7CkrQ6M-


## Library sources:

- GLFW: \
  https://www.glfw.org/

- GLAD: \
  https://glad.dav1d.de/

- GLEW (Not used, But works similar to GLAD): \
  https://glew.sourceforge.net/

- stb: \
  https://github.com/nothings/stb

- glm: \
  https://github.com/g-truc/glm/releases/tag/1.0.1