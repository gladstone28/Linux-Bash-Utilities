
Linux Shell Utilities

# Archive Utilities

Archiving allows us to consolidate multiple files or directories into a single archived file. Two of the popular archive commands on 
Linux
Preview: Docs Loading link description
, zip and tar, have the ability to compress and archive files. This means that unlike the compression commands which compress a single file at a time, the files’ size will be reduced and packaged into a single archive file in one command.

### zip

Zip files are very popular across multiple operating systems. We can create a .zip archive like so:

```
zip <archive_name>.zip <file1> <file2> …

```

Note: On some distributions of Linux, zip must first be installed using the command sudo apt install zip unzip.

Directories can be easily archived with the -r option. Archived files can be extracted and decompressed using the unzip command and providing paths to one or more .zipfiles.

**tar**

tar, which stands for tape archive or tarball, is a very important archiving utility for Linux systems. While a zip archive is more popular across platforms, it is recommended to use tar when distributing archives among Linux-based systems. This is because tar archives store Unix file attributes, retaining file permissions and other metadata.

```
tar -cf <archive_name>.tar <files or directories>

```

creates an uncompressed .tar archive. A .tar file can be referred to as a tarball.

For example,

```
tar -cf example.tar index.html script.js style.css

```
will create a .tar archive file with three files: index.html, script.js, and style.css.

To extract the files in a .tar archive, we can use the -xf option.

```
tar -xf <archive_name>.tar

```

link to the lesson below

https://www.codecademy.com/courses/introduction-to-linux-bash-scripting/lessons/linux-shell-utilities/exercises/compressing-tar-files
