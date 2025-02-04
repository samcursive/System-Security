# Objectives
1. Install VM
2. Understand packet capture, filter and intercept them using `Wireshark` and `pyshark`




# Install a Linux VM
1. Install [VirutalBox]()


# Install and run Wireshark VM.

1. Update apt (Advanced Package Tool)
    `sudo apt update`

2. Upgrade apt
    `sudo apt upgrade`

3. Install wireshark:
    `sudo apt install wireshark`

4. Enable Root Privileges. When Wireshark installs on your system, you will be prompted to enable super user `su` / **root** privileges to operate. You will also be asked to enable permissions for non-super users either. Yes or No, your call. 

5. Reconfigure Permission Settings
    `sudo dpkg-reconfigure wireshark-common`
     <!-->Select yes<--->
     `sudo usermod -a -G wireshark <username>`
     `reboot`

6. Launch wireshark
    `sudo wireshark`
