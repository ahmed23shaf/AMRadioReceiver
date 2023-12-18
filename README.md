# Superheterodyne AM Radio Receiver
Based off the following model below, I created 3 main sub circuits (envelope detector, amplifiers, band pass filter) which comprise the essential building blocks of an AM receiver.  

![image](https://github.com/ahmed23shaf/AMRadioReceiver/assets/112600024/56f29657-7136-4dd5-9fa4-75af0b416f66)

## (1) Envelope Detector
The envelope detector circuit takes in an AM radio input signal and outputs the resulting message signal by demodulating it using non-linear circuit devices.

![image](https://github.com/ahmed23shaf/AMRadioReceiver/assets/112600024/d3ca52fa-c431-469a-97e9-9af1ca05d5a6)

## (2) Amplifiers
To ensure that our envelope detector circuit sufficiently recovers the message signal, it is imperative that our incoming input signal is large enough (hence the left amplifier). The other amplifier acts as a buffer which removes any delay from the time constant of the envelope detector and also drives the output of the loudspeaker.

![image](https://github.com/ahmed23shaf/AMRadioReceiver/assets/112600024/601b2b4d-5f40-45f8-ae16-8829e9aa1063)

## (3) Band Pass Filter
The specific filter implements a type of IF (intermediate frequency) filter which only selects signals on the IF frequency range. 

![image](https://github.com/ahmed23shaf/AMRadioReceiver/assets/112600024/dd7f07ab-4677-4015-985d-1e3129b1f052)

# Fully Assembled Circuit

![image](https://github.com/ahmed23shaf/AMRadioReceiver/assets/112600024/7f4a6349-cc12-40c9-ace0-47407e42b0ad)


![image](https://github.com/ahmed23shaf/AMRadioReceiver/assets/112600024/fafdfb3c-7e9e-43a2-bead-482e72d33614)


![image](https://github.com/ahmed23shaf/AMRadioReceiver/assets/112600024/fec349eb-c9c9-48e0-9cec-32573c98696f)

