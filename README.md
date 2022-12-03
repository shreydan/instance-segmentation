# Instance Segmentation


## Binary Segmentation

Detecting roads in car driving clips - Reaching validation accuracy of 95%

model: U-NET

the steps are mentioned briefly in the notebook.

- [notebook](./u-net-binary-instance-segmentation-pytorch.ipynb)
- [kaggle notebook](https://www.kaggle.com/code/shreydan/u-net-binary-instance-segmentation-pytorch/notebook)


Original Segmentation Dataset (CamVid):

![](https://media1.giphy.com/media/QeMYXIMpakTgJXr1Cg/giphy.gif)

Detecting Roads in the dataset:

![](https://media3.giphy.com/media/sKxAUV8WPqsm1gRGOq/giphy.gif)

![](https://media0.giphy.com/media/SPzdI0gYWvJBYVey4f/giphy.gif)


### TODO

- multiclass segmentation
- train on other datasets such as Cityscapes
- combining datasets
- better resolution
- look at other Loss functions like dice loss
- understand IoU

___
