# yolov5-streamlit

Deploy [YOLOv5](https://github.com/ultralytics/yolov5/releases/tag/v5.0) detection with [Streamlit](https://github.com/streamlit/streamlit)

reference： <https://xugaoxiang.com/2021/08/27/yolov5-streamlit/>

# Image Recognition Application

Visit <https://share.streamlit.io/ntecai/testing1/main/main.py>

# Installation

```
# 本地安装的话，請將opencv-python-headless改為opencv-python
pip install -r requirements.txt
```

如果有`GPU`的話，將`torch`替換成`gpu`版本可加速來檢測

# Run the application

```
streamlit run main.py
```

**Image Detection**

![streamlit yolov5 image detection](data/images/image.png)

**Video Detection**

![streamlit yolov5 video detection](data/images/video.png)
