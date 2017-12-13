# Packages Necessaries for the build (Ubuntu)
build-essential
linux-headers

# Use mode

In the projects folder type the following command

make

After use the commando for init the module

insmod ./hello−1.ko

For verify the module use

lsmod | grep hello

Then verify the success about this process using

dmesg | grep Hello -> This return an line with Hello World

For remove the module from the kernel use

rmmod hello−1
