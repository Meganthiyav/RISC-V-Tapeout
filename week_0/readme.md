# RISC-V Chip Tapeout Program  

## 📅 Week 0: Thu, 18 Sep 2025 – Wed, 24 Sep 2025  

### 🔧 Environment Setup & RTL Simulation Basics  

---

### ✅ Task 1: GitHub Repository  
Repository: [RISC-V Tapeout](https://github.com/Meganthiyav/RISC-V-Tapeout)
---

### ✅ Task 2: Tool Installation  

<img width="1199" height="702" alt="neofetch" src="https://github.com/user-attachments/assets/7941eaab-3a46-4521-b3bb-0a4d022518db" />


 

[Download Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads)  

 



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
<img width="1141" height="615" alt="yosys" src="https://github.com/user-attachments/assets/2a66c015-1417-4247-9504-57cf77c76313" />



**iVerilog**
```
$ sudo apt-get update
$ sudo apt install gtkwave
```

<img width="777" height="493" alt="iverilog" src="https://github.com/user-attachments/assets/02a7b572-64c1-4d0d-8538-63dec44274ec" />


**GTKWAVE**
```
$ sudo apt-get update
$ sudo apt install gtkwave
```

<img width="1113" height="713" alt="gtkwave" src="https://github.com/user-attachments/assets/f5dfe712-7355-4038-9c4f-989a02c83d15" />

