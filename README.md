# tyro-pi
...is my repository for Raspberry Pi beginners. This is just a basic *Getting Started* repo for some of the most common tasks in one place.
---
1. Download Pi Imager --> [Official Raspberry-Pi Imager](https://www.raspberrypi.com/software/)
2. Insert microSD card into card slot on your computer. (I recommend 64GB microSD card at minimum)
- For this setup, we will be installing a 64-bit version of the PI OS manually.
- I have included the Pi OS image file in the Pi-Images folder in this repo.
3. *Use Custom* from the *OS Select* tab on the imager
4. Navigate to the 64bit-lite image in *Pi-Images* folder and select to make boot disk from microSD card
5. Eject microSD card and reinsert to make an .ssh file
6. CD into your *Boot* disk from the terminal and enter this command: 'touch ssh' (sudo may be required)