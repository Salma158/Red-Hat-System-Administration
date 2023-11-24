# Red-Hat-System-Administration
# Lab 2
1. Create a user account with the following attribute
username: islam
Fullname/comment: Islam Askar
Password: islam

<img src="./Lab2/q1.png" width="500" />

2. Create a user account with the following attribute
Username: baduser
Full name/comment: Bad User
Password: baduser

<img src="./Lab2/q2.png" width="500" />

3. Create a supplementary (Secondary) group called pgroup with group ID of 30000

<img src="./Lab2/q3.png" width="500" />

4. Create a supplementary group called badgroup

<img src="./Lab2/q4.png" width="500" />

5. Add islam user to the pgroup group as a supplementary group

<img src="./Lab2/q5.png" width="500" />

6. Modify the password of islam's account to password

<img src="./Lab2/q6.png" width="500" />

7. Modify islam's account so the password expires after 30 days

<img src="./Lab2/q7.png" width="500" />

8. Lock bad user account so he can't log in

<img src="./Lab2/q8.png" width="500" />

9. Delete bad user account

<img src="./Lab2/q9.png" width="500" />

10. Delete the supplementary group called badgroup.

<img src="./Lab2/q10.png" width="500" />

13. Create a folder called myteam in your home directory and change its permissions to
read only for the owner.

<img src="./Lab2/q13.png" width="500" />

14. Log out and log in by another user
15. Try to access (by cd command) the folder (myteam)

<img src="./Lab2/q15.png" width="500" />

16. Using the command Line
Change the permissions of oldpasswd file to give owner read and write
permissions and for group write and execute and execute only for the others
(using chmod in 2 different ways)

<img src="./Lab2/q16p1.png" width="500" />

Change your default permissions to be as above.

<img src="./Lab2/q16p2.png" width="500" />

What is the maximum permission a file can have, by default when it is just
created? And what is that for directory.

for file : 666 (read & write) for owner, group, and others.
<br>
for directory : 777 (read & write & execute)  for owner, group, and others.

Change your default permissions to be no permission to everyone then create a
directory and a file to verify.

<img src="./Lab2/q16p3.png" width="500" />

<img src="./Lab2/q16p4.png" width="500" />

<img src="./Lab2/q16p5.png" width="500" />

17. What are the minimum permission needed for:

Copy a directory (permission for source directory and permissions for target
parent directory)

-> source directory : read and execute
<br>
-> target parent directory : write

Copy a file (permission for source file and and permission for target parent
directory)

-> source directory : read
<br>
-> target parent directory : write

Delete a file

-> write

Change to a directory

-> execute

List a directory content (ls command)

-> read

View a file content (more/cat command)

-> read 

Modify a file content

-> write

18. Create a file with permission 444. Try to edit in it and to remove it? Note what
happened.

<img src="./Lab2/q18.png" width="500" />
<br>
<img src="./Lab2/q18p2.png" width="500" />

19. What is the difference between the “x” permission for a file and for a
directory?

for a file: execute (x): allows the file to be executed as a program or script.
<br>
for a directory: execute (x): Allows accessing and traversing the directory.

