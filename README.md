## MyoController

AIR Native Extension for Myo

This library is in a very early stage and has not been tested as i didn't receive the Myo yet.

ane_src contains c++ and as3 sources for the ANE, swcCompiler.bat is a script to automate the creation of the .ane
as3_demo is a FlashDevelop project to show the library usage. 

/!\ You may need to add myo32.dll and ble32.dll in a path that the AIR SDK can find ! 

You can do this either by copying the 2 files in the [FlashDevelopInstall]/tools/flexsdk/bin folder or by adding the path of the folder containing these 2 dlls in the PATH environment variable.
