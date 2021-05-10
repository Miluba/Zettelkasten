# In Linux everything is a file
In linux [everything is a file](https://en.wikipedia.org/wiki/Everything_is_a_file) in fact everything is an *index node* called [inode](https://en.wikipedia.org/wiki/Inode) which is a data structure in unix based filesystems.
There are different type of files:
| Type | Descriptor | Description
| --- | --- | --- |
| [Normal](https://github.com/Miluba/Zettelkasten/blob/3e815024a9b95023bf0cbc0c764b2284792a5302/20210509071218/Readme.md) | - | Normal file |
| [Directories](https://github.com/Miluba/Zettelkasten/blob/508fbb015ea52070c72aff438b41ef9f0118e1ab/20210510100509/Readme.md) | d | Normal directory |
| [Hard Link](https://github.com/Miluba/Zettelkasten/blob/1c23a3183a9fc517689fcd662f7f869f4487b1e9/20210510090904/Readme.md) | - | Additional name for an existing file |
| [Symbolic Link](https://github.com/Miluba/Zettelkasten/blob/8bf7721a41b11654de27a54f98059d54eedafde6/20210509204657/Readme.md) | l | Shortcut to a file or directory |
| Socket | s | Pass data between processes |
| Named Pipes | p | Like sockets provides the output of a process as an input to other processes |
| [Character Device](https://github.com/Miluba/Zettelkasten/blob/de0990c1785daa7e34b5edd65701d9c8820a109a/20210509202209/Readme.md) | c | Processes character hardware communication |
| [Block Device](https://github.com/Miluba/Zettelkasten/blob/97741a1d8790b17e3b2b889a02dd65c56e85f5d8/20210509201026/Readme.md) | b | Processes buffered hardware communication |
----
#linux #filetypes #inodes #filesystem
