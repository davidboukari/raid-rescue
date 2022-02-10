# raid-rescue

```
mdadm --examine --scan >> /etc/mdadm.conf

cat /etc/mdadm.conf
ARRAY /dev/md/md2  metadata=1.2 UUID=xxxxxx name=md2
ARRAY /dev/md/md4  metadata=1.2 UUID=xxxxxx name=md4


mount /dev/md126 /mnt
vgscan
pvscan
mount /dev/vg/lvvar /mnt/var/
mount /dev/vg/lvhome /mnt/home

```
