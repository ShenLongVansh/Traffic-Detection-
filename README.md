# Hackathon Project

## Overview
This Python script allows users to interactively create polygon zones on a video frame by clicking to define the vertices of the polygon. This can be particularly useful for applications requiring predefined zones in video analysis, such as motion detection, area monitoring, or advanced video processing tasks.

## Features
- **Interactive Polygon Creation**: Click on the video frame to define the vertices of your polygon.
- **Real-time Feedback**: See the polygon being drawn in real-time as you click.
- **Customizable Video Source**: Easily change the video source by modifying the `video_path` variable.

## Prerequisites
You can configure the packages by the following command:- 
```bash
pip install -r requirements.txt
```

## Usage
1. Clone this repository to your local machine.
2. Modify the `video_path` variable in the script to point to your video file.
3. Run the script:
```bash
python Create_Zones.py
```
4. Click on the video window to start creating your polygon. The points will be connected by lines.

## Please!! 🙏

Collaboration is welcome! Let's make it better together~  
Feel free to open an issue if you have any problem or suggestion 🤗  

## License
This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements
This project makes use of the [OpenCV](https://opencv.org/) library for video processing and polygon drawing functionalities.


