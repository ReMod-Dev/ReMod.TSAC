# ReMod.TSAC
A ReMod module implementation of TrueShaderAntiCrash

# Description
This is a ReMod module implementation for knah's TrueShaderAntiCrash. The original code can be found [here](https://github.com/knah/VRCMods).  
This module prevents practically all known shader crashes. Note that it can affect how stuff looks as it rewrites shader code to be non-crashy. Setting changes require world rejoin to reload shaders.
### Partial source code
Main logic of this mod is located in the native DLL that currently is not opensource. The DLL is build upon [HLSLcc](https://github.com/Unity-Technologies/HLSLcc) and uses [Microsoft Detours](https://github.com/microsoft/Detours).

## License
This mod is here is provided under the terms of [GNU GPLv3 license](LICENSE)
