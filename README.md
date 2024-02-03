# Multiclass Food Prediction

Excited to reflect on my fifth and final responsibility as a Machine Learning Intern at Prodigy Infotech – the creation of a sophisticated multiclass food prediction model. This endeavor was both challenging and rewarding, featuring a dataset of colossal proportions exceeding 10 GB, with each of the 101 classes boasting an impressive 1000 images.

Due to GPU processing limitations and time constraints, a strategic decision was made to train the model on a subset of three classes. Despite this constraint, the architecture was meticulously designed to be flexible, facilitating scalability for future expansions to accommodate the entire spectrum of 101 food classes.

The model's foundation rested on the fine-tuning of an InceptionV3 pre-trained model, a powerful convolutional neural network architecture. Leveraging the Food-101 dataset, the model underwent rigorous training, achieving an impressive accuracy rate of almost 94%. This outcome underscores the efficacy of transfer learning and the ability to harness pre-existing knowledge for specialized tasks.

The strategic selection of classes not only demonstrated adaptability but also allowed for an in-depth exploration of model nuances, contributing to its robustness. The computational challenges posed by a dataset of this magnitude were met with thoughtful resource allocation and optimization strategies, ensuring a balance between accuracy and computational efficiency.

This experience underscored the importance of resource-conscious model development and the dynamic nature of machine learning projects. I am enthusiastic about the prospect of expanding the model to encompass the full breadth of classes in the future, leveraging the knowledge and insights gained from this transformative internship at Prodigy Infotech. Excited to apply these learnings in my ongoing journey through the dynamic landscape of machine learning!

## `data` Folder Structure:

```
├── data
|   ├── food-101
|   ├── test
|   ├── test_mini
|   ├── train
|   ├── train_mini
```

## `model` Folder Structure:

```
├── model
|   ├── best_model.hdf5
|   ├── history.log
|   ├── model.hdf5
```