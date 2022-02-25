# ARM64-virtual-address-to-physical-address-in-user-space

This code convert virtual address(allocated in different numa node) to physical address by reading /proc/self/pagemap in user space.(Need root permission)

After Linux 4.2, only information in bit55-63 can be read.
![BY8cI6X8kJ](https://user-images.githubusercontent.com/55872966/155648494-fb44f655-ea2d-426e-a950-1ec480cf746c.png)
