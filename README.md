# fusefilesystem
to compile:
gcc project3_main.c -o main -D_FILE_OFFSET_BITS=64 -l fuse <br/>
to run:
./main /mount_directory
<br/>
to compile:
gcc project3_with_debug.c -o main -D_FILE_OFFSET_BITS=64 -l fuse <br/>
to run with debug mode:
./main -d /mount_directory
<br/>
to unmount:
fusermount -u /mount_directory
<br/>
Şamil Taner Cengiz <br/>
Melih Kağan Özçelik <br/>
Halil İbrahim Yavuz
