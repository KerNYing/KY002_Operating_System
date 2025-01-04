## What Operating Systems Do 
in &#x1F1FA;&#x1F1F8;

- [x] 1.1.0 Intro
- [x] 1.1.1 User View
- [x] 1.1.2 System View
- [ ] 1.1.3 Defining Operating Systems 

<!-- &#x1F1F0;&#x1F1F7; 한국  
&#x1F1FA;&#x1F1F8; 미국 -->

### A computer system can be divided roughly into four components
 - Hardware
    
    > provides the basic computing resources for the system

 - Application programs

    > define the ways in which these resources are used to solve user's computing problems
 - **Operating system**
  
    > controls the hardware and coordinates its use among the various application programs for the various user
 - User
  
### User View
The user's view of the computer varies according to the interface being used.

Laptop or PC consisting of a monitor, keyboard, and mouse is designed for one user to monopolize its resources. The goal is to maximize the work that the user is performing. In this case, the OS is designed mostly for **ease of use**, with some attention paid to performance and security and none paid to **resource utilization**

Many users interact with mobile devices featuring a **touch screen**, where they press and swipe their fingers across the screen, as well as **voice recognition** interfaces.

Some computers, such as **embedded computers**, have little or no user view. They may have numeric keypads and status indicators with lights but are primarily designed to run without user intervention

### System View

From the computer's point of view, the operating system functions as a **resource allocator**,
managing resources such as CPU time, memory space, storage, and I/O devices. It determines how to allocate these resources effectively. 

Alternatively, the operating system can be viewed as a **control program** that oversees user program execution to prevent errors and improper use of the system.


### Defining Operating Systems

The term *operating system* covers many roles and functions.

**Moore's Law** predicted that the number of transistors on an integrated circuit would double every 18months, and that prediction has held true.

The operating system is the one program running at all times on the computer - usually called the **kernel**.

Along with the kernel, there are two other types of programs
- **system program**: associated with the operating system but are not necessarily part of the kernel
- **application program**: include all programs not associated with the operation of the system.


Mobile operating systems include not only a core kernel but also **middleware** - a set of software frameworks that procide additional services to application developers.

In summary, the operating system includes the always running kernel, middleware frameworks that ease application development and provide features, ans system programs that aid in managing the system while it is running.
