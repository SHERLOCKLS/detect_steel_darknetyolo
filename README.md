## 1. 比赛地址
[智能盘点—钢筋数量AI识别](https://www.datafountain.cn/competitions/332/details)


----------
## 2. 依赖
`pandas`, `tqdm`


----------
## 3.使用方法
安装:

    git clone https://github.com/SHERLOCKLS/detect_steel_darknetyolo
    cd detect_steel_darknetyolo
    make -j
    pip install -r requirements.txt
下载数据并解压,训练和测试图像分别放到train目录和test目录:

    - detect_steel_darknetyolo
	    train/
	    test/
	  

训练:

    ./get_weight.sh
    ./train.sh
预测:

    python infer.py
## 4. 效果:
线上 0.96+


----------


## 5. 参考

> [darknet-yolo](https://github.com/pjreddie/darknet)

## 6.其他
如遇问题,可在issue区提问. 第一次尝试开源, 大家玩的开心.

    
    
    
