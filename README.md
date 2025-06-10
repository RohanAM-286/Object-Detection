Object-Detection
Object detection using OpenCV to identify and track objects in images and videos. Implements various techniques like Haar cascades, deep learning models ( SSD), and contour detection for efficient recognition. Optimized for accuracy and real-time performance


YOLO (You Only Look Once)
YOLO treats object detection as a single regression problem, meaning it processes the entire image in one forward pass through a convolutional neural network. This makes it extremely fast and suitable for real-time applications like robotics and surveillance. YOLO divides an image into a grid and predicts bounding boxes and class probabilities for objects within each grid cell.


SSD (Single Shot MultiBox Detector)
SSD also performs object detection in a single pass but differs by using multiple feature maps at different scales to detect objects of various sizes. This improves accuracy for smaller objects compared to YOLO. SSD is often paired with lightweight backbone networks like MobileNet, making it a great choice for embedded systems and mobile devices


Made by Rohan A M
