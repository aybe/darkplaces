This fork fixes a few annoying bugs in darkplaces.

## Dependencies

[SDL version 1.2.15](https://www.libsdl.org/release/SDL-devel-1.2.15-VC.zip)

[SDL version 2.0.5](https://www.libsdl.org/release/SDL2-devel-2.0.5-VC.zip)

[Microsoft DirectX SDK (June 2010)](https://www.microsoft.com/en-us/download/details.aspx?id=6812)

## Changes

### Xbox 360 Controller / Xbox One Controller
- running was not applied
- persistence of joy_x360_sensitivity* vars

### Video
- texture filtering in video options (previously you had to use console at every launch)

### VC++
- fixed DirectX SDK paths
- defaulting SDL paths to C:\SDL-1.2.15 and C:\SDL2-2.0.5
