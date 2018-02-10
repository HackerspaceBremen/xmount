# README

## xmount | Version 1.0 | bash script
&nbsp;

Description:

- 'xmount' extends the 'mount' command to automatically detect and mount multiple partitions in file images. If more than one partition / file system is detected, one can be selected and mounted in a loop device.

Dependencies:

- GNU parted => [Website](https://www.gnu.org/software/parted/)

Usage:

- 'xmount' can be used in the same way as the 'mount' command.

```code
Examples:
	xmount -o loop <image file> <mountdir>
	xmount --xinfo
	...
```
&nbsp;

***
**!!! Please send bug reports !!!**  
skynet-devel@mailbox.org