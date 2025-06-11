# Barebones Linux

A W.I.P linux distro that will be designed to run on the most low end devices!

This means that the OS will be free of disgusting bloatware that forces more and more performance (which I know your dad's old Windows Vista laptop can't do.) This means that Barebones will be; of course, barebones.

## Important

**This project is in early development.**  
Expect frequent changes, missing features, and possible instability.
(Don't believe me? Test it out and try typing `exit`)
Contributions and feedback are welcome!

## How to use in QEMU VM ONLY!
1. Download the boot file from the linux directory in this repository.

- ![Barebones Linux Screenshot](images/directory.png)
2. Make sure you have qemu installed on your computer. 
(You can cd to ) 
Then, open your terminal and type:
```
    qemu-system-x86_64 boot

```
The VM should start. But we are not done just yet!

You should see a prompt that says `boot# ` or similar. Type:

```
    /bzImage -initrd=/init.cpio

```
After a bit, you should see the shell.