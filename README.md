# group_10 term project

## env setting

using python 3.10.8
and check the "requirements.txt" in /code

## how to config
all modified setting is already done.
you can view the yaml file of the model, the ones I modified are "model/yolov5x.yaml", "train.py", "detect.py", and "data/VisDrone_mix.yaml"

### File path setting:
Put the "code" folder and the "datasets" folder in the same directory.
Put the weight file under the "/code" path.

## how to run
once configured, use the following command line: 
python detect.py --weights ./weight.pt -- source ../data/testing\ data/

the result will be saved in the "/code/run/detect/" path.