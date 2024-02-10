# Colorful Lock

*a custom plymouth theme*

https://github.com/OsiPog/colorful-lock/assets/87434959/1a0056ef-63b2-4bfa-a919-c7bacfd27c63



## Installation

1. clone the repo somewhere

   `git clone https://github.com/OsiPog/colorful-lock.git`

2. move it to the plymouth themes directory

   `sudo mv colorful-lock /usr/share/plymouth/themes/`

3. set the default plymouth theme

   `sudo plymouth-set-default-theme colorful-lock`

4. update initramfs

   `sudo update-initramfs -u`



## Credit

- Lock Icon is from Material Design: https://pictogrammers.com/library/mdi/icon/lock/
- The two animations (before and after lock) are from here: https://github.com/adi1090x/plymouth-themes (colorful_loop and circle_alt)
