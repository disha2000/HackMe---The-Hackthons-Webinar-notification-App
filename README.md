# Hackme - The Hackthons/Webinars notification App

## Overview

We have many websites that notify the current hackthons like MLH, and devfolio but for mobile devices there is no such app for this. So for this, I have built the app using flutter that will keep users updated with latest hackathons. To get all information related to upcoming hackathons and webinars I scraped 3 4 sites example devfolio, MLH, and hackerarth based on dates ignoring past hackathons using python. Further, This all fetched information of hackthons is stored in firestore 
Here python script will act as a server that will continuesly running to update itself with new hackthons. and all this new hackthon is fetch from the firestore and display on flutter app. When latest hackthon is upload on firestore then with the help of firebase function which triggers when new hackthon added and then notifies to users.
This app also allows hosting an event on various platforms.
## Getting Started

### Dependencies
## Getting Started

* Python 3.6
* Beautiful Soup : HTML Parser
* Flutter
* firebase

## Demonstration Video
<img src="https://github.com/disha2000/HackMe-The-Hackthons-Webinar-notification-App/blob/master/demo/demogif.gif" width="500" height="900" />


##Contributors names and contact info
* Disha Doshi:&nbsp;doshidisha555@gmail.com
