# Hard link files in Linux

A hard link is in contrast to the symbolic link a copy of the original file. 
Contents of the files are synced but if you delete a hardlink the origin is kept.

You can create a hard link `/home/miluba/file1` to `file1` using the 
```sh
ln file1 /home/miluba/
```

command.

You can see how many hard links of a given file exist with the
```sh
ls -al
```

command.

The number right to the permission is indicating the amount of hard links. `2` in `-rw------- 2` is indicating 
that one hard link exists. The number is indicating the reference count to the underlying inode. Hard links are unidirectional that means that the origin file is not aware of the corresponding hard links.

You can find all hard links using the inode number of the original and find.
```sh
ls -i 
# 83320 file1

find / -inum 83320
# /home/miluba/file1
# /home/miluba/test/file1
```


----
[20210509063319](https://github.com/Miluba/Zettelkasten/blob/0d04c6346387273fff651b920754d77044ab0d9b/20210509063319)
#linux #filetypes #terminal #hardlinks
