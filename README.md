# Google_MLCC_1
Facial recognition system to identify or verifying a person from video.
Code Requirements:
•	You need to install conda for python for dependencies for machine learning.
•	For install new library just type on command terminal ‘pip install <library name>


Description:
	Facial recognition system to identify or verifying a person from video.

For training:
1.	Network used – inception network
2.	Original paper – Facenet by Google
Compile and run 
Preconditions:
•	Python 3.x
•	Tensorflow  
•	Dlib
•	Opencv3
•	Keras
•	h5py
•	scipy
•	numpy
Strongly recommended to install:
•	nVidia CUDA Toolkit 8.0 or higher version
•	nVidia cuDNN GPU accelerated deep learning framework
Procedure:
•	For train model run Train-inception.py. but here it already trained model and save it as .h5 which loaded at runtime.
•	You need to have imge in /dataset folder. You can paste your image or you can take image using web cam. For doing that run gather_data.py 
•	Run detect_face.py

