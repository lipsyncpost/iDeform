# iDeform
Deformer suite for Autodesk Maya.

## Videos
[iCollide tutorial on Vimeo](https://vimeo.com/55876041)

[iDisplace tutorial on Vimeo](https://vimeo.com/55511098)

[Vertex color based displacement tutorial on Vimeo](https://vimeo.com/157510194)

[iSkinDeform tutorial on Vimeo](https://vimeo.com/55880201)

## Installation
Installation is easy with the included installer.

[Easy Install](https://github.com/IngoClemens/iDeform/wiki/Installation)

## Getting Started
Visit the [Quick Guide](https://github.com/IngoClemens/iDeform/wiki/Quick-Guide) for basic tool usage.

See the [Wiki](https://github.com/IngoClemens/iDeform/wiki) for full details.

## Building
To build with cmake see the [Building](https://github.com/IngoClemens/iDeform/wiki/Building) page.

## Linux Compile Instructions For Maya 2020

export CC="/sw/pkg/gcc/6.3.1/bin/gcc"

export DEVKIT_LOCATION="/sw/pkg/maya/2020/maya2020/devkit"

cmake -H. -Bbuild -G "Unix Makefiles"

cmake --build build/