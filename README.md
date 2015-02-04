HyperToolchain ARM-EABI Manifest
================================
This is to sync all my toolchains for standalone kernel building, NOT for inline building with ROMs (meaning you have to put them in your source manually)

###Create a Dowload Directory###
```bash
# Make a directory
$ mkdir -p ~/toolchain
# cd into it
$ cd ~/toolchain
```

###Initializing the Repo and Syncing###
```bash
# Initialize the repo
$ repo init -u https://github.com/hyper-toolchains/KernelToolchain_Manifest -b master
# Sync the repo
$ repo sync -j4
```
