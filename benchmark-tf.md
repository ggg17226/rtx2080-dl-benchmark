## System info  

### CPU: Intel 6700k @4.5Ghz  
### Memory: DDR4 16G  
### Graphics card:MSI GeForce RTX 2080 VENTUS 8G OC  
### Operation system: Ubuntu 18.04 x86_64 kernel 4.15.0-36-generic  
### Cuda version: 10.0.130  
### Cudnn version: 7.3.1.20-1 for cuda 10.0  
### TrnsorRT version: 5.0.0.10-rc for cuda 10.0  
### Tensorflow version: Release 1.11.0 (commit id:c19e29306ce1777456b2dbb3a14f511edf7883a8)  


## Test tool  
### url: https://github.com/HewlettPackard/dlcookbook-dlbs/tree/master/python/tf_cnn_benchmarks
### commit id: 5ef7bbf10871a81425bc82048ea820566c2fa4e6  

## Test Result  
#### result unit: images/sec

|Net|batch_size 32|batch_size 64|
|:--:|:--:|:--:|
|DeepMNIST|8045.27|15811.44|
|AcousticModel|4208.21|8330.38|
|SensorNet|30135.81|53900.03|
|VGG11|240.60|260.31|
|VGG13|148.33|145.10(memory not enough)|
|VGG16|126.27|128.15(memory not enough)|
|VGG19|108.83|111.23(memory not enough)|
|LeNet|15951.14|26556.00|
|GoogleNet|468.09|515.9|
|Overfeat|595.07|833.16|
|AlexNet|613.62|689.35|
|AlexNetOWT|1546.52|2103.99|
|Trivial|8916.93|15436.50|
|InceptionV3|133.04|146.95|
|InceptionV4|68.32|out of memory|
|ResNet18|411.48|459.15|
|ResNet34|263.17|300.79|
|ResNet50|178.01|192.91|
|ResNet101|108.99|out of memory|
|ResNet152|out of memory|out of memory|
|ResNet200|out of memory|out of memory|
|ResNet269|out of memory|out of memory|
