# Block files in linux
Block files provide buffered access to system hardware components. 
Used to communicate with device drivers through the filesystem.
They can transfer a large block of data at a given time. 
They are indicated by the file descriptor `b` in the in front of the permission string `brw-r--r--`

You can list the files in the current directory with the 
```sh
ls -l | grep "^b"
```

command.

----
[20210509063319](https://github.com/Miluba/Zettelkasten/blob/0d04c6346387273fff651b920754d77044ab0d9b/20210509063319)
#linux #filetypes #terminal #blockfiles
