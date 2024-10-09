# LinuxCommands


To show authorization of file, We can use -l

eaydin@eaydin ~/devel/crc $ ls -l
total 4
-rwxr-xr-- 1 eaydin plugdev 1925 Nov  4 01:36 crc8.py

First 3 rwx is representing the authorizations of eaydin user.

Second 3 r-x is representing the authorizations of plugdev group users.

Third 3 r-- is representing the authorizations of other users.


In order to enable write for all users, we need only chmod (change mod) +w

chmod +w crc8.py

Read = 4, Write = 2, Execute = 1


Total = 7 ( WRX)

For example:
rwx r-x r-- = 7    5    4

