# GLFW CMake starter

This starter project shows how to use CMake to create a project with GLFW. The code is multi-platform and runs on Windows, Linux and MacOS.

Quickstart: [glfw.org](https://www.glfw.org/docs/3.3/quick_guide.html)  
GLFW on GitHub: [github.com/glfw/glfw](https://www.github.com/glfw/glfw)

## Getting the code

The easiest way to get hold of the starter code is to run the following command using a shell you can run git from:

```
git clone --recursive https://github.com/AntohiRobert/GLFW-CMake-starter
```

If you are on Windows you can download git from [git-scm.com/download/win](https://git-scm.com/download/win) and use the right click menu in Windows File Explorer to "Git Bash here" and then run git commands.

This will create the directory _GLFW-CMake-starter_ and get the latest source code, using the ```--recursive``` option to download the GLFW code which is included in the repository as a submodule. If you want to run further git commands from the command line you'll need to cd into the directory:

```
cd GLFW-CMake-starter
```

Alternatively you can use a git GUI program such as [Fork](https://git-fork.com/) to get the code. Most of these will automatically download the git submodules.


## Using CMake to create the project

From a command prompt in the `GLFW-CMake-starter` directory:
1. `mkdir build`
1. `cd build`
1. `cmake ..`
1. Either run `make all` or for Visual Studio open `GLFW-CMake-starter.sln`

