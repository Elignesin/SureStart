# SureStart
Edited for Action Items for 2/10/21


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
