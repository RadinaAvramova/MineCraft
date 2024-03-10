# MineCraft

## Building

You will need GLM and SFML 2.4.1+ libraries w/headers, and this also requires a compiler that supports C++14 (or newer) with threads.

### macOS

Install macports from https://www.macports.org 

`sudo port install sfml glm`

### Ubuntu

`sudo apt-get install libsfml-dev libglm-dev`

## Compile Source and Running

### Linux

#### Debug

```sh
sh scripts/build.sh
sh scripts/run.sh
```

#### Release

```sh
sh scripts/build.sh release
sh scripts/run.sh release
```

