## Acknowledgements
This project is adapted from the original work by [TiffinTech](https://github.com/TiffinTech/posture-corrector). The modifications include additional functionality for calibration, angle calculations, and enhanced documentation for deployment in a virtual environment.

## Prerequisites
1. [Anaconda](https://www.anaconda.com/) should be installed on your system.

## Installation Steps

**Clone the Repository**
```bash
git clone https://github.com/ctch3ng/posture-corrector.git
cd posture-corrector
```

**Create and Activate the Virtual Environment Open a terminal and run:**
```bash
conda create --name posture-corrector python=3.8 -y
conda activate posture-corrector
```

**Install Required Packages Install the necessary dependencies**
```bash
pip install opencv-python mediapipe numpy playsound ipykernel
```

**Configure IPython Kernel for Jupyter Notebook If you plan to use Jupyter Notebook:**
```bash
python -m ipykernel install --user --name=posture-corrector --display-name "Python (posture-corrector)"
```

