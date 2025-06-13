# UAI-Universal-Assembly-Interpreter-
Hey there guys. So this is just a project MADE BY BIONICBEAVERLINUX2 (this was just in case one person cloned this git repo and is messed up enough to make it there' s. Trust me there are a lot of people that I know who do this. Anyways hope you use this assembler/editor and hopefully this makes programming in assembly a lot easier.


How to run this project.


Linux/BSD

Dependencies: gzip, python3, python3-pip

So depending on your distro you will oviously have a package mananger so il keep this as simple as possible.

Debian based distros:

1. Sudo apt install gzip python3 python3-pip.
2. cd Downloads
3. Gunzip assembly_editor.py.gz
5. (Use whatever preferred text editor to create this directory) ~/.local/share/applications/assembly_editor.desktop.
6. Type this exactly.
[Desktop Entry]
Name=UAI
Comment=Universal Assembly Interpreter/Assembly/Editor.
Exec=python3 /home/YOURUSERNAME/UAI/assembly_editor.py
Terminal=false
Type=Application
Categories=Utility;
7. Then it should run. By the way instead of your username you can also add $HOME.
8. Then it should work. Happy coding.

Red hat based distros:

1. Sudo dpm install gzip python3 python3-pip
2. Than you type the exact same entry in this distro referring to the Debian based distro instructions.

Gentoo based distros:

1. Sudo emerge gzip python3 python3-pip
2. Than you type the exact same entry in this distro referring to the Debian based distro instructions.

Arch based distros: 

1. Sudo pacman -S gzip python3 python3-pip
2. Than you type the exact same entry in this distro referring to the Debian based distro instructions.

BSD:

1. pkg_add gzip python3 python-pip
2. Than you type the exact same entry in this distro referring to the Debian based distro instructions.



