HyperToolchain ARM-EABI Manifest
================================
This is to sync all my toolchains for standalone kernel building, NOT for inline building with ROMs.

First do the following
  $ mkdir -p ~/toolchain
  $ cd ~/toolchain
  
To sync up,
 $ repo init -u https://github.com/hyper-toolchains/KernelToolchain_Manifest -b master
 $ repo sync -j4
