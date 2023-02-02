# safety-helmet-and-no-helmet-detection-using-YOLOv5
this is my first project to study AI and try to detect safety helmets

![work2](https://user-images.githubusercontent.com/78607405/216264445-285e80de-393e-4767-9ea0-b871b5d2f731.jpg)

if you want to use it, please understand that the dataset I use comes from the internet and is for educational purposes only and not for business. I'm not responsible for copyright infringement if you use it in the future, thank you.

To improve accuracy, you need to add more data objects to each class to train to produce a better model.

if you want to detect object using file while running main.py
use or change it with following command in main.py files:
cap=cv2.VideoCapture("helmet.mp4")

if you want to detect object using facecam or realtime while running main.py 
use or change it with following command in main.py file:
cap=cv2.VideoCapture(0)cap=cv2.VideoCapture(0)

Happy Hacking :)
