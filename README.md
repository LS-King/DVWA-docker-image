# Introduction
This repository contains all you need to build a DVWA docker image.
# Version info
Sys: Debian 10
PHP: 7.3
DVWA: 1.10 (Development) Updated in Jun. 2021
# A builded image
You can directly download the image I have builded in "Releases".
# Out of date ?
Just replace the "dvwa" folder with the new one published on [DVWA Official](https://github.com/digininja/DVWA).
Maybe you also have to change the copy direction of "php.ini" in Dockerfile because each version of PHP7 create its own config folder. 
