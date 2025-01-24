Lane Detection and Video Processing

This project implements a lane detection algorithm using computer vision techniques. It processes video files to detect and highlight lane markings on roads. The detected lanes are drawn on the video and saved as an output file. This system is particularly designed to work effectively in varying lighting conditions, including night-time scenarios.

Features

Image Enhancement: Improves image quality using advanced contrast and brightness adjustments to handle low-light or high-glare conditions.

Color Masking: Detects lane markings using optimized thresholds to accommodate various road types and lighting environments.

Edge Detection: Identifies edges dynamically, adapting to different noise levels in the video frames.

Region of Interest (ROI): Focuses on the road area where lane markings are most likely to be present, minimizing distractions from irrelevant areas.

Lane Line Detection: Uses advanced techniques to detect and accurately visualize lane lines, even with slight road curves.

Video Processing: Processes video files frame-by-frame and saves the result while maintaining real-time performance insights like frames processed per second.

Requirements

Ensure you have the following installed:

Python 3.x

OpenCV

NumPy

To install the required Python libraries, run:

pip install opencv-python numpy

Usage

Prepare Video Files:

Place the input video file in an accessible directory.

Update the video_path and output_path variables in the script with the paths to the input and output video files, respectively.

Run the Script:

Execute the script using Python:

python lane_detection.py

The program will process the video and save the output with detected lanes to the specified output path.

Keyboard Controls:

Press q during processing to quit early.

Scenarios and Corner Cases

This lane detection system has been designed to handle a variety of real-world challenges, including:

Night-time Driving: Enhanced image processing techniques ensure that lanes are visible even in low-light conditions.

Bright Sunlight or Glare: Contrast adjustments mitigate the effects of overexposure and reflections.

Curved Roads: Accurate fitting methods capture and highlight curved lane markings.

Road Noise: Advanced cleaning operations reduce false positives caused by shadows, cracks, or debris.

Dynamic Lane Widths: Adaptive techniques accommodate lanes of varying widths.

High Traffic Areas: Focuses solely on lane markings, ignoring moving vehicles and pedestrians.

Variable Lane Colors: Optimized thresholds detect both standard and non-standard lane markings effectively.

Limitations

While the system is robust, it may face challenges in the following conditions:

Roads with no visible markings or faded markings.

Extreme weather conditions such as heavy rain, fog, or snow.

Non-standard road designs or off-road scenarios.

Output

The processed video will include:

Detected lane markings highlighted in red.

Lane area filled with a translucent overlay for better visualization.

Example

Input video: vecteezy_time-lapse-driving-car-and-moving-on-road-in-bangkok-thailand_3153946.mp4
Output video: output-test7(polynomial-degree1).mp4

Contact

If you want the complete code or have any queries, please email me at:
ashwinhole18@gmail.com

