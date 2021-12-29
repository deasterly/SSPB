# RTLV Workshop

## Day 2 Agenda

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Linux System Administration | Users and Groups | Creating and managing users and groups | Using `groupadd`, `groupmod`, and `groupdel` |
| " | " | " | Using `useradd`, `usermod`, and `userdel` |
| " | " | Setting user passwords | Using `passwd` |
| " | " | " | Using `chage` |
| " | " | Elevating user privileges | Using `su` |
| " | " | " | Using `sudo` |
| " | Software Package Management | Adding and removing software | Using `yum` |
| " | " | " | Using `rpm` to query packages |
| " | " | Adding installation repositories | Understanding */etc/yum.repos.d/*.repo* files |
| " | File Ownership and Permissions | Identifying and interpreting ownership and permissions | Permission Basics |
| " | " | " | Understanding `stat` and `ls -l` output |
| " | " | Modifying ownership | Using `chgrp` and `chown` |
| " | " | Modifying permissions | Using `chmod` |
| " | " | " | Special Permissions |
| " | Searching Linux Logs | Understanding `rsyslogd` rules | Common Logs |
| " | " | " | Adding Custom Logs |
| " | " | Understanding log rotation | Using `logrotate` and */etc/logrotate.conf* |
| " | " | Searching the ***systemd*** journal using `journalctl` | Using `journalctl` |
| " | " | " | Persistent Journal Logging |
||||

## Day 3 Agenda

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Linux System Administration | Collecting Troubleshooting Information | The `cockpit` Web Console | Connecting to Cockpit |
| " | " | " | Using Cockpit |
| " | " | Using `sosreport` | Collection and Extraction |
| " | " | " | Finding Information |
| Running Linux on PowerEdge | Supported Versions | Indentifying supported Linux versions | Finding OS version and release info |
| " | " | " | Locating support matrices |
| " | Identifying storage | Identifying disks and partitions | Disks and Partitions |
| " | " | Identifying LVM storage | PVs, VGs, and LVs |
| " | " | Identifying filesystems and mountpoints | Identifying Filesystems |
| " | " | " | Identifying Mountpoints |
| " | Configuring storage | Creating partitions | Using `fdisk`, `gdisk`, and `parted` |
| " | " | Creating XFS and EXT4 Filesystems | Using `mkfs`, `mkfs.xfs`, and `mkfs.ext4` |
| " | " | Mounting filesystems | Using `mount` and `umount` |
| " | " | " | Configuring */etc/fstab* |
| " | " | Creating and activating SWAP filesystems | Using `swapon` and `swapoff` |
| " | " | " | Using `mkswap` and configuring */etc/fstab* |
| " | " | Configuring LVM | LVM Basics |
| " | " | " | Using `pvcreate`, `vgcreate`, and `lvcreate`
| " | " | " | Using `vgexted` and `lvextend` |
||||

## Day 4 Agenda

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Running Linux on PowerEdge | Identifying Networks | Identifying NICs | Using `ip link` and `ethtool` |
| " | " | " | Using `lsmod` and `modinfo` |
| " | " | Finding IP address, routing, and DNS info | Using `ip addr` and `ip route` |
| " | " | " | Using `dig` to query DNS |
| " | " | " | Using `nmcli` to find information |
| " | Configuring Ethernet Networks | Understanding the `NetworkManager` service | Devices and Connections |
| " | " | " | Using 'nmtui` and `nmcli` |
| " | Identifying additional hardware | Finding RAM information | Using `free` and */proc/meminfo* |
| " | " | " | Using `dmidecode` to identify RAM |
| " | " | Finding PCI device information | Using `lspci` and `lshw` |
| " | " | Finding USB device information | Using `lsusb` and `lshw` |
| " | " | Finding driver information | Kernel module basics |
| " | " | " | Using `lsmod`, `modprobe`, and `modinfo` |
| " | Using Dell Software on Linux | Booting to the SLI | Launching OMSA |
| " | " | " | Clearing Single Bit Errors from Event Logs  |
| " | " | " | Running Intel CPU Diagnostics |
| " | " | Installing the DSU repos on RHEL8 | Installing and Using `dsu` |
| " | " | Installing OMSA on RHEL8 | Using the DSU repos |
||||

## Day 5 Agenda

| **Section** | **Module** | **Lesson** | **Topic** |
| :---------: | :--------: | :--------: | :-------- |
| Running Linux on PowerEdge | Ubuntu Server | Idenfitying Supported Versions | Ubuntu "LTS" versions |
| " | " | " | What "Certified," "Validated," and "Fully Supported" mean |
| " | " | Important Ubuntu Differences | Logging differences from RHEL |
| " | " | " | Configuration differences from RHEL |
| " | Deploy and configure a server activity | Deployment | Resetting the hardware configuration |
| " | " | " | Installing RHEL8 manually |
| " | " | Configuration | Setting up users and groups |
| " | " | " | Configuring the network |
| " | " | " | Installing DSU and OMSA |
| " | " | Validation | Collecting a `sosreport` |
| " | " | " | Verifying system information using `sosreport` |
||||
