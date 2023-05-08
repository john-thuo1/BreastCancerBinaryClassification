# **BreastCancerDiagnosticTool**
The repository contains code implementation of a Breast Cancer Diagnostic Tool that determines whether a given Patient's Mammogram Image is Benign or Malignant.
VGG19 model (A pre-trained model), which is 19 layers deep and able to classify 1000 images of 1000 different categories with 93.75% accuracy.<br />
More details on the architecture of VGG19 can be found here : [VGG-19 Convolutional Neural Network
](https://blog.techcraft.org/vgg-19-convolutional-neural-network/) <br />

The project has been hosted on Streamlit Community Cloud. Find the link below <br />
  **Live Project : [breast-cancer-tool.com](https://johnthuo1-breast-cancer-tool-streamapp-647vh4.streamlit.app/)** <br/>
 
 # Model Performance 
 
  ![image](https://user-images.githubusercontent.com/108690517/236889935-f8a160ec-2379-4730-85dd-838200d36066.png)


Based on the confusion matrix provided, we can generate a summary of the results as follows:  <br />

The given confusion matrix shows the performance of a binary classification model for tumor detection. Out of 32 cases, 20 benign tumors were correctly identified as benign (true negative), while 10 malignant tumors were correctly identified as malignant (true positive). There were 2 cases of false negatives where malignant tumors were misclassified as benign, but no false positives where benign tumors were misclassified as malignant. <br />
  
# **Testing the project**
I have included a few images you can test the application with in the Images directory. However, you can use your own images. For now, try using breast cancer images. 
In later modifications of the project, I will include a functionality to tell whether the image uploaded is breast cancer related or not. 

  # **Limitations of the Project:**
1. The model was trained using more Benign cases than malignant. Hence on rare occasions, its predictions may be skewed towards benign.
2. The data was small. The more the data used, the more efficient the model will be in predicting accurately. Hence the small train data also affected the accuracy of the model.
  

  
 
