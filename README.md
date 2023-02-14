# Gtk3/Gtk4 project wizards for Code::Blocks

using Msys2-MinGW64 toolchain in x64-windows box.  

Usage:  

unzip the file Gtk3-Gtk4_project_wizards_for_CodeBlocks-Msys2-MinGW64.rar  
      to <[CodeBlocks dir]\share\CodeBlocks\templates\wizard> folder.  


before that,  

0. install Msys2-x64;
1. install the build toolchain: pacman -S mingw-w64-x86_64-toolchain base-devel
2. install Gtk4: pacman -S mingw-w64-x86_64-gtk4
3. install Gtk3: pacman -S mingw-w64-x86_64-gtk3
4. add <[Msys2 dir]\mingw64\bin> to the PATH.
5. install CodeBlocks, configure using Msys2-Mingw64 toolchin.

Enjoy!  
