PHILOSOPHY:
- everything is a file
- small, single purpose programs
- ability to chain programs together to perform complex tasks
- avoid captive user interfaces (communicate directly with the shell)
- configuration data (like passwords) stored in a .txt file

STRUCTURE:
- Bootloader: a piece of code that runs to guide the booting process ParrotOS uses GRUB Bootloader
- OS Kernel: Main component of OS system, manages resources for systems I/O (input/output) devices at hardware level
- Daemons: Background services, ensure key functions such as scheduling, printing and multimedia working correctly
- OS shell: Also known as command line, interface between the Kernel and user, Bash is an example of this
- Graphics Server: provides a graphical or sub-system server called "X-server" to allow graphical programs to run locally or remotely through X-windowing system
- Window manager: Also known as GUI (graphical user interface) options include GNOME and Unity. Creates a desktop enviroment so you can use search tools and everything you would usually use on a desktop
- Utilities: Programs that perform a particular function for you or another program

ARCHITECTURE:
- Hardware: peripheral devices such as RAM, hard drive, CPU and others
- Kernel: manages common computer hardware such as CPU, allocated memory, accessed data. Gives them their own resorces and prevents conflict between them.
- Shell: command-line interface
- System Utility: makes available to user OS systems functionality

FILE SYSTEM HIERARCHY:
- /	The top-level directory is the root filesystem and contains all of the files required to boot the operating system before other filesystems are mounted, as well as the files required to boot the other filesystems. After boot, all of the other filesystems are mounted at standard mount points as subdirectories of the root.
- /bin	Contains essential command binaries.
- /boot	Consists of the static bootloader, kernel executable, and files required to boot the Linux OS.
- /dev	Contains device files to facilitate access to every hardware device attached to the system.
- /etc	Local system configuration files. Configuration files for installed applications may be saved here as well.
- /home	Each user on the system has a subdirectory here for storage.
- /lib	Shared library files that are required for system boot.
- /media	External removable media devices such as USB drives are mounted here.
- /mnt	Temporary mount point for regular filesystems.
- /opt	Optional files such as third-party tools can be saved here.
- /root	The home directory for the root user.
- /sbin	This directory contains executables used for system administration (binary system files).
- /tmp	The operating system and many programs use this directory to store temporary files. This directory is generally cleared upon system boot and may be deleted at other times without any warning.
- /usr	Contains executables, libraries, man files, etc.
- /var	This directory contains variable data files such as log files, email in-boxes, web application related files, cron files, and more.
