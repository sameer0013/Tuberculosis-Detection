### TUBERCULOSIS DETECTION


It detect whether a person has tuberculosis or not by using Chest X-rays of humans ,it shows responses like "Tuberculosis Detected"( for X-rays having TB) or "Tuberculosis Not Detected"( for other X-rays), for detection i made a lenet CNN model with some extra dense layers from scratch and [here is the link of that](https://github.com/sameer0013/Tuberculosis-Detection/blob/main/mymodel.h5),
	you can also check visual image of [model.h5](https://github.com/sameer0013/Tuberculosis-Detection/blob/main/mymodel.h5.png).

This shows what pooling layers, filter size and activation functions i used for model building and also this image is genertaed by netron( Netron is a viewer for neural network, deep learning and machine learning models) you can check your builded model here just go to the website of [netron](https://netron.app/) you can also check there github for more details.

and ya also i train this model with [dataset of kaggle](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset).
Kaggle is an online community platform for data scientists and machine learning enthusiasts.

	
	
## How to use

1) If possible i recommend you to create a virtual environment on your local system as a VE has some own benfits like 
		VMs( Virtual machines) are isolated from one another and have their own hardware, you can create a VE using python or Anaconda.
		In my case i am using Anaconda. you can read about it on anaconda website.
		
	
2) Now, working starts from here, first clone this repositary on your system by running the command in your system's terminal. 
		
		git clone https://github.com/sameer0013/Tuberculosis-Detection.git
		
3) Now, you have to install all the libraries or requirements. just run on Terminal.
	
		pip install -r requirements.txt
		
4) After installation is done, you have to run this final command:
		
		streamlit run app.py 
		
	open the generated link and hurray!! you are now able to see what i really made. 

5) Now, to check if it is working or not you have to provide it with a image of chest X-ray 
		
	`Warning: Image other than chest X-rays will create an error as the title define its aim is only for Tuberculosis Detection.`
		
	
and yes if you dont have dataset for testing worry not you can get it from [kaggle](https://www.kaggle.com/datasets/raddar/chest-xrays-tuberculosis-from-india)
