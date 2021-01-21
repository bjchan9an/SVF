# SVF
* Forked from https://github.com/davidtr1037/SVF
* Ported to work with LLVM 4.0

## Build (CMake)
```
git checkout master
mkdir Release-build
cd Release-build
cmake \
    -DLLVM_DIR=<LLVM_BUILD_DIR>/share/llvm/cmake/ \
    -DLLVM_SRC=<LLVM_SRC_DIR> \
    -DLLVM_OBJ=<LLVM_BUILD_DIR> \
    -DCMAKE_BUILD_TYPE:STRING=Release \
    ..
make
```
