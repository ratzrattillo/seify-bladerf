# seify-bladerf

For debugging via Wireshark under Arch:
```bash
sudo modprobe usbmon && sudo setfacl -m u:jl:r /dev/usbmon*
```