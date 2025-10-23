# Early Wheat Disease Detection

This project uses **Deep Learning** to detect wheat diseases from leaf images.  
It supports multiple classes of wheat diseases and can classify healthy plants as well.

---

## 📂 Project Structure

Diseases<br>
├── data/<br>
│ ├── train/ <br>
│ │ ├── Healthy/<br>
│ │ ├── Yellow Rust/<br>
│ │ └── ...<br>
│ ├── valid/ <br>
│ │ ├── Healthy/<br>
│ │ ├── Yellow Rust/<br>
│ │ └── ...<br>
│ └── test/ <br>
├── Diseases.py <br>
├── inference.py <br>
├── best_wheat_model.pth <br>
└── README.md<br>

---

# ⚡ Features

1. Multi-class wheat disease detection
2. Transfer learning using EfficientNet
3. Early stopping & checkpointing
4. Single-image inference with confidence scores

---

# How To use

``` bash

Install requirements.txt

pip install -r requirements.txt

``` bash
python3 Diseases.py
python3 inference.py
