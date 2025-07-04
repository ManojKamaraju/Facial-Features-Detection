# Facial-Features-Detection
The repository contain code to detect multiple facial features 
To get mouth and nose recognition option please write the following code



---------------------------------------------------------------------------------------------------------------------------------------------------------------------
import urllib.request

# Old working links from OpenCV 3.4
nose_url = "https://raw.githubusercontent.com/opencv/opencv_contrib/3.4.0/modules/face/data/cascades/haarcascade_mcs_nose.xml"
mouth_url = "https://raw.githubusercontent.com/opencv/opencv_contrib/3.4.0/modules/face/data/cascades/haarcascade_mcs_mouth.xml"

urllib.request.urlretrieve(nose_url, "haarcascade_mcs_nose.xml")
urllib.request.urlretrieve(mouth_url, "haarcascade_mcs_mouth.xml")

print("Files downloaded successfully.")
---------------------------------------------------------------------------------------------------------------------------------------------------------------------
