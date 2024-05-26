# Ubuntu 22.04 - Remove "Daemons using outdated libraries" Message

## Why you're getting the message in the first place

In Ubuntu 22.04 this is due to a change that was made to the needrestart command. This command is part of the apt upgrade process. By default it's set to interactive (i) mode which prompts the message. To remove the message you need to edit a variable in needrestart.conf.

## Remove the message

**Edit File**

`nano /etc/needrestart/needrestart.conf`
