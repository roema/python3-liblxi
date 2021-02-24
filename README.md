# python-liblxi (Python3.8)

Fork from https://github.com/lxi-tools/python-liblxi

```
sudo apt install libboost-python-dev libavahi-client-dev pkg-config cmake libxml3-dev
```

## build liblxi

```
$ cd python3-liblxi/liblxi
$ ./autogen.sh
$ ./configure
$ make
$ make install
```

## cmake python

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
