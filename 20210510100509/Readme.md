# Directory file in Linux
A directory stores other linux files. Directories are organized in the Linux filesystem in a hierarchy 
starting from the root `/` directory. They are indicated by the file descriptor 
`d` in the in front of the permission string `drw-r--r--`

You can create a directory using the 
```sh
mkdir folder
```

command.

You can list the direcories in the current directory with the 
```sh
ls -l | grep "^d"
```

command.

----
[20210509063319](https://github.com/Miluba/Zettelkasten/blob/0d04c6346387273fff651b920754d77044ab0d9b/20210509063319)
#linux #filetypes #terminal #directory
