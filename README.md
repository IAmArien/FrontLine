# FrontLine
<b>FrontLine - SSH and SQL Database Critter</b> is written in a <b>Python Script</b>, with the support of <b>Shell Scripting</b>, capable of brute forcing a specific selected server with a bunch of passphrases and be able to load commands, access directories, data, tables from a databases, schemas and table structures and more..<br/>
![alt text](https://blogvaronis2.wpengine.com/wp-content/uploads/2018/10/brute-force-attack.jpg)<br/>
<b>What is a Brute Force ?</b><br/>
In cryptography, a brute-force attack consists of an attacker submitting many passwords or passphrases with the hope of eventually guessing correctly. The attacker systematically checks all possible passwords and passphrases until the correct one is found.

# Oracle SQL Database Server
Brute Forcing Oracle SQL Database Server using <b>cx_Oracle</b> with <b>Python</b>
![alt text](https://user-images.githubusercontent.com/45601866/75333738-a21d8f00-58c1-11ea-9ba8-fbf1f2c4c847.png)

The script can also easily access and dig into Database Structures, Hundreds and Thousands of Data, Table Structures, Schemas and more using the Brute Force Attack with <b>Oracle SQL Database</b>. Once the correct passphrase successfully loaded and match the exact credentials needed to access the server, the user can now execute <b>Oracle SQL Commands</b> that could fetch certain data from the database, manipulate the database and even do some critical executions such as to <b>Truncate, Drop, Delete, Create, Alter etc</b> the following tables inside the DB.<br/>
You can navigate through <a href="https://docs.oracle.com/cd/E11882_01/server.112/e41085/sqlqr01001.htm#SQLQR110" target="_blank"> here </a> to browse for more <b>Oracle SQL Statement Syntax</b> that you can use here 

# SSH Server
![74913855-69cb0c00-53fc-11ea-9513-763c70206107](https://user-images.githubusercontent.com/45601866/75428545-56331e80-5983-11ea-8986-b75db6e73fb0.png)

The script can access any <b>SSH Servers</b> once the correct passphrase is found during the loads of brute forcing. When the script finally accessed the SSH Server, the user can now navigate to different directories stored in the server, also can <b>create, read, update, and delete</b> different files and execute some critical commands such as <b>rm or rmdir</b> to delete files or directories, run jobs and processes saved in the server and many more. The user can also upload shell scripts that can quickly and easily manipulate files. 
This is very helpful when an attacker wants to gain some information from a specific company, or even delete their back ups and permanent files the companies is using in a daily basis.<br/>

<b>Below are the special commands that you can run for alternatives.</b><br/>
<ul>
  <li><b>--upload-local-file</b>: type and press the enter key to execute this type of command to start uploading a local file/s from your computer to the <b>SSH Server</b>. Once executed, the script will going to ask for two inputs, <b>Remote File Path</b> (<i>asking the user to enter the specific path in where the uploaded file will be stored</i>), <b>Local File Path</b> (<i>there will be a prompt window for the user to choose a single or multiple files he/she wants to upload to the server</i>). If all things are okay, the script will now going to upload the selected file/s to the <b>SSH Server</b></li>
  <li><b>--download-remote-file</b>: type and press te enter key to execute. This type of command do the vice versa of the above command, it download file/s from the <b>SSH Server</b> and save it to the local directories. There's also two inputs the script will gonna ask, <b>Remote File Path</b> (<i>asking the user to enter the compelete path of the file the user wants to download</i>), <b>Local Path</b> (<i>asking to enter the path or the directory where the downloaded remote file will be stored</i>).</li>
</ul><br/>
<b>Using --upload-local-file</b><br/>

![74913166-14dac600-53fb-11ea-91e1-3c1a96f2d80c](https://user-images.githubusercontent.com/45601866/75428460-2edc5180-5983-11ea-9752-cd98d0e82a6d.png)

<b>Using --download-remote-file</b><br/>
![74913162-13110280-53fb-11ea-8dfc-cee3d3507e44](https://user-images.githubusercontent.com/45601866/75428525-4adff300-5983-11ea-8621-15df12a7d2e7.png)

You can check if the file was successfully uploaded by executing <b>ls -lrt</b> command in the FrontLine Terminal, just type <i>cd /some/directory/; ls -lrt</i>...

Also the same thing when checking if you have successfully downloaded the file from the remote server, just browse in the selected directory in where you have enter the directory of the downloaded file.
