### Parking Spot Detection and Counting

**Project Overview**

This project implements a computer vision-based solution for detecting and counting available parking spots in a parking lot. It utilizes OpenCV to process video frames, identify parking spaces using a provided mask, and determine occupancy status based on vehicle presence. 

**Key Features**

* **Video Processing:** Efficiently handles video input for real-time or offline analysis.
* **Parking Spot Detection:** Accurately identifies parking space boundaries using a mask.
* **Occupancy Detection:** Determines if a parking spot is occupied or vacant.
* **Counting:** Provides a real-time count of available parking spaces.

**Dependencies**

* OpenCV
* NumPy (or other numerical libraries)

**Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/ZedKi7/parking-spot-detection.git
   ```
2. Install required dependencies:
   ```bash
   pip install opencv-python numpy
   ```

**Usage**

1. Prepare your video and mask files. Ensure the mask accurately delineates parking spaces.
2. Modify the code to specify input video and mask paths.
3. Run the script:
   ```bash
   python main.py
   ```

**Results**

The output will display the video with overlaid information about detected parking spaces and their occupancy status. The number of available parking spaces will also be displayed.
