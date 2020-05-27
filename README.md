# HackCube-Making-simple
 
 It is believed that hackcube special, a hacknown product, has attracted the attention of many radio security enthusiasts. Of course, I am also an open source project of 360 team.<br>

The following link is attached: https://github.com/unicornteam/hackcube-special <br>

This project is a simplified version of hackcube (large), many functions can't be realized, but as a radio security product, hackcube is great. <br>

Hackcube specialke can realize badusb function through Arduino Pro micro <br>

It can interfere with 4338 *315 signals, record, listen, replay, and analyze the scroll code. However, this function has no obvious purpose. The complexity of the scroll code is well known. The realization of these functions is realized through CC101 module <br>

There are also low-frequency card simulation, blasting, card writing functions th



There is also a 2.4G signal module, nRF24L01, which exists in the source code of Arduino but has been commented out in the web of esp8266

The function is clearly stated in the project address of unicorenteam <br>

Well, there's no more bullshit. <br>

This repository is my self-made PCB board, which is convenient for DIY. In addition, hackcube special has been sold out, but many people haven't bought it. I have seen that the project has PCB files <br>

It uses four layers of boards plus; components; shell; patch welding; steel mesh; the cost can be imagined, in fact, it can buy modules according to the community's drawings to weld itself, the disadvantage is not beautiful. <br>

To sum up, I chose to draw a PCB to balance the cost of beauty and the difficulty of welding

Because the code about 2.4G module is commented out in the original code, I did not consider adding nRF24L01 module when drawing PCB <br>

If there is any addition in the original project later, I will redraw the board. <br>

This board is 57mm long and 31mm wide. It is the same as an esp8266 module with ch340 serial port. It is easy to assemble

It is divided into two parts: the top plate and the bottom plate, which are only 5 RMB in JLC. The top plate is mainly cc1101 module, Arduino, status light, etc. <br>

The backplane is relatively simple without wiring, leaving the low-frequency antenna bit and module bit, which is also the disadvantage of this PCB. Only through the Flywire to establish the link between the module and Arduino, I will modify later. <br>


 

