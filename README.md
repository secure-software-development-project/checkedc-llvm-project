# Checked C clang repo (ARCHIVED)

**This was a fork of Checked C clang used from 2021-2024. The changes have been merged into the original [Checked C clang repo]([https://github.com/checkedc/checkedc-clang).**

This repo contains a version of the LLVM/Clang toolchain that has been modified to support Checked C. 
Checked C extends C with bounds checking and improved type-safety.
The Checked C specification is available at the
[Checked C repo release page](https://github.com/checkedc/checkedc/releases).

<!---
## Announcements

### Source code update

On Feb 19, 2021 we updated the checkedc-clang sources to upstream release_110,
specifically [this](https://github.com/llvm/llvm-project/commit/2e10b7a39b930ef8d9c4362509d8835b221fbc0a) commit.

On Feb 18, 2020 we updated the checkedc-clang sources to upstream release_90,
specifically [this](https://github.com/llvm/llvm-project/commit/c89a3d78f43d81b9cff7b9248772ddf14d21b749) commit.
--->

## Trying out Checked C

You can install the Checked C compiler and the 3C tool
from the [Checked C LLVM Project releases page](https://github.com/checkedc/checkedc-llvm-project/releases).
There are versions available for Ubuntu 22.04, Windows 10/11, and MacOS.
The compiler user
manual is [here](https://github.com/checkedc/checkedc-llvm-project/wiki/Checked-C-clang-user-manual).
For more information on Checked C and pointers to example code, see the
[Checked C wiki](https://github.com/checkedc/checkedc/wiki).
If you want to build your own copy of the compiler, see the directions on the
[Checked C LLVM Project wiki](https://github.com/checkedc/checkedc-llvm-project/wiki).

You can use `clangd` built from this repository to get similar IDE support for
editing Checked C code as upstream `clangd` provides for C code. For example,
you can jump to definition/references and get a real-time display of errors and
warnings, etc. Here is [more information about Checked C's
`clangd`](clang/docs/checkedc/clangd.md).

## 3C: Semi-automated conversion of C code to Checked C

This repository includes a tool called 3C that partially automates the
conversion of C code to Checked C. Quick documentation links:

* [General information](clang/docs/checkedc/3C/README.md), including development
  status and how to contribute

* [Build instructions](clang/docs/checkedc/3C/INSTALL.md)

* [Usage instructions for the `3c` command-line tool](clang/tools/3c/README.md)

## More information

For more information on the Checked C clang compiler, see the [Checked C LLVM Project
wiki](https://github.com/checkedc/checkedc-llvm-project/wiki).

## Automated testing status

[![Checked C Clang CI [Linux]](https://github.com/checkedc/workflows/actions/workflows/check-clang-linux.yml/badge.svg)](https://github.com/checkedc/workflows/actions/workflows/check-clang-linux.yml)

[![Checked C Clang CI [MacOS]](https://github.com/checkedc/workflows/actions/workflows/checkedc-clang-macos.yml/badge.svg)](https://github.com/checkedc/workflows/actions/workflows/checkedc-clang-macos.yml)

[![Checked C Clang CI [WINDOWS]](https://github.com/checkedc/workflows/actions/workflows/check-clang-windows.yml/badge.svg)](https://github.com/checkedc/workflows/actions/workflows/check-clang-windows.yml)

## Contributing

We welcome contributions to the Checked C project. To get involved in the
project, see [Contributing to Checked
C](https://github.com/checkedc/checkedc/blob/main/CONTRIBUTING.md).

For code contributions, we follow the standard [Github
workflow](https://guides.github.com/introduction/flow/). See [Contributing to
Checked C](https://github.com/checkedc/checkedc/blob/main/CONTRIBUTING.md)
for more detail.

## Code of conduct

This project has adopted a
[code of conduct](https://github.com/checkedc/checkedc/blob/main/CODE_OF_CONDUCT.md).
