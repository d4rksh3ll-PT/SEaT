#SEaT (Share Enumeration and Test)

This a command tool to test misconfigurated ACL's. It will try to find write privilenges using the current user credentials.
Can also be used with "runas" or "psexec" to impersonate another user.

Usage:
======
SEaT.exe *
Enumerates all computers and shares even hidden or administrative.

SEaT.exe serverXYZ
Enumerates all matching computers with the given string.

SEaT.exe \\\\server\\share[\\folder] [/R]
List and tests the share, can use the /R switch to perform recursive tests.