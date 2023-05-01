Download Link: https://assignmentchef.com/product/solved-cecs326-homework-0
<br>
Purpose: To test your accounts, logins, remote access, demos, and write simple programs on Linux. This assignment is ungraded but should help familiarize you with the Linux environment.

Applications/Utilities directory.

The terminal will start you out in your home directory. It is in /home and is named after your student id. If you do an “ls” you should see sub directories like Downloads and Desktop.

<ul>

 <li>Use “cd Desktop” to go to your desktop. Now, make a new directory called testdir using the command “mkdir testdir”. You should see this directory appear on your desktop.</li>

 <li>Create an empty file with the touch command. “touch emptyfile”. You’ll see an emtpy file on your desktop. You can open and edit it if you wish.</li>

 <li>Delete the empty file with “rm emptyfile”. You should see it dissapear. Delete the directory using “rm -r testdir”. (the -r argument is needed for directories. It stands for recursive.)</li>

 <li>Use “cd ..” to go back up one level to the root of your home directory. Make a new directory there called “Homework00” (this should not be on your desktop, although you can open a file explorer and see it in a window).</li>

 <li>Create 3 files in this Homework00 directory.</li>

</ul>

<ol>

 <li>The first should be called “whereami” and should contain a single line with the output of the “pwd”command.</li>

 <li>The second is a python “helloworld.py”. You should already know how to do this, but perhaps youhaven’t done this outside of an IDE like pycharm. I’d like you to write this with a basic text editor and run it on the command line using “python helloworld.py”.</li>

 <li>Lastly, you’ll write an equivalent C++ “helloworld.cpp” program in a basic text editor. To compile the program: g++ helloworld.cpp -o helloworld</li>

</ol>

<ul>

 <li>After the first homework, work will be done on a remote server called “linux1.cecs.csulb.edu”. First, run</li>

</ul>

the “hostname” command on your local machine and note the name. Then use “ssh <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="c4bdabb1b6b7b0b1a0a1aab0ada084a8adaab1bcf5eaa7a1a7b7eaa7b7b1a8a6eaa1a0b1">[email protected]</a>” and run the hostname command there.

<ul>

 <li>OPTIONAL: If you have a laptop or are at home, you may still access linux1 remotely. If you use Linux or a Mac, open a terminal, use “ssh -p 2022 <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="225b4d575051565746474c564b46621311160c13111b0c10161a0c10">[email protected]</a>”. If you are using windows, download a tool called “Putty” and use ssh (port 2022) with that. Note: ssh may work with the default port 22, but this is not guarenteed due to campus firewall rules.</li>

</ul>


