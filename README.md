# What to do

1. Define your goals: Begin by outlining the goals for your operating system. Decide on the target audience, supported hardware, and the specific features you want to      include. This will help you determine the requirements and constraints of your OS.

2. Choose a development environment: Select the programming languages, tools, and libraries you will use to build your OS. Typically, OS development involves a              combination of low-level languages like Assembly and high-level languages like C or Rust.

3. Learn OS fundamentals: Study the essential concepts related to OS development, including:
    -Process management
    -Memory management
    -File systems
    -Input/output (I/O) and device drivers
    -Inter-process communication (IPC)
    -Scheduling and synchronization
    -Networking

4. Develop a bootloader: The bootloader is the first piece of software that runs when a computer starts. It initializes hardware, loads the kernel into memory, and jumps    to the kernel's entry point. Study existing bootloaders, such as GRUB, to understand how they work.

5. Write a basic kernel: Develop a minimal kernel that includes basic features like memory management, process management, and I/O. You can start with a "Hello, World!" kernel and gradually expand its functionality.

6. Implement key OS components: Once you have a basic kernel, you'll need to build the essential components of your operating system. These include:
    *Process scheduler: This component manages the allocation of CPU time to processes and threads. Implement a scheduling algorithm (e.g., Round Robin, Priority           Scheduling, or Multilevel Feedback Queue) to manage process execution.
    *Memory manager: Implement a memory management scheme (e.g., paging, segmentation, or both) to allocate and deallocate memory for processes.
    *File system: Design and implement a file system for your OS that supports essential operations like creating, reading, writing, and deleting files and                  directories.
    *Device drivers: Write device drivers to enable communication between the OS and various hardware devices (e.g., display, keyboard, mouse, disk drives).
    *System calls: Implement a set of system calls (APIs) that allow user applications to request OS services (e.g., file I/O, process creation).
    *IPC mechanisms: Develop inter-process communication mechanisms (e.g., pipes, message queues, shared memory) to enable data exchange between processes.
  
7. Design a user interface: Design a user interface (UI) for your OS, which can be text-based (command-line interface) or graphical (graphical user interface). For a      graphical UI, you'll need to create a windowing system and develop libraries to support graphical applications.

8. Develop standard libraries and utilities: Create standard libraries that provide essential functionality to user applications (e.g., string manipulation, file I/O, memory allocation). Additionally, develop basic utilities (e.g., a text editor, file manager, and terminal emulator) to provide users with a functional environment.

9. Test and debug: Test your OS on various hardware configurations and in virtual environments (e.g., QEMU, VirtualBox, or VMware) to ensure compatibility and stability. Debug and fix any issues that arise during testing.

10. Document and distribute: Prepare documentation for your OS, including installation guides, user manuals, and developer resources. Distribute your OS as an installable image (e.g., an ISO file) or provide a source code repository (e.g., on GitHub) for users and contributors.


# How to start

1.Research existing operating systems: Study existing OS projects, like Linux, FreeBSD, or hobbyist OSes like ToaruOS and SerenityOS. Understand their design decisions, architecture, and the challenges they've faced. This will give you valuable insights and inspiration.

2.Set up your development environment: You will need a cross-compiler, an assembler, a linker, and a text editor or IDE for writing code. You may also want to use version control software (e.g., Git) to manage your codebase.

3.Choose a target platform: Decide on the hardware architecture and platform you want your OS to support, such as x86, x86_64, ARM, or RISC-V. This will determine the assembly language you'll use and influence other design decisions.

4.Learn Assembly language: Assembly is a low-level programming language used to communicate with hardware directly. Familiarize yourself with the assembly language for your target platform, as you'll need it to write the bootloader and parts of the kernel.

5.Write a bootloader: Start by creating a simple bootloader that initializes the hardware, loads your kernel into memory, and transfers control to it. You can find tutorials and examples online to help you write a basic bootloader for your chosen platform.

6.Learn about kernel development: Study the basics of kernel development, including process management, memory management, and hardware interaction. There are many resources available online, such as the "Writing a Simple Operating System from Scratch" by Nick Blundell and the "OSDev.org" wiki.

7.Write a minimal kernel: Develop a minimal kernel that can display a "Hello, World!" message on the screen. This will give you a starting point to build upon as you implement more advanced features.

8.Iterate and expand: Once you have a minimal kernel, gradually add features like process scheduling, memory management, file systems, and device drivers. Focus on one component at a time and test your implementation thoroughly before moving on to the next.

9.Seek help and collaborate: Join online forums, mailing lists, or open-source communities focused on OS development. Ask questions, share your progress, and learn from others. Collaboration can help you overcome challenges and improve your OS.


# Helpful reference

Books:

"Modern Operating Systems" by Andrew S. Tanenbaum
"Operating System Concepts" by Abraham Silberschatz, Peter B. Galvin, and Greg Gagne
"Linux Kernel Development" by Robert Love
"Understanding the Linux Kernel" by Daniel P. Bovet and Marco Cesati
"The Design of the UNIX Operating System" by Maurice J. Bach
"Writing a Simple Operating System from Scratch" by Nick Blundell (free PDF)
"Operating Systems: Three Easy Pieces" by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau (free online)
Websites and Tutorials:

OSDev.org (https://wiki.osdev.org) - A comprehensive wiki and forum for OS development.
JamesM's Kernel Development Tutorials (http://www.jamesmolloy.co.uk/tutorial_html) - A set of tutorials on creating a basic x86 kernel.
BrokenThorn's OS Development Series (http://www.brokenthorn.com/Resources/OSDevIndex.html) - Another set of tutorials covering a wide range of OS development topics.
ToaruOS (https://github.com/klange/toaruos) - A hobbyist OS project with well-documented source code.
SerenityOS (https://github.com/SerenityOS/serenity) - Another hobbyist OS project with clean, readable source code.
Video Lectures and Courses:

Operating Systems and System Programming (UC Berkeley) - CS 162 (https://inst.eecs.berkeley.edu/~cs162/sp19/) - A complete undergraduate course on operating systems, including video lectures and assignments.
Operating System Engineering (MIT) - 6.828 (https://pdos.csail.mit.edu/6.828/2021/schedule.html) - A graduate-level course on OS engineering, focused on building an exokernel-based OS.
Introduction to Operating Systems (Georgia Tech) - CS 8803 (https://www.udacity.com/course/introduction-to-operating-systems--ud923) - An online course by Udacity, covering the essential concepts of operating systems.
