# Yggdrasil-1994
Yggdrasil Plug and Play Linux Fall 1994

Read more at

  - Reddit (English): https://www.reddit.com/r/linux/comments/cbfr32/yggdrassil_plug_and_play_linux_fall_1994/
  - linux-user.gr (Greek): https://linux-user.gr/t/yggdrassil-plug-and-play-linux-fall-1994/798
  - Russian YouTube channel with some videos about Yggdrasil: https://youtube.com/@gavrilovegor519

**QEMU and VirtualBox is not working! Use a 86Box for boot this distro!**

## Get the ISO

Get the ISO from https://drive.google.com/file/d/12EjeCiAxFqvTKL4x5H9UbY7yvnIzrKj7/view

## Installing on 86Box (guide for any Yggdrasil releases and betas)

For install to 86Box, use this parameters:

  - Machine - any machine from 386 line **(but better using 486DX/486DX2 machines)**. If you want install Yggdrasil Beta (1993), **must not use Socket 3 and any Pentium machines**.
  - Storage controllers - IDE for HDD, Buslogic/Adaptec SCSI controller for CD-ROM. Or setup SCSI BIOS memory zone in device parameters on 86Box for using SCSI for bootable HDD. IDE CD-ROMs may using only on **Fall 1995** release.
  - Mouse - Microsoft serial mouse is recommended on 86Box.
  - RAM - 8+ MB RAM is recommended for any Yggdrasil releases.
  - HDD - 512+ MB is recommended for any Yggdrasil releases.
  - Video: ET4000AX video card is recommended for any Yggdrasil releases.
  - Network: NE2000 ISA is recommended for any Yggdrasil releases. Better using SLiRP host backend for Internet access from Yggdrasil.

You must setup HDD geometry in BIOS on pre-Pentium machines because early BIOSes not support autodetect of HDDs on POST stage (but BIOS Setup autodetect is supported in 486's BIOS). Also, you must check format of FDD and change to installed format.
