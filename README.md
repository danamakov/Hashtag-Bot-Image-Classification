# #Hashtag Bot – Computer Vision
This document organizes all the files related to the project.
I recommend you to read the “Final Document” to have a more theoretical background about the project, the process, its results and future recommendation for further work.

### The files:
* Final_Documentation.pdf - a document that summaries the project.
* X1.pkl, y1.pkl … X13.pkl, y13.pkl files – pickle files which contain the images’ numpy array and tags - These files not in the repository but you can create the files by the "create data.ipynb" file.
* keywords.tsv000 - the dataset keywords (not in the repository).
* photos.tsv000 - the photos information (not in the repository).
* hashtag presentation.pdf.

#### Models’ notebooks:
* create data.ipynb - create the data by converting each picture from the web - to array, and keep it in pickle files (only run once).
* create vgg model.ipynb - create the model (only run once).
* create Inception V3 model.ipynb - create the model (only run once).
* create XCeption model.ipynb - create the model (only run once).
* train vgg model.ipynb - train the model.
* train Inception model.ipynb - train the model.
* train XCeption model.ipynb - train the model.
* Utils.ipynb - contain functions.
* telegram.ipynb - create and run the Telegram Bot.

#### Models’ weights and history files
(not in the repository, but will be saved after model training):
-	Inception_model.h5
-	vgg_model.h5
-	Xception_model.h5
-	Saved_model_inception.pb 
-	Saved_model.pb

In order to run the telegram bot, please run telegram.ipynb notebook and follow this link (from a desktop or a phone client):
https://t.me/Pic_hashtag_bot

### Links
| Plugin | LINK |
| ------ | ------ |
| GitHub | https://github.com/danamakov/Hashtag-Bot__Image-Classification.git |
| Telegram Bot | https://t.me/Pic_hashtag_bot |
| Unsplash | https://unsplash.com/ |
