# Setting-up-discord.py

## Step 1 | Python
The first step in setting up discord.py is installing python, python is the languge d.py has been developed in. To start the installation head over (here)[python.org] hover over downloads and press download you want to download python 3.8

**IMPORTANT** When running the installer it is very important to tick the box that sais `Click here to enable PATH` since that will allow us to use python from everywhere 

After that just run the automatic installation

## Step 2 | Verifying python
We need to verify that python was installed correctly, the method of verification differs from os to os but i will go over windows and unix systems

**Windows**
First we need to open a terminal this is also the window from where we will run the bot
To open up the terminal click `win + r` and a window named run should pup up, here your should type `cmd` and a black window should pup up, i will refer to this as the terminal
To check that we have python installed successfully we use the command `py -3 --version` the terminal should tell us the version you installed from the website (note this only works for python 3.8 since we gave the command the `-3` flag)

**Unix**
Depending on your os you might have diffrent ways to the open the terminal if you go into you search bar area and type terminal you should be able to get it up otherwise look up how to open the terminal on your system

To check the installation type `python3.8 --version` if python tells you the corret version it installed correctly

## Step 3 | The installation
In order to use discord with python we need to install their api (application programming interface) so that we can talk to discord though python
This method agein differs from os to os

This is the general idea
```py
# Linux/macOS
python3.8 -m pip install -U discord.py

# Windows
py -3 -m pip install -U discord.py
```
If you want more information on installing d.py check the offical documenation (here)[https://github.com/Rapptz/discord.py]

## Step 4 | Getting to the code
In order to run the code we need to navigate to our files using the terminal, the unix and windows terminal is agein diffrent so i will go over each agein.

**Windows**
In the windows terminal we have 3 main commands
```
dir (lists folders and files in your current directory)
cd <folder> (change directory or move into a diffrent folder)
cd .. (move out of the current folder)
```

**Unix**
The unix terminal is a bit more complicated but i will go over the basics here
```
ls (This lists all files in your current directory you can also add the -l flag to make it a list)
cd <folder> (Changes the directory)
cd .. (Moves you out of a folder)
```
Using these 3 commands you should be able to move arround in the terminal, you want to move into your work folder 

## Step 5 | Running the code
Once you have located your files you want to run the code, this is agein diffrent.

**Windows**
```
py -3 <file>.py
```

**Unix**
```
python3 <file>.py
```

And once the bot tells you its ready it should go online
