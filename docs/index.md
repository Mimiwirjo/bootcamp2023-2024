Day 1 Friday 10 february 2023
==========

Objective:
==========

-   graduation requirements

-   project management

hands on
--------

previous steps done before the lesson:

-   signed up for github account

https://github.com/

-   downloaded Notepad++

<https://notepad-plus-plus.org/downloads/v8.4.9/>

-   downloaded Github Desktop

[https://desktop.github.com/ ](https://desktop.github.com/)

start of class download

to manage our projects we are using github.

github:

-   system keeps track of changes of files 

-   Automatically merges code together so that there is no conflict between codes.

1.  went on online github account then went  to plus icon on top right corner. Clicked "new repository"

-   named repository "Bootcamp 2023-2024", pressed green "create repository button"

went to  to -> [CB_Project_Management_Github](https://docs.google.com/presentation/d/1FARWTSs0OG99aUsmFXXkM_LHZ4ugUkLEY7SosxUjvNA/edit#slide=id.g1dcbd7600c3_0_40)

slide 4 find : Clone Repo <https://drive.google.com/drive/folders/1rEbBA5UYhnrQrHGsEiU3D2dWEZyIuBi2?usp=sharing>

-   download files -> unzip

documents -> GitHub -> 

-   docs-> index.md

-   gitignore

-   gitlab-ci

-   mkdocs

went to online github:

-   screen shows blue screen with quick setup written in the beginning. Link to repository is seen near "https"

-   Copied address link

1.  went to github desktop:

-   went to File → went to Clone Repository → went to Url

-   Pasted address Link

-   went to Github Folder on Desktop (Documents → Github)

-   pressed blue button "clone"

-   find local repository {Documents → Github -> docs ->index.md)

1.  Synced with Github Desktop

-   Made changes in index.md →saved

-   Synced to Github Desktop

-   Committted with Text (e.g. commit or change)

-   pressed green button " Push"

1.  Online Repo

went to online github  -> went to settings icon (right corner)

Settings changed to general → went to pages →

Branch →pressed " Main"

Folder -> pressed "Docs"

Saved

1.  waited 5 minutes -> llink appeared where site would appear

 <https://mimiwirjo.github.io/bootcamp2023-2024/>

1.  Convert Doc to MarkDown

went to google docs-> innostarter document -> copied documet

Use [DOCS TO MARKDOWN](https://euangoddard.github.io/clipboard2markdown/) to convert Google Docs to Markdown

-   Install Markdown Plugin

-   Paste Mkdoc into notepad++

-   Preview using plugin

repository local vs remote

local repository on computer

remote repository is online

make changes to local repository and then push the change to remote repository

github will compare the local repository with the remote  repository then changes anything in the remote repository that changed in the local repository

Vice versa when changing the repository online one can pull the online repository into the local repository. Github will then compare local with remote repository and change anything in the local repository that has been changed in the remote  one.

github tracks history of commits

commit: checkpoint or  change(s) made on local machine are saved and stored with  a certain point in time. It stores data on the  repository and indicates the time the changes were made.







DAY 2 Friday 16 february 2023
==========


objective:
==========

-setup esp32

-using api

components list:
================

USBC Cable

esp 32

Led

resistor

Cables

breadboard

Hands on
========

Communication protocol

http Vs websocket

today we use http

go to slide 8 google presentation -> press <https://randomnerdtutorials.com/esp32-web-server-spiffs-spi-flash-file-system/>

short explanation on html5 , its basic page and cc3

steps done before class:

-   made sure arduino IDE 1.8.19 is downloaded

-   set up circuit

Setting up esp32

install ESP32 board in your Arduino IDE

1.  In your Arduino IDE, go to File> Preferences.

2.  Enter into the "Additional Board Manager URLs" field`

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json

1.  Open the Boards Manager. Go to Tools > Board > Boards Manager...

2.  Search for ESP32 and press install button for the "ESP32 by Espressif Systems" select version 2.02 (not higher) -> Install or Update

-go to slide 6 of google presentation

5.spiff

Press [Download Jar](https://github.com/me-no-dev/arduino-esp32fs-plugin/releases/) ,press code -> green button"code"

extract "jar file"  to arduino/tools

-   arduino files download asyncwebserver

<https://github.com/me-no-dev/ESPAsyncWebServer>

-download asyncTCP

<https://drive.google.com/drive/folders/184_RwUj3iOGNeZ4GtvciJrSK2s-s0FCY?usp=sharing> 

Delete Double WIFI.H LIB

create folder "coddetesbootcamp 2023" in "documents"

press: [Download Files](https://github.com/RuiSantosdotme/ESP32-Course/raw/master/code/SPIFFS/ESP32_Async_Web_Server.zip/) 

unzip in "codettesbootcamp2023

-open arduino file in async wbserver 

- go to tools open boards: board manager: esp32 arduino: Esp32 dev module

important libraries to use webserver that will appear in file

#include "WiFi.h"

#include "ESPAsyncWebServer.h"

#include "SPIFFS.h"

under this find :

const char* ssid = "fill in Wifi name";

const char* password = "fill in password"

-compile file

connect esp32 to laptop with usbc cable

-select port ; change upload speed to: 115200

-upload file 

-open serial monitor; change baud to: 115200

 press left button on esp 32 if left doesnt work press right

Serial monitor will show code like : 192.168.100.149

-copy code, paste into omnibox/addresbar

something like this wlll appear:

![](https://lh3.googleusercontent.com/tTbEG7KU09SKKyGXh8iuFJY1LGhQaJWCcu60PZqWmeQjh1e3p-AfKrs4az6bIrr99pRIXsR4VdZ6AeUMOXvblTlzja3UeuiaGvRhPwJ1sR-coZMU0vR9OtEn7EuClslgfgt1p2qV4jiOiXRVBoOoePk)on is lamp on 0ff is lamp off







Day 3 Friday 24 february 2023
==========


objective:
==========

review last lesson

api vs websocket

html5 & css 

-multi sliders pwm

esp 32 web server

architecture

components list:
================

-breadboard 

-led *3

- resistor*3

-wires*4

-esp 32

-usbc capbles

To build this project, you need to install the following libraries:

[Arduino_JSON library by Arduino version 0.1.0](https://github.com/arduino-libraries/Arduino_JSON) (Arduino Library Manager)

[ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer) (.zip folder);

[AsyncTCP](https://github.com/me-no-dev/AsyncTCP) (.zip folder).

notes taken during class:
=========================

api vs websocket

difference updates all the clients

itc all the browser

spiff upload files

index cml

html5

css

http request

websocket

fading pwm pins

potentiometer + lamp

potentiometer + led

duty cycle o = 0 faded 50= 50 faded

homework: pwm

how long we want it on ot off

sliders

eerie open tag has a closing tag

homework

ide

hands on
========

steps done before class:\
downloaded ; <https://github.com/arduino-libraries/Arduino_JSON>

extracted in: arduino/libraries

Circuit wiring:

![](https://lh5.googleusercontent.com/nak4PHKqc3tCr2h6vi5EpwwCYDcyhRmZ5VDJX_kGT7GH7Wtd4kPZSYech1-m_7ltiVyaouMmD7avEYm_kKXqW_0aIGF20jo_fWK9z4S3IJieefw1dEzWFAcDQ0Fye8IjWLAkmenQ5kzHEiC42CWvlq8)

-download [Download All the Arduino Project Files](https://github.com/RuiSantosdotme/Random-Nerd-Tutorials/raw/master/Projects/ESP32/ESP32_Multiple_Sliders_Web_Server/ESP32_Multiple_Sliders_Web_Server.zip)

and extract in  "codettebootcamp2023" code folder

*it contains: HTML, CSS, and JavaScript files

-   open arduino file from downloaded file 

-   go to: tools; board; board manager; esp 32 arduino; esp 32 de vmodule

-   upload speed 115200 

-   fill in  wifi name and password

-   compile, connect to laptop; upload,  esp 32 sketch data upload 

-   -pen serial monitor; press button on esp 32

-   copy ip address -> paste into omnibox

adjust brightness of leds

![](https://lh6.googleusercontent.com/gzYFzVWPD6VMYvT0sijohKn-jxiMc9IBZDbuBaeVh6KV5gNA1AWiYLhTUBSQj6Qlx-CGZAUyepZ3-FqMZfyHlmjbYpL2RiQLyJu8SSPEOpZdyg6O4PUPfoSBDAEc-pCU8L3bEHVbHsqgzJJEpakZ4UI)

1.  CHANGE BACKGROUND COLOR

2.  CHANGE HEADER AND HEADER COLOR

3.  ADD 1 MORE WIDGET 

4.  ADD ONE MORE LED (D2)

-right click mouse; press inspect

screen will appear like this: (minus the red background)

![](https://lh6.googleusercontent.com/rukDydVD0NggmmGnfHV6ib4oe2ogmwnt_lxUM0BFWzrnuKi2iSw-MxKaozCVLxkFYfHBfSztxqHUhO0_4mVlDPfxmtG06329V_kd_sVHy8jaTqTAGZOQ3YcQAiPXyR6FRdqrJIZevGUxpdyWJ5QAhTY)

go to elements; select body, go to styles  background write in  color 

right above is written where to change the code

-open style with notepad++ and go to designated line of code 

change background color to desired color