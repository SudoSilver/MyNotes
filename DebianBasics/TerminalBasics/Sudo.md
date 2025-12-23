The keyword *sudo* before a command is a better and more secure way to do a task with elevated privileges. Just add *sudo* before a command in the terminal and the command has [[Root Privilege|Root Privileges]].

The reason *sudo* is more secure than [[Root Privilege|Root Privileges]] is because it asks you for your users password before executing the action and at the very least is a mental warning that what you are doing could damage your system. It is more so a mental trick but one that can prevent many issues.

In case your current user does not have *sudo* privileges in Debian it is a simple fix. You just need to do the below to use [[Root Privilege|Root Privileges]] to add your user to the sudoers group.
```bash
su -
usermod -aG sudo username
exit
```
Remember to replace username with your actual username then log out and back in.
If you do not remember your username run
```bash
whoami
```
To then confirm the solution worked run
```bash
sudo whoami
```
This is the simplest way to fix the simple issue of not having *sudo* privileges. In case this doesn't work you can search in Stack Overflow or Chat GPT for another solution but this is the easiest most basic way to fix it.  

**IMPORTANTLY** sudo and [[Root Privilege|Root Privileges]] are the same thing it's more so you don't run a command as root by accident causing some issue.  

**NOTE**: This is more for technical accuracy but *sudo* grands [[Root Privilege|Root Privileges]] temporarily while logging in as root grands [[Root Privilege|Root Privileges]] to every action until you log off.   