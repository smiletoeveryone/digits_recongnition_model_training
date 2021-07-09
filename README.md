# smiletoeveryone-digits_recongnition_model_training

1. please pip install -r requirements.txt for installiing the environment dependancies

2. python train.py --img 640 --batch 16 --epochs 5 --data xxx.yaml --weights yolov3.pt --device 0,1,2,3,4,5 // if you have multi-gpus, not recommend

3. xxx.yaml for classes set and nc(number of classes), same number as classes names
