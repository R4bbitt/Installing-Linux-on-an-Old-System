# Installing-Linux-on-an-Old-System
A project to learn about Linux Distros and troubleshoot an unknown system. I came across this old Phillips system my work was going to through away and I thought it would make for a fun little project. First I wanted to find out what it was used for. 

I started by dissambling the whole system to get a good look at all the moving parts. By looking up the motherboard model and found this machine was most likely a Phillips Light System Engine. Being that, the system was meant to run headless, and run for a long time while consuming minimal power and staying cool. 

![IMG_3601](https://github.com/user-attachments/assets/4c0dd0d1-0ec9-472e-ac89-ef99d8943385)

This motherboard only supports up to 4GB of RAM limiting my options for Linux Distros and use cases. I decided to go with Lubuntu a lightweight distribution of Linux. 

Upon first boot, in BIOS the original SSD was not being recognized and only my bootable USB with Linux was showing up. So next I bought a larger SSD that was compatible with the old power supply, as well as changing out the 1GB stick of RAM with two 2GB sticks to max out the capacity. 

(Before, 64GB SSD, 2x2GB RAM already installed)

![IMG_3619](https://github.com/user-attachments/assets/b43303a1-b628-4093-8b6f-a62670095446)

(After: 240GB SSD)

![IMG_3679](https://github.com/user-attachments/assets/8b1177f0-1135-4641-8422-85228d60693e)

Next I went into BIOS and now seeing the SSD I was able to continue with booting and downloading Lubuntu from USB

![IMG_3682](https://github.com/user-attachments/assets/19d2f1b6-174c-44c7-b661-162850cd7898)

![IMG_3683](https://github.com/user-attachments/assets/6a50a50c-c8f2-4cc2-ab6b-e10e9c3673dd)

Next, just as a fun exercise I implemented stronger password complexity: adding a 12 character minimum, at least one uppper case letter, one number, and allowing one failed password attempt.

![IMG_3765](https://github.com/user-attachments/assets/8ef0d870-1187-4eb2-9457-639eef67e6c9)

Here's a screenshot to show it working by trying to set a password that does not meet these reuqirements.

![IMG_3767](https://github.com/user-attachments/assets/32aa5772-c3b5-4da1-b2c4-7d96c8f68be0)

