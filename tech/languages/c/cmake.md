---
title: CMake
page: cmake
---

### CMake

## CMake Description

CMake is a multi-platform software designed for automated compilation on various operating systems. 
It uses C++ compiler and make build evniroment to build your project. 
CMake uses special configuration files CMakeLists.txt. CMakeLists.txt is a file containing `cmake` commands. 
With these commands you can specify directories, libraries, header files, output binary files and many more 
features that are part of your project and are important for succesfully building your project. 

To familiarize yourself with basic features of CMake you should try the online tutorial on cmake website:

[CMake basic tutorial](http://www.cmake.org/cmake-tutorial/)

To discover the full application of various features that CMake has to offer use the online documentation:

[CMake latest documantation](http://www.cmake.org/cmake/help/v3.3/)


## CMake Installation

To install CMake all you need to do is:

```
# sudo dnf install cmake
```

## CMake Usage

The beauty of CMake is that after you create a simple CMakeLists.txt file you only need to use this command:

```
# cmake /path/to/CMakeLists.txt
```

This command should be used in a directory where you want to have the Makefile for your project. 
It will create all necessary Makefiles and configuration files needed to compile your project. 
Than after using the command `make` your project is built and ready for use.
This `cmake` command above is only a basic example. There are of course many more options that can be used with `cmake`. 
These can be found in the manual page:

```
# man cmake
```