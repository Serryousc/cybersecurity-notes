# Linux Fundamentals - Permissions 

This document covers basic Linux permissions and how it works

---

## Basic Permission Commands

### Bash
`adduser 'username'` <br>
`deluser 'username'` <br>
`passwd 'username'` <br>
`su 'username'` <br>
`adduser 'username' sudo` <br>
`deluser 'username' sudo` <br>
`chmod` <br>
`chown` <br>
`groups` <br>
`id` <br>

### Command descriptions
  • `adduser 'username'`<br>
    Add a new user to the system <br>
  • `deluser 'username'`<br>
    removes user 'username' from the system<br>
  • `passwd 'username'`<br> 
    Set a password to user 'username' <br>
  • `su 'username'`<br> 
    Get a shell from user 'username' <br>
  • `adduser 'username' sudo`<br> 
    Add user 'username' to the system administration group <br>
  • `chmod`<br> 
    Changes file or directory permissions.<br>
    &nbsp;It controls three types of access:<br>
      &nbsp;&nbsp;`r` (read)<br>
      &nbsp;&nbsp;`w` (write)<br>
      &nbsp;&nbsp;`w` (execute)<br>
    &nbsp;For three types of entities:<br>
      &nbsp;&nbsp;Owner (`u`)<br>
      &nbsp;&nbsp;Group (`g`)<br>
      &nbsp;&nbsp;Others (`o`)<br>
    &nbsp;Example: `chmod 755 script.sh`<br>
    &nbsp;Owner: `rwx`, Group: `r-x`, Others: `r-x`.<br>
  • `chown`<br> 
    Changes the owner and/or group of a file or directory.<br>
    &nbsp;Example: `chown user file.txt`, `chown user:group file.txt`<br>
  • `groups`<br> 
    Displays the groups a user belongs to.<br>
    &nbsp;Example: `groups username`<br>
  • `id`<br> 
    Displays the UID, GID and group memberships of the current user or a specified user. <br>
    &nbsp;Example: `id`, `id username`<br>
 
 ### Security relevance
  • Improper user privilege assignment can lead to privilege escalation.<br>
  • Attackers may create new users to maintain persistence. <br>
  • Sudo group membership must be strictly controlled. <br>
  • Monitoring user creation and privilege is critical for detection.<br>
  • Correct permissions prevent unauthorized execution, reading and writing of sensitive data.<br>
  

  






