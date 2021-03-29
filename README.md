# Foglia Design VI

This is a repository for ECE 322 - Design VI <br /> <br />

The work contained in this repository is primarily tailored to use with a Raspberry PI, or other Linux machines. <br />
There is also work involving remote connection from my Windows 10 laptop to the Raspberry PI via Secure Shell (SSH) and a remote desktop service (VNC Server).  <br />


# Lab 1

The Lab1 directory contains my custom startup_mailer.py script when sends me a personalized email to my inbox when the script is run, which happens automatically at startup due to a call to it in the file '/etc/rc.local'. The directory also contains screenshots of the email received from the mailer script, as well as sccreenshot of an active connection from my laptop to the vnc server running on the PI (remote desktop service). <br />


# Lab 2 

The Lab2 directory just contains a screenshot of minicom running on the PI. The rest of the lab I couldn't complete because I do not have access to a breadboard or the other components required. 


# Lab 3 

The Lab3 directory contains various scripts and screenshots, including Python scripts for querying system info and sending an email.  Additionally I benchmarked some python scripts using time.c. Standard Python seems to be the fasted, followed closely by Python3. PyPy is the slowest environment. I was able to get Doxygen working correctly. Parts B and D I could not complete because I dont have the breadboard and other components. Everything else was completed. 


# Lab 4

The Lab4 directory contains Lab 4 in its entirety excluding the Django projects that require sensors. The Stevens weather was working properly except for the live map. I generated and used a Google API key but for some unknown reason this didn't fix the map issue. Other than that, the site was working and I could access it from another computer on my network. The same goes for the myraspi Django REST site. I also got the Alexa Skill Kit to work properly.  The Apache server was also running properly. I did run into some issues while generating the Wordpress configuration and running the installation,  but I think it was working properly in the end. Screenshots are available in this directory. 


# Lab 5

Lab 5 was completed entirely. I got the crossbar.io site up and running fine. Additionally the publish and subscript clients were working fine on the Pi. Eclipse Mosquitto and Eclipse Paho were also working properly. The messages were sent successfully and showed in the terminal, as shown in the screenshots available in this directory. 


# Lab 6

The Lab6 directory contains just screenshots. All parts of the lab were completed successfully. Node-RED was working and I could access the 'Hello World' page from another laptop on my network. Pystache was also working, and it correctly updated every time I refreshed the page. I set up a Particle Cloud Account and was able to communicate between the mobile app and the pi. 


# Lab 7

Lab 7 was completed in its entirety. Thingspeak was working fine. I choose not to save the API key on disk for future use because I didn't want it in the GitHub repo anyway. For the Google Cloud Platform components, everything was working. The Google Sheets document was being updated. One thing I noticed is that my JSON API key didn't begin with 'rpidata-", but rather 'main-' which seemed strange considering I named the project rpidata. Nonetheless, the API key worked properly. 
