# reactriot2019-noobtiger

For some reason I cannot push to this repo, so created in gitlab where I usually create my projects.
https://gitlab.com/noobtiger/beatysabery

Make sure that you are going to HTTPS on both desktop and mobile https://beatysabery.herokuapp.com/

I used chrome both on desktop and android for testing, device sensor browser APIS are only available in chrome android. If you  want to try out the game, you can only use chrome browser on an Android device.

![Phone Saber](http://i.imgur.com/4G9UHByl.jpg)


This project idea is inspired by the VR game Beat saber. I was curious to see if I can do a similar game like that but with your smartphone as the controller. I initally thought I will be able to pair with bluetooth, unforuntely bluetooth support is not avaibale in browser yet. So I created a small nodeJS server with web sockets and the phone will send its sensor data via sockets to the desktop browser or wherever you have the game running. 
