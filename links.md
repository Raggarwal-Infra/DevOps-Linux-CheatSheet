# ln

Create a hard link to a file. Inode of actual file and the hard link are same. Changes made to hard link will reflect in the actual file as well. Deleting the actual file will not delete the content from hard link.

ln file.txt hardlink.txt
# ln -s

Create a symbolic (soft) link. Both actual file and the soft link will have different inodes. Deleting the actual file will also disable the soft link.

ln -s /var/log/app.log applog
