# Linux From Scratch (LFS) Randomizer Setup Guide

## Prerequisites

- [Archipelago](https://github.com/ArchipelagoMW/Archipelago)
- A recent Linux distribution with Glibc: Debian, Ubuntu, Fedora, Arch, etc
- The latest [LFS](https://linuxfromscratch.org/lfs) handbook
- Completed Part II of the LFS handbook
- Understanding of basic Linux commands and building software from source
- Or have completed LFS before

## Setup

This randomizer is intended for a multiworld multi-game setup. It is mostly a
linear experience completed in multiple stages following the handbook. If you do
try to create this world on its own, then it **will fail**. You are better to do
LFS normally as there are lots programs that require dependencies locked in
early stages.

If you have not done it already, complete Part II of the LFS handbook. This
randomizer starts when you build the first pass of Binutils. It is expected that
in order to check a location you need to fully compile and install the program
for that location.

You should also follow any
[erratas](https://linuxfromscratch.org/lfs/errata/stable-systemd/)
and [security advisories](https://linuxfromscratch.org/lfs/advisories/) if you
intend to use or share the installation.
