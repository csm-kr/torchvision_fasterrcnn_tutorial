## torchvision fasterrcnn tutorial

This repository is a tutorial of faster rcnn using torchvision

The Characteristics of this repo
- [x] No Normalization
- [x] Dataset is coco (91 classes)
- [x] Easily extensible to other TORCHVISION models]

### Results

#### input
![input](./soccer.png)

#### qualitative 
![output](./result.png)

### COCO
#### quantitative
```
Accumulating evaluation results...
DONE (t=4.81s).
IoU metric: bbox
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.369
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.586
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.396
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.212
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.403
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.482
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.307
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.485
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.509
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = 0.317
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.544
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.649
mAP :  0.36949663588048526
Eval Time : 433.9941
4952 / 433.9941 = 11.4103 (fps)
```

### Start Guide

- Run demo.py

### Reference

https://github.com/csm-kr/retinanet_pytorch/blob/master/demo.py

https://github.com/spmallick/learnopencv/blob/master/PyTorch-Mask-RCNN/PyTorch_Mask_RCNN.ipynb






