# Proposal: Smart category of photographs

Description: It will feels much convenient to have a function in your phone that can automatically sort your photos into travel, people, foods, etc. And this is actually an image classification problem that mattered and are explored in many fields. Therefore, this project will probe into this problem using simple algorithms and superior algorithms, and compare their performance for deeper understanding.  
## Dataset
Four categories of photographs will be collected by simply searching on google. Specifically, type in "Photography of people", "Photography of scenery", "Photography of foods", "Photography of people", and download them separately with resolution of 100 x 100 px. In this case the labels of the images are automatically generated. Each category will contain 500 images, then 2000 example in total for this project.


Backup data source: ImageNet. http://image-net.org/. Also a diverse database site for image classification problems.

## Algorithms

In order to classify the photograghs, we need to do object detection and feature extraction in the images that are expressed as 100x100 matrixs. 

### 1. Kernel-based Support Vector Machines
It builds a hyper-plane or a set of hyper-planes in a high dimensional space and good separation between the two classes is achieved by the hyperplane that has the largest distance to the nearest training data point of any class.
The real power of this algorithm depends on the kernel function being used.
The most commonly used kernels are: Linear Kernel, Gaussian Kernel, Polynomial Kernel. 
Will learn more about this method in class and literatures. 
### 2. K-Nearest Neighbor
This algorithm simply relies on the distance between feature vectors and classifies unknown data points by finding the most common class among the k-closest examples.
In order to apply the k-nearest Neighbor classification, we need to define a distance metric or similarity function. Common choices include the Euclidean distance and Manhattan distance. 
### 3. Convolutional Neural Network
Convolutional neural networks (CNN) uses some of its features of visual cortex and have therefore achieved state of the art results in computer vision tasks.It is comprised of two very simple elements, namely convolutional layers and pooling layers.Although simple, we need much effort to design the architecture of the layers to generate the best prediction. 
## Timeline

Oct.22th-Oct.30th 1. Literature review for a better start point of algorithm design and problem anticipation.
                  2. Data collection and basic organizing and pre-processing

Nov.1st - Nov.17th: Build the first two algorithm listed above and finish cross-validation. Accumulate results and obstacles in the first update.

Nov.17th - Dec.1st: Build a CNN model and finish cross-validation. Compare performance of those algorithms and finish the second update.

Dec.1st - Dec.12th: try to optimize the codes for better performance. Since those simple algoorithms may be not efficient enouh for such problem, another complex algoritnm worths a try. And finall wrap up for the final report. 
