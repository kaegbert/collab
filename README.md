# photocell-synthesis
Progress towards sound as a product of light...

### get p5bots server
####(you'll need node / node package manager for this...)
1. Open Terminal.
2. Install p5bots-server by running: `npm install -g p5bots-server`


```bots-go -d YOUR/PATH/GOES/HERE```

##### project description
This project uses sarahgp's [p5bots](https://github.com/sarahgp/p5bots) library as well as the p5 sound library to generate a tone based off the value of a photo resistor. The resistance value of the photocell also triggers mp3 samples when a certain threshold is broken.

##### what to do next...

1. calibrate - cannot rely environment to be stable. Use key commands to "sample" current resistance value and create threshold based of these values...

#### setup details

#### upload firmata to arduino

1. Download the [Arduino IDE](https://www.arduino.cc/en/main/software) if you don't have it...
2. Upload `File > Examples > Firmata > StandardFirmata` to your board. To do this, you'll have to select your board and serial port from the `Tools` menu. ([More instructions from Arduino.](https://www.arduino.cc/en/Guide/MacOSX))
3. Write down the port your board is using; you may need it later.

Install [node](https://nodejs.org/)

### Get p5.js, p5.bots, p5.sound
1. [Download `p5.js`.](https://github.com/processing/p5.js/releases/download/0.4.8/p5.zip)
2. [Download `p5.bots`.](https://raw.githubusercontent.com/sarahgp/p5bots/master/lib/p5bots.js)
3. [Download `p5.sound`.](https://github.com/processing/p5.js-sound)
