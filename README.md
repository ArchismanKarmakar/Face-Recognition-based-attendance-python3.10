# Face-Recognition-based-attendance-python3.10

### Recognize The faces And Take Automatic Attandance. :sparkles:

![Face Recognition Logo](https://github.com/kmhmubin/Face-Recognition-Attendance-System/blob/master/Document%20Metarial/Project%20demo%20images/Face-Recognition-Attendance-System-Logo.jpg)


![GitHub](https://img.shields.io/github/license/ArchismanKarmakar/Face-Recognition-based-attendance-python3.10?color=red&style=for-the-badge)

![Issues](https://img.shields.io/github/issues/ArchismanKarmakar/Face-Recognition-based-attendance-python3.10?color=red&style=for-the-badge)

![Forks](https://img.shields.io/github/forks/ArchismanKarmakar/Face-Recognition-based-attendance-python3.10?color=blue&style=for-the-badge)

![Stars](https://img.shields.io/github/stars/ArchismanKarmakar/Face-Recognition-based-attendance-python3.10?color=yellow&style=for-the-badge)

## Motivation :astonished:

We seek to provide a valuable attendance service for both teachers and students. Reduce manual process errors by provide automated and a reliable attendance system uses face recognition technology.

## Features :clipboard:

* Capture Faces automatically
* Train Faces directly by putting raw image of person
* Automatic Recognition of Faces & Attendance
* Live attendance tracking and 24x7 online


## Tech Used :computer:

Build With - 
* Python 3.10.x

Module Used -

```console
certifi==2020.6.20
chardet==3.0.4
click==7.1.2
cmake==3.18.2.post1
decorator==4.4.2
dlib==19.18.0
face-recognition==1.3.0
face-recognition-models==0.3.0
idna==2.10
imageio==2.9.0
imageio-ffmpeg==0.4.2
moviepy==1.0.3
numpy==1.18.4
opencv-python==4.4.0.46
Pillow==8.0.1
proglog==0.1.9
requests==2.24.0
tqdm==4.51.0
urllib3==1.25.11
wincertstore==0.2
scikitlearn
python-csv
```


Face Recognition Algorithms -
* Haar Cascade
* LBPH (Local Binary Pattern Histogram)

Software Used -
* Pycharm 2019.2
* VS CODE 
* Git

## Installation :key:

#### Download or Clone the project

Download using GitHub Desktop

or

You can clone the project with git bash.To clone the project using git bash first open the git bash and write the following code
```
git clone https://github.com/ArchismanKarmakar/Face-Recognition-based-attendance-python3.10.git
```

After download, Open the project using **Pycharm or VSCODE**. Then we have to create an python enviroment to run the program.

#### create enviroment 
First open the terminal or command line in the IDE.Then write the following code.
```
python -m venv env
```
Then activate the enviroment using the code below for windows.
```
.\env\Scripts\activate
```
[ *Notice:*
If your pc don't have virtual enviroment or pip install the follow this link.
[How to create Virtual Enviroment](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) ]

#### Installing the packages

After creating the enviroment on your project let's install the necessary packages. 

![pip isntall demo](https://github.com/kmhmubin/Face-Recognition-Attendance-System/blob/master/Document%20Metarial/Project%20demo%20images/pip%20install_edit_0.gif)

To install those package open the terminal or command line and paste the code from below

```console
pip install certifi==2020.6.20
```
```console
pip install chardet==3.0.4
```
```console
pip install click==7.1.2
```
```console
pip install cmake==3.18.2.post1
```
```console
pip install decorator==4.4.2
```
```console
pip install dlib==19.18.0
```
```console
pip install scikitlearn
```
```console
pip install face-recognition==1.3.0
```
```console
pip install face-recognition-models==0.3.0
```
```console
pip install idna==2.10
```
```console
pip install imageio==2.9.0
```
```console
pip install imageio-ffmpeg==0.4.2
```
```console
pip install moviepy==1.0.3
```
```console
pip install numpy==1.18.4
```
```console
pip install opencv-python==4.4.0.46
```
```console
pip install Pillow==8.0.1
```
```console
pip install proglog==0.1.9
```
```console
pip install requests==2.24.0
```
```console
pip install tqdm==4.51.0
```
```console
pip install python-csv
```
```console
pip install urllib3==1.25.11
```
```console
pip install wincertstore==0.2
```

[ **Notice: During the package installization, sometime it shows some error, to avoid those error you can install those packages as admin. ]

## Test Run :bicyclist:

After creating the enviroment and installing the packages, open the IDE terminal/command line to run the program. Using the code below.

```
py main.py
```
Here is a demo to run the program. I'm Using the Pycharm IDE in my demo.


## How To Use? :pencil:

If you want to use it just follow the steps below.

1. First download or clone the project
2. Import the project to your favourit IDE
3. Create an python enviroment
4. Install all the packages 
5. Change the mail information
6. Run the project using the command line or your IDE Run Button

## Known Bugs :bug:
------------------------------
This project have some bugs.

* <strike>Student Details: In student details folder the **StudentDetails.csv** file don't have ID & name column.This problem show when the program run first time and create the <stong>StudentDetails.csv</strong> file automatically. To soleve the problelm just open the file and add *ID & Name Column* in the file and save it.</strike>
* Auto Attachment: This is not a problem actually. The problem is before sent auto mail we have to manually change the file name. I tried to automate the attachment but i faild.



## Credits :sparkling_heart:

Thanks to [Sumon Chatterjee](https://github.com/) for working with me.

## Licence :scroll:

MIT © [Archisman Karmakar](https://github.com/ArchismanKarmakar) Archisman Karmakar
