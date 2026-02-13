# Linux Fundamentals - Bash and Terminal 

This document covers basic Linux navigation commnads and heir relevance for system administration and security operations.

---

## Basic Navegation Commands

# Bash
`pwd`
`ls`
`ls -l`
`ls -a`
`cd`
`cd ..`
`cd /path/to/directory`

## Command descriptions
  • `pwd` 
    Display the current working directory
  • `man`
    Display how a command works example: man pwd
  • `ls` 
    List files and directories in the current location
  • `ls -l` 
    Show detailed information such as permissions, owner and size
  • `ls -a` 
    Includes hidden files(files starting with ".")
  • `cd` 
    Change the current directory (Change Directory)
  • `cd ..` 
    Moves to the parent directory
  • `cd /path/to/directory` 
    Change directly to the specified adsolute path
## Security relevance
  • Hidden files may contains sensitive data(e.g. `.ssh`, `.env`)
  • File permissions revealed by `ls -l` are useful for privilege escalation analysis
  • Directory transversal is essential during reconnaissance
  






