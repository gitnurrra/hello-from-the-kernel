# Hello From the Kernel

This is a simple Hello World program, but with one twist - **the program doesn't use any standard libraries**.
> No `#include <iostream>` at all

## Build

### Linux x64
```bash
gcc -o main_linux_x64 main_linux_x64.c
```
### Mac x64
```bash
gcc -o main_mac_x64 main_mac_x64.c
```
### Mac arm64
```bash
gcc -o main_mac_arm64 main_mac_arm64.c
```
### Windows x64 (through WSL or MinGW)
```bash
gcc -o main_win_x64 main_win_x64.c
```

## Run

### Linux x64
```bash
./main_linux_x64
```
### Mac x64
```bash
./main_mac_x64
```
### Mac arm64
```bash
./main_mac_arm64
```
### Windows x64
```bash
./main_win_x64
```

## Notes
- This program has different implementations for different OSes and CPU architectures without using any standard library functions.
