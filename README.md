# musl-clang
A gentoo musl repository meant to support native use of the clang compiler and llvm libraries such as libc++ and libc++abi to replace gnu libraries. 
This repository is meant to be used in conjunction with the [gentoo musl overlay](https://github.com/gentoo/musl).

## Why does this exist?
Some packages, such as qtcore, have ~~awful~~ complicated build processes, and require special configuration that is specific toward clang and llvm libraries.
Since these packages cannot be patched in a way that would maintain compatibility with gcc and clang at the same time, a seperate repository is required.
