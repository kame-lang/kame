# Kame Development Guide

- [Kame Development Guide](#kame-development-guide)
  - [Setting Up](#setting-up)
    - [Prerequisites](#prerequisites)
  - [Building Kame](#building-kame)
    - [First-Time Build](#first-time-build)
    - [Incremental Builds](#incremental-builds)

## Setting Up

### Prerequisites

Before you begin, ensure you have the following installed on your development machine:

- Git (For version control)
- C Compiler (GCC or Clang)
- CMake (For building the project, version 4.1.1 or higher)

## Building Kame

### First-Time Build

```bash
mkdir -p build
cd build
cmake ..
make
```

### Incremental Builds

After the initial build, you can simply run `make` in the `build` directory to compile any changes made to the source code:

```bash
cd build
make
```
