## SSH Access for Browan/Merryiot

Follow Instructions on this YouTube video to gain SSH Access. 

- [Youtube Video](https://www.youtube.com/watch?v=bkl76iK-WAo) 
- [Google Drive Link](https://drive.google.com/drive/folders/1xxxJP7udmXkyyLGqBmzz7l15Ing898cl) 


## Crankk Install

Download Crankk Installer

- [Crankk Installer](https://crankk.io/downloads/) 

- Open Crankk Installer, install Crankk
  - Type In Gateway IP
  - Default Port is 168
  - Username: root
  - Password: Password generated when you enabled SSH
 

- Log into the Local Dashboard
  - http://gatewayIP:/17080
  - Username: admin
  - Password: Last 6 symbols of MAC Address (ex. B163B9)
  - Can change password in settings tab

- Follow the rest of the instructions for Panther X1/X2
  - [Panther Instructions](https://crankk.io/storage/2023/08/Panther-X1-X2-1.pdf) 
  - Continue at step #7
  - After install, stop the Browan packet-forwarder to use Crankk packet-forwarder `sudo systemctl stop lora_pkt_fwd.service` & `sudo systemctl disable lora_pkt_fwd.service`



