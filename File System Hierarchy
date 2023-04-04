
# root Directory

`/tmp` for creating a file temporarily

```bash
mkdir directroy_Name
```

## long list

```bash
ls -l
```

## `Output`

```

dr-xr-xr-x.   2 root root    6 Aug 10  2021 afs
lrwxrwxrwx.   1 root root    7 Aug 10  2021 bin -> usr/bin
dr-xr-xr-x.   5 root root 4096 Apr  4 23:13 boot
drwxr-xr-x.  20 root root 3440 Apr  4 23:56 dev
drwxr-xr-x. 133 root root 8192 Apr  4 23:56 etc
drwxr-xr-x.   3 root root   31 Apr  4 23:11 home
lrwxrwxrwx.   1 root root    7 Aug 10  2021 lib -> usr/lib
lrwxrwxrwx.   1 root root    9 Aug 10  2021 lib64 -> usr/lib64
drwxr-xr-x.   2 root root    6 Aug 10  2021 media
drwxr-xr-x.   3 root root   18 Apr  4 23:08 mnt
drwxr-xr-x.   2 root root    6 Aug 10  2021 opt
dr-xr-xr-x. 358 root root    0 Apr  4 23:56 proc
dr-xr-x---.   3 root root  168 Apr  4 23:25 root
drwxr-xr-x.  45 root root 1160 Apr  4 23:56 run
lrwxrwxrwx.   1 root root    8 Aug 10  2021 sbin -> usr/sbin
drwxr-xr-x.   2 root root    6 Aug 10  2021 srv
dr-xr-xr-x.  13 root root    0 Apr  4 23:56 sys
drwxrwxrwt.  19 root root 4096 Apr  5 00:01 tmp
drwxr-xr-x.  12 root root  144 Apr  4 23:06 usr
drwxr-xr-x.  20 root root 4096 Apr  4 23:13 var
```

>[!Info]
>Here [->] is used as shortcut from the / directory.

_______

### /bin

This contains the binary files through which we could execute command.

### /dev

This contains files releated to hardware.

```bash
[root@localhost /]# ls /dev

autofs           input         random    tty17  tty4   tty62    vcsa2
block            kmsg          rfkill    tty18  tty40  tty63    vcsa3
bsg              log           rhel      tty19  tty41  tty7     vcsa4
bus              loop-control  rtc       tty2   tty42  tty8     vcsa5
cdrom            lp0           rtc0      tty20  tty43  tty9     vcsa6
char             lp1           sg0       tty21  tty44  ttyS0    vcsu
console          lp2           sg1       tty22  tty45  ttyS1    vcsu1
core             lp3           shm       tty23  tty46  ttyS2    vcsu2
cpu              mapper        snapshot  tty24  tty47  ttyS3    vcsu3
cpu_dma_latency  mcelog        snd       tty25  tty48  udmabuf  vcsu4
disk             mem           sr0       tty26  tty49  uhid     vcsu5
dm-0             midi          sr1       tty27  tty5   uinput   vcsu6
dm-1             mqueue        stderr    tty28  tty50  urandom  vfio
dma_heap         net           stdin     tty29  tty51  usbmon0  vga_arbiter
dmmidi           ng0n1         stdout    tty3   tty52  usbmon1  vhci
dri              null          tty       tty30  tty53  usbmon2  vhost-net
fb0              nvme0         tty0      tty31  tty54  vcs      vhost-vsock
fd               nvme0n1       tty1      tty32  tty55  vcs1     vmci
full             nvme0n1p1     tty10     tty33  tty56  vcs2     vsock
fuse             nvme0n1p2     tty11     tty34  tty57  vcs3     zero
hidraw0          nvram         tty12     tty35  tty58  vcs4
hpet             port          tty13     tty36  tty59  vcs5
hugepages        ppp           tty14     tty37  tty6   vcs6
hwrng            ptmx          tty15     tty38  tty60  vcsa
initctl          pts           tty16     tty39  tty61  vcsa1

```

### /home

Local user Directory.

### /lib64

Library files used for 64 bit system are stored in /lib64 directory.

### /mnt 

This is an empty directory but it is actually used to share files . Mount any image.

```bash
[root@localhost /]# ls /mnt

hgfs
```

### /proc

Files releated to processes. These directory directly interact with the kernel.


### /run

Any removeable storage are mounted to this directory.

