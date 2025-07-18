
The second column in each row of the listed files and directories  actually  represents the owner of the file of the directory.

It is also divided into two parts (two names) the first one is the owner and the second name is the group owner.

In order to change the ownership of a file or a directory the chown command is used (changes the first name) 

Before changing to the root user for example, you should navigate to the root user first


		chown the user that you want to change the ownership to  the file name you want to change its ownership ---> changes the ownership of the specified file


In order to change the group owner of a file or a directory the chgrp command is used (changes the second name)


		chgrp the group that you want to change the ownership to  the file name you want to change its ownership ---> changes the group ownership of the specified file