# Linux Fundamentals - Bash and Terminal 

This document covers basic Linux navigation commnads and heir relevance for system administration and security operations.

---

## Basic Navegation Commands

# Bash
`pwd` <br>
`ls` <br>
`ls -l` <br>
`ls -a` <br>
`cd` <br>
`cd ..` <br>
`cd /path/to/directory` <br>

## Command descriptions
  • `pwd`  
    Display the current working directory <br>
  • `man`
    Display how a command works example: man pwd <br>
  • `ls` 
    List files and directories in the current location <br>
  • `ls -l` 
    Show detailed information such as permissions, owner and size <br>
  • `ls -a` 
    Includes hidden files(files starting with ".") <br>
  • `cd` 
    Change the current directory (Change Directory) <br>
  • `cd ..` 
    Moves to the parent directory <br>
  • `cd /path/to/directory` 
    Change directly to the specified adsolute path <br>
## Security relevance
  • Hidden files may contains sensitive data(e.g. `.ssh`, `.env`) <br>
  • File permissions revealed by `ls -l` are useful for privilege escalation analysis <br>
  • Directory transversal is essential during reconnaissance <br>
  






