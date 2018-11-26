# FinalProjectML
### Machine Learning Fall 2018 Final Project
Hayden Nix & Catherine Diaz
***
## About the Data
This is the Google dataset from the Quick, Draw! application. It contains 50 million drawings across 345 classes. The data is provided in several different formats.

###### Get the data:
Link to data: [Quick, Draw! Dataset](https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/)

##### Data formats:
* **Binary**: files that contain the full binary representations of every drawing in a given class
* **Raw**: files that contain full, unsimplified NDJSON vector representations of every drawing in a given class
* **Simplified**: files that contain simplified (removing redundant values like middle of lines) NDJSON vector representations of every drawing in a given class
* **Numpy_bitmap**: npy files that contais the simplified data converted into a 28x28 greyscale bitmap representation in nparrays for every drawing in a given class

The data is also available in csv representations of vectors, both simplified and unsimplified, in the [GoogleAI Quick, Draw! Kaggle Competition](https://www.kaggle.com/c/quickdraw-doodle-recognition/data)

##### For this project:
For this project, it will likely be best to use the Numpy bitmap representation of the data, as it can be easily read by data, eliminating some of the tedious load work, is simplified, reducing the data's size and therefore train/test time, and is converted to match the format of the MNIST datasets, so resources should be widley available.

***
## Initial Thoughts on Approach

***
## Running the Models