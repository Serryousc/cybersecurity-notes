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
  • `deluser 'username' sudo` 
    Remove user 'username' to the system administration group <br>
 
 ### Security relevance
  • Improper user privilege assignment can lead to privilege escalation. <br>
  • Attackers may create new users to maintain persistence. <br>
  • Sudo group membership must be strictly controlled. <br>
  • Monitoring user creation and privilege is critical for detection.<br>

  






