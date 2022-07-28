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
![exiftool](images/2-exiftools.png)<br/>

Now copy `OWoodflint` this text and Search on [Google](https://www.google.com). Let's visit first link which is twitter.<br/>
![Search Result](images/3-result.png)<br/>

We've found exact username and the users avatar of a `cat`.
![cat](images/4-avatar.png)<br/>

#### A: `cat`

### Q: What city is this person in?
Let's open third link of search result which is Github.<br/>
![github-result](images/5-result-github.png)<br/>

As you can see the same person of github account and his location is `London`.
![github](images/6-location-github.png)<br/>

#### A: `London`