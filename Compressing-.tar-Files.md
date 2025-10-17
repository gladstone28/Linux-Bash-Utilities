
Linux Shell Utilities

#### Compressing .tar Files

What makes tar powerful is that we can combine it with the compression utilities we discussed in a previous exercise to create a compressed archive. tar with the -c and -f options relate to archiving functionalities, but we can also call tar with other options to compress:

- -z : Compress the resulting archive using gzip. Resulting file extension: .tar.gz.
- -j : Compress the resulting archive using bzip2. Resulting file extension: .tar.bz2.
- -J : Compress the resulting archive using xz. Resulting file extension: .tar.xz.

For example, to compress an archive/tarball of some video files video1.mp4 and video2.mkv, where we want the resulting compress archive to be called videos.tar.bz2 we use the following command:

```
tar -cjf videos.tar.bz2 video1.mp4 video2.mkv

```
The compression and archiving results in the concatenation of file extensions. Make sure the extension of the archive name corresponds with the compression option.

### Decompressing and Extracting .tar Files

To extract and decompress a compressed .tar archive, we change the option -c to -x:

```
tar -xjf videos.tar.bz2

```

Be sure to use the right option that corresponds with the compressed format, whether it’s bz2, xz, or gzip.

link to lesson

https://www.codecademy.com/courses/introduction-to-linux-bash-scripting/lessons/linux-shell-utilities/exercises/compressing-tar-files
