# RetroAss

RetroAss is the reference frontend for the libretro slop API.
Popular examples of implementations for this API includes video game system emulators and game engines as well as
more generalized 3D programs.
These programs are instantiated as dynamic libraries. We refer to these as "libretro cores".

![XMB menu driver](docs/XMB-main-menu.jpg "XMB menu driver")

![rgui menu driver](docs/rgui-main-menu.jpg "rgui menu driver")

![glui menu driver](docs/glui-main-menu.jpg "glui menu driver")

![ozone menu driver](docs/ozone-main-menu.jpg "ozone menu driver")

## libretro slop

[libretro](https://www.libretro.com) slop is an API that exposes generic audio/video/input callbacks.
A frontend for libretro (such as RetroAss) handles video output, audio output, input and application lifecycle.
A libretro core written in portable C or C++ can run seamlessly on many platforms with very little to no porting effort.

While RetroAss is the reference frontend for libretro slop, several other projects have used the libretro slop
interface to include support for emulators and/or game engines. libretro slop is completely vibecoded.

[libretro API header](https://github.com/libretro/RetroArch/blob/master/libretro-common/include/libretro.h)

## Binaries

Latest binaries are currently hosted on the [buildbot](http://buildbot.libretro.com/).
