# Banana Leaf Disease Detection Project
This project is aimed at detecting banana leaf diseases like Segatoka, Xanthomonas, etc. and differentiating them from healthy leaves. The project is built using computer vision techniques and machine learning algorithms.

## Dataset
The dataset used in this project consists of images of banana leaves infected with Segatoka and Xanthomonas diseases as well as images of healthy banana leaves. The dataset is available in the dataset/ directory of the project repository.

## Dependencies
The project requires the following dependencies:

1. Python 3.6 or higher
2. OpenCV 4.5.1 or higher
3. TensorFlow 2.4.1 or higher
4. Keras 2.4.3 or higher
5. NumPy 1.19.3 or higher
6. Matplotlib 3.3.2 or higher
7. Scikit-learn 0.23.2 or higher

## Usage
To train the model, run the train.py script: python train.py

To test the model on a single image, run the test.py script: python test.py --image path/to/image.jpg

To test the model on a directory of images, run the test.py script with the --dir flag: python test.py --dir path/to/images/

## Results
The model achieved an accuracy of 95% on the test dataset. Below is a sample output of the model:
![Screenshot 2023-05-06 000253](https://user-images.githubusercontent.com/97793147/236633599-7cc66489-949f-4143-83ac-8729ddb38903.png)


## Conclusion
This project demonstrates the effectiveness of computer vision techniques and machine learning algorithms in detecting banana leaf diseases. The model can be further improved by increasing the size of the dataset and fine-tuning the hyperparameters.





