# In Linux everything is a file
In linux [everything is a file](https://en.wikipedia.org/wiki/Everything_is_a_file) in fact everything is an *index node* called [inode](https://en.wikipedia.org/wiki/Inode) which is a data structure in unix based filesystems.
There are different type of files:
| Type | Descriptor | Description
| --- | --- | --- |
| Normal | - | Normal file |
| Directories | d | Normal directory |
| Hard Link | - | Additional name for an existing file |
| Symbolic Link | l | Shortcut to a file or directory |
| Socket | s | Pass data between processes |
| Named Pipes | p | Like sockets provides the output of a process as an input to other processes |
| Character Device | c | Processes character hardware communication |
| Block Device | b | Processes buffered hardware communication |
----
#linux #filetypes #inodes #filesystem
