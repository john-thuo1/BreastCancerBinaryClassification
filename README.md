# **BreastCancerDiagnosticTool**
The repository contains code implementation of a Breast Cancer Diagnostic Tool that determines whether a given Patient's Mammogram Image is Benign or Malignant.
VGG19 model (A pre-trained model), which is 19 layers deep and able to classify 1000 images of 1000 different categories with 93.75% accuracy.<br />
More details on the architecture of VGG19 can be found here : [VGG-19 Convolutional Neural Network
](https://blog.techcraft.org/vgg-19-convolutional-neural-network/) <br />

The project has been hosted on Streamlit Community Cloud. Find the link below <br />
  **Live Project : [breast-cancer-tool.com](https://johnthuo1-breast-cancer-tool-streamapp-647vh4.streamlit.app/)** <br/>
 
 # Model Performance 
 The model I am using is too big(140mb) and I have already exhausted my Github data quota. If you want to try it on your local machine,
 download the model from this [link](https://drive.google.com/file/d/1-T5H_8jIqT0VTvQZYLAWucx3gRcapny_/view?usp=sharing) <br />
 I have modified the project to use the model I trained from scratch(trainedModel.h5) instead of the pre-trained  model(vgg19breastCancerClassifier.h5) due to the github lfs data quota limit.
 
  ![image](https://user-images.githubusercontent.com/108690517/236889935-f8a160ec-2379-4730-85dd-838200d36066.png)
  
# **Testing the project**
I have included a few images you can test the application with in the Images directory. However, you can use your own images. For now, try using breast cancer images. 
In later modifications of the project, I will include a functionality to tell whether the image uploaded is breast cancer related or not. 

  # **Limitations of the Project:**
1. The model was trained using more Benign cases than malignant. Hence on rare occasions, its predictions may be skewed towards benign.
2. The data was small(1312 images). The more the data used, the more efficient the model will be in predicting accurately. Hence the small train data also affected the accuracy of the model.
  

  
 
