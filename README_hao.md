## Knowledge 
Yolov4 vs. Yolov3
https://manivannan-ai.medium.com/yolo-v4-750cd627064f

## Requirements 
pip install -r requirements.txt

numpy, 
torch-1.6.0


## Prepare the data: 
https://github.com/ultralytics/yolov3/wiki/Train-Custom-Data





## Train
python train.py --device 0 --batch-size 1 --img 640 640 --data coco.yaml --cfg cfg/yolov4-tiny.cfg --weights '' --name yolov4-tiny --epochs 30



## Test 
python test.py --img 640 --conf 0.001 --batch 8 --device 0 --data coco.yaml --cfg cfg/yolov4-pacsp.cfg --weights weights/yolov4-pacsp.weights