``` bash
[root@localhost /]# ls /run

alsactl.pid   cron.reboot      irqbalance      ostree          sudo
atd.pid       cryptsetup       lock            plymouth        systemd
auditd.pid    cups             log             podman          tmpfiles.d
avahi-daemon  dbus             lsm             rhsm            tpm2-tss
chrony        dmeventd-client  lvm             rsyslogd.pid    tuned
chrony-dhcp   dmeventd-server  mdadm           samba           udev
cockpit       faillock         media           sepermit        udisks2
console       firewalld        motd            setrans         user
credentials   gdm              motd.d          setroubleshoot  utmp
criu          initctl          mount           spice-vdagentd  vmblock-fuse
crond.pid     initramfs        NetworkManager  sshd.pid        vmware

```

### /srv 

It is a serving directory. Temp data.

### /tmp

Access by everyone. But it can delete only own file because of sticky bit. Earse after system reboot.

```bash
[root@localhost /]# ls tmp

systemd-private-7f8487c8a06a4c08a5a01d221139b3a4-chronyd.service-l7Yepg
systemd-private-7f8487c8a06a4c08a5a01d221139b3a4-colord.service-T63cdy
systemd-private-7f8487c8a06a4c08a5a01d221139b3a4-dbus-broker.service-V8ziHO
systemd-private-7f8487c8a06a4c08a5a01d221139b3a4-fwupd.service-phcwq8
systemd-private-7f8487c8a06a4c08a5a01d221139b3a4-ModemManager.service-Z7ugnz
systemd-private-7f8487c8a06a4c08a5a01d221139b3a4-power-profiles-daemon.service-uGVYNO
systemd-private-7f8487c8a06a4c08a5a01d221139b3a4-rtkit-daemon.service-owoYGc
systemd-private-7f8487c8a06a4c08a5a01d221139b3a4-switcheroo-control.service-n32RMX
systemd-private-7f8487c8a06a4c08a5a01d221139b3a4-systemd-logind.service-afl49a
systemd-private-7f8487c8a06a4c08a5a01d221139b3a4-upower.service-9P69bj
tracker-extract-3-files.1000
vmware-root_914-2689209517
vmware-root_926-2731217702
```

### /var

It contains logs releated to different domains.

```bash
[root@localhost /]# ls /var

account  cache  db     ftp    kerberos  local  log   nis  preserve  spool  yp
adm      crash  empty  games  lib       lock   mail  opt  run       tmp
```
### /boot

It contains  booting files and kernel images. Both for rescue mode and normal mode.

```bash
[root@localhost /]# ls /boot

config-5.14.0-162.6.1.el9_1.x86_64
efi
grub2
initramfs-0-rescue-aa764282da294d7583bb3d0ac646d5c8.img
initramfs-5.14.0-162.6.1.el9_1.x86_64.img
initramfs-5.14.0-162.6.1.el9_1.x86_64kdump.img
loader
symvers-5.14.0-162.6.1.el9_1.x86_64.gz
System.map-5.14.0-162.6.1.el9_1.x86_64
vmlinuz-0-rescue-aa764282da294d7583bb3d0ac646d5c8
vmlinuz-5.14.0-162.6.1.el9_1.x86_64

```

#### grub2

```bash
device.map  fonts  grub.cfg  grubenv  i386-pc  locale
```

### /etc 

It contains system's configuration files. Files or setting related to configuration.

### /media

Mount through media.

### /opt 

Used as optional directory.

### /root

Home directory of root user.

### /sbin

Super User binary or System user binary. 

```bash

```

```bash
[root@localhost /]# fdisk -l

Disk /dev/nvme0n1: 25 GiB, 26843545600 bytes, 52428800 sectors
Disk model: VMware Virtual NVMe Disk
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes
Disklabel type: dos
Disk identifier: 0x7dd69f6c

Device         Boot   Start      End  Sectors Size Id Type
/dev/nvme0n1p1 *       2048  2099199  2097152   1G 83 Linux
/dev/nvme0n1p2      2099200 52428799 50329600  24G 8e Linux LVM


Disk /dev/mapper/rhel-root: 21.5 GiB, 23081254912 bytes, 45080576 sectors
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes


Disk /dev/mapper/rhel-swap: 2.5 GiB, 2684354560 bytes, 5242880 sectors
Units: sectors of 1 * 512 = 512 bytes
Sector size (logical/physical): 512 bytes / 512 bytes
I/O size (minimum/optimal): 512 bytes / 512 bytes

```

### /sys

Additional file releated to kernel and system.

```bash
[root@localhost /]# ls /sys

block  class  devices   fs          kernel  power
bus    dev    firmware  hypervisor  module

```

### /usr

```bash

bin  games  include  lib  lib64  libexec  local  sbin  share  src  tmp

```
