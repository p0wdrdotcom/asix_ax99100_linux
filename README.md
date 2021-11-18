# What is this?
Patched linux driver for the startech 2 port PCIe Serial card with 16950 UART for Ubuntu 20.04
partnumber PEX2S953LP

### build and install
make
sudo make install

### clean up
make clean

### uninstall
sudo make uninstall

# dmesg output
```
[    0.870522] serial 0000:05:00.0: enabling device (0000 -> 0003)
[    0.870856] serial 0000:05:00.2: enabling device (0000 -> 0003)
```
```
[    5.309616] ax99100: loading out-of-tree module taints kernel.
[    5.309795] ax99100: module verification failed: signature and/or required key missing - tainting kernel
[    5.310569] ASIX AX99100 PCIe Bridg to Serial Port:v1.3.0    http://www.asix.com.tw
[    5.310700] 0000:05:00.0: ttyF0 at I/O 0xd010 (irq = 139, base_baud = 115200) is a AX99100
[    5.344182] ASIX AX99100 PCIe Bridg to Serial Port:v1.3.0    http://www.asix.com.tw
[    5.344746] 0000:05:00.2: ttyF1 at I/O 0xd000 (irq = 39, base_baud = 115200) is a AX99100
```
