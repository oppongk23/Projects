I keep all my personal projects here. Much of it is pretty self-explanatory, but I do add some write-ups to explain the code and the thought processes behind certain descisions I make at each point. 
Some of the projects are still ongoing as I try to update them as I learn newer ways of improving the models, but I hope you learn something new all the same.



#### [Image Classification using an Artificial Neural Network](https://oppongk23.github.io/Image-Classification-ANN/): 
In this project, I try to tackle a very basic yet important task in Computer Vision, _**Image Classification**_, using a  very simple Artificial Neural Network (ANN). The work revolves around concepts such as artificial neurons and how they learn from data, how they tend to generalize poorly i.e _overfit_ to training data, and how we can use methods such as regularization and dropouts to improve the generalization performance of the model. The models were trained on the CIFAR10 Dataset. I use mostly _**Tensorflow**_ and _**Keras**_ for this implementation, but there is also the usage of _**Numpy**_ and _**Matplotlib**_ at various points in the project. The walkthrough of the model can be found [here](https://oppongk23.github.io/Image-Classification-ANN/), and the notebook can be found over [here](https://github.com/oppongk23/Image-Classification-ANN/blob/main/ANN_Assignment.ipynb).


#### [Image Classification using Convolutional Neural Networks (CNNs)](https://oppongk23.github.io/Image-Classification-CNN/):
To investigate the impact of convolution layers on the Image classification task, simple CNNs are constructed and used to classify images from the CIFAR10 Dataset. Like in the [ANN example](https://oppongk23.github.io/Image-Classification-ANN/), we try to look at the model performance in terms of overfitting and underfitting, and take steps to solve both scenarios. I've explained the steps in the project [here](https://oppongk23.github.io/Image-Classification-CNN/), and the code for the whole project can be found [here](https://github.com/oppongk23/Image-Classification-CNN/blob/main/CIFAR-10_CNN.ipynb). I use _**Tensorflow, Keras, Numpy**_ and _**Matplotlib**_ in this project.


#### Object Detection
In this project I use _Pytorch_ to implement an object detection model. I fine-tune a pre-trained **Resnet50 Faster RCNN** model and trained it on the [Trash-ICRA19](https://experts.umn.edu/en/datasets/trash-icra19-a-bounding-box-labeled-dataset-of-underwater-trash) dataset. The main aim of the project is to be able to detect the presence of plastic in the underwater environment. The model should be able to detect the difference between an underwater organism (labelled _bio_ in the dataset), a piece of plastic (labelled _plastic_), and a remote operated vehicle (_rov_ in the dataset). The code for the project is found over [here](). As mentioned earlier, I used _**Pytorch**_ in this implementation of this project.


#### [Churn Modelling](https://github.com/oppongk23/Churn_Modelling) 
This project is one I worked on with a few other colleagues. We try to predict whether or not a customer leaves a certain institution based on some factors available in the dataset. The dataset, was carefully analyzed, and decisions were made in order to increase the model performance. Two models (**Logistic Regression and Random Forest**) are coompared in different scenarios and the Random Forest model is chosen as the better option. Model **_accuracy_** is considered, and other metrics such as **_precision_** and **_recall_** are also explored.


#### Optical Communication using a laser
This experiment covers the complete communication setup involving a laser diode. I set up a signal generator using a Basys3 FPGA and used a laser driver to provide a signal to a laser diode. An optical receiver is used to receiver the signal which is then observed using an oscilloscope. Details of the whole experiment are provided [here]() including all the parts and component details. 


