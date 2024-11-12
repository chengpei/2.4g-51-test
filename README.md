# 2.4g-51-test
51单片机使用NRF24L01进行2.4G无线通信

主要逻辑是初始化，设置为接收模式，循环读状态寄存器判断是否可读，读出数据到读缓冲区，如果按钮P3^5被按下，则设置发送模式发送0x31，然后切回接收模式，如果你有两套51单片机加NRF24L01可以烧录进去进行读写测试，详情内容可以查看我的博文：[https://www.chengpei.top/archives/51-nrf24l01](https://www.chengpei.top/archives/51-nrf24l01)
