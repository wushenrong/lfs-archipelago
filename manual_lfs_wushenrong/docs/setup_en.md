# Linux From Scratch (LFS) Randomizer Setup Guide

## Prerequisites

-   [Archipelago](https://github.com/ArchipelagoMW/Archipelago)
-   A recent Linux distribution with Glibc: Debian, Ubuntu, Fedora, Arch, etc
-   The latest [LFS handbook](https://linuxfromscratch.org/lfs)
-   Completed Part II of the LFS handbook
-   And one of the following
    - Basic understanding of Linux commands and building software from source
    - Completed LFS before

## Preface

This randomizer is best "played" with a multi-game multi-world setup. It is
mostly a linear experience completed in multiple stages with long wait times,
following the LFS handbook. Basically a glorified watching the paint dry
experience. If you do try to create this world on its own, then it
**will fail**. You are better to do LFS normally as there are dependencies
locked behind early stages of LFS.

You should also follow any
[erratas](https://linuxfromscratch.org/lfs/errata/stable-systemd/)
and [security advisories](https://linuxfromscratch.org/lfs/advisories/) if you
intend to use or share the installation.

## Setup

If you have not done so already, complete Part II of the LFS handbook. It is
recommended to put the installation on a hard disk image to avoid making your
Linux system unbootable.

This randomizer starts when you build the first pass of Binutils. In order to
check a location, you need to fully compile, test, and install the program that
is required for that location.
