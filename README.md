<h1 align="center">:fire: TryHackMe OhSINT room :fire: </h1>

![preview](images/preview.png)<br/>

TryHackMe [Room link](https://tryhackme.com/room/ohsint)<br/>

## Task 1: OhSINT
### Q: What is this users avatar of?
Download this file by clicking that button<br/>
![download](images/1.png)<br/>

You need `Exiftool` tool. Exiftool installation command<br/>
    sudo apt install exiftool -y

Run this command where you Download the image<br/>
    exiftool WindowsXP.jpg
![exiftool](images/1-exiftool.png)<br/>