# Understanding the Linux File System

When I first started learning Linux, one thing that confused me was the file system structure.
Unlike Windows, which has different drives like `C:` or `D:`, Linux has just **one single root directory (`/`)** — and everything starts from there.
Whether it’s files, folders, or even hardware devices, in Linux **everything is treated as a file**.


## The Root Directory and Its Structure

Below is a simple explanation of the main directories you’ll find in every Linux system.
Understanding these helps a lot when you start working with servers or debugging issues.

 Directory | What It’s Used For 
 
 `/`    | The **root directory** — everything in Linux begins here. 
 `/home`| Each user gets their own folder here. For example, my files go in `/home/<username>`. 
 `/etc` | Stores system configuration files (like network settings, users, and startup scripts). 
 `/bin` | Contains basic Linux commands like `ls`, `cp`, `mv`, etc. 
 `/usr` | Stands for "user programs" — installed applications and libraries live here. 
 `/var` | Stores variable data like logs and cache files.
 `/tmp` | Temporary files that get deleted after reboot. 
 `/dev` | Represents hardware devices — for example, `/dev/sda1` is your hard drive. 
 `/proc`| A virtual directory that provides details about running processes and system information. 
 `/lib` | Shared system libraries that help programs run. 
 `/boot`| Files needed to boot the system — like the Linux kernel. 



## Commands to Explore the File System

Here are a few simple commands that I personally found useful while learning:

```bash
pwd               # Shows the current directory path
ls                # Lists files and directories
ls -l             # Lists files with detailed info (permissions, size, date, etc.)
cd /path          # Moves into a specific directory
cd ..             # Moves one step back
tree              # Displays the folder structure as a tree (install it first)
du -sh *          # Shows the size of each folder in the current directory
