# Termux-GUI
Use termux in GUI mode using XFCE environment

#### XFCE running on Termux -
![Screenshot_20200211-114119](https://user-images.githubusercontent.com/32305505/75316470-74b5ee80-588b-11ea-8454-4fd4c0aceba7.png)

A simple python script to install xfce environment in Termux

## Installation
1) apt install python3
2) git clone https://github.com/OnlineHacKing/Termux-GUI.git
3) cd Termux-GUI
4) pip3 install -r requirements.txt
5) python3 gui.py

## Download
VNC Viewer - [Download](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android&hl=en_IN)

## How to start Termux-GUI

a) Run 'vncserver' command

b) Add new password for vnc

c) You will get IP Address like this -

      localhost:<session_number>

      e.g. localhost:1
   
d) After above step,type following command -

      DISPLAY=:1 startxfce4 &

   Here,1 is a session number.
      
e) Install VNC Viewer on your phone

f) Add IP Address which you got at Step 3

      e.g. localhost:1
    
g) Add name

h) Click on Connect

i) Enter VNC password which you used at Step 2

## Exit GUI

Enter following command before exit -

            vncserver -kill :<session_number>
            e.g. vncserver -kill :1
            
### Subscribe our channel on youtube
https://www.youtube.com/channel/UCwREEQuPIk7EtaRrZBVvDwg?view_as=subscriber&pbjreload=101

### Chekout our webite 
www.onlinehacking-net.cf

# ■□■□■□■□■□■□ Warning □■□■□■□■□■□■

***This tool is only for educational purpose. If you use this tool for other purposes except education we will not be responsible in such cases.***

***This information is only for educationla purpose and we are not responsible for any kind of illegal activity done by this tool***


# ■□■□■□■□■□■□ Social Media □■□■□■□■□■□■

Website :- http://www.onlinehacking-net.cf

YouTube Channel :- https://bit.ly/on9youtube

Telegram Change :- https://t.me/OnlineHacking

Telegram Group :- https://t.me/OnlineHacking0

Github :- https://github.com/OnlineHacKing

Facebook :-  https://bit.ly/facebook4page

Twitter :- https://bit.ly/twittersuman

Instagram :- https://bit.ly/instagram9oh

<a href="https://t.me/OnlineHacking"><img src="https://img.shields.io/badge/telegram-Ms.Suman || OnlineHacking-blue.svg">


                                       Inspired By github.com/OnlineHacking
