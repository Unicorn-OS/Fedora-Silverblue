# Guide:
test: works!
1. https://discussion.fedoraproject.org/t/intel-graphics-best-practices-and-settings-for-hardware-acceleration/69944
2. https://discussion.fedoraproject.org/t/how-do-you-set-kernel-module-parameters-in-silverblue/71820

```
echo "export LIBVA_DRIVER_NAME=iHD" >>.bashrc
sudo rpm-ostree kargs --append=i915.enable_guc=3
sudo rpm-ostree kargs --append=i915.enable_fbc=1
```
