# JCtp
期货公司，期货行情接入， 包含交易穿透式监管验证

该项目主要用于接收期货行情,所有的合约列举在`resources\futures.yml`文件中，如果想要添加订阅的合约，请按格式加入
在启动时，直接扫描文件中所有的合约，并计算出该合约往后12月内的symbol，然后在进行订阅
s
