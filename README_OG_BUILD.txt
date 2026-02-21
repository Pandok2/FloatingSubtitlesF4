Floating Subtitles F4 - OG Build Ready

This package is preconfigured for Fallout 4 OG (1.10.163).

Requirements:
- Visual Studio 2022
- CMake
- vcpkg
- F4SE 0.6.23
- Address Library (OG)

Build Steps:
1. vcpkg install commonlibf4:x64-windows
2. cmake -B build
3. cmake --build build --config Release

Output:
build/Release/FloatingSubtitlesF4.dll

Install:
Copy DLL to:
Fallout 4/Data/F4SE/Plugins/
