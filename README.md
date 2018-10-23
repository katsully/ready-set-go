# Ready Set Go

## Building From Scratch
### Cinder Blocks
[Cinder-Gui](https://github.com/simongeilfus/Cinder-ImGui) </br>
[Cinder-Spout](https://github.com/brucelane/Cinder-Spout) -  switch to 32bit branch
[Cinder]
Cinder OSC already part of Cinder install

Install all 3 as Relative blocks via Tinderbox

### Header Files and other fun things
copy headers, lib, and bin folders from [here](https://github.com/ValveSoftware/openvr)

Add headers to Additional Include Directories, add openvr_api.lib to Additional Dependencies, and ..lib/win32 and ../lib/win32 to Additional Library Dependencies

Add openvr_api.dll to vc2015\build\Win32\Debug


From the same repo, copy samples/shared. Add ../shared to Additional Include Directories. Add header files from shared to Header Files in the Solution Explorer. Add cpp files from shared to Source Files in Solution Explorer.
