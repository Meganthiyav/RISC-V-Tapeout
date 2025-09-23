# RISC-V Chip Tapeout Program  

## 📅 Week 0: Thu, 18 Sep 2025 – Wed, 24 Sep 2025  

### 🔧 Environment Setup & RTL Simulation Basics  

---

### ✅ Task 1: GitHub Repository  
Repository: [RISC-V Tapeout](https://github.com/Meganthiyav/RISC-V-Tapeout)
---

### ✅ Task 2: Tool Installation  

<img width="1199" height="702" alt="neofetch" src="https://github.com/user-attachments/assets/31b4e01e-b868-4e12-a4be-8f39f032772d" />

 

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
<img width="1141" height="615" alt="yosys" src="https://github.com/user-attachments/assets/43739134-0f1d-4910-9772-a5ac50ec2f9c" />


**iVerilog**
```
$ sudo apt-get update
$ sudo apt install gtkwave
```

<img width="777" height="493" alt="iverilog" src="https://github.com/user-attachments/assets/d5351f2d-f58a-471d-b777-0492612abfbe" />


**GTKWAVE**
```
$ sudo apt-get update
$ sudo apt install gtkwave
```

<img width="1113" height="713" alt="gtkwave" src="https://github.com/user-attachments/assets/a809c0f4-2ddc-499d-9b13-0a7dbe19aa2c" />
