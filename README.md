## 🎓 Take Home Assignment 1

## 🧠 Tasks

### ✅ Task 1 – Reduce Intensity Levels  
Reduce the number of intensity levels in an image from 256 to any specified power of 2 (e.g., 2, 4, 8, 16). This is done by applying quantization to each channel of a color image.

### ✅ Task 2 – Spatial Averaging  
Perform spatial averaging on the image using different kernel sizes:
- 3×3
- 10×10
- 20×20

### ✅ Task 3 – Rotate Image  
Rotate the image by:
- 45 degrees
- 90 degrees

### ✅ Task 4 – Block Averaging for Resolution Reduction  
Reduce the spatial resolution of the image by applying block-wise averaging for:
- 3×3 blocks
- 5×5 blocks
- 7×7 blocks  
Each block is replaced with the average color of its pixels.

---

## 📁 Folder Structure

```
TAKE HOME ASSIGNMENT 1/
├── images/
│   └── input.jpg
│
├── outputs/
│   ├── task1/
│   │   └── reduced_4_levels.jpg
│   │
│   ├── task2/
│   │   ├── blur_3x3.jpg
│   │   ├── blur_10x10.jpg
│   │   └── blur_20x20.jpg
│   │
│   ├── task3/
│   │   ├── rotated_45.jpg
│   │   └── rotated_90.jpg
│   │
│   └── task4/
│       └── [output files from Task 4 will be saved here]
│
├── README.md
│
├── Task_1.ipynb
├── Task_2.ipynb
├── Task_3.ipynb
└── Task_4.ipynb
```

---

## 🧪 Requirements

Install dependencies using:

```bash
pip install opencv-python matplotlib numpy
```

---

## ▶️ How to Run

1. Place your input image as `images/input.png`.
2. Open `Assignment1.ipynb` in Jupyter Notebook or VS Code.
3. Run each cell to view the results.
4. All outputs will be saved under the `outputs/` folder.

---

## 🔗 GitHub Repo

[https://github.com/HirunaD/EC7212-Take-Home-Assignment-1](https://github.com/HirunaD/EC7212-Take-Home-Assignment-1)

---

## 👤 Student Info

- **Name:** Hiruna De Silva  
- **Course:** EC7212 – Computer Vision and Image Processing  
- **Semester:** 7  

---

## 📷 Sample Output

You can view visual outputs under the `outputs/` folders once you run the notebook.