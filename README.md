# tyro-pi
...is my repository for Raspberry Pi beginners. This is just a basic *Getting Started* repo for some of the most common tasks in one place.
---
1. Download Pi Imager --> [Official Raspberry-Pi Imager](https://www.raspberrypi.com/software/)
2. Insert microSD card into card slot on your computer. (I recommend 64GB microSD card at minimum)
- For this setup, we will be installing a 64-bit version of the PI OS manually.
- I have included the link to the [raspios_lite_arm64](https://downloads.raspberrypi.org/raspios_lite_arm64/images/raspios_lite_arm64-2021-11-08/) Pi OS image file for download. (Choose the file that has the single .zip extension)
3. *Use Custom* from the *OS Select* tab on the imager
4. Navigate to the *2021-10-30-raspios-bullseye-arm64-lite.img* that you downloaded and select it
5. Choose your microSD card from the *Storage Locations* tab
6. Click on the *Write* tab and wait 
7. Eject the microSD card and reinsert to make an *.ssh* file
8. CD into your *Boot* disk from the terminal and enter this command: ```touch ssh``` (sudo may be required)
9. Eject the microSD card once again and insert it into to microSD slot on your raspberry pi and power it up
---
## Connecting To Your Pi