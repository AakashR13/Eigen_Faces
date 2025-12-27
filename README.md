# Eigen Faces

Face recognition using Eigenfaces (Principal Component Analysis) for face identification.

![Language Distribution](https://img.shields.io/badge/Jupyter-100%25-orange) ![GitHub](https://img.shields.io/badge/GitHub-Repository-blue)

**Repository:** [AakashR13/Eigen_Faces](https://github.com/AakashR13/Eigen_Faces)

## Overview

This project implements face recognition using the Eigenfaces method, which applies Principal Component Analysis (PCA) to facial images for dimensionality reduction and face identification.

The Eigenfaces algorithm is a classic computer vision technique that uses PCA to extract the most significant features from face images, enabling efficient face recognition and classification.

## Features

- 🧮 **PCA Implementation** - Principal Component Analysis for face recognition
- 👤 **Eigenfaces Method** - Classic face recognition algorithm with full implementation
- 📊 **Multiple Dataset Support** - Works with custom datasets and Yale Face Database
- 🔬 **Jupyter Notebook Implementation** - Interactive notebooks for development and analysis
- 📈 **Complete Pipeline** - From data preprocessing to face recognition
- 📄 **Comprehensive Report** - Detailed project report with methodology and results

## Project Structure

```
Eigen_Faces/
├── Dataset/                    # Face dataset
├── YaleDataset/               # Yale face dataset
├── Eigen_face.ipynb           # Initial implementation
├── Eigen_face_Final.ipynb     # Final implementation
├── Team21_SMAI.zip            # Project archive
├── Team21_SMAI_Report.docx.pdf  # Project report
└── README.md                  # This file
```

## Requirements

- **Python 3.x**
- **Jupyter Notebook**
- **NumPy** - Numerical computations
- **Matplotlib** - Visualization
- **scikit-learn** - Machine learning utilities (optional)
- **OpenCV** - Image processing (optional)

### Installation

```bash
pip install numpy matplotlib jupyter scikit-learn opencv-python
```

## Usage

### Quick Start

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AakashR13/Eigen_Faces.git
   cd Eigen_Faces
   ```

2. **Install dependencies:**
   ```bash
   pip install numpy matplotlib jupyter scikit-learn opencv-python
   ```

3. **Open Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Load the dataset:**
   - Place face images in `Dataset/` or `YaleDataset/` folders
   - Ensure proper folder structure for training/test sets
   - Each person should have their own subfolder with multiple images

5. **Run the notebook:**
   - Open `Eigen_face_Final.ipynb` for the complete implementation (recommended)
   - Or `Eigen_face.ipynb` for the initial version
   - Execute cells sequentially to train and test the face recognition system

### Notebooks

- **`Eigen_face_Final.ipynb`** - Final, complete implementation with all features
- **`Eigen_face.ipynb`** - Initial implementation for reference

## Methodology

The Eigenfaces method works as follows:

1. **Data Preparation** - Collect and preprocess face images
2. **Mean Face Calculation** - Compute average face from training set
3. **Covariance Matrix** - Calculate covariance of face vectors
4. **Eigenvalue Decomposition** - Extract principal components (eigenfaces)
5. **Projection** - Project faces onto eigenface space
6. **Recognition** - Compare test faces with training faces using distance metrics

## Language Distribution

- **Jupyter Notebook**: 100.0% - Complete implementation in notebooks

## Documentation

- **Project Report**: See [`Team21_SMAI_Report.docx.pdf`](https://github.com/AakashR13/Eigen_Faces/blob/main/Team21_SMAI_Report.docx.pdf) for detailed methodology, implementation details, and experimental results
- **Project Archive**: `Team21_SMAI.zip` contains the complete project submission

## Datasets

- **Dataset/** - Custom face dataset
- **YaleDataset/** - Yale face database

## Implementation Details

### Key Components

1. **Data Preprocessing**
   - Image loading and normalization
   - Face image vectorization
   - Training/test set preparation

2. **PCA Computation**
   - Mean face calculation
   - Covariance matrix computation
   - Eigenvalue decomposition
   - Eigenface extraction

3. **Face Recognition**
   - Projection onto eigenface space
   - Distance metric computation (Euclidean distance)
   - Classification and matching

### Performance

The implementation demonstrates:
- Efficient dimensionality reduction using PCA
- Accurate face recognition on test datasets
- Scalable approach for multiple face classes

## References

- [Eigenfaces - Wikipedia](https://en.wikipedia.org/wiki/Eigenface)
- [Principal Component Analysis](https://en.wikipedia.org/wiki/Principal_component_analysis)
- [Face Recognition using Eigenfaces](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/pentland-eigenfaces.pdf) - Original paper by Turk and Pentland
- [Yale Face Database](http://vision.ucsd.edu/content/yale-face-database)

## License

This project is licensed under the **MIT License**.

This project was created as part of a course project (Team 21, SMAI).

See the [LICENSE](https://github.com/AakashR13/Eigen_Faces/blob/main/LICENSE) file in the repository for full license details.

## Acknowledgments

- Eigenfaces method by Turk and Pentland
- Yale Face Database
- Course: Statistical Methods in AI (SMAI)

