# DD_notes
DD_Notes 


English version 

Deface Detector was created to fill in the gap between active monitoring and passive monitoring 

Mostly for security related issues. 

The basic need of every web application developer or hosting is to know when the site is down...

So With that said, you can actually know when the site is down but you cant really know 

when your site was hacked or even defaced. 

By placing your monitors internaly or externaly you could have a basic idea if and when your site

has been compromisd, this is done by checking on a few factory which are mostly used on the xxxxxxxxx

The technique called html parsing  and here are some examples of what its actually applies on. 

1. partial http response like part of an expected code like a know javascripts or images. 

2.   Title of the webpage.     

3.   And even hashing the leanding URL with a hash value to check for diffrences.

Added to the project some example from a webUI 

This Small WEBUI was specialy created for this project and can litterly changeing the view/colors 

based on the status of the monitor...  Red / yellow / green

Main idea is to place the WEBUI view at some NOC/SOC facility as screen to watch and alert base on its result. 

For Siem integration we have created a full syslog connector that will upload the last time result to the

Siem collector in your Network.

All code is written with pyhton, for a Linux based environment

The WEBUI is an appatchy web server 

You can install it on by using a shell script. /install.sh and it will Automate the setup and extract of the files for you. 

