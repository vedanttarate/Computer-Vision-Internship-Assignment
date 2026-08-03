## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/PPE-Detection.git
cd PPE-Detection
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

or install the required libraries manually:

```bash
pip install torch torchvision opencv-python matplotlib pandas numpy pyyaml seaborn tqdm
```

---

## Running the Project

This project is implemented in **Google Colab** using a Jupyter Notebook.

### Step 1: Open the Notebook

Open the notebook file:

```
PPE_Detection.ipynb
```

in Google Colab.

### Step 2: Enable GPU

Go to:

```
Runtime → Change runtime type → GPU (Tesla T4)
```

### Step 3: Mount Google Drive

Run the following cell:

```python
from google.colab import drive
drive.mount('/content/drive')
```

### Step 4: Run All Cells

Execute the notebook cells in the following order:

1. Environment Setup
2. Clone YOLOv5 Repository
3. Install Dependencies
4. Load Dataset
5. Dataset Validation
6. Exploratory Data Analysis (EDA)
7. Model Training (YOLOv5s / YOLOv5m)
8. Model Evaluation
9. Image Inference
10. Video Inference
11. Error Analysis

---

## Output

The project generates the following outputs:

- Trained model weights (`best.pt` and `last.pt`)
- Training logs
- Evaluation metrics
- Predicted images
- Predicted videos
- Error analysis results

---

## Requirements

- Python 3.10+
- Google Colab
- NVIDIA GPU (Tesla T4 recommended)
- PyTorch
- OpenCV
- YOLOv5
- NumPy
- Pandas
- Matplotlib
