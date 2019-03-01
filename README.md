# Plant Seedlings Classification - Can you differentiate a weed from a crop seedling?
Determine the species of a seedling from an image. Kaggle Competition: https://www.kaggle.com/c/plant-seedlings-classification

The ability to do so effectively can mean better crop yields and better stewardship of the environment.

The Aarhus University Signal Processing group, in collaboration with University of Southern Denmark, has recently released a dataset containing images of approximately 960 unique plants belonging to 12 species at several growth stages.

The goal of the competition is to create a classifier capable of determining a plant's species from a photo. The list of species is as follows:

Black-grass
Charlock
Cleavers
Common Chickweed
Common wheat
Fat Hen
Loose Silky-bent
Maize
Scentless Mayweed
Shepherds Purse
Small-flowered Cranesbill
Sugar beet

# Model Training History 
Transfer Learning based on ResNet pre-trained on ImageNet dataset and fine tune using two unfrozen layers.

![Model Training History](performances_epochs.png)

# Confusion Matrix / Validation Dataset
![Normalised Confusion Matrix](normalised_confusion_matrix.png)
