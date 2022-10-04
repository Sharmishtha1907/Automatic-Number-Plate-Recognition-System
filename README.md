# Automatic-Number-Plate-Recognition-System

Smart City Application using AI Technique
PROBLEM STATEMENT:
    Smart City Application using AI Technique: Here I have made a model of an Automatic Number Plate Recognition System that reads the license plate of a vehicle in python that implements the concept of AI. It is used in majority for surveillance in Smart Cities.

Introduction :
This project is based on the concepts of AI involving computer vision and deep learning. This project uses the pre trained model of an OCR available as EasyOCR package for python to read the characters on license plate. The libraries and tools that have been used to implement the model are:
1.	Google Colab: It is a cloud-based Integrated Development Environment that I used to create my deep-learning model.
2.	Opencv: OpenCV is a Python open-source library, that is used for computer vision in Artificial intelligence, Machine Learning, face recognition, etc.
3.	Imulits: A collection of convenience functions which makes image processing functions such as translation, rotation, resizing, skeletonization, displaying   Matplotlib images, sorting contours, detecting edges easier with open cv.
4.	Matplotlib: basic level graph plotting library in python that serves as a visualization utility.
5.	Numpy: Python library that is utilized for working with array or matrix.
6.	EasyOCR: Package to implement OCR.
More about EasyOCR:
Created by Jaided AI company, Easy OCR is a python library that is capable of converting images to text. It is one of the easiest way to implement OCR that supports more than 70 languages. It can process multiple language at the same time.
Pre-requites:
Before proceeding with ANPR we are required to have knowledge about Artificial Intelligence and Machine Learning. A prior knowledge of programming language that is capable of implementing ML such as python. We also need to visualize the steps required in ANPR and awareness of all libraries that we are going to use.
Theory: 
Security has always been a major concern for humanity. These days video surveillance have been installed in various places such as schools, colleges, hospitals, shops, parking lots, etc. With the recent advancement in technology and introduction of concepts of AI and ML such as image processing, visualization, computer vision and deep learning, it has become possible to make these cameras smarter by training them to process information from video feed.
ANPR stands for automatic number plate recognition, is a technology that uses optical recognition to read vehicle registration plates. ANPR has wide scale application such as in surveillance, toll booths, parking lots etc.
METHODOLOGY: 
This project illustrates AI techniques for Smart City Application through an Automatic Number Plate Recognition System. In this project, digital image processing prototype is designed that detects the license plate of a vehicle and reads its components using an OCR.
 
This is implemented in three steps:
1.	Detecting license plate: The process starts with reading the image then converting it into grayscale. The image is read in layers of color – BGR, Blue-Green-Red respectively forming a 3D matrix, therefore in order to reduce the size of the image we convert it into grayscale which is 2D matrix. This makes the program faster. In addition to this, grayscale enhances the image and makes visualization easier than that of colored images. After this we apply bilateral filter to blur the background and reduce noise to imply more focus on the vehicle and the license plate. Now, we find edges to localize the license plate using canny edge and then we find contours using the respective edged image. The next step compromises of finding contours of area that represent a rectangle, that is the shape of the license plate and storing the edge points position in a variabl
2.	Character Segmentation: Once the license plate is detected it is cropped and masked over a blank image. This is done using open cv and numpy.        
3.	Character Recognition: The image that we obtained at the end of segmentation contains some character symbols or alphabets engraved on it. We perform OCR (Optical Character Recognition) to detect the unique identity of the vehicle. To perform OCR we are using the pre-trained OCR model – Easy OCR package.

Limitations of model:
The accuracy of the model depends solely on the quality of the images such as clarity, orientation, light exposure, size, etc. In worst case scenario the model fails to detect the license plate correctly. In such cases we can change kernel size or sigma value while finding edges or contours, but in the end we have to rely on machine learning or improve the quality of image.

APPLICATION OF ANPR:
1.	Vehicle access control at gate barriers.
2.	Data collection in Smart Cities.
3.	Surveillance 
4.	Toll Booths 
5.	Traffic management 
6.	Ticketless Parking

CONCLUSION:
This project has successfully implemented AI to read license plate of a vehicle. The The project completely relies on the machine learning in order to execute and give the desired output.


 
