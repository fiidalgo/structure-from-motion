# Structure from Motion (SfM) Project

## Overview

Structure from Motion (SfM) is a photogrammetric technique used to reconstruct a 3D structure from a series of 2D images taken from different viewpoints. This project implements the basic steps of SfM, including feature detection, matching, and 3D point cloud visualization.

## Project Features

- Feature detection and matching across multiple images.
- Estimation of camera poses using epipolar geometry.
- Triangulation of 3D points from 2D image correspondences.
- Visualization of the reconstructed 3D point cloud.

## Setup Instructions

### 1. Clone the Repository

To clone this repository using HTTPS, run the following command:

```bash
git clone https://github.com/fiidalgo/structure-from-motion.git
cd structure-from-motion
```

### 2. Create and Activate a Virtual Environment (Optional but Recommended)

Creating a virtual environment is recommended to manage dependencies:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

Install the required Python packages using `pip` and the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

Run the `sfm.ipynb` file in the IDE of your choice, or run it using Jupyter Notebook:

```bash
jupyter notebook sfm.ipynb
```

## Project Structure

* `sfm.ipynb`: The main Jupyter notebook containing the code for Structure from Motion.
* `requirements.txt`: Lists the Python dependencies needed to run the project.
* `.gitignore`: Specifies which files and directories should be ignored by Git (e.g., virtual environments, VSCode settings).
* `README.md`: Instructions for setting up and running the project (this file).

## Dependencies

This project relies on the following Python libraries:

* `requests`
* `pickle`
* `pupil_apriltags`
* `numpy`
* `glob`
* `matplotlib`
* `opencv-python`
* `plotly`

These dependencies are listed in the `requirements.txt` file and can be installed with `pip`.

## Notes

* Ensure you have Python 3.12 or higher installed.
* The notebook uses OpenCV, NumPy, and Plotly for image processing and visualization.
* The `pupil_apriltags` package is used for detecting april tags in images.

## Contact

If you have any questions or issues, please feel free to open an issue on this repository or contact me at [nicom.fidalgo@gmail.com](mailto:nicom.fidalgo@gmail.com).