# Java Benchmark records  

自分用のJavaベンチマーク記録  

#### + OS (lsb_release -a)
```
No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 20.04 LTS
Release:        20.04
Codename:       focal
```

#### + Kernel (uname -a)
```
Linux 5.10.16.3-microsoft-standard-WSL2 #1 SMP x86_64 x86_64 x86_64 GNU/Linux
```

#### + CPU (lshw -class processor)
```
  *-cpu
       product: AMD Ryzen 9 5950X 16-Core Processor
       vendor: Advanced Micro Devices [AMD]
       physical id: 1
       bus info: cpu@0
       width: 64 bits
       capabilities: fpu fpu_exception wp ... (and more)
```

#### + GPU (nvidia-smi --query-gpu=index,name,uuid,serial --format=csv)
```
index, name, uuid, serial
0, NVIDIA GeForce RTX 3080 Ti, GPU-9fcf2c75-c742-c00b-24df-xxxxxxxxx, [N/A]
```
