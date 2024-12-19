# 5. Operating Systems

**Prerequisites**: 
- Systems Programming
- C/C++ Programming
- Computer Architecture basics
**Estimated Time**: 12-14 weeks (10-15 hours/week)

## Learning Objectives

- Understand operating system internals
- Master process and memory management
- Learn file system implementation
- Gain practical OS development skills

## 5.1 Process Management

**Time**: 3-4 weeks

### Resources

- 📚 **Books**:
  - "Operating Systems: Three Easy Pieces" by Remzi H. Arpaci-Dusseau (2018)
  - "Modern Operating Systems" by Andrew S. Tanenbaum (5th Edition, 2022)
  - "Operating System Concepts" by Silberschatz et al. (10th Edition, 2018)
  - "Linux Kernel Development" by Robert Love (3rd Edition, 2010)
  - "Understanding the Linux Kernel" by Bovet and Cesati (3rd Edition, 2005)
- 🎓 **Courses**:
  - [MIT 6.828: Operating System Engineering](https://pdos.csail.mit.edu/6.828/)
  - [Stanford CS140: Operating Systems](http://web.stanford.edu/~ouster/cgi-bin/cs140-spring20/)
  - [Berkeley CS162: Operating Systems and Systems Programming](https://cs162.org/)
- 💻 **Tools**:
  - [Minix](https://www.minix3.org/)
  - [Linux Kernel](https://www.kernel.org/)
  - [Xv6](https://pdos.csail.mit.edu/6.828/2020/xv6.html)
  - [QEMU](https://www.qemu.org/)
  - [VirtualBox](https://www.virtualbox.org/)
  - [Docker](https://www.docker.com/)
  - [SystemTap](https://sourceware.org/systemtap/)
  - [GDB Kernel Debugging](https://sourceware.org/gdb/onlinedocs/gdb/Kernel-Debugging.html)

### Supplemental Resources
- 📺 **Videos**:
  - [MIT 6.828 Lectures](https://www.youtube.com/playlist?list=PLfciLKR3SgqNJKKIKUMRY-tu4c014ZO4r)
  - [OS Development Series](https://www.youtube.com/playlist?list=PLHh55M_Kq4OApWScZyPl5HhgsTJS9MZ6M)
  - [Neso Academy OS](https://www.youtube.com/playlist?list=PLBlnK6fEyqRiVhbXDGLXDk_OQAeuVcp2O)
  - [Gate Smashers OS](https://www.youtube.com/c/GateSmashers)
  - [David Black-Schaffer](https://www.youtube.com/c/DavidBlackSchaffer)
  - [Berkeley CS 162](https://www.youtube.com/playlist?list=PLRdybCcWDFzCag9A0h1m9QYaujD0xefgM)
  - [Systems Programming](https://www.youtube.com/c/SystemsProgramming)
  - [OS Dev](https://www.youtube.com/c/WritingAnOperatingSystem)
- 📝 **Practice**:
  - [OSDev Wiki](https://wiki.osdev.org/)
  - [Linux Kernel Newbies](https://kernelnewbies.org/)
  - [xv6 OS Labs](https://pdos.csail.mit.edu/6.828/2020/labs/)
- 📝 **Blogs & Articles**:
  - [OS Dev Wiki](https://wiki.osdev.org/)
  - [Linux Kernel Blog](https://www.kernel.org/blog/)
  - [LWN.net](https://lwn.net/)
  - [Writing an OS in Rust](https://os.phil-opp.com/)
  - [Linux Weekly News](https://lwn.net/)
  - [The Linux Kernel Archives](https://www.kernel.org/)

### Core Concepts

- [ ] Process States
- [ ] Context Switching
- [ ] Scheduling Algorithms
- [ ] Inter-process Communication
- [ ] System Calls
- [ ] Process Synchronization

### Projects

1. **Beginner**: Simple shell implementation with basic commands
2. **Intermediate**: System call implementation
3. **Advanced**: Complete process management subsystem

## 5.2 Memory Management

**Time**: 3-4 weeks

### Resources

- 📚 **Books**:
  - "Understanding Linux Virtual Memory Manager" by Mel Gorman (2004)
  - "Memory Systems: Cache, DRAM, Disk" by Jacob, Ng, and Wang (2007)
  - "What Every Programmer Should Know About Memory" by Ulrich Drepper (2007)
- 🎓 **Courses**:
  - [CMU 15-213: Introduction to Computer Systems](http://www.cs.cmu.edu/~213/)
  - [Stanford CS346: Database System Implementation](https://web.stanford.edu/class/cs346/)
  - [MIT 6.172: Performance Engineering](https://ocw.mit.edu/courses/6-172-performance-engineering-of-software-systems-fall-2018/)
- 💻 **Tools**:
  - [Valgrind](https://valgrind.org/)
  - [Perf](https://perf.wiki.kernel.org/)
  - [Intel VTune](https://software.intel.com/content/www/us/en/develop/tools/vtune-profiler.html)
  - [Memory Sanitizer](https://github.com/google/sanitizers)

### Supplemental Resources
- 📺 **Videos**:
  - [Virtual Memory in Operating Systems](https://www.youtube.com/watch?v=qcBIvnQt0Bw&list=PLiwt1iVUib9s2Uo5BeYmwkDFUh70fJPxX)
  - [Memory Management Tutorials](https://www.youtube.com/playlist?list=PLEJxKK7AcSEGPOCFtQTJhOElU44J_Jaun)
- 📝 **Practice**:
  - [Memory Management Unit Implementation](https://github.com/mit-pdos/xv6-public/blob/master/vm.c)
  - [Linux Memory Management Documentation](https://www.kernel.org/doc/html/latest/admin-guide/mm/index.html)
- 📝 **Blogs & Articles**:
  - [OS Dev Wiki](https://wiki.osdev.org/)
  - [Linux Kernel Blog](https://www.kernel.org/blog/)
  - [LWN.net](https://lwn.net/)
  - [Writing an OS in Rust](https://os.phil-opp.com/)
  - [Linux Weekly News](https://lwn.net/)
  - [The Linux Kernel Archives](https://www.kernel.org/)

### Core Concepts

- [ ] Virtual Memory
- [ ] Paging
- [ ] Segmentation
- [ ] Memory Allocation
- [ ] Page Replacement
- [ ] Memory Protection

### Projects

1. **Beginner**: Memory allocator with different allocation strategies
2. **Intermediate**: Page table implementation
3. **Advanced**: Virtual memory system

## 5.3 File Systems

**Time**: 3-4 weeks

### Resources

- 📚 **Books**:
  - "File Systems: Design and Implementation" by Marshall Kirk McKusick (2019)
  - "The Design and Implementation of the FreeBSD Operating System" by McKusick and Neville-Neil (2nd Edition, 2014)
  - "Unix and Linux System Administration Handbook" by Nemeth et al. (5th Edition, 2017)
- 🎓 **Courses**:
  - [CS 140e: Operating Systems](https://cs140e.sergio.bz/)
  - [Advanced Operating Systems](https://www.udacity.com/course/advanced-operating-systems--ud189)
  - [File Systems and Storage](https://www.coursera.org/learn/file-systems-storage)
- 💻 **Tools**:
  - [FUSE](https://github.com/libfuse/libfuse)
  - [e2fsprogs](http://e2fsprogs.sourceforge.net/)
  - [btrfs](https://btrfs.wiki.kernel.org/)
  - [ZFS](https://openzfs.org/)

### Supplemental Resources
- 📺 **Videos**:
  - [File System Implementation](https://www.youtube.com/watch?v=n2AAhiujAqs)
  - [Modern File Systems](https://www.youtube.com/watch?v=0ZQhrcQ4YFk)
- 📝 **Practice**:
  - [Write a File System](https://github.com/psankar/simplefs)
  - [FUSE Tutorials](https://github.com/libfuse/libfuse/tree/master/example)
- 📝 **Blogs & Articles**:
  - [OS Dev Wiki](https://wiki.osdev.org/)
  - [Linux Kernel Blog](https://www.kernel.org/blog/)
  - [LWN.net](https://lwn.net/)
  - [Writing an OS in Rust](https://os.phil-opp.com/)
  - [Linux Weekly News](https://lwn.net/)
  - [The Linux Kernel Archives](https://www.kernel.org/)

### Core Concepts

- [ ] File System Architecture
- [ ] Directory Structure
- [ ] File Operations
- [ ] Storage Management
- [ ] Journaling
- [ ] File System Security

### Projects

1. **Beginner**: Simple file system implementation
2. **Intermediate**: FUSE-based file system
3. **Advanced**: Distributed file system

## 5.4 I/O Systems

**Time**: 2-3 weeks

### Resources

- 📚 **Books**:
  - "Linux Device Drivers" by Jonathan Corbet (3rd Edition, 2005)
  - "Essential Linux Device Drivers" by Sreekrishnan Venkateswaran (2008)
  - "Systems Programming in Unix/Linux" by K.C. Wang (2018)
- 🎓 **Courses**:
  - [Linux Driver Programming](https://training.linuxfoundation.org/training/linux-kernel-internals-and-development/)
  - [Device Driver Programming](https://www.youtube.com/playlist?list=PLkH1REggdbJYjpNvDv_PFlkG0nJSXhFTP)
  - [Embedded Linux and Kernel Engineering](https://bootlin.com/training/kernel/)
- 💻 **Tools**:
  - [Linux Device Driver Kit](https://01.org/linuxgraphics/gfx-docs/drm/driver-api/index.html)
  - [Kernel Driver Development Tools](https://elinux.org/Development_Tools)
  - [udev](https://wiki.archlinux.org/title/udev)
  - [sysfs](https://www.kernel.org/doc/Documentation/filesystems/sysfs.txt)

### Supplemental Resources
- 📺 **Videos**:
  - [Linux Device Driver Programming](https://www.youtube.com/playlist?list=PLCGpd0Do5-I3b5TtyqeF1UdyD4C-S-dMa)
  - [I/O System Design](https://www.youtube.com/watch?v=F18RiREDkwE)
- 📝 **Practice**:
  - [Write a Linux Kernel Module](https://sysprog21.github.io/lkmpg/)
  - [Device Driver Examples](https://github.com/martinezjavier/ldd3)
- 📝 **Blogs & Articles**:
  - [OS Dev Wiki](https://wiki.osdev.org/)
  - [Linux Kernel Blog](https://www.kernel.org/blog/)
  - [LWN.net](https://lwn.net/)
  - [Writing an OS in Rust](https://os.phil-opp.com/)
  - [Linux Weekly News](https://lwn.net/)
  - [The Linux Kernel Archives](https://www.kernel.org/)

### Core Concepts

- [ ] Device Drivers
- [ ] Interrupt Handling
- [ ] DMA
- [ ] I/O Scheduling
- [ ] Device Management
- [ ] Buffer Management

### Projects

1. **Beginner**: Character device driver
2. **Intermediate**: Block device driver
3. **Advanced**: Network device driver
