# CONTRIBUTOR

(c) 2020 RyuichiUeda and SoutaNakamura

# RobotDeviceDriver

2020年CITロボットシステム学課題１として作成したデバイスドライバーです。
入力によってLEDを点滅させます。

# 実行方法
    $ git clone https://github.com/aprsoshan/RobotDeviceDriver-.git
    $ cd RobotDeviceDriver- 
    $ make
    $ sudo insmod myled.ko
    $ sudo chmod 666 /dev/myled0
