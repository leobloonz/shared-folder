# shared-folder
Just add the following line to your /etc/fstab and reboot your machine:

vmhgfs-fuse /mnt/hgfs fuse defaults,allow_other 0 0

You will find your shared folder at /mnt/hgfs/<FOLDER_NAME> afterwards.
