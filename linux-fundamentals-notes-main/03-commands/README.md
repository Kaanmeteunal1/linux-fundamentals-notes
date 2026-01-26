https://explainshell.com/ command help site
# 🛠️ Essential Linux Commands

Here is a list of basic commands to get information about the system, network, and hardware.

| Command | Description |
| :--- | :--- |
| **`ls`** | Lists **File and Folders** (-i for inode, -a,-l,-t modification time). |
| **`man <tool>`** | Opens the **manual** page for a specific tool. (e.g., `man ls`). |
| **`<command> --help`** | Displays a short **help message** and usage options for the command. (Also `-h`). |
| **`apropos <keyword>`** | Searches the manual page names and descriptions for a specific **keyword**. |
| **`whoami`** | Displays the current **username**. |
| **`id`** | Returns the user identity (UID, GID, and groups). |
| **`hostname`** | Sets or prints the name of the current **host system**. |
| **`uname -a`** | Prints basic information about the **OS kernel** and system hardware. |
| **`pwd`** | **Print Working Directory.** Shows the full path of the folder you are in. |
| **`ifconfig`** | (Old) Used to view or configure **network interfaces** (IP address, netmask). |
| **`ip`** | (New) Shows or manipulates routing, network devices, and interfaces. Replaces `ifconfig`. |
| **`netstat`** | Shows **network status** (open ports, connections). |
| **`ss`** | Another utility to investigate **sockets**. (Faster/modern replacement for `netstat`). |
| **`ps`** | Shows **process status** (currently running programs). |
| **`who`** | Displays who is currently **logged in** to the system. |
| **`env`** | Prints the current **environment variables**. |
| **`lsblk`** | Lists **block devices** (Storage devices like Hard Drives, SSDs, USBs). |
| **`lsusb`** | Lists connected **USB devices**. |
| **`lsof`** | Lists **opened files** (files currently being used by processes). |
| **`lspci`** | Lists **PCI devices** (Graphics cards, Network adapters, etc.). |

---
*Tip: Use `man <command>` to learn more details about any of these tools!*
