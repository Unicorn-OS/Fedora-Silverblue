relation: https://docs.fedoraproject.org/en-US/quick-docs/virtualization-getting-started/

# install:
Current: https://discussion.fedoraproject.org/t/overlaying-libvirt-on-silverblue-kinoite-sericea-onyx-and-coreos/86312

# simplest:
https://discussion.fedoraproject.org/t/best-way-to-install-libvirt-and-virt-manager-on-silverblue/30700

```
rpm-ostree install virt-install virt-manager virt-viewer libvirt

# reboot
systemctl enable libvirtd
systemctl start libvirtd
# reboot again
# Works!
```
