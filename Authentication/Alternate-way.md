# Using Grub boot menu 

( Using this method ,it would not be a sudoer's account, but rather root.)

- While in Grub bootloader ( option = Debian testing probably )

- Go to the bottom where it says linux

- Look for /boot/vmlinuz-5.......( "vvmlinuz" not "vmlinux" )got to the end of the line

- Type "single" and hit f10

__We are now booting as "single user mode"__


Now,


- Type "passwd" - to change the password

- Input your new password - setting the new password

- Reboot - to reboot the computer
