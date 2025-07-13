# Buffer memory

- Buffer is tempporary storage area, usually in memory
- it is mostly used in input/output process
- Example: In print operation CPU given data for printing , it is temporary stored in buffer.
  after giveing data to printer, CPU will do other task in system and printing will be doine by the data in buffer.

- Buffer is used to compensate that exchange or use data. 
- It is mostly used for input/output processes
- It is noramal storage area on RAM for temporary storage
- it si made of dynamic RAm
- It doesnt increase the accessing time

# Cache memory

- cache is holding recently access data
- it is fastest memory in entire system
- All the oprations done by computer system is well organized with respect to cache memory
- Chache is smaller and fastest memory component in the computer.
- It si used during readiing and writing process from the disk.
- It si high speed storage area for temporary storage
- It is made of Static RAM
- It increasing the accessing speed of CPU

#######
- to regenerate the initramfs file if the kernel panic happend Go to rescue mode by booting the linux and select rescue option
- we can use either mkinitrd or dracut command to generate the initramfs file
- rpmquery kernel
- mkinitrd

- dracut initramfs-3.10.0-1160.114.2.el7.x86_64.img 3.10.0-1160.114.2.el7.x86_64
- reboot the machine

- If already initramfs files is present and its currupted then use the -f command to do the forcefully.
- dracut -f initramfs-3.10.0-1160.114.2.el7.x86_64.img 3.10.0-1160.114.2.el7.x86_64

# or

- another method if all initramfs files get deleted then 

- attach ISO and boot the linux and select "troubleshoot" while booting 
- Then select "rescue mode" then press "1" to enter in rescue mode
- chroot /mnt/sysimage
- cd /boot 
- dracut --regenerate-all --force    (after some time it will show the initram fs files on /boot)
- ls 
