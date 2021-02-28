# SureStart
Edited for Action Items for 2/25/21


## Reflections

*2/8/21*
Through the SureStart program, I hope to further reinforce my skills in Machine Learning while learning new skills and concepts in Artificial Intelligence. I also hope to collaborate with the fellow members of my cohort and have a fun experience working with others and learning new skills from them.  

*2/9/21*
1. Supervised and unsupervised machine learning differ primarily in that, for supervised machine learning, training data which has already been labeled is fed in, and the model is adjusted on that "training data" so that it can make conclusions on new data. Conversely, for unsupervised machine learning, the model is given unlabeled data and has to find relationships and patterns within it.  
2. This is false because Scikit-Learn is simply a modeling library; it does not have tools to load and handle data, as Pandas does, or to visualize it like Graphviz does. Thus, it uses these libraries to manipulate and visualize data, but Scikit-Learn cannot iself visualize data without these other libraries being used.  

*2/10/21*
1. "Tensors" are multidimensional arrays used to represent graph edges in some neural networks. These arrays are mathematical objects representing physical entities, like vectors, with both magnitude and multiple directions. Tensors are often used in machine learning because they can represent multi-dimensional space with a simple array of numbers, which a computer can work with.  
2. Unfortunately, I was having issues downloading tensorflow on my machine, so I'm not sure what you're looking for here.  

*2/11/21*
The dataset I found is hosted at https://www.kaggle.com/techsash/waste-classification-data. The dataset contains 22,500 images, split between images of "organic" food and images of "recyclable" materials. The goal of this is to mirror a real-world problem of waste sorting. Ideally, it would be possible to develop an algorithm that could take a single stream of waste, and could identify recyclable and compostable items in it before separating those items from the stream. Using this data, I would hope to build a rudimentary version of this with only two classes, being "recyclable" or "non-recyclable". To do this, I would plan on using a Convolutional Neural Network in order to classify images in one of the two given groups. For this problem, a CNN would be helpful in being much less computationally intensive, which would allow a theoretical future model to be run inexpensively in local waste sorting centers.  

*2/12/21*
I was unable to make the chrome extension that moves from Kaggle to Github to work correctly, so I downloaded the notebook from Kaggle and uploaded the notebook here.  

*2/15/21*
I have uploaded my adapted version of the notebook found at https://www.kaggle.com/kanncaa1/convolutional-neural-network-cnn-tutorial, which was augmented with the full training dataset from the MNIST database (linked at http://yann.lecun.com/exdb/mnist/).  
**Edit: I made a second version of this notebook (v2) on 2/17, which changed the graphing to include validation and training accuracy and loss. From this, I concluded that the model probably should have trained using more epochs.**  

*2/16/21*
1. Machine Learning and AI were used in the design of "Survival of the Best Fit" in order to demonstrate the issue with opaque hiring algorithms and how human biases, such as those on race or gender, can affect the training of machine learning models such that the models themselves are biased.  
2. One real-world machine learning model that is likely biased is the facial recognition technology often used in Police Departments. Such models are likely biased because of historic and current biases in policing in minority communities, which is given as training data to the models to determine who is a "criminal" or not. Some thoughts on how this might be resolved are to train the model on more complete datasets, or to attempt to combat the historical biases in policing by changing how the model weights various features in the data.  

*2/17/21*
Convolutional Neural Networks differ from Fully Connected Neural Networks in their scope, construction, and purpose. The primary difference is in layering: the convolutional and pooling layers in CNNs iterate through the image, breaking it up into pieces and analyzing those pieces before combining the results together and analyzing those. Those results are then fed into a "fully connected" layer, from which classifications are decided upon. Fully Connected Neural Networks, on the other hand, do not have this structure, and all data is passed through all neurons. At higher input resolutions, Fully Connected Neural Networks are too computationally expensive to train and run on quickly and efficiently. As such, CNNs are particularly useful for computer vision tasks, such as image classification and image segmentation, since they can be trained relatively inexpensively and have fewer parameters to select.   

*2/18/21* I added my own version of a notebook with a Convolutional Neural Network for predicting MNIST digits to this repository. I have also included graphs for training and validation loss and accuracy.

*2/19/21* This action item was actually completed on 2/20/21, but no matter. I added my own notebook from Google Colab with a basic image classification model for classifying dogs and cats, which was built from and modified from the activity found at https://keras.io/examples/vision/image_classification_from_scratch/. I also included some graphs for training and validation loss and accuracy.  

*2/22/21* I have added the notebook for the action item on February 22, including a CNN for classifying facial images by gender (I chose to do only by gender because of the length of time for which the CNN took to train). This was modeled from the activity at https://www.kaggle.com/thanaphatj/gender-classification-of-facial-images-cnn, but I largely built the CNN using what I'd learned from the previous week.  

*2/23/21* The Rectified Linear Unit , or ReLU, is is the activation function most often used in the hidden layers of many Neural Networks. It has become the standard, as opposed to Sigmoid or Tanh activation functions, because those functions satruate too easily and, as such, are anti-useful for multi-layer models due to their vanishing gradients (after a certain point, due to the saturation, layers no longer receive useful gradient information, and this error is carried through the rest of the model). ReLU, by comparison, is advantageous in that it is nonlinear but acts like a linear function (for positive values, ReLU returns the input value; for negative values, ReLU returns 0). ReLU is particularly advantageous in Neural Networks because it computationally trivial, requiring only a max function (as opposed to the sigmoid/tanh functions need for exponentials). This is especially useful in training deep networks because, due to its linear behaviors, it does not suffer with the gradient vanishing issue of the other functions. ReLU can also be easily extended, allowing for small negative values in some cases (Leaky ReLU), in order to combat the issue wherein the weights update such that the activation function gets stuck in forever outputting 0.0.  

*2/24/21* The notebook for today's action item is added to the repository. This notebook is lightly modeled off of https://hackernoon.com/build-your-first-neural-network-to-predict-house-prices-with-keras-3fb0839680f4, but was largely built on its own. I'm very happy with how this model came out; it is fairly accurate but does not appear to be overfit.  

*2/25/21* The notebook for today's action item is added to the repository. This notebook is adapted from https://towardsdatascience.com/handling-overfitting-in-deep-learning-models-c760ee047c6e#, and the data in the notebook comes from https://www.kaggle.com/crowdflower/twitter-airline-sentiment.  

*2/26/21* This action item was actually completed on 2/28/21 because of time constraints prior. Both the notebook for upsampling, which came from https://machinelearningmastery.com/upsampling-and-transpose-convolution-layers-for-generative-adversarial-networks/, and the notebook on autoencoding from https://blog.keras.io/building-autoencoders-in-keras.html have been added to the repository.
