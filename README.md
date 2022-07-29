# Emotion-Based-MusicPlayer

“Emotion-based music player” captures the user's emotion using a webcam from the front end and plays music according to the emotion. For example if the user's facial expression is sad then the application would play a sad song. 

This is front end ,when user click on "start camera"  button it will start web camera.
<img src="images/1.jpg" width="100%" align="top-left" alt="" />

when "start face reading" button will be clicked ,applicaiton will start imotion detection.
<img src="images/2.jpg" width="100%" align="top-left" alt="" />

It will detect emotion for 5 second and then music will be played in play button as you can see in the follwing image
<img src="images/3.jpg" width="100%" align="top-left" alt="" />

If user wants to close web camera while face is not being read for emotion detection,then user can click on "close camera",but song is being played still.
<img src="images/4.jpg" width="100%" align="top-left" alt="" />

### Install conda
#### step1
#### download the Miniconda installer for Linux:- 
https://repo.anaconda.com/miniconda/Miniconda3-py39_4.12.0-Windows-x86_64.exe

#### step2
#### run downloaded file
bash Miniconda3-latest-Linux-x86_64.sh
Press Enter to review the license agreement. Then press and hold Enter to scroll
Enter “yes” to agree to the license agreement.


### Create conda environment 
conda create -n myenv python=3.9

### install requirements.txt file
pip install -r requirements.txt
     
### get data set using following link


## Install google cloud sdk

To install google cloud run follwoing command in terminal

### Step 1
Install some dependencies
sudo apt-get install apt-transport-https ca-certificates gnupg
 
 
### step 2  
Add the gcloud CLI distribution URI as a package source. If your distribution supports the signed-by option, run the following command:
echo "deb [signed-by=/usr/share/keyrings/cloud.google.gpg] https://packages.cloud.google.com/apt cloud-sdk main" | sudo tee -a /etc/apt/sources.list.d/google-cloud-sdk.list
 
### Step 3
Import the Google Cloud public key. If your distribution's apt-key command supports the --keyring argument, run the following command:
curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key --keyring /usr/share/keyrings/cloud.google.gpg add -
 
### Step3 
Update and install the gcloud CLI
sudo apt-get update && sudo apt-get install google-cloud-cli



