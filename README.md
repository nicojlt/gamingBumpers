# gamingBumpers
a fun way to practice with little light-up bumpers

## what ?
The goal of this project is to create a simple and cheap light bumpers systems.

### origin of the projet
today my wife saw a facebook add for BlasePODS, and instantly wanted it.
then she saw the price ;
Then I saw the product :)
and it's clear that it's quite simple to create...

### have it been done ?
I didn't find many sources.
* the best so far was https://www.instagram.com/projectswithalex/ 's one (https://github.com/projectswithalex/Reaction-Lights-Training-Module)
* a wired project https://create.arduino.cc/projecthub/science-camp/light-trainer-55eb60 
* an interesting projet which seems nipped in the bud (thanks google translate for the expression, in France we say "killed in the egg" !)  https://www.youtube.com/watch?v=aLupsy850e0

### concept
I thing it would be cool to have a master pad for confirguration and on screen score display (that may be wired), and 3 to 6 wireless pads.

### electronics
At first glance: 
_main board_
** ESP32 board 
_captors_
* infrared proximity captors
* maybe piezzo mics for vibration detection
* maybe a dedicated mic for the master, to get music beats
_user interfaces_
* RGB leds to be defined for the satellites
* maybe a small screen or a RGB matrix for the master
_power_ 
* usb power suppy for the master
* l18560 batteries for the satellites (i love those !)

## functionnalities

* "get the light" : one of the satellites lights on, and stay until user interaction, then another one lights. gaming example : how many time did it takes to punch 10 lights ?
* "music beats" : the light change every detected music beat, the screen continiously display the average of the xx last beats
* ... _to be continued_

## when ?
well... I thin I'll start on T4 2022.
Then why start this project now ?
to save ideas and needs !
