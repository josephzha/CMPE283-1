1. I did the assignment myself.
2. steps that I took:
	1. Install VMware Fusion on my mac.
	2. Download Ubuntu 20.04 desktop verison iso file.
	3. Using the iso, create a virtual machine with Fusion.
	4. Increase the size of hard disk in Fusion setting.
	5. Select "enable hypervisor application in this virtual machine".
	6. Start virtual machine.
	7. Login to Canvas, download Makefile and cmpe283-1.c.
	8. Go to https://wiki.ubuntu.com/Kernel/BuildYourOwnKernel, use the command in first section to setup environment.
	9. In cpme283-1.c, define MSR address, define capability_info's index and name, duplicate the code block that reads and interprets the MSRs, following the example given for PINBASED controls. The infomation can be found in sdm volume3, chapter 24.6, 24.7, 24.8, and 24.9
	10. Save and exit the file, in terminal, use "make" command and "sudo insmod" to load module.
	11. In terminal, use "dmesg" to read the output.
