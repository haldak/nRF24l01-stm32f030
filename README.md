﻿# nRF24l01-stm32f030
电设18通讯板
2016.9.12 收发调试成功！

小结：
先调发送，关闭ACK和自动重发，直到发送后STATUS变为0x2e,FIFO_STATUS为0x11说明发送成功；

然后调接收，同样关闭自动应答，刚才卡了半天都是因为这个忘关了……

虽然调试这版忘留串口了，但这并不影响我用一个LED闪啊闪debug成功~而且好处是，这样一旦成功，瞬间反馈，心情大好，效果拔群！

下一步就是写串口通讯协议啦~甩锅甩锅^ω^