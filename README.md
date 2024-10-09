<h1>Linux</h1>

<h2>Description</h2>
Linux is a powerful, open-source operating system widely used for its stability, flexibility, and strong security features. Its versatility makes it a key platform in IT infrastructure and cybersecurity, supporting tools for system administration, network management, and penetration testing. Popular distributions like Ubuntu and Kali Linux are essential for professionals in development and security operations.<br />

<h2>Languages and Utilities Used:</h2>

- <b>Bash</b>: For scripting, task automation, and system administration
- <b>SQL</b>: For database queries and management
- <b>TCPdump</b>: For packet capture and network traffic analysis
- <b>Wireshark</b>: For detailed protocol analysis and network troubleshooting
- <b>Python</b>: For security automation, scripting, and network analysis


<h2>Key Commands for Navigating the File System:</h2>

- <b>pwd</b>: Prints the current working directory.
  - Example: pwd shows the path of the directory you're currently in.
  - Pro Tip: Use whoami to display the current user's name.
- <b>ls</b>: Lists files and directories in the current directory.
  - Example: ls displays files like logs and updates.txt.
  - Tip: To list the contents of another directory, use an absolute or relative path, e.g., ls /home/analyst/projects.
- <b>cd</b>: Changes the current directory.
  - Example: cd projects moves to the projects subdirectory.
  - Pro Tip: Use cd .. to go up one directory level.
<img src="https://i.imgur.com/KV15cfv.jpeg" height="70%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Common Commands for Reading File Content:</h2>

- <b>cat</b>: Displays the full content of a file.
  - Example: cat updates.txt shows the entire file.
- <b>head</b>: Displays the first few lines of a file (default 10).
  - Example: head updates.txt returns the first 10 lines.
  - Pro Tip: Customize the number of lines with -n, e.g., head -n 5 updates.txt.
- <b>tail</b>: Displays the last few lines of a file (default 10).
  - Example: tail updates.txt returns the last 10 lines.
- <b>less</b>: Displays file content one page at a time.
  - Example: less updates.txt lets you scroll through a file.
  - Controls: Use spacebar to move forward, b to move back, and q to quit.


<h2>Filtering and Searching Commands:</h2>

- <b>grep</b>: Searches for a specific string in a file.
  - Example: grep OS updates.txt finds all lines containing "OS".
- <b>Piping (|)</b>: Sends output of one command as input to another.
  - Example: ls /home/analyst/reports | grep users lists files containing "users".

 <h2>File and Directory Management:</h2>

- <b>mkdir</b>: Creates a new directory.
  - Example: mkdir /home/analyst/logs/network creates the network directory.
- <b>rmdir</b>: Removes an empty directory.
  - Example: rmdir /home/analyst/logs/network removes the network directory.
- <b>touch</b>:Creates an empty file.
  - Example: touch permissions.txt creates a file called permissions.txt.
- <b>rm</b>: Removes a file.
  - Example: rm permissions.txt deletes the file
- <b>mv</b>:Moves or renames a file or directory.
  -Example: mv permissions.txt /home/analyst/logs moves the file to the logs directory.
- <b>cp</b>: Copies a file or directory.
  - Example: cp permissions.txt /home/analyst/logs copies the file to the logs directory.

 <h2>Permissions and Ownership:</h2>
 
- <b>ls -l</b>: Displays detailed file information, including permissions.
  - Example: ls -l shows file permissions, owner, and group.
- <b>chmod</b>: Changes file permissions
  - Example: chmod g+w,o-r access.txt grants write permission to the group and removes read access for others.


<img src="https://i.imgur.com/eRPorkY.jpeg" height="70%" width="80%" alt="Disk Sanitization Steps"/>

<ins>Since the file is empty, there won't be any output, but  <b>cat</b> will display its contents if it had text. </ins>

<img src="https://i.imgur.com/RLOapBF.jpeg" height="70%" width="80%" alt="Disk Sanitization Steps"/>

