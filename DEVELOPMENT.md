# Kame Development Guide

## Setting Up

### Prerequisites

Before you begin, ensure you have the following installed on your development machine:

- Git (For version control)
- C Compiler (GCC or Clang)
- CMake (For building the project, version 3.22 or higher)

## Building Kame

### First-Time Build

```bash
cmake -S . -B build
cmake --build build -j
```

### Incremental Builds

To rebuild after making changes, run:

```bash
cmake --build build -j
```
