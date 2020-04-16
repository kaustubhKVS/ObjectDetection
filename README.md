# Object Detection

This repository serves as a plug and play template for training and inferencing in object detection tasks <br>
We chose this architecture of Yolov2 (you look only once) due to its added benifits over RCNNs in speed and accuracy<br>
RCNNs have a seperate region proposal network RPN while yolo doesnt and hence is faster and accurate

## How to 

<li> Train </li>

Assign appropriate values to all variables in the config.json file <br>
run python train.py -c path-to-config in any terminal


<li> Predict </li>

run python predict.py --conf 'path to configuration file' --weights 'path to pretrained weights'--input 'path to an image or an video (mp4 format)' in any terminal
