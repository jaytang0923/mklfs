# mklfs
tool for make littlefs image

eg:
	1.use cygwin compile mklfs.
		make
	2.prepare filesystem files
	3.make lfs image file.
		./mklfs.exe -c ./ -b 4096 -r 256 -p 256 -s 2097152 -i ./mklfs.img