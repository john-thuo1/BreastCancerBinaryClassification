# **BreastCancerDiagnosticTool**
The repository contains code implementation of a Breast Cancer Diagnostic Tool that determines whether a given Patient's Mammogram Image is Benign or Malignant.
VGG16 model (A pre-trained model), which is 16 layers deep and able to classify 1000 images of 1000 different categories with 92.7% accuracy.<br />
More details on the architecture of VGG16 can be found here : [Everything you need to know about VGG16](https://medium.com/@mygreatlearning/everything-you-need-to-know-about-vgg16-7315defb5918) <br />

The project has been hosted on Streamlit Community Cloud. Find the link below <br />
  **Live Project : [breast-cancer-tool.com](https://johnthuo1-breast-cancer-tool-streamapp-647vh4.streamlit.app/)** <br/>
 
 # Model Performance 
 
 ![image](https://user-images.githubusercontent.com/108690517/236040775-4b0fda34-8ab7-431f-94f6-53b391a31300.png)

  

Based on the confusion matrix provided, we can generate a summary of the results as follows:  <br />

1. True Positive (TP): The model correctly predicted 21 cases as benign (positive) when they were actually benign (actual positive). <br />
2. True Negative (TN): The model correctly predicted 10 cases as malignant (negative) when they were actually malignant (actual negative).  <br />
3. False Positive (FP): The model incorrectly predicted 1 case as benign (positive) when it was actually malignant (actual negative).  <br />
4. False Negative (FN): The model did not make any false negative predictions in this case, i.e., it did not predict any malignant cases as benign. <br />

Overall, the model performed well, achieving a high accuracy, precision, and recall. However, it did make one false positive prediction, which is something to be aware of when interpreting the results.  <br />
  
  # **Limitations of the Project:**
1. The model was trained using more Benign cases than malignant. Hence on rare occasions, its predictions may be skewed towards benign.
2. The data was small. The more the data used, the more efficient the model will be in predicting accurately. Hence the small train data also affected the accuracy of the model.
  

  
 
