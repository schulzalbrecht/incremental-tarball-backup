

# BACKUP - still trying to find a good name for it

It helps back up data using veracrypt volumes. 

It assumes you have already created the encrypted volume.
The rest will be done by verarquive, it means:
1. Mounting the volume;
2. Moving the selected data onto the encrypted volume;
3. Dismounting the volume.


## Why use tar and find over rsync backups?

Although rsync is great at creating incremental backups, it does not offer the
compression functionality (only the compression during data transfer).
Tar on the other hand offers good compression options and when combined with find
it allows incremental backups. 


Copyright 2021 Afonso Schulz Albrecht

