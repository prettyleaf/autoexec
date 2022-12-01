# Apex Legends Season 15 Autoexec

## Apex Legends Autoexec based on performance improvement.

- Please remove preset name argument in file name to make it work in-game.
- Please make sure you have checked the "Read-only" box in the file properties before launching the game.

## Installation

- How to make it work? Put ``autoexec.cfg`` in the directory:

    ```
    D:\Steam\steamapps\common\Apex Legends\cfg
    ```
- Please make sure you have checked the "Read-only" box in the file properties before launching the game.  

## Start-up commands

- You may also use some additional commands to improve perfomance

    ```
    +exec autoexec.cfg -dev -preload -novid -fullscreen -dxlevel95 +mat_compressedtextures 1 +cl_ragdoll_collide 0
    ```
- ``-preload`` may lower fps, so test it.
- ``-high`` is not included as it's just a placebo, which makes things worse.

## Attention
- We know that some commands no longer work, but such "Placebo" doesn't make things worse and maybe one day gonna work again.
