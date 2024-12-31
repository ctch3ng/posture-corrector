## Acknowledgements
This project is adapted from the original work by [TiffinTech](https://github.com/TiffinTech/posture-corrector). The modifications include additional functionality for calibration, angle calculations, and enhanced documentation for deployment in a virtual environment.

## Prerequisites
[Anaconda](https://www.anaconda.com/) should be installed on your system.

## Installation Steps

**1. Create and Activate the Virtual Environment** 
- Open an Anaconda PowerShell Prompt and run:
```bash
conda create --name posture-corrector python=3.8 -y
conda activate posture-corrector
```

**2. Install Required Packages**
- Install the necessary dependencies
```bash
pip install opencv-python mediapipe numpy playsound ipykernel
```

**3. Configure IPython Kernel for Jupyter Notebook (If you plan to use Jupyter Notebook)**
```bash
python -m ipykernel install --user --name=posture-corrector --display-name "Python (posture-corrector)"
```

**4. Launch Jupyter Notebook**

- In Jupyter Notebook, create a new notebook.
- Select the kernel `Python (posture-corrector)` by going to `Kernel > Change Kernel` and choosing the correct environment.

**5. Copy and Paste the Code**
- Copy the Python code from the main script (`main.py`) and paste it into a cell in the new notebook.

**6. Run the Notebook**
- Execute the code cell by cell to see the output and interact with the posture corrector project.
