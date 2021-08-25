Electrical Substation extraction from images

This is an Implementation for electrical substation extraction from images provided using Machine Learning and Deep-Learning 
techniques.

Prerequisites You must have installed Scikit Learn, Pandas ,numpy,tensorflow , keras , cv2 .

Project Structure This project has five major parts which has to be executed serial wise as mentioned below :

------- code implementation start------
1) opencv2.ipynb :This contains the code for our project which extracts the masks from the given images and dimensions
provided at link

2) Mask_prediction.ipynb : This contains the code for implementation of Prediction Mechanism for extracting the masks
for the electrical substations from the test images 
**The code file has all the extra installion procedures mentioned run each line of code for successful termination  

3)Final_preprocessing.ipynb and Collage.py : These files contains the codes for storing the masks generated and rertiving
the required format for submission and collage.py helps in processing the masks to a mosaic format of 3750x3750 img 

---------code implementation ends-------

4) p_test_images.zip and final_image.jpg : contains the mask images predicted for each of the test image and final_image is
the mosaic format i.e 3750x3750 format of the predicted mask

5) out_imds.npy : Is the evaulation file as specified format from the predicted mosaic mask 

Other files:

1)npy_files: consist of npy format of each individual predicted mask

2)tmpch14e8gh.jpg: Is the collage /Mosiac image  

3) .py files : which consist of all the code files in .py format (note:This format is share for submission purpose however 
the original code was built and run in .ipynb format) 

4) ML based electrical substation extraction.pdf : a intial write up paper regarding the methodology followed in the process

NOTE: Please check the path of the local system before loading the files/folders since it varies from system to system
any dependency which needs to be downloaded is mentioned as eg : (!pip install keras-unet-collection) the code was built as 
.ipynb on Google -colab platform however the .py format files also has been shared
