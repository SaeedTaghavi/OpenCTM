If you know a little bit about cmake, soon you will find out how you can make use of this package.

if you are a beginner, afte downloading the reqirements such as `libopenctm-dev`, `openctm-tools`, and `libopenctm1` you can use cmake to build the project:

```bash
mkdir build 
cd build
cmake ..
make 
ls
```

now you can the executable `mesh2ctm` in the dirrectory. 
`./mesh2ctm` will give you help to use it in the correct way, also it shows the options about compression methods.

`main()` function in located in the `tools/ctmconv.cpp`
