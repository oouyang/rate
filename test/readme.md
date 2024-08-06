我目前在大陸地區，而我的中華民國護照效期已
過（或快要過），請問我怎樣申請辦理換發新護
照？
===
如果您並未在大陸地區設有戶籍或領用大陸地區護照，申請辦理換發護照方式依申請地
點分別說明如下：
1. 香港：
您可備妥申請護照之相關文件（如已逾期或未逾期護照、照片等）親自前往我們
派駐香港之「台北經濟文化辦事處」（地址：香港灣仔港灣道18號中環廣場49樓
4907室，電話：（852）2887-5011）申請換發護照。
2. 澳門：
您可備妥申請護照之相關文件（如已逾期或未逾期護照、照片等）親自前往我們
派駐澳門之「台北經濟文化辦事處」（地址：澳門新口岸宋玉生廣場411-417號皇
朝廣場5樓J-O座，電話：（853）2875-0320）申請換發護照。

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
