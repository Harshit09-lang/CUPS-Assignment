# ADDING COMMENTS AND PRINTING THEM
I made some changes to the cupsFilePrintf() function in the scheduler's log.c file. I made a note of the function. Following the file's modification. Retype the build and make install commands.

## Here is modified accesslog
```
localhost - - [23/Dec/2022:11:37:39 +0530] "POST /admin/ HTTP/1.1" 401 243 CUPS>
localhost - harshitk [23/Dec/2022:11:37:39 +0530] "POST /admin/ HTTP/1.1" 403 2>
localhost - - [23/Dec/2022:11:38:46 +0530] "POST /admin/ HTTP/1.1" 401 239 CUPS>
localhost - root [23/Dec/2022:11:38:46 +0530] "POST /admin/ HTTP/1.1" 200 239 C>
localhost - - [23/Dec/2022:11:39:06 +0530] "POST /admin/ HTTP/1.1" 401 239 CUPS>
localhost - root [23/Dec/2022:11:39:06 +0530] "POST /admin/ HTTP/1.1" 200 239 C>
 Harshit Krishna was here
 localhost - - [23/Dec/2022:12:01:58 +0530] "POST /admin/ HTTP/1.1" 401 241 CUP>
 Harshit Krishna was here
 localhost - root [23/Dec/2022:12:01:58 +0530] "POST /admin/ HTTP/1.1" 200 241 >
 Harshit Krishna was here
 localhost - - [23/Dec/2022:12:07:30 +0530] "POST / HTTP/1.1" 200 187 Renew-Sub>
 Harshit Krishna was here
 localhost - - [23/Dec/2022:12:13:03 +0530] "POST /printers/testPrint HTTP/1.1">
 Harshit Krishna was here
```
