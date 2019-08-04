# Dogitizer App
In this project we will build a Convolutional Neural Networks (CNN) algorithm using pytorch. This algorithm can be used as part of a mobile or web app to classify humans, dogs and dog breeds.

## Project overview
Using PyTorch and Convolutional Neural Networks, we will build an algorithm that process photos supplied by users. User will supply a photo of a dog and our Algorithm will classify the dog breed. This model will also accept human photos and will identify the dog breed that this human photo resembles.  
The goal of this project is to understand the challenges involved in designing and implementing a Convolutional Neural Networks model using PyTorch to achieve reasonable classification accuracy.

![Dog Double2](/images/double2.jpg)

### Steps
0. Import Datasets
1. Detect Humans
1. Detect Dogs
1. Create a CNN to Classify Dog Breeds (from Scratch)
1. Create a CNN to Classify Dog Breeds (using Transfer Learning)
1. Write the Algorithm
1. Test the Algorithm

---

### Results

* [x] The implemented model was able to achieve accuracy of 87% on test data.
* [x] When human image is detected, the model returns the resembling dog breed.
* [x] When dog image is detected, the model returns the predicted breed.
* [x] When neither dog or human image is detected, the model returns an output that indicates an error.

#### Human Results
When we input a human image, the model will detect a human and returns the resembling dog breed.
* Input1: the algorithm was successfully able to detect a "human" and identified the resembling breed as "Chinese crested"

![Chinese crested](/images/Chinese-crested.jpg)


* Input2: the algorithm was successfully able to detect a "human" and identified the resembling breed as "Dachshund"

![Dachshund](/images/Dachshund.jpg)


* Input3: the algorithm was successfully able to detect a "human" and identified the resembling breed as "Bedlington terrier"

![Bedlington terrier](/images/Bedlington-terrier.jpg)


#### Dog Results
When we input a dog image, the model will detect a dog and returns the predicted breed.
* Input1: the algorithm was successfully able to detect a "dog" and classify the breed as "English springer spaniel"

![English springer spaniel](/images/dogrslt1.jpg)


* Input2: the algorithm was successfully able to detect a "dog" and classify the breed as "Basenji"

![Basenji](/images/dogrslt2.jpg)


* Input3: the algorithm was successfully able to detect a "dog" and classify the breed as "Bull terrier"

![Bull terrier](/images/dogrslt3.jpg)

---


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Reference

Udacity deep learning program (Capstone project)
