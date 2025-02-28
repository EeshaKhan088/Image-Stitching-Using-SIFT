# Image Stitching using SIFT on COIL-20 Dataset

**Description:** Image stitching with SIFT on COIL-20 dataset. Creates normal, circular, and spherical panoramas for 20 objects using 15 images each. Built with Python, OpenCV, and NumPy.

## Overview
Stitches 15 images per object from the COIL-20 dataset (20 objects, 72 angles each) into normal, circular, and spherical panoramas using SIFT for feature detection and alignment.

## Dataset
- **Source**: [COIL-20 on Kaggle](https://www.kaggle.com/datasets/cyx6666/coil20)
- **Details**: 1,440 grayscale images; 15 selected per object (0° to 56°, step 4°).

## Implementation
- **Tools**: Python, OpenCV (SIFT, processing), NumPy, Matplotlib (visualization).
- **Process**: Detects keypoints with SIFT, stitches linearly (normal), arranges circularly with rotation, and aims for spherical projection (WIP).

## Output
- 20 normal panoramas (linear).
- 20 circular panoramas (saved to `output_circular_panorama/`).
- Spherical panoramas (WIP).

## How to Run
1. Download COIL-20 from Kaggle.
2. Install: `pip install opencv-python numpy matplotlib`.
3. Update dataset path in script.
4. Run: `Image_Stitching.ipynb`.

## Results
Normal and circular panoramas show seamless multi-angle views; 

## License
MIT License - see [LICENSE](LICENSE).
