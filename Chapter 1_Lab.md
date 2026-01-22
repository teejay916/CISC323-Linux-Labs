Project 1-2: Connecting to the Server
I used SSH to securely connect to the Sacramento City College server.
`ssh -l cisc32x_wID cis.scc.losrios.edu`



Project 1-3: Using the date command
This project demonstrates that Linux is case-sensitive. The `date` command works, but `Date` does not.

Command:
`date`
`Date`
`date -u`



Project 1-5: Using the 'who' Command
I used the `who` command with various options (`-H`, `-u`, `-q`) to list logged-in users and session details. I also used `who am i` to verify my specific connection.

Command:
`who`, `who -H`, `who -uH`, `who -q`, `who am i`, `whoami`



Project 1-6: Clearing the Terminal
I used the `clear` command to reset the terminal display. This is a vital practice for maintaining a clean and organized workspace during complex tasks.

Command:
 `clear`



Project 1-7: Accessing Manual Pages
I used the `man` command to access the system's built-in manual for the `who` command. This is an essential skill for troubleshooting and learning new command flags.

Commmand:
`man who`



Project 1-8: Command-Line Editing
I practiced using Bash shell shortcuts to navigate and edit the command line. This included using `echo $SHELL` to identify my environment and shortcuts like `Ctrl+a` and `Ctrl+k`.

Command:
`echo $SHELL`
`who am I` (Edited using shortcuts)



Project 1-10: Command History
I used the Bash shell history feature to recall and execute previous commands using the arrow keys. This is a time-saving technique for repeating frequent tasks.

Command:
`history`



Project 1-11: Changing the User Password
I used the `passwd` command to practice account security. I observed that Linux does not display any characters (not even asterisks) when typing passwords, which is a security feature to prevent shoulder-surfing.

Command
`passwd`



Project 1-12: Viewing Files with 'cat'
I used the `cat` command to view the `/etc/shells` file, which lists the valid shell programs on this system. I also used the `-n` flag to display the output with line numbers.

Command:
`cat /etc/shells`
`cat -n /etc/shells`



Project 1-15: Output Redirection
I used the `>` operator to redirect the output of the `who` command into a new text file named `current_users`. I then verified the file's contents using the `cat` command.

Commands:
`who > current_users`
`cat current_users`



Project 1-17: Creating and Appending Files
I practiced creating a text file using `cat >` and appending new data (including a calendar) using `cat >>` and `cal >>`. This demonstrated how to build and modify files without using a text editor.

Commands:
`cat > notes`
`cat >> notes`
`cal 9 2009 >> notes`
`cat notes`
