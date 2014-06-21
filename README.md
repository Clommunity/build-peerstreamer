build-peerstreamer
==================

Scripts to build peerstreamer


## Prepare
If you want build ARM version with debian wheezy, you need add repositories embedded from squeeze like this:

	# Embedded
	deb http://ftp.us.debian.org/debian/ squeeze main
	deb http://ftp.uk.debian.org/embedian/toolchains testing main
	deb http://ftp.us.emdebian.org/debian/ squeeze main
	deb http://security.debian.org/ squeeze/updates main
	deb http://www.emdebian.org/debian/ squeeze main

And install gcc cross-compiler:

	apt-get install gcc-4.4-arm-linux-gnueabi


## Build x86 versions:

	./buildps

## Build arm version:

	ARCH=arm ./buildps



