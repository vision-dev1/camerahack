# CAMERA HACK
![Camera Hack](https://github.com/vision-dev1/camerahack/blob/aa5883bcfe4b7ba6719908fc26233c51ecbb3505/haha.jpg)


###### HACK CAMERA LIVE WITH CLOUDFLARED LINK.
***
### <p align="center">Commands to run tool in ur terminal Termux && Kali Linux
***

### Overview
This project is an educational demonstration that illustrates how camera‑permission phishing attacks can work in a controlled environment. It is intended for learning, awareness, and defensive research only.
Do not use this project to harm, harass, spy on, or violate the privacy of others. Unauthorized access to devices, cameras, or personal data is illegal in many jurisdictions.

### [+] Features
 - Three Templates (More Templates Coming Soon)
 - Get IP, Location, Device type and Browser
 - Dual Tunneling (Cloudflare && ngrok)
 - Choose where to save images(custom directory) 
 - Error Diagnoser
 - Argument support for templates, tunnelers and directory

### Supported Platforms
- Kali Linux
- Termux
- MacOS
- Ubuntu
- Perrot Sec OS
- Garuda Linux

### Technology Stack
- Bash Script
- HTML
- PHP
- JavaScript
- CSS

### How It Works ?
This tool hosts a phishing website on the attacker’s local network and provides two port-forwarding options ( Ngrok and Cloudfare) to expose the site to the internet.
In practice, the attacker launches the tool via the terminal and generates a public link, which is then shared with the target. When the target accesses the link, the target’s IP address is captured and transmitted to the attacker.
After the website loads, it requests permission to access the device’s camera. If the target grants permission, the site captures camera images sequentially and sends them back to the attacker.

###### Installation
```bash
apt update && apt upgrade -y
```
```bash
apt install git -y
```
```bash
apt install php
```
```bash
apt install curl -y
```
```bash
apt install wget -y
```
```bash
git clone https://github.com/vision-dev1/camerahack.git
```
```bash
cd camerahack
```
```bash
chmod +x hack_camera.sh (optional)
```
```bash
bash setup
```
```bash
bash hack_camera.sh
```
###### For Termux Additional Command 
```bash
 termux-setup-storage
 ```
###### Disclaimer
This project is developed strictly for educational and awareness purposes. It demonstrates how camera‑permission phishing techniques may work so developers, students, and security enthusiasts can better understand and defend against them.
You are solely responsible for how you use this project. Any misuse, damage, or violation of laws is entirely your responsibility. The author(s) and contributors assume no liability for improper or illegal use.
