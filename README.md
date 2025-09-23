# RISC-V Chip Tapeout Program  

## 📅 Week 0: Thu, 18 Sep 2025 – Wed, 24 Sep 2025  

### 🔧 Environment Setup & RTL Simulation Basics  

---

### ✅ Task 1: GitHub Repository  
Repository: [RISC-V Tapeout](https://github.com/Meganthiyav/RISC-V-Tapeout)
---

### ✅ Task 2: Tool Installation  

#### System Requirements  
- **RAM:** 6GB minimum  
- **Disk:** 50GB HDD  
- **CPU:** 4 vCPUs  
- **OS:** Ubuntu 20.04+  

[Download Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads)  
![image](Photos)
 



**Yosys**
```
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ sudo apt install git
$ cd yosys
$ sudo apt install make               # If make is not installed
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
# Yosys build depends on a Git submodule called abc, which hasn't been initialized yet. You need to run the following command before running make
$ git submodule update --init --recursive
$ make 
$ sudo make install
$sudo apt install yosys
```
![image](

**iVerilog**
```
$ sudo apt-get update
$ sudo apt install gtkwave
```


**GTKWAVE**
```
$ sudo apt-get update
$ sudo apt install gtkwave
```

