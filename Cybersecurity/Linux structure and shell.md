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
