# macOS EFI for Lenovo Thinkpad L380
You really had to do it to em.

To disable `SIP` go into the recovery mode terminal and type these commands:
```
csrutil disable 
system reboot
```

To access `/System/Library/Extensions/` use this command which works until restart:
```sudo mount -uw /```
