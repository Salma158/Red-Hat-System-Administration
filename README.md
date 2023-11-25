# Red-Hat-System-Administration

# Lab 2

name : salma sherif 

track : open source application development

branch : new capital 

1. List the user commands and redirect the output to /tmp/commands.list

<img src="./Lab4/q1.png" width="500">

2. Count the number of user commands

<img src="./Lab4/q2.png" width="500">

3. Get all the users names whose first character in their login is ‘g’.

<img src="./Lab4/q3.png" width="500">

4. Get the logins name and full names (comment) of logins starts with “g”.

<img src="./Lab4/q4.png" width="500">

5. Save the output of the last command sorted by their full names in a file.

<img src="./Lab4/q5.png" width="500">

6. Write two commands: first: to search for all files on the system that named
.bash_profile. Second: sorts the output of ls command on / recursively, Saving
their output and error in 2 different files and sending them to the background.

<img src="./Lab4/q6.png" width="500">

7. Display the number of users who is logged now to the system.

<img src="./Lab4/q7.png" width="500">

8. Display lines 7 to line 10 of /etc/passwd file

<img src="./Lab4/q8.png" width="500">

9. What happens if you execute:

- cat filename1 | cat filename2

<img src="./Lab4/q9p1.png" width="500">

- it will display the content of filename2 only.

- ls | rm

<img src="./Lab4/q9p2.png" width="500">

error : missing operand , because ls will not output anything to rm , and rm is waiting for file to delete

- ls /etc/passwd | wc –l

<img src="./Lab4/q9p3.png" width="500">

it lists the content of the /etc/passwd file,
The output is then piped to wc -l, which counts the number of lines.
This command counts the number of user accounts on the system.

10.Issue the command sleep 100.

<img src="./Lab4/q10.png" width="500">

11.Stop the last command.

<img src="./Lab4/q11.png" width="500">

12.Resume the last command in the background

<img src="./Lab4/q12.png" width="500">

13.Issue the jobs command and see its output.

<img src="./Lab4/q13.png" width="500">

14.Send the sleep command to the foreground and send it again to the background.

<img src="./Lab4/q14.png" width="500">

15.Kill the sleep command.

<img src="./Lab4/q15.png" width="500">

16.Display your processes only

<img src="./Lab4/q16.png" width="500">

17.Display all processes except yours

<img src="./Lab4/q17.png" width="500">

18.Use the pgrep command to list your processes only.

<img src="./Lab4/q18.png" width="500">

19.Kill your processes only.

-> pkill -u dell
