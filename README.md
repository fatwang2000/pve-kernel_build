# Actions-pve-kernel

Linux Kernel for Proxmox projects

根据koolshare 上 emile239 提出解决Proxmox VE 各版本下J3455主板直通iommu分组问题的方法编译Proxmox Kernel，该内核也适用于其它iommu不能分组的主板。

每天自动检查 git://git.proxmox.com/git/pve-kernel.git master分支代码中的内核版本是否有更新，发现新版本内核时自动拉取分支代码，并自动修改patch文件，让内核使用特制的ACS_override补丁。

# Thanks 

参考了该项目的用docker环境进行编译的思路 **roforest/Actions-pve-kernel**: https://github.com/roforest/Actions-pve-kernel.git
