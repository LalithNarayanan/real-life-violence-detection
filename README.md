# Real-Life-Violence-Detection-With-oneAPI

![image](https://upload.wikimedia.org/wikipedia/en/1/18/Will_Smith_slaps_Chris_Rock.jpg)

# Inspiration <img src="https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/inspiration.png" width="60" height="60"> 
Machine learning is evloving day by day and is solving many real life problems that are life changing. One such application is violence detection which uses machine learning model trained with lots of videos including violence to detect violence in live stream and/or in pre-recorded video. Violence detection includes detection of physical beating, stabbing, robbery, firing of gun, riot, hijack, terrorist attack, etc. 

# Methodology  <img src="https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/solution.png" width="60" height="60">  

Violence detection using transfer learning involves using a pre-trained Convolutional Neural Network (CNN) on a large dataset, such as ImageNet, and re-purposing it for the task of violence detection. The methodology involves fine-tuning the pre-trained model on a smaller dataset of violent and non-violent videos, and then testing the model on new, unseen videos. Transfer learning can significantly reduce the time and resources required for model training, as it leverages the pre-existing knowledge of the pre-trained CNN.


# Dataset  <img src="https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/Dataset.jpeg" width="60" height="60"> 

The dataset used in this project is the ‘Real Life Violence Situations Dataset’  from the Kaggle Repository published by Mohamed Elesawy.
The dataset contains 1000 Violence and 1000 non-violence videos collected from youtube videos, which includes many real street fights situations in several environments and conditions.
## Glimpse of violence dataset
![image](https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/Screenshot%202023-04-08%20111034.png)


## Glimpse of non-violence dataset
![image](https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/Screenshot%202023-04-08%20111116.png)

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

# Why oneAPI

![image](https://upload.wikimedia.org/wikipedia/en/f/fa/OneAPI-rgb-3000.png)

oneAPI is an open, unified programming model developed by Intel that simplifies development of high-performance applications across different hardware architectures. It provides a single cross-architecture programming model based on industry standards like C++ and SYCL, and includes a set of programming tools and libraries such as compilers, performance libraries, and analysis tools. oneAPI can be applied to various industries including HPC, AI/ML, media and entertainment, finance, and healthcare, where high-performance computing and parallel processing are needed.

# Result
![image](https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/output.png)

![image](https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/output2.png)

# Conclusion <img src="https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/idea.png" width="60" height="60"> 

Violence detection is an important application of machine learning that can help prevent harm and save lives. By developing a machine learning model to detect violence in videos and in live stream, we can assist emergency services like police, ambulance, fire engine, etc., in identifying potentially dangerous situations.


## Dependencies <img src="https://user-images.githubusercontent.com/72274851/222215296-64d3a566-02c2-4ff9-9b8f-9ec5096f5799.png" width="60" height="60"> 
This project requires the following dependencies:

✅ Python 3.7 or higher

✅ keras

✅ TensorFlow

✅ Pandas

✅ NumPy

✅ Matplotlib

✅ Seaborn

# Usage <img src="https://user-images.githubusercontent.com/72274851/222215440-158ffdc1-8a23-4c7f-81c2-44e864d6d043.png" width="60" height="60"> 

To run the project, follow these steps:

- [x] Clone this repository to your local machine.
- [x] Install the dependencies listed above.
- [x] Open a terminal and navigate to the project directory.
- [x] Run the model.ipynb and then run the implementation.ipynb.

