After listing the directories and files in a specific directory using (ls -l or ls -la or.....(listing the content in a table format)), we can see in the beginning of each row letters like rwx...
these letters are called file and directory Permissions.

x ---> meaning "allowed to execute it"

r ---> meaning "allowed to read it"

w ---> meaning "allowed to write changes to it"

((((These are mainly the three basic permissions to be learnt))))

The Permissions column in each row is divided into three blocks, each block contains three places for r, w, and x.

The first block stands for the user (owner) (u)
The second block stands for group (g)
The third one stands for others (o)

chmod ---> change mode command is used to change edit the permissions of any file or directory 

		chmod u=rwx the file name ---> edit the user permissions to allow to read, write and execute. (one, or two, or all the letters r,w,or x can be used)(and u, g, or o or two of them or all of them can be used instead of u in this case)

The previous way is called symbolic mode, there is also another mode called octo mode where;

r = 4 

w = 2

x = 1 

You can put numbers instead of letters, you can also add numbers instead of putting more than one letter. For example instead of writing chmod a=rwx the name of the file (a stands for all three (u, g, and o)), you can simply write chmod 777 the name of the file (which is 4 +2 +1).

There is also a command that can edit the Permissions of the files or directories in another directory (Recursively) which is:

Example:
chmod -R 777 the name of the file or directory

