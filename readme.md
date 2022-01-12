this is ks edition of [onekeydevdesk](../../../onekeydevdesk) with i350,e1000e module and gpt support

usage:

```bash <(wget -qO- --no-check-certificate https://github.com/minlearn/onekeydevdeskks/raw/master/instks.sh) -t onekeydevdesk```

after dd,then:

```/run/initramfs/usr/bin/growpart /dev/sda 3; resize2fs /dev/sda3``` (change to vda if needed)

access with:

```https://ip:8006,root,tdl```


