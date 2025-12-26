Face Attribute Recognition (Age/Gender/Emotion) for Batch Image Processing

1.Core Features
- Batch recognition: Automatically detect and recognize age, gender, and dominant emotion for all face images in a specified folder.
- Adaptive preprocessing: Improve recognition accuracy for low-quality images (blurred/low-light) via targeted image enhancement.
- face images support formats: jpg, png, bmp, etc.
  
2.Experimental Environment
- Python 3.9+
- deepface==0.0.96
- opencv-python==4.9.0.80
- pandas==2.0.3
- numpy==1.26.4
- tensorflow==2.16.1
- tf-keras>=2.17.0
  
 3.Parameter Configuration
- DETECTOR_BACKEND ：mtcnn/retinaface/opencv
- EMOTION_CONF_THRESHOLD 
- DETECT_TIMES
