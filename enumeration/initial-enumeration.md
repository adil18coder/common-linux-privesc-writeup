# Initial Enumeration

After connecting to the target machine using SSH, enumeration was performed to gather information about the system.

Example connection:

ssh user3@TARGET_IP

The following commands were used during enumeration:

hostname

cat /etc/passwd

cat /etc/shells

These commands revealed useful information about users, system configuration and available shells.

Enumeration results showed:

- multiple users on the system
- available login shells
- system hostname
