# RISC-V Chip Tapeout Program  

## 📅 Week 0: Thu, 18 Sep 2025 – Wed, 24 Sep 2025  

### 🔧 Environment Setup & RTL Simulation Basics  

---

### ✅ Task 1: GitHub Repository  
Repository: [RISC-V Tapeout](https://github.com/Meganthiyav/RISC-V-Tapeout)
---

### ✅ Task 2: Tool Installation  

<img width="1199" height="702" alt="Screenshot from 2025-09-23 15-45-42" src="https://github.com/user-attachments/assets/813f6f6b-8db9-472e-8de4-87b018e2a269" />
 

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
<img width="1141" height="615" alt="Screenshot from 2025-09-23 15-40-39" src="https://github.com/user-attachments/assets/15a84d0e-7401-40c9-b695-9c7d7888650e" />


**iVerilog**
```
$ sudo apt-get update
$ sudo apt install gtkwave
```

<<img width="777" height="493" alt="Screenshot from 2025-09-23 15-41-10" src="https://github.com/user-attachments/assets/7a07579c-effe-4c30-84fd-e2d018eff4e5" />


**GTKWAVE**
```
$ sudo apt-get update
$ sudo apt install gtkwave
```

<img width="1113" height="713" alt="Screenshot from 2025-09-23 15-41-34" src="https://github.com/user-attachments/assets/d40cb026-423d-468f-a74d-fecaba58f00f" />



