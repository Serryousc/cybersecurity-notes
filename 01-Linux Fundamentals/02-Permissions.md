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
  • `adduser 'username'`
    Add a new user to the system <br>
  • `deluser 'username'`
    removes user 'username' from the system<br>
  • `passwd 'username'` 
    Set a password to user 'username' <br>
  • `su 'username'` 
    Get a shell from user 'username' <br>
  • `adduser 'username' sudo` 
    Add user 'username' to the system administration group <br>
  • `chmod` 
    Changes file or directory permissions.<br>
    It controls three types of access:<br>
      `r` (read)<br>
      `w` (write)<br>
      `w` (execute)<br>
    For three types of entities:<br>
      Owner (`u`)<br>
      Group (`g`)<br>
      Others (`o`)<br>
    Example: `chmod 755 script.sh`<br>
    Owner: `rwx`, Group: `r-x`, Others: `r-x`.<br>
  • `chown` 
    Changes the owner and/or group of a file or directory.<br>
    Example: `chown user file.txt`, `chown user:group file.txt`<br>
  • `groups` 
    Displays the groups a user belongs to.<br>
    Example: `groups username`<br>
  • `id` 
    Displays the UID, GID and group memberships of the current user or a specified user. <br>
    Example: `id`, `id username`
 
 ### Security relevance
  • Improper user privilege assignment can lead to privilege escalation.<br>
  • Attackers may create new users to maintain persistence. <br>
  • Sudo group membership must be strictly controlled. <br>
  • Monitoring user creation and privilege is critical for detection.<br>
  • Correct permissions prevent unauthorized execution, reading and writing of sensitive data.<br>
  

  






