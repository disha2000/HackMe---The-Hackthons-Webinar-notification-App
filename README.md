# Hackme - The Hackthons/Webinars notification App

## Overview

We have many websites that notify the current hackathons like MLH, and devfolio but for mobile devices, there is no such app for this. So for this, I have built the app using flutter that will keep users updated with the latest hackathons. To get all information related to upcoming hackathons and webinars I scraped 3 and 4 sites example devfolio, MLH, and HackerEarth based on dates ignoring past hackathons using python. Further, This all fetched information of hackathons is stored in firestore 
Here python script will act as a server that will continue running to update itself with new hackathons. and all this new hackathon is fetched from the firestore and displayed on the flutter app. When the latest hackathon is uploaded on firestore then with the help of firebase function which triggers when a new hackathon is added and then notifies to users.
This app also allows hosting an event on various platforms.
## Getting Started

### Dependencies
## Getting Started

* Python 3.6
* Beautiful Soup : HTML Parser
* Flutter
* firebase

## Demonstration Video
<img src="https://github.com/disha2000/HackMe-The-Hackthons-Webinar-notification-App/blob/master/demo/demogif.gif" width="250" height="500" />


## Contributors' names and contact info
* Disha Doshi:&nbsp;doshidisha555@gmail.com
