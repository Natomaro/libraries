# libraries
the libraries in my program filesx86/arduino/ that enable the ec reading and calibration scripts and the aforementioned scripts themselves


I got these to work in Arduino by placing Arduino-Temperature-Control-Library-master and OneWireNoResistor-master
into the libraries directory in Arduino.

the other two folders contain the actual .ino files to run - calibration_ec.ino and ec_rig_main_code.ino. They just
need to be somewhere within the same program files directory for Arduino (I just happened to leave my in the libraries directory 
before this, hence why the are also in this repo labelled "libraries". 

I excluded all of my other Arduino libraries that were in this directory for clarity.
