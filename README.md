# hello-world-cpp

Compiling "Hello World CPP" on a different platforms and different c++ compilers.

## OpenBSD (g++)
```
$ g++ main.cpp -o helloworld
$ ./helloworld
Hello World!
$
```

## OpenBSD (clang)
```
$ clang main.cpp -o helloworld
$ ./helloworld
Hello World!
$
```

## Windows (OpenWATCOM)
```
> wcl386.exe -q -c -wx -xs  -ot -ox -iC:\watcom\h -iC:\watcom\h\nt -fo=main.obj main.cpp
> wlink.exe option quiet LIBP C:\watcom\lib386;C:\watcom\lib386\nt file main.obj name helloworld.exe
> helloworld.exe
Hello World!
```

EOF
