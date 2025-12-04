Computer Vision: Deployable waste segregation model(self project)

Achieved and accuracy of 92% by using transferring learning and then fine tuning by ResNet50
Switched to mobilenet_v2 for making the model light weight and made changes in labels to meta classes to make it human understandable and used metric as AUC
Converted model to tfLite to make it android deployable and quantized model to INT 8 from float32 reducing latency by 86%

Dataset used: https://www.kaggle.com/datasets/farzadnekouei/trash-type-image-dataset
