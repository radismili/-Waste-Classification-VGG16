# Waste-Classification-VGG16

-About the data-

Waste means any item excluded from further use. It can come from our homes, like food scraps and packaging, or from businesses and factories, like leftover materials and byproducts. Inadequate waste management represents one of the biggest problems from the aspect of environmental protection. When waste is not properly managed, it often ends up in landfills, where it can leach harmful chemicals into the soil and groundwater. Poor waste management also contributes to pollution, as plastics and other materials can end up in oceans and other natural habitats, harming wildlife. Additionally, the improper disposal of waste can lead to the release of toxic substances into the air, exacerbating air pollution and contributing to climate change. Effective waste management is crucial to minimizing these environmental impacts and protecting public health.

Dataset is divided into train data (85%) and test data (15%). Segregated into two classes (Organic and recyclable).
- Training data - 22564 images;
- Test data - 2513 images.

-Objectives-

We will train a model to classify the waste in the images as organic or recyclable. Main idea is to implement Transfer Learning: utilize VGG-16, a pre-trained convolutional neural network (CNN), as the base model. By transfer learning we means using pre-trained models, fine-tuning them on new data, and adapting their learned features to new tasks, thereby accelerating learning and improving model performance.

Database: https://www.kaggle.com/datasets/techsash/waste-classification-data
