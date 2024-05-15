LLGo wrapper of sqlite
=====
[![Build Status](https://github.com/goplus/sqlite/actions/workflows/go.yml/badge.svg)](https://github.com/goplus/sqlite/actions/workflows/go.yml)
[![GitHub release](https://img.shields.io/github/v/tag/goplus/sqlite.svg?label=release)](https://github.com/goplus/sqlite/releases)
[![GoDoc](https://pkg.go.dev/badge/github.com/goplus/sqlite.svg)](https://pkg.go.dev/github.com/goplus/sqlite)
[![Compiler](https://img.shields.io/badge/compiler-llgo-darkgreen.svg)](https://github.com/goplus/llgo)
[![Language](https://img.shields.io/badge/language-Go+-blue.svg)](https://github.com/goplus/gop)

## How to install

```sh
git clone https://github.com/goplus/sqlite.git
cd sqlite
git submodule init
git submodule update
mkdir build.dir
cd build.dir
../sqlite/configure --enable-shared
sudo make install
```
