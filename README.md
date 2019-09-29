# Phone saber

For some reason I cannot push to this repo, so created in gitlab where I usually create my projects.
https://gitlab.com/noobtiger/beatysabery

Make sure that you are going to HTTPS on both desktop and mobile https://beatysabery.herokuapp.com/

Please use chrome both on desktop and android for trying the game out, device sensor browser APIs are only available in chrome android.

![Phone Saber](http://i.imgur.com/4G9UHByl.jpg)


This project idea is inspired by the VR game Beat saber. I was curious to see if I can do a similar game like that but with smartphone as the controller. I initially thought I will be able to pair with bluetooth, unfortunately bluetooth support is not available in browser yet. So I created a small nodeJS server and the phone sends its sensor data via websockets to the desktop browser or wherever you have the game running.
