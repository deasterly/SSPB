# Server Support Linux Workshop

## [Day 1 Agenda](./Day_1/)

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Class Introduction | Welcome to this Workshop! | Getting Started | [What is this workshop? ](./WSINTRO.md) |
| " | " | " | [Lab Environment Information](./WSLABINFO.md) |
| " | " | " | [Additional Resources](./WSRESROURCES.md) |
| Using RHEL | BASH CLI Shell | Logging in to the CLI shell | [Local Terminals](./Day_1/topic_1.md) |
| " | " | " | [Remote SSH Terminals](./Day_1/topic_2.md) |
| " | " | Understanding commands and their syntax | [Shell Built-ins](Day_1/topic_3.md) |
| " | " | " | [External Commands and Scripts](./Day_1/topic_4.md) |
| " | " | " | [Using the `$PATH`, `whereis` and `which` ](./Day_1/topic_5.md)  |
| " | " | Understanding BASH metacharacters | [Special Characters](./Day_1/topic_6.md) |
| " | " | " | [Quoting and Escaping](./Day_1/topic_7.md) |
| " | " | " | [Control Operators](./Day_1/topic_8.md) |
| " | " | Using timesaving BASH features | [Tilde Expansion](./Day_1/topic_9.md) |
| " | " | " | [ **`<TAB>`** Autocompletion](./Day_1/topic_10.md) |
| " | " | " | [Brace Expansion](./Day_1/topic_11.md) |
| " | " | " | [Keyboard Shortcuts](./Day_1/topic_12.md) |
| " | " | Documentation | [Built-in Help](./Day_1/topic_13.md) |
| " | " | " | [Understanding  `man` Pages](./Day_1/topic_14.md) |
| " | " | " | [Using GNU Info pages](./Day_1/topic_15.md) |
| " | Managing Files and Directories | Creating, copying, moving/renaming, and removing | [GNU Coreutils](./Day_1/topic_16.md) |
| " | " | " | [Filename Expansion (a.k.a. "globbing")](./Day_1/topic_17.md) |
| " | " | Archiving files an directories | [GNU `tar` ](./Day_1/topic_18.md) |
| " | " | Transferring files over a network | [Using `sftp` and `scp` ](./Day_1/topic_19.md) |
| " | Working with Text | Reading text files | [Using `cat`, `less`, `tail`, `head`, `wc` et.al](./Day_1/topic_20.md) |
| " | " | Editing text using `vim` | [VIM Modes](./Day_1/topic_21.md) |
| " | " | " | [Using `vimtutor` ](./Day_1/topic_22.md) |
| " | " | " | [Timesaving Tips and Tricks](./Day_1/topic_23.md) |
| " | " | Searching for text using `grep` | [RegEx Fundamentals](./Day_1/topic_24.md) |
| " | " | " | [RegEx Documentation and Examples](./Day_1/topic_25.md) |
||||

*****

## [Day 2 Agenda](./Day_2/)

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Linux System Administration | Users and Groups | Creating and managing users and groups | [Using `groupadd`, `groupmod`, and `groupdel` ](./Day_2/topic_1.md) |
| " | " | " | [Using `useradd`, `usermod`, and `userdel` ](./Day_2/topic_2.md) |
| " | " | Setting user passwords | [Using `passwd` ](./Day_2/topic_3.md) |
| " | " | " | [Using `chage` ](./Day_2/topic_4.md) |
| " | " | Elevating user privileges | [Using `su` ](./Day_2/topic_5.md) |
| " | " | " | [Using `sudo` ](./Day_2/topic_6.md) |
| " | Software Package Management | Adding and removing software | [Using `yum` ](./Day_2/topic_7.md) |
| " | " | " | [Using `rpm` to query packages](./Day_2/topic_8.md) |
| " | " | Adding installation repositories | [Understanding */etc/yum.repos.d/*.repo* files](./Day_2/topic_9.md) |
| " | File Ownership and Permissions | Identifying and interpreting ownership and permissions | [Permission Basics](./Day_2/topic_10.md) |
| " | " | " | [Understanding `stat` and `ls -l` output](./Day_2/topic_11.md) |
| " | " | Modifying ownership | [Using `chgrp` and `chown` ](./Day_2/topic_12.md) |
| " | " | Modifying permissions | [Using `chmod` ](./Day_2/topic_13.md) |
| " | " | " | [Special Permissions](./Day_2/topic_14.md) |
| " | Searching Linux Logs | Understanding `rsyslogd` rules | [Common Logs](./Day_2/topic_15.md) |
| " | " | " | [Adding Custom Logs](./Day_2/topic_16.md) |
| " | " | Understanding log rotation | [Using `logrotate` and */etc/logrotate.conf* ](./Day_2/topic_17.md) |
| " | " | Searching the ***systemd*** journal using `journalctl` | [Using `journalctl` ](./Day_2/topic_18.md) |
| " | " | " | [Persistent Journal Logging](./Day_2/topic_19.md) |
||||


