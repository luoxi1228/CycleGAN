# CycleGAN
# checkpoints：存放模型进行训练后，确定下来的相关参数的记录
# datasets: 存放用来进行训练的图片数据
# results: 存放最后的展示图片
# 程序运行方式：控制台输入
# 训练：python train.py --dataroot ./datasets/数据集 --name 数据集名称 --model cycle_gan
# 测试：python test.py --dataroot ./datasets/数据集 --name 数据集名称 --model cycle_gan
# 示例: python train.py --dataroot ./datasets/horse2zebra --name horse2zebra --model cycle_gan

# DataAugmentation
# data-augmentation-master: 数据增强的代码
# pythonProject: 存放增强之后的数据集
# 说明：需要将增强之后的数据集trainA trainB 复制到datasets中的数据集中。
