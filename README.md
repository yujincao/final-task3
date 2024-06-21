# 基于NeRF的物体重建和新视图合成

安装好python环境

执行 pip install -r requirements.txt 安装依赖

训练需要在gpu环境下

运行 python run_nerf.py --config configs/COLMAP_test.txt
自制数据集在nerf模型上训练
训练结束后会保存模型权重、评价指标、视频、测试图片在logs文件夹下

运行 python run_nerf.py --config configs/COLMAP_test.txt --render_only
只在训练好的模型下测试
测试结束后会保存视频、测试图片在logs文件夹下



数据权重地址链接：https://pan.baidu.com/s/1ObYurMLphgAsXjSGmHLicA?pwd=jukk 

提取码：jukk