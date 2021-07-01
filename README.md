

# INCREMENTAL TARBALL BACKUP

The goal of the project is to create a script that combines `tar` with `find` to
produce incremental compressed backups. 

## Why am I using tar & find over rsync?
The rsync command is great at creating incremental backups; however, it does
compress the output folders. 
Tar, on the other hand, offers a great compression functionality, but does create
incremental backups like rsync.
Therefore, this program aims to create incremental compressed backups.

To do:
1. Organise the md5sum files and the tarballs in a more intuitive folder structure;
2. Create the recovery function;
3. Add functionality to support encrypted folders with veracrypt, so the user can
   just plug in the encrypted volume, type `backup` in the terminal and have the
   backups folders moved onto the encrypted volume. 
   

**IMPORTANT: This project is still being developed.**

Copyright 2021 Afonso Schulz Albrecht

