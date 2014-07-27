johnny-five-intro
=================

flashing led and web controls over server

Simple LED controll and web page,


Install
=======

1. Get NodeJS and NPM installed, and follow johnny-five install instructions.
2. Clone this repo, and cd into the folder.
3. Run ```npm install```
4. Run ```node index```
4. Wire up leds to pins 5 and 6 on your Arduino
5. Open a browser and go to ```http://localhost:3000```
6. Win!


Bonus: control via mobile
===========================

*Run the server following steps above*

1. got to command line on your pc and type ```ipconfig``` look for your wireless ipv4 address.
2. on a mobile device (on the same wifi network) go to that ipv4 address and add :3000 to the end.
3. Magic!
