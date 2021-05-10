# Socket files in Linux
Socket files provide inter process communication. They can transfer data between processes on different environments.
That means e.g. tranferring data between processes on different machines on the network.
They are indicated by the file descriptor `s` in the in front of the permission string `srw-rw-rw-`

You can list the files in the current directory with the 
```sh
ls -l | grep "^s"
```

command.

----
[20210509063319](https://github.com/Miluba/Zettelkasten/blob/0d04c6346387273fff651b920754d77044ab0d9b/20210509063319)
#linux #filetypes #terminal #sockets
