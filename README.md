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

### Q: Whats the SSID of the WAP he connected to?
Again go to this `twitter account` and scroll down, copy the bssid `B4:5D:50:AA:86:41`
![bssid](images/7-bssid-link.png)<br/>

Search `wigle` on [Google](https://www.google.com) and visit the website.<br/>
![wigle](images/8-searching-wigle.png)<br/>

Past the BSSID click on `Filter` and find the location pointer and it's `UnileverWiFi`.<br/>
![wigle](images/9-wigle-bssid.png)<br/>

#### A: `UnileverWiFi`

## Q: What is his personal email address?
Go to this `Github account` and search the gmail id.<br/>
![gmail id](images/10-gmail-id.png)<br/>

#### A: `OWoodflint@gmail.com`

## Q: What site did you find his email address on?
#### A: `Github`

## Q: Where has he gone on holiday?
Go to this link<br/>
![blog](images/11-blog-link.png)<br/>

As you can see He is in New York now.<br/>
![new york](images/12-new-york.png)<br/>

#### A: `New York`

## Q: What is this persons password?
When I drag by mouse it's highlighted and found the password.<br/>
![pwd](images/13-pwd-found.png)<br/>

#### A: `pennYDr0pper.!`

<h3 align="center">Congratulations, Finished the room.</h3>