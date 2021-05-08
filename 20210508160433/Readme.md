# Getting the UTC time ISO seconds in terminal
You can get the current second formatted as ISO second with the [date](https://man7.org/linux/man-pages/man1/date.1.html) command.
Simply by tiping the following command:
```sh
date -u +%Y%m%d%H%M%S
```
You have to be sure that your system time is correct. To do this you can set your system time from your hardware clock:
```sh
sudo hwclock --hctosys
```
This is espacially useful if you are using wsl in windows because it is likely that the time is not correct.
----
[1620093558](https://github.com/Miluba/Zettelkasten/tree/main/1620093558)
#terminal #date #linux #isoseconds
