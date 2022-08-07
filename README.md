# qemu-single-passthrough
Single GPU passthrough for Asus B550I Strix


Use hooks scripts to enable automatic gpu disconnect / reconnect

https://gitlab.com/risingprismtv/single-gpu-passthrough

## Observations
- Occasionally the guest fails to boot which seems to coencide with the host sleeping/waking, GPU doesn't get detached properly. This requires a host reboot which is a dealbreaker for me.
- Network tx/rx reporting in windows is incorrect
