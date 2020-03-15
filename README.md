# Scripts

This repository contains all of the scripts required to create an ameliorated Windows 10.

These scripts are used in conjunction with each other to, in part, create an Ameliorated Windows 10 install from scratch. These are divided into two folders, one for Windows and one for Linux. They have been divided into BASH and BATCH for simplicity's sake. The reason for not dividing them into Windows and Linux is due to the rational that some of the scripts, while they are BASH scripts, they are made to be run on Windows. The reason for this is made apparent in the documentation.

## Download

If you are following the [documentation](https://ameliorated.info/documentation.html), the links will point directly to the correct files. If you want all of the scripts, they can be downloaded from the releases page in a zip file.

## How to use these scripts

The documentation for the use of these scripts is on the main website, [found here](https://ameliorated.info/documentation.html), to avoid any unnecessary problems, please follow this documentation when using these scripts. Simply put, the batch script is to be run both before and after the bash script, and the bash script *must* be run in Linux.

## BATCH scripts

The main script in the folder is the "amelioration" script, this is the script that sets up everything that can be set up in Windows itself. This script is used both before and after the BASH script is run in Linux.

## BASH scripts

This folder holds both the main "ameliorate" script and auxiliary scripts. The auxiliary scripts are helpful in setting up Windows and can be ran in Windows with Cygwin. As will all BASH scripts, it is required to change the file permissions so that they can be executed, regardless of the OS being used, example below.

`chmod +x ameliorated_1903_debian.sh`

## FAQ

* __Which versions of Windows do these scripts worth with?__

They have only been thoroughly tested with 1809 and 1903, but these scripts will work with __1809__, __1903__, and __1909__.  Windows 10 1909 should work as there are likely no outstanding differences between it and 1903, but be aware that it has not been tested.