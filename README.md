# PCSX2OOM
Simple port of DOOM to the Playstation 2
A few ports of DOOM have been created for the PS2 by the homebrew scene, 
but they're outdated and use old versions of the PS2SDK and toolchain.  
This project aims to fix this and update functions so it builds in the latest 
PS2DEV project and eventually add new features such as USB peripheral support, networking and PWAD loading.

To build just the PCSX2OOM.ELF executable, simply run the following:  
```
cd src
make
```

To build an ISO containing PCSX2OOM.ELF and other files, copy your DOOM WADs into bin/ and run the following:  
```
cd src
make iso
```
