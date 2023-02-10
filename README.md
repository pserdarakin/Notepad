# Notepad

Overview

This code is an implementation of a basic text editor using PyQt5, a popular GUI library for Python.
The text editor features a text area, a clear button to clear the text, an open button to open a text file, and a save button to save the contents of the text area to a file.
Additionally, it also implements a menu bar with options to open, save, clear, and exit the text editor.

Requirements

In order to run this code, you will need to have Python 3 installed on your machine, along with the following libraries:

>PyQt5
>sys
>os

Running the Code

To run the code, simply execute the following command in your terminal/command prompt:

python3 notepad.py

Code Structure

The code is structured in two classes: Notepad and Menu.
The Notepad class contains the implementation of the text editor and its buttons, while the Menu class contains the implementation of the menu bar.

How it works

The code creates an instance of the Menu class, which in turn creates an instance of the Notepad class and sets it as the central widget. 
The menu bar is created using the menuleri_olustur method, which adds a Dosya (File) menu with options to open, save, clear, and exit the text editor.
The appropriate action is triggered based on the selected menu item.
The text area, clear button, open button, and save button are implemented in the Notepad class.
The clear button triggers the yaziyi_temizle method, which clears the contents of the text area.
The open button triggers the dosya_ac method, which opens a file dialog to select a text file to be opened.
The save button triggers the dosya_kaydet method, which opens a file dialog to specify the file name and location to save the contents of the text area.
