# Rice Leaf Disease Detection

An end-to-end Deep Learning and Computer Vision project designed to automate the detection and classification of diseases in rice crops. This tool aims to help farmers and agricultural professionals identify infections early to optimize crop yield.

---

##  Project Overview
Rice is a staple food for a large portion of the world's population. Crop diseases significantly threaten food security. This project utilizes Data Science and Deep Learning techniques to analyze images of rice leaves and accurately classify them into healthy or specific diseased categories.

### Dataset Insights (Task 1: Data Analysis)
The current dataset includes images representing the following classes:
* **Bacterial Leaf Blight** (Avg. Resolution: 3081x897)
* **Brown Spot** (Avg. Resolution: 766x250)
* **Leaf Smut** (Avg. Resolution: 3081x897)

---

##  Project Workflow

### 1. Data Analysis & Visualization
* Explored dataset directory structure.
* Extracted image counts and original resolutions per class using `OpenCV` and `OS`.
* Visualized class distributions utilizing `Seaborn` bar plots to check for class imbalances.

### 2. Data Preprocessing & Augmentation (In Progress)
* *Upcoming:* Resizing images to a uniform shape for neural network compatibility.
* *Upcoming:* Applying augmentation techniques (rotation, flipping, zooming) to artificially expand the dataset and prevent overfitting.

### 3. Model Building & Training (Upcoming)
* Implementing Convolutional Neural Networks (CNNs) / Transfer Learning models.

---

##  Getting Started

### Prerequisites
Ensure you have Python installed (preferably via Anaconda environment) along with the following libraries:

```bash
pip install pandas matplotlib seaborn opencv-python tensorflow torch