# Another grave yard of samples around *Unity Game engine*

## My start environment

### Hardware and OS

```
~/github/micrub/unity-pg(develop ✔) cat /etc/issue
Ubuntu 16.04.5 LTS \n \l
~/github/micrub/unity-pg(develop ✔) uname -a
Linux micr-ThinkPad-X1 4.4.0-130-generic #156-Ubuntu SMP Thu Jun 14 08:53:28 UTC 2018 x86_64 x86_64 x86_64 GNU/Linux
~/github/micrub/unity-pg(develop ✔) lspci | grep -i vga
00:02.0 VGA compatible controller: Intel Corporation 2nd Generation Core Processor Family Integrated Graphics Controller (rev 09)
~/github/micrub/unity-pg(develop ✔) sudo lshw -C display
  *-display
       description: VGA compatible controller
       product: 2nd Generation Core Processor Family Integrated Graphics Controller
       vendor: Intel Corporation
       physical id: 2
       bus info: pci@0000:00:02.0
       version: 09
       width: 64 bits
       clock: 33MHz
       capabilities: msi pm vga_controller bus_master cap_list rom
       configuration: driver=i915 latency=0
       resources: irq:33 memory:f0000000-f03fffff memory:e0000000-efffffff ioport:5000(size=64)
```
### Unity Editor

#### Version (copied from content of Editor's window, that beeing triggered by *Help > About Unity*)

> Version 2017.2.0f3 (ee86734cf592) Personal
> Thu, 12 Oct 2017 13:32:44 GMT
> Branch: 2017.2/linux/editor

