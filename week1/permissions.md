# Permissions (Week 1)

## Key commands
- `ls -l` : view permissions
- `chmod` : change permissions
- `chown` : change owner
- `chgrp` : change group
- `umask` : default permissions mask

## Notes
- r = read, w = write, x = execute
- Common patterns:
  - 644 = rw-r--r--
  - 755 = rwxr-xr-x

## Mini lab
1. Create a folder and file
2. Change file permissions to 600
3. Verify with `ls -l`
4. Explain what changed and why
