# HackCube-Making-simple
 相信hacknown的产品hackcube special引起了许多无线电安全爱好者的关注，当然我也是，hackcube-special是360团队的一个开源项目 <br>
 附下链接：https：//github.com/UnicornTeam/HackCube-special <br>
 这个项目是hackcube（大的）的简化版，好多的功能实现不了，但是hackcube作为一个无线电安全产品来讲是很棒的。<br>
 hackcube-specialke可以实现badusb功能通过arduino pro mical <br>
 可以实现对433 315信号的干扰，录听，重放功能，还可以分析滚动码，但是这个功能没有什么明显的用途，滚动码的复杂程度大家都是知道的，这些功能的实现通过cc101模块<br>
 还有低频卡的模拟，爆破，写卡功能通过em模块<br>
 还有2.4g信号的一个模块nrf24l01这部分功能在arduino的源码里存在但是在esp8266的web里注释掉了<br>
 功能在unicornteam的项目地址里有很明确的说明<br>
 好了，废话不多说。<br>
 这个储存库是我自制的pcb板，方便diy，还有就是hackcube-special已经销售尽了，但是好多人没有买到，自己看了一下项目有pcb文件<br>
 用的是四层板加上；元件；外壳；贴片焊接；钢网；成本可想而知，其实可以根据社区里的图买模块来自己焊接，缺点是不美观。<br>
 ![image](
 综上，我选择了自己画个pcb板，平衡美观成本焊接难度的问题<br>
 值得一提的是原版的hackcube-special体积虽然小但是cc1101模块的信号距离比较近，所以，我在画pcb的时候对这个模块采用了ipex天线的形式<br>
 经过我自己的测试信号扩大了很多。<br>
 由于在原版的代码里关于2.4g模块的代码注释掉了，所以我在画pcb的时候没有考虑添加nrf24l01模块<br>
 如果后期在原项目里有添加我会重新画板。<br>
 这个板子是二层板长57mm宽31mm与一块esp8266模块带ch340串口的一样，方便组装<br>
 分为顶板和底板两个部分在jlc制作才5人民币.
 ![image](https://github.com/ED-NY/HackCube-Making-simple/blob/master/up.jpg)
 ![image](
 顶板主要是cc1101模块，arduino，状态灯等<br>
![image](
![image](
 底板比较简单没有接线，留下了低频天线位和模块位，这也是这个pcb的不足之处，只能通过飞线建立模块与arduino的链接，后续我会修改。<br>
 下面是以上文字的英语
Here is the English of the above words.<br>
 It is believed that hackcube special, a hacknown product, has attracted the attention of many radio security enthusiasts. Of course, I am also an open source project of 360 team.<br>

The following link is attached: https://github.com/unicornteam/hackcube-special <br>

This project is a simplified version of hackcube (large), many functions can't be realized, but as a radio security product, hackcube is great. <br>

Hackcube specialke can realize badusb function through Arduino Pro micro <br>

It can interfere with 4338 *315 signals, record, listen, replay, and analyze the scroll code. However, this function has no obvious purpose. The complexity of the scroll code is well known. The realization of these functions is realized through CC101 module <br>

There are also low-frequency card simulation, blasting, card writing functions through the EM module <br>



There is also a 2.4G signal module, nRF24L01, which exists in the source code of Arduino but has been commented out in the web of esp8266

The function is clearly stated in the project address of unicorenteam <br>

Well, there's no more bullshit. <br>

This repository is my self-made PCB board, which is convenient for DIY. In addition, hackcube special has been sold out, but many people haven't bought it. I have seen that the project has PCB files <br>

It uses four layers of boards plus; components; shell; patch welding; steel mesh; the cost can be imagined, in fact, it can buy modules according to the community's drawings to weld itself, the disadvantage is not beautiful. <br>

To sum up, I chose to draw a PCB to balance the cost of beauty and the difficulty of welding

It is worth mentioning that although the original hackcube special is small in size, the signal distance of cc1101 module is relatively close, so I used the form of IPEX antenna for this module when drawing PCB <br>

After my own test signal expanded a lot. <br>

Because the code about 2.4G module is commented out in the original code, I did not consider adding nRF24L01 module when drawing PCB <br>

If there is any addition in the original project later, I will redraw the board. <br>

This board is 57mm long and 31mm wide. It is the same as an esp8266 module with ch340 serial port. It is easy to assemble

It is divided into two parts: the top plate and the bottom plate, which are only 5 RMB in JLC. The top plate is mainly cc1101 module, Arduino, status light, etc. <br>

The backplane is relatively simple without wiring, leaving the low-frequency antenna bit and module bit, which is also the disadvantage of this PCB. Only through the Flywire to establish the link between the module and Arduino, I will modify later. <br>


 

