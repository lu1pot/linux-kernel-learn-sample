# linux-kernel-learn-sample
## 1. Kernel Source Preparing
*   Instal a Linux distribution on VirtualMachine
*   Get your kernel version

      ![pc-1](https://user-images.githubusercontent.com/90546600/192127394-c34ea119-192f-4877-be6d-05c555a781b1.png)

*   Download the source code of the corresponding version and decompress it

      ![pc-2](https://user-images.githubusercontent.com/90546600/192127516-258591df-a0c6-466f-a0e0-077febd15735.png)

*   Compiling a Kernel
        
        cd ./linux-5.15.65
        make menuconfig
        make oldconfig 
        make prepare 
        make scripts
        make modules_prepare
        make modules
        make modules_install
        make install
        
## 2. VSCode Settings
*   SSH remote and C/C++ plugins

      ![pc-3](https://user-images.githubusercontent.com/90546600/192127969-9f9c2dcd-0e8e-4bad-ba7d-58dce5ade414.png)

*   Connect to virtual machine

      ![pc-4](https://user-images.githubusercontent.com/90546600/192128130-8b57a68d-dd91-46d7-872c-8491af58f165.png)
      
*   Open your workspace folder

      ![pc-5](https://user-images.githubusercontent.com/90546600/192128200-00fb518b-5a2e-4b14-bfd6-dd6a438c8c6f.png)
