# winedog

winedog is a simple kernel originally written to relearn asm, but its been a few years and so instead of restarting like I planned, I'm rewriting this one and expanding it.

    Currently has a (basic) C library that allows for (simple task) commands to be created.
    Supports full QWERTY keyboard mapping including non typist keys such as ScrLk and NumLk.

Requirements

    gcc
    grub2
    make
    nasm
    xorriso

Usage

Install all the requirements (I used debian WSL2 and had no issues) and execute the following:

$ cd ~/path/to/winedog/
$ make

