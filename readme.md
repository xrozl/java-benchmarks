# Java Benchmark records  

自分用のJavaベンチマーク記録  

#### + Java Version (java -version)
```
openjdk version "11.0.15" 2022-04-19
OpenJDK Runtime Environment (build 11.0.15+10-Ubuntu-0ubuntu0.20.04.1)
OpenJDK 64-Bit Server VM (build 11.0.15+10-Ubuntu-0ubuntu0.20.04.1, mixed mode, sharing)
```

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
0, NVIDIA GeForce RTX 3080 Ti, GPU-xxxxxxxxxxxxxxxxx-xxxxxxxxx, [N/A]
1, NVIDIA GeForce RTX 2080 SUPER, GPU-xxxxxxxxxxxxxxxxx-xxxxxxxxx, [N/A]
```
