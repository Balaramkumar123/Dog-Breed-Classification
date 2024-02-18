# Dog-Breed-Classification

This project is done as a part pf the kaggle dog breed identification competition: https://www.kaggle.com/c/dog-breed-identification/overview

There are a variety of dog breeds, and the dataset is quite large, containing around 10000 training images and 10000 testing images.

We have used TensorFlow as our working environment for this problem.

So, we have used the mobilenetV2 model, which in turn was trained on the Imagenet dataset, finding useful patterns.

We have implied Transfer Learning hear, using the mobilenetv2 model and training it with our data to find only those patterns that will be helpful in our problem.

The entire dataset and details could be found here. https://www.kaggle.com/c/dog-breed-identification/overview

The mobilenetv2 model could be found here. https://www.kaggle.com/models/tensorflow/mobilenet-v2/frameworks/tfLite/variations/1-0-224/versions/1?tfhub-redirect=true
