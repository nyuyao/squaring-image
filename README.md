This is the README file for this application. 

The following instruction is for MAC users:

In order to run this web application, there are some things you must do to prepare the ideal environment. 

One of the first things you need to do is to make sure you have Python downloaded. To check this, you can just type python in your shell, where you should see some code that resembles the following: 

Python 3.7.0 (v3.7.0:1bf9cc5093, Jun 26 2018, 23:26:24) 
[Clang 6.0 (clang-600.0.57)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>>

If you do not have Python already installed, you can download the latest version from this link: 
https://www.python.org/downloads/

Once Python is downloaded, you're going to want to install pip if you do not have it already. pip is an easy to use installer for packages. If you do have pip and you find out it is outdated, your shell will provide you with directions for how to update pip. 

After pip is installed, you are going to want to download virtualenv. Virtualenv provides you with an isolated Python environment, which is more practical than installing packages systemwide and also allow you to install packages without administrator privileges. you can visit this webpage: http://flask.pocoo.org/docs/0.12/installation/  where it will tell you to do the following:

$ sudo pip install virtualenv

Once you have virtualenv installed, just open a shell and create your own environment. you can create a project folder and a venv folder within:

$ mkdir your_file_name
$ cd your_file_name
$ virtualenv venv

Then to activate the corresponding environment. On OS X and Linux do: $ . venv/bin/activate. Once the above is done, it is time to download Flask. To do so, you just need to enter the command pip install Flask in the shell prompt. To verify you that Flask can be seen by Python, type python into your shell. Then at the Python prompt, try to import Flask. 

>>> import flask

To exit out of the Python prompt, simply type quit() 

Once Flask is on the machine, you should download OpenCV since we will be using it to interact with the images. To do this, type the command pip install opencv-python.

Once done, you need to run app.py file, this will allow you to see the pages on your browser. To see the pages, copy the IP address the shell gives you: http://127.0.0.1:5000/

Mannual for web users:

This is the Squaring Image Web Application Interface. You will just have to select your image file, select the resizing mode (use side length / use ratio), and input your parameter. This web could enlarge or shrink the images. But the performance of shrinking images is the best. After submitting the image and parameters, you will be allowed to download the image squared in png format.



