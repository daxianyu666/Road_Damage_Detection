# Road_Damage_Detection

训练：python train.py --img 640 --batch 16 --epochs 5 --data dataset1.yaml --weights yolov5s.pt

预测：python detect.py --source filename.jpg --weights ./runs/train/exp/weights/best.pt

结果保存在
\runs\detect
