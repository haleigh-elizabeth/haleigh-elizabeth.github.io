# haleigh-elizabeth.github.io
## Arch Linux Documentation
---
* Here is a link to the tutorial I used incase you are more a visual person! https://www.youtube.com/watch?v=8YE1LlTxfMQ
* **Step 1:** Download the iso: https://mirror.arizona.edu/archlinux/iso/2024.12.01/
* **Step 2:** Open Virtual Box
   * Click new
   * Click the Arch iso that we just downloaded
   * Boot up the Arch VM!
* **Step 3:** Click the regular install on the welcome page (Arch Linux Install Medium (x86_64 BIOS)
<img width="433" alt="Arch_welcome_pg" src="https://github.com/user-attachments/assets/f47a019d-048e-4662-ab92-b147e6ef9b2f" />

* **Step 4:** Use the Arch install script to make our lives easier
   * Run: $${\color{blue}archinstall}$$
   * Make any changes here you would like, I'm just going to change mirroring and rootpassword'
   * Under mirroring, if we type $${\color{blue}/}$$ we can search for counties
       *  $${\color{blue}/unitedstates}$$
   * Under Disk Configuration:
       * Press enter on "best effort default partition layout"
       * Choose the one that has the most storage
       * Click enter on btrfs
       * Yes on default
       * Yes on compression
   * Under Root Password, set your password (it will complain if it is weak)
       * press enter on "adduser"
       * enter username
       * and enter another password
       * press enter on "making your user the super user"
       * press enter on "confirm and exit"
   * Under audiosevrers, press enter on pipewire
   * Under Network confiuration:
       * Press enter under network manager
   * Optional: Change the timezone, but this won't break the machine if youu dont change it, ask me how I know
* **Step 5:** Install
<img width="641" alt="arch_installing" src="https://github.com/user-attachments/assets/0831b214-51f6-440b-ab26-bfb7e3dd202b" />

   * Finally!! What we have been waiting for! Click enter on "install" and then enter on the "yes" button
   * This might take 5 years but that is ok
* **Step 6:** Click yes on chroot
   * Setting up our desktop env: Gnome
       * $${\color{blue}pacman -S gnome}$$
       * Hit enter to install all
       * Enter in 1
* **Step 7:** Reboot
   * Scroll down on the arch welcome page and click "Boot existing OS"
   * Select Arch Linux
   * Log in
   * type $${\color{blue}systemctl enable gdm.service}$$
   * Enter Pseudo password
   * $${\color{blue}sudo systenctl start gdm.service}$$
* WE HAVE A GRAPHICAL INTERFACE!
* **Step 8:**
   * Login again
