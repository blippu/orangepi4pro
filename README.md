What’s inside the README


Overview <br>
the kernel for the Orangepi4pro debian bookworm is missing quite some features (http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/service-and-support/Orange-Pi-4-Pro.html)

This new kernel includes modules for:
 - TUN
 - POSIX MQUEUE
 - OVERLAY FS
 - UTF 8

linux-image-current-sun60iw2_1.0.4_arm64.deb — Kernel image & essential modules

install via 
sudo dpkg -i linux-image-current-sun60iw2_1.0.4_arm64.deb
