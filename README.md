# Tracking-memory-and-CPU-usage
<br>

*GDB DEBUGGER
<br>

![gdb output](https://github.com/Arunprasath2003/Tracking-memory-and-CPU-usage/assets/98107416/b6de49f8-7bc1-45bb-ab7f-cbdd364a2eaa)

<br>
*Used valgrind to analyze memory usage
<br>

![valgrind output](https://github.com/Arunprasath2003/Tracking-memory-and-CPU-usage/assets/98107416/bc216666-71f0-4fdf-b3e0-662b4d0e2f7b)

<br>
*Used perf to monitor CPU usage
<br>

![perf output](https://github.com/Arunprasath2003/Tracking-memory-and-CPU-usage/assets/98107416/fdc1c0fc-f156-4eca-a162-2c1a1376cad2)

<br>

**Run Debugger in local machine and track execution in virtual machine**
<br>
**On Virtual Machine**
<br>
1.Install GDB server

2.Start GDB server on the target machine 

<br>

![gdb vm](https://github.com/Arunprasath2003/Tracking-memory-and-CPU-usage/assets/98107416/621df12d-c7e4-457c-93da-7af0c3a5e3d5)


<br>

**On host machine**

<br>
1.Run GDB on host machine

2.Connect to the GDB server on the VM

3.Set breakpoints, debug and monitor in virtual machine
