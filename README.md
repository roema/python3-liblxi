# python-liblxi (Python3)

Initial attempt at python bindings for liblxi. 

NOT tested yet, likely buggy or doesn't work at all - use at your own risk!

## cmake out-of-source build

Note: the config.h is built by autogen/configure - not currently produced by cmake.

```
$ mkdir bld
$ cd bld
$ cmake ..
$ make
$ sudo make install
```

## python test

```
$ python test.py 
Siglent Technologies,SDG2042X,SDG2XCAC2R0212,2.01.01.23R7
```
