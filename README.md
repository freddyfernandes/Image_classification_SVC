Simple Image Classifier for Parking Space Occupancy
This project is a simple image classifier designed to determine the occupancy status of parking spaces. The classifier uses the Support Vector Classification (SVC) algorithm from the Scikit-learn library. The dataset consists of images of parking spaces categorized as either 'empty' or 'not_empty.'

Project Structure
clf-data: This directory contains subdirectories for each category ('empty' and 'not_empty'), each containing respective image samples.

classifier.py: The main Python script for the image classifier. It reads the dataset, preprocesses the images, performs a grid search for hyperparameter tuning, evaluates the model's performance, and saves the trained model.

model.p: The saved model file in pickle format, which can be loaded for future use without retraining.

Notes:
-Make sure to customize the input_dir variable in the classifier.py script to point to the correct dataset directory.
-The hyperparameters for the SVC model are fine-tuned using grid search. If you want to explore further improvements, consider adjusting the hyperparameter search space in the parameters variable.
-Feel free to use the trained model (model.p) for predicting occupancy status on new images.

-Freddy Fernandes
