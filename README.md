# esp32_game

用的是micropython编写的，所以这个固件包含了micropython和我的py代码
烧录完毕后可以在thonny这个软件（其它软件也可）中查看源码


# --------------------
默认的接口是： OLED:
                  scl -->p22
                  sda -->p21
              电位器:
                  out -->p36
# --------------------
游戏有两个操控方法：按键操控和电位器操控（电位器里也可以用按键辅助操作）
开始界面按下p32开始游戏，按下p33进入设置（里面可以选择按键和电位器操作）
# --------------------
游戏内容就是躲避从上方飞来的原点
