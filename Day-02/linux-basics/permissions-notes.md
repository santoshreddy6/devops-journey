## Linux Permissions (Day 02)

Linux permissions control who can read, write, or execute a file.

### Permission Types
- r → Read (4)
- w → Write (2)
- x → Execute (1)

### Permission Levels
- Owner
- Group
- Others

### Common Permission Values
- 755 → rwxr-xr-x
- 700 → rwx------
- 600 → rw-------

### Notes
- Execute permission is required to run scripts
- Directories need execute permission to be accessed
- SSH private keys must have 600 permission
