# Using Anomaly Detection
Using `Anomaly Detection.ipynb` you can provide a path to some arrays that contain the values detected by a head posture detection algorithm. If you don't have those available, you can use the `Write Videos.ipynb` notebook for RealHePoNet to extract these values from a video.
You can then visualize how the head moved over some time, change the frame rate (default is 30), and compare it with how the anomaly detection algorithm performed. 

### Requirements

    pyod==0.9.3
    suod==0.0.7
    matplotlib==3.4.3
    numpy==1.21.2
    pandas==1.3.2
