# real-life-violence-detection
#Introduction  <img src="(https://user-images.githubusercontent.com/72274851/222216353-58874ba5-d9cc-4298-baab-4255bbdb0193.png" width="60" height="60">

Machine learning is evloving day by day and is solving many real life problems that are life changing. One such application is violence detection which uses machine learning model trained with lots of videos including violence to detect violence in live stream and/or in pre-recorded video. Violence detection includes detection of physical beating, stabbing, robbery, firing of gun, riot, hijack, terrorist attack, etc. 


DataSet:

The dataset used in this project is the ‘Real Life Violence Situations Dataset’  from the Kaggle Repository published by Mohamed Elesawy.
It contains 1000 Violence and 1000 non-violence videos collected from youtube videos, which includes many real street fights situations in several environments and conditions.


Methodology

We will use a convolutional neural network (CNN) to classify videos as violent or non-violent. We will preprocess the videos by extracting frames and resizing them to a fixed size. We will then train the CNN on these frames.

Workflow:

	Dataset collection: Gather a dataset of videos containing both violent and non-violent scenes. The dataset should be balanced and diverse, containing videos with different lighting 		conditions, camera angles, and types of violence.

	Data pre-processing: Convert the videos to a suitable format and resize them to a fixed resolution. Extract individual frames from the videos and create a dataset of images. Apply 		pre-processing techniques such as normalization, resizing, and augmentation to improve the performance of the transfer learning model.

	Selecting a pre-trained model: Choose a pre-trained model that has been trained on a large dataset of images or videos. Ideally, the pre-trained model should be designed for video 		analysis, such as the Two-Stream Convolutional Neural Network or the Temporal Segment Network.

	Model customization: Remove the last few layers of the pre-trained model and replace them with new layers that are designed for the specific task of violence detection. Freeze the 		weights of the pre-trained layers and only train the weights of the new layers. This process is known as fine-tuning.

	Model training: Train the customized model on the pre-processed dataset. The model should have multiple convolutional layers followed by pooling and activation functions. The output 		of the final layer should be a binary classification of violence or non-violence.

Why oneAPI:
	oneAPI is an open, unified programming model developed by Intel that simplifies development of high-performance applications across different hardware architectures. It provides a single cross-architecture programming model based on industry standards like C++ and SYCL, and includes a set of programming tools and libraries such as compilers, performance libraries, and analysis tools. oneAPI can be applied to various industries including HPC, AI/ML, media and entertainment, finance, and healthcare, where high-performance computing and parallel processing are needed.

Conclusion

Violence detection is an important application of machine learning that can help prevent harm and save lives. By developing a machine learning model to detect violence in videos and in live stream, we can assist emergency services like police, ambulance, fire engine, etc., in identifying potentially dangerous situations.
