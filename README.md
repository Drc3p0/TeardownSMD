## Teardown SMD Challenge

With the rise of the [SMD challenge boards](https://hackaday.com/2019/11/18/a-newbie-takes-the-smd-challenge-at-supercon/), we thought that the layout would work perfectly with our "90's abandoned mall" vaporwave design for [Teardown 2024](https://www.crowdsupply.com/teardown/portland-2024)! Thanks to the support from [OshPark](https://oshpark.com/), [MakersBox](https://www.tindie.com/stores/makersbox/), [Crowd Supply](https://www.crowdsupply.com/), and [Mouser](https://www.mouser.com/), we bring you the *Teardown 2024 SMD Challenge*. 

<img width="283" alt="Screenshot 2024-06-12 at 2 56 26 PM" src="https://github.com/Drc3p0/TeardownSMD/assets/5934416/f1f2bea6-d3bd-458e-b79d-878ee8acabda">

This hexagonal PCB comes in two flavors: *Courtesy* edition and *Cursed* edition. The *Courtesy* edition uses pads meant for hand-soldering, and with the sizes going down to 0201, it's plenty challenging on its own! 
But if that's not enough, the *Cursed* edition has smaller SMD pads for those who want an even more impossible challenge. 

This SMD challenge layout and concept came from the famous design by [MakersBox](https://www.tindie.com/stores/makersbox/). Support their work by buying one of their OG SMD Challenge boards [here](https://www.tindie.com/products/MakersBox/smd-challenge/)!

New to SMD soldering? You'll want to practice on something much more reasonable than this design. Check out this video to better understand what you're getting yourself into.. 

https://www.youtube.com/watch?v=8Q6YNmBKjiU

### Tools Needed:
- Fine-tip soldering iron
- Solder
- Plenty o' flux
- Fine-tip tweezers
- Probably a magnifying device of some kind
- Spare dose of sanity (or lack thereof)

We would say use a hot plate or heat gun, but that takes too much of the challenge out of it ;)

### Components

You may need to look at the Datasheets to see what the correct orientation of the LEDs looks like.. 
Refer to the [Components list](https://github.com/Drc3p0/TeardownSMD/blob/main/Components.md) for links. 

This SMD LED polarity photo reference guide will be helpful too: https://lighthouseleds.com/blog/polarity-guide-of-0402-0603-0805-1206-and-most-all-smd-leds.html 

### Firmware

Code for the Attiny is the same as the OG SMD Challenge boards: 

https://raw.githubusercontent.com/aspro648/KiCad/master/projects/Attiny/Attiny85Challenge/firmware/SMD_challenge_Cylon/SMD_challenge_Cylon.ino

Instructions for using the Sparkfun tiny programmer for uploading code to the Attiny: https://docs.google.com/document/d/1_V8jWTGxLiAL2kk-nU6e-c7un_Uen9MeraUU5jMNWxs/edit?usp=sharing 
