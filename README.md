# Real-Life-Violence-Detection-With-oneAPI

![image](https://upload.wikimedia.org/wikipedia/en/1/18/Will_Smith_slaps_Chris_Rock.jpg)

# Inspiration <img src="https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/inspiration.png" width="60" height="60"> 
Machine learning is evloving day by day and is solving many real life problems that are life changing. One such application is violence detection which uses machine learning model trained with lots of videos including violence to detect violence in live stream and/or in pre-recorded video. Violence detection includes detection of physical beating, stabbing, robbery, firing of gun, riot, hijack, terrorist attack, etc. 

# Methodology  <img src="https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/solution.png" width="60" height="60">  

Violence detection using transfer learning involves using a pre-trained Convolutional Neural Network (CNN) on a large dataset, such as ImageNet, and re-purposing it for the task of violence detection. The methodology involves fine-tuning the pre-trained model on a smaller dataset of violent and non-violent videos, and then testing the model on new, unseen videos. Transfer learning can significantly reduce the time and resources required for model training, as it leverages the pre-existing knowledge of the pre-trained CNN.


# Dataset  <img src="https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/Dataset.jpeg" width="60" height="60"> 

The dataset used in this project is the ‘Real Life Violence Situations Dataset’  from the Kaggle Repository published by Mohamed Elesawy.
The dataset contains 1000 Violence and 1000 non-violence videos collected from youtube videos, which includes many real street fights situations in several environments and conditions.

# WorkFlow  <img src="https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/workflow.png" width="60" height="60">

### Dataset collection 
Gather a dataset of videos containing both violent and non-violent scenes. The dataset should be balanced and diverse, containing videos with differentlighting conditions, camera angles, and types of violence.

### Data pre-processing 
Convert the videos to a suitable format and resize them to a fixed resolution. Extract individual frames from the videos and create a dataset of images. Apply pre-processing techniques such as normalization, resizing, and augmentation to improve the performance of the transfer learning model.

### Selecting a pre-trained model 
Choose a pre-trained model that has been trained on a large dataset of images or videos. Ideally, the pre-trained model should be designed for video analysis, such as the Two-Stream Convolutional Neural Network or the Temporal Segment Network.

### Model customization 
Remove the last few layers of the pre-trained model and replace them with new layers that are designed for the specific task of violence detection. Freeze the weights of the pre-trained layers and only train the weights of the new layers. This process is known as fine-tuning.

### Model training 
Train the customized model on the pre-processed dataset. The model should have multiple convolutional layers followed by pooling and activation functions. The output of the final layer should be a binary classification of violence or non-violence.

✅ Used model using intel oneAPI 

![image](https://user-images.githubusercontent.com/72274851/218504609-585bcebe-5101-4477-bdd2-3a1ba13a64a8.png)

✅ The result is as shown
![image](https://user-images.githubusercontent.com/72274851/222212005-75a01710-901f-4f88-9f4d-10e609acd48c.png)


## Dependencies <img src="https://user-images.githubusercontent.com/72274851/222215296-64d3a566-02c2-4ff9-9b8f-9ec5096f5799.png" width="60" height="60"> 
This project requires the following dependencies:

✅ Python 3.7 or higher

✅ Scikit-learn

✅ XGBoost

✅ Pandas

✅ NumPy

✅ Matplotlib

✅ Seaborn

# Usage <img src="https://user-images.githubusercontent.com/72274851/222215440-158ffdc1-8a23-4c7f-81c2-44e864d6d043.png" width="60" height="60"> 

To run the project, follow these steps:

- [x] Clone this repository to your local machine.
- [x] Install the dependencies listed above.
- [x] Open a terminal and navigate to the project directory.
- [x] Run the fake_currency_detection.ipynb Jupyter notebook to train and evaluate the machine learning model.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
