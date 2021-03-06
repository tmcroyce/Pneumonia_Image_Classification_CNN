Business Understanding:

In this image classification project, I am utilizing neural networks - primarily convolutional neural networks - to create a model that can identify whether or not a patient has pneumonia by analyzing their lung x-rays.

There are two types of pneumonia - bacterial and viral. The image classification system will have to be able to pick out both, while not necessarily knowing which one is which, as the types of pneumonia are not labeled in the dataset.


Data Understanding:
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

Due to the relatively small amount of validation data (16 images), as well as test data, I created my own validation data instead of using the provided split.

Modeling:
In the main jupyter notebook (pneumonia_classification), I run initial models from densely-layered neural networks to a plethora of CNN's. In the second jupyter notebook, I run the VGG model. This was done in a secondary notebook because it had to be processed differently due to algorithmic complexity (i.e., my computer couldn't run it). 

Results:
CNN #4 achieved 95.5 percent accuracy.

