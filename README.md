# katoolinv2
A python script for installing Kali Linux tools on Debian derived linux distros.

# Features
- Add Kali linux repositories
- Remove kali linux repositories
- Install Kali linux tools

# Requirements
- Python 2.7
- An operating system (tested on Ubuntu,Lubuntu,Debian)
- Kubuntu does have some problems with installtion, I have not figured out what tool installation attempts cause them.
This seems to be likely to different KDE frameworks, etc in each distro's main repo.

# Installation
- sudo su
- git clone https://github.com/nullr00t/katoolinv2.git && cp katoolinv2/katoolin.py /usr/bin/katoolin
- chmod +x /usr/bin/katoolin
- sudo katoolin 

# Usage
- Typing the number of a tool will install it
- Typing 0 will install all Kali Linux tools
- back : Go back
- gohome : Go to the main menu
- By installing armitage , you will install metasploit

# Warning
Before updating your system , please remove all Kali-linux repositories to avoid any kind of problem .

# If you have any questions or issues, please track at following URL

Please visit https://github.com/nullr00t/katoolinv2/issues
