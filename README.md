# BEFORE YOU READ !
> IMPORTANT NOTICE
> This project has been moved to https://gihub.com/ferretbounce/FerretOS.git
> Hence, this would be the last update here
> Sorry for the incovenience :|
```
See you on the other side
```

# CLine OS

`CLine OS` is an acronym for `Command Line Operating System` 

> An operating system (OS) that manages computer hardware and software resources and provides common services for computer programs via a command-line interface (CLI).

> A light-weight, but complex, terminal-based OS where all the basic features of an OS are displayed on, and operated from, the CLI.

# Key Features

**User interface:** provides a friendly `user interface` that allows users to interact with the system via a command-line interface.

**File system management:** manages the `organisation` and `storage` of files on disk, providing a hierachical file system and file access controls, via the CLI.

**Process management:** manages the `execution` of programs or proceses, allocating resources such as CPU time, memory, and I/O devices.

**Memory management:** manages the `allocation` and `deallocation` of memory to processes, ensuring that each process has access to the memory it needs.

**Device management:** manages the `interaction` between the computer and its peripheral devices, such as printers, scanners, and network adapters.

**Security:** provides `security features` such as `user authentication`, `access controls`, and `encryption` to protect the system and its data from `unauthorised access`.

**Networking:** provides networking features such as `TCP/IP` protocol support, `network configuration`, and `network device drivers`.

**Web interfacing:** provides `web browsing` features, `interfaced` through the command line.

**Multitasking:** allows multiple programs or processes to `run simultaneously`, sharing system resources such as CPU time and memory.

**Error handling:** provides error handling features that `detect` and `recover` from errors such as `hardware failures`, `software crashes`, and `network errors`.

**Virtualisation:** provides virtualisation features that allow multiple operating systems or instances of an operating system to run on a single physical machine, and also ability to run on virtualisation softwares, like `virtual box` and `vmware`, as a `guest operating system`.

**Windowless:** provides a command-line interface, where there is no support for `windowing` features or `graphical user interface (GUI)` , every activity is carried out on a `single terminal`.

**Customization:** provides customization for system `layouts` and `appearance`.

# Project Structure

```
CLineOS
 |
 |-core/
 |  |
 |  |-boot/
 |  |
 |  |-cpu/
 |  |
 |  |-drivers/
 |  |
 |  |-kernel/
 |
 |-os/
    |
    |-bash/
    |
    |-libs/
    |
    |-sysroot/
    |  |
    |  |-bin/
    |  |
    |  |-devices/
    |  |
    |  |-etc/
    |  |  
    |  |-home/
    |  |
    |  |-media/
    |  |
    |  |-root/
    |  |
    |  |-tmp/
    |  |
    |  |-usr/
    |     |
    |     |-bin/
    |
    |-term/
    |
    |-utils/
    |
    |-websh/

```
> The above structure shows a prototype for directories of the project.
> NOTE: It's just a PROTOTYPE and can be modified or entirely changed with time.
> See the readme files located in each directories for more info

