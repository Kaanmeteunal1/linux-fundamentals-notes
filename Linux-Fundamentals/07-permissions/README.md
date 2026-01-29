```shell-session
Binary Notation:                4 2 1  |  4 2 1  |  4 2 1
----------------------------------------------------------
Binary Representation:          1 1 1  |  1 0 1  |  1 0 0
----------------------------------------------------------
Octal Value:                      7    |    5    |    4
----------------------------------------------------------
Permission Representation:      r w x  |  r - x  |  r - -
```
chmod (u/g/a +/- rwx) filename  "u user g group a for all + add - remove r is read w is write x is execute " change permission
chmod 754 "first number for user second is group and third is for all" read's number is 4 w is 2 x 1 total of numbers means permissions. 
```shell-session
chown <user>:<group> <file/directory>
``` to change owner 
https://gtfobins.github.io/gtfobins/journalctl/
Sticky Bit
permission for shared fields prevents to delete that file or direction from users when they have perm and that file does not made by him
T means other users do not have execute permission 
t means sticky bit set for nothing means
to set chmod 1xxx or chmod +t filename