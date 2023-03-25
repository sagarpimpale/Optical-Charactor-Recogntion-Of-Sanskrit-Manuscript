Objective:- OCR Recogntion And bounding Box Creation On Sanskrit Manuscript.

Requirements:
	Libraries:
		Computer Vision
		numpy
		pdf2image
		json
Installations:
First we need to install openCV using 'pip install opencv-python'
then we need to install numpy using 'pip install numpy'
also we need pdf2image for conversion of input pdf file into jpg for text extraction by using 'pip install pdf2Image'
for saving coordinates in json file we need to import json file.


Explaination:
	we used jupyter notebook as environment
	we converted the input pdf file into image files.
	then we used computer vision to identify Sanskrit text and creating bounding box around each line.
	 we used numpy for creating bounding box with specific coordinates and storing them  in a json file.

Output:
	the output is generated in the same directory where notebook is open.
	we will get all the pages of pdf in jpg format
	then we will get line by line sanskrit text in bounding boxes in seperate jpg files.
	then json file with coordinates is generated.
	#for convenience purpose we have stored all the generated image files in output folder

created by  : Sagar Pimpale 
Email 	: sagarpimpale19@gmail.com
contact	: 7709465298

