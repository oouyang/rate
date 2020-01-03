SUMMARY
===
| model | input size | param mem | feat. mem | flops  |
|-------|------------|--------------|----------------|-------------|
| resnet-50 | 224 x 224 | 98 MB | 103 MB | 4 BFLOPs |
| resnet-152 | 224 x 224 | 230 MB | 219 MB | 11 BFLOPs |
| inception-v3 | 299 x 299 | 91 MB | 89 MB | 6 BFLOPs |
| vgg-vd-19 | 224 x 224 | 548 MB | 63 MB | 20 BFLOPs |
| alexnet | 227 x 227 | 233 MB | 3 MB | 1.5 BFLOPs |
| ssd-300 | 300 x 300 | 100 MB | 116 MB | 31 GFLOPS |


**syn-replicated-fp32-1gpus**

Config | i9-9900K-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 |299.57 |
resnet152 |116.34 |
inception3 |201.25 |
inception4 |83.39 |
vgg16 |184.38 |
alexnet |3880.06 |
ssd300 |154.14 |


**syn-parameter_server-fp32-1gpus**

Config | i9-9900K-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 |299.45 |
resnet152 |116.32 |
inception3 |201.64 |
inception4 |83.46 |
vgg16 |184.46 |
alexnet |3882.50 |
ssd300 |154.16 |


**syn-replicated-fp16-1gpus**

Config | i9-9900K-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 |590.40 |
resnet152 |212.02 |
inception3 |376.43 |
inception4 |140.61 |
vgg16 |257.11 |
alexnet |5073.66 |
ssd300 |170.19 |


**syn-parameter_server-fp16-1gpus**

Config | i9-9900K-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 |566.11 |
resnet152 |223.08 |
inception3 |378.49 |
inception4 |146.38 |
vgg16 |261.45 |
alexnet |5166.57 |
ssd300 |172.12 |
