# Brain_Tumour-Detection
Basic Website to detect Brain Tumour in initial stages using CNN<br>
__Project Description:__
Brain tumours are not detected until after the symptoms appear at which point sometimes it is too late. The main goal of this system is to identify accurate and meaningful information from the brain MRI images with the minimum errors possible and also try to avoid any human errors. Here we try to accurately detect brain tumour at a faster rate from the given image and classify the image as a tumour or non-tumour image.
In our proposed system, a robotized approach has been identified where X-ray (MRI) gray scale pictures are used for brain tumor recognition where brain tumor pictures are taken as input for our system. The images will be undergoing different pre-processing techniques for building a better accurate model that can detect tumors in the MRI images more accurately and also at a faster rate in initial stages for better chances of survival.
The programmed brain tumor discovery is proposed by utilizing Convolutional Neural Networks (CNN) characterization. Examining outcomes show that the CNN documents pace of **97.5** percent accuracy with low complexity and compared with the all-other state of arts methods.

How to install and run the project:<br>
__XAMPP:__<br>
Step 1: Create database “myflaskapp” in XAMPP.<br>
Step 2: Create three tables: 1.“patient” with attributes p_id,image,result.<br>
                             2.”token” with attributes token,email.<br>
                             3.”users” with attributes id(primary  key),  name, email, password,  gender ,age.<br>
Note: Keep the server on while executing the code.<br><br>

__GitHub:__<br>
Step 1: Download and Unzip the Front-End and Back-End zip files under view raw and save it in a folder.<br>
Step 2: Download the dataset for the brain tumor no and yes image folder from the link<br> https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection and move it to the same folder as of code.<br>
Step 3:Change the path to the path of the folder on your computer.<br>
Step 4: Execute the backend code to train the model.<br> 
Step 5: Open a new terminal and create a virtual environment using the code.<br>
      &ensp;1.pip install virtualenv<br> 
      &ensp;2.virtualenv venv<br>
      &ensp;3.To activate the virtual environment “./venv/Scripts/activate”<br>
Step 6: Install all the packages required.<br>
Step 7: Run the program by giving the command “python manage.py runserver”<br>


