# A guide for GPD WIN4 Owners
<a name="readme-top"></a>
<div align="center">
<img src="images/BlondDentalAnchovy-mobile.gif" alt="Logo" width="600" height="400">
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#useful-information">Useful information</a></li>
      </ul>
    </li>
    <li>
      <a href="#drivers--applications">Drivers & Applications</a>
      <ul>
        <li><a href="#motion-assistant">Motion Assistant</a></li>
        <li><a href="#screen-color-correction">Screen Color Correction</a></li>
        <li><a href="#power-control-panel-v2">power-Control-Panel-v2</a></li>
        <li><a href="#test-your-device">Test your device</a></li>
      </ul>
    </li>
    <li><a href="#youtube-videos">Youtube Videos</a></li>
    <li><a href="#accesories--parts">Accesories & Parts</a></li>
    <li><a href="#specs">Specs</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- GETTING STARTED -->
## Getting Started

This is an set of instruction or checklist of sorts for me to follow once I get my device. I will do two different ones because I will be doing a fresh install of windows on a new SSD, and the included SSD will be left for trouble-shooting.

> for those of us that would lopve to 3D print some accesories. </br>
***[3D model file](https://github.com/lertsoft/GPD_WIN4/releases/tag/v0.1.1-3DModel)***

### Test your Hardware 
1. Test gpu under load, look for black screens. (Use graphically instensive software. ie. AAA games, 3dmark, photoshop, etc.)
    * [🚨🚨 GPU STRESS TEST SOFTWARE 🚨🚨](https://geeks3d.com/furmark/)
2. Check bios version (Only update if necessary, see #1 ^^ Above ^^)
3. Test all keyboard keys and buttons.
4. Test all the ports. 
    * USB C 4 - Top. Should charge and transmit up to 40 Gbps.
    * USB A 3.2 - Top. Should transmit up to 10 Gbps.
    * USB C 3.2 - Bottom. Should charge and transmit up to 10 Gbps.
5. Test the micro sd card slot. Look for disconnecting and reconnecting issues, be patience as this might take a day or two of using the slot to notice any unexpected behavior.
4. Test analog deadzones and update firmware if needed
6. Look for dead pixels
7. Test the Touch screen for deadzones. (dragging your finger across the entire screen could help finding any)
8. Test the small touchpad ( if it doesn't work or is not working properly update firmware)
9. Look for any gaps on the devices.
    * Check the seams between the top shell and bottom shell.
    * Check for gaps between the screen and the screen holder.
    * Check for more than normal gaps between the sliding screen and keyboard, ( More than 3 mm should bad, I think)
10. [Test your analog stick circularity](https://gamepad-tester.com).
11. Make sure your keycaps, top and bottom shell does not have any cracks.
12. Do a full malware scan, or reinstall OS.
13. [Stress Test Your CPU ](https://www.mersenne.org/download/)

    
### Installation
 * ***Windows***
    <details>
    <summary>GPD Windows ISO</summary>
     1. <a href="https://gpd.hk/download">Download GPD's windows ISO</a> </br>
     2. Install Windows like you normally would </br>
   
    
   </details>
    
   <details>
     <summary>Clean Windows ISO</summary>
     1. Download microsoft official ISO: </br>
     <ul>
         <a href="https://www.microsoft.com/en-us/software-download/windows10ISO">Windows 10</a> </br>
         <a href="https://www.microsoft.com/en-us/software-download/windows11">Windows 11</a> </br>
      </ul>
     2. Install Windows like you normally would </br>
    
    </details>
 
  
 * ***SteamOS***
     > Useful repo if venturing into Steam os. [Proton's Direct3D 12 implementation](https://github.com/HansKristian-Work/vkd3d-proton) 
 
 
     <details>
     <summary>SteamDeck OS - Recovery Image</summary>
     1.    <a href="https://help.steampowered.com/en/faqs/view/1B71-EDF2-EB6D-2BB3">Download the steamdeck OS recovery image from valve</a> </br>
     2.    <a href="https://gist.github.com/drraccoony/8a8d0a9e3dfde9fafd3e374e418d2935#setting-expectations">This gist has all the needed information</a> </br>
     3. TBD - I will follow these steps once I receive my Win4
    
    </details>
    
     <details>
     <summary>Steam OS</summary>
     1.    <a href="https://store.steampowered.com/steamos/buildyourown">Download steamOS official ISO</a> </br>
     2. TBD - Once I receive my unit I will populate this
    
    </details>

### Useful Information

[GPD WIN4 Manual](Manuals/GPD_WIN4_User_Mannual.pdf)

***Changing the iGPU vRAM allocation***
> Note: The ram on the GPD Win 4 is shared meaning that the 16GB or 32GB of RAM of the device will go to both the CPU and GPU which could hamper performance of the devices depending on the configuration. The recommended amount of vRAM is 4GB for the 16GB RAM model, and 8GB for the 32GB RAM model.

1. Enter BIOS by holding the DEL key during boot
2. Go to "Advanced" tab
3. Go to "GFX Configuration"
4. Change "UMA Frame buffer Size" to desired value, the recommended value is 4GB for the 16GB RAM model, and 8GB for the 32GB RAM model.
5. Press ESC and go to "Save & Exit" tab
6. Select "Save Changes and Exit" and select "Yes"

> ***btprice2001*** shared this images on the discord to show the difference between difference vRAM allocations at different TDP's.

![Red Dead Redemption](https://github.com/lertsoft/GPD_WIN4/blob/main/images/RDR2-32APU%20Share%20memory%20perfomance.png)

![Cyberpunk](https://github.com/lertsoft/GPD_WIN4/blob/0374d83c747fbcd464f696301f024df4ed26fbd5/images/CP-32APU%20Share%20memory%20perfomance.png)

![Forza Horizon 5](https://github.com/lertsoft/GPD_WIN4/blob/0374d83c747fbcd464f696301f024df4ed26fbd5/images/FH5-APU%20Share%20memory%20perfomance.png)

![Shadow of the Tomb Raider](https://github.com/lertsoft/GPD_WIN4/blob/0374d83c747fbcd464f696301f024df4ed26fbd5/images/SOTTR-32APU%20Share%20memory%20perfomance.png)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DRIVERS & APPLICATIONS -->
## Drivers & Applications
> GPD Official release drivers are out! This is the link to get them. [GPD Download page](https://gpd.hk/gpdwin4firmwaredriver)

1. [AMD Adrenalin software](https://www.amd.com/en/support/apu/amd-ryzen-processors/amd-ryzen-7-mobile-processors-radeon-graphics/amd-ryzen-7-6800u)
2. [GPD Driver pack](https://github.com/lertsoft/GPD_WIN4/releases/tag/v5)
3. [GPD Windows 11 22H2](https://gpd.hk/gpdwin4firmwaredriver)
4. Motion Assistant <br>
    a. [Original Source](https://discord.com/channels/243411108940087297/826965330965430272/1037625013441933382) </br>
    b. [download link](https://github.com/lertsoft/GPD_WIN4/releases/tag/v1.1.4) </br>
    c. [Motion Asisstant Manual](Manuals/Motion_Assitant_manual.pdf) </br>
5. WIN Control <br>
    a. [Original Source](https://gpd.hk/gpdwin4firmwaredriver) </br>
    b. [download link](https://github.com/lertsoft/GPD_WIN4/releases/tag/v1.08) </br>
    c. [WIN Controls Manual](Manuals/GPD_Win_Controls_Manual.pdf) </br>

### Screen Color Correction
> These files were provided by GPD. See video description. </br>

* [Files](Color_Correction)

* [GPD Color correction Video](https://www.youtube.com/watch?v=-QiW4Zqy-6E)

### Handheld Companion
Use cases taken from the Handheld companion repo:
```
" You want to add universal motion controls (UMC) to any game.
You want to add high-precision motion controls to your Windows game library through Steam.
You want to play your Sony Playstation 4 library through PlayStation Now or PS4 Remote Play.
You want to enjoy all your Wii, WiiU and Switch games with full motion controls through UDP motion control protocol. "
```
https://github.com/Valkirie/HandheldCompanion/tree/0.14.0.9

### Power-Control-Panel-v2
Control and change the TDP of the compatible devices.</br>
https://github.com/project-sbc/Power-Control-Panel-v2

### test your device
***GPU***</br>
https://github.com/kruzer/poclmembench/tree/0.91

***CPU, GPU, RAM, & Others***</br>
https://www.passmark.com/products/performancetest/index.php

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- YOUTUBE TUTORIAL AND VIDEOS -->
## Youtube Videos

The Phawx</br>
- Setting up Motion Assistant on the WIN4. [LINK](https://www.youtube.com/watch?v=WWkmyAxn6-E) </br>
- Setting up Auto TDP tool on 6800U devices. [LINK](https://www.youtube.com/watch?v=ZnEQ068poY0)

TheRelaxingEnd</br>
- ASMR Video of the GPD Win 4. [LINK](https://www.youtube.com/watch?v=livIIS8MYe0)

NITTRX</br>
- Disassembly of the GPD Win 4. [LINK](https://www.youtube.com/watch?v=dhbx1abJWTc)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACCESORIES AND REPAIR PARTS -->
## Accesories & Parts

Batteries from GPD AliExpress store.</br>
https://www.aliexpress.us/item/3256802595312541.html?gatewayAdapt=Pc2Msite </br>
https://www.aliexpress.us/item/3256803076020665.html?gatewayAdapt=Pc2Msite </br>

GPD Win 3 replacement Joystick by [Dovah](https://www.thingiverse.com/dovahkiiiin/designs)</br>
Someone said on discord that the Joystick for the win 3 and win 4 are the same but I will update once the retail unit starts arriving in peoples hands. </br>
https://www.thingiverse.com/thing:5100417

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- SPECS AND HARDWARE DETAILS -->
## Specs
```
Any SSD that is single sided should work on the GPD Win 4.
These are some of them.
```
* WD Black SN770
* Crucial P3

#### GPD Win 4 Specs
>Turn off dark mode to see the image better

![GPD Win4](images/GPD_Win4_Specs.png)

#### Comparison between the AMD 6800U and The AMD 7735 APU's. </br>

> This is for future reference for peeps figuring out which APU is better.

![AMD6800U VS AMD7735](images/AMD6800U_VS_AMD7735.png) </br>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

* [Open a new issue](https://github.com/lertsoft/GPD_WIN4/issues)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Ronny Coste - [@costeronny](https://twitter.com/costeronny)

Project Link: [https://github.com/lertsoft/GPD_WIN4](https://github.com/lertsoft/GPD_WIN4)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Choose an Open Source License](https://choosealicense.com)
* [btprice2001]()
* [Sabrina](https://github.com/SabrinaRDC/WM2-Help)
* [The Phawx](https://www.youtube.com/@ThePhawx)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
