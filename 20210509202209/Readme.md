# Character files in Linux
Character files are device files that provide unbuffered serial access to system hardware components.
They provide communication with devices transferring one char at a time.

They are indicated by the file descriptor `c` in the in front of the permission string `crw-r--r--`

You can list the files in the current directory with the 
```sh
ls -l | grep "^c"
```

command.

----
[20210509063319](https://github.com/Miluba/Zettelkasten/blob/0d04c6346387273fff651b920754d77044ab0d9b/20210509063319)
#linux #filetypes #terminal #characterfiles
