This fork fixes a few annoying bugs in darkplaces.

## Binaries

(don't forget dependencies below)

https://github.com/aybe/darkplaces/releases

## Dependencies

### For playing

(for the build using SDL2)

https://github.com/aybe/darkplaces/releases/tag/dependencies

### For development

(you need these for all projects)

[SDL version 1.2.15](https://www.libsdl.org/release/SDL-devel-1.2.15-VC.zip)

[SDL version 2.0.5](https://www.libsdl.org/release/SDL2-devel-2.0.5-VC.zip)

[Microsoft DirectX SDK (June 2010)](https://www.microsoft.com/en-us/download/details.aspx?id=6812)

If you get error S1023 during install:

https://support.microsoft.com/en-us/help/2728613/s1023-error-when-you-install-the-directx-sdk-june-2010

## Issues/enhancements etc

See https://github.com/aybe/darkplaces/issues.

## Changes

### Xbox 360 Controller / Xbox One Controller
- running was not applied
- persistence of joy_x360_deadzone*, joy_x360_sensitivity* vars

### Video
- texture filtering in video options (previously you had to use console at every launch)

### VC++
- fixed DirectX SDK paths
- defaulting SDL paths to C:\SDL-1.2.15 and C:\SDL2-2.0.5
