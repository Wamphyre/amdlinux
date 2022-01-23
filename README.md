# AMDLinux
Linux kernel optimized for AMD CPUs.

AMDLinux is a personal and independent Linux kernel optimization project specially customized for AMD CPUs and packaged for GNU/Linux distros of the Debian/Devuan family.

The idea is to take advantage of the full potential of these CPUs by compiling the kernel specifically using flags only compatible with the Athlon/Opteron/Hammer/K8/Ryzen families.

The "Linux-Libre" version of the FSFLA is used as the basis of the Linux-Libre AMDLinux version. 

The project offers Linux and Linux-Libre kernel versions, and is divided into 3 different types depending on the task.

1 - DESKTOP KERNEL
For multipurpose tasks, gaming and desktop work. Patched with ZEN SMP PREEMPT. (Only available on regular Linux version)

2 - REAL TIME KERNEL
For audio/video production and tasks where ultra-low latency is critically needed. Patched with SMP PREEMPT_RT

3 - SERVER KERNEL
Designed for server loads, fully patched for SMP.

The kernel is provided directly as easily installable binaries (.deb) and is NOT COMPATIBLE WITH INTEL CPUs.

=====WARNING=====

- It is recommended that before trying these kernels you have a different kernel already installed on your system as backup and recovery.

- As we saw before, the "Linux-Libre" version does not contain any proprietary blob, so it is possible that this kernel is not 100% compatible with all the hardware on your machine.

- If you crash your machine during the installation it is solely your fault.
