
This is a repo for the Tanzania AI lab hackathon 2020 & the AI4Dev2020 challenge, where we as the Elixir team created the 1st AI based cancer diagnosis system, built a model comprising of Deep Convolutional Neural Network(CNN) and a web app that screens microscopic images so as to detect cancer tumors, thus increasing speed, accuracy in cancer diagnosis, and testing.

Pitch Video: https://youtu.be/Pfgfh4DJToo
# THE ELIXIR REPOSITORY.
**This is the repository for a Cancer Diagnosis web app system, that detects cancer from microscopic images, developed during the Tanzania AI-LAB hackathon 2020 and The AI4DEV2020 Challenge**

You can learn more about the app and the reason for it's existence via the following link https://www.youtube.com/watch?v=Pfgfh4DJToo


To use the web app, you need to do the following:

**- Create a python virtual environment and install the packages in the requirements.txt file.**

**- Clone the repository to your local device.**

**- Once you open the source code directory, run the terminal and type the following in the terminal -> python manage.py migrate**

**- After migration is done type -> python manage.py runserver**

**- You will get the link to the web app local host, follow the link to run the web app.** 




However on some code-editors such as  Visual-studio code, one may encounter  an error as detailed below which is due to some of the visual studio code redistributables, as we encountered it, this occured on a **Windows OS** device.
we **strongly recommend** the use of a virtual environment on developing and testing this project:

**Could not find the DLL(s) 'msvcp140.dll or msvcp140_1.dll'. TensorFlow requires that these DLLs be installed in a directory that is named in your %PATH% environment variable. You may install these DLLs by downloading "Microsoft C++ Redistributable for Visual Studio 2015, 2017 and 2019" for your platform from this URL: https://support.microsoft.com/help/2977003/the-latest-supported-visual-c-downloads**


Futhermore, for **Linux OS** users, one may get an error **illegal instruction(core-dumped) when importing tensorflow as tf** to solve the error one would need to downgrade the tensorflow cpu by running the following commands on the terminal:

**pip uninstall tensorflow**

**pip install tensorflow==1.5**


This will downgrade the cpu to device capability and prevent the **app from crashing!!**
