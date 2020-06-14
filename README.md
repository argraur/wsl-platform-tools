# Android platform-tools installer for WSL

This method uses WSL's ability to run Windows executables in WSL shell.

## Requirements

* Windows Subsystem for Linux distribution
* wget

## Installation

In WSL shell, run:

`curl https://raw.githubusercontent.com/argraur/wsl-platform-tools/master/wsl-platform-tools | sudo bash -`

## Uninstallation

Same as installation.

## Usage

Use just as if it is normal Linux platform-tools installation

**NOTE: If you use /mnt/c/... path, use C:/... instead.**

## Issues

`make_f2fs` fails for some reason