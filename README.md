# Malaria cell detection
Human cells with and without malaria viruses are feed to the model and the model detects if the cell is infected with malaria or not.
The dataset can be downloaded from the location https://drive.google.com/drive/folders/1IxJI_vJQdjTs4o8C4heJeSCj58bGsn7H?usp=sharing

The dataset is lodaed using a ImageDataGenerator into a normal CNN model having 4 convolutional layers and 
also into a CNN model built from VGG16 using transfer learning.
The transfer learning model has been trained only for 1 epoch due to hardware and time constraints but it can be trained for more number of epochs for better results.
