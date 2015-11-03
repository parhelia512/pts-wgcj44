GCJ 4.4.0 binaries for Win32

It is a working GCJ (GNU Java Compiler) 4.4.0 compiled for Win32. You can
use it to compile .java and .class files to Win32 .exe files. The generated
.exe is stand-alone, it doesn't need a JDK or JRE, and it can run on any
Win32 system. (There are some bugs, restrictions and incompatibilities
between e.g. OpenJDK and GNU ClassPath, the Java standard library GCJ 4.4
uses. So your Java programs won't work out-of-the-box, but it's possible to
make small porting changes to make them work.)

It has been tested and found working on Windows XP and Wine 1.2 on Ubuntu
Lucid.

The binaries are from MinGW (thus they are free software under the GPL,
parts under different free licenses, see http://www.mingw.org/license). Most
of the files were extracted from archives downloaded from
http://sourceforge.net/projects/mingw/files/MinGW/Base/gcc/Version4/Previous%20Release%20gcc-4.4.0/
on 2012-06-30.
