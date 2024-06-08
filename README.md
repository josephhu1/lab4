# Hey! I'm Filing Here

In this lab, I successfully implemented a valid ext2 filesystem.
It contains 2 directories, 1 regular file, and 1 symbolic link.

## Building

$ make # compile the executable

## Running

$ ./ext2-create # run the executable to create cs111-base.img
$ mkdir mnt # create a directory to mnt your filesystem to
$ sudo mount -o loop cs111-base.img mnt # mount your filesystem, loop lets you use a file


## Cleaning up

$ sudo umount mnt # unmount the filesystem when you're done
$ rmdir mnt # delete the directory used for mounting when you're done
$ make clean # remove executable files

