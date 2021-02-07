# fusefilesystem
to compile:
gcc project3_main.c -o main -D_FILE_OFFSET_BITS=64 -l fuse
to run:
./main /mount_directory

to compile:
gcc project3_with_debug.c -o main -D_FILE_OFFSET_BITS=64 -l fuse
to run with debug mode:
./main -d /mount_directory

to unmount:
fusermount -u /mount_directory

Şamil Taner Cengiz \n
Melih Kağan Özçelik \n
Halil İbrahim Yavuz
