# RestoreEco Utility

This utility helps amd navi21/RDNA2 graphic card from eco mode (VRAM Frequency stuck at 0Mhz when you gaming).

## Usage
1. Enable AMD Driver Overdrive Function
2. Simply double-click on `RestoreVram.exe` to run the utility (you can put this file in user dir. and run this program by `win key+search RestoreVram+enter key`)
3. The program will automatically recovery from eco mode
4. No additional configuration or parameters needed

## Source
Forked from: [AMD Display Library SDK](https://github.com/GPUOpen-LibrariesAndSDKs/display-library/)

## Requirements
- AMD GPU with supported drivers
- Windows operating system
- ADL SDK components (included)

Note: Run as Administrator if you encounter permission issues.

## Compile Method
- using Visual Studio 2022 
- install C++ library and Windows SDK