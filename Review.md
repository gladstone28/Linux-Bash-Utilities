
Linux Shell Utilities
Review

Good job on reaching the end of this lesson! You are now well-equipped or at least aware of the number of utilities available in the 
Linux
Preview: Docs Loading link description
 shell. To review, we talked about:

####Documentation

Documentation is a great way to learn about installed utilities.

- The /usr/share/doc/ directory contains README files and other documents for installed commands.
- man is a command to access reference manual pages for all installed commands. Usage: man <command_name>.
- infois a command to access full-detailed information pages for all installed commands. Usage info <command_name>.

#### Compression
Compression reduces file sizes. Three popular compression commands are gzip, bzip2, and xz. To compress, run commands like so: <compression_utility> [options] <file_name>. To decompress, include the -d option: <compression_utility> -d <compressed_file_name>. gzip also supports the -r option to compress all files in a directory.

#### Archive

zip and tar are two archiving utilities that package multiple files into a single archive file. zip: archives and compresses files.

- Archive: zip <archive_name>.zip <file1> <file2>... Use -r option for directories.
- Extract: unzip <archive_name>.zip.

tar: only archives files by default but has options to utilize compression utilities. Unlike zip, it preserves Unix file attributes like file permissions.

- Archive: tar -cf <archive_name>.tar <files or directory>.
- Extract: tar -xf <archive_name>.tar.
- Add options -z, -j, or -J to compress via gzip, bzip2, or xz respectively.

#### Networking

Basic network commands:

- curl or wget: Interacts with a webpage or file hosted online.
- ping <target domain or IP>: Checks connectivity between two devices on the same network.
- host <domain or IP>: Performs DNS lookups.
- ifconfig: Shows network interface information.

Feel free to practice in the terminal!

