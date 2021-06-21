#tools

*< architectures
*< cross compiler
*< raspberry
*< ubuntu
*< ssh , ip
*< docker container
*< cmds of all these techs

# Rasperry PI Toolchains

*< Repository for Raspberry PI 
---------------------------
*< cross compiler using the new GCC8 and GCC9 for Raspbian Buster.
This supports all new Raspberry PIs (ARMv7), 
and the older ones, including: 
Zero, A, B, B+ (ARMv6) with newer GCCs.
----------------
Try this repository for other ARMv6 and ARMv7 devices: not done yet


## toolchain
We have to download toolchain from git hub release()recommended
wget https://github.com/garou93/Rasberry-toolchains-gen/releases/latest/download/raspi-toolchain.tar.gz
or,
build toolchain by yourself: build docker container (dockerfile), then copy toolchain from container to host



*>After that, you can test toolchain:
cross compile project (of course, you should get current libs and include files from rasp): rsync rootfs

Then copy exec to raspi.

Done!


