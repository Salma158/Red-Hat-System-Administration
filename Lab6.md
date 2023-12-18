# Lab 6
1. Use systemctl to view the status of all the system services.
<img src="./Lab6/Q1.png" width="500" >
2. Change the default run level back to multi-user.target and reboot.
<img src="./Lab6/Q2.png" width="500" >
3. Send mail to the root user.
<img src="./Lab6/Q3.png" width="500" >
4. Verify that you have received this mail.
<img src="./Lab6/Q4.png" width="500" >
5. Use  systemctl utility to stop postfix service
<img src="./Lab6/Q5.png" width="500" >
6. 6. Send mail again to the root user.
<img src="./Lab6/Q6.png" width="500" >
7. Verify that you have received this mail.
<img src="./Lab6/Q7.png" width="500" >
8. Use systemctl utility to start postfix service
<img src="./Lab6/Q8.png" width="500" >
9. Verify that you have received this mail.
<img src="./Lab6/Q9.png" width="500" >
10. Edit in the GRUB2 configuration file and change the timeout variable equal 20 seconds.
<img src="./Lab6/Q10p1.png" width="500" >
<img src="./Lab6/Q10P2.png" width="500" >
11.  Edit in the GRUB2 configuration file and change your default operating system
<img src="./Lab6/Q11p1.png" width="500" >
<img src="./Lab6/Q11p2.png" width="500" >
12. You want to know some information about the status of the system every ten minutes today between the hours of  8:00 AM and 5:00 PM. to help investigate some performance issues you have been having. You suspect it might be memory related and want to keep an eye on those resources.
<img src="./Lab6/Q12p1.png" width="500" >
<img src="./Lab6/Q12p2.png" width="500" >
13. Use mail as the root user to check for e-mail from the cron jobs you have scheduled.
<img src="./Lab6/Q13p1.png" width="500" >
<img src="./Lab6/Q13p2.png" width="500" >
14. How could you send the output from these cron jobs to another e-mail address (the manager user)?
15. Use mail as the manager user to check for e-mail from the cron jobs you have scheduled.
17. Attempt to run the command gnuplot. You should find that it is not
installed.
<img src="./Lab6/q17.png" width="500" >
18. Search for the plotting packages.
<img src="./Lab6/q18.png" width="500" >
19. Find out more information about the gunuplot package.
<img src="./Lab6/q19.png" width="500" >
20. Install the gnuplot package.
<img src="./Lab6/q20.png" width="500" >
21. Attempt to remove the gnuplot package, but say no
How many packages would be removed
<img src="./Lab6/q21.png" width="500" >
Using rpm
22. List all installed packages in your system.
23. View the files in the initscripts package

=> yum installed list | grep 'initscripts'

24. Get general information about bash rpm.
25. Have the files from the pam package changed since it was
installed.
26. Which installed packages have gnome in their names?

=> yum list installed | grep 'gnome'

27. Install any uninstalled package from RH Enterprise Linux cds
28. Search for software resemble the Photoshop software other than
Gimp and install it.
29. Create the file /etc/yum.repos.d/cdrom.repo to enable install from
the iso from the iso of Red Hat.
30. Try to install any package from the new repository