## [Day 3 Agenda](./Day_3/)

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Linux System Administration | Collecting Troubleshooting Information | The `cockpit` Web Console | [Connecting to Cockpit](./Day_3/topic_1.md) |
| " | " | " | [Using Cockpit](./Day_3/topic_2.md) |
| " | " | Using `sosreport` | [Collection and Extraction](./Day_3/topic_3.md) |
| " | " | " | [Finding Information](./Day_3/topic_4.md) |
| Running Linux on PowerEdge | Supported Versions | Indentifying supported Linux versions | [Finding OS version and release info](./Day_3/topic_5.md) |
| " | " | " | [Locating support matrices](./Day_3/topic_6.md) |
| " | Identifying storage | Identifying disks and partitions | [Disks and Partitions](./Day_3/topic_7.md) |
| " | " | Identifying LVM storage | [PVs, VGs, and LVs](./Day_3/topic_8.md) |
| " | " | Identifying filesystems and mountpoints | [Identifying Filesystems](./Day_3/topic_9.md) |
| " | " | " | [Identifying Mountpoints](./Day_3/topic_10.md) |
| " | Configuring storage | Creating partitions | [Using `fdisk`, `gdisk`, and `parted` ](./Day_3/topic_11.md) |
| " | " | Creating XFS and EXT4 Filesystems | [Using `mkfs`, `mkfs.xfs`, and `mkfs.ext4` ](./Day_3/topic_12.md) |
| " | " | Mounting filesystems | [Using `mount` and `umount` ](./Day_3/topic_13.md) |
| " | " | " | [Configuring */etc/fstab* ](./Day_3/topic_14.md) |
| " | " | Creating and activating SWAP filesystems | [Using `swapon` and `swapoff` ](./Day_3/topic_15.md) |
| " | " | " | [Using `mkswap` and configuring */etc/fstab* ](./Day_3/topic_16.md) |
| " | " | Configuring LVM | [LVM Basics](./Day_3/topic_17.md) |
| " | " | " | [Using `pvcreate`, `vgcreate`, and `lvcreate` ](./Day_3/topic_18.md) |
| " | " | " | [Using `vgexted` and `lvextend` ](./Day_3/topic_19.md) |
||||


## [Day 4 Agenda](./Day_4/)

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Running Linux on PowerEdge | Identifying Networks | Identifying NICs | [Using `ip link` and `ethtool` ](./Day_4/topic_1.md) |
| " | " | " | [Using `lsmod` and `modinfo` ](./Day_4/topic_2.md) |
| " | " | Finding IP address, routing, and DNS info | [Using `ip addr` and `ip route` ](./Day_4/topic_3.md) |
| " | " | " | [Using `dig` to query DNS](./Day_4/topic_4.md) |
| " | " | " | [Using `nmcli` to find information](./Day_4/topic_5.md) |
| " | Configuring Ethernet Networks | Understanding the `NetworkManager` service | [Devices and Connections](./Day_4/topic_6.md) |
| " | " | " | [Using 'nmtui` and `nmcli` ](./Day_4/topic_7.md) |
| " | Identifying additional hardware | Finding RAM information | [Using `free` and */proc/meminfo* ](./Day_4/topic_8.md) |
| " | " | " | [Using `dmidecode` to identify RAM](./Day_4/topic_9.md) |
| " | " | Finding PCI device information | [Using `lspci` and `lshw` ](./Day_4/topic_10.md) |
| " | " | Finding USB device information | [Using `lsusb` and `lshw` ](./Day_4/topic_11.md) |
| " | " | Finding driver information | [Kernel module basics](./Day_4/topic_12.md) |
| " | " | " | [Using `lsmod`, `modprobe`, and `modinfo` ](./Day_4/topic_13.md) |
| " | Using Dell Software on Linux | Booting to the SLI | [Launching OMSA](./Day_4/topic_14.md) |
| " | " | " | [Clearing Single Bit Errors from Event Logs](./Day_4/topic_15.md)  |
| " | " | " | [Running Intel CPU Diagnostics](./Day_4/topic_16.md) |
| " | " | Installing the DSU repos on RHEL8 | [Installing and Using `dsu` ](./Day_4/topic_17.md) |
| " | " | Installing OMSA on RHEL8 | [Using the DSU repos](./Day_4/topic_18.md) |
||||

## [Day 5 Agenda](./Day_5/)

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Running Linux on PowerEdge | Ubuntu Server | Idenfitying Supported Versions | [Ubuntu "LTS" versions](./Day_5/topic_1.md) |
| " | " | " | [What "Certified," "Validated," and "Fully Supported" mean](./Day_5/topic_2.md) |
| " | " | Important Ubuntu Differences | [Logging differences from RHEL](./Day_5/topic_3.md) |
| " | " | " | [Configuration differences from RHEL](./Day_5/topic_4.md) |
| " | Deploy and configure a server activity | Deployment | [Resetting the hardware configuration](./Day_5/topic_5.md) |
| " | " | " | [Installing RHEL8 manually](./Day_5/topic_6.md) |
| " | " | Configuration | [Setting up users and groups](./Day_5/topic_7.md) |
| " | " | " | [Configuring the network](./Day_5/topic_8.md) |
| " | " | " | [Installing DSU and OMSA](./Day_5/topic_9.md) |
| " | " | Validation | [Collecting a `sosreport` ](./Day_5/topic_10.md) |
| " | " | " | [Verifying system information using `sosreport` ](./Day_5/topic_11.md) |
||||
