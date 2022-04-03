# Venture Funding with Deep Learning

This prototype application demonstrates machine learning and neural network model through a venture capital firm, Alphabet Soup. This prototype neural network model predicts whether the applicant will be successful if funded by Alphabet Soup. The CSV file contains a variety of information about these businesses, including whether or not they utlimately became successful.

This project is broken down into the following sections: 
* Prepare the data for use on a neural network model.
* Compile and evaluate a binary classification model using a neural network.
* Optimize the neural network model.

## Technologies
Click on the links below for documentation on each of the technologies used. This project uses the following libraries and dependencies:
+ [**Anaconda**](https://docs.anaconda.com/): an open source package and environment management system.
+ [**JupyterLab**](https://jupyterlab.readthedocs.io/en/stable/): an extensive environment using web-based user interface designed for data analysis. 
+ [**Pandas**](https://pandas.pydata.org/docs/getting_started/index.html): (included in Anaconda) a Python package data analysis toolkit.
+ [**scikitlearn**](https://scikit-learn.org/stable/install.html) an open source machine learning library that supports supervised and unsupervised learning. It also provides various tools for model fitting, data preprocessing, model selection, model evaluation, and many other utilities. 
+ [**TensorFlow**](https://www.tensorflow.org/install): an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.

## Installation Guide
Check to ensure that Jupyterlab is installed on your machine by entering the following into your environment using `conda list`. If any of these techologies are not installed into your environment, use the corresponding codes in your terminal: 

TensorFlow 2.0 library has several dependencies, should already be installed in the default Conda environment. 
```
pip install --upgrade tensorflow
```

### Instructions to Use JupyterLab

To launch JupyterLab:
  1. Open terminal window, and type `conda activate dev`.
  2. Type `jupyter lab`. JupyterLab user interface should open in your browser. 
      a. Or copy and paste one of the URLs: "http://localhost:8888/lab?token=..." into web browser. 

To exit JupyterLab:
  1. On your web browser, use the Run button to shut down any running kernel sessions.
  2. On the menu bar, on the File menu, select Shut Down. 
  3. Okay to close tabs once a dialog box with "Server stopped" message indicates the server has stopped. 
  4. Navigate to terminal window, where you launched JupyterLab and type `conda deactivate`. This will return you to your `base` environment. 

## Usage 

1. Clone the repository `https://github.com/leighbadua/venture_funding_with_deep_learning.git`
2. Using your terminal, activate the environment and launch jupyter lab (instructions mentioned above). 
3. Launch `venture_funding_with_deep_learning.ipynb` in JupyterLab

### Import other required libraries and dependencies: 

![image](https://user-images.githubusercontent.com/96001018/161419422-8e10b94e-afd2-4efb-af9c-9674719b3893.png)


### **Prepare the Data to be Used on the Neural Network Model**

![image](https://user-images.githubusercontent.com/96001018/161419046-79ab6696-1ebe-4553-bbd7-12ac8c870c77.png)

The following image uses `OneHotEncoder` to encode the dataset's categorical variables. It places the encoded variables into a new DataFrame.

![image](https://user-images.githubusercontent.com/96001018/161419396-9a6323cb-7733-42f7-b602-a4dc57999364.png)

The following image shows the features (`X`) and target (`y`) datasets, and split them into training and testing datasets. 

![image](https://user-images.githubusercontent.com/96001018/161419546-c784226e-ebb3-4f6a-b30c-9519555ea34b.png)
![image](https://user-images.githubusercontent.com/96001018/161419572-e99051c2-4b0e-4f6c-bc30-7d9929e65178.png)

Use scikit-learn's `StandardScaler` to scale the features data. 

![image](https://user-images.githubusercontent.com/96001018/161419592-b8ae76ef-7ab1-466d-afd9-465effea871f.png)


### **Compile and Evaluate a Binary Classification Model using a Neural Network**

![image](https://user-images.githubusercontent.com/96001018/161419644-51a92aeb-f3b0-4a6f-87dc-d044c627cf91.png)

![image](https://user-images.githubusercontent.com/96001018/161419655-b48687de-553b-4705-8063-3e9c5bd93e66.png)

![image](https://user-images.githubusercontent.com/96001018/161419672-3079f17b-069b-4f4f-afc0-61ca46ff346f.png)
![image](https://user-images.githubusercontent.com/96001018/161419681-8211e6a6-76af-4573-a5f1-32468e2d463a.png)


### **Optimize the Neural Network Model**

[**Alternative Model 1**]
![image](https://user-images.githubusercontent.com/96001018/161419756-0a41be83-6a36-45d6-88ee-cf32de874932.png)
![image](https://user-images.githubusercontent.com/96001018/161419773-ccfb6d59-efc9-42e0-b319-3a0a31cf291f.png)


[**Alternative Model 2**]
![image](https://user-images.githubusercontent.com/96001018/161419892-9f9fcd09-ac1f-4054-a97e-347f802a7136.png)
![image](https://user-images.githubusercontent.com/96001018/161419916-0ec74d2f-ab8f-4769-aa03-da31e1e3b7fc.png)

[**Final Display of Accuracy Scores Achieved from Each Model**]
![image](https://user-images.githubusercontent.com/96001018/161419979-50cc86b1-dfd3-46e8-acc0-bf71a6f631b0.png)
![image](https://user-images.githubusercontent.com/96001018/161419992-2e99ac42-ed6d-4b17-b031-0fc844ef1b59.png)
![image](https://user-images.githubusercontent.com/96001018/161420003-c35e3865-f752-44c1-828f-a131e7b119b1.png)

**Each model was saved as an HDF5 file, located in the Resources folder.**



## Contributors

Leigh Anne Badua leighbadua@gmail.com 


## License

MIT


