#SEaT (Share Enumeration and ACL Testing)

This a command-line tool to test misconfigurated ACL's. It will try to find write privilenges using the current user credentials.
Can also be used with "runas" or "psexec" to impersonate another user.

Usage:
======
SEaT.exe *
Enumerates all computers and shares even hidden or administrative.

SEaT.exe server[XYZ]
Enumerates all matching computers with the given string.

SEaT.exe \\server\share[\folder] [/R]
List and tests the share, can use the /R switch to perform recursive tests.

Download: https://github.com/d4rksh3ll-PT/SEaT/releases/latest
