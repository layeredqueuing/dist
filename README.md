Tarballs (.tar.gz) of the source code for lqns.  See the README files for build instructions (./configure; make; make install). Builds on Windows with mingw64, though extra packages are needed. 

Tou bould, you require the following programs/packages which may not be installed by default on Linux/MinGW/FreeBSD/...
  flex,
  bison,
  gcc-c++,
  expat,
  automake,
  libtool,
  gd-devel (optional for png/jpeg output),
  texlive (optional for documentation),
  texlive-epsf (optional for documentation),
  xfig (optional for documentation),
  fig2dev (optional for documentation),
  
  On Redhat (Fedora, Centos,...), use "sudo dnf install {program}".
  On Ubuntu, use "apt-get install {program}".
  On MinGW, use pacman ????
  On MacOS, use "port install {program}", or fink ???, or brew ????
