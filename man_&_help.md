
# LSBLK

- It lists the information about all available or the specified block devices.
- The command reads the sysfs fielsystem and udev dv to gather information.
-  If the udev db is not available or lsblk is compiled without udev support, then it tries to read LABELs, UUIDs and filesystem types from the block device. In this case root permissions are necessary.

***[ Bascially shows the disk information in your system. ]***

```bash
[root@localhost ~]# lsblk
NAME    MAJ:MIN RM  SIZE RO TYPE MOUNTPOINTS
sr0      11:0    1 1024M  0 rom
sr1      11:1    1  8.4G  0 rom  /run/media/infosec-pradyumna/RHEL-9-1-0-BaseOS-                   x86_64
nvme0n1 259:0    0   25G  0 disk
├─nvme0n1p1
│       259:1    0    1G  0 part /boot
└─nvme0n1p2
        259:2    0   24G  0 part
  ├─rhel-root
  │     253:0    0 21.5G  0 lvm  /
  └─rhel-swap
        253:1    0  2.5G  0 lvm  [SWAP]
```


>[!Note]
> Note that lsblk might be executed in time when udev does not have all information about recently added or modified devices yet. In this case it is recommended to use udevadm settle before lsblk to synchronize with udev.

# rsyslog

It is a config file of log file of rsys daemon. 

```bash
[root@localhost ~]# whatis rsyslog.conf
rsyslog.conf (5)     - rsyslogd(8) configuration file
```

```bash
 To  forward  messages  to  another  host via UDP, prepend the hostname with the at sign ("@").  To forward it via plain tcp, prepend two at signs ("@@"). To forward via RELP, prepend the string
       ":omrelp:" in front of the hostname.

       Example:
              *.* @192.168.0.1

In the example above, messages are forwarded via UDP to the machine 192.168.0.1, the destination port defaults to 514. Due to the nature of UDP, you will probably lose some messages in transit.
If you expect high traffic volume, you can expect to lose a quite noticeable number of messages (the higher the traffic, the more likely and severe is message loss).

Sockets for forwarded messages can be bound to a specific device using the "device" option for the omfwd module.

       Example:
              action(type="omfwd" Target="192.168.0.1" Device="eth0" Port=514 Protocol="udp")

In the example above, messages are forwarded via UDP to the machine 192.168.0.1 at port 514 over the device eth0. TCP can be used by setting Protocol to "tcp" in the above example.

or Linux with VRF support, the device option is used to specify the VRF to send messages.

If you would like to prevent message loss, use RELP:
              *.* :omrelp:192.168.0.1:2514

Note that a port number was given as there is no standard port for relp.

```


# ssh

sshd is the daemon service of ssh.

# Description of command

If error occure use the command mandb. The manual database entires will be fix and index will be created.

```bash
whatis <cmd>
```

# Manual of command

Not only it finds the manual but also gives us the binary file.

```bash
[root@localhost ~]# whereis route
route: /usr/sbin/route /usr/share/man/man8/route.8.gz
```

# man section view

``` 
man 5 passwd
```
Shows the fifth entry of the manual.

# man

An interface to system reference manual.
### Examples: 

```
EXAMPLES
       man ls
           Display the manual page for the item (program) ls.

       man man.7
           Display the manual page for  macro  package  man  from  section  7.
           (This is an alternative spelling of "man 7 man".)

       man 'man(7)'
           Display  the  manual  page  for  macro  package man from section 7.
           (This is another alternative spelling of "man 7 man".   It  may  be
           more convenient when copying and pasting cross-references to manual
           pages.  Note that the parentheses must normally be quoted  to  pro‐
           tect them from the shell.)

       man -a intro
           Display,  in  succession,  all  of the available intro manual pages
           contained within the manual.  It is possible to quit  between  suc‐
           cessive displays or skip any of them.

       man -t bash | lpr -Pps
           Format  the  manual  page  for bash into the default troff or groff
           format and pipe it to the printer named ps.  The default output for
           groff  is usually PostScript.  man --help should advise as to which
           processor is bound to the -t option.

       man -l -Tdvi ./foo.1x.gz > ./foo.1x.dvi
           This command will decompress and format  the  nroff  source  manual
           page  ./foo.1x.gz  into a device independent (dvi) file.  The redi‐
           rection is necessary as the -T flag causes output to be directed to
           stdout  with  no  pager.  The output could be viewed with a program
           such as xdvi or further processed into PostScript using  a  program
           such as dvips.

       man -k printf
           Search the short descriptions and manual page names for the keyword
           printf as regular expression.  Print out any  matches.   Equivalent
           to apropos printf.

       man -f smail
           Lookup the manual pages referenced by smail and print out the short
           descriptions of any found.  Equivalent to whatis smail.

```


# Help

```bash
<cmd> --help
```

```bash
[root@localhost ~]# whatis help
help (1)             - bash built-in commands, see bash(1)

[root@localhost ~]# whereis help
help: /usr/share/help /usr/share/man/man1/help.1.gz
```
