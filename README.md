# not_MNIST
## 1_notmnist.ipynb
In this project, we processing the dataset notMNIST instead of MNIST, the notMNIST includes 10 classes of english letters, from 
A to J
In the 1_notmnist.ipynb, I download the data form the net, and do some precessing about the dataset, such as storing the data in 
.pickle files separately, from A to J, and then store the whole data in a .pickle file. And dividing the data into three parts: 
training data, validation data, testing data.
And in the final, I used the LogisticRegression classifier on the dataset.

![image text](https://github.com/BlackLee68/not_MNIST/blob/master/img_folder/untitled.png)
## 2_fullconnected.ipynb
In this section, I used the fullconnected network to process the dataset, and then I add another hidden layer into the network, 
You can also get the details about parameters in the network in the 2_fullconnected.ipynb.
## 3_regularization.ipynb
In this section, I add a kind of regularization in the network: the L2 Regularization,  and I also tried the dropout function in 
the network. In the final, I added L2 regularization and multiple layers into the network, and got 94.9% accuracy.
## 4_convolutions.ipynb
In this section, I used the convolution network, when I used two convolutions and two max_pooling layers in the network, I got 
96.3% accuracy at end. Notice: the results in the 4_convolutions.ipynb is under the condition that I set the num_steps=1000, 
we can see we can still got a accuracy of 91.8%.
