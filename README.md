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

 # 説明
5以下の数字が入力された場合、入力した数字の数だけLEDを点滅させる。

    & echo 1 > /dev/myled0

6以上の数字が入力された場合、点滅をしないでカーネルにメッセージを出力する。

    $ echo 2 > /dev/myled0

 # 実行参考動画
https://youtu.be/vp-5vF9OgAc

 # License]
 GPLv3 license
 
