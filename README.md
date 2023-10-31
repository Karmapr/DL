# DL
## 运行步骤
### 训练
打开train.py，然后更改parse_opt中parser.add_argument()中的各个参数，例如模型位置、标签文件位置、训练次数、训练设备等等，将其调整为自己需要的。
随后就可以运行，训练后的结果将放在runs/train/中。
### 检测
打开detect.py，同样更改parse_opt中parser.add_argument()中的参数，然后将检测的图片放到data/images中。
随后开始运行检测，检测后的结果会存放在runs/detect/中。
