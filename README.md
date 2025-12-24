功能：
- 批量识别文件夹下所有图片的年龄、性别、主导情绪
- 高精度优化：MTCNN/RetinaFace检测器、人脸对齐、多次检测降噪
- 图片预处理：增强对比度，提升模糊/低光图片识别率
  
环境&库：
- Python 3.9+
- deepface==0.0.96
- opencv-python==4.9.0.80
- pandas==2.0.3
- numpy==1.26.4
- tensorflow==2.16.1
- tf-keras>=2.17.0
  
数据：
- 将需要识别的人脸图片放入 data/ 目录（支持 jpg/png/bmp 等格式）
- 识别完成后，结果会自动保存到 face_high_precision_results_update.xlsx
  
参数配置
- DETECTOR_BACKEND ：mtcnn/retinaface/opencv
- EMOTION_CONF_THRESHOLD 情绪置信度阈值
- DETECT_TIMES 单图检测次数
