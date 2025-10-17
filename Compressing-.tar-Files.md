
Linux Shell Utilities

#### Compressing .tar Files

What makes tar powerful is that we can combine it with the compression utilities we discussed in a previous exercise to create a compressed archive. tar with the -c and -f options relate to archiving functionalities, but we can also call tar with other options to compress:

- -z : Compress the resulting archive using gzip. Resulting file extension: .tar.gz.
- -j : Compress the resulting archive using bzip2. Resulting file extension: .tar.bz2.
- -J : Compress the resulting archive using xz. Resulting file extension: .tar.xz.

For example, to compress an archive/tarball of some video files video1.mp4 and video2.mkv, where we want the resulting compress archive to be called videos.tar.bz2 we use the following command:
