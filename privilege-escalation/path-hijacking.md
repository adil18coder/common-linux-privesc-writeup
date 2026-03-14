# PATH Variable Exploitation

The PATH variable determines where the system searches for executable files.

Command used to view PATH:

echo $PATH

If a privileged program calls another command without specifying its full path, it may be possible to hijack the execution.

Steps:

1. Create a malicious script with the same name as the called program
2. Place the script inside a writable directory
3. Modify the PATH variable so the system executes the malicious script first

When the privileged program runs, the attacker's script executes with elevated privileges.
