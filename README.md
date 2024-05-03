# Toolbox

A [Zig][2] package to package & maintain C APIs packaged for [Zig][2]

## Important note

Currently this package is not intented to be used outside of the [tiawl/spaceporn][1] dependencies chain. But it could. If you are using it for your own needs, expect breaking (but also documented) changes for each release.

If you want to see how to use it you can check repositories list into the **"CICD reminder"** section.

## Dependencies

The [Zig][2] part of this package is relying on the latest [Zig][2] release (0.12.0) and will only be updated for the next one (so for the 0.13.0).

## CICD reminder

These repositories are automatically updated when a new release is available:
* [tiawl/vulkan.zig][3]
* [tiawl/wayland.zig][4]
* [tiawl/X11.zig][5]
* [tiawl/glfw.zig][6]
* [tiawl/cimgui.zig][7]
* [tiawl/spirv.zig][8]
* [tiawl/glslang.zig][9]
* [tiawl/shaderc.zig][10]

This repository is automatically updated when a new release is available from these repositories:
* [tiawl/spaceporn-action-ci][11]
* [tiawl/spaceporn-action-cd-ping][12]
* [tiawl/spaceporn-action-cd-pong][13]

## Documentation

Available [here](https://github.com/tiawl/toolbox/blob/trunk/DOC.md)

[1]:https://github.com/tiawl/spaceporn
[2]:https://github.com/ziglang/zig
[3]:https://github.com/tiawl/vulkan.zig
[4]:https://github.com/tiawl/wayland.zig
[5]:https://github.com/tiawl/X11.zig
[6]:https://github.com/tiawl/glfw.zig
[7]:https://github.com/tiawl/cimgui.zig
[8]:https://github.com/tiawl/spirv.zig
[9]:https://github.com/tiawl/glslang.zig
[10]:https://github.com/tiawl/shaderc.zig
[11]:https://github.com/tiawl/spaceporn-action-ci
[12]:https://github.com/tiawl/spaceporn-action-cd-ping
[13]:https://github.com/tiawl/spaceporn-action-cd-pong
