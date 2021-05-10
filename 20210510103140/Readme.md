# Pipes or named pipes files in Linux
Pipes or named pipes allow inter-process communication by connecting the output of one process to the input of another.
A named pipe is a file that acts as a pipe to enable communication between two processes.

They are indicated by the file descriptor `p` in the in front of the permission string `prw-r--r--`

You can list the files in the current directory with the 
```sh
ls -l | grep "^p"
```

command.

You can create a named pipe using the 
```sh
mkfifo namedpipe
```

command. Now you can access the data from another terminal e.g. using the
```sh
while read line ;do echo "This was passed-'$line' "; done<namedpipe
```

command.

----
[20210509063319](https://github.com/Miluba/Zettelkasten/blob/0d04c6346387273fff651b920754d77044ab0d9b/20210509063319)
#linux #filetypes #terminal #namedpipe
