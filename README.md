# CharacterDeviceDriver
A Linux Kernel Module written in C that creates a custom character device (/dev/marvellous_driver). It implements file operations like open(), read(), write(), and close(), and demonstrates safe data transfer between user space and kernel space using copy_to_user() and copy_from_user()
