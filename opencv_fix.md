# OpenCV Fix when nodes fail in comfyUI

This is for when you get the error for module `cv2.gapi.wip.draw` not loading. Activate the python enviornment and run the below.

```
pip uninstall -y opencv-python opencv-contrib-python opencv-python-headless
```
```
pip install opencv-python==4.7.0.72
```
