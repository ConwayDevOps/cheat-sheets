# Fedora Management Cheat Sheet

Feroda is a Linux distribution based off of Red Hat. The commands in this Feroda cheat sheet will also work with Red Hat, Rocky Linux, CentOS, and other Red Hat-based distros.

**Upgrading Fedora**

| Command | Description |
| --- | --- |
| `sudo dnf upgrade --refresh` | Preform Fedora upgrade |
| `sudo dnf needs-restarting` | Check if system needs reboot after update/upgrade |

**Grant User Full Admin Privileges**

| Command | Description |
| --- | --- |
| `$ sudo usermod -aG wheel <username>` | Give user sudo privileges |

**Copy User Permissions to Group Permissions**

| Command | Description |
| --- | --- |
| `chmod -R g=u *` | User to group recursively |
| `find /patch/to/change/perms -name '*.txt' -exec chmod g=u {} +` | For a filespec |

I'm still learning Fedora, so as I discover more this cheat sheet will get updated.
