# malasong
基于深度学习的极简版无人车项目

# 设计（基于手头材料）
简述：DL(PaddlePaddle)>Macbook>Arduino>RC>GoProWirelessHack>DL(PaddlePaddle)
RC体积小，无法承载笔记本电脑，所以采用GoPro无线回传图像数据，电脑计算数据后通过Arduino控制RC遥控器修正路线，从而实现无人驾驶

# 示意图
![2017-01-16 17_08_32](https://cloud.githubusercontent.com/assets/25008736/22008757/eb9857e2-dcb8-11e6-992b-98aba37fdf42.gif)

## 参考：
- GoPro session 与计算机通信 https://github.com/KonradIT/goprowifihack
- 计算机与遥控车间通信、控制 https://github.com/iooiiooii/malasong/blob/master/car_run.ino
- 路况模型训练 https://github.com/paddlepaddle/paddle

## 已知问题
- GoPro回传延迟有2~3秒
