# LibOptions

## What is it??
LibOptions a library that allows user to conveniently calculate options price paths and use different algorithms to calculate when to execute. Clients of the library can also easily replace the algorithms in the library with their own custom algorithms!

## How to Install
`LibOptions` requires CMake (>= 3.14) and Eigen3 library. 

Please refer to this link to install [CMake](https://cmake.org/install/) and (this)[http://eigen.tuxfamily.org/index.php?title=Main_Page#Download] to install the Eigen3 library.

## How to Compile
To compile everything, simply run
```
make
```

This will compile everything (library and the driver that uses the library) inside the `build` directory (which will be generated by the Makefile if not present).

To directly build everything and run the driver, run

```
make driver
```
 