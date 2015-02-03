HyperToolchain ARM-EABI Manifest
================================
This is to sync all my toolchains for standalone kernel building, NOT for inline building with ROMs.

Create a Dowload Directory
--------------------------
   $ mkdir -p ~/toolchain
   $ cd ~/toolchain
  
Initializing the Repo and Syncing
----------------------------------
   $ repo init -u https://github.com/hyper-toolchains/KernelToolchain_Manifest -b master
   $ repo sync -j4
