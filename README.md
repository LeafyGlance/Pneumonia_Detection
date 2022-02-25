# Special Project: Computer Aided Diagnosis for Pneumonia in Chest X-Rays 
* Created a program that can detect if pneumonia is present in an uploaded image
* Used random oversampling of minority class to handle data imbalance
* Performed data augmentation
* Utilized transfer learning on 5 networks (using weights from Imagenet)
* Created ensemble network to handle classification task based on trained networks
* Packaged into a portable executable file

# Program UI
![Program UI](/images/Pneumonia_Detection_UI.png)
* The program can take input in the form of png or jpg files
* Any uploaded image will automatically be resized

# Program Processing a CXR
![Program Processing](/images/Pneumonia_Detection_Processing.png)

# Program Classifying No Pneumonia CXR
![Program No Pneumonia](/images/Pneumonia_Detection_No_Pneumonia.png)
* Displays classification together with a probability

# Program Classifying Pneumonia CXR
![Program Pneumonia](/images/Pneumonia_Detection_Pneumonia.png)
* Displays classification together with a probability
