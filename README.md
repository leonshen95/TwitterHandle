# 601

EC601
Class Repository for Product Design in ECE


Description:

This project is for downloading images from a twitter feed, labeling the description by image detection, and then convert them to a video.

-----------------------------------------------------------

Instruction: 

1. The program may require you to get an authentication key to set up. Refer to https://cloud.google.com/docs/authentication/getting-started the for instructions on setting up
credentials for applications.

2. Open the terminal and make sure you have a python programming environment. Use the pip to install the package required. Refer to the packages imported at the beginning of the file.

2. Run the ImageDownload.py, the twitter images from a specific user will be downloaded automatically and stored to a folder named "images",

2. Then run the GoogVis.py, the google vision api will auto detect the description of the images and label the tags on each of images. The processed images will be stored in a new folder named "finalimages". Meanwhile, the labelled images will be converted into a video. 

