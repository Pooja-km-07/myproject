**Title**

**Sign Language Recognition Using Neural Network and Gaussian Blur**

All the source code is available inside SourceCode Directory. It requires python version 3.6 or later as to synchronize with tensorflow.

* winGuiAuto.py available inside source code directory contains the hwnd handler which is used to tweak the default window behavior much similar to windows programming.

* The Recognise.py will recognise the gesture as per the trained dataset, recogniseAppend.py file will make a formation of sentences. These are acting as the stubs for this project. This project has been developed module wise and then has been integrated into a whole full fledge application. Long press 'escape' key for exiting a window.

* gestfinal2.min.mp4 is the introductory video demonstration of the complete application. icons and UI_Files directory contains all the necessary front end assets.

* Capture.py file will help in creating your own dataset and cnn_model.py file will use cnn deep neural nets to train your model and store it in the form of hadoop distributed (h5) format.

* Build the model with name "ASLModel.h5" using cnn_model.py or give any name just modify the line 38 inside "Dashboard.py"

* Install the required libraries and packages.

* Start using the application by simply double clicking "Dashboard.py"

* If you want to move the placing of the window then simply refer to the coordinates available inside cv2.moveWindow() functions.

**Prerequisites**

-python 3.6 or later

-pyqt5, tkinter

-keyboard

-winGuiAuto

-pypiwin32

-pyttsx3

-tensorflow

-keras

-scipy

-opencv

-qimage2ndarray

-pillow
