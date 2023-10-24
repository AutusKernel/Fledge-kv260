# Update history  
Author : Kenny  
update : 2023/10/23  

# Install Fledge-GUI 

## Method 1. Base on source

## Hardware    
MacBook Pro  
2.3 GHz Dual-Intel Core i5  
8 GB 2133 MHz LPDDR3  
MacOS 13.2.1    


## Get Resource and Install

1. Update yarn  
     `sudo npm i -g yarn`

2. Clone fledge gui.  
 `git clone https://github.com/fledge/fledge-gui.git
 && cd fledge-gui`

3. Run yarn manager and launch guide server  
`yarn install && yarn start`

4.  Make sure the following text appears in the terminal  
`Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/`   
 
5. Now, we could open web browser and navigate to   
 `http://localhost:4200/`

6. You should see the gui configuration screen below.
 ![enter image description here](https://drive.google.com/uc?id=1WuPChGjMZw5trbh__kaPm9xaESEzZZZ4)

7. Hit the blue button to "Set the URL & Restart", after modifying the host ip address

8. Using curl get to test RPC :  
    `curl -sX GET http://fledge-ip:8081/fledge/ping`


## Method 2. Base on .deb package  
## Hardware
Asus E203 
Intel N4000  Dual-core
4 GB LPDDR4  
UBUNTU 20.04    

## Get Resource and Install
`sudo DEBIAN_FRONTEND=noninteractive apt -y install fledge fledge-gui`
