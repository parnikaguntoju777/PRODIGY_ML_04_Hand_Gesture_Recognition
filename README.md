**# ✋ Hand Gesture Recognition using CNN**



**## 📌 Project Overview**

This project focuses on building a \*\*Hand Gesture Recognition System\*\* using \*\*Convolutional Neural Networks (CNN)\*\*.  

The model is trained on the \*\*LeapGestRecog dataset\*\* to classify different hand gestures from grayscale images.



This project is developed as part of \*\*Prodigy Infotech – Machine Learning Internship (Task 04)\*\* and follows a clean, modular folder structure.



---



**## 📂 Dataset**

\- \*\*Dataset Name:\*\* LeapGestRecog

\- \*\*Type:\*\* Image dataset

\- \*\*Gestures Included:\*\* Palm, Fist, Thumb, Index, OK sign, C shape, Down, etc.

\- \*\*Image Format:\*\* Grayscale images



Dataset is stored inside:

```text

dataset/leapGestRecog/



Model Used



* CNN (Convolutional Neural Network)



* Layers used:



1. Conv2D
2. MaxPooling2D
3. Flatten
4. Dense

5\. Dropout



* Optimizer: Adam
* Loss Function: Categorical Crossentropy
* Metrics: Accuracy



**📁 Project Structure**

PRODIGY\_ML\_04/

├── dataset/

│   └── leapGestRecog/

├── notebooks/

│   └── hand\_gesture\_recognition.ipynb

├── results/

│   ├── hand\_gesture\_model.h5

│   ├── training\_history.csv

│   ├── accuracy\_plot.png

│   ├── loss\_plot.png

│   ├── predictions.csv

│   ├── confusion\_matrix.png

│   └── test\_accuracy.txt

├── requirements.txt

└── README.md



**How to Run the Project:**



Clone or download the project

Install required libraries:

pip install -r requirements.txt

Open Jupyter Notebook:

jupyter notebook



**Run:**

notebooks/hand\_gesture\_recognition.ipynb

All outputs will be saved automatically in the results/ folder



**📊 Results**



Trained CNN model saved as .h5

Accuracy \& loss graphs

Predictions stored in CSV format

Confusion matrix image

Final test accuracy saved as text file



**🚀 Conclusion**



This project demonstrates how deep learning can be used for real-world hand gesture recognition tasks.

The trained model achieves good accuracy and can be extended for real-time gesture recognition using a webcam.



**🏢 Internship Details**



Internship Provider: Prodigy Infotech

Domain: Machine Learning

Task: Task 04 – Hand Gesture Recognition





**✨ Author**



Parnika Guntoju

Machine Learning Intern 






