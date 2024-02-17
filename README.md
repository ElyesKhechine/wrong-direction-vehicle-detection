# Wrong-Way Driver Detection System for Enhanced Traffic Safety

### EPT

**Technologies:** Python, NumPy, OpenCV, Matplotlib Pyplot, SciPy, Hough Transform, Lucas-Kenad Method, Gaussian Smoothing

## Introduction

This project delves into the development of a sophisticated algorithm for detecting wrong-direction driving vehicles. Leveraging a combination of Python programming and advanced computer vision techniques, our goal was to accurately identify vehicles traveling in the wrong direction on roads, thereby enhancing road safety measures.

## Project Scope

This project was undertaken as a semester project by myself and my colleague to validate our understanding of the "Image Processing" subject in our Master of Research program at EPT. Spanning from December 10, 2023, to February 1, 2024, the project encapsulated our efforts to apply theoretical knowledge into practical solutions.

## Technical Details

- **Frame Selection and Resizing**: Empirically selected frames were strategically resized to optimize computation time during Hough Transform calculation while ensuring the effectiveness of the optical flow method.
- **Smoothing and Edge Detection**: Applied smoothing techniques and edge detection algorithms to eliminate noise and accurately identify vehicle edges and road dividers.
- **Thresholding and Detection**: Implemented thresholding techniques to filter weak edges and accurately detect road dividers using customized accumulator strategies.
- **Gaussian Smoothing Optimization**: Explored the impact of Gaussian smoothing on Hough Transform performance and refined strategies to reduce false positives in noise-rich environments.
- **Divider Line Detection**: Developed an algorithm utilizing the Hough Transform's accumulator array to detect traffic divider lines with high precision.
- **Optical Flow Estimation**: Utilized the Lucas-Kanade method to estimate optical flow for vehicle direction determination, enhancing accuracy in varied scenarios.
- **Direction Analysis**: Analyzed vehicle directions using UV magnitude thresholds, distinguishing between correct and wrong direction travel with high accuracy.

## Project Presentation

For a comprehensive overview of the project, methodologies, and outcomes, please refer to the [Project Presentation](https://www.canva.com/design/DAF7fqI8_3s/MhgKHvwGRLyusVwnfhe42Q/view?utm_content=DAF7fqI8_3s&utm_campaign=designshare&utm_medium=link&utm_source=editor).

## Getting Started

### Installation

1. Clone the project repository to your local machine.
2. Ensure compatibility and proper setup of required software dependencies, including Python, NumPy, OpenCV, and SciPy.

### Usage

1. Run the "test-Final-Project" script to execute the vehicle detection algorithm.
2. Monitor the output for accurate identification of correct and wrong direction driving vehicles.
3. Analyze results and fine-tune parameters as necessary for specific scenarios.

## Contributing

Contributions aimed at enhancing project functionalities and addressing emerging challenges are encouraged.

## License

This project is licensed under the [GPL-3.0 License](LICENSE).

## Contacts

For inquiries or collaboration opportunities, please contact:

- Elyes Khechine: elyeskhechine@gmail.com
- Amer Djobbi: amer.djobbi@insat.ucar.tn
