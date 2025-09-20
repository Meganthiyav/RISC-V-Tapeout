# RISC-V Chip Tapeout Program  

## 📅 Week 0: Thu, 18 Sep 2025 – Wed, 24 Sep 2025  

### 🔧 Environment Setup & RTL Simulation Basics  

---

### ✅ Task 1: GitHub Repository  
Repository: [RISC-V Tapeout](https://github.com/eceelango/Elango_RISC-V-Chip-Tapeout-Program)  

---

### ✅ Task 2: Tool Installation  

#### System Requirements  
- **RAM:** 6GB minimum  
- **Disk:** 50GB HDD  
- **CPU:** 4 vCPUs  
- **OS:** Ubuntu 20.04+  

[Download Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads)  

<img width="981" height="480" alt="System Details" src="https://github.com/user-attachments/assets/92a6a29f-0acd-413b-9392-31fbca24488b" />  

---

#### 🛠️ Yosys Installation  
```bash
sudo apt-get update
git clone https://github.com/YosysHQ/yosys.git
cd yosys
sudo apt install make
sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
make config-gcc
git submodule update --init --recursive   # Initialize abc submodule
make
sudo make install
