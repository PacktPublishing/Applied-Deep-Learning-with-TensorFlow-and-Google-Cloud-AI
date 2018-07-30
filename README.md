# Applied Deep Learning with TensorFlow and Google Cloud AI
![image1][image-1] 
_Authors: [Haohan Wang][1] & [Christian Fanli Ramsey][2]_ \> [dyad x machina][3]
## Getting Started
This course is aimed at intermediate machine learning engineers, DevOps, technology architects and programmers who are interested in knowing more about deep learning, especially applied deep learning, TensorFlow, Google Cloud and Keras. We ares here to give you the skills to analyze large volumes of data in distributed ways for a production level system. After the course, you will be able to have a solid background in how to scale-out machine learning algorithms in general and deep learning in particular. 

We have designed the course to provide you with the right blend of hands-on, theory and best practices in this rapidly developing area while providing grounding in essential concepts which remain timeless.

 Tools and frameworks like, `Keras`, `TensorFlow`, and `Google Cloud` are used to showcase the strengths of various approaches, trade-offs and building blocks for creating real-world examples of distributed deep learning models.


* Link to Packt Publishing: https://www.packtpub.com/big-data-and-business-intelligence/distributed-deep-learning-video

### Prerequisites
This course is for intermediate machine learners like you who want to learn more about deep learning, how to scale out your deep learning model, and then quickly turn around and use the tools and techniques you are about to learn from this course to solve your tricky deep learning tasks. 

You will be successful in this course if you have a basic knowledge of computer programming especially Python programming language. Also some familiarity with deep learning like neural networks will be helpful. 

In this course, you will need a Google Cloud free tier account. Note that you won't be charged by creating the account. Instead, you can get `$300` credit to spend on Google Cloud Platform for 12 months and access to the Always Free tier to try participating products at no charge. By going through this course, you will probably need to spend at most `$50` out of your `$300` free credit. 

### Built with
* [Keras][4]
* [TensorFlow][5] *low and high level*
* [Google Cloud MLE][6]

### Versioning
* [Keras][7] `2.1.6`
* [TensorFlow][8] `1.8`
* [Google Cloud MLE][9] `latest`

### Installing
##### Keras
```
sudo pip install keras
```
##### TensorFlow GPU
```
sudo pip install tensorflow-gpu
```
**OR**
##### TensorFlow CPU
```
sudo pip install tensorflow
```
##### Google Cloud MLE
Link: https://cloud.google.com/sdk/
> Installation details will be explained in [Section III][10]

### Authors
**Christian Fanli Ramsey** 
* Github: https://github.com/christianramsey
* LinkedIn : https://www.linkedin.com/in/christianramsey/
* Tumblr : https://www.tumblr.com/blog/anthrochristianramsey
* Medium : https://medium.com/@christianramsey
* Twitter : https://twitter.com/christianramsey

**Haohan Wang**
* Github: https://github.com/haohanwang23 
* LinkedIn : https://www.linkedin.com/in/haohanw/
* Tumblr : https://www.tumblr.com/blog/haohanwang 
* Medium : https://medium.com/@haohanwang

**DyadxMachina**
* Website:  https://dyadxmachina.com
---- 
### Content
**PREPARATION - [Installation and Setup][11]**
* Nvidia Setup
* Anaconda Setup
* TensorFlow GPU and Google Cloud
* Requirements
---

**SECTION I – [Deep Learning with Keras][12]**
* 1.1 Keras Introduction
* 1.2 Review of backends Theano, TensorFlow, and Mxnet
* 1.3 Design and compile a model
* 1.4 Keras Model Training, Evaluation and Prediction
* 1.5 Training with augmentation 
* 1.6 Training Image data on the disk with Transfer Learning and Data augmentation 
---- 

**SECTION II – [Scaling Deep Learning using Keras and TensorFlow][13]**
* 2.1 Tensorflow Introduction
* 2.2 Tensorboard Introduction
* 2.3 Types of Parallelism in Deep Learning – Synchronous vs Asynchronous
* 2.4 Distributed Deep Learning with TensorFlow 
* 2.5 Configuring Keras to use TensorFlow for distributed problems 
---

**SECTION III - [Distributed Deep Learning with Google Cloud MLE][14]**
* 3.1 Representing data in TensorFlow
* 3.2 Diving into Estimators
* 3.3 Creating your Data Input Pipeline
* 3.4 Creating your Estimator
* 3.5 Packaging your model/trajectory 
* 3.6 Training in the Cloud
* 3.7 Automated Hyperparameter Tuning
* 3.9 Deploying your Model to the Cloud for Prediction 
* 3.10 Creating your Machine Learning API

---

#### Feel Free to contact us if you have any question:
Visit our website [dyadxmachina.com]()
> Haohan Wang: haohan723@gmail.com

> Christian Fanli Ramsey: thechristianramsey@gmail.com



![image][image-2]

[1]:	http://haohanwang.tumblr.com "Haohan Wang Life Blog"
[2]:	http://anthrochristianramsey.tumblr.com "Lifeblog | Christian Fanli Ramsey"
[3]:	http://dyadxmachina.com "Dyad x Machina - affective neuroscience x deep learning"
[4]:	https://keras.io/
[5]:	https://www.tensorflow.org/
[6]:	https://cloud.google.com/
[7]:	https://github.com/keras-team/keras
[8]:	https://github.com/tensorflow/tensorflow
[9]:	https://github.com/GoogleCloudPlatform
[10]:	https://github.com/dyadxmachina/Distributed-Deep-Learning-with-Tensorflow/tree/master/0.%20Setup%20distributed%20deep%20learning%20environment
[11]:	https://github.com/dyadxmachina/Distributed-Deep-Learning-with-Tensorflow/tree/master/0.%20Setup%20distributed%20deep%20learning%20environment
[12]:	https://github.com/dyadxmachina/Distributed-Deep-Learning-with-Tensorflow/tree/master/1.%20Deep%20Learning%20with%20Keras
[13]:	https://github.com/dyadxmachina/Distributed-Deep-Learning-with-Tensorflow/tree/master/2.%20Distributed%20TensorFlow%20&%20Keras
[14]:	https://github.com/dyadxmachina/Distributed-Deep-Learning-with-Tensorflow/tree/master/3.%20Distributed%20Deep%20Learning%20with%20Google%20ML%20Engine


[image-1]:	https://image.ibb.co/e9rhPT/Screen_Shot_2018_07_24_at_15_10_09.png "Applied Deep Learning with TensorFlow and Google Cloud AI"
[image-2]:	https://image.ibb.co/khJuB7/Screenshot_from_2018_05_05_17_38_05.png
