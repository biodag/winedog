# winedog

A while back I started this, now I'm working on it again

# Requirements

  - gcc
  - grub2
  - make
  - nasm
  - xorriso

# Usage

There is an `iso` in versions. Just create a virtual machine in VMWare or whatever you use, and set the iso as the boot image. It requires an incredibly low amount of ram too, so you can run it in the background if for some reason you actually need to (You don't; all you can do is shut it down at the moment.)

# Building

Install all the requirements (I used debian WSL and had no issues) and execute the following:

```shell
$ cd ~/path/to/winedog/
$ make
```
