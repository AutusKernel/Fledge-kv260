# Setup Fledge South-Plugin

 **1. Install RPM**  
 `sudo dnf localinstall fledge-2.1.0-1.aarch64.rpm` 

**2. Make a work directory**  
`cd ~`  
`mkdir work`  
`cd work`  
 `git clone https://github.com/fledge-iot/fledge.git && cd fledge/`   
 `export FLEDGE_ROOT=~/work/fledge`  

**3. Setup Sinusoid plugin**   
`cd ~/work`  
 `git clone https://github.com/fledge-iot/fledge-south-sinusoid.git 
 && cd fledge-south-sinusoid/`   
 `cp -r python/fledge/plugins/south/sinusoid  $FLEDGE_ROOT/python/fledge/plugins/south`   
  `cd ~/work/fledge/scripts/`   
 
**4. Run**  
 `./fledge start`  

# Setup Remote Dashboard 

Open your Fl-edge-GUI on remote terminal device, and follow these steps :

## 1. Enter South plugin dashboard
**![](https://lh7-us.googleusercontent.com/HpVyOaKWWTKui30G4yP-1atNJ5ENow8EnyZd7rLcU5mGIUeIfqIT-qTGU6ryCfzqM_3GBtNqOSDCTDmr3AjHDjf2cPLwnKCpT3qYi8D_hwj2yBuPQSOQ6isvkTBJAUUY6WIZvXMYEMzcY5V6JrLIt8c)**

## 2. Setup sinusoid plugin
**![](https://drive.google.com/uc?id=1efy1b67mOELGBLBacw2eca5Bup_Wt405)**
## 3. input Asset name and next
**![](https://lh7-us.googleusercontent.com/A1Wlp_pR1l2nnBk5ObsQjjT0PooC3PQG8ozovmaQXymZcAwQ7Q32VHzM-5bJg-eVBDw4hBCzIQTyTpbGu28R2aPJJwVhIt31URjU1YvKVkY0fKkzb_ttsL_2SI4_hQRNnJTMbiNoeBvLZ7ezWDIoQCI)**



## 4. Make sure the “Enable” icon is checked!

**![](https://lh7-us.googleusercontent.com/SiVoKn7B1qsPUBpuIJn2voa3R_3cMfz4a8TmLUba-cHnd-R6fDTIdVX9FKYAQ2fCD1hfEXf52FCRHZ8RPkAi7GdpNMMk2LPLfIHtzzfXVgRHE2z6krXloAygnqu_VnjFePnQOTsn3kITtrwz8Da6rN0)**



## 5. Click done, and wait for a movement

**![](https://lh7-us.googleusercontent.com/RGzDIpu9zuPrXcB3OGGxAPSTBLQKA4r7GFjtXNuYs5HH69qkl1gi7HK7SHlie4GEnXFsZiI5JHDrGfFCuRmntFihiANGueTUmSRRDXgVe_oTVVRbQ67NGCrfi2nxECHJOXN9SHh5V85Q0SD4voJenoE)**  



# Plot real-time data

## 1. Make sure your south plugin is enabled ! 
**![](https://drive.google.com/uc?id=1p7pvRkTtnc1tN-YzOT4dd66lt2coOZia)**


## 2. Click Assets & Readings 
**![](https://drive.google.com/uc?id=14QBITxO6fMqAqjqU5dZnD0w4beAfIft5)**


## 3. Show ploting
**![](https://drive.google.com/uc?id=1IBaXPwMFNbFCQTI8wvPizgKie89Mp2i5)**
