# How to install QEMU on Ubuntu 23.04

```bash
$ sudo apt install qemu-system-x86 virt-manager virtinst libvirt-clients bridge-utils libvirt-daemon-system
$ sudo systemctl enable --now libvirtd
$ sudo systemctl start libvirtd
$ sudo usermod -aG kvm $USER
$ sudo usermod -aG libvirt $USER
$ sudo virt-manager
```
