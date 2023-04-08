# Fake-Currency-Detection-using-AI-ML

![image](https://upload.wikimedia.org/wikipedia/en/1/18/Will_Smith_slaps_Chris_Rock.jpg)

# Inspiration: <img src="https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/inspiration.png" width="60" height="60"> 
Machine learning is evloving day by day and is solving many real life problems that are life changing. One such application is violence detection which uses machine learning model trained with lots of videos including violence to detect violence in live stream and/or in pre-recorded video. Violence detection includes detection of physical beating, stabbing, robbery, firing of gun, riot, hijack, terrorist attack, etc. 

# Methodology: <img src="https://github.com/LalithNarayanan/real-life-violence-detection/blob/main/Icons/solution.png" width="60" height="60">  

This project aims to develop a machine learning model to predict the authenticity of banknotes. The model uses features such as variance, skewness, kurtosis, and entropy of wavelet-transformed images of the banknotes. The target value is 0 for real banknotes and 1 for fake banknotes.

## How i made it <img src="https://user-images.githubusercontent.com/72274851/222215141-6ced575e-414b-4088-bd99-d78921f80f66.png" width="60" height="60"> 

✅ The dataset used in this project is the Banknote Authentication Dataset from the UCI Machine Learning Repository. 
✅ It contains 1,372 instances of banknotes, each with five numeric input variables and one binary target variable.
✅ Use a pairplot to plot it ![image](https://user-images.githubusercontent.com/72274851/222211365-56851fa0-44b4-4a3e-b09c-772935129bb2.png)
✅ Balanced the dataset ![image](https://user-images.githubusercontent.com/72274851/222211438-2bbab41d-9275-4c6c-9c3b-ec4c182ebe42.png)
![image](https://user-images.githubusercontent.com/72274851/222211493-33f11ebb-25a2-466c-b84e-b95ec801cace.png)

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
