the screenshots display the contents of the /etc/passwd group, which displays user 1 to 15 which was created and assigned to 3 different groups comprising of 5 users per group.

User1 is logged into and used to create a file and is granted permissions to read and write to it using the chmod 600 user1.txt command.

User2 is logged into and tries to read the file created by user1 but is unable to because permissions have not been granted to it on the file by user1.(The terminal throws a permission denied error)

Once permission for similar groups to read and write to the file is given to the file by user 1 using the command chmod 660 user1.txt, user2 can go ahead and read the file without the terminal throwing any errors.
