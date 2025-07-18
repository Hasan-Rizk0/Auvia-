
Solutions of levels 4,5,and 6 + steps:

First you should log into the game using SSH:

		ssh bandit(the_number_of_the_level)@bandit.labs.overthewire.org -p 2220

bandit (the_number_of_the_level) ----> the username

bandit.labs.overthewire.org ----> the host 

-p 2220 ----> the connection is on port 2220

Each level has a password to be opened, and this password is gained by solving the previous level challenge.

--------------------------------------------------------------------------

**Level 4:
			First, we should list the files in our directory using ls command or ls -lah command and go to the inhere directory using (cd)
			Second, we should (ls) the contents of inhere directory which contains the password of the next level 
			Third, we should use the  find . -type f | xargs file command
			Finally, the only file which contains ASCII content (readable) will be the password 

**Level 5:
			First, we should list the files in our directory using ls command or ls -lah command to see the hidden files and in a human readable way and in a tabular form 
			Second, we should go to the inhere directory using (cd)
			Third, we should use Find -type f -size 1033c ! -executable 
			Finally, cat the resultant file and you will get the password

**Level 6:
			First, we should list the files in our directory using ls command 
			Second, we should use the Find / -user bandit7 -group bandit6 -size 33c 
			Finally, you will find a list of files between them a path that leads you to the password, cat this file and you have the password