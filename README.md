# Colorizing Pakistan

In this project, I use perceptual loss in neural networks to colorize black and white photos. I picked old black & white photos depicting Pakistan for my examples but they cna just as easily apply to any picture: https://medium.com/@btahir/colorizing-pakistan-5697f7754b2a

The jupyter notebook outlines all the steps. I use the fastai library and the Ocford Pets Dataset for training the models. 

Some results:

![alt text](https://github.com/btahir/colorizing-pakistan/blob/master/3.png)

![alt text](https://github.com/btahir/colorizing-pakistan/blob/master/4.png)

![alt text](https://github.com/btahir/colorizing-pakistan/blob/master/7.png)

## Notes for improvement

Since the models were trained on a Pets dataset, my suspicion is much better performance can be achieved using more generalized datasets such as the Imagenet dataset. One shortcoming we can see using the current dataset is how in the first picture the road is covered in a green tinge and this is probably because a lot of the photos in the Pets dataset is of animals on grass.
