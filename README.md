# ALX_SIM_D1_Skll

PART 1 Installing Alexa on RaspBerry Pi

Alexa Skill Smart Home with Simric Smart Home Skill

Here you can find all of the files used in the Videotutorial

Hardware Used: 

1. Rapberry Pi Device: https://www.amazon.de/Raspberry-Pi-Model-ARM-Cortex-A53-Bluetooth/dp/B01CD5VC92/ref=sr_1_4?ie=UTF8&qid=1539344592&sr=8-4&keywords=raspberry+pi

2. USB Microphone: https://www.amazon.de/Sienoc-Mikrofon-Stecker-Sprachaufnahme-Schwarz/dp/B00XU1GHO4/ref=sr_1_10?s=computers&ie=UTF8&qid=1539344726&sr=1-10&keywords=USB+Microphone

3. Mini SD - Card: https://www.amazon.de/Samsung-Micro-Class-Speicherkarte-Adapter/dp/B06XFSZGCC/ref=sr_1_4?s=computers&ie=UTF8&qid=1539344792&sr=1-4&keywords=Mini+SD+Karte

4. Loudspeakers: https://www.amazon.de/ARCTIC-S111-Mini-Soundsystem-%C3%BCberzeugender-Klangqualit%C3%A4t/dp/B00KR4J276/ref=sr_1_11?s=computers&ie=UTF8&qid=1539344849&sr=1-11&keywords=Lautsprecher%2Bmit%2BKabel&th=1

5. Wemos D1 Mini Clone: https://www.ebay.de/itm/D1-Mini-ESP8266-WLAN-Mikrokontroller-Wifi-Nodemcu-Modul-Board-Wemos-Arduino/252745698566?hash=item3ad8d14d06:g:0WgAAOSwnw9aD2pQ:rk:1:pf:0

LED, Resistors, Breadboard and Wires you can buy in every good Electronic shop.



Links to Sources and Provider:

1. Amazon Developer Account: developer.amazon.com 
2. Raspian ISO File : https://downloads.raspberrypi.org/raspbian_latest
3. WinDisk32 Imager to transfer Image to SD Card: https://sourceforge.net/projects/win32diskimager/

Installations and Commands
To install the Alexa demo App on Raspberry Pi : git clone https://github.com/alexa/alexa-avs-sample-app.git

To edit config file:
cd ~/alexa-avs-sample-app
sudo nano automated_install.sh

Start the Script:

cd ~/alexa-avs-sample-app
. automated_install.sh

***** This could take till 30 minutes*****

Start for the firs Time from a Terminal:

cd ~/alexa-avs-sample-app/samples/companionService && npm start

Start GUI from 2nd Terminal:

cd ~/alexa-avs-sample-app/samples/javaclient && mvn exec:exec

Start Voice recognition:

cd ~/alexa-avs-sample-app/samples/wakeWordAgent/src && ./wakeWordAgent -e sensory



Now it should work on Raspberry :-)

Part 2 Getting your DIY-Chip running:

Alexa App for Android: https://play.google.com/store/apps/details?id=com.amazon.dee.app
Alexa App for Apple Devices: In the Apple Store U can search for it.

Sinric Smart Home Skill for Alexa:www.sinric.com
Alexa Web App: https://alexa.amazon.de

Now you have all the links what you need to do the tutorial.

Feel free to comment...






