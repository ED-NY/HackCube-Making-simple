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
 综上，我选择了自己画个pcb板，平衡美观成本焊接难度的问题<br>
 值得一提的是原版的hackcube-special体积虽然小但是cc1101模块的信号距离比较近，所以，我在画pcb的时候对这个模块采用了ipex天线的形式<br>
 经过我自己的测试信号扩大了很多。<br>
 由于在原版的代码里关于2.4g模块的代码注释掉了，所以我在画pcb的时候没有考虑添加nrf24l01模块<br>
 如果后期在原项目里有添加我会重新画板。<br>
 这个板子是二层板长57mm宽31mm与一块esp8266模块带ch340串口的一样，方便组装<br>
 分为顶板和底板两个部分在jlc制作才5人民币。顶板主要是cc1101模块，arduino，状态灯等<br>
 底板比较简单没有接线，留下了低频天线位和模块位，这也是这个pcb的不足之处，只能通过飞线建立模块与arduino的链接，后续我会修改。<br>
 下面是以上文字的英语
Here is the English of the above words.<br>
 


 

