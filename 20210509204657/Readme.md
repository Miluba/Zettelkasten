# Symbolic link files in Linux

They are indicated by the file descriptor `l` in the in front of the permission string `lrw-r--r--`

You can create a symbolic link `/home/miluba/file1.txt` to `file.txt` link using the 
```sh
ln -s file.txt /home/miluba/file1.txt
```

command.

You can list the files in the current directory with the 
```sh
ls -l | grep "^l"
```

command.

----
[20210509063319](https://github.com/Miluba/Zettelkasten/blob/0d04c6346387273fff651b920754d77044ab0d9b/20210509063319)
#linux #filetypes #terminal #symboliclinks
