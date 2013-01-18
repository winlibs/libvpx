# libvpx

## Building for PHP

### Requirements

  * libvpx sources [https://github.com/winlibs/libvpx](https://github.com/winlibs/libvpx)

  * Common tools used to compile PHP

  * yasm

  * cygwin

### Configuration

To compile libxpm the VS projects have to be generated first, follow the
instructions under the [libvpx project page](http://www.webmproject.org/code
/build-prerequisites/). PHP uses the static libvpx linked with the static VC
runtime. Note that the VS project files are generated with make under Cygwin
and empirically the paths in the project files are often Cygwin paths, so they
might need correction.

### Compile

Open in the generated vpx.sln solution in visual studio and compile the vpx
project.