![digital-meter-reading_03 (1)](https://user-images.githubusercontent.com/41283107/125089217-c8cc1680-e100-11eb-9d09-38380d4e281b.jpg)
# smiletoeveryone-digits_recongnition_model_training

1. please pip install -r requirements.txt for installiing the environment dependancies

2. python train.py --img 640 --batch 16 --epochs 5 --data xxx.yaml --weights yolov3.pt --device 0,1,2,3,4,5 // if you have multi-gpus, but not recommend

3. xxx.yaml for classes set and nc(number of classes), same number as classes names

4. the version of nvidia cuda depends on what type of gpus you own, please note it.
