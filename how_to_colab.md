# Running the tutorials on Google Colaboratory:
All of the seminars were created using Jupyter Notebooks. In order to reduce the time spent on installing various software, we have made sure that all of the seminars are Google Colaboratory friendly. 

Colaboratory is a free Jupyter notebook environment that requires no setup and runs entirely in the cloud. With Colaboratory you can write and execute code, save and share your analyses, and access powerful computing resources, all for free from your browser. All of the notebooks already contain all the set-ups needed for each particular seminar, so you will just be required to run the first several cells.

There are two ways to access our seminars through Google Colaboratory (tested on Google Chrome, version 76.0.):
1. Opening the corresponding seminar's Jupyter Notebook in Github and clicking the button "Open in Google Colab":
![image01](/img/img01.png)
2. Through https://colab.research.google.com/github/adasegroup/ML2020_seminars: 
  
   * First go to https://colab.research.google.com/github/adasegroup/ML2020_seminars
   * In the pop-up window, sign-in into your GitHub account 
     ![image0](/img/img0.png)
   * In the opened window, choose the notebook correspodning to the seminar
  ![image1](/img/img1.png)


* After you have opened the notebook one way or another make sure that you are signed-in into your Google account
![image2](/img/img2.png)
* Try to run the first cell, you will get the following message:
![image3](/img/img3.png)
Press ```RUN ANYWAY```
* For the message ```Reset all runtimes``` press ```YES```
![image4](/img/img4.png)

Sometimes you will need to download seminars' subdirectories as packages in order to download all the material for the seminar. We will insert the cells with the corresponding code into the seminar if needed, so, if it is the case, make sure you run the cells containing the following code first:
* For downloading the github subdirectory containing the seminar:

```!pip install --upgrade git+https://github.com/adasegroup/ML2020_seminars.git#subdirectory=<name of seminar subdirectory>```

* For declaring the data files' path: 
```
import pkg_resources
DATA_PATH = pkg_resources.resource_filename('name_of_the_installed_seminar_package', 'data/')
```
# Using GPU with Google Colaboratory:
Sometimes for computationally hard tasks you will be required to use GPU instead of default CPU, in order to do this follow these steps:
* Go to ```Edit->Notebook Settings```
![image5](/img/img5.png)
* In the ```Hardware accelerator``` field choose ```GPU```
![image6](/img/img6.png)
![image7](/img/img7.png)

# Saving and downloading the notebooks
You can save your notebook in your Google Drive or simply download it, for that go to ```File->Save a copy in Drive``` or ```File->Download.ipynb```.
![image8](/img/img8.png)



If you would like to see more tutorials regarding Google Colaboratory have a look at this notebook: https://colab.research.google.com/notebooks/welcome.ipynb
