This is a minimal, C++ cross-platform library for writing
real-time games that run in a terminal in text mode.

![](screenshot.png)
![](screenshot2.png)

# Features

- Windows 11 terminal, macOS Tahoe Terminal, macOS iTerm2, Linux xterm
- 24-bit (RBA8) color for foreground and background
- Keyboard input
- Mouse input
- Clipping region stack
- Blitting with transparency
- Double buffered (no flicker)
- String printing with word wrap
- Number formatting to string
- Full Unicode support using [char32_t characters](https://en.wikipedia.org/wiki/UTF-32) and strings
- Struct and function C-like API, with C++ strings and destructors for memory management
- No dependencies--uses only standard built-in platform libraries

# Files

`main.cpp`
: Demo program

`textgame.h`
: Cross-platform header and entry point documentation.
  Defines `Vector2i`, `Color3`, `String`, `Character`,
  `Image`, overloaded operators, and helper functions.

`textgame.cpp`
: Cross-platform library implementation

# License

MIT License

# See Also

Some other small, cross-platform libraries useful for making terminal-mode games:

- [Crossline](https://github.com/jcwangxp/Crossline): readline()
- [ffaudio](https://github.com/jcwangxp/Crossline): wave audio input and output
- [Gainput](https://github.com/jkuhlmann/gainput): gamepad input
- [GameNetworkingSockets](https://github.com/ValveSoftware/GameNetworkingSockets): networking
- [Recast Navigation](https://recastnav.com/): 3D pathfinding and CPU voxelization
- [Box2D](https://box2d.org/): 2D physics

