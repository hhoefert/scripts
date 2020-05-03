# scripts
A repository for all my shell scripts

# Initialization and Update
After cloning the repository to an arbitrary location on your system, navigate to the repository. Run `sh update_scripts`.
This will fetch all new scripts and makes all of the scripts in the folder `/scripts/` executable and copies them to `/usr/local/bin/` (make sure to add this folder to your path variable.)

## update
Uses apt to update all existing packages and saves installed packages to ~/pkglist.txt.
Use pkglist.txt to reinstall all packages: <https://www.ostechnix.com/create-list-installed-packages-install-later-list-centos-ubuntu/>

Usage: `update`

## semester
This is a personal script, that navigates to the corresponding folder for the given course abbreviation. Also it syncs all changes from OneDrive.

Usage: `. semester coursename`
