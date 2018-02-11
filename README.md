# DCGAN
This is an interesting application for DCGAN in animation people drawing  
## Result show
Training data examples:  
![avatar](https://raw.githubusercontent.com/awonderfullife/DCGAN/master/TrainingDataExamples/02ec07fd55a902bd1b75d70ca097a8a2-0.jpg)
![avatar](https://raw.githubusercontent.com/awonderfullife/DCGAN/master/TrainingDataExamples/0a5aa42fdc12fa232abcff8eb1fb58b7-2.jpg)
![avatar](https://raw.githubusercontent.com/awonderfullife/DCGAN/master/TrainingDataExamples/0ce58d74df4454fb89b4b41e95fa3d5b-0.jpg)
![avatar](https://raw.githubusercontent.com/awonderfullife/DCGAN/master/TrainingDataExamples/0ce63ebf32fb66210679f78f05932c51-0.jpg)
![avatar](https://raw.githubusercontent.com/awonderfullife/DCGAN/master/TrainingDataExamples/0e4ea7052b2b731e5d14074d5a001d8f-1.jpg)
![avatar](https://raw.githubusercontent.com/awonderfullife/DCGAN/master/TrainingDataExamples/1c34767b7a179a5b140a313714efd42c-1.jpg)
![avatar](https://raw.githubusercontent.com/awonderfullife/DCGAN/master/TrainingDataExamples/1e39c262f95199963ec70d2dac7f55f7-0.jpg)
![avatar](https://raw.githubusercontent.com/awonderfullife/DCGAN/master/TrainingDataExamples/1fc48726d2aaa2a7d77c3299f5c859d3-0.jpg)

Results after 300 epoches:  
![avatar](https://raw.githubusercontent.com/awonderfullife/DCGAN/master/Result.png)
## Training data download 
Link：https://pan.baidu.com/s/1gg3eF2V psw：pf32  
extract it under the data folder then you could use it for training  
## Train Model 
python main.py --input_height 96 --input_width 96 --output_height 48 --output_width 48 --dataset anime --crop --train --epoch 300
## Test Model 
python main.py --input_height 96 --input_width 96 --output_height 48 --output_width 48 --dataset anime --crop  
