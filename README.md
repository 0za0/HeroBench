# BrickBench
A map editor for TT Games LEGO games... and Bionicle Heroes :)

![BBPic](https://user-images.githubusercontent.com/6656968/150651051-7461ce38-b028-4fd7-a0df-322d2e04ec8d.png)

BrickBench is a map editor for Lego Star Wars: The Complete Saga, as well as an experimental viewer for Lego Indiana Jones & Lego Batman.

# Requirements

BrickBench works on Windows and Linux x64 platforms. In addition, it requires:

* A graphics driver with support for OpenGL 4.5 or higher. 
* A processor with AES acceleration is required for map editing.

# Installation

To install, select your preferred installation method in the latest [release](https://github.com/BrickBench/BrickBench/releases). 

If installing for Windows, you can choose between the `.zip` portable and `.msi` installer versions. 
If you do not know which one to choose, install BrickBench with the `.msi` installer.

If installing for Linux, there is a portable `.tar.gz` archive. In addition, we provide `.deb` packages for Debian-based systems and `.rpm` packages. 
There is also a build available for Arch on the AUR [here](https://aur.archlinux.org/packages/brickbench).

# Documentation

For the most up-to-date documentation, please visit https://brickbench.readthedocs.io.

# Developers

To build BrickBench, install the latest version of Java (currently Java 18). You can get the AdoptOpenJDK build [here](https://adoptopenjdk.net/).
In addition, because GitHub Packages does not support unauthenticated downloads of packages, a local install of the OpenGG Engine is needed. You
can clone that from [here](https://github.com/OpenGGEngine/OpenGG-Project).

BrickBench can be built by running `./gradlew.bat build` and ran with `./gradlew.bat run`.

Before contributing, we do request that an issue is made beforehand so that we are aware of what is being worked on.
