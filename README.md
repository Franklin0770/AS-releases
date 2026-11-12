This repository is meant to host pre-compiled versions of The Macroassembler AS by Alfred Arnold, so [MegaEnvironment](https://github.com/Franklin0770/megaenvironment) can download them without problems.  
The build won't get updated often, unless there's fixes for 68k and Z80 assembly or other additions. Obviously, not all compatible platforms executables supported by AS are compiled: only the ones that Visual Studio Code runs on (because my extension relies on them).  

# Authors
### Original Build
Website: http://john.ccac.rwth-aachen.de:8000/as/  

### Fixed Build
ASL GitHub: https://github.com/flamewing/asl-releases
P2BIN GitHub: https://github.com/Clownacy/p2bin

All these builds are made to work with Sonic disassemblies, by fixing bugs and adding relevant functionality. They may work on regular source code, but compatibilty isn't guaranteed.
The reason why the executables are separated in two different repositories is because the mantainers added functionality by their own apparently. P2BIN from flamewing's repository won't work on Sonic disassemblies by itself.

#### Latest compiled versions
The latest original build version here is: beta v1.42 build 316
The latest fixed build version here is: Snapshot v1.4.2.20261107-run42348676225

---
Thanks to [RobiWanKenobi](https://github.com/RobiTheGit) for being so kind to provide the Linux binaries without even asking him!  
Fixed build is provided by [flamewing](https://github.com/flamewing) to make sure we have support for Sonic disasseblies. Gives random errors while trying the normal version.

PSA: due to Apple phasing out Rosetta 2 in future macOS 28, I'm sure I'm going to struggle to compile the x86_64 macOS version on my Apple silicon Mac. We'll see what happens.