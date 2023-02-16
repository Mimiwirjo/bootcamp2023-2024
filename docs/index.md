##mi-ann made changes again
I love someone
About me

My name is Mi-ann Wirjosentono. I am from Santo Boma,Wanica and. I am currently 17 years old and I will be starting my second year of VWO. 

![](https://lh6.googleusercontent.com/vvrq8colqale10AmB0lF_pn1QCbEpq_xd2HBcTv21lDSEjDLbY9a0zG3TA5iqwiwozoylSL1YpC-tDpvkahqYM1azyizSTi-IWdUYt5Lph30AGX52QtBs-m0YTVxTOFCpsoTjJN7GMrAjB6Pc2MJztw)

I applied for the program because I want to develop my skills and learn about coding and building things. My dad also liked to develop circuits in his spare time. I have always liked to learn things in my spare time and I like physics as well as reading and writing. I also like to things that are difficult to solve.

Day 1 September 5th 2022

Objective:

introduction:

Introduction to the 3 types of circuits and its components

Introduction to Arduino

Build a basic blinking led

Component list:

AAA 1.5 V battery

9V battery 

resistors 

diode

led 

breadboard

multimeter

Arduino uno

Pushbutton

Circuits

First there was a quick review on what electricity was and referred to as water on a mountain.

Electricity consists of current, potential energy and resistance.

the law potential energy is equal to the current times the resistance.

 We were introduced to the follwing 3 types of circuits:

1.  Simple circuit

2.  serie circuit

3.  parallel circuit

4.  arduino circuit

1.  Simple circuit

Here I learned how to select three AAA 1.5V batteries on tinkercad and to couple it to a led. A resistor must be placed between the anode and positive pole of the battery to prevent it from blowing up.

1.  Serie circuit

Here I used a 9V battery and 3 led lights. I coupled the leds together by connecting the anode of one led to the cathode of the other. I then coupled the free anode to the positive pole via a resistor and the free cathode to the negative pole of the battery.

3  parallel circuit

Here I once again used a 9V battery and 3 lights. However I coupled a diode with the positie pole to let the current flow in only one direction. From the diode I placed 3 separate cables each going to a cathode of a led. Then I placed another diode and coupled 3 seperate cables to for the cathode of each led. This diode I then coupled to the negative pole of the battery

Then I used a breadboard and a multimeter to check the resistance of the resistors. I was taught how to check the resistance of resistors of both parallel and serie circuit situations

4\. Arduino Circuit

I used an arduino uno R3 and a breadboard. This I coupled with a potential energy of 5v from the power section to the bottom of the breadboard with the plus sign.and groundpin to the bottom of the breadboard where the minus sign is. In the row where the groundpin is connected I placed a resistor and placed a led in the upper row of the 3rd section of the breadboard with the cathode being in the same column as the resistor. From the Digital section I coupled number two with the bread board one row above the resistor in the column where the led's anode is.

![](https://lh6.googleusercontent.com/ixRebLrgx76dG2e-4HWwFvNUzS7BzyccIF9lHyQJYF9yKq2FFZIVqUz-kGNsNTFfHT932MgD-ISfV_F27N-B3mg6V8LxcZTDyZZcHwX1D2YGie6zms9963IU6M9nmAjoXT5Wi7470YGGFSVU3tbL_nk)

Then I added a pushbutton. Terminal 1a and 2a were in same row as the led light but 7 coloms away from it  To connect this I connected the positive cable of bottom section to the top section's plus sign row aswell with the negative cable to the top section's minus sign row. In the row of the latter I placed a resistor horizontally in the same colomn as terminal 2b  and parallel to it as well as evenly long I placed a cable in the colomn of terminal 1b.

Then I typed the code to make the light turn on and flicker.

Code

int led = 2;

int button= 3;

void setup () {

pinMode (led,  OUTPUT);

pinMode(button.  INPUT);

}

void loop () {

if (digitalRead(button)== High)

{

digitalWrite (led, HIGH);

delay (500) 

digitalWrite (led, LOW);

delay (500)

}

else 

{digitalWrite (led,  HIGH);

}

}

mistakes:

I coupled the cables wrong a couple times during the arduino circuit because i didnt fully understand what I was doing. During coding I also made some mistakes Sometimes I accidentally deleted the entire lines of code and sometimes I forgot the curly brackets or ";" sometimes I pressed "shift+:" sometimes I forgot how to continue editing a design after accidentally leaving.

note to self: edit = press tinker
