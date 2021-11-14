# 2021年第五届全国大学生FPGA创新设计竞赛
## PYNQ—隔空书写
### Server

- server_tcp.ipynb 使用tcp传输时，服务器端的代码
- server_tcp_udp.ipynb 使用tcp+udp传输时，服务器端的代码

### Client

- client_tcp.ipynb 使用tcp传输时，PYNQ端的代码
- client_tcp_udp.ipynb 使用tcp+udp传输时，PYNQ端的代码

### data

- data/Original  原始数据

- data/Original/Training 训练集

- data/Original/Test 测试集

### 主路径

- Label_Hands_detection.ipynb 采集训练集标记
- Training.ipynb 训练分类网络
- TestModel.ipynb 测试分类网络效果
- model.pkl 分类PyTorch模型
- hand_landmark.tflite 手掌骨骼点识别模型（Mediapipe Hands）
- palm_detection.tflite 手掌位置识别模型（Mediapipe Hands）

