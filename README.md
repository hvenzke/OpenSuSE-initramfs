OpenSuSE-mkinitramfs
====================

 This Mini project been created for xen-tools oss 13.1 hooks  24-setup-initramfs update


Files                             -      what purpuse

/sbin/mkdracutramfs               - create an initramfs with the dracut tool


/sbin/mkinitramfs                 - create an dynamic linked initramfs 
/usr/share/mkinitramfs/init.in    - initramfs init script file for the dynamic linked iniramfs

/sbin/mkBusyBoxinitramfs          - create busyBox based initramfs
/usr/share/mkinitramfs/BusyBoxramfs.init  - initramfs init script file for static linked iniramfs

-------------------



ORIGN SOURCES & Ideas : 
- http://www.linuxfromscratch.org/blfs/view/svn/postlfs/initramfs.html
- http://jootamam.net/howto-initramfs-image.htm
- https://access.redhat.com/site/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Deployment_Guide/sec-Verifying_the_Initial_RAM_Disk_Image.html
- http://oreilly.com/linux/excerpts/9780596100797/kernel-boot-command-line-parameter-reference.html
