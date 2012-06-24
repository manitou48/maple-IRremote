port of Arduino IRremote lib to maple
  see http://www.arcfn.com/2009/08/multi-protocol-infrared-remote-library.html
       https://github.com/shirriff/Arduino-IRremote

uses PWM on pin 24, timer 4/channel 4  (maple RET6) varies by board
   recv on pin 8, uses timer2/channel to do 50us samples

limited testing with Sony remote/VCR

examples/ need to fix pin number and Serial to SerialUSB

