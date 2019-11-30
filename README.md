## Cloning directory
To clone a project run this command
```bash
git clone --recurse-submodules https://github.com/LoGosX/sfml-cmake-template
```
this command will download source for this project and for third party libraries.

## Building 
To build a project run following commands (in bash or Windows Power Shell) from project directory (directory that was created by ```git clone``` command):
```bash
cd build
cmake ..
cmake --build .
```

To build a project again run 
```bash
cmake --build .
``` 
from ```build``` directory.

## Summary
This chain of commands should clone repository and build it using cmake:
```bash
git clone --recurse-submodules https://github.com/LoGosX/sfml-cmake-template
cd sfml-cmake-template/build
cmake ..
cmake --build .
./FIZYKA2019
```
if you want to change the name of the executable change all occurrences of FIZYKA2019 in CMakeLists.txt.
