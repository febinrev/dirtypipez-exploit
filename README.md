# CVE-2022-0847 DirtyPipe Exploit.

Credit: Max Kellermann <max.kellermann@ionos.com>

A new Linux vulnerability known as 'Dirty Pipe' allows local users to gain root privileges through publicly available exploits.

Today, security researcher Max Kellermann responsibly disclosed the 'Dirty Pipe' vulnerability and stated that it affects Linux Kernel 5.8 and later versions, even on Android devices.

The vulnerability is tracked as CVE-2022-0847 and allows a non-privileged user to inject and overwrite data in read-only files, including SUID processes that run as root.

Kellerman discovered the bug after tracking down a bug that was corrupting web server access logs for one of his customers.
