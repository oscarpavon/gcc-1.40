This directory contains the version 1.40 release of the GNU C compiler.

See the file gcc.texinfo for installation and porting information.
The file INSTALL contains a copy of the installation information.

The GNU C compiler is free software.  See the file COPYING for copying
permission.

The files print-self.c and print-self1.c are not part of GCC.
They are programs that print themselves on standard output.
They were written by Dario Dariol and Giovanni Cozzi, and are
included for your hacking pleasure.

## Build
```
./config.gcc i386-sysv
make -j1 CC="gcc -O -Wno-implicit-int -Wno-return-mismatch -Wno-implicit-function-declaration -Wno-int-to-pointer-cast -Wno-builtin-declaration-mismatch -Wno-int-conversion"
```

