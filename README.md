## SSH Access for Browan/Merryiot

Follow Instructions on this YouTube video to gain SSH Access. 

Browan Devices
  - [Youtube Video](https://www.youtube.com/watch?v=bkl76iK-WAo) 
  - [Google Drive Link](https://drive.google.com/drive/folders/1xxxJP7udmXkyyLGqBmzz7l15Ing898cl) 

PantherX2 Devices
  - [SSH Instructions](https://github.com/sicXnull/pantherx2_merryiot) 


## Crankk Install

Download Crankk Installer

- [Crankk Installer](https://crankk.io/downloads/) 

- Open Crankk Installer, install Crankk
  - Type In Gateway IP
  - Default Port is 168
  - Username: root
  - Password: password (change this after you get in by running `sudo passwd root`)
 

- Log into the Local Dashboard
  - http://gatewayIP:/17080
  - Username: admin
  - Password: Last 6 symbols of MAC Address (ex. B163B9)
  - Can change password in settings tab

- Follow the rest of the instructions for Panther X1/X2
  - [Panther Instructions](https://crankk.io/crankk-official-guide-for-onboarding-a-panther-x1-x2-gateway/) 
  - Continue at step #7
  - After install, stop the Browan packet-forwarder to use Crankk packet-forwarder `sudo systemctl stop lora_pkt_fwd.service` and `sudo systemctl disable lora_pkt_fwd.service`



