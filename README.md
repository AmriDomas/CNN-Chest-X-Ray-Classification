**CNN:CHEST XRAY CLASSIFIER (NORMAL And PNEUMONIA)**

**Muh Amri Sidiq**

Pneumonia is an infection that causes inflammation of the air sacs (alveoli) in one or both lungs. The alveoli may fill with fluid or pus, disrupting the oxygen exchange process. We use CNN Deep Learning tensor flow keras and application VGG1

**Load Data**
Data image convert to 224x224x3 (RGB) according to pre-train VGG19

**Data Visualization**

![image](https://github.com/user-attachments/assets/3740edf1-86fc-4521-bbb1-a8e040bb3199)

Insight: For normal more dark than pneumonia

**Exploratory Data Analysis**

![image](https://github.com/user-attachments/assets/9c04997d-5199-4c11-8df2-5a78eab8ac71)

**Modeling**

We use CNN with pre-train VGG19

![image](https://github.com/user-attachments/assets/415eaa73-ba35-4195-a378-974608deae70)

the ability of the model to separate data classes by 98%

![image](https://github.com/user-attachments/assets/9eaf10bd-0e77-452f-ab02-3874e69b294b)

**Conclussion**

From build modeling above we can use deployment for predict new data test, with Accuracy model validation until 98%

**Refrence**

1. https://www.kaggle.com/code/madz2000/pneumonia-detection-using-cnn-92-6-accuracy
2. https://www.analyticsvidhya.com/
3. https://www.tensorflow.org/guide/keras
4. https://keras.io/



