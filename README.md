Tarballs (.tar.gz) of the source code for lqns.  See the README files for build instructions (./configure; make; make install). For Windows, use MingGW64 (and use the 32-bit version of msys).

To build, you require the following programs/packages which may not be installed by default on Linux/MinGW/FreeBSD/...
  flex,
  bison,
  gcc-c++,
  expat-devel (header files are necessary),
  automake,
  libtool,
  gd-devel (optional for png/jpeg output),
  texlive (optional for documentation),
  texlive-epsf (optional for documentation),
  fig2dev (optional for documentation).
  
  On Redhat (Fedora, Centos,...), use "dnf install {program}".
  On Ubuntu, use "apt-get install {program}".
  On MinGW, use "pacman install {program}".
  On MacOS, use "port install {program}", or fink ???, or brew ????
