# Dog-Breed-TensorFlow
The problem looks into develop a Deep Learning model that is able to predict a dog breed from an image based on the patterns found in training dataset. The model is built using TensorFlow 2.x, Keras API and a pre-trained model MobilNetV2.

The problem is a multi-class image classifier.

**1. Problem definition:** Try to identify the dog breed from a given image of a dog.

**2. Data:** The data is imported from Kaggle. 
> https://www.kaggle.com/c/dog-breed-identification/data

**3. Evaluation:** The evaluation is a DataFrame with prediction probabilities of the test dataset for each dog breed.
> https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

**4. Features:**
* It is going to be used deep learning and transfer leaning because the data is unstructured.
* The training dataset has 10 000+ dog images and 120 unique labels.
* The test dataset has 10 000+ dog images and no labels.

**5. Modelling:** It is going to be used a pre-trained model imported from Kaggle and the model is built using Keras API. 

## Project files:
* **dog-breed.ipynb** - Google CoLab notebook that follows all the steps of building a multi-class image classifier model
* **MobilNetV2** - https://www.kaggle.com/models/google/mobilenet-v2/TensorFlow2/140-224-classification/2
* **Data** - download here: https://www.kaggle.com/c/dog-breed-identification/data
