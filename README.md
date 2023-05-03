# **BreastCancerDiagnosticTool**
The repository contains code implementation of a Breast Cancer Diagnostic Tool that determines whether a given Patient's Mammogram Image is Benign or Malignant.
VGG16 model (A pre-trained model), which is 16 layers deep and able to classify 1000 images of 1000 different categories with 92.7% accuracy.<br />
More details on the architecture of VGG16 can be found here : [Everything you need to know about VGG16](https://medium.com/@mygreatlearning/everything-you-need-to-know-about-vgg16-7315defb5918) <br />

  **Live Project : [breast-cancer-tool.com](https://johnthuo1-breast-cancer-tool-streamapp-647vh4.streamlit.app/)** <br/>
 
 # Model Performance 
 
 ![image](https://user-images.githubusercontent.com/108690517/236040775-4b0fda34-8ab7-431f-94f6-53b391a31300.png)

  
  
  # **Limitations of the Project:**
1. The model was trained using more Benign cases than malignant. Hence on rare occasions, its predictions may be skewed towards benign.
2. The data was small. The more the data used, the more efficient the model will be in predicting accurately. Hence the small train data also affected the accuracy of the model.
  

  
 
